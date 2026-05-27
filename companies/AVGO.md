---
type: company
ticker: AVGO
name: AVGO
updated: "2026-05-27"
sources:
  - info.json
  - value_chain.md
  - segments.json
  - insider.json
  - holders.json
  - transcript_competitors.json
---

# AVGO (AVGO)

## Competitors

- [AMD](AMD.md) (AMD)
- [META](META.md) (META)
- [NVDA](NVDA.md) (NVDA)
- [QRVO](QRVO.md) (QRVO)
- [TSM](TSM.md) (TSM)

## Key Insiders

- Bryant Diane M (director)
- DELLY GAYLA J (director)
- Hao Kenneth (director)
- Kawwas Charlie B (officer: President, SSG)
- Low Check Kian (director)
- PAGE JUSTINE (director)
- SAMUELI HENRY (director)
- TAN HOCK E (director, officer: President and CEO)
- Velaga S. Ram (officer: President, ISG)
- You Harry L. (director)

## Top Institutional Holders

- ADAPT Investment Managers SA
- ALKEON CAPITAL MANAGEMENT LLC
- BERKOWITZ CAPITAL & CO  LLC
- BNP PARIBAS FINANCIAL MARKETS
- BOOTHBAY FUND MANAGEMENT, LLC
- COATUE MANAGEMENT LLC
- CTC LLC
- Capital Advisory Group Advisory Services, LLC
- DAI ICHI MUTUAL LIFE INSURANCE CO
- DRUKER NEIL

---

> **⚠️ DRAFT — this report did not pass the citation audit.** Some claims may lack source verification. Treat as preliminary research.

# Broadcom Inc. (AVGO) — Research Report

**Report Date:** 2026-05-27
**Data As Of:** 2026-05-26 (price), FY2025 (ended Nov 2, 2025) for annual financials, Q1 FY2026 (ended Feb 2, 2026) for most recent quarter
**Ticker:** AVGO | NASDAQ | Technology | Semiconductors
**Price:** $422.01 [info.json: price]
**ADV:** $10,036MM [info.json: averageVolume (23,781,641) × price ($422.01)]
**Market Cap:** $1,998.1B [info.json: marketCap]
**Net Debt:** $49.0B (2.5% of mkt cap) [balance.json: totalDebt ($65,136M) − cashAndShortTermInvestments ($16,178M)]
**Net Cash:** −$49.0B (−2.5% of mkt cap) [balance.json: cashAndShortTermInvestments ($16,178M) − totalDebt ($65,136M)]
**Enterprise Value:** $2,047.0B [Computed: $1,998.1B mkt cap + $65.1B debt − $16.2B cash]
**Short Interest:** 1.10% of float (51,011,972 shares short / 4,642,774,789 float) [short_interest.md + shares_float.json]

---

## 1. Business Overview

<!-- IC Question: What does this company do, how is it organized, and how large is each piece? What would change the answer: major divestiture, acquisition, segment reclassification, revenue mix shift. -->

Broadcom Inc. is a global technology company that designs, develops, and supplies semiconductor and infrastructure software solutions. Headquartered in Palo Alto, CA, with 37,000 full-time employees [info.json: fullTimeEmployees]. CEO: Hock E. Tan [info.json: ceo]. Listed on NASDAQ Global Select (CIK 0001730168) since August 6, 2009 [info.json: ipoDate].

### Reportable Segments

Broadcom reports **two** segments: **Semiconductor Solutions** and **Infrastructure Software** [segment_financials.md: SEC 10-Q avgo-20260201.htm] [claim_verification.json: C069, Verified]. Note: the FMP info.json description references four legacy segments (Wired Infrastructure, Wireless Communications, Enterprise Storage, Industrial & Other); this is outdated post-VMware restructuring.

| Segment | FY2025 Revenue | % of FY2025 | Q1 FY2026 Revenue | Q1 FY2026 % | Q1 YoY Growth |
|---------|---------------|-------------|-------------------|-------------|---------------|
| Semiconductor Solutions | ~$36.9B | ~57.7% | $12.5B | 64.7% | +52% |
| Infrastructure Software | ~$27.0B | ~42.3% | $6.8B | 35.2% | +1% |
| **Total** | **$63,887M** | **100%** | **$19,311M** | **100%** | **+29.5%** |

Sources: FY2025 total revenue from [income.json: revenue]. FY2025 segment split from Bullfincher aggregator [business_overview.md] [Single-Source caveat: FMP segments.json returned 404; Bullfincher is the only source for the annual percentage]. Q1 FY2026 segment data from [transcript_segments.json: Kirsten Spears]. Q1 FY2026 total from [earnings.json: revenueActual, 2026-03-04]. Percentages computed: $12.5B/$19.311B = 64.7%; $6.8B/$19.311B = 35.2%.

### Semiconductor Solutions ($12.5B, 64.7% of Q1 revenue)

Management discloses two sub-categories on earnings calls (not in SEC filings):

| Sub-Category | Q1 FY2026 Revenue | % of Semi | YoY Growth |
|--------------|-------------------|-----------|------------|
| AI Semiconductors | $8.4B | 67.2% | +106% |
| Non-AI Semiconductors | $4.1B | 32.8% | flat (0%) |

AI semiconductor sub-components (management commentary): Custom AI Accelerators (XPUs) ~$5.6B (~2/3 of AI revenue, +140% YoY) [Inference: Hock Tan stated AI networking = "1/3 of total AI revenue," implying XPU = remaining 2/3] [Sources: transcript_segments.json]. AI Networking (switches, DSPs, SerDes, optical) ~$2.8B (~1/3 of AI revenue, +60% YoY) [transcript_segments.json: Hock Tan] [claim_verification.json: C007, Single-Source].

Key products: (1) Custom AI XPUs including Google TPU (Ironwood, 7th gen) and Meta MTIA; (2) Tomahawk 6 Ethernet switching ASICs (100 Tbps, 200G SerDes); (3) Optical DSPs at 1.6 Tbps; (4) High-Speed SerDes (200G shipping, 400G in development); (5) Jericho routing ASICs; (6) Broadband SoCs; (7) Wireless SoCs (Apple customer [claim_verification.json: C092, Corroborated]); (8) Server storage controllers [transcript_segments.json: Hock Tan].

### Infrastructure Software ($6.8B, 35.2% of Q1 revenue)

Key products: (1) VMware Cloud Foundation (VCF) — VMware revenue grew 13% YoY in Q1 FY2026, TCV >$9.2B, ARR growth 19% YoY [transcript_segments.json: Hock Tan]; (2) CA Technologies mainframe software (acquired 2018, $18.9B); (3) Symantec Enterprise Security (acquired 2019, $10.7B); (4) Brocade SAN/Fiber Channel [business_overview.md].

Segment-level Q1 FY2026 margins (non-GAAP): Semiconductor gross margin ~68%, operating margin 60%. Software gross margin 93%, operating margin 78% [transcript_segments.json: Kirsten Spears].

### Revenue Mix: Narrative vs. Reality

AI semiconductor revenue ($8.4B, 43.5% of Q1 total) is the largest single revenue stream, growing 106% YoY. Q2 FY2026 AI guidance is $10.7B (+140% YoY), rising to ~48.6% of guided $22B total [transcript_segments.json: Hock Tan]. This is disclosed, quantified, and verified revenue — not pre-revenue [claim_verification.json: C041, Verified].

Infrastructure Software ($6.8B) generates 93% gross margins and 78% operating margins — the highest-margin segment. At 93% gross margin, Software contributes ~$6.3B gross profit vs. Semi's ~$8.5B at 68% [Inference: margin × revenue computation] [Sources: transcript_segments.json].

Non-AI Semiconductors ($4.1B, 21.2%) are flat and declining as a share of total.

### Major Customers

6 named custom AI XPU customers: Google (TPU Ironwood), Anthropic (1 GW in 2026, 3+ GW in 2027), Meta (MTIA), OpenAI (first-gen XPU, volume 2027), and 2 unnamed [transcript_segments.json: Hock Tan]. $10B Ironwood TPU rack order from Anthropic received Q3 FY2025 [claim_verification.json: C003, Corroborated].

Top 5 end customers ~40% of FY2025 and FY2024 revenue through all channels [EDGAR: 10-K FY2025]. Per-customer revenue is not disclosed in SEC filings [Data gap]. 48% of revenue via distributors [EDGAR: 10-K FY2025].

### Brief History

Avago Technologies (HP spinoff) acquired Broadcom Corporation ($37B, 2016), then CA Technologies ($18.9B, 2018), Symantec enterprise ($10.7B, 2019), and VMware ($61B, closed Nov 22, 2023) [business_overview.md; income.json]. FY2024 revenue jumped 44.0% ($35.8B → $51.6B), substantially driven by VMware consolidation [Inference: goodwill increased $54.2B from FY2023 to FY2024, confirming acquisition impact] [Sources: balance.json, income.json]. 10-for-1 stock split completed July 2024.

---

## 2. Competitive Position

<!-- IC Question: For each product, who competes and what are relative strengths? What would change: loss of a top customer, entry of well-capitalized competitor, customer building in-house, technology disruption. Base rate: custom AI ASIC market has had zero successful new entrants at scale. -->

### Custom AI XPUs

**Broadcom vs. Marvell Technology (MRVL):** AVGO is #1 by revenue in custom AI ASICs. AVGO's single-quarter AI revenue ($8.4B) exceeds Marvell's total full-year revenue ($8.2B, FY2026 ended Jan 2026) [income.json; ecosystem_signals.md: MRVL FY2026, Verified C011]. Marvell's custom ASIC revenue is ~$1.5B annualized [ecosystem_signals.md: Single-Source C016]. Third-party market share estimates for AVGO: ~70% [ecosystem_signals.md: Gotrade, Single-Source C039]; Yahoo Finance separately projects 60% for 2027 [claim_verification.json: C039 cross-reference]. AVGO does not disclose custom AI ASIC market share in SEC filings [Data gap].

Marvell competitive signals: (1) reportedly secured portion of next-gen Google TPU work [ecosystem_signals.md: Corroborated C015, 3 independent sources]; (2) NVIDIA invested $2B in Marvell (March 2026) for NVLink-compatible interconnect [ecosystem_signals.md: Verified C017]; (3) acquired Celestial AI ($3.25B), XConn ($540M), Polariton in optical interconnect [Verified C018, C019]; (4) 20+ custom design wins at record level [Corroborated C020].

**Broadcom vs. NVIDIA (GPU co-opetition):** NVIDIA's data center revenue was $75.2B in Q1 FY2027 (+92% YoY) [ecosystem_signals.md: Contradicted C022 — $75.2B not $75.3B as cited in some sources]. GPUs and custom ASICs compete for the same hyperscaler compute budget but serve different optimization points. Vera Rubin next-gen promises "up to 10x more performance per watt" for specific inference workloads vs. Blackwell [Verified C031, with "up to" qualifier].

**Customer-owned tooling (COT) risk:** Hyperscalers (Google, Amazon Trainium, Microsoft Maia) have internal silicon teams. CEO Tan: "We will not see competition in COT for many years to come" [transcript.json: Hock Tan, Q&A]. This is management's assessment, not independently verified.

### Networking ASICs

Tomahawk 6 at 100 Tbps with 200G SerDes — CEO called Broadcom "first-to-market" [transcript.json: Hock Tan]. Optical DSPs: "We are again the only player out there doing DSP at 1.6 terabit" [transcript_segments.json: Hock Tan]. Marvell competes in switching and optical DSPs, bolstered by the $2B NVIDIA investment for NVLink-compatible interconnect. Quantified market share data for networking ASICs is not available [Data gap].

