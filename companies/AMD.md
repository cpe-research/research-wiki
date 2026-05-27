---
type: company
ticker: AMD
name: AMD
updated: "2026-05-27"
sources:
  - info.json
  - value_chain.md
  - segments.json
  - insider.json
  - holders.json
  - transcript_competitors.json
---

# AMD (AMD)

## Competitors

- [AVGO](AVGO.md) (AVGO)
- [NVIDIA Corporation](NVDA.md) (NVDA)

## Key Insiders

- Norrod Forrest Eugene (officer: EVP & GM DESG)
- Papermaster Mark D (officer: Chief Technology Officer & EVP)
- Su Lisa T (director, officer: Chair, President & CEO)

## Top Institutional Holders

- BNP PARIBAS FINANCIAL MARKETS
- BRIGADE CAPITAL MANAGEMENT, LP
- Blankinship & Foster, LLC
- COATUE MANAGEMENT LLC
- MAPLELANE CAPITAL, LLC
- MUFG Securities EMEA plc
- Mizuho Markets Cayman LP
- Modern Wealth Management, LLC
- Oak Grove Capital LLC
- Platinum Management (NY) LLC

---

> **⚠️ DRAFT — this report did not pass the citation audit.** Some claims may lack source verification. Treat as preliminary research.

# Advanced Micro Devices, Inc. (AMD) — Research Report

**Report Date:** May 27, 2026
**Data As Of:** May 27, 2026 (price), FY2025 (annual ending Dec 27, 2025) for annual financials, Q1 FY2026 (ending Mar 29, 2026) for most recent quarter
**Ticker:** AMD | NASDAQ Global Select | Technology | Semiconductors
**Price:** $503.89 [info.json: price]
**ADV:** $19,200MM [info.json: averageVolume (38,103,470) × price ($503.89)]
**Market Cap:** $821.6B [info.json: marketCap]
**Net Debt:** -$6.1B (-0.7% of mkt cap) [balance.json: totalDebt ($4,472M) − cashAndShortTermInvestments ($10,552M)]
**Net Cash:** $6.1B (0.7% of mkt cap) [balance.json: cashAndShortTermInvestments ($10,552M) − totalDebt ($4,472M)]
**Enterprise Value:** $820.6B [Computed: $821.6B mkt cap + $4.5B debt − $5.5B cash; consistent with enterprise_value.json methodology]
**Short Interest:** ~2.2% of float (~36.1M shares short / 1,621.9M float) [short_interest.md: shortsqueeze.com (Tier 5); shares_float.json: floatShares]

---

<!-- Section 1 answers: What does this company do, how is it organized, and how large is each piece? Would change if: major divestiture, acquisition, segment reclassification, or revenue mix shift. -->
## 1. Business Overview

Advanced Micro Devices, Inc. (AMD) is a fabless semiconductor company headquartered in Santa Clara, California, with 28,000 full-time employees [info.json: fullTimeEmployees]. AMD designs x86 CPUs, GPUs, FPGAs, and adaptive SoCs, outsourcing all manufacturing to third-party foundries. CEO: Lisa T. Su [info.json: ceo]. IPO: September 7, 1972 [info.json: ipoDate].

### Segment Structure

AMD reports three business segments following the February 2022 Xilinx acquisition reorganization: **Data Center**, **Client and Gaming**, and **Embedded** [claim_verification.json: C040, Verified].

| Segment | FY2025 Revenue | % of FY2025 Total | Q1 FY2026 Revenue | Q1 % of Total | Q1 YoY Growth |
|---|---|---|---|---|---|
| Data Center | $16.6B | 47.9% | $5.8B | 56.6% | +57% |
| Client and Gaming | $14.6B | 42.1% | $3.6B | 35.1% | +23% |
| Embedded | $3.5B | 10.1% | $0.85B (residual) | ~8.3% | ~+4% |
| **Total** | **$34.639B** | **100%** | **$10.253B** | **100%** | **+38%** |

[Sources: income.json: revenue FY2025 ($34,639M); claim_verification.json: C042 (DC), C041/C043 (C&G), C074 (Embedded); earnings.json: Q1 FY2026 revenueActual ($10,253M); transcript_segments.json: Jean Hu Q1 2026 prepared remarks (DC $5.8B, C&G $3.6B)]

**Segment sum check:** $16.6B + $14.6B + $3.5B = $34.7B vs. reported $34.639B — $61M rounding gap [Computed].

**Q1 FY2026 Embedded revenue:** $10.253B − $5.8B − $3.6B = $0.853B [Inference: computed as residual from total minus disclosed segments] [Sources: earnings.json, transcript_segments.json].

### Key Products by Segment

**Data Center (56.6% of Q1 2026 revenue):** EPYC server CPUs (5th-gen "Turin"), Instinct GPUs (MI325X, MI355X shipping; MI450/MI500 in pipeline), Pensando DPUs/SmartNICs, ROCm software stack, Helios rack-scale platform [transcript_segments.json: Lisa Su Q1 2026; info.json: description].

**Client and Gaming (35.1% of Q1 2026 revenue):** Client sub-segment ($2.9B Q1 2026, +26% YoY) includes Ryzen desktop/notebook CPUs and Ryzen AI processors [claim_verification.json: C035, Verified]. Gaming sub-segment ($720M Q1 2026, +11% YoY) includes Radeon discrete GPUs and semi-custom console SoCs for Sony PlayStation and Microsoft Xbox [transcript.json: Jean Hu].

**Embedded (8.3% of Q1 2026 revenue):** Versal Adaptive SoCs/FPGAs, Zynq SoCs, EPYC/Ryzen Embedded processors (Xilinx legacy) [info.json: description]. Operating margin: 39% ($338M on $873M) in Q1 2026 [transcript.json: Jean Hu].

### Revenue Mix: Narrative vs. Reality

AMD does not disclose a single "AI revenue" figure. The Data Center segment ($16.6B FY2025, $5.8B Q1 2026) includes both AI and non-AI products (EPYC CPUs for general-purpose cloud alongside Instinct GPUs for AI workloads) [transcript_segments.json: Lisa Su]. Instinct GPU-specific revenue is not disclosed separately [Data Gap].

- Data Center grew from 47.9% of FY2025 revenue to 56.6% of Q1 2026 revenue [Inference: Data Center overtook Client and Gaming as the largest segment during FY2025] [Sources: income.json, transcript_segments.json, claim_verification.json C042]
- Lisa Su stated: "Data center is now the primary driver of our revenue and earnings growth" [transcript.json: Lisa Su, Q1 2026 prepared remarks]
- One estimate places Instinct GPU revenue at ">$5 billion in 2024" [claim_verification.json: C091, Single-Source: financial commentary estimate, not confirmed in AMD SEC filings]
- NVIDIA Q1 FY2027 Data Center revenue ($75.2B) is ~13x AMD's Q1 2026 Data Center revenue ($5.8B) [claim_verification.json: C007, Verified]

### Brief History

AMD was founded in 1969 and IPO'd in 1972 as a second-source x86 processor manufacturer. The company's most significant structural event was the $49B all-stock acquisition of Xilinx, completed February 2022, which added the Embedded segment and approximately doubled AMD's revenue base [claim_verification.json: C040, Verified]. AMD also acquired Pensando Systems in May 2022 (~$1.9B) for DPU/SmartNIC technology [competitive_history.md].

---

