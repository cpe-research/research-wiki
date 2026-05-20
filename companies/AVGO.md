---
type: company
ticker: AVGO
name: Broadcom Inc.
sector: Technology
industry: Semiconductors
country: US
website: https://www.broadcom.com
cik: "0001730168"
updated: "2026-05-13"
sources:
  - info.json
  - peers.json
  - value_chain.md
  - competitive_position.md
edges:
  - { type: competes_with, target: ADI, confidence: 0.6 }
  - { type: competes_with, target: AMD, confidence: 0.7 }
  - { type: competes_with, target: ASML, confidence: 0.5 }
  - { type: competes_with, target: META, confidence: 0.4 }
  - { type: competes_with, target: MU, confidence: 0.5 }
  - { type: competes_with, target: MRVL, confidence: 0.85 }
  - { type: competes_with, target: NVDA, confidence: 0.9 }
  - { type: competes_with, target: QCOM, confidence: 0.6 }
  - { type: competes_with, target: TSM, confidence: 0.4 }
  - { type: competes_with, target: INTC, confidence: 0.7 }
  - { type: supplied_by, target: TSMC, confidence: 0.95 }
  - { type: supplied_by, target: ASE, confidence: 0.8 }
  - { type: supplied_by, target: SPIL, confidence: 0.7 }
  - { type: supplied_by, target: UMC, confidence: 0.5 }
  - { type: supplied_by, target: GlobalFoundries, confidence: 0.5 }
  - { type: supplied_by, target: Amkor, confidence: 0.6 }
  - { type: supplied_by, target: Foxconn, confidence: 0.5 }
  - { type: sells_to, target: Google, confidence: 0.92 }
  - { type: sells_to, target: Meta, confidence: 0.88 }
  - { type: sells_to, target: OpenAI, confidence: 0.8 }
  - { type: sells_to, target: Anthropic, confidence: 0.75 }
  - { type: sells_to, target: Microsoft, confidence: 0.7 }
---

# Broadcom Inc. (AVGO)

## Overview

Broadcom is a global technology company that designs, develops, and supplies semiconductor and infrastructure software solutions. Headquartered in San Jose, California with approximately 37,000 employees.

The company operates across three strategic areas: AI Silicon/XPU (custom accelerators for hyperscalers), Networking (switching, routing, PHY), and Infrastructure Software (VMware, acquired November 2023).

## Segments

- **AI Silicon / XPU**: Custom AI accelerators (ASICs) for hyperscale cloud providers. Q1 FY2026 AI revenue was $8.4B, growing 106% YoY. Management has 6 custom XPU customers including Google, Anthropic, Meta, and OpenAI.
- **Networking**: Switching ASICs (Memory: Memory: Memory: Memory: Tomahawk, Jericho), SerDes, PHY, and optical connectivity for data center fabrics.
- **Infrastructure Software / VMware**: VMware Cloud Foundation, security (Symantec), mainframe (CA Technologies). Broadest customer base of the three segments. Price hikes of up to 45% reported post-acquisition.

## Competitors

| Company | Ticker | Overlap |
|---------|--------|---------|
| Marvell Technology | MRVL | Direct competitor in custom AI ASICs (#2 player) |
| NVIDIA | NVDA | GPU vs custom ASIC competition in AI training/inference |
| Advanced Micro Devices | AMD | AI accelerators, networking |
| Intel | INTC | Networking ASICs, infrastructure |
| Analog Devices | ADI | Semiconductors |
| Qualcomm | QCOM | Semiconductors, connectivity |
| ASML | ASML | Semiconductor equipment supply chain |
| Micron Technology | MU | Memory/semiconductors |
| Meta Platforms | META | Customer and in-house silicon competitor |
| TSMC | TSM | Foundry supplier (listed as peer by FMP) |

## Key Suppliers

| Supplier | Role | Confidence | Notes |
|----------|------|------------|-------|
| **TSMC** | Wafer fabrication | 0.95 | ~95% of wafers (FY2025 10-K). Primary bottleneck in 2026. |
| **ASE** | Test, assembly, packaging | 0.80 | Singapore, China, Taiwan |
| **SPIL** | Test, assembly, packaging | 0.70 | Taiwan |
| UMC | Secondary foundry | 0.50 | Singapore, Taiwan |
| GlobalFoundries | Secondary foundry | 0.50 | Singapore, Germany |
| Amkor | Assembly & packaging | 0.60 | Korea, Philippines, Taiwan, China |
| Foxconn | Manufacturing partner | 0.50 | |

No long-term supplier agreements. All procurement on a per-order basis (per 10-K).

## Key Customers

| Customer | Relationship | Confidence | Notes |
|----------|-------------|------------|-------|
| **Google** | Custom AI accelerator (XPU) | 0.92 | Named XPU customer |
| **Meta** | Custom AI accelerator (XPU) | 0.88 | Named XPU customer |
| **OpenAI** | Custom AI accelerator (XPU) | 0.80 | Named XPU customer |
| **Anthropic** | Custom AI accelerator (XPU) | 0.75 | Named XPU customer |
| **Microsoft** | Infrastructure / cloud | 0.70 | Enterprise IT customer |
| Enterprise IT | VMware Cloud Foundation | 0.85 | NEC, Lenovo, Dell, HP, Cisco |

Customer concentration risk: AI revenue ($8.4B Q1 FY2026) comes primarily from a small number of hyperscale customers. This is a growing share of total semiconductor revenue.

## Key Metrics

| Metric | Value | Source |
|--------|-------|--------|
| Revenue (FY2025) | $63.9B | income.json |
| AI Revenue (Q1 FY2026) | $8.4B | company_ir.md |
| AI Revenue Growth | 106% YoY | company_ir.md |
| Q2 FY2026 AI Guidance | $10.7B | company_ir.md |
| Employees | ~37,000 | info.json |
| Revenue CAGR (5Y) | 21.7% | income.json |
| CIK | 0001730168 | info.json |

## Open Questions

- What is the real customer concentration risk if one hyperscaler pauses or delays XPU orders?
- How does TSMC advanced packaging capacity constrain AVGO's AI revenue ramp?
- Will hyperscalers develop in-house ASIC design capability (customer-owned tooling) that displaces Broadcom?
- What is the organic growth rate excluding VMware acquisition effects?