### Infrastructure Software (VMware)

VMware Cloud Foundation occupies a dominant position in enterprise server virtualization. VMware TCV >$9.2B in Q1 FY2026, ARR growth 19% YoY [transcript_segments.json: Hock Tan]. Alternatives include Nutanix, Red Hat OpenShift, and public cloud native. Post-acquisition pricing changes (reported increases up to 45%) have created customer dissatisfaction [claim_verification.json: C079]. No quantified churn data is available [Data gap].

### Competition Evolution (3-5 Years)

2021-2023: Broadcom competed broadly across networking, broadband, wireless. Custom ASIC concentrated on Google TPU. 2023-2024: AI demand explosion + $61B VMware acquisition. Competitive field narrowed to AI dynamics. 2025-2026: Market becoming more oligopolistic at the custom ASIC layer. MRVL closing the gap through M&A and NVIDIA partnership, but starting from 7.8x smaller revenue base. Barriers to entry rising (capital intensity, TSMC access, multi-year customer relationships).

---

## 3. Supply/Demand Balance

<!-- IC Question: Is industry supply sufficient to meet demand at current prices, and when does that change? What would change: major capacity announcement, demand shock, policy change. Base rate: semiconductor supply/demand imbalances in advanced nodes have historically persisted 18-36 months. -->

### Demand

**Backlog:** Total consolidated backlog $162B (Q4 FY2025), AI-specific backlog $73B [backlog_breakdown.md: Verified C001]. Total backlog = 2.5x FY2025 revenue ($162B/$63.9B). AI backlog = ~2.2 years at Q1 FY2026 run rate ($73B/$33.6B annualized) [Computed].

**AI revenue trajectory:** ~$4.1B (Q1 FY2025 implied) → $8.4B (Q1 FY2026, +106% YoY) → $10.7B guided (Q2 FY2026, +140% YoY) [transcript_segments.json: Hock Tan; earnings.json]. AI as % of total: ~27% → 43.5% → ~48.6%.

**Demand durability:** Hyperscaler AI capex commitments: Google $175-185B, Meta $60-65B, Microsoft $80B+, Amazon $100B+ [customer_capex.md]. TSMC CEO C.C. Wei: demand "significantly outpaces supply" with "sold-out environment" through 2026 [ecosystem_signals.md]. CEO Tan targets "$100 billion in 2027" from AI chips [transcript.json: Hock Tan]. ~98% of Q1 FY2026 YoY revenue growth was from AI semiconductors [Inference: Q1 FY2025 total $14,916M; growth of ~$4.4B YoY almost entirely from AI semi growth of ~$4.3B] [Sources: earnings.json, transcript.json].

### Supply Constraints

1. **Leading-edge wafers (TSMC 3nm/5nm):** Sold out. Advanced chips (≤7nm) = ~74% of TSMC wafer revenue [ecosystem_signals.md].
2. **CoWoS advanced packaging:** TSMC only provider at scale; growing >80% CAGR 2026-2028 [Corroborated C036]. NVDA estimated ~50% of CoWoS capacity [Unverifiable C043].
3. **HBM:** Industry-wide constraint from SK Hynix, Samsung, Micron.
4. **Substrates (T-glass):** CEO Tan: "We were early in being able to lock up T-glass" [transcript.json].

AVGO has "fully secured capacity of these components for '26 through '28" [transcript.json: Hock Tan]. Kawwas confirmed: "we're probably the first one to secure that up to '28 or beyond" [transcript.json: Charlie Kawwas].

### Supply Addition Timeline

- TSMC Tainan 3nm fab: volume H1 2027 [ecosystem_signals.md]
- TSMC Arizona 2nd fab (3nm): production H2 2027 [Verified C037]
- TSMC Japan 2nd fab (3nm): production 2028
- TSMC Arizona packaging fab: permitting stage
- Total TSMC US investment: $165B [Verified C037]

### Synthesis

Demand exceeds supply in 2026. TSMC is "sold out" and CEO Tan described capacity as "choked." The supply constraint is structural in 2026 and begins easing in 2027 as new fabs come online. Pricing has been stable: CEO Tan rejected margin dilution concerns from rack-level shipments, stating "you must be a bit hallucinating" [transcript.json: Hock Tan, Q&A]. AVGO, NVDA, and MRVL all compete for the same TSMC capacity pool.

---

## 4. Value Chain

<!-- IC Question: Where is value captured, and is it migrating toward or away from this company? What would change: vertical integration by customer/supplier, margin compression, technology disintermediation. Base rate: semiconductor value chain positions rarely shift materially within 5 years absent a major architecture transition. -->

### Value Chain Map

**Semiconductor:** Raw materials → TSMC foundry (primary) → CoWoS packaging (TSMC) → **AVGO: chip design + IP** → OSAT assembly/test (ASE, SPIL, Amkor, Foxconn) → Distribution (48% distributors, 52% direct) → Hyperscaler customers → AI data centers [EDGAR: 10-K FY2025; transcript.json]. AVGO is fabless for standard CMOS; maintains internal III-V fabrication (FBAR filters, GaAs/InP lasers) in the U.S. and Singapore [EDGAR: 10-K FY2025].

**Software:** Open-source ecosystem → **AVGO: software development + IP** (VMware, CA, Symantec) → Distribution → Enterprise customers [transcript_segments.json].

### Upstream Dependencies

TSMC is the primary foundry: "the majority of front-end wafer manufacturing" [EDGAR: 10-K FY2025]. The specific "~95% of wafers" figure widely cited is not in the 10-K [Unverifiable C038]. No long-term supply contracts per 10-K ("generally on a purchase order basis") [EDGAR: 10-K FY2025], but management describes multiyear capacity commitments for AI components [transcript.json; claim_verification.json: C096, Verified — Broadcom VP confirmed "long-term agreements with suppliers to secure capacity commitments for as long as three to four years"]. [Inference: general purchases remain per-order, while strategic AI components have specific capacity agreements] [Sources: 10-K FY2025, transcript.json, claim_verification.json C096].

### Margin Capture Across the Chain

| Stage | Entity | Gross Margin | Operating Margin |
|-------|--------|-------------|-----------------|
| Foundry | TSMC | 66.2% | 58.1% |
| Chip design (semi) | AVGO | 68% (non-GAAP) | 60% (non-GAAP) |
| Software | AVGO | 93% | 78% |
| GPU design | NVIDIA | 75.0% (GAAP) | — |
| OSAT | ASE/SPIL | ~20-25% | ~8-12% |

[ecosystem_signals.md: TSMC Q1 2026, Verified C034; transcript_segments.json: Kirsten Spears; Inference for OSAT margins from general industry knowledge] [Sources: ecosystem_signals.md, transcript_segments.json]

AVGO's GAAP operating margin (39.9% FY2025) is depressed by $8.8B D&A, primarily amortization of acquired intangibles [income.json: depreciationAndAmortization]. Capex-to-revenue: 0.98% ($623M/$63.9B FY2025) [cashflow.json], consistent with fabless model.

### Integration Direction

**Forward:** AVGO has moved from chips to rack-level systems (Anthropic $10B rack order [Corroborated C003]) and into the software abstraction layer (VMware acquisition). CEO Tan positioned VCF as "the permanent abstraction layer between AI software and physical chips" [transcript.json].

**Competitors integrating toward AVGO:** Marvell secured portion of Google TPU work [Corroborated C015]. NVIDIA invested $2B in Marvell [Verified C017]. Hyperscalers have internal silicon teams, though CEO Tan asserts no COT competition "for many years."

### Inventory Signals

Inventory increased from $2.27B (FY2025) to $3.0B (Q1 FY2026), days on hand expanded from 40 to 68 days. CFO Spears attributed this to "anticipation of accelerating AI semiconductor growth" [transcript_segments.json: Kirsten Spears]. Deferred revenue totaled $13.0B (FY2025-end: $9.5B current + $3.5B non-current [balance.json]), primarily VMware subscription prepayments.

---

## 5. Capital Structure

<!-- IC Question: How does the company raise money to spend on its business? What would change: major debt issuance or repayment, M&A financing, credit rating change, new equity issuance. -->

### Equity Composition

Single class of common stock ($0.001 par value) [insider.json: securityName]. No preferred equity outstanding — Series A Mandatory Convertible Preferred ($3.0B issued Sep 2019) fully converted to common stock September 30, 2022 [convertible_search.json; balance.json: preferredStock $0, FY2025]. Shares outstanding: 4,734,670,000. Float: 4,642,774,789 (98.1% free float) [shares_float.json].

### Market Cap

$1,998.1B at $422.01/share [quote.json: marketCap].

### Debt Composition

| Component | Amount | Source |
|-----------|--------|--------|
| **Total Debt** | **$65,136M** | [balance.json: totalDebt, FY2025] |
| Short-term Debt | $3,152M | [balance.json: shortTermDebt] |
| Long-term Debt | $61,984M | [balance.json: longTermDebt] |
| Capital Lease Obligations | $0 | [balance.json: capitalLeaseObligations] |

Debt consists primarily of senior unsecured notes. In November 2023, Broadcom issued $29B in new senior notes for VMware acquisition financing. Known tranche: 2031 Notes at 5.150% [convertible_detail.md: SEC.gov filing reference]. Full maturity schedule by tranche is not available in the raw data [Data gap: 10-K debt maturity table not extracted].

**Debt trajectory:** FY2023 $39.6B → FY2024 $67.6B (+$28.0B, VMware financing) → FY2025 $65.1B (−$2.4B reduction). [Inference: FY2024 debt increase aligns with VMware close and cashflow.json showing $20.3B net debt issuance + $26.0B acquisition spend] [Sources: balance.json, cashflow.json].

### Convertible Debt

None outstanding. The Series A Mandatory Convertible Preferred was fully converted by Sep 2022 [convertible_search.json; balance.json: FY2025 preferredStock $0].

### Cash and Equivalents

$16,178M [balance.json: cashAndCashEquivalents, FY2025].

### Minority Interest

$0 [balance.json: minorityInterest, FY2025].

### Enterprise Value

$2,047.0B [Computed: $1,998.1B market cap + $65,136M debt − $16,178M cash]. The FMP-stored EV of $1,757.3B [enterprise_value.json] was calculated at the filing-date price of $362.55 and is stale.

### Net Debt / EBITDA

**1.41x** [Computed: $48,958M net debt / $34,714M FY2025 EBITDA] [Sources: balance.json, income.json]. This compares to 2.44x at FY2024-end, reflecting rapid deleveraging as EBITDA grew and $2.4B debt was repaid.

---

## Cross-Reference Discrepancies

1. **NVDA data center revenue:** Risk_factors.md cites $75.3B in one instance; competitive_position.md cites $75.2B and flags Contradicted C022. The verified figure is $75.2B, not $75.3B [claim_verification.json: C022].
2. **TSMC wafer dependency:** Multiple analyses cite "~95% of wafers from TSMC." The 10-K says "the majority" without quantification [Unverifiable C038].
3. **Employee count:** info.json description says 19,000; info.json fullTimeEmployees field says 37,000. The 37,000 figure is current [info.json: fullTimeEmployees].
4. **ADV discrepancy:** technicals.json adv_30d ($7.87B, using 30-day avg volume 18.77M shares) vs. info.json averageVolume × price ($10.04B, using longer-term avg volume 23.78M shares). Report header uses info.json per specification.