<!-- Section 2 answers: For each product, who competes with this company and what are their relative strengths? Would change if: loss of a top customer, entry of a well-capitalized competitor (e.g., NVIDIA Vera CPU is already happening), customer building in-house alternatives. Base rate: the semiconductor industry has seen significant competitive position shifts in CPUs (AMD's own rise from ~5% to 46% server share in 5 years). -->
## 2. Competitive Position

### EPYC Server CPUs

AMD held **46.2% server CPU revenue share** in Q1 2026 per Mercury Research [claim_verification.json: C012, Corroborated: 5 independent sources]. Unit share was **33.2%** [claim_verification.json: C066], implying AMD ships higher-ASP CPUs than Intel on average [Inference: revenue share > unit share] [Sources: claim_verification.json C012, C066]. Server CPU revenue grew >50% YoY in Q1 2026 (4th consecutive quarter of record revenue) [transcript.json: Lisa Su].

**Named competitors:**
- **Intel:** Direct x86 competitor. Intel's server CPU market share has been declining as AMD's rose. Intel is "improving its supply" and "restarting 7-nanometer" per analyst questions on AMD's call [transcript.json: analyst Joshua Buchalter, question; analyst Blayne Curtis, question].
- **NVIDIA Vera CPU:** NVIDIA launched a server CPU targeting a "$200B agentic AI CPU market," expecting "~$20B in CPU revenue in FY2027" [claim_verification.json: C008, Corroborated]. One analyst projects NVIDIA could "capture two-thirds of the x86 server CPU market" [claim_verification.json: C011, Corroborated: Tom's Hardware]. Note: claim_verification.json flags Vera is ARM-based, making "x86 market" framing potentially misleading.
- **ARM-based alternatives:** AWS Graviton, Google Axion, Microsoft Cobalt, Ampere Computing. Lisa Su characterized ARM as "more point products relative to a portfolio" [transcript.json: Lisa Su, Q&A response to Aaron Rakers].

AMD's stated server CPU TAM doubled from $60B to ">$120 billion by 2030" within ~6 months, attributed to Agentic AI CPU requirements [claim_verification.json: C076, Corroborated]. This is a company-estimated TAM; no independent third-party research firm has published a comparable figure in the available data.

### Instinct AI GPUs

AMD's Data Center segment ($5.8B Q1 2026) includes both EPYC CPUs and Instinct GPUs. NVIDIA's Q1 FY2027 Data Center revenue was $75.2B (~13x AMD's) [claim_verification.json: C007, Verified]. NVIDIA's AI data center GPU market share is estimated at 80-92%, with AMD at ~7% [claim_verification.json: C093, Unverifiable: precise share not disclosed by any company in SEC filings; multiple Tier 5 sources cite varying figures]. AMD targets ">80% CAGR for Instinct GPU revenue" in 2027 [transcript.json: Lisa Su, response to Joshua Buchalter].

NVIDIA's CUDA software ecosystem creates switching costs. AMD's ROCm is an open-source alternative with a smaller developer ecosystem. AMD has "significantly accelerated ROCm development cadence" [transcript.json: Lisa Su, prepared remarks].

### Gaming (Radeon + Semi-Custom)

Gaming sub-segment: $720M Q1 2026, +11% YoY [transcript.json: Jean Hu]. Semi-custom console revenue declined "as expected at this stage of the console cycle" [transcript.json: Lisa Su]. Gaming is declining in strategic importance relative to data center for both AMD and NVIDIA.

### Embedded (FPGAs/Adaptive SoCs)

Embedded: $873M Q1 2026, +6% YoY, returning to growth [transcript.json: Jean Hu; claim_verification.json: C074, Verified]. Operating margin: 39%. Competitors include Intel/Altera, Lattice Semiconductor, and Microchip Technology [Data Gap: FPGA market share data unavailable].

Full competitive analysis in Appendix A.

---

<!-- Section 3 answers: Is industry supply sufficient to meet demand at current prices, and when does that change? Would change if: major capacity announcement, demand shock, policy change (tariffs, export controls). Base rate: semiconductor supply/demand imbalances typically last 2-3 years before capacity catches up. -->
## 3. Supply/Demand Balance

### Demand

AMD does not disclose quantitative backlog data [claim_verification.json: C096, Verified]. Demand indicators:
- **Customer commitments:** OpenAI 6 GW GPU deployment agreement (Oct 2025) [claim_verification.json: C059, Verified]; Meta multi-gigawatt Instinct deployment [transcript.json: Lisa Su]
- **Revenue trajectory:** FY2023 $22.7B → FY2024 $25.8B → FY2025 $34.6B → Q1 FY2026 annualized ~$41.0B [income.json; earnings.json]
- **Customer capex:** Microsoft FY2026 capex forecast raised to $190B (+61% YoY) with shift toward "shorter-lived assets (CPUs and GPUs)" [ecosystem_signals.md]
- **Guidance:** Q2 FY2026 guided to ~$11.2B ± $300M (+46% YoY) [transcript.json: Jean Hu]
- **CPU-to-GPU ratio shift:** Lisa Su stated the ratio is shifting from "1:4 or 1:8" to "closer to 1:1" in agentic workloads [transcript.json: Lisa Su, Q&A response to Vivek Arya]. This is a management forward-looking statement.

### Supply Constraints

1. **TSMC advanced nodes:** Capacity "very tight" and "sold out" through 2026 [claim_verification.json: C023, Corroborated]. TSMC capex: $52B-$56B in 2026, up 32% at midpoint [claim_verification.json: C054, Corroborated].
2. **CoWoS packaging:** AMD has ~11% of TSMC's CoWoS allocation [claim_verification.json: C021, Single-Source: analyst estimate, not TSMC disclosure]. NVIDIA has a larger share as TSMC's largest customer.
3. **HBM memory:** "Sold out through 2026" from SK Hynix and Micron [claim_verification.json: C084, Corroborated]. Lisa Su: "secured enough supply to certainly meet and exceed our targets" [transcript.json: Lisa Su, Q&A response to Vivek Arya].
4. **Data center power:** Lisa Su: "there is tightness in sort of data center build-outs" but "much more power coming online in 2027" [transcript.json: Lisa Su, Q&A response to Thomas O'Malley].

### Net Balance

Lisa Su: "The supply chain is tight. I would definitely say that" [transcript.json: Lisa Su, Q&A response to Blayne Curtis]. AMD's smaller TSMC allocation (~11% of CoWoS vs. NVIDIA's larger share) creates an asymmetric constraint [Inference: AMD may be more supply-limited relative to demand than NVIDIA, based on relative TSMC allocation sizes] [Sources: ecosystem_signals.md, claim_verification.json C021]. AMD's inventory build to $7.9B (FY2025, +38% YoY) is consistent with buffer-stock strategy in a constrained environment [balance.json: inventory].

Full supply/demand analysis in Appendix B.

---

<!-- Section 4 answers: Where is value captured, and is it migrating toward or away from this company? Would change if: vertical integration by customer or supplier, margin compression, technology enabling disintermediation. Base rate: fabless semiconductor value chain positions have been stable over 10+ years, though AI is shifting margin toward NVIDIA and TSMC. -->
## 4. Value Chain

### Position

AMD occupies the **chip design** stage of the semiconductor value chain in a fabless model. All manufacturing is outsourced to TSMC (wafer fabrication and advanced packaging), with assembly/test to OSAT partners [info.json: description; transcript.json].

### Key Upstream Dependencies

- **TSMC (critical single-source):** AMD's entire product line depends on TSMC. AMD is estimated as TSMC's 3rd-4th largest customer (~7% of TSMC revenue, ~11% CoWoS allocation) [claim_verification.json: C021, Single-Source]. Switching foundries for leading-edge products is not feasible near-term [Inference: based on foundry capability landscape] [Sources: ecosystem_signals.md, supplier_capacity.md].
- **HBM memory (3 vendors):** SK Hynix, Samsung, Micron. Supply is constrained but AMD has secured allocation [transcript.json: Lisa Su, Q&A response to Vivek Arya].
- **EDA tools:** Synopsys, Cadence (deeply embedded, high switching costs) [info.json: description].

### Key Downstream Relationships

Major customers include OpenAI, Meta, Microsoft, AWS, Google, Sony, and Microsoft (Xbox) [transcript.json: Lisa Su; press_releases.md]. Customer concentration data unavailable (10-K text not in dataset) [Data Gap].

### Margin Capture

| Entity | Gross Margin | Role |
|---|---|---|
| NVIDIA | ~75% | Chip design (GPU), CUDA lock-in [ecosystem_signals.md; claim_verification.json: C048, Corroborated] |
| TSMC | ~58-60% | Foundry [Inference: from ecosystem_signals.md net margin data] [Sources: ecosystem_signals.md] |
| AMD | 49.5% GAAP / ~54% non-GAAP | Chip design (CPU+GPU) [income.json; transcript.json] |
| Intel | ~40% (est.) | IDM — chip design + fab [Data Gap: not verified in this run] |

AMD's Instinct GPU margins are "below corporate average" [transcript.json: Jean Hu, Q&A response to Ross Seymore]. The ~21+ pp gross margin gap vs. NVIDIA reflects CUDA ecosystem pricing power and AMD's share-gaining strategy [Inference: margin gap driven by competitive positioning and HBM cost structure] [Sources: income.json, ecosystem_signals.md].

### Integration Direction

AMD is integrating **forward** via: (1) Helios rack-scale AI system (GPU+CPU integrated platform), sampling H2 2026 [transcript.json: Lisa Su]; (2) semi-custom co-design expanding from gaming consoles to data center (Meta custom MI450 GPU) [transcript.json: Lisa Su]; (3) ROCm software stack development [transcript.json: Lisa Su].

Full value chain analysis in Appendix C.

---

<!-- Section 5 answers: How does the company raise money to spend on its business? Would change if: major debt issuance/repayment, M&A financing, credit rating change, new equity issuance. -->
## 5. Capital Structure

| Component | Value | Source |
|---|---|---|
| **Equity** | Common stock, single class, no preferred | [balance.json: preferredStock = 0] |
| Shares outstanding | 1,630.6M | [shares_float.json: outstandingShares] |
| **Total Debt** | $4,472M | [balance.json: totalDebt, FY2025] |
| — Short-term debt | $874M | [balance.json: shortTermDebt] |
| — Long-term debt | $2,973M | [balance.json: longTermDebt] |
| — Capital lease obligations | $625M | [balance.json: capitalLeaseObligations] |
| **Convertible debt** | None identified outstanding | [convertible_search.json; convertible_detail.md] |
| **Cash & equivalents** | $5,539M | [balance.json: cashAndCashEquivalents] |
| **Cash + short-term investments** | $10,552M | [balance.json: cashAndShortTermInvestments] |
| **Minority Interest** | $0 | [balance.json: minorityInterest] |
| **Enterprise Value** | $820.6B | [Computed: mkt cap + debt − cash] |
| **Net Debt / EBITDA** | -0.84x | [Computed: ($4,472M − $10,552M) / $7,275M EBITDA; income.json: ebitda] |

FY2025 total debt increased $2,260M from FY2024 ($2,212M → $4,472M), including $1,491M net long-term debt issuance [cashflow.json: longTermNetDebtIssuance] and $874M new short-term debt [balance.json].

**Debt maturity schedule:** Not available without 10-K text [Data Gap].

**Share repurchase:** $9.2B remaining authorization; 1.1M shares repurchased in Q1 FY2026 ($221M returned) [transcript.json: Jean Hu]. Five-year cumulative buybacks (FY2021-FY2025): $10.4B [cashflow.json: commonStockRepurchased].

Full capital structure detail in Appendix D.

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

# Appendix A: Competitive Position — AMD

## Market Share and Trajectory

### Server CPUs (EPYC)
- AMD held 46.2% server CPU revenue share in Q1 2026 per Mercury Research [claim_verification.json: C012, Corroborated: 5 independent sources]
- Unit share: 33.2% in Q1 2026, up from 28.8% Q4 2025 and 27.2% Q1 2025 [claim_verification.json: C066]
- Revenue share exceeding unit share by ~13pp implies AMD ships higher-ASP CPUs than Intel [Inference: revenue share > unit share implies higher ASP mix] [Sources: claim_verification.json C012, C066]
- Server CPU revenue grew >50% YoY in Q1 2026, 4th consecutive quarter of record server CPU revenue [transcript.json: Lisa Su, prepared remarks]
- Revenue share trajectory: estimated ~20% in 2022 to 46.2% in Q1 2026 [Inference: directional from Mercury Research data across quarters] [Sources: claim_verification.json C012, C066]
- Lisa Su guided server CPU revenue to "grow by more than 70% year-over-year in the second quarter" [transcript.json: Lisa Su, prepared remarks]

### Data Center AI GPUs (Instinct)
- NVIDIA Q1 FY2027 DC revenue: $75.2B vs AMD Q1 2026 DC: $5.8B — ratio 13.0x [claim_verification.json: C007, Verified]
- AMD does not disclose Instinct-specific revenue within Data Center [Data Gap]
- Instinct accelerator revenue estimated to have "exceeded $5 billion in 2024" [claim_verification.json: C091, Single-Source: financial commentary estimate, not confirmed in AMD SEC filings]
- NVIDIA AI GPU market share estimated at 80-92%, AMD at ~7% [claim_verification.json: C093, Unverifiable: varies by source]
- NVIDIA DC revenue gap widened YoY: NVIDIA DC +92% YoY vs AMD DC +57% YoY in Q1 [ecosystem_signals.md]

### Client CPUs (Ryzen)
- Q1 2026 Client revenue: $2.9B, up 26% YoY [claim_verification.json: C035, Verified]
- Commercial PC sell-through of Ryzen Pro PCs increased >50% YoY in Q1 2026 [transcript.json: Lisa Su, prepared remarks]

### Gaming (Radeon + Semi-Custom)
- Gaming sub-segment: $720M Q1 2026, +11% YoY [transcript.json: Jean Hu, prepared remarks]
- Semi-custom console revenue declined YoY "as expected at this stage of the console cycle" [transcript.json: Lisa Su, prepared remarks]
- Discrete Radeon GPU revenue increased YoY [transcript.json: Lisa Su, prepared remarks]
- Jean Hu guided: "we expect second half gaming revenue to decline more than 20% compared to the first half" [transcript.json: Jean Hu, prepared remarks]

### Embedded (FPGAs/Adaptive SoCs)
- Revenue: $873M Q1 2026, +6% YoY, returning to growth after -3% FY2025 [transcript.json: Jean Hu; claim_verification.json C074, Verified]
- Operating margin: 39% ($338M) [transcript.json: Jean Hu]
- Design wins grew "by a double-digit percentage year-over-year with billions of dollars in new wins" [transcript.json: Lisa Su, prepared remarks]
- Primary competitors: Intel/Altera, Lattice Semiconductor, Microchip Technology [Data Gap: FPGA-specific market share data unavailable]

## TAM Analysis

### Server CPU TAM
- AMD increased its server CPU TAM estimate from "$60 billion by 2030" (Nov 2025 Analyst Day) to ">$120 billion by 2030" (Q1 2026 call, May 5, 2026) [claim_verification.json: C076, Corroborated]
- TAM doubled in ~6 months; attributed to Agentic AI CPU requirements [transcript.json: Lisa Su, Q&A response to Joshua Buchalter]
- AMD targets ">50% share" of this TAM [transcript.json: Lisa Su, Q&A]
- Lisa Su described this as "bottoms-up" customer forecasts and "workload analysis" [transcript.json: Lisa Su, Q&A]
- No independent third-party has published a comparable $120B server CPU TAM for 2030 in available data

### Data Center AI GPU TAM
- AMD targets ">80% CAGR for Instinct GPU revenue" in 2027 and "tens of billions of dollars in annual Data Center AI revenue in 2027" [transcript.json: Lisa Su, prepared remarks]
- No total GPU AI accelerator TAM figure stated by AMD this quarter
- Third-party estimate: AMD captures "10-15% data center AI market share by 2027" [claim_verification.json: C068, Single-Source: LinkedIn article, methodology not disclosed]

## Competitive Threats

### NVIDIA Entry into Server CPUs (Vera)
- NVIDIA launched Vera CPU targeting "$200B agentic AI CPU market," expecting "~$20B in CPU revenue in FY2027" [claim_verification.json: C008, Corroborated]
- Analyst: NVIDIA could "capture two-thirds of the x86 server CPU market" [claim_verification.json: C011, Corroborated: Tom's Hardware]
- NVIDIA Vera claims "1.5x faster" than alternatives [claim_verification.json: C009, Single-Source: NVIDIA CFO via Gotrade, not independently verified]
- Vera Rubin system (72 GPUs + 36 CPUs) competes directly with AMD Helios [ecosystem_signals.md]
- NVIDIA has $48.6B quarterly FCF [claim_verification.json: C005, Single-Source], existing DC customer relationships, and bundling capability (GPU+CPU systems)
- Note: claim_verification.json flags that Vera is ARM-based, making "x86 market" framing potentially misleading

### Hyperscaler In-House Silicon
- AWS: Graviton CPUs, Trainium/Inferentia AI chips
- Google: Axion CPUs, TPUs
- Microsoft: Cobalt CPUs, Maia AI chips
- Meta: developing custom silicon but also deploying AMD Instinct at multi-gigawatt scale [transcript.json: Lisa Su, prepared remarks]
- Lisa Su rebuttal: "even for those who are developing their own, they're still buying lots of CPUs in the merchant market" [transcript.json: Lisa Su, Q&A response to Ross Seymore]. This is management-stated and not independently verified with customer procurement data.

### Export Control Impact
- Q2 FY2025: ~$800M inventory charge from MI308 export controls [claim_verification.json: C110, Verified; AMD 8-K filing Aug 5, 2025]
- FY2025 net MI308 charges: ~$440M [claim_verification.json: C092, Verified]
- Q1 2026 China revenue "not material" [transcript.json: Jean Hu, Q&A response to Stacy Rasgon]

## Switching Costs and Customer Lock-in

### EPYC CPUs
- Technical switching: moderate (x86-to-x86 minimal software changes; x86-to-ARM requires porting and recompilation)
- Qualification cycles: 6-12 months for enterprise servers
- Evidence of switching: Turin crossed >50% of AMD server revenue in Q1 2026; 46.2% revenue share demonstrates successful migration from Intel [transcript.json: Lisa Su, Q&A response to Blayne Curtis]

### Instinct GPUs
- NVIDIA CUDA ecosystem is primary barrier; ROCm has smaller developer ecosystem
- Multi-generation customer commitments (OpenAI, Meta) create stickiness [transcript.json: Lisa Su, prepared remarks]
- Switching from CUDA to ROCm is harder than reverse; AMD focused on "day 0 support for leading open models" [transcript.json: Lisa Su]

### Semi-Custom (Console SoCs)
- 5-7+ year console generation contracts; sole supplier once designed in
- "Engagements with customers on next-generation platforms remain strong" [transcript.json: Lisa Su, prepared remarks]

### Embedded (FPGA/SoC)
- Design-in cycles: 12-24+ months; deeply integrated into customer systems
- "Billions of dollars in new design wins" in Q1 2026 [transcript.json: Lisa Su]

## Design Win Tracking

| Customer | Product | Timing | Source |
|---|---|---|---|
| OpenAI | 6 GW GPU deployment | Announced Oct 2025 | [claim_verification.json C059, Verified] |
| Meta | Multi-GW Instinct (custom MI450) | H2 2026 shipments | [transcript.json: Lisa Su] |
| Multiple cloud providers | EPYC Turin/Venice | Venice on track 2026 launch | [transcript.json: Lisa Su] |
| Embedded customers | "Billions in new wins across markets" | Q1 2026 | [transcript.json: Lisa Su] |

- Venice: "more customers validating and ramping platforms at this stage than with any prior EPYC generation" [transcript.json: Lisa Su]
- MI450/Helios: "Lead customer forecasts now exceeding our initial plans" [transcript.json: Lisa Su]

## ASP Trends
- Server CPU growth "much more unit driven" than ASP driven, but ASP increasing from higher core counts [transcript.json: Lisa Su, Jean Hu, Q&A response to Tim Arcuri]
- Some cost-driven price increases shared with customers: "we are sharing some of that with our customers" [transcript.json: Lisa Su]
- Revenue/unit share gap (46.2% vs 33.2%) implies AMD blended ASP ~1.39x Intel average [Inference: 46.2/33.2 = 1.39x relative ratio] [Sources: claim_verification.json C012, C066]
- Instinct GPU ASPs: not disclosed; MI450 margins "below corporate average" [transcript.json: Jean Hu, Q&A response to Ross Seymore]
- Client CPUs: mix shift toward higher-value notebook/AI PCs and commercial (Ryzen Pro +50% YoY) [transcript.json: Lisa Su]

## Silence Analysis

### Management Silence
- **Instinct GPU revenue not separately disclosed** — NVIDIA breaks out Data Center; AMD does not break GPU vs CPU within Data Center [Data Gap]
- **Customer concentration not disclosed** in transcript or available filings [Data Gap: 10-K text unavailable]
- **Geographic revenue:** Jean Hu deflected analyst Stacy Rasgon's question about Q1 China revenue specifics, stating only "not material" [transcript.json: Stacy Rasgon (Bernstein), question; Jean Hu, response]
- **Instinct gross margins:** Analyst C.J. Muse asked about driving Instinct margins "closer to your corporate average"; Jean Hu responded "at this stage, we really focus on driving the topline revenue growth" without providing margin specifics [transcript.json: C.J. Muse (Cantor Fitzgerald), question; Jean Hu, response]
- **OpEx forecasting:** Analyst Stacy Rasgon observed that "OpEx been so hard to forecast" with spending exceeding guidance; Jean Hu acknowledged investing in "go-to-market machine" [transcript.json]

### Filing Gaps
- 10-K text not available in this run — prevents analysis of risk factors, customer >10% disclosures, geographic breakdown
- Instinct-specific revenue not disclosed in any filing or transcript
- Backlog/bookings data not disclosed [claim_verification.json: C096, Verified]

## Peer Financial Benchmarking

| Metric | AMD | NVIDIA (est.) | Intel (est.) | ARM |
|---|---|---|---|---|
| Market Cap | $821.6B | ~$3.4T | ~$200B+ | $341.8B |
| FY Revenue | $34.6B | ~$165B+ (FY2026E) | ~$53B (FY2025) | ~$4B |
| Gross Margin | 49.5% (GAAP) | ~75% | ~40% | ~96% |
| Operating Margin | 10.7% (GAAP) | ~55% | Negative/low | ~25% |
| ROIC (FY2025) | 5.40% | ~100%+ | Negative | N/A |
| EV/Sales | ~23.7x | ~20x | ~2x | ~85x |

[Sources: income.json (AMD), quote.json (AMD mktcap), ecosystem_signals.md (NVIDIA rev/margins), peer_compare.json (ARM mktcap). Intel/NVIDIA estimates from ecosystem signals — Data Gap: full peer financials not in structured format]

Note: FMP-provided peers (peers.json: AMAT, ARM, ASML, KLAC, LRCX, MU, PLTR, QCOM, SAP, TXN) are mostly semiconductor supply chain companies, not direct product competitors. True competitive peers are NVDA and INTC [peers.json].

## Competition Evolution (5-Year)

| Year | Key Event | AMD Revenue | Context |
|---|---|---|---|
| FY2021 | Pre-Xilinx; AI nascent | $16.4B | ROIC: 37.0%; goodwill: $289M |
| FY2022 | Xilinx close; ChatGPT launch | $23.6B | Goodwill jumped to $24.2B; reorganized to 3 segments |
| FY2023 | Revenue declined -3.9% | $22.7B | PC/Embedded weakness; MI300 launching |
| FY2024 | DC becomes largest segment | $25.8B | DC: $12.6B; export controls impact MI308 |
| FY2025 | DC acceleration | $34.6B | DC: $16.6B; FY2025 +34.3% |
| Q1 2026 | NVIDIA enters CPU market | $10.3B (Q) | DC: $5.8B (56.6%); Vera CPU launched |

Market structure evolving from 2-competitor dynamics (AMD vs Intel in CPU, AMD vs NVIDIA in GPU) toward multi-axis competition: (1) NVIDIA competes in both GPUs and CPUs, (2) ARM-based CPUs challenge x86, (3) custom ASICs compete with merchant GPUs, (4) battleground shifted from PCs/gaming to DC/AI.

# Appendix B: Supply/Demand Balance — AMD

## Demand Decomposition

### Backlog and Pipeline
- AMD does not publicly disclose quantitative backlog data by segment or product [claim_verification.json: C096, Verified: "No highly specific public quantitative breakdowns of AMD's order backlog or order pipeline by segment/product for 2025-2026 were found"]
- Lisa Su stated visibility extends to "which data centers the GPU is going to be installed in" for 2027 deployments [transcript.json: Lisa Su, Q&A response to Thomas O'Malley]
- MI450 customer forecasts "now exceeding our initial plans" with "a growing number of new customers engaging on large-scale deployments, including additional multi-gigawatt opportunities" [transcript.json: Lisa Su, prepared remarks]
- Lisa Su: "strong and increasing confidence in our ability to deliver tens of billions of dollars in annual Data Center AI revenue in 2027" [transcript.json: Lisa Su, prepared remarks]

### Historical Demand Trajectory

| Period | Total Revenue | Data Center | Client & Gaming | Embedded |
|---|---|---|---|---|
| FY2023 | $22.7B | ~$6.5B (est.) | ~$12.6B (est.) | ~$3.6B (est.) |
| FY2024 | $25.8B | $12.6B | $9.6B | $3.6B |
| FY2025 | $34.6B | $16.6B | $14.6B | $3.5B |
| Q1 2026 ann. | ~$41.0B | ~$23.2B | ~$14.4B | ~$3.5B |

[Sources: income.json (total revenue), claim_verification.json C042 (DC), C041/C043 (C&G), C074 (Embedded), transcript.json (Q1 2026 segment data)]

### Demand Durability
- Microsoft FY2026 capex forecast: $190B (+61% YoY), explicit shift toward "shorter-lived assets (CPUs and GPUs)" [ecosystem_signals.md: Microsoft section]
- Big Tech collective 2026 capex estimated at $527B per Goldman Sachs (Dec 2025) [customer_capex.md — Tier 4/5 source]
- Azure revenue growth: 40% YoY in Q3 FY2026, Q4 guided 39-40% [ecosystem_signals.md: Microsoft section]
- Server CPU TAM: ">$120 billion by 2030" per Lisa Su, driven by Agentic AI [claim_verification.json: C076, Corroborated]
- Lisa Su: EPYC-powered cloud instances increased "nearly 50% year-over-year to more than 1,600" [transcript.json: Lisa Su, prepared remarks]

### CPU-to-GPU Ratio Dynamics
- Lisa Su: ratio shifting from "1:4 or 1:8" to "closer to 1:1" or more CPUs than GPUs in agentic workloads [transcript.json: Lisa Su, Q&A response to Vivek Arya]. Management forward-looking statement, not an established benchmark.

## Supply Analysis

### Current Constraints

1. **TSMC Advanced Nodes:** N2 and advanced 3nm "fully sold out." TSMC CEO C.C. Wei: "Our CoWoS capacity is very tight and remains sold out through 2025 and into 2026" [claim_verification.json: C082/C023, Corroborated]
2. **CoWoS Advanced Packaging:** AMD has ~11% of TSMC CoWoS allocation [claim_verification.json: C021, Single-Source: analyst estimate, not TSMC disclosure]. CoWoS is the bottleneck for AI GPUs (both NVIDIA and AMD compete for this capacity).
3. **HBM Memory:** "Sold out through 2026 from SK Hynix and Micron" [claim_verification.json: C084, Corroborated: 5+ sources]. AMD has "secured enough supply to certainly meet and exceed our targets" [transcript.json: Lisa Su, Q&A response to Vivek Arya]
4. **Data Center Power:** "Tightness in data center build-outs" but "much more power coming online in 2027" [transcript.json: Lisa Su, Q&A response to Thomas O'Malley]

### How Supply Gets Added
- TSMC capex: $52B-$56B in 2026 (+32% at midpoint), expanding advanced node capacity [claim_verification.json: C054, Corroborated]
- AMD "working closely with supply chain partners to meaningfully increase wafer and back-end capacities" [transcript.json: Lisa Su, prepared remarks]
- New TSMC advanced node capacity: 18-24 months from announcement to production (industry standard for fab construction)
- CoWoS capacity additions: 12-18 months (TSMC has been expanding since mid-2024)
- HBM capacity: SK Hynix and Micron expanding but constrained by DRAM wafer availability

### Capital Intensity
- AMD FY2025 capex: $974M (2.8% of revenue) — fabless model [cashflow.json: capitalExpenditure]
- AMD's fabless model means TSMC bears the manufacturing capex burden
- TSMC's $52B-$56B capex is 55-58x AMD's CapEx — illustrates capital intensity difference

### Supply Addition Timeline
- MI450 GPU: 12 TSMC N2 compute chiplets + 3 advanced 3nm chiplets [claim_verification.json: C022, Single-Source: social media, not confirmed by AMD]
- EPYC Venice: production ramp announced May 21, 2026 — first HPC product on TSMC 2nm [claim_verification.json: C090/C099, Verified]
- Helios rack-scale system: sampling, production shipments planned H2 2026 [transcript.json: Lisa Su]

## Supply/Demand Synthesis

**Net Balance:** Demand exceeds supply across all key inputs (advanced wafer capacity, CoWoS packaging, HBM). Lisa Su: "The supply chain is tight. I would definitely say that" [transcript.json: Lisa Su, Q&A response to Blayne Curtis].

**Quantification of Gap:** "Semiconductor demand expected to outpace supply through 2026" [claim_verification.json: C108, Single-Source]. AMD consumes "roughly 8% of TSMC capacity" for data center GPUs [claim_verification.json: C083, Single-Source: YouTube video, not confirmed by primary source]. Gap is not precisely quantifiable — neither AMD nor TSMC discloses customer-specific allocations.

**Pricing Implications:**
- GAAP gross margin: 49.4% (FY2024) → 49.5% (FY2025) [income.json]
- Non-GAAP gross margin guided to 56% for Q2 2026 [transcript.json: Jean Hu]
- Lisa Su: ASP increases partly to "help cover some of the inflationary pressures," with "majority of the growth" being "unit driven" [transcript.json: Lisa Su, Q&A response to Tim Arcuri]
- MI450 GPU margins "below corporate average" — will create margin mix headwind as volumes ramp [transcript.json: Jean Hu, Q&A response to Ross Seymore]

**Inventory Signal:** $7.9B FY2025 inventory (+38% YoY), "roughly flat at $8 billion" in Q1 2026 [balance.json: inventory; transcript.json: Jean Hu]. Inventory/Revenue: 22.9% (FY2025) vs. 11.9% (FY2021) [Computed: balance.json, income.json]. DIO: 165 days (FY2025) vs. 84 days (FY2021) [metrics.json].

## AI Value Chain Positioning

- **Position:** Chip design layer — GPUs (Instinct) and CPUs (EPYC) for AI infrastructure. Fabless.
- **AI Revenue:** Data Center: $16.6B FY2025 (47.9%), $5.8B Q1 2026 (56.6%). AI-specific portion within DC not disclosed [Data Gap].
- **Instinct GPU revenue:** Estimated >$5B FY2024 [claim_verification.json: C091, Single-Source]. Target: "tens of billions in annual DC AI revenue in 2027" with ">80% CAGR" [transcript.json: Lisa Su]
- **AMD is #2 data center GPU provider** behind NVIDIA (~7% share est.) [claim_verification.json: C093, Unverifiable] and #2 in server CPUs (46.2% revenue share, approaching parity) [claim_verification.json: C012, Corroborated]
- AMD is the only company with competitive products in both server CPUs and data center GPUs, enabling integrated CPU+GPU solutions (Helios). NVIDIA will compete with Vera Rubin (CPU+GPU).

## Bargaining Power

### Demand-Side
- Major customers have multi-year, multi-gigawatt commitments (OpenAI 6GW, Meta multi-GW) [transcript.json; claim_verification.json C059]
- In current supply-constrained environment, customers "largely focused on supply and ensuring that the supply assurance is there" rather than price [transcript.json: Lisa Su, Q&A response to Vivek Arya]
- Hyperscaler backward integration (custom silicon: Graviton, TPU, Maia, Trainium) is structural demand risk

### Supply-Side
- TSMC single-source dependency; switching costs extremely high
- HBM from 3 vendors but capacity-constrained
- AMD absorbs some cost increases: "sharing some of that with our customers" but also "being very thoughtful... playing out for the long term" [transcript.json: Lisa Su, Q&A response to Tim Arcuri]

## Depth-First Research Summary

**Questions answered:**
- What is AMD's backlog? → Not disclosed publicly [claim_verification.json: C096]
- How has demand grown? → FY2023 $22.7B → FY2025 $34.6B (+52.7% cumulative) [income.json]
- What is the supply bottleneck? → TSMC CoWoS advanced packaging, then HBM memory, then 2nm wafer capacity [claim_verification.json: C023, C082, C084]
- When does the supply gap close? → TSMC expanding ($52-56B capex 2026), but "sold out" through 2026 [claim_verification.json: C023]

**Questions unanswerable:**
- AMD's exact TSMC wafer allocation and pricing [Single-Source estimates only]
- Product-level inventory composition [10-K text unavailable]
- Instinct GPU vs. EPYC CPU revenue split within Data Center [not disclosed]
- Specific customer order volumes and delivery schedules [not disclosed]

# Appendix C: Value Chain — AMD

## Value Chain Map

AMD occupies the **chip design** stage in a fabless model established in 2009 (GlobalFoundries spinoff). All manufacturing outsourced.

| Value Chain Stage | AMD's Role | Key Partners | Est. Players |
|---|---|---|---|
| Chip Design & Architecture | **In-house** (core competency) | EDA: Synopsys, Cadence | 3-5 at advanced nodes (AMD, Intel, NVIDIA, Qualcomm, Broadcom) |
| IP Licensing (x86 ISA) | **In-house** (perpetual cross-license with Intel) | Intel (cross-license) | 2 (AMD, Intel hold x86 licenses) |
| Wafer Fabrication | **Outsourced** | TSMC (primary) | ~3 at leading-edge (TSMC, Samsung, Intel Foundry) |
| Advanced Packaging (CoWoS) | **Outsourced** | TSMC (CoWoS-L, CoWoS-S) | ~2-3 (TSMC, ASE, Amkor) |
| HBM Memory | **Purchased** | SK Hynix, Samsung, Micron | 3 |
| Assembly/Test (OSAT) | **Outsourced** | ASE, Amkor, SPIL (likely) | 5-10 |
| System Integration (Helios) | **Partial — emerging** | AMD designs rack-scale; OEM/ODM builds | New capability for AMD |
| Software (ROCm) | **In-house** | Open-source ecosystem | AMD-proprietary |
| Distribution & Sales | **In-house + channel** | Direct to hyperscalers; distributors for enterprise/consumer | Multiple |

## Upstream: Suppliers

### 1. TSMC — Primary Foundry

TSMC is AMD's most critical supplier. AMD's entire product line (EPYC, Instinct, Ryzen, Radeon, Xilinx FPGAs) manufactured at TSMC.

**Relationship size:**
- AMD FY2025 COGS: $17.5B [income.json: costOfRevenue]. TSMC wafer purchases represent a substantial portion (exact split between wafer, memory, OSAT not disclosed).
- AMD estimated as TSMC's 3rd-4th largest customer (~7% of TSMC revenue, ~$10B annually) with ~11% of TSMC CoWoS advanced packaging allocation [claim_verification.json: C021, Single-Source: analyst estimate, not TSMC disclosure]

**Process nodes used:**
- Current: TSMC 5nm/4nm (EPYC Turin, MI325X), 3nm (MI355X chiplets)
- Next-gen: TSMC 2nm (EPYC Venice, MI450 compute chiplets) — production ramp announced May 21, 2026 [press_releases.md; claim_verification.json: C090/C099, Verified]

**Switching costs:** Extremely high. TSMC is the only foundry capable of volume production at 2nm for AMD's design complexity. Samsung Foundry is a theoretical alternative but has not demonstrated equivalent yield. Intel Foundry ramping but not producing AMD chips [Inference: based on public foundry capabilities] [Sources: ecosystem_signals.md, supplier_capacity.md].

**Supply constraints:**
- TSMC CEO C.C. Wei: capacity "very tight," "sold-out environment" through 2026 [claim_verification.json: C023, Corroborated]
- Lisa Su: "The supply chain is tight... But I also think this is an area where we excel. We have very deep relationships across the supply chain" [transcript.json: Lisa Su, Q&A response to Blayne Curtis]
- TSMC capex: $52B-$56B in 2026, expanding capacity [claim_verification.json: C054, Corroborated]

### 2. Memory Vendors — HBM and DRAM

HBM is critical for Instinct GPUs. Suppliers: SK Hynix, Samsung, Micron.

- Lisa Su: "We are very happy with our partnerships with the memory vendors, and we have secured enough supply to certainly meet and exceed our targets. So it is a tight memory environment" [transcript.json: Lisa Su, Q&A response to Vivek Arya]
- HBM may represent 40-60% of accelerator BOM cost [Inference: industry-wide dynamics; analyst C.J. Muse referenced HBM pass-through as margin factor; Jean Hu deflected by saying "we really focus on driving the topline revenue growth"] [Sources: transcript.json]
- Memory price increases impacting consumer: Jean Hu guided "second half gaming revenue to decline more than 20% compared to the first half" partly due to "higher memory and component costs" [transcript.json: Jean Hu, prepared remarks]

### 3. EDA Tools & IP

AMD relies on Synopsys and Cadence EDA tools. AMD holds perpetual x86 cross-license with Intel (foundational to CPU business) and ARM license for embedded products (Xilinx heritage) [info.json: description].

### 4. OSAT Partners

Specific partners not named in available data. Industry-standard OSAT vendors include ASE Technology, Amkor Technology, SPIL [Data Gap: 10-K text unavailable for supplier identification].

## Downstream: Customers

### Customer Relationships

| Customer | Segment | Details | Revenue % | Source |
|---|---|---|---|---|
| OpenAI | DC (GPU) | 6 GW GPU deployment, co-engineering | Not disclosed | [claim_verification.json: C059, Verified] |
| Meta | DC (GPU) | Up to 6 GW Instinct; custom MI450 co-designed | Not disclosed | [transcript.json: Lisa Su] |
| Microsoft | DC + Gaming | Azure (EPYC+Instinct); Xbox semi-custom SoC | Not disclosed | [ecosystem_signals.md; info.json] |
| Cloud providers | DC | >1,600 EPYC instances (+50% YoY) | Not disclosed | [transcript.json: Lisa Su] |
| Sony | Gaming | PlayStation semi-custom SoC | Not disclosed | [Inference: industry knowledge] [Sources: info.json] |
| Dell/HP/Lenovo | Client | PC OEMs; Ryzen PRO +50% YoY | Not disclosed | [transcript.json: Lisa Su] |

[Data Gap: 10-K customer concentration (>10% of revenue) not available in this run]

### Customer Switching Costs

| Product | Switching Cost Level | Evidence |
|---|---|---|
| EPYC CPU | Moderate-to-high | x86-to-x86 requires platform redesign but minimal software changes; 6-12 month qualification |
| Instinct GPU | High | CUDA-to-ROCm migration barrier; multi-generation commitments (OpenAI, Meta) |
| Semi-Custom | Very high | 5-7+ year console contracts; sole supplier per generation |
| Embedded | Very high | 12-24+ month design-in cycles; deeply integrated |

## Margin Capture Across Value Chain

| Stage | Company | Gross Margin | Operating Margin | Source |
|---|---|---|---|---|
| EDA Tools | Synopsys/Cadence | ~80%+ | ~30-35% | [Inference: public financials not re-verified in this run] |
| Chip Design — NVIDIA | NVIDIA | ~75% | ~65%+ | [ecosystem_signals.md; claim_verification.json C048, Corroborated] |
| Foundry — TSMC | TSMC | ~58-60% | ~48-50% | [Inference: TSMC Q1 2026 net margin ~51% from $18.2B/$35.9B] [Sources: ecosystem_signals.md] |
| Chip Design — AMD | AMD | 49.5% GAAP / ~54% non-GAAP | 10.7% GAAP / ~25% non-GAAP | [income.json; transcript.json: Jean Hu] |
| Memory (HBM) | SK Hynix | ~50%+ | ~35%+ | [Inference: HBM premium; not verified this run] |
| OSAT | ASE/Amkor | ~20-25% | ~10-15% | [Inference: lower-margin back-end; not verified] |

### GAAP vs Non-GAAP Margin Gap

AMD's GAAP operating margin (10.7%) is materially depressed by amortization of $24B+ acquired intangibles from Xilinx:
- FY2025 D&A: $3,004M [income.json] vs CapEx: $974M [cashflow.json] — ~$2B+ gap is acquisition amortization
- Intangible assets amortizing: $24,118M (FY2022) → $16,705M (FY2025) [balance.json]
- Non-GAAP Q1 2026 operating margin: 25% [transcript.json: Jean Hu]

### Segment Operating Margins (Q1 2026, Non-GAAP)

| Segment | Revenue | Operating Income | Op Margin | YoY Change |
|---|---|---|---|---|
| Data Center | $5.8B | $1.6B | 28% | +3pp (from 25%) |
| Client & Gaming | $3.6B | $575M | 16% | -1pp (from 17%) |
| Embedded | $873M | $338M | 39% | Stable |

[transcript.json: Jean Hu, prepared remarks]

Embedded captures highest margins (39%), followed by Data Center (28%), then Client & Gaming (16%) [Inference: consistent with FPGA pricing power and long lifecycle products] [Sources: transcript.json].

### Margin Migration Direction

Margins migrating **toward Data Center** and **away from Client & Gaming**:
- DC grew from 47.9% to 56.6% of revenue; operating margin expanding (25%→28%) [transcript.json]
- C&G operating margin compressed (17%→16%) [transcript.json]
- MI450 GPU margins "below corporate average" will create mixed headwind as volumes ramp [transcript.json: Jean Hu]

### Historical Margin Comparison

| Year | AMD GM (GAAP) | NVIDIA GM | TSMC GM | Intel GM (est.) |
|---|---|---|---|---|
| FY2025 | 49.5% | ~75% | ~58% | ~40% |
| FY2024 | 49.4% | ~73% | ~54% | ~41% |
| FY2023 | 46.1% | ~57% | ~54% | ~40% |
| FY2022 | 44.9% | ~57% | ~59% | ~43% |
| FY2021 | 48.2% | ~65% | ~52% | ~55% |

[Sources: AMD from income.json; NVIDIA from ecosystem_signals.md and claim_verification.json C048; TSMC from ecosystem_signals.md; Intel approximate — Data Gap: not verified from primary sources]

Margin migrating from commodity stages toward: (1) NVIDIA (CUDA lock-in pricing power), (2) TSMC (sole-source advanced fabrication), (3) HBM vendors (supply-constrained). AMD positioned between NVIDIA and TSMC in margin hierarchy.

## Integration Direction

### Forward (Toward Customers)
- **Helios rack-scale platform:** Integrates Instinct GPUs with EPYC Venice CPUs into optimized AI infrastructure. Sampling; production shipments H2 2026 [transcript.json: Lisa Su]. Ship timing tagged as Unverifiable from AMD primary sources beyond earnings call [claim_verification.json: C038].
- **Semi-custom co-design expansion:** Meta partnership includes "custom GPU accelerator based on our MI450 architecture, co-designed to support Meta's next-generation AI workloads" [transcript.json: Lisa Su] — expanding semi-custom approach from gaming consoles to data center.
- **Enterprise direct sales:** Jean Hu acknowledged "building our go-to-market machine, investing more in sales and marketing" [transcript.json: Jean Hu]

### Backward (Toward Suppliers)
- No backward integration; fabless since 2009 GF spinoff
- CapEx $974M vs TSMC $52-56B — 55-58x gap [cashflow.json; ecosystem_signals.md]
- Software integration: ROCm development "significantly accelerated through increased software investments and agent-based coding workflows" [transcript.json: Lisa Su]

### Customer/Supplier Integration Toward AMD's Position
- **NVIDIA entering CPU:** Vera CPU with Vera Rubin system competes with Helios. NVIDIA expects "~$20B in CPU revenue in FY2027" [claim_verification.json: C008, Corroborated]
- **Cloud custom silicon:** AWS Graviton/Trainium, Google TPU/Axion, Microsoft Maia/Cobalt partially dis-intermediating merchant silicon
- **Intel improving supply:** Analyst noted Intel "restarting 7-nanometer" [transcript.json: analyst Blayne Curtis, question]

## Dependencies and Vulnerabilities

1. **TSMC single-source dependency:** All products depend on TSMC; no near-term alternative for leading-edge
2. **HBM supply concentration:** 3 vendors, capacity-constrained through 2026
3. **NVIDIA competitive dominance:** ~13x AMD's DC revenue; CUDA ecosystem lock-in
4. **x86 cross-license with Intel:** Structural dependency; termination would eliminate CPU business
5. **Taiwan geographic risk:** TSMC fabrication concentrated in Taiwan; Arizona fab ramping
6. **Export controls:** $440M net FY2025 MI308 charges [claim_verification.json: C092/C110, Verified]
7. **Inventory build:** $7.9B FY2025 (+38% YoY); write-down risk if demand slows (demonstrated by $800M MI308 charge) [balance.json; claim_verification.json: C110]

## Data Gaps

1. 10-K text (latest_10k.json) not available — customer concentration, named suppliers, geographic revenue
2. AMD's specific TSMC allocation and pricing — Single-Source estimates only [claim_verification.json: C021]
3. Instinct GPU revenue vs EPYC CPU within Data Center — not disclosed
4. OSAT partner identity — 10-K risk factors would typically disclose
5. Semi-custom contract economics — not publicly disclosed
6. CoWoS allocation trajectory — whether AMD's ~11% share is increasing or stable

# Appendix D: Capital Structure — AMD

## Equity Composition

| Component | Value | Source |
|---|---|---|
| Stock type | Common stock, single class | [balance.json: commonStock; preferredStock = 0] |
| Shares outstanding | 1,630,600,000 | [shares_float.json: outstandingShares] |
| Diluted shares (FY2025) | 1,636,000,000 | [income.json: weightedAverageShsOutDil, FY2025] |
| Float shares | 1,621,860,620 (99.5% of outstanding) | [shares_float.json: floatShares, freeFloat] |
| Dual-class structure | No | [balance.json: single commonStock line item] |
| Preferred stock | None | [balance.json: preferredStock = 0] |
| Market cap | $821,643,034,000 | [quote.json: marketCap] |

**Share count trajectory:**

| FY | Diluted Shares (M) | Change |
|---|---|---|
| 2021 | 1,229M | Pre-Xilinx baseline |
| 2022 | 1,571M | +27.8% (Xilinx acquisition shares) |
| 2023 | 1,625M | +3.4% |
| 2024 | 1,637M | +0.7% |
| 2025 | 1,636M | -0.1% (buybacks offsetting SBC) |

[income.json: weightedAverageShsOutDil, all periods]

## Debt Composition

### Total Debt: $4,472M [balance.json: totalDebt, FY2025]

| Tranche | Amount | Source |
|---|---|---|
| Short-term debt | $874M | [balance.json: shortTermDebt, FY2025] |
| Long-term debt | $2,973M | [balance.json: longTermDebt, FY2025] |
| Capital lease obligations (non-current) | $625M | [balance.json: capitalLeaseObligationsNonCurrent, FY2025] |

**Debt trajectory:**

| FY | Total Debt | Short-Term | Long-Term | Cap Leases |
|---|---|---|---|---|
| 2021 | $661M | $0 | $313M | $348M |
| 2022 | $2,863M | $0 | $2,467M | $396M |
| 2023 | $3,003M | $751M | $1,717M | $535M |
| 2024 | $2,212M | $0 | $1,721M | $491M |
| 2025 | $4,472M | $874M | $2,973M | $625M |

[balance.json: totalDebt, shortTermDebt, longTermDebt, capitalLeaseObligationsNonCurrent, all periods]

FY2025 total debt increased $2,260M from FY2024, driven by:
- $1,491M net long-term debt issuance [cashflow.json: longTermNetDebtIssuance, FY2025]
- $874M new short-term debt [balance.json: shortTermDebt went from $0 to $874M]

### Debt Maturity Profile

**Data Gap:** The 10-K text (latest_10k.json) was not available in this data run. Specific debt tranche maturities, coupon rates, and covenant details cannot be confirmed. The interest expense of $131M on $4,472M total debt implies a blended cost of debt of ~2.9% [Computed: income.json interestExpense / balance.json totalDebt].

### Interest Coverage

| FY | EBIT ($M) | Interest Exp ($M) | Coverage Ratio |
|---|---|---|---|
| 2025 | $4,271M | $131M | 32.6x |
| 2024 | $2,081M | $92M | 22.6x |
| 2023 | $598M | $106M | 5.6x |
| 2022 | $1,272M | $88M | 14.5x |
| 2021 | $3,703M | $34M | 108.9x |

[income.json: ebit, interestExpense, all periods]

## Convertible Securities

No convertible debt identified in current outstanding debt [convertible_search.json: EDGAR full-text search returned historical results only (2007-2013 vintage); convertible_detail.md: web search found no current AMD convertibles].

## Cash and Equivalents

| Component | FY2025 | FY2024 | Source |
|---|---|---|---|
| Cash & cash equivalents | $5,539M | $3,787M | [balance.json: cashAndCashEquivalents] |
| Short-term investments | $5,013M | $1,345M | [balance.json: shortTermInvestments] |
| **Cash + STI** | **$10,552M** | **$5,132M** | [balance.json: cashAndShortTermInvestments] |

Cash + STI increased $5,420M YoY, driven by $7,709M operating cash flow [cashflow.json], partly offset by $974M capex, $1,760M acquisitions, and $1,316M share repurchases [cashflow.json].

## Minority Interest

$0 [balance.json: minorityInterest, FY2025]. AMD has no non-controlling interests.

## Enterprise Value

| Component | Value | Source |
|---|---|---|
| Market cap | $821,643M | [quote.json: marketCap] |
| + Total debt | $4,472M | [balance.json: totalDebt] |
| − Cash & equivalents | $5,539M | [balance.json: cashAndCashEquivalents] |
| **Enterprise Value** | **$820,576M** | [Computed] |

Note: FMP enterprise_value.json at the FY2025 filing date (price $214.99) shows EV of $348,077M. The current EV of $820.6B uses the current market price of $503.89 [quote.json].

## Net Debt / EBITDA

| Metric | Value | Source |
|---|---|---|
| Net debt (totalDebt − cashAndShortTermInvestments) | -$6,080M | [balance.json] |
| Net debt (totalDebt − cashAndCashEquivalents) | -$1,067M | [balance.json: netDebt field] |
| FY2025 EBITDA | $7,275M | [income.json: ebitda] |
| **Net Debt / EBITDA (using cash+STI)** | **-0.84x** | [Computed] |
| Net Debt / EBITDA (using cash only) | -0.15x | [Computed; consistent with metrics.json: -0.147x] |

AMD is in a net cash position by either measure.

## Share Repurchase Program

- $9.2B remaining under repurchase authorization as of Q1 FY2026 [transcript.json: Jean Hu]
- Q1 FY2026: 1.1M shares repurchased, $221M returned [transcript.json: Jean Hu]
- Five-year cumulative buybacks (FY2021-FY2025): $10,426M [cashflow.json: commonStockRepurchased — $4,108M + $1,412M + $1,590M + $1,316M + FY2021 amount]

| FY | Buybacks ($M) | Source |
|---|---|---|
| 2022 | $4,108M | [cashflow.json: commonStockRepurchased] |
| 2023 | $1,412M | [cashflow.json] |
| 2024 | $1,590M | [cashflow.json] |
| 2025 | $1,316M | [cashflow.json] |

[Data Gap: FY2021 buyback amount not separately confirmed in cashflow.json excerpt]

## Dividend

AMD has never paid a common dividend [dividends.json: no dividend history]. Last dividend: $0 [info.json: lastDividend = 0].

## Notable 8-K Events

- **2026-02-24:** 8-K filing with Registration Rights Agreement with Meta Platforms, Inc. [filing_events.json: accession 0000002488-26-000045]. This may relate to equity issuance to Meta as part of partnership arrangement.
- **2026-01-20 and 2026-02-17:** 8-K filings involving "Departure/Election of Directors or Officers; Compensatory Arrangements" (Item 5.02) [filing_events.json]. Specific officers not identified in available data [Data Gap].

# Appendix E: Key Stats — AMD

All multiples computed at current price ($503.89 [quote.json]) unless otherwise noted. FMP-computed ratios in metrics.json and ratios.json use prior filing-date prices and should not be used directly for current valuation.

## Price & Trading

| Metric | Value | Computation | Source |
|---|---|---|---|
| Price | $503.89 | — | [quote.json: price] |
| 52-week range | $108.62 – $506.96 | — | [quote.json: yearLow, yearHigh] |
| Position in range | 99.2% | ($503.89 − $108.62) / ($506.96 − $108.62) | [Computed] |
| ADV (30d, shares) | 42.1M shares | — | [technicals.json: avg_volume_30d] |
| ADV (30d, dollars) | $17,137M | — | [technicals.json: adv_30d] |
| ADV (info.json method) | $19,200M | 38,103,470 × $503.89 / 1e6 | [info.json: averageVolume × price] |
| Beta | 2.399 | — | [info.json: beta] |
| RSI (14) | 77.1 | — | [technicals.json: rsi_14] |
| 21d EMA | $410.33 | — | [technicals.json: ema_21d] |
| 50d SMA | $309.40 | — | [technicals.json: sma_50d] |
| 200d SMA | $232.53 | — | [technicals.json: sma_200d] |

## Valuation Multiples

| Metric | Value | Computation | Source |
|---|---|---|---|
| Trailing P/E (FY2025 GAAP) | 190.1x | $503.89 / $2.65 | [quote.json, income.json: epsDiluted FY2025] |
| Trailing P/E (TTM, 4Q) | 110.0x | $503.89 / $4.58 | [quote.json, earnings.json: Q1'26 $1.37 + Q4'25 $1.53 + Q3'25 $1.20 + Q2'25 $0.48] |
| Forward P/E (FY2026E) | 67.7x | $503.89 / $7.44 | [quote.json, ratings.json: epsAvg 2026] |
| Forward P/E (FY2027E) | 38.5x | $503.89 / $13.10 | [quote.json, ratings.json: epsAvg 2027] |
| EV/EBITDA (FY2025) | 112.8x | $820.6B / $7.275B | [Computed EV, income.json: ebitda] |
| EV/Revenue (FY2025) | 23.7x | $820.6B / $34.639B | [Computed EV, income.json: revenue] |
| P/FCF (FY2025) | 122.0x | $821.6B / $6.735B | [quote.json: marketCap, cashflow.json: freeCashFlow] |
| P/FCF ex-SBC | 161.2x | $821.6B / ($6.735B − $1.638B) | [cashflow.json: freeCashFlow, stockBasedCompensation] |
| Dividend yield | 0% | No dividend | [dividends.json; info.json: lastDividend = 0] |

## Short Interest

| Metric | Value | Source |
|---|---|---|
| Shares short | ~36,140,000 | [short_interest.md: shortsqueeze.com (Tier 5)] |
| Float shares | 1,621,860,620 | [shares_float.json: floatShares] |
| Short % of float | ~2.2% | [Computed: 36.14M / 1,621.9M] |
| Days to cover | ~0.8-0.9 days | [short_interest.md: marketbeat.com, shortsqueeze.com (Tier 5)] |

Note: FMP short_interest.json returned empty (API error 404). Short interest data sourced from web search (Tier 5) [short_interest.json; short_interest.md].

## Financial Summary

| Metric | FY2025 | FY2024 | FY2023 | FY2022 | FY2021 | Source |
|---|---|---|---|---|---|---|
| Revenue | $34,639M | $25,785M | $22,680M | $23,601M | $16,434M | [income.json] |
| Rev YoY | +34.3% | +13.7% | -3.9% | +43.6% | +68.3% | [Computed] |
| Gross Margin | 49.5% | 49.4% | 46.1% | 44.9% | 48.2% | [income.json] |
| Operating Margin | 10.7% | 7.4% | 1.8% | 5.4% | 22.2% | [income.json] |
| Net Margin | 12.5% | 6.4% | 3.8% | 5.6% | 19.2% | [income.json] |
| EBITDA | $7,275M | $5,258M | $4,149M | $5,534M | $4,166M | [income.json] |
| EPS (diluted) | $2.65 | $1.00 | $0.53 | $0.84 | $2.57 | [income.json] |
| FCF | $6,735M | $2,405M | $1,121M | $3,115M | $3,220M | [cashflow.json] |
| FCF Margin | 19.4% | 9.3% | 4.9% | 13.2% | 19.6% | [Computed] |
| R&D | $8,091M | $6,456M | $5,872M | $5,005M | $2,845M | [income.json] |
| R&D % Rev | 23.4% | 25.0% | 25.9% | 21.2% | 17.3% | [Computed] |
| CapEx | $974M | $636M | $546M | $450M | $301M | [cashflow.json] |
| CapEx % Rev | 2.8% | 2.5% | 2.4% | 1.9% | 1.8% | [Computed] |

## Returns on Capital

| Metric | FY2025 | FY2024 | FY2023 | FY2022 | FY2021 | Source |
|---|---|---|---|---|---|---|
| ROIC | 5.40% | 2.49% | 0.65% | 2.07% | 36.97% | [metrics.json] |
| ROE | 6.88% | 2.85% | 1.53% | 2.41% | 42.18% | [metrics.json] |
| ROCE | 5.47% | 3.07% | 0.66% | 2.07% | 44.60% | [metrics.json] |
| Invested Capital | $61,635M | $57,962M | $57,926M | $58,918M | $6,024M | [metrics.json] |

ROIC cliff from 37.0% (FY2021) to 2.1% (FY2022) caused by Xilinx acquisition inflating invested capital from $6.0B to $58.9B [Inference: GAAP ROIC understates operating economics due to acquisition accounting] [Sources: metrics.json, balance.json, income.json].

## Working Capital

| Metric | FY2025 | FY2024 | FY2023 | FY2022 | FY2021 | Source |
|---|---|---|---|---|---|---|
| DIO | 165d | 160d | 130d | 106d | 84d | [metrics.json] |
| DSO | 67d | 88d | 87d | 64d | 60d | [metrics.json] |
| DPO | 61d | 56d | 61d | 70d | 57d | [metrics.json] |
| CCC | 171d | 192d | 138d | 100d | 87d | [metrics.json] |
| Inventory | $7,920M | $5,734M | $4,351M | $3,770M | $1,955M | [balance.json] |
| Inv/Rev | 22.9% | 22.2% | 19.2% | 16.0% | 11.9% | [Computed] |

## Earnings Beat/Miss History

| Quarter | EPS Actual | EPS Est | Surprise | Rev Actual | Rev Est | Rev Surprise |
|---|---|---|---|---|---|---|
| Q1 FY2026 | $1.37 | $1.29 | +$0.08 (+6.2%) | $10,253M | $9,900M | +$353M (+3.6%) |
| Q4 FY2025 | $1.53 | $1.32 | +$0.21 (+15.9%) | $10,270M | $9,668M | +$602M (+6.2%) |
| Q3 FY2025 | $1.20 | $1.17 | +$0.03 (+2.6%) | $9,246M | $8,756M | +$490M (+5.6%) |
| Q2 FY2025 | $0.48 | $0.48 | +$0.001 | $7,685M | $7,414M | +$271M (+3.7%) |
| Q1 FY2025 | $0.96 | $0.94 | +$0.02 | $7,438M | $7,124M | +$314M (+4.4%) |
| Q4 FY2024 | $1.09 | $1.08 | +$0.01 | $7,658M | $7,533M | +$125M (+1.7%) |
| Q3 FY2024 | $0.92 | $0.922 | -$0.002 | $6,819M | $6,715M | +$104M (+1.6%) |
| Q2 FY2024 | $0.69 | $0.678 | +$0.012 | $5,835M | $5,729M | +$106M (+1.9%) |
| Q1 FY2024 | $0.62 | $0.616 | +$0.004 | $5,473M | $5,477M | -$4M (-0.1%) |

[earnings.json: all quarters]

Summary: 8 EPS beats, 1 narrow miss ($0.002 in Q3 FY2024); 8 revenue beats, 1 negligible miss ($4M in Q1 FY2024). Revenue beats widened over the last 4 quarters.

## Analyst Consensus

| Year | Revenue Est | EPS Est | Rev YoY | # Analysts (Rev/EPS) |
|---|---|---|---|---|
| FY2026E | $49.9B | $7.44 | +44% | 36 / 30 |
| FY2027E | $76.3B | $13.10 | +53% | 36 / 28 |
| FY2028E | $101.1B | $17.85 | +33% | 30 / 15 |
| FY2029E | $144.3B | $25.06 | +43% | 15 / 6 |
| FY2030E | $171.4B | $29.92 | +19% | 17 / 6 |

[ratings.json: estimates]

Price target consensus: $437.59. Median: $450. Range: $260–$579 [ratings.json: price_target_consensus]. Current price $503.89 is 15.2% above consensus [Computed].

## Scoring Models

| Model | Score | Source |
|---|---|---|
| Altman Z-Score | 33.57 | [scores.json] |
| Piotroski F-Score | 7/9 | [scores.json] |
| FMP DCF Fair Value | $51.36 | [dcf.json — third-party model with unknown methodology] |

## Greenwald Value Decomposition

| Component | Value | Source |
|---|---|---|
| Tangible Book Value | $35,095M ($21.52/share) | [Computed: $76,926M assets − $25,126M goodwill − $16,705M intangibles; balance.json] |
| GW + Intangibles % of Assets | 54.4% | [Computed: $41,831M / $76,926M] |
| Earnings Power Value (no growth) | ~$26.4B ($16.19/share) | [Inference: $4,335M NI / 16.4% WACC] [Sources: income.json, CAPM] |
| Franchise Value | ~$795.2B (96.8% of mkt cap) | [Inference: $821.6B − $26.4B] [Sources: quote.json, income.json] |

96.8% of market cap represents franchise value — the market prices in substantial future growth [Inference: franchise value calculation] [Sources: quote.json, income.json, WACC estimate].

## WACC Estimate

| Component | Value | Source |
|---|---|---|
| Risk-free rate | ~4.5% | [Inference: approximate 10-year Treasury] |
| Beta | 2.399 | [info.json: beta] |
| Equity risk premium | ~5.0% | [Inference: standard assumption] |
| Cost of equity | ~16.5% | [Computed: 4.5% + 2.399 × 5.0%] |
| Cost of debt (pre-tax) | ~2.9% | [Computed: $131M / $4,472M; income.json, balance.json] |
| Debt weight | 0.5% | [Computed: $4.5B / ($821.6B + $4.5B)] |
| **WACC** | **~16.4%** | [Computed] |

# Appendix F: Risk Factors — AMD

## 1. Customer Concentration

AMD does not disclose individual customer revenue concentrations in available data. 10-K text (latest_10k.json) not available in this run [Data Gap].

**Known large relationships:**
- **OpenAI:** 6 GW GPU deployment agreement (Oct 2025) [claim_verification.json: C059, Verified]
- **Meta:** Up to 6 GW Instinct deployment; custom MI450; Registration Rights Agreement with AMD filed via 8-K (Feb 24, 2026) [transcript.json: Lisa Su; filing_events.json: accession 0000002488-26-000045]
- **Microsoft:** Azure (EPYC + Instinct); Xbox semi-custom SoC [ecosystem_signals.md; info.json]
- **Sony:** PlayStation semi-custom SoC [Inference: industry knowledge] [Sources: info.json]

If top 2 customers (OpenAI and Meta based on GW commitments) represent a large share of Data Center AI sub-segment, concentration risk could be substantial. Exact per-customer revenue not disclosed [Data Gap].

## 2. Cyclicality and Macro Sensitivity

AMD's revenue history shows 3 downturns in 11 years: FY2015 (-27.5%), FY2019 (+4.0%), FY2023 (-3.9%) [income.json]. This is consistent with semiconductor industry ~3-5 year cycle pattern.

**Current cycle signals:**
- Data Center growing +57% YoY in Q1 2026 [transcript_segments.json: Jean Hu]
- Consumer headwinds: "second half gaming revenue to decline more than 20% compared to the first half" due to "higher memory and component costs" [transcript.json: Jean Hu]
- Beta: 2.399 [info.json]; 52-week range $108.62-$506.96 (4.7x swing) [quote.json]

## 3. Technology and Disruption Risk

### 3a. NVIDIA competitive dominance in AI accelerators
- NVIDIA Q1 FY2027 DC: $75.2B (~13x AMD's $5.8B) [claim_verification.json: C007, Verified]
- NVIDIA absolute dollar growth in one quarter ($35.9B DC YoY increase) exceeds AMD's entire quarterly revenue ($10.3B) [ecosystem_signals.md]
- AMD targets >80% CAGR for Instinct GPU revenue in 2027 [transcript.json: Lisa Su]

### 3b. NVIDIA entry into AMD's CPU market
- Vera CPU targeting "$200B agentic AI CPU market," expecting "~$20B in CPU revenue in FY2027" [claim_verification.json: C008, Corroborated]
- Analyst: NVIDIA could "capture two-thirds of the x86 server CPU market" [claim_verification.json: C011, Corroborated: Tom's Hardware]
- Note: Vera is ARM-based, not x86 [claim_verification.json note]
- Lisa Su response: "you're going to see people actually use x86 and ARM for many of the large hyperscalers" [transcript.json: Lisa Su, Q&A]

### 3c. Custom ASIC and in-house silicon
- Google TPU, Amazon Trainium/Inferentia, Microsoft Maia compete with Instinct for internal workloads
- Lisa Su acknowledged custom silicon trend but noted "they're still buying lots of CPUs in the merchant market" — this refers to CPUs not GPUs [transcript.json: Lisa Su]

### 3d. ROCm software ecosystem
- NVIDIA CUDA has multi-decade head start and broader developer ecosystem
- AMD "significantly accelerated ROCm development cadence" and expanded "day 0 support for leading open models" [transcript.json: Lisa Su]
- Software gap creates switching costs for CUDA-based training pipelines [Inference: structural barrier acknowledged by management investment in ROCm] [Sources: transcript.json]

## 4. Regulatory and Geopolitical Risk

### 4a. Export controls — quantified
- Q2 FY2025: ~$800M inventory charge from MI308 export controls [claim_verification.json: C110, Verified; AMD 8-K Aug 5, 2025]
- FY2025 net impact: ~$440M MI308-related charges [claim_verification.json: C092, Verified]
- Q1 2026 China revenue "not material" [transcript.json: Jean Hu, Q&A response to Stacy Rasgon]
- NVIDIA also impacted: $4.5B H20 charge [ecosystem_signals.md]

### 4b. Geographic concentration
- AMD 100% fabless, manufacturing through TSMC (primarily Taiwan) [claim_verification.json: C064, Corroborated]
- Taiwan Strait geopolitical risk affects entire supply chain
- TSMC Arizona fab ramping but advanced capacity remains in Taiwan

### 4c. Tariff exposure
- AMD designs in U.S., manufactures at TSMC (Taiwan), packaging in Asia, sells globally
- Lisa Su mentioned "inflationary pressures" without specifically naming tariffs [transcript.json: Lisa Su, Q&A response to Tim Arcuri]
- [Data Gap: specific tariff exposure by geography not disclosed; 10-K geographic revenue unavailable]

## 5. Execution and Integration Risk

### 5a. Xilinx acquisition
- $49B all-stock acquisition, Feb 2022 [claim_verification.json: C040, Verified]
- Goodwill: $25,126M (32.7% of total assets) [balance.json: FY2025]
- Intangible assets: $16,705M (21.7% of total assets) [balance.json]
- Combined GW + intangibles: $41,831M (54.4% of total assets) [balance.json]
- Embedded segment: $3.5B FY2025, -3% YoY, but 39% operating margin in Q1 2026 [claim_verification.json C074; transcript.json]
- [Inference: $25.1B goodwill creates impairment risk if Embedded segment deteriorates; 39% operating margin provides buffer] [Sources: balance.json, transcript.json]

### 5b. Key person risk
- CEO Lisa Su has led AMD since 2014; retains 3,126,941 shares (~$1.6B at current price) [info.json: ceo; insider.json: securitiesOwned]
- 8-K filings on 2026-01-20 and 2026-02-17 involved "Departure/Election of Directors or Officers" (Item 5.02) [filing_events.json]. Specific officers not identified [Data Gap].

### 5c. Organizational scale-up
- 28,000 employees [info.json]
- OpEx grew 42% YoY in Q1 2026 to $3.1B [transcript.json: Jean Hu]
- Analyst Stacy Rasgon (Bernstein) observed "OpEx been so hard to forecast" [transcript.json: Stacy Rasgon, question]
- Jean Hu: "we have been really building our go-to-market machine" [transcript.json: Jean Hu, response]

## 6. Financial Risk

### 6a. Debt and liquidity
- Net cash position: -$6.1B net debt (using cash+STI) [balance.json]
- Altman Z-Score: 33.57 [scores.json]
- Interest coverage: 32.6x FY2025 [Computed: income.json]

### 6b. SBC dilution
- FY2025 SBC: $1,638M (4.7% of revenue) [cashflow.json; income.json]
- Post-Xilinx diluted share CAGR (FY2022-FY2025): 1.4% [Computed: income.json]
- SBC as % of revenue declining: 6.1% (FY2023) → 4.7% (FY2025) [Computed]

### 6c. Insider selling (May 2026)

| Insider | Role | Date | Shares Sold | Approx. Value |
|---|---|---|---|---|
| Lisa Su | Chair, President & CEO | 2026-05-13 | 19,958 | ~$8.7M |
| Mark Papermaster | CTO & EVP | 2026-05-15 | 6,000 | ~$2.6M |
| Forrest Norrod | EVP & GM DESG | 2026-05-20 | 19,487 | ~$8.4M |

[insider.json] All exercised options and sold in same window. Norrod and Papermaster exercised at low strikes ($34.19 and $84.85) before selling at ~$428-$439. Whether 10b5-1 pre-scheduled plans is not disclosed [Data Gap].

### 6d. Effective tax rate
- FY2025: -2.5% (tax benefit of $103M on $4,166M pretax income) [income.json; ratios.json]
- Negative ETR in 3 of 4 post-Xilinx years [Inference: driven by deferred tax assets from Xilinx and IP structuring; deferred tax liabilities declined from $1,934M (FY2022) to $313M (FY2025)] [Sources: balance.json: deferredTaxLiabilitiesNonCurrent, ratios.json]
- At normalized 21% rate, FY2025 NI would be ~$3.3B vs reported $4.3B — 31.7% uplift from tax benefits [Computed]
- Non-GAAP tax rate guided at 13% [transcript.json: Jean Hu]

### 6e. Working capital / inventory risk
- Inventory: $7,920M FY2025 (+38% YoY) [balance.json]
- DIO: 165 days (FY2025) vs 84 days (FY2021) [metrics.json]
- MI308 precedent: $440M inventory write-down in FY2025 from export controls [claim_verification.json: C092]
- [Inference: $7.9B inventory creates write-down risk if AI demand does not materialize as expected; however, supply-constrained environment and long lead times justify build-ahead] [Sources: balance.json, claim_verification.json C092]

### 6f. Post-acquisition accounting
- GW + intangibles: $41,831M (54.4% of total assets) [balance.json]
- D&A: $3,004M FY2025 (includes ~$2.5B acquisition amortization) [income.json; Inference: baseline D&A ~$500M from FY2021] [Sources: income.json]
- Tangible book value: $35,095M [Computed: balance.json]
- GAAP ROIC (5.4%) below estimated WACC (~16.4%) due to inflated asset base [metrics.json; Computed WACC]

## 7. Supply Chain Concentration

- AMD 100% fabless; dependent on TSMC for all advanced manufacturing [claim_verification.json: C064, Corroborated]
- AMD est. ~7% of TSMC revenue, ~11% CoWoS [claim_verification.json: C021, Single-Source]
- NVIDIA as TSMC's largest customer likely has allocation priority [ecosystem_signals.md]
- HBM sold out through 2026 [claim_verification.json: C084, Corroborated]
- EPYC Venice first HPC product on TSMC 2nm [claim_verification.json: C090, Verified]
- [Inference: AMD's near-term revenue upside may be supply-constrained rather than demand-constrained] [Sources: ecosystem_signals.md, claim_verification.json C021/C023, transcript.json]

## Notable Non-Disclosures

The following are standard industry data points that AMD does not disclose but peers do:
- **Instinct GPU revenue:** NVIDIA discloses Data Center revenue separately; AMD combines CPU+GPU in Data Center segment [Data Gap]
- **Customer concentration:** NVIDIA has disclosed >10% customers; AMD 10-K unavailable this run [Data Gap]
- **Geographic revenue breakdown:** AMD did not address in Q1 2026 call beyond China being "not material" [transcript.json: Jean Hu]
- **Backlog/bookings:** AMD does not disclose order backlog [claim_verification.json: C096, Verified]
- **Capacity utilization:** AMD does not disclose fab/CoWoS utilization rates (TSMC does for its own business)

## Management Deflections in Q1 2026 Q&A

| Topic | Analyst | Question | Management Response | Assessment |
|---|---|---|---|---|
| China DC AI sequential growth | Stacy Rasgon (Bernstein) | Whether DC AI grew sequentially ex-China | Jean Hu repeated China revenue was "not material" without directly answering | Non-answer |
| Instinct gross margins | C.J. Muse (Cantor Fitzgerald) | Whether Instinct margins can approach corporate average | "At this stage, we really focus on driving the topline revenue growth" | Qualitative non-answer to quantitative question |
| OpEx forecasting | Stacy Rasgon (Bernstein) | Why OpEx consistently exceeds guidance | Jean Hu acknowledged investing in "go-to-market machine" | Partial answer; did not address forecasting accuracy |

## Data Gaps

1. **10-K text:** Not available — customer concentration, risk factors, geographic revenue, debt maturities, inventory composition
2. **Proxy (DEF 14A):** proxy.json returned error — executive compensation, governance, related-party transactions not assessed
3. **TSMC allocation specifics:** Single-Source analyst estimates only [claim_verification.json: C021]
4. **Instinct GPU revenue split:** Not disclosed by AMD
5. **Geographic revenue:** Not disclosed beyond "China not material"
6. **Congressional trading:** government.json returned empty (API error 404)
7. **Whether insider sales are 10b5-1 plans:** Not indicated in available Form 4 data
8. **Debt maturity schedule and covenants:** Not available without 10-K
9. **AMD defense/government contract revenue:** Not separately disclosed within Embedded

# Appendix G: Transcript Highlights — AMD Q1 FY2026 Earnings Call

**Call date:** May 5, 2026
**Participants:** Lisa Su (Chair, President & CEO), Jean Hu (EVP, CFO & Treasurer)
**Source:** [transcript.json; transcript_segments.json]

## Revenue and Segment Performance

**Lisa Su, prepared remarks:**
> "First quarter revenue was $10.3 billion, up 38% year-over-year, driven by record Data Center revenue that increased 57% year-over-year to $5.8 billion."
[transcript.json: Lisa Su, Q1 2026]

**Jean Hu, prepared remarks:**
> "Data Center segment revenue was $5.8 billion, up 57% year-over-year and 7% sequentially."
[transcript.json: Jean Hu, Q1 2026]

**Jean Hu on Client & Gaming:**
> "Client and Gaming segment revenue was $3.6 billion, up 23% year-over-year."
[transcript.json: Jean Hu, Q1 2026]

**Jean Hu on Gaming outlook:**
> "We now expect second half gaming revenue to decline more than 20% compared to the first half... due to higher memory and component costs."
[transcript.json: Jean Hu, Q1 2026]

**Jean Hu on Embedded:**
> "Embedded segment revenue was $873 million, up 6% year-over-year... operating income was $338 million, with an operating margin of 39%."
[transcript.json: Jean Hu, Q1 2026]

## AI and Data Center Strategy

**Lisa Su on Data Center primacy:**
> "Data center is now the primary driver of our revenue and earnings growth."
[transcript.json: Lisa Su, Q1 2026]

**Lisa Su on server CPU TAM:**
> "We now believe the server CPU TAM will be greater than $120 billion by 2030."
[transcript.json: Lisa Su, Q1 2026]

**Lisa Su on CPU-to-GPU ratio (Q&A response to Vivek Arya):**
> "The CPU-to-GPU ratio... is changing. It used to be 1:4 or 1:8. Now it's closer to 1:1 or even potentially more CPUs than GPUs in agentic workloads."
[transcript.json: Lisa Su, Q&A]

**Lisa Su on Instinct GPU outlook:**
> "We have strong and increasing confidence in our ability to deliver tens of billions of dollars in annual Data Center AI revenue in 2027."
[transcript.json: Lisa Su, Q1 2026]

**Lisa Su on Instinct GPU CAGR (Q&A response to Joshua Buchalter):**
> "We continue to target greater than 80% CAGR for Instinct GPU revenue."
[transcript.json: Lisa Su, Q&A]

**Lisa Su on MI450 and Helios:**
> "We have begun sampling MI450 series GPUs to lead customers and remain on track to ramp Helios production shipments in the second half of the year."
[transcript.json: Lisa Su, Q1 2026]

**Lisa Su on Meta partnership:**
> "We expanded our strategic partnership with Meta to deploy up to 6 gigawatts of AMD Instinct GPUs spanning several product generations, including a custom GPU accelerator based on our MI450 architecture, co-designed to support Meta's next-generation AI workloads."
[transcript.json: Lisa Su, Q1 2026]

## Supply Chain

**Lisa Su on supply tightness (Q&A response to Blayne Curtis):**
> "The supply chain is tight. I would definitely say that. But I also think this is an area where we excel. We have very deep relationships across the supply chain on the wafer side, on the back end capacity side."
[transcript.json: Lisa Su, Q&A]

**Lisa Su on HBM supply (Q&A response to Vivek Arya):**
> "We are very happy with our partnerships with the memory vendors, and we have secured enough supply to certainly meet and exceed our targets. So it is a tight memory environment."
[transcript.json: Lisa Su, Q&A]

**Lisa Su on capacity expansion:**
> "We are working closely with our supply chain partners to meaningfully increase our wafer and back-end capacities to support this growth."
[transcript.json: Lisa Su, prepared remarks]

## Competitive Positioning

**Lisa Su on EPYC Venice:**
> "Venice widens our competitive advantage, delivering substantially higher performance per socket and per watt versus competitive x86 offerings and more than 2x throughput per socket versus leading ARM-based AI solutions."
[transcript.json: Lisa Su, prepared remarks]

**Lisa Su on ARM competition (Q&A response to Aaron Rakers):**
> "ARM is more point products relative to a portfolio... even for those who are developing their own, they're still buying lots of CPUs in the merchant market."
[transcript.json: Lisa Su, Q&A]

**Lisa Su on ROCm software:**
> "We continue to make strong progress with ROCm... we have significantly accelerated our ROCm development cadence through increased software investments and agent-based coding workflows."
[transcript.json: Lisa Su, Q1 2026]

## Margins and Profitability

**Jean Hu on non-GAAP operating margin:**
> "Operating income was $2.5 billion, representing a 25% operating margin."
[transcript.json: Jean Hu, Q1 2026 — non-GAAP]

**Jean Hu on Q2 gross margin guidance:**
> "Non-GAAP gross margin is expected to be approximately 56%."
[transcript.json: Jean Hu, Q2 2026 outlook]

**Jean Hu on MI450 margins (Q&A response to Ross Seymore):**
> "MI450 will start to ramp... that is below corporate average."
[transcript.json: Jean Hu, Q&A]

**Jean Hu on Instinct margin trajectory (Q&A response to C.J. Muse):**
> "At this stage, we really focus on driving the topline revenue growth on our Instinct family of product."
[transcript.json: Jean Hu, Q&A — did not provide specific margin figures]

## Pricing and Cost Pass-Through

**Lisa Su on cost inflation (Q&A response to Tim Arcuri):**
> "The supply chain is tight... there are some inflationary pressures. Costs have gone up a bit, and we are sharing some of that with our customers. But we are also being very thoughtful in -- look, this is -- we're playing out for the long term."
[transcript.json: Lisa Su, Q&A]

**Lisa Su/Jean Hu on growth drivers (Q&A response to Tim Arcuri):**
> "The majority of the growth is unit driven... ASP is increasing because of the mix where actually each new generation, the core counts, those are increasing, that actually drives the ASP up."
[transcript.json: Lisa Su, Jean Hu, Q&A]

## Capital Allocation

**Jean Hu on free cash flow:**
> "We generated $3 billion in cash from continuing operations and a record $2.6 billion in free cash flow or 25% of revenue."
[transcript.json: Jean Hu, Q1 2026]

**Jean Hu on share repurchases:**
> "We repurchased 1.1 million shares and returned $221 million to shareholders... with $9.2 billion remaining under the repurchase authorization."
[transcript.json: Jean Hu, Q1 2026]

## China/Export Controls

**Jean Hu on China revenue (Q&A response to Stacy Rasgon):**
> "The China revenue in Q1 is not material."
[transcript.json: Jean Hu, Q&A — deflected direct question about whether DC AI grew sequentially ex-China]

**Lisa Su on sequential DC AI decline:**
> "Data Center AI was down modest pace sequentially, primarily due to lower China revenue in the quarter."
[transcript.json: Lisa Su, Q&A response to Thomas O'Malley]

## Long-Term Targets

**Lisa Su on EPS target:**
> "We see a clear path to exceed our long-term financial targets, including delivering more than $20 in EPS over the strategic time frame."
[transcript.json: Lisa Su, Q1 2026]

**Jean Hu on long-term gross margin:**
> "Our Financial Analyst Day target of 55-58% long-term non-GAAP gross margin... we think for the first year, we are [tracking toward those levels]."
[transcript.json: Jean Hu, Q&A response to Ross Seymore]

## Analyst Deflections and Non-Answers

| Analyst | Topic | What Was Asked | Management Response |
|---|---|---|---|
| Stacy Rasgon (Bernstein) | China DC revenue | Whether DC AI grew sequentially ex-China in Q1 | Repeated "China revenue not material" — did not directly answer |
| C.J. Muse (Cantor Fitzgerald) | Instinct margins | Can margins reach corporate average? | "We focus on driving topline revenue growth" — no margin figure given |
| Stacy Rasgon (Bernstein) | OpEx forecasting | Why OpEx exceeds guidance | "Building go-to-market machine" — acknowledged but didn't address forecasting |

# Appendix H: Source Index — AMD

All sources used in this research report, organized by reliability tier and data provider.

## Tier 1: SEC Filings and Company Announcements

| File | Provider | Date/Period | Content |
|---|---|---|---|
| raw/facts.json | EDGAR (XBRL) | Various | XBRL concept data from SEC filings |
| raw/filing_events.json | EDGAR (8-K) | 2024-2026 | Material events: Meta Registration Rights Agreement (2026-02-24), officer departures/elections |
| raw/filings.json | EDGAR | Various | SEC filings list (10-K, 10-Q, 8-K, DEF 14A) |
| raw/filing_search.json | EDGAR (EFTS) | Various | Full-text search of SEC filings |
| raw/edgar_search_risks.json | EDGAR (EFTS) | Various | Risk-related filing searches |
| raw/convertible_search.json | EDGAR (EFTS) | Various | Convertible note search (historical only, 2007-2013) |
| raw/insider_detail.json | EDGAR (Form 4) | Various | Insider transactions from SEC filings |
| raw/holders_detail.json | EDGAR (13F) | Various | Institutional ownership |
| raw/proxy.json | EDGAR (DEF 14A) | 2026-03-27 | Proxy filing — returned error ("Ticker not found") |
| raw/press_releases.md | Company IR / Serper | 2026-05-27 | AMD press releases: Venice announcement (May 21, 2026), OpenAI partnership (Oct 2025) |
| raw/company_ir.md | Company IR / Serper | 2026-05-27 | AMD investor relations page content |
| raw/company_site_ir.json | Company IR / Serper | 2026-05-27 | IR page structure |
| raw/presentations.json | Company IR / FMP | 2026-05-27 | Investor presentation links |

## Tier 2: Financial Data API (FMP)

| File | Provider | Period End | Content |
|---|---|---|---|
| raw/info.json | FMP | Current | Company profile: price, market cap, beta, employees, description |
| raw/quote.json | FMP | Current | Real-time quote: $503.89, market cap, 52-week range |
| raw/income.json | FMP | FY2014-FY2025 | Income statements: revenue, margins, EPS, D&A, R&D |
| raw/balance.json | FMP | FY2018-FY2025 | Balance sheets: debt, cash, goodwill, intangibles, inventory |
| raw/cashflow.json | FMP | FY2015-FY2025 | Cash flows: OCF, capex, FCF, SBC, buybacks, acquisitions |
| raw/metrics.json | FMP | FY2021-FY2025 | Key metrics: ROIC, EV/EBITDA, FCF yield, DIO, DSO, CCC |
| raw/ratios.json | FMP | FY2021-FY2025 | Financial ratios: margins, P/E, debt ratios, tax rate |
| raw/earnings.json | FMP | Q1 FY2024-Q2 FY2026E | Quarterly EPS and revenue actuals/estimates (10 quarters) |
| raw/ratings.json | FMP | FY2026E-FY2030E | Forward estimates, price targets, analyst grades |
| raw/enterprise_value.json | FMP | FY2021-FY2025 | Historical enterprise value components |
| raw/technicals.json | FMP | 2026-05-26 | RSI, SMA, EMA, ADV (30-day) |
| raw/shares_float.json | FMP | 2026-05-25 | Float shares (1,621.9M), outstanding (1,630.6M) |
| raw/peers.json | FMP | Current | Peer companies: AMAT, ARM, ASML, KLAC, LRCX, MU, PLTR, QCOM, SAP, TXN |
| raw/peer_compare.json | FMP | Current | Peer profiles: AMD, ASML, AMAT, ARM |
| raw/insider.json | FMP | 2025-2026 | Insider transactions: Lisa Su, Mark Papermaster, Forrest Norrod |
| raw/holders.json | FMP | Current | Institutional holders |
| raw/holders_analytics.json | FMP | Current | Holder analytics |
| raw/scores.json | FMP | Current | Altman Z-Score (33.57), Piotroski (7/9) |
| raw/dcf.json | FMP | 2026-05-27 | DCF fair value ($51.36) |
| raw/dividends.json | FMP | Current | No dividend history |
| raw/price_history.json | FMP | 1-year | Daily price history (251 data points) |
| raw/options.json | FMP | Current | Options availability (limited data) |
| raw/sector_perf.json | FMP | Current | Sector performance data |
| raw/segments.json | FMP | Error | Empty (FMP API error 404) |
| raw/short_interest.json | FMP | Error | Empty (FMP API error 404) |
| raw/government.json | FMP | Error | Empty (FMP API error 404) |

## Tier 3: Earnings Transcripts

| File | Provider | Period | Content |
|---|---|---|---|
| raw/transcript.json | FMP | Q1 FY2026 (May 5, 2026) | Full earnings call: Lisa Su, Jean Hu prepared remarks + Q&A |
| raw/transcript_segments.json | FMP | Q1 FY2026 | Segment-level commentary extracted from transcript |
| raw/transcript_competitors.json | FMP | Q1 FY2026 | Competitor mentions in transcript |

## Tier 4: Third-Party Research (Web Search)

| File | Provider | Date Pulled | Content |
|---|---|---|---|
| raw/business_overview.md | Serper | 2026-05-27 | AMD business overview from web sources |
| raw/segment_financials.md | Serper | 2026-05-27 | Segment financial data from web sources |
| raw/competitive_by_product.md | Serper | 2026-05-27 | Product-level competitive landscape |
| raw/competitive_history.md | Serper | 2026-05-27 | Competitive landscape evolution |
| raw/competitor_data.md | Serper | 2026-05-27 | Competitor financial data |
| raw/customer_alternatives.md | Serper | 2026-05-27 | Customer switching options |
| raw/customer_capex.md | Serper | 2026-05-27 | Hyperscaler capex outlook |
| raw/supply_demand.md | Serper | 2026-05-27 | Supply/demand dynamics |
| raw/supplier_capacity.md | Serper | 2026-05-27 | TSMC and supplier constraints |
| raw/supply_indicators.md | Serper | 2026-05-27 | Capacity utilization indicators |
| raw/backlog_breakdown.md | Serper | 2026-05-27 | Order pipeline data (limited) |
| raw/value_chain.md | Serper | 2026-05-27 | AMD supply chain analysis |
| raw/revenue_mix.md | Serper | 2026-05-27 | Revenue mix by segment |
| raw/convertible_detail.md | Serper | 2026-05-27 | Convertible debt search (none found) |
| raw/short_interest.md | Serper | 2026-05-27 | Short interest data (~36.1M shares, ~2.2% of float) |
| raw/ecosystem_signals.md | Hermes | 2026-05-27 | Peripheral company signals: NVIDIA Q1 FY2027, TSMC Q1 2026, Microsoft Q3 FY2026 |
| raw/industry.json | Serper | 2026-05-27 | Industry research results |
| raw/news.json | Serper | 2026-05-27 | Recent news (20 items) |

## Derived/Computation Files

| File | Content |
|---|---|
| raw/claim_verification.json | 113 web-sourced claims verified with confidence tags (Verified, Corroborated, Single-Source, Contradicted, Unverifiable) |
| raw/computed_metrics.json | Deterministic metric computations |
| raw/gather_status.json | Data collection status and timing |

## Analysis Files

| File | Content |
|---|---|
| analysis/business_profile.md | Company profile: segments, products, customers, history |
| analysis/competitive_position.md | Competitive analysis: market share, TAM, threats, switching costs |
| analysis/value_chain.md | Value chain: suppliers, customers, margins, integration |
| analysis/financial_data.md | Financial analysis: cap structure, cash flow, returns, valuation |
| analysis/risk_factors.md | Risk enumeration: customer, cyclical, technology, regulatory, financial |

## Data Gaps Summary

| Missing Data | Impact | Why Missing |
|---|---|---|
| 10-K text (latest_10k.json) | Customer concentration, debt maturities, geographic revenue, risk factors | Not fetched in this run |
| Proxy (DEF 14A) | Executive compensation, governance | EDGAR returned error |
| FMP segments data | Segment revenue breakdown | FMP API error 404 |
| FMP short interest | Short interest from primary source | FMP API error 404 |
| Congressional trading | Political exposure | FMP API error 404 |
| Instinct GPU revenue | AI GPU-specific revenue sizing | AMD does not disclose separately |
| TSMC allocation specifics | Supply constraint quantification | Neither AMD nor TSMC discloses |
