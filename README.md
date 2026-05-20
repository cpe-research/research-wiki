# CPE Knowledge

Cross-ticker knowledge base for [CPE Research](https://github.com/cpe-research/research-agent). Files are the source of truth; there is no primary database. Any agent can clone this repo, open `index.md`, and navigate to whatever it needs.

Inspired by [Karpathy's LLM Wiki pattern](https://x.com/karpathy/status/2040572272944324650): explicit, yours, file over app, bring your own AI.

## How it works

Every page is a Markdown file with YAML frontmatter that carries structured metadata (type, ticker, edges, sources, confidence scores). The file system is the index; backlinks and cross-references make the graph navigable without a query engine.

A derived SQLite index in the research-agent repo can be rebuilt from these files at any time via `make knowledge-rebuild`. If the DB gets corrupted, delete it and rebuild. The files are always canonical.

## Directory layout

```
index.md              Catalog of all pages, entry point for agents
companies/            One file per covered company (AVGO.md, TSMC.md, ...)
suppliers/            Non-company supplier entities
customers/            Non-company customer entities
themes/               Cross-ticker synthesis (e.g. ai-infrastructure.md)
bottlenecks/          Capacity constraints and supply bottlenecks
supply-chains/        End-to-end supply chain maps
questions/
  open.md             Research questions waiting for evidence
  resolved.md         Closed questions with answers and sources
```

## Commit conventions

Every commit message follows one of these formats:

- `[TICKER run:YYYY-MM-DD] summary` — automated update from a research pipeline run
- `[lint] summary` — automated lint pass (stale edges, contradictions, orphans)
- `[manual] summary` — human edit

Examples:

```
[AVGO run:2026-05-13] Initial scaffold with AVGO seed data
[TSMC run:2026-05-14] Added capacity constraint edges from Q1 earnings
[lint] Marked 3 stale edges on INTC
[manual] Corrected AVGO customer list from 10-K review
```

## YAML frontmatter

Every page carries structured metadata between `---` markers:

```yaml
---
type: company
ticker: AVGO
name: Broadcom Inc.
sector: Technology
industry: Semiconductors
updated: "2026-05-13"
sources:
  - info.json
  - peers.json
  - value_chain.md
edges:
  - { type: competes_with, target: NVDA, confidence: 0.9 }
  - { type: supplied_by, target: TSMC, confidence: 0.95 }
  - { type: sells_to, target: Google, confidence: 0.92 }
---
```

The `edges` list is the machine-readable graph. Agents and the `rebuild_index()` function in research-agent parse this to populate the SQLite query index.

## For agents

1. Clone this repo (or read it via GitHub API).
2. Start at `index.md`.
3. Follow links to the pages relevant to your task.
4. After producing new research, write updated pages back and commit with the appropriate convention.