## Data Gaps

- **Per-customer revenue:** Broadcom does not disclose individual customer revenue in SEC filings. AI revenue concentration among 6 XPU customers is not quantified at the customer level.
- **Debt maturity schedule:** Specific amounts by maturity year not available.
- **Geographic revenue breakdown:** FMP segments API returned 404; 10-K geographic split not extracted.
- **AVGO's TSMC CoWoS allocation:** Not publicly disclosed. NVDA at ~50% is Unverifiable [C043].
- **Custom vs. GPU allocation ratio at hyperscalers:** No hyperscaler discloses this split.
- **VMware churn rate post-pricing changes:** Not quantified by Broadcom.
- **Annual AI revenue total:** Broadcom does not disclose annual AI semiconductor revenue; only quarterly figures from earnings calls.
- **Proxy statement (DEF 14A):** EDGAR parsing error [proxy.json: error]. Executive compensation and governance data unavailable.
- **Patent portfolio:** raw/patents.json not present in workspace.
- **Congressional trading:** FMP API returned 404 [government.json].

---

## Appendix

    Mac OS X            	   2   q      �                                      ATTR       �   �                     �     com.apple.provenance  ���%��_

    Mac OS X            	   2   q      �                                      ATTR       �   �                     �     com.apple.provenance  ���%��_

    Mac OS X            	   2   q      �                                      ATTR       �   �                     �     com.apple.provenance  ���%��_

    Mac OS X            	   2   q      �                                      ATTR       �   �                     �     com.apple.provenance  ���%��_

    Mac OS X            	   2   q      �                                      ATTR       �   �                     �     com.apple.provenance  ���%��_

    Mac OS X            	   2   q      �                                      ATTR       �   �                     �     com.apple.provenance  ���%��_

    Mac OS X            	   2   q      �                                      ATTR       �   �                     �     com.apple.provenance  ���%��_

    Mac OS X            	   2   q      �                                      ATTR       �   �                     �     com.apple.provenance  ���%��_

# Appendix A: Competitive Position — Expanded

## Custom AI Accelerator (XPU/ASIC) Market

### Market Share Estimates

Third-party estimates for AVGO custom AI ASIC market share:
- Gotrade (Apr 2026): ~70% for 2026 [ecosystem_signals.md] [Single-Source C039: Gotrade blog, no methodology cited]
- Yahoo Finance: 60% projected for 2027 [claim_verification.json: C039 cross-reference]
- Broadcom does not disclose custom AI ASIC market share in SEC filings [Data gap]

### Scale Comparison: AVGO vs. MRVL

| Metric | AVGO | MRVL | Ratio |
|--------|------|------|-------|
| AI revenue (Q1 FY2026) | $8.4B quarterly | ~$1.5B annualized custom ASIC [Single-Source C016] | 5.6x (AVGO quarterly vs MRVL annual) |
| Total revenue (latest FY) | $63.9B (FY2025) | $8.2B (FY2026 ended Jan 2026) [Verified C011] | 7.8x |
| Data center revenue (latest FY) | ~$30B+ (AI + networking est.) | >$6.0B (+46% YoY) [Corroborated C013] | ~5x |

[income.json: FY2025 revenue $63,887M; ecosystem_signals.md: MRVL data]

### Named AI XPU Customers

| Customer | Product | FY2027 Scale | Source |
|----------|---------|--------------|--------|
| Google (Alphabet) | TPU (Ironwood, 7th gen) | "Strong demand"; analyst Rasgon estimated 3+ GW | [transcript.json: CEO Hock Tan] |
| Anthropic | TPU racks | 1 GW in 2026, "surging in excess of 3 GW" in 2027 | [transcript.json: CEO Hock Tan] |
| Meta | MTIA custom accelerator | "multiple gigawatts in '27 and beyond" | [transcript.json: CEO Hock Tan] |
| OpenAI | Custom XPU (6th customer) | "over 1 gigawatt" in 2027 | [transcript.json: CEO Hock Tan] |
| Customers 4 & 5 | Custom XPUs | "strong shipments...more than double in 2027" | [transcript.json: CEO Hock Tan] |

Total FY2027 scale: ~10 gigawatts. Revenue per GW: analyst Rasgon estimated ~$20B/GW; CEO Tan said "it's not far from the dollars you're talking about" [transcript.json: Hock Tan, Q&A with Stacy Rasgon (Bernstein)].

CEO Tan stated "line of sight to achieve AI revenue from chips, just chips, in excess of $100 billion in 2027" [transcript.json: Hock Tan]. OpenAI 10 GW collaboration through 2029 confirmed [press_releases.md; Verified C066].

### Marvell Competitive Detail

- FY2026 revenue: $8.195B (+42% YoY), data center >$6B (+46% YoY) [ecosystem_signals.md: Verified C011, Corroborated C013]
- Custom chip ~$1.5B annualized [Single-Source C016]; guided >20% growth in FY2027
- 20+ custom design wins at record level [Corroborated C020]
- $2B strategic investment from NVIDIA (March 2026) for NVLink-compatible interconnect and optical DSPs [Verified C017]
- Acquisitions: Celestial AI ($3.25B base, up to $5.5B with earnouts, Dec 2025), XConn Technologies ($540M, Jan 2026), Polariton Technologies (Apr 2026) [Verified C018, C019]
- Non-GAAP gross margin 59.0% (Q4 FY2026), operating margin 35.7% [ecosystem_signals.md: Marvell IR]
- Reportedly secured portion of next-gen Google TPU work [Corroborated C015: 3 independent sources including The Information, CNBC]. No formal contract confirmed by Marvell IR [Data gap].

### NVIDIA Competitive Detail

- Q1 FY2027 revenue $81.6B (+85% YoY), data center $75.2B (+92% YoY) [Verified C021; Contradicted C022 at $75.2B not $75.3B]
- Hyperscaler revenue $38B (>50% of data center), up 12% QoQ [Corroborated C028]
- Vera Rubin next-gen: "up to 10x more performance per watt" for specific inference workloads [Verified C031 with "up to" qualifier]
- Supply constrained "throughout the entire life of Vera Rubin" per Jensen Huang [Verified C031]
- NVDA acquired Groq for $20B total ($13B upfront) [Contradicted C029: total was $20B, not $13B as stated in some sources; $13B was upfront portion]
- Cerebras IPO'd at ~$95B market cap (CNBC) to ~$70B (Yahoo Finance) [Corroborated C030; discrepancy in share count methodology]

### Adjacent Competitors / Potential Entrants

- **Hyperscaler in-house teams:** Google, Amazon (Trainium), Microsoft (Maia), Meta (MTIA with Broadcom). Risk of full in-house design over time.
- **AMD:** MI300 and upcoming Helios rack-scale AI systems. Primarily competes with NVIDIA.
- **Cerebras:** Wafer-scale computing, different from custom ASICs.

### Switching Costs

**Custom AI ASICs:** 2-4 year co-engineering design cycles with hyperscalers [transcript.json: Charlie Kawwas]. Customers develop proprietary software stacks (Google's JAX/XLA). NRE costs at advanced nodes: $50-100M+ [customer_alternatives.md; verification notes this may be outdated]. Total co-engineering investment per XPU program likely exceeds $500M over multi-year programs [Inference: based on multi-gigawatt scale at ~$20B/GW content] [Sources: transcript.json, customer_alternatives.md].

**VMware:** Deep enterprise integration (compute, storage, networking). Post-acquisition subscription bundling increases lock-in. CEO Tan: VCF "cannot be disintermediated or replaced" (management characterization, not independently verified) [transcript.json: Hock Tan]. ARR growth of 19% YoY suggests customers continue signing contracts despite pricing changes [transcript_segments.json: Hock Tan].

### Peer Financial Benchmarking

| Metric | AVGO | MRVL (est.) | NVDA (est.) | AMD |
|--------|------|-------------|-------------|-----|
| Revenue (latest FY, $B) | $63.9 | $8.2 | $215.9 | ~$25B |
| Revenue Growth (YoY) | +23.9% | +42% | +65% | +14%* |
| Gross Margin | 67.8% (GAAP) | 59.0% (non-GAAP) | 75.0% (GAAP, Q1 FY2027) | ~50%* |
| Operating Margin | 39.9% (GAAP) | 35.7% (non-GAAP) | ~55%* | ~25%* |
| Market Cap ($B) | $1,998 | ~$130* | ~$3,000+* | $822 |
| FCF Margin | 42.1% | N/A | ~60% (Q1) | N/A |

[income.json: AVGO; ecosystem_signals.md: MRVL, NVDA; peer_compare.json: AMD market cap $822B]
*Marked figures are approximate from available data; detailed peer metrics not pulled in this run.

### Short Interest

| Metric | Value | Source |
|--------|-------|--------|
| Shares short | 51,011,972 | [short_interest.md: Corroborated C077; FINRA report Apr 30, 2026] |
| % of float | 1.10% | [short_interest.md: Corroborated C077] |
| Change from prior | -6.62% (from 54.63M) | [short_interest.md: Corroborated C077] |
| Days to cover | 2.1-2.6 | [Contradicted C074; varies by volume window] |

Short interest of 1.10% of float is low and declining.

# Appendix B: Supply/Demand Balance — Expanded

## Demand Decomposition

### Backlog

- **Total consolidated backlog:** $162B (disclosed Q4 FY2025, Dec 2025) [backlog_breakdown.md: Verified C001]
- **AI-specific backlog:** $73B "in excess" [backlog_breakdown.md: Verified C001]
- **AI backlog concentration:** 5 customers at Q4 FY2025 disclosure (now 6) [backlog_breakdown.md: Corroborated C004]
- **Backlog composition:** includes orders for "XPU switches, DSPs" [claim_verification.json: C001 chase_result]
- **Backlog coverage:** Total backlog = 2.5x FY2025 revenue ($162B / $63.9B). AI backlog = ~2.2 years at Q1 FY2026 AI run rate ($73B / $33.6B annualized) [Computed]
- **Single order:** $10B Ironwood TPU rack order from Anthropic received Q3 FY2025 [Corroborated C003]
- **Updated backlog (Q1 FY2026):** Not disclosed [Data gap]

### AI Revenue Trajectory

| Period | AI Revenue | YoY Growth | Source |
|--------|-----------|------------|--------|
| Q1 FY2025 (implied) | ~$4.1B | — | [Inference: $8.4B / (1 + 1.06)] [Sources: transcript_segments.json, earnings.json] |
| Q4 FY2025 | Not separately disclosed | +74% YoY | [Verified C071] |
| Q1 FY2026 | $8.4B | +106% | [Verified C084; transcript_segments.json: Hock Tan] |
| Q2 FY2026 (guided) | $10.7B | +140% | [transcript_segments.json: Hock Tan] |

AI as % of total revenue: ~27% (Q1 FY2025 implied) → 43.5% (Q1 FY2026) → ~48.6% (Q2 FY2026 guided) [Computed].

Within semiconductors, AI was 67.2% in Q1 FY2026, rising to ~72.3% in Q2 guidance [Computed: $10.7B / ($22.0B − estimated $7.2B software) ≈ $10.7B / $14.8B semi].

### Demand Durability: Hyperscaler Capex

| Customer | Capex Guidance | Source |
|----------|---------------|--------|
| Google (Alphabet) | $175-185B for 2026 | [customer_capex.md: MarketBeat, Feb 2026] |
| Meta | $60-65B for 2025 (most recent) | [customer_capex.md] |
| Microsoft | $80B+ | [customer_capex.md] |
| Amazon | $100B+ | [customer_capex.md] |

Total hyperscaler AI capex envelope: $350B+ collectively. Specific allocation to AVGO products is not disclosed.

### Demand-Side Bargaining Power

Gross margin stability despite volume growth. CEO Tan explicitly rejected margin dilution concerns from rack-level shipments: "you must be a bit hallucinating" [transcript.json: Hock Tan, Q&A with Timothy Arcuri (UBS)]. CFO Spears confirmed: "the impact relative to our overall mix is actually not going to be substantial at all" [transcript.json: Kirsten Spears].

### Growth Driver Decomposition

In Q1 FY2026, AVGO grew total revenue by ~$4.4B YoY ($19.3B − $14.9B). AI revenue grew by ~$4.3B ($8.4B − ~$4.1B). Non-AI semi was flat; software grew 1% (~$0.1B). Therefore, approximately 98% of YoY revenue growth was from AI semiconductors [Inference: Q1 FY2025 total was $14,916M per earnings.json] [Sources: earnings.json, transcript.json].

---

## Supply Analysis

### Current Constraints by Input Type

1. **Leading-edge wafers (TSMC 3nm/5nm):** TSMC sold out across advanced nodes. Advanced chips (≤7nm) = ~74% of TSMC wafer revenue [ecosystem_signals.md: CNBC, Apr 16, 2026]. CEO Tan stated TSMC capacity "has become a bottleneck, or that has kind of choked the supply chain in 2026" [supplier_capacity.md: Yahoo Finance, Mar 23, 2026].

2. **CoWoS advanced packaging:** Only TSMC provides at scale. Capacity growing >80% CAGR 2026-2028 [Corroborated C036: 3 independent sources, TSMC management]. NVDA estimated ~50% of CoWoS capacity [Unverifiable C043: no primary source, TSMC does not disclose customer-level allocation]. AVGO's specific share not disclosed [Data gap].

3. **High-Bandwidth Memory (HBM):** Constrained industry-wide. SK Hynix, Samsung, Micron supply. AVGO secured HBM through 2028 [transcript.json: Hock Tan].

4. **Substrates (T-glass):** CEO Tan: "We were early in being able to lock up T-glass" [transcript.json: Hock Tan, Q&A with Ben Reitzes].

### How Supply Gets Added

| Capacity | Timeline | Source |
|----------|----------|--------|
| TSMC Tainan 3nm fab | Volume production H1 2027 | [ecosystem_signals.md: Manufacturing Dive, Apr 17, 2026] |
| TSMC Arizona 2nd fab (3nm) | Production H2 2027 | [Verified C037] |
| TSMC Japan 2nd fab (3nm) | Production 2028 | [ecosystem_signals.md] |
| TSMC Arizona packaging fab | Permitting stage | [ecosystem_signals.md] |
| TSMC total US investment | $165B | [Verified C037] |
| CoWoS capacity | >80% CAGR through 2028 | [Corroborated C036] |
| TSMC 2026 capex | High end of $52-56B | [Corroborated C046] |

New fabs take 2-3 years from announcement to production. Earliest new 3nm capacity (Tainan) reaches volume H1 2027. Supply constraint is structural in 2026; begins easing 2027.

### Supply-Side Bargaining Power

TSMC has demonstrable pricing power: Q1 2026 gross margin 66.2% (operating margin 58.1%, net margin 50.5%) [Verified C034], exceeding its own 63-65% guidance range. TSMC is investing at high end of $52-56B capex while maintaining premium pricing.

AVGO's lack of formal long-term supplier agreements per 10-K [Unverifiable C045] contrasts with CEO claims of having "secured capacity through '28." [Inference: operational arrangements exist that are not structured as formal contracts disclosed in SEC filings] [Sources: 10-K FY2025, transcript.json].

TSMC margin dilution from 2nm ramp and overseas expansion could flow through to AVGO's wafer costs [ecosystem_signals.md: Manufacturing Dive, Apr 17, 2026].

---

## Supply/Demand Synthesis

**Net balance:** Demand exceeds supply in 2026. TSMC is sold out. AVGO has secured capacity through 2028, but total industry demand from NVDA, AVGO, MRVL, AMD, Apple, QCOM competing for the same nodes means allocation — not total demand — is the binding constraint.

**Quantitative gap:** AVGO targets $100B+ AI chip revenue for FY2027 from Q1 FY2026 run rate of ~$33.6B ($8.4B × 4). This requires substantial ramp. CoWoS capacity growing >80% CAGR should ease the bottleneck progressively, but demand is also growing (NVDA guided Q2 at $91B).

**Pricing implications:** Gross margins stable-to-expanding. Supply-constrained environment supports pricing stability.

---

## AI Value Chain Position

### Revenue Quantification

| Component | Q1 FY2026 Revenue | % of Total | YoY Growth |
|-----------|-------------------|-----------|------------|
| AI Semiconductors (total) | $8.4B | 43.5% | +106% |
| — Custom XPUs (~2/3) | ~$5.6B (est.) | ~29.0% | +140% |
| — AI Networking (~1/3) | ~$2.8B (est.) | ~14.5% | +60% |
| Non-AI Semiconductors | $4.1B | 21.2% | 0% |
| Infrastructure Software | $6.8B | 35.2% | +1% |
| **Total** | **$19.3B** | **100%** | **+29.5%** |

[transcript.json: Hock Tan and Kirsten Spears; earnings.json: Q1 FY2026 actual $19,311M]

### Remaining Data Gaps

- Custom vs. GPU allocation ratio at hyperscalers [Not disclosed by any hyperscaler]
- AVGO's TSMC CoWoS allocation [Not publicly disclosed]
- Q1 FY2026 updated backlog figure [Not disclosed on Q1 call]
- Wafer pricing dynamics between TSMC and AVGO [Not disclosed by either party]

# Appendix C: Value Chain — Expanded

## Value Chain Map

### Semiconductor Solutions

```
Raw materials (silicon wafers, chemicals, substrates, HBM)
  → Wafer fabrication (TSMC primarily; UMC, GlobalFoundries for legacy)
    → Advanced packaging (TSMC CoWoS; ASE, SPIL, Amkor)
      → AVGO: CHIP DESIGN + IP + SYSTEM ARCHITECTURE (fabless)
        → Assembly & test (ASE, SPIL, Foxconn, Amkor)
          → Distribution (48% via distributors; 52% direct/OEM CMs)
            → End customers: hyperscalers (Google, Meta, Anthropic, OpenAI + 2 unnamed)
              → AI data centers → LLM training/inference
```

[EDGAR: 10-K FY2025 — Manufacturing section]

### Infrastructure Software

```
Open-source ecosystem (Linux, Kubernetes)
  → AVGO: SOFTWARE DEVELOPMENT + IP (VMware, CA, Symantec)
    → Distribution: direct sales, resellers, distributors, cloud providers, OEM partners
      → End customers: enterprises (banks, insurers, government, telcos)
        → Private/hybrid cloud, mainframe ops, cybersecurity
```

[transcript_segments.json: Kirsten Spears]

## Upstream: Suppliers

### Wafer Fabrication

| Supplier | Role | Concentration | Source |
|----------|------|---------------|--------|
| **TSMC** | Primary foundry (3nm/5nm/7nm) | "Majority" of front-end wafer manufacturing | [EDGAR: 10-K FY2025] |
| UMC | Secondary foundry (mature nodes) | Minor share | [Corroborated C098] |
| GlobalFoundries | Secondary foundry (specialty) | Minor share | [Corroborated C098] |

The "~95% of wafers from TSMC" figure is widely cited but not confirmed in 10-K filing text [Unverifiable C038]. The 10-K uses "the majority" without quantification.

### Assembly, Test, and Packaging

| Supplier | Role | Geography | Source |
|----------|------|-----------|--------|
| ASE | Assembly & test | Taiwan, China, Singapore | [EDGAR: 10-K FY2025] |
| SPIL | Assembly & test | Taiwan | [EDGAR: 10-K FY2025] |
| Amkor | Assembly & packaging | Korea, Philippines, Taiwan, China | [EDGAR: 10-K FY2025] |
| Foxconn | Contract manufacturing | Taiwan, China | [EDGAR: 10-K FY2025] |
| TSMC | Advanced packaging (CoWoS) | Taiwan (Arizona permitting) | [EDGAR: 10-K FY2025; ecosystem_signals.md] |

### Critical Materials

Management stated capacity for HBM, substrates (T-glass), and leading-edge wafers secured through 2028 [transcript.json: Hock Tan; Charlie Kawwas]. Charlie Kawwas: "We have to go secure it for multiple years and we're probably the first one to secure that up to '28 or beyond" [transcript.json: Charlie Kawwas, Q&A].

### Procurement Structure

10-K states: "We purchase materials from hundreds of suppliers on a global basis. These purchases are generally on a purchase order basis" [EDGAR: 10-K FY2025]. However, VP Ramachandran confirmed "long-term agreements with suppliers to secure capacity commitments for as long as three to four years" [Verified C096]. [Inference: general purchases remain per-order; strategic AI components have specific capacity agreements] [Sources: 10-K FY2025, claim_verification.json C096].

### Internal Fabrication

Broadcom maintains internal fab capabilities for III-V compound semiconductors (FBAR filters, GaAs/InP lasers) in the U.S. and Singapore. This is a longstanding capability from Avago Technologies heritage [EDGAR: 10-K FY2025 — Manufacturing section].

## Downstream: Customers

### Customer Concentration (10-K, Tier 1)

- 48% of revenue via distributors (FY2025 and FY2024) [EDGAR: 10-K FY2025]
- Top 5 end customers ~40% of revenue (FY2025 and FY2024) [EDGAR: 10-K FY2025]
- No individual customer named or disclosed as >10% of revenue [Inference: SEC rules require disclosure if a single customer exceeds 10%; absence of disclosure suggests either no single customer exceeds 10% or aggregation through distributors masks direct concentration] [Sources: EDGAR 10-K FY2025]

### Customer Switching Costs

**XPU (custom ASIC):** Multi-year co-engineering (2-4 years), proprietary software stacks, NRE costs $50-100M+ at advanced nodes [customer_alternatives.md; Single-Source C057]. CEO Tan: "Can you produce 100,000 of those chips quickly at yields that you can afford? And we don't see too many players in the world that can do that" [transcript.json: Hock Tan].

**VMware:** Enterprise-wide integration of compute, storage, networking virtualization. CEO Tan: VCF is "the permanent abstraction layer between AI software and physical chips" (management characterization) [transcript.json]. TCV >$9.2B booked Q1 FY2026, indicating ongoing customer commitment [transcript_segments.json: Hock Tan].

### Evidence of Actual Switching

- Google/MRVL: Marvell reportedly secured portion of next-gen TPU work — supply diversification, not full switch [Corroborated C015]. No formal contract confirmed [Data gap].
- VMware: "potential for customer churn to alternative private cloud solutions" post-pricing changes [claim_verification.json: C079]. No quantified churn data available.

## Margin Capture Analysis

| Stage | Entity | Gross Margin | Operating Margin | Source |
|-------|--------|-------------|-----------------|--------|
| EDA tools | Synopsys, Cadence | ~80% | ~30-35% | [Inference: publicly reported margins] |
| Foundry | TSMC | 66.2% | 58.1% | [Verified C034] |
| Chip design (semi) | AVGO | 68% (non-GAAP) | 60% (non-GAAP) | [transcript_segments.json: Kirsten Spears, Q1 FY2026] |
| Chip design + software (blended) | AVGO | 77% (non-GAAP) | 66.4% (non-GAAP adj. EBITDA ~68%) | [transcript_segments.json: Kirsten Spears] |
| Software | AVGO | 93% | 78% | [transcript_segments.json: Kirsten Spears, Q1 FY2026] |
| OSAT | ASE/SPIL | ~20-25% | ~8-12% | [Inference: general industry knowledge, not from workspace data] |
| GPU design | NVIDIA | 75.0% (GAAP) | — | [ecosystem_signals.md: NVDA Q1 FY2027] |

**GAAP vs. Non-GAAP gap:** AVGO GAAP operating margin (39.9% FY2025) is ~26pp below non-GAAP (~66%) due to $8.8B D&A (primarily VMware intangible amortization) and $7.6B SBC [income.json; cashflow.json].

**Margin trend:** Semiconductor non-GAAP operating margin expanded 260 bps YoY to 60% in Q1 FY2026 [transcript_segments.json: Kirsten Spears]. Software expanded 190 bps YoY to 78% [transcript_segments.json: Kirsten Spears].

## Integration Direction

### Vertical Integration Score

| Stage | Integration Level | Change Over 3Y |
|-------|------------------|----------------|
| EDA/Design tools | Outsourced | Stable |
| Chip architecture & IP | **In-house** (~19,000 patents) | Stable |
| SerDes/PHY IP | **In-house** (200G/400G) | Stable |
| Wafer fabrication (CMOS) | Outsourced (TSMC) | Stable |
| Wafer fabrication (III-V) | **In-house** | Stable |
| Advanced packaging | Outsourced (TSMC CoWoS) | Stable |
| Assembly & test | Outsourced | Stable |
| System/rack integration | **Partial** (Anthropic racks) | **Integrating** (new FY2024+) |
| Networking design | **In-house** (Tomahawk, DSPs) | Stable |
| Infrastructure software | **In-house** (via acquisition) | **Integrated** (VMware Nov 2023) |

[EDGAR: 10-K FY2025; transcript.json]

## Dependencies and Vulnerabilities

1. **TSMC single-foundry:** All advanced AI XPUs, Tomahawk, optical DSPs require TSMC leading-edge nodes and CoWoS packaging. No alternative at scale.
2. **Taiwan geographic:** TSMC, ASE, SPIL headquartered in Taiwan. TSMC expanding to Arizona ($165B, H2 2027+) [Verified C037].
3. **Customer concentration (AI):** 43.5% of Q1 revenue from 6 XPU customers. Rising to ~48.6% by Q2 guidance.
4. **HBM/substrate supply:** Industry-wide constraint; AVGO claims secured through 2028.
5. **CoWoS allocation:** AVGO's specific share not disclosed [Data gap].
6. **Export controls:** U.S. EAR restrictions on advanced AI semiconductors [EDGAR: 10-K FY2025 risk factors].

## Ecosystem Signals

**MRVL (competitor):** FY2026 revenue $8.2B (+42%); custom ASIC ~$1.5B; secured Google TPU work; $2B NVDA investment [ecosystem_signals.md].

**NVDA (co-opetition):** Q1 FY2027 data center $75.2B (+92%); hyperscaler revenue $38B; acknowledges customer ASIC development in 10-Q [ecosystem_signals.md].

**TSMC (supplier):** Q1 2026 revenue $35.9B (+40.6%); HPC = 61% of revenue; gross margin 66.2%; sold-out 2026; capex $52-56B; CoWoS >80% CAGR [Verified C032, C034; Corroborated C036].

# Appendix D: Capital Structure — Expanded

## Equity Composition

| Item | Value | Source |
|------|-------|--------|
| Share Class | Common Stock, $0.001 par value | [insider.json: securityName] |
| Preferred Equity | $0 (Series A Mandatory Convertible Preferred fully converted Sep 2022) | [balance.json: preferredStock, FY2025; convertible_search.json] |
| Shares Outstanding | 4,734,670,000 | [shares_float.json: outstandingShares] |
| Float Shares | 4,642,774,789 (98.1% free float) | [shares_float.json: floatShares, freeFloat] |
| Dual-Class Structure | No (single class common) | [insider.json] |

## Market Cap

$1,998,078,086,700 ($1,998.1B) at $422.01/share as of 2026-05-26 [quote.json: marketCap].

## Debt Composition

| Component | Amount ($M) | Source |
|-----------|------------|--------|
| **Total Debt** | **$65,136** | [balance.json: totalDebt, FY2025] |
| Short-term Debt | $3,152 | [balance.json: shortTermDebt, FY2025] |
| Long-term Debt | $61,984 | [balance.json: longTermDebt, FY2025] |
| Capital Lease Obligations | $0 | [balance.json: capitalLeaseObligations, FY2025] |

### Debt Type

Primarily senior unsecured notes across multiple maturities. In November 2023, Broadcom issued $29B in new senior notes to finance the VMware acquisition ($61B). Known tranche: 2031 Notes at 5.150% [convertible_detail.md: SEC.gov filing reference, Tier 1 source].

### Debt Maturity Profile

**Data gap:** The detailed maturity schedule by year (specific amounts maturing each year) is not available in the raw data files. A 10-K extraction or SEC filing review would provide this detail. What is known:
- Short-term debt (due within 1 year): $3,152M [balance.json]
- Long-term debt: $61,984M [balance.json]
- Known tranche: 2031 Notes at 5.150% [convertible_detail.md]

### Debt Trajectory

| Year | Total Debt ($M) | Cash ($M) | Net Debt ($M) | Source |
|------|----------------|----------|--------------|--------|
| FY2025 | $65,136 | $16,178 | $48,958 | [balance.json] |
| FY2024 | $67,566 | $9,348 | $58,218 | [balance.json] |
| FY2023 | $39,648 | $14,189 | $25,459 | [balance.json] |
| FY2022 | $39,978 | $12,416 | $27,562 | [balance.json] |
| FY2021 | $40,273 | $12,163 | $28,110 | [balance.json] |

Total debt increased $27,918M from FY2023 to FY2024 due to VMware acquisition financing [Inference: timing aligns with VMware close Nov 2023; cashflow.json shows $20.3B net debt issuance + $26.0B acquisition spend] [Sources: balance.json, cashflow.json]. FY2025 saw $2,430M debt reduction while cash increased $6,830M, reducing net debt by $9,260M.

### Interest Expense

| Year | Interest Expense ($M) | Implied Avg Cost of Debt | Source |
|------|----------------------|--------------------------|--------|
| FY2025 | $3,210 | 4.9% ($3,210M / $65,136M) | [income.json: interestExpense] |
| FY2024 | $3,996 | 5.9% ($3,996M / $67,566M) | [income.json] |
| FY2023 | $1,625 | 4.1% ($1,625M / $39,648M) | [income.json] |

## Convertible Debt Details

No convertible debt currently outstanding. Historical: Series A Mandatory Convertible Preferred Stock ($3.0B issued September 2019) automatically converted to common stock September 30, 2022 [convertible_search.json: EDGAR EFTS results; convertible_detail.md: PR Newswire press release]. By FY2025, preferred stock = $0 [balance.json: preferredStock].

## Cash and Equivalents

| Item | Amount ($M) | Source |
|------|------------|--------|
| Cash & Cash Equivalents | $16,178 | [balance.json: cashAndCashEquivalents, FY2025] |
| Short-term Investments | $0 | [balance.json: cashAndShortTermInvestments = cashAndCashEquivalents] |
| **Total Cash & STI** | **$16,178** | [balance.json] |

## Minority Interest

$0 [balance.json: minorityInterest, FY2025].

## Enterprise Value

| Method | Value | Source |
|--------|-------|--------|
| **Current Price** | **$2,047,036M ($2,047.0B)** | [Computed: $1,998,078M + $65,136M − $16,178M] |
| FMP at Filing (stale) | $1,757,294M ($1,757.3B) | [enterprise_value.json: at $362.55/share] |

The FMP-stored EV was calculated at $362.55/share (FY2025 filing date), which is 14.1% below the current price of $422.01.

## Net Debt / EBITDA

| Metric | Value | Computation | Source |
|--------|-------|-------------|--------|
| Net Debt | $48,958M | $65,136M − $16,178M | [balance.json] |
| FY2025 EBITDA | $34,714M | — | [income.json: ebitda] |
| **Net Debt / EBITDA** | **1.41x** | $48,958M / $34,714M | [Computed] |

Leverage trajectory:
- FY2025: 1.41x
- FY2024: 2.44x ($58,218M / $23,867M EBITDA)
- FY2023: 1.24x ($25,459M / $20,548M EBITDA)

Rapid deleveraging from FY2024 peak of 2.44x [Inference: driven by EBITDA growth ($23.9B → $34.7B, +45%) and $2.4B debt paydown] [Sources: balance.json, income.json].

## Interest Coverage

EBIT / Interest Expense:
- FY2025: 7.9x ($25,484M / $3,210M) [income.json]
- FY2024: 3.4x ($13,461M / $3,996M) [income.json]
- FY2023: 10.0x ($16,206M / $1,625M) [income.json]

# Appendix E: Key Stats — Expanded

All multiples computed at current price ($422.01) unless otherwise noted. All monetary figures in USD.

## Price and Trading

| Metric | Value | Computation | Source |
|--------|-------|-------------|--------|
| Price | $422.01 | — | [quote.json: price, 2026-05-26] |
| 52-Week Range | $234.43 – $442.36 | — | [quote.json: yearLow, yearHigh] |
| ADV (30d, shares) | 18,770,049 | — | [technicals.json: avg_volume_30d] |
| ADV (30d, $) | $7,868M | 18,770,049 × $422.01 / 1e6 = $7,921M (note: technicals.json reports $7,868M pre-computed) | [technicals.json: adv_30d] |
| ADV (longer-term, $) | $10,036M | info.json avgVolume (23,781,641) × $422.01 | [info.json: averageVolume] |
| RSI (14-day) | 56.4 | — | [technicals.json: rsi_14] |
| 21-day EMA | $413.84 | — | [technicals.json: ema_21d] |
| 50-day SMA | $379.04 | — | [technicals.json: sma_50d] |
| 200-day SMA | $350.44 | — | [technicals.json: sma_200d] |
| Beta | 1.44 | — | [info.json: beta] |

## Valuation Multiples

| Metric | Value | Computation | Source |
|--------|-------|-------------|--------|
| Trailing P/E (FY2025 diluted EPS) | 88.5x | $422.01 / $4.77 | [quote.json; income.json: epsDiluted FY2025] |
| LTM P/E (last 4 quarters non-GAAP) | 58.0x | $422.01 / $7.27 ($1.58+$1.69+$1.95+$2.05) | [quote.json; earnings.json: epsActual Q2-Q4 FY2025 + Q1 FY2026] |
| Forward P/E (FY2026E) | 37.5x | $422.01 / $11.27 | [quote.json; ratings.json: epsAvg FY2026] |
| Forward P/E (FY2027E) | 23.3x | $422.01 / $18.11 | [quote.json; ratings.json: epsAvg FY2027] |
| EV/EBITDA (FY2025) | 59.0x | $2,047.0B / $34.7B | [Computed: EV from balance.json + quote.json; EBITDA from income.json] |
| EV/Revenue (FY2025) | 32.0x | $2,047.0B / $63.9B | [Computed] |
| EV/Revenue (FY2026E) | 19.8x | $2,047.0B / $103.3B | [Computed; ratings.json: revenueAvg FY2026] |
| EV/Revenue (FY2027E) | 12.6x | $2,047.0B / $162.3B | [Computed; ratings.json: revenueAvg FY2027] |
| P/FCF (FY2025) | 74.2x | $1,998.1B / $26.9B | [quote.json; cashflow.json: freeCashFlow FY2025] |
| P/FCF-ex-SBC | 103.3x | $1,998.1B / ($26.9B − $7.6B SBC) = $1,998.1B / $19.3B | [quote.json; cashflow.json] |
| Dividend Yield | 0.62% | ($0.65/qtr × 4) / $422.01 = $2.60 / $422.01 | [transcript.json: Kirsten Spears; quote.json] |

### Notes on Trailing P/E

The 88.5x trailing P/E uses FY2025 diluted EPS of $4.77. This figure is affected by: (1) a negative effective tax rate of -1.7% in FY2025, which increased reported net income by ~$4.1B vs. a normalized 16.5% rate [Inference: at 16.5%, tax would be $3.75B vs. actual benefit of -$397M, a $4.1B swing] [Sources: income.json, ratios.json]; (2) $8.8B in D&A (primarily VMware intangible amortization) [income.json]. The LTM P/E of 58.0x using the last 4 reported quarters' non-GAAP EPS provides a more comparable metric [earnings.json].

## Margins (GAAP)

| Year | Gross Margin | Operating Margin | Net Margin | EBITDA Margin | Source |
|------|-------------|-----------------|-----------|--------------|--------|
| FY2025 | 67.8% | 39.9% | 36.2% | 54.3% | [income.json] |
| FY2024 | 63.0% | 26.1% | 11.4% | 46.3% | [income.json] |
| FY2023 | 68.9% | 45.2% | 39.3% | 57.4% | [income.json] |
| FY2022 | 66.5% | 42.8% | 34.6% | 57.7% | [income.json] |
| FY2021 | 61.4% | 31.0% | 24.5% | 53.5% | [income.json] |

## Segment Margins (Q1 FY2026, Non-GAAP)

| Segment | Gross Margin | Operating Margin | Source |
|---------|-------------|-----------------|--------|
| Semiconductor Solutions | ~68% | 60% | [transcript_segments.json: Kirsten Spears] |
| Infrastructure Software | 93% | 78% | [transcript_segments.json: Kirsten Spears] |
| Consolidated | 77% | ~68% adj. EBITDA | [transcript_segments.json: Kirsten Spears] |

## Cash Flow

| Year | Revenue ($B) | OCF ($B) | CapEx ($M) | FCF ($B) | FCF Margin | Source |
|------|-------------|---------|-----------|---------|-----------|--------|
| FY2025 | $63.9 | $27.5 | $623 | $26.9 | 42.1% | [income.json, cashflow.json] |
| FY2024 | $51.6 | $20.0 | $548 | $19.4 | 37.6% | [income.json, cashflow.json] |
| FY2023 | $35.8 | $18.1 | $452 | $17.6 | 49.2% | [income.json, cashflow.json] |
| FY2022 | $33.2 | $16.7 | $424 | $16.3 | 49.1% | [income.json, cashflow.json] |
| FY2021 | $27.4 | $13.8 | $443 | $13.3 | 48.5% | [income.json, cashflow.json] |

CapEx/Revenue consistently below 2% [Inference: consistent with fabless model where wafer fabrication is outsourced to TSMC] [Sources: cashflow.json, 10-K FY2025].

## Returns on Capital

| Year | ROIC | ROIC-WACC Spread | Invested Capital ($B) | Source |
|------|------|------------------|----------------------|--------|
| FY2025 | 16.4% | +4.2pp | $145.7 | [metrics.json] |
| FY2024 | 5.6% | −6.6pp | $143.9 | [metrics.json] |
| FY2023 | 22.5% | +10.3pp | $63.6 | [metrics.json] |
| FY2022 | 19.7% | +7.5pp | $64.4 | [metrics.json] |
| FY2021 | 12.2% | ~0pp | $67.5 | [metrics.json] |

WACC estimate: ~12.2% (CAPM: 4.5% RFR + 1.44 beta × 5.5% ERP = 12.4% cost of equity; 4.9% pre-tax cost of debt; 96.8% equity weight) [Computed from info.json, income.json, balance.json, quote.json].

## DuPont ROE Decomposition (FY2025)

| Component | Value | Source |
|-----------|-------|--------|
| Net Margin | 36.2% ($23.1B / $63.9B) | [income.json] |
| Asset Turnover | 0.373x ($63.9B / $171.1B) | [income.json, balance.json] |
| Financial Leverage | 2.10x ($171.1B / $81.3B) | [balance.json] |
| **ROE** | **28.4%** (36.2% × 0.373 × 2.10) | [Computed] |

## Greenwald Decomposition

| Item | Value | Source |
|------|-------|--------|
| Tangible Book Value | −$48.8B | [Computed: $171.1B assets − $97.8B goodwill − $32.3B intangibles − $89.8B liabilities] |
| Earnings Power Value | $155.6B ($32.86/share) | [Inference: $19.0B normalized NI / 12.2% WACC] [Sources: income.json, transcript.json] |
| Franchise Value | $1,842.5B (92.2% of mkt cap) | [Computed: $1,998.1B − $155.6B] |

## Earnings History

| Quarter | EPS Actual | EPS Est. | EPS Delta | Rev Actual ($B) | Rev Est. ($B) | Rev Delta ($M) |
|---------|-----------|---------|-----------|----------------|--------------|----------------|
| Q1 FY2026 | $2.05 | $2.03 | +$0.02 | $19.31 | $19.26 | +$55 |
| Q4 FY2025 | $1.95 | $1.87 | +$0.08 | $18.02 | $17.47 | +$549 |
| Q3 FY2025 | $1.69 | $1.66 | +$0.03 | $15.95 | $15.83 | +$126 |
| Q2 FY2025 | $1.58 | $1.57 | +$0.01 | $15.00 | $14.96 | +$46 |
| Q1 FY2025 | $1.60 | $1.51 | +$0.09 | $14.92 | $14.62 | +$300 |
| Q4 FY2024 | $1.42 | $1.38 | +$0.04 | $14.05 | $14.07 | −$14 |
| Q3 FY2024 | $1.24 | $1.22 | +$0.02 | $13.07 | $12.98 | +$93 |
| Q2 FY2024 | $1.10 | $1.09 | +$0.01 | $12.49 | $12.06 | +$430 |
| Q1 FY2024 | $1.10 | $1.04 | +$0.06 | $11.96 | $11.79 | +$166 |

[earnings.json: all quarters]

9 of 9 quarters beat on EPS. 8 of 9 beat on revenue (Q4 FY2024 was −$14M). Average EPS beat: +$0.04 (+2.8%). Average revenue beat: +$195M (+1.4%).

## Analyst Consensus

| Year | Revenue Est. ($B) | YoY Growth | EPS Est. | # Analysts | Source |
|------|------------------|-----------|---------|-----------|--------|
| FY2026E | $103.3 | +61.7% | $11.27 | 33 (rev) | [ratings.json] |
| FY2027E | $162.3 | +57.1% | $18.11 | 35 (rev) | [ratings.json] |
| FY2028E | $206.4 | +27.2% | $22.61 | 21 (rev) | [ratings.json] |

Price target consensus: Median $456, range $335–$582, 46 analysts [ratings.json].

## Capital Returns

| Year | Dividends ($B) | Buybacks ($B) | Total ($B) | % of FCF | Source |
|------|---------------|-------------|-----------|---------|--------|
| FY2025 | $11.1 | $6.3 | $17.5 | 65% | [cashflow.json] |
| FY2024 | $9.8 | $12.4 | $22.2 | 114% | [cashflow.json] |
| FY2023 | $7.6 | $7.7 | $15.3 | 87% | [cashflow.json] |

Q1 FY2026: $3.1B dividends + $7.8B buybacks = $10.9B [transcript.json: Kirsten Spears].

## Other Scores

| Metric | Value | Source |
|--------|-------|--------|
| Altman Z-Score | 14.49 | [scores.json] |
| Piotroski Score | 6/9 | [scores.json] |

Note: Z-Score of 14.49 is elevated [Inference: the market-value-of-equity / total-liabilities component is dominant at $2,008B / $90.0B = 22.3x] [Sources: scores.json].

# Appendix F: Risk Factors — Expanded

## 1. Customer Concentration

**AI XPU revenue concentration:** $8.4B quarterly AI semiconductor revenue (43.5% of total) from 6 XPU customers [transcript_segments.json: Hock Tan]. Per-customer revenue not disclosed in SEC filings [Data gap]. The 10-K discloses: top 5 end customers ~40% of total revenue through all channels (FY2025 and FY2024) [EDGAR: 10-K FY2025].

**Revenue impact estimate:** If the largest customer (likely Google, with analyst Rasgon estimating ~3 GW of ~10 GW total) represents ~25% of AI revenue, a 50% reduction from that customer would equal ~$1.05B/quarter or ~$4.2B annually, approximately 5.4% of the annualized Q1 run rate [Inference: assumes top customer = ~25% of AI revenue] [Sources: transcript.json].

**Correlated demand risk:** All 6 XPU customers are hyperscale AI infrastructure buyers. A macro-driven AI capex pause would affect all customers simultaneously.

**Trend:** Customer count grew from 5 to 6 with OpenAI added in Q1 FY2026 [transcript.json: Hock Tan].

## 2. Cyclicality and Macro Sensitivity

**Revenue through prior cycles:**
| Period | Revenue ($B) | YoY Growth |
|--------|-------------|------------|
| FY2020 (COVID) | $23.9 | +5.7% |
| FY2023 (semi downturn) | $35.8 | +7.9% |
| FY2025 (AI ramp) | $63.9 | +23.9% |

[income.json]

Beta: 1.44 [info.json]. 52-week range: $234.43–$442.36 (89% peak-to-trough) [quote.json].

**Current AI cycle risk:** AI revenue growing 106% YoY (Q1 FY2026), guided 140% YoY (Q2). These growth rates are historically anomalous. No hyperscaler has publicly disclosed ROI from AI infrastructure at current spending levels. CEO Tan addressed this indirectly: customers are "on the path to...productizing and monetizing their LLMs" [transcript.json: Hock Tan].

## 3. Technology and Disruption Risk

**GPU competition:** NVIDIA data center revenue $75.2B in Q1 FY2027 exceeds AVGO's entire FY2025 revenue ($63.9B) [Contradicted C022: $75.2B not $75.3B]. Vera Rubin promises "up to 10x more performance per watt" for specific inference workloads [Verified C031].

**Customer-owned tooling (COT):** Analyst Harlan Sur (JPMorgan) raised the risk. CEO Tan: "We will not see competition in COT for many years to come. It will come eventually" [transcript.json: Hock Tan, Q&A]. Note: Sur's assertion that COT designs are "at least 2x less performant" is the analyst's opinion, not a confirmed fact [transcript.json: analyst Harlan Sur (JPMorgan), question].

**Marvell threat:** MRVL custom ASIC ~$1.5B annualized vs. AVGO $33.6B annualized AI revenue (4.5% scale). Growing faster (>20% guided). Reportedly secured portion of Google TPU work [Corroborated C015]. NVIDIA $2B investment [Verified C017].

**CPO disruption:** Could displace Broadcom optical DSPs and SerDes. CEO Tan: CPO "will come in its time, not this year, maybe not next year" [transcript.json: Hock Tan].

## 4. Supply Chain Risk

**TSMC single-source:** "The majority" of front-end wafer manufacturing [EDGAR: 10-K FY2025]. No alternative foundry offers comparable advanced packaging (CoWoS) at scale. TSMC sold out through 2026 [ecosystem_signals.md].

**Taiwan geographic:** TSMC, ASE, SPIL headquartered in Taiwan. TSMC expanding to Arizona ($165B total, first 3nm fab H2 2027) [Verified C037]. Partially addresses geographic concentration over 2027-2028 timeframe.

**Middle East supply chain:** TSMC flagged specialty chemical/gas supply concerns from Middle East conflict [ecosystem_signals.md: CNBC, Apr 16, 2026]. Indirect risk to AVGO.

**No long-term contracts:** 10-K states "generally on a purchase order basis" [EDGAR: 10-K FY2025]. However, VP Ramachandran confirmed "long-term agreements...for as long as three to four years" for strategic components [Verified C096].

## 5. Execution and Integration Risk

**VMware integration:** Goodwill increased $54.2B (FY2023→FY2024) [balance.json]. Software operating margin expanding (78%, +190 bps YoY) [transcript_segments.json]. VMware TCV >$9.2B, ARR +19% YoY [transcript_segments.json: Hock Tan]. Post-acquisition pricing increases (up to 45% reported) create churn risk [claim_verification.json: C079]. No quantified churn data [Data gap].

**Key person risk:** CEO Hock E. Tan has led all major acquisitions. No succession plan details available [Data gap].

**Employee count discrepancy:** info.json description says 19,000 (outdated); fullTimeEmployees field says 37,000 [info.json].

## 6. Financial Risk

**Leverage:** Net Debt/EBITDA 1.41x (FY2025), down from 2.44x (FY2024) [Computed: balance.json, income.json]. Interest coverage 7.9x (FY2025) vs. 3.4x (FY2024) [income.json].

**SBC dilution:** SBC grew from $2.2B (6.1% of revenue, FY2023) to $7.6B (11.8%, FY2025) [cashflow.json]. Diluted shares grew 13.7% over 2 years (FY2023→FY2025, 4,270M → 4,853M) [income.json]. P/FCF-ex-SBC of 103.3x vs. headline P/FCF of 74.2x.

**AR/revenue divergence:** FY2025 AR grew 61.8% vs. revenue 23.9%. DSO expanded from 31.3 to 40.8 days (+30%) [balance.json, income.json, metrics.json]. The divergence warrants monitoring. [Inference: partially a mix effect from higher Q4 revenue run rate, but the $2.7B AR build suggests real term changes] [Sources: balance.json, income.json, cashflow.json].

**Tax rate volatility:** FY2021: 0.4%, FY2022: 7.5%, FY2023: 6.7%, FY2024: 37.8%, FY2025: -1.7% [ratios.json]. FY2025 negative rate inflated net income by ~$4.1B vs. normalized 16.5%. CFO guided 16.5% for Q2 FY2026 [transcript.json: Kirsten Spears].

**Working capital drain:** Accelerating: FY2021 −$0.1B → FY2022 −$1.7B → FY2023 −$1.6B → FY2024 −$4.6B → FY2025 −$8.5B [cashflow.json]. FY2025 includes −$2.7B AR, −$0.5B inventory, −$5.2B "other working capital" [cashflow.json].

## 7. Regulatory and Geopolitical Risk

**Export controls:** Advanced AI semiconductors subject to U.S. EAR restrictions. Primary customers are U.S.-based hyperscalers, limiting direct China exposure. Tariff/trade policy changes could affect broader semiconductor pricing [EDGAR: 10-K FY2025 risk factors].

**Geographic revenue:** Not available (FMP segments API returned 404) [Data gap].

## 8. Insider Activity

| Insider | Role | Date | Shares | Price | Value | Remaining | Source |
|---------|------|------|--------|-------|-------|-----------|--------|
| Henry Samueli | Director | 2026-03-25 | 223,402 sold | $317-321 | ~$71.3M | ~37.0M (indirect) | [insider.json] |
| S. Ram Velaga | President ISG | 2026-04-08-10 | 38,215 sold | $352-371 | ~$13.5M | 57,932 | [insider.json] |
| Charlie Kawwas | President SSG | 2026-04-08 | 10,000 sold | $345 | ~$3.5M | 787,184 (indirect) | [insider.json] |
| Hock E. Tan | CEO | 2026-04-08 | 22,000 gifted | — | $0 | 110,836 (direct) | [insider.json] |

No insider purchases in the available window. Samueli's $71.3M sale = 0.46% of ~$15.6B remaining position.

## 9. Notable Non-Disclosures (Negative Space)

- Broadcom does not disclose per-customer revenue in SEC filings, while the AI revenue is concentrated among 6 named customers
- Broadcom does not report AI revenue in SEC filings as a separate line item — only in quarterly earnings call commentary
- Geographic revenue breakdown not separately available from FMP data
- VMware churn rate post-pricing changes not disclosed
- No specific TSMC CoWoS allocation data disclosed
- Custom ASIC vs. GPU allocation ratio not disclosed by any hyperscaler
- Proxy statement parsing error prevented governance and compensation analysis [proxy.json: error]

## 10. Management Deflections (Transcript)

- When asked about rack-level gross margins by analyst Timothy Arcuri (UBS), CEO Tan dismissed the premise rather than providing data: "you must be a bit hallucinating" [transcript.json: Hock Tan]
- When asked about chip vs. rack revenue breakdown by analyst Vivek Arya (BofA), CEO Tan declined: "I'd rather not answer that" [transcript.json: Hock Tan]
- When asked about $100B+ target composition, CEO Tan stated it was "pretty much all based on chips" without providing a precise chip/rack split [transcript.json: Hock Tan, Q&A with Blayne Curtis]

# Appendix G: Transcript Highlights — Key Management Quotes by Topic

Source: Q1 FY2026 Earnings Call (reported March 4, 2026). Speakers: Hock Tan (CEO), Kirsten Spears (CFO), Charlie Kawwas (President, Semiconductor Solutions Group).

---

## AI Revenue and Growth

**Hock Tan (CEO), prepared remarks:**
> "In our fiscal Q1 2026, total revenue reached a record $19.3 billion, and that's up 29% year-on-year and exceeding our guidance on the back of stronger than expected AI semiconductor revenue."

**Hock Tan, on AI revenue:**
> "AI semiconductor revenue of $8.4 billion was up 106% year-on-year, and our custom accelerator business grew 140% year-on-year."

**Hock Tan, on AI networking:**
> "Q1 AI networking revenue grew 60% year-on-year and represented 1/3 of total AI revenue."

**Hock Tan, on FY2027 target:**
> "We have line of sight to achieve AI revenue from chips, just chips, in excess of $100 billion in 2027."

[transcript_segments.json: Hock Tan]

---

## Custom XPU Customers

**Hock Tan, on 6 customers:**
> "We also now have a sixth customer. We expect OpenAI deploying in volume their first-generation XPU in 2027 at over 1 gigawatt."

**Hock Tan, on Anthropic:**
> "Anthropic is off to a very good start in 2026 for 1 gigawatt of TPU compute. For '27, demand expected to surge in excess of 3 gigawatts."

**Hock Tan, on Meta:**
> "Meta's custom accelerator MTIA road map is alive and well. We're shipping now...will scale to multiple gigawatts in '27."

**Hock Tan, on scale confirmation (Q&A with Stacy Rasgon, Bernstein):**
> "If you look at it by gigawatt in '27, we are seeing it getting close to 10 gigawatts."

**Stacy Rasgon (analyst, Bernstein), question:** Asked about ~$20B/GW content.
**Hock Tan, response:** "You're right, it's not far from the dollars you're talking about."

[transcript_segments.json: Hock Tan; transcript.json: Q&A section]

---

## Competitive Position and COT

**Harlan Sur (analyst, JPMorgan), question:** "There's been a lot of noise around CSPs and hyperscalers embarking on their own internal XPU, TPU design efforts, right? We call it COT, or customer-owned tooling."

**Hock Tan, response:**
> "We will not see competition in COT for many years to come. It will come eventually, but we're still a long way off."

**Hock Tan, on differentiation:**
> "We bring to the partnerships unmatched technology in SerDes, silicon design, process technology, advanced packaging and networking to enable each of these customers to achieve optimal performance."

**Hock Tan, on production capability:**
> "Anybody can design a chip in a lab that works well. Can you produce 100,000 of those chips quickly at yields that you can afford? And we don't see too many players in the world that can do that."

**Hock Tan, on GPU vs. XPU (Q&A with C.J. Muse):**
> "The one size fits all of a general purpose GPU gets you only that far...XPUs will eventually be more the choice simply because it will allow flexibility in making designs that work with particular workloads."

[transcript.json: Hock Tan, Q&A]

---

## Supply Chain and Capacity

**Hock Tan, on supply secured:**
> "We have fully secured capacity of these components for '26 through '28."

**Charlie Kawwas, on supply commitments:**
> "We have to go secure it for multiple years and we're probably the first one to secure that up to '28 or beyond."

**Hock Tan, on T-glass substrates:**
> "We were early in being able to lock up T-glass."

**Hock Tan, on TSMC bottleneck (industry event, March 2026):**
> Referenced in supplier_capacity.md: "They will be increasing the capacity to 2027, but that has become a bottleneck, or that has kind of choked the supply chain in 2026."

[transcript.json: Hock Tan, Charlie Kawwas; supplier_capacity.md]

---

## Networking Strategy

**Hock Tan, on Tomahawk:**
> "Tomahawk 6 operates at 100 terabit per second with 200G SerDes, and we are first-to-market."

**Hock Tan, on optical DSPs:**
> "We are again the only player out there doing DSP at 1.6 terabit."

**Charlie Kawwas, on Ethernet:**
> "Ethernet is the scale-out of choice" and XPU designs are "being asked to scale-up through Ethernet."

**Hock Tan, on CPO (co-packaged optics):**
> "CPO will come in its time, not this year, maybe not next year."

[transcript_segments.json; transcript.json: Q&A]

---

## VMware / Infrastructure Software

**Hock Tan, on VCF:**
> VCF is "the permanent abstraction layer between AI software and physical chips, silicon" that "cannot be disintermediated or replaced."

**Hock Tan, on VMware TCV:**
> "Total contract value booked in Q1 exceeded $9.2 billion, sustaining ARR growth of 19% year-on-year."

[transcript_segments.json: Hock Tan]

---

## Financial Guidance and Margins

**Kirsten Spears (CFO), prepared remarks:**
> "Revenue for our Semiconductor Solutions segment was a record $12.5 billion, with growth accelerating to 52% year-on-year."
> "Revenue for Infrastructure Software of $6.8 billion was up 1% year-on-year."
> "Gross margin for Infrastructure Software was 93% in the quarter."
> "Semiconductor operating margin of 60% was up 260 basis points year-on-year, reflecting strong operating leverage."
> "Q1 software operating margin was up 190 basis points year-on-year to 78%."
> "Free cash flow in the quarter was $8 billion and represented 41% of revenue."
> "Adjusted EBITDA of $13.1 billion or 68% of revenue."

**Kirsten Spears, Q2 guidance:**
> "We expect consolidated gross margin to be flat sequentially at 77%."
> "We expect adjusted EBITDA to be approximately 68% of revenue."
> Non-GAAP tax rate: "approximately 16.5% due to the impact of the global minimum tax."
> Diluted shares: "approximately 4.94 billion, excluding the impact of potential share repurchases."

**Hock Tan, on rack-level margins (Q&A with Timothy Arcuri, UBS):**
> "Hate to tell you that you must be a bit hallucinating. Our gross margin is solidly at the number Kirsten reported."

**Kirsten Spears, on rack margins:**
> "The impact relative to our overall mix is actually not going to be substantial at all."

**Hock Tan, on chip vs. rack breakdown (Q&A with Vivek Arya, BofA):**
> "I'd rather not answer that."

[transcript_segments.json; transcript.json: Q&A]

---

## Capital Allocation

**Kirsten Spears, on Q1 returns:**
> Dividends of $3.1B and buybacks of $7.8B. Dividend per share: $0.65.

**Kirsten Spears, on buyback:**
> Board authorized new repurchase program effective through end of calendar year 2026.

[transcript.json: Kirsten Spears]

---

## Analyst Questions with Non-Specific or Deflected Answers

1. **Chip vs. rack revenue split** — CEO Tan declined to answer (Vivek Arya question).
2. **Rack-level gross margin quantification** — CEO Tan dismissed premise (Timothy Arcuri question).
3. **Per-customer revenue concentration** — Not addressed despite multiple customer-level questions.
4. **TSMC CoWoS allocation specifics** — Not disclosed.

# Appendix H: Source Index

## Source Files Used in This Report

| # | File | Provider | Data Date | Reliability Tier | Usage |
|---|------|----------|-----------|-----------------|-------|
| 1 | raw/info.json | FMP | 2026-05-27 | Tier 2 (Financial API) | Company profile, price, market cap, employees, beta |
| 2 | raw/quote.json | FMP | 2026-05-26 | Tier 2 (Financial API) | Current price, market cap, 52-week range |
| 3 | raw/income.json | FMP | Period end 2025-11-02 | Tier 2 (Financial API) | Revenue, margins, EBITDA, EPS, D&A, R&D, interest expense, tax |
| 4 | raw/balance.json | FMP | Period end 2025-11-02 | Tier 2 (Financial API) | Debt, cash, goodwill, intangibles, assets, equity, AR, inventory, deferred revenue |
| 5 | raw/cashflow.json | FMP | Period end 2025-11-02 | Tier 2 (Financial API) | OCF, capex, FCF, SBC, dividends, buybacks, working capital |
| 6 | raw/metrics.json | FMP | Period end 2025-11-02 | Tier 2 (Financial API) | ROIC, DSO, DIO, DPO, CCC, FCF yield, SBC/revenue, intangibles/assets |
| 7 | raw/ratios.json | FMP | Period end 2025-11-02 | Tier 2 (Financial API) | Margins, tax rate, leverage ratios, dividend data |
| 8 | raw/earnings.json | FMP | Through 2026-06-03 | Tier 2 (Financial API) | Quarterly EPS and revenue actuals vs. estimates |
| 9 | raw/ratings.json | FMP | 2026-05-27 | Tier 2 (Financial API) | Consensus revenue/EPS estimates, price targets |
| 10 | raw/enterprise_value.json | FMP | Period end 2025-11-02 | Tier 2 (Financial API) | Historical enterprise value at filing-date prices |
| 11 | raw/shares_float.json | FMP | 2026-05-27 | Tier 2 (Financial API) | Outstanding shares, float, free float % |
| 12 | raw/technicals.json | FMP | 2026-05-26 | Tier 2 (Financial API) | RSI, EMA, SMA, ADV, volume |
| 13 | raw/scores.json | FMP | 2026-05-27 | Tier 2 (Financial API) | Altman Z-Score, Piotroski Score |
| 14 | raw/dcf.json | FMP | 2026-05-26 | Tier 2 (Financial API) | FMP DCF model estimate |
| 15 | raw/insider.json | FMP | 2026-05-27 | Tier 2 (Financial API) | Insider transactions |
| 16 | raw/peers.json | FMP | 2026-05-27 | Tier 2 (Financial API) | Peer company list |
| 17 | raw/peer_compare.json | FMP | 2026-05-27 | Tier 2 (Financial API) | Peer company profiles (AMD, etc.) |
| 18 | raw/segments.json | FMP | 2026-05-27 | Tier 2 (Financial API) | Empty (404 error) |
| 19 | raw/short_interest.json | FMP | 2026-05-27 | Tier 2 (Financial API) | Empty (404 error) |
| 20 | raw/dividends.json | FMP | 2026-05-27 | Tier 2 (Financial API) | Empty (404 error) |
| 21 | raw/transcript.json | FMP | Q1 FY2026 | Tier 3 (Transcript) | Earnings call: Hock Tan, Kirsten Spears, Charlie Kawwas, analyst Q&A |
| 22 | raw/transcript_segments.json | FMP | Q1 FY2026 | Tier 3 (Transcript) | Segment-specific transcript excerpts |
| 23 | raw/transcript_competitors.json | FMP | Q1 FY2026 | Tier 3 (Transcript) | Competitor mentions in transcript |
| 24 | raw/presentations.json | Company IR | 2026-05-27 | Tier 1 (Company Disclosure) | Investor presentations and IR events |
| 25 | raw/facts.json | EDGAR | 2026-05-27 | Tier 1 (SEC Filing) | XBRL concept data |
| 26 | raw/filings.json | EDGAR | 2026-05-27 | Tier 1 (SEC Filing) | SEC filings list |
| 27 | raw/filing_search.json | EDGAR | 2026-05-27 | Tier 1 (SEC Filing) | EDGAR full-text search results |
| 28 | raw/filing_events.json | EDGAR | 2026-05-27 | Tier 1 (SEC Filing) | 8-K material events |
| 29 | raw/edgar_search_risks.json | EDGAR | 2026-05-27 | Tier 1 (SEC Filing) | Risk factor search results |
| 30 | raw/convertible_search.json | EDGAR | 2026-05-27 | Tier 1 (SEC Filing) | Convertible notes EFTS search |
| 31 | raw/proxy.json | EDGAR | Filed 2026-03-02 | Tier 1 (SEC Filing) | DEF 14A (parsing error, empty) |
| 32 | raw/insider_detail.json | EDGAR | 2026-05-27 | Tier 1 (SEC Filing) | Form 4 transactions |
| 33 | raw/holders_detail.json | EDGAR | 2026-05-27 | Tier 1 (SEC Filing) | 13F institutional ownership |
| 34 | raw/latest_10k_text.txt | EDGAR | FY2025 (filed 2025-12-18) | Tier 1 (SEC Filing) | 10-K full text (partial) |
| 35 | raw/business_overview.md | Serper (Web) | 2026-05-27 | Tier 4 (Web Research) | Business description, acquisition history |
| 36 | raw/segment_financials.md | Serper (Web) | 2026-05-27 | Tier 4 (Web Research) | Segment revenue data |
| 37 | raw/competitive_by_product.md | Serper (Web) | 2026-05-27 | Tier 4 (Web Research) | Product-level competitive landscape |
| 38 | raw/competitive_history.md | Serper (Web) | 2026-05-27 | Tier 4 (Web Research) | Competitive landscape evolution |
| 39 | raw/competitor_data.md | Serper (Web) | 2026-05-27 | Tier 4 (Web Research) | Competitor financial comparisons |
| 40 | raw/customer_alternatives.md | Serper (Web) | 2026-05-27 | Tier 4 (Web Research) | Switching costs, Porter's analysis |
| 41 | raw/customer_capex.md | Serper (Web) | 2026-05-27 | Tier 4 (Web Research) | Hyperscaler capex guidance |
| 42 | raw/ecosystem_signals.md | Hermes | 2026-05-27 | Tier 4 (Web Research) | MRVL, NVDA, TSMC peripheral signals |
| 43 | raw/backlog_breakdown.md | Serper (Web) | 2026-05-27 | Tier 4 (Web Research) | Backlog data |
| 44 | raw/supplier_capacity.md | Serper (Web) | 2026-05-27 | Tier 4 (Web Research) | TSMC capacity constraints |
| 45 | raw/supply_demand.md | Serper (Web) | 2026-05-27 | Tier 4 (Web Research) | Supply/demand indicators |
| 46 | raw/supply_indicators.md | Serper (Web) | 2026-05-27 | Tier 4 (Web Research) | Backlog and capacity data |
| 47 | raw/revenue_mix.md | Serper (Web) | 2026-05-27 | Tier 4 (Web Research) | Revenue mix breakdown |
| 48 | raw/value_chain.md | Serper (Web) | 2026-05-27 | Tier 4 (Web Research) | Value chain structure |
| 49 | raw/convertible_detail.md | Serper (Web) | 2026-05-27 | Tier 4 (Web Research) | Debt details |
| 50 | raw/short_interest.md | Serper (Web) | 2026-05-27 | Tier 4 (Web Research) | Short interest data |
| 51 | raw/press_releases.md | Serper (Web) | 2026-05-27 | Tier 4 (Web Research) | Recent press releases |
| 52 | raw/company_ir.md | Serper (Web) | 2026-05-27 | Tier 4 (Web Research) | IR page information |
| 53 | raw/claim_verification.json | Derived | 2026-05-27 | Derived | Confidence tags for 135 web-sourced claims |

## Reliability Tier Definitions

1. **Tier 1 — SEC filings and company announcements:** 10-K, 10-Q, proxy statements, company IR, press releases. Highest confidence.
2. **Tier 2 — Standardized financial APIs:** FMP-derived financial statements, metrics, ratios, quotes. Derived from filings.
3. **Tier 3 — Earnings transcripts:** Management statements and analyst questions. Narrative-shaped; speaker attribution required.
4. **Tier 4 — Third-party research:** Expert calls, industry research, web search results. Verify against higher tiers.
5. **Tier 5 — News, blogs, commentary:** Context only. Not primary evidence.

## Claim Verification Summary

135 web-sourced claims checked:
- **Verified:** 64 (47%)
- **Corroborated:** 37 (27%)
- **Single-Source:** 14 (10%)
- **Contradicted:** 10 (7%)
- **Unverifiable:** 10 (7%)

[claim_verification.json]

## Key Contradicted Claims

| Claim ID | Claim | Issue | Resolution |
|----------|-------|-------|------------|
| C022 | NVDA Q1 FY2027 data center revenue | $75.3B vs $75.2B cited across sources | Use $75.2B per NVDA earnings release |
| C029 | NVDA-Groq acquisition total | $13B vs $20B | Total was $20B ($13B upfront + earnouts) |
| C074 | AVGO days-to-cover | 2.1 vs 2.6 | Varies by volume averaging window |

## Key Unverifiable Claims

| Claim ID | Claim | Issue |
|----------|-------|-------|
| C038 | AVGO depends on TSMC for ~95% of wafers | 10-K says "the majority" without quantification |
| C043 | NVDA occupies ~50% of TSMC CoWoS capacity | TSMC does not disclose customer-level allocation |
| C045 | AVGO has no long-term supplier agreements | 10-K uses "generally on a purchase order basis" but VP confirmed 3-4 year agreements for strategic components |

## Data Not Available

- FMP segments.json: 404 error (segment revenue by FMP API)
- FMP short_interest.json: 404 error
- FMP dividends.json: 404 error
- EDGAR proxy.json: parsing error (DEF 14A text empty)
- Geographic revenue breakdown: not available
- Debt maturity schedule by year: not extracted from 10-K
- Per-customer revenue concentration: not disclosed by Broadcom
- Patent portfolio: raw/patents.json not present
- Congressional trading: FMP API 404
