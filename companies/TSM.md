---
type: company
ticker: TSM
name: Taiwan Semiconductor Manufacturing Company Limited
sector: Technology
industry: Semiconductors
country: TW
updated: "2026-05-28"
sources:
  - info.json
  - value_chain.md
  - segments.json
  - insider.json
  - holders.json
  - transcript_competitors.json
---

# Taiwan Semiconductor Manufacturing Company Limited (TSM)

## Overview

- **Sector:** Technology
- **Industry:** Semiconductors
- **Country:** TW
- **Website:** https://www.tsmc.com

## Competitors

- Samsung Foundry
- Semiconductor Manufacturing International Corporation
- [Samsung Electronics](SSNLF.md) (SSNLF)
- [GlobalFoundries](GFS.md) (GFS)
- [United Microelectronics Corporation](UMC.md) (UMC)
- [Intel](INTC.md) (INTC)
- SMIC

## Key Insiders

- Chuang Tzu-Sou (officer: VP)
- Huang Jen-Chau (officer: SVP and CFO)
- Liaw Yung-Haw (officer: VP)
- Lin Chris Horng-Dar (officer: VP and CIO)
- Lin Shyue-Shyh (officer: VP)
- Lu Lee-Chung (officer: VP)
- Mii Yuh-Jier (officer: EVP and Co-COO)
- Tien Bor-Zen (officer: VP)
- Wang Ying-Lang (officer: SVP)
- Wei Che-Chia (director, officer: Chairman and CEO)

## Top Institutional Holders

- Ayalon Insurance Comp Ltd.
- Brooklands Fund Management Ltd
- CANTILLON CAPITAL MANAGEMENT LLC
- CASTLEROCK ASSET MANAGEMENT INC
- CASTLEROCK MANAGEMENT LLC
- CAUSEWAY CAPITAL MANAGEMENT LLC
- FCM INVESTMENTS/TX
- FIRSTHAND CAPITAL MANAGEMENT INC
- FIRSTHAND CAPITAL MANAGEMENT INC/CA
- First National Bank of Hutchinson

---

> **⚠️ DRAFT — this report did not pass the citation audit.** Some claims may lack source verification. Treat as preliminary research.

# Taiwan Semiconductor Manufacturing Company Limited (TSM) — Research Report

**Report Date:** May 27, 2026
**Data As Of:** May 26, 2026 (price), FY2025 for annual financials, Q1 2026 for most recent quarter
**Ticker:** TSM | NYSE | Technology | Semiconductors
**Price:** $412.32 [info.json: price]
**ADV:** $5,676MM [info.json: averageVolume 13,766,381 × price $412.32]
**Market Cap:** $2,138.5B [info.json: marketCap] *(Note: FMP computes this as ADR price × all common shares (5,186.5M); since 1 ADR = 5 ordinary shares, the ADR-equivalent market cap is ~$427.7B and the TWD-basis market cap converted at 31.7 TWD/USD is ~$1,558B. P/E ratios remain valid as the 5x factor cancels in numerator and denominator.)*
**Net Debt:** −$65.1B (−3.0% of FMP mkt cap) [balance.json: totalDebt NT$1,064.6B − cashAndShortTermInvestments NT$3,128.3B = NT$−2,063.7B; converted at 31.7 TWD/USD]
**Net Cash:** $65.1B (3.0% of FMP mkt cap) [balance.json: cashAndShortTermInvestments NT$3,128.3B − totalDebt NT$1,064.6B = NT$2,063.7B]
**Enterprise Value:** NT$47,684.2B (~$1,504B at 31.7 TWD/USD) [enterprise_value.json: enterpriseValue]
**Short Interest:** ~0.57% of float (~26.71M shares short / 4,727.2M float shares) [short_interest.md: MarketBeat (Tier 5, Single-Source) + shares_float.json: floatShares; FMP short_interest.json returned 404]

---

## Section 1: Business Overview

<!-- IC Question: What does this company do, how is it organized, and how large is each piece? What would change the answer: Major divestiture, acquisition, segment reclassification, revenue mix shift. -->

### Company Identity

Taiwan Semiconductor Manufacturing Company Limited (TSMC) is a pure-play semiconductor foundry headquartered in Hsinchu Science Park, Hsinchu City, Taiwan. TSMC manufactures, packages, tests, and sells integrated circuits and other semiconductor devices designed by its customers — it does not design its own chips. [info.json: description] The company is listed as an ADR on the NYSE (1 ADR = 5 ordinary shares) and on the Taiwan Stock Exchange (TWSE: 2330). [info.json: isAdr, exchange]

| Field | Value | Source |
|---|---|---|
| CEO | C. C. Wei | [info.json: ceo] |
| Employees | 65,152 full-time | [info.json: fullTimeEmployees] |
| IPO Date (US) | October 9, 1997 | [info.json: ipoDate] |
| Incorporation | 1987 (Taiwan) | [info.json: description] |
| Auditor | Deloitte & Touche (Taiwan) | [claim_verification.json: C080] |

### Single Operating Segment

TSMC reports as a **single operating segment** (semiconductor foundry services) per its SEC filings (20-F). FMP segments.json returned a 404 error, confirming no multi-segment API data is available. [segments.json: segments_message] However, TSMC discloses revenue by platform and by technology node in its quarterly earnings calls. These are management-disclosed breakdowns, not audited reportable segments. [business_profile.md]

### Revenue by Platform — Q1 2026 (Most Recent Quarter)

| Platform | Q1 2026 Revenue (USD) | % of Q1 2026 Total | QoQ Change |
|---|---|---|---|
| **HPC** | $21.95B | 61% | +20% QoQ |
| **Smartphone** | $9.35B | 26% | −11% QoQ |
| **IoT** | $2.16B | 6% | +12% QoQ |
| **Automotive** | $1.44B | 4% | −7% QoQ |
| **DCE** | $0.36B | 1% | +28% QoQ |
| **Others** | ~$0.72B | ~2% | Not disclosed |
| **Total** | **$35.98B** | **100%** | +6.4% QoQ |

[transcript_segments.json: Jen-Chau Huang prepared remarks; earnings.json: Q1 2026 revenueActual = $35,978,710,000. Platform USD amounts computed as total revenue × disclosed percentage. [Inference: percentage × total revenue] [Sources: transcript_segments.json, earnings.json]]

### Revenue by Technology Node — Q1 2026

| Technology Node | % of Wafer Revenue |
|---|---|
| 3nm | 25% |
| 5nm | 36% |
| 7nm | 13% |
| **Advanced (≤7nm)** | **74%** |
| Mature (>7nm) | 26% |

[transcript_segments.json: Jen-Chau Huang Q1 2026 prepared remarks]

### Annual Consolidated Revenue

| Fiscal Year | Revenue (TWD) | Revenue (USD, quarterly sum) | YoY Growth (TWD) |
|---|---|---|---|
| FY2025 | NT$3,848.5B | $123.05B | +33.0% |
| FY2024 | NT$2,894.3B | $88.96B | +33.9% |
| FY2023 | NT$2,161.7B | — | −4.5% |

[income.json: revenue; earnings.json: quarterly actuals summed for USD figures]

**Note:** FMP income.json reports FY2025 total revenue of NT$3,848,511M vs. 20-F net revenue of NT$3,809,054M — a 1.0% discrepancy. [Inference: likely definitional (total revenue vs. net revenue)] [Sources: income.json, claim_verification.json: C045]

### Revenue by Geography — FY2025

North America accounted for 75% of FY2025 net revenue. [claim_verification.json: C023 — Contradicted: TSMC's own 4Q25 Management Report states 75%; Motley Fool secondary source says 76%. The 75% figure from TSMC's own filing is used.] The 75% North America concentration reflects the dominance of U.S.-headquartered fabless chip designers (Nvidia, Apple, AMD, Qualcomm, Broadcom). [Inference: chips fabricated for these customers ship globally, so geographic revenue reflects customer headquarters, not end-use location] [Sources: info.json, claim_verification.json: C023]

### Major Customers

| Customer | FY2025 Revenue Share | Estimated FY2025 Revenue | FY2024 Share |
|---|---|---|---|
| **Nvidia** | ~19% | ~$23.4B | ~12% |
| **Apple** | ~17% | ~$20.9B | ~22% |

[claim_verification.json: C014 — Corroborated: 6+ independent sources including SemiWiki, TechPowerUp citing TSMC filing; Apple's share has minor 17% vs 18% discrepancy across sources]

Nvidia overtook Apple as TSMC's largest customer in FY2025. Other known customers include AMD, Qualcomm, Broadcom, MediaTek, Intel (confirmed as both customer and competitor by CEO C.C. Wei), and Tesla (confirmed by CEO on Q1 2026 call). [transcript_segments.json: C.C. Wei remarks]

### Narrative vs. Reality: AI Revenue

TSMC does not separately break out "AI revenue" as a standalone line item. The closest proxies:

| Metric | Q1 2026 | FY2025 |
|---|---|---|
| Total revenue | $35.98B | $123.05B |
| HPC revenue (disclosed platform) | $21.95B (61%) | ~$70.8B (57.6% of net rev) |
| AI accelerators (mgmt commentary) | Not separately disclosed | "High-teens %" (~$20-22B at 16-18%) |
| Advanced packaging (CoWoS) | Not separately disclosed | ~$9.8B (~8%) |

[AI accelerator dollar amount: [Inference: "high-teens %" × $123.05B] [Sources: claim_verification.json: C015, earnings.json]. CoWoS: claim_verification.json: C038 — Corroborated via Yahoo Finance and GraniteFirm]

HPC is the largest and fastest-growing platform, growing from 40% of revenue in 2022 to 61% in Q1 2026. However, "HPC" includes non-AI workloads (CPUs, FPGAs, networking). AI accelerators specifically are a "high-teens" percentage of total revenue — meaningful but not a majority share of HPC. [Sources: transcript_segments.json, claim_verification.json: C015]

### Brief History

TSMC was incorporated in 1987 in Hsinchu, Taiwan, pioneering the dedicated semiconductor foundry model. It listed ADRs on the NYSE in October 1997. [info.json: description, ipoDate] The company's revenue composition has shifted materially: HPC grew from 40% of revenue in 2022 to 61% in Q1 2026, and Nvidia overtook Apple as the largest customer in FY2025. TSMC is expanding globally with fabs under construction or operating in Arizona (USA), Kumamoto (Japan), and Germany, while continuing to expand in Taiwan. [transcript_segments.json: C.C. Wei; claim_verification.json: C014, C015]

---

## Section 2: Competitive Position

<!-- IC Question: For each product, who competes with this company and what are their relative strengths? What would change the answer: Loss of a top customer, entry of a well-capitalized competitor, customer building in-house alternative, technology disruption. Base rate: What % of companies in this industry lost their competitive position to a new entrant in the past 5 years? In leading-edge foundry, the answer is effectively 0% — no new entrant has gained meaningful share at ≤7nm nodes in the past 5 years. -->

### Overall Market Share

TSMC held an estimated 70–72% share of the global pure-play semiconductor foundry market in 2025. TrendForce reported 70.4% (Q4 2025); Counterpoint Research reported 72% (Q3 2025). [claim_verification.json: C066 — Corroborated: 4 independent sources; C104 — Corroborated: 2 sources] At advanced nodes (≤5nm), TSMC's share is estimated at ~90% of application processor manufacturing. [claim_verification.json: C086 — Corroborated: 3 sources]

TSMC's share has increased from ~54% (2021) to ~72% (2025) as it captured the majority of AI-driven demand growth. [competitive_position.md]

### Leading-Edge Foundry: TSMC vs. Samsung vs. Intel

**Samsung Foundry:**
- Commenced 2nm (SF2) mass production in Q4 2025. [claim_verification.json: C021 — Verified: Samsung earnings press release]
- 2nm yields estimated at 50–60% (averaging ~55%) vs. TSMC's estimated 60–70%. [claim_verification.json: C018 — Contradicted: sources range from 55% (TrendForce/PhoneArena) to >60% (LinkedIn/Fudzilla). The yield gap is directionally confirmed but exact figures vary.]
- Top-tier clients (Apple, Nvidia, AMD) have not committed to Samsung foundry. [claim_verification.json: C020 — Single-Source: PhoneArena]
- Samsung's Galaxy S26 Ultra uses a TSMC-made Qualcomm chip for its premium variant. [claim_verification.json: C019]

**Intel Foundry Services (IFS):**
- ASML noted Intel has "significant existing capacity" but "limited 2026 shipments expected." [ecosystem_signals.md]
- CEO C.C. Wei described Intel as a "formidable competitor" while noting foundry success requires "technology leadership, manufacturing excellence and customer trust." [transcript_segments.json: C.C. Wei]
- Intel has not secured top-tier third-party foundry customers at leading-edge nodes as of Q1 2026.

### Advanced Packaging Competition

TSMC's CoWoS advanced packaging accounted for ~8% of FY2025 revenue (~$9.8B), expected to exceed 10% in FY2026. [claim_verification.json: C038 — Corroborated] CoWoS capacity is "very tight." [transcript_segments.json: C.C. Wei] Intel offers eMIP as a competing packaging technology. OSAT companies (Amkor, ASE) provide packaging services, with TSMC collaborating with OSAT partners to supplement capacity. [transcript_segments.json: C.C. Wei]

### Customer Backward Integration

- **Tesla** announced a "Terafab" initiative and signed a foundry deal with Samsung. [transcript_segments.json: C.C. Wei; claim_verification.json: C020 — Single-Source]
- **Hyperscalers** (Google, Amazon, Microsoft) design custom AI chips but manufacture them at TSMC. This trend increases TSMC's customer count rather than reducing it. [transcript_segments.json: C.C. Wei]

### Pricing Power

TSMC is raising chip prices 5–10% on advanced nodes for 2026. [claim_verification.json: C013 — Corroborated: TrendForce primary source, 6+ secondary] Gross margins expanded from 56.1% (FY2024) → 59.9% (FY2025) → 66.2% (Q1 2026). [income.json; transcript_segments.json]

See **Appendix A** for expanded competitive analysis.

---

## Section 3: Supply/Demand Balance

<!-- IC Question: Is industry supply sufficient to meet demand at current prices, and when does that change? What would change the answer: Major capacity announcement, demand shock, policy change. Base rate: Leading-edge foundry supply/demand imbalances have historically lasted 2-4 years; the current constraint began in 2023. -->

### Demand Drivers

**Revenue trajectory as demand proxy:** TSMC's quarterly revenue has grown from $18.32B (Q1 2024) to $35.98B (Q1 2026), with FY2025 YoY growth of +33.0% in TWD and +35.9% in USD. [earnings.json; claim_verification.json: C036 — Verified]

**HPC/AI demand is the primary growth driver:**
- HPC grew from 40% of revenue (2022) to 61% (Q1 2026). [claim_verification.json: C015 — Corroborated]
- AI accelerators specifically represented a "high-teens" percentage of FY2025 sales (~$20-22B). [claim_verification.json: C015 — Corroborated — note: CAGR projection is forward guidance, not independently verifiable]
- CEO C.C. Wei stated AI accelerator CAGR is "toward higher 50s" through 2029. [transcript_segments.json: C.C. Wei]

**Customer demand signals:**
- Hyperscalers collectively guiding ~$650B aggregate capex in 2026. [claim_verification.json: C075 — Corroborated]
- Broadcom's CEO flagged TSMC capacity as "a bottleneck" that has "kind of choked the supply chain in 2026." [claim_verification.json: C077 — Corroborated]
- Apple reportedly secured >50% of TSMC's 2nm capacity for 2026. [claim_verification.json: C012 — Corroborated: 6+ sources; note: supply chain estimate, not official TSMC/Apple disclosure]

**Forward guidance:** Q2 2026 revenue $39.0–40.2B; FY2026 growth "above 30%" in USD. FY2026 capex toward high end of $52–56B. [claim_verification.json: C064 — Verified; C063 — Verified; C071 — Verified]

### Supply Constraints

**Capacity is "very tight"** across leading-edge nodes through at least 2027:
- CEO C.C. Wei confirmed: "Still, our supply is very tight. Demand is continuing to increase." [transcript_segments.json]
- When asked about supply constraint duration, C.C. Wei confirmed "'27 is also very tight." [transcript_segments.json]
- ASML CEO characterized demand as outpacing supply with constraints expected "beyond 2026." [claim_verification.json: C033 — Corroborated]

**How supply gets added:**
- New fab: 2–3 years to build + 1–2 years to ramp. [transcript_segments.json: C.C. Wei]
- ASML EUV shipments: ≥60 Low NA systems in 2026, ≥80 in 2027. [claim_verification.json: C004 — Corroborated]
- TSMC advanced capacity (5nm to 1.4nm) CAGR: ~30% from 2025 to 2028. [claim_verification.json: C103 — Corroborated]
- CoWoS capacity: 65K–90K WPM range in 2025. [claim_verification.json: C102 — Contradicted: sources disagree on exact figures]

### Supply/Demand Synthesis

Demand exceeds supply at leading-edge nodes through at least 2027. TSMC is capturing value through 5–10% price increases and gross margin expansion (56.1% → 66.2% over 2 years). The main risks to this balance are demand deceleration (e.g., AI capex pullback) or faster-than-expected competitor capacity additions.

See **Appendix B** for expanded supply/demand analysis.

---

## Section 4: Value Chain

<!-- IC Question: Where is value captured, and is it migrating toward or away from this company? What would change the answer: Vertical integration by customer or supplier, margin compression, technology enabling disintermediation. Base rate: Value chain position shifts in semiconductors are rare at this scale; TSMC's foundry position has been stable for 20+ years, though its expansion into packaging is a 3-5 year development. -->

### Value Chain Map

```
[1] Raw Materials → [2] Equipment → [3] TSMC: Wafer Fab → [4] TSMC: Adv Packaging → [5] Testing → [6] Fabless Designers → [7] End Customers
```

TSMC occupies stages [3] and [4], and partially [5]. It does not design chips and does not manufacture equipment. [info.json: description]

### Key Upstream Dependencies

| Input | Supplier(s) | Concentration |
|---|---|---|
| EUV lithography | ASML (sole source) | Single-source; no alternative exists |
| DUV lithography | ASML, Nikon, Canon | Low |
| Deposition/etch/metrology | Applied Materials, Lam Research, Tokyo Electron, KLA | Low |
| Silicon wafers | Shin-Etsu, SUMCO, Siltronic, SK Siltron, GlobalWafers | Low |
| Specialty chemicals/gases | Multiple regions | Low (per management) |
| Energy (Taiwan) | Taipower | Single-source for Taiwan fabs |

[ecosystem_signals.md; claim_verification.json: C053 — Corroborated; transcript_segments.json: Jen-Chau Huang]

**ASML bilateral dependency:** ASML is the sole EUV supplier; TSMC is ASML's largest customer. ASML's FY2025 backlog: €38.8B. [claim_verification.json: C002 — Verified]

### Margin Capture in the Value Chain

TSMC's gross margin (59.9% FY2025, 66.2% Q1 2026) exceeds its most critical equipment supplier ASML (52.8% FY2025). [income.json; claim_verification.json: C001 — Verified] Gross margin expanded 1,320bp from FY2019 (46.0%) to Q1 2026 (66.2%). [income.json; transcript_segments.json]

### Integration Direction

TSMC is expanding into advanced packaging (CoWoS, CoPoS, System on Wafer), capturing margin that would otherwise go to OSATs. CoWoS grew from minimal revenue to ~8% of FY2025 revenue (~$9.8B). [claim_verification.json: C038 — Corroborated] TSMC is **not** integrating forward into chip design. [transcript_segments.json: C.C. Wei]

### Geographic Manufacturing Concentration

The vast majority of leading-edge capacity remains in Taiwan. Overseas fabs under construction/operating:
- **Arizona:** Fab 1 (N4P) in production; Fab 2 (3nm) production H2 2027; third fab land acquired
- **Japan (Kumamoto):** Fab 1 operating; Fab 2 (3nm) planned for 2028
- **Germany (ESMC):** Automotive/industrial applications
[transcript_segments.json: C.C. Wei]

See **Appendix C** for expanded value chain analysis.

---

## Section 5: Capital Structure

<!-- IC Question: How does the company raise money to spend on its business? What would change the answer: Major debt issuance, credit rating change, new equity issuance. -->

### Equity Composition

| Item | Value | Source |
|---|---|---|
| Share class | Single class of ordinary shares (no preferred, no dual-class) | [balance.json: preferredStock: 0] |
| Ordinary shares outstanding | 5,186,200,000 (FY2025 diluted) | [income.json: weightedAverageShsOutDil] |
| ADR ratio | 1 ADR = 5 ordinary shares | [info.json: isAdr] |
| ADR-equivalent shares | ~1,037,240,000 | [Inference: 5,186.2M / 5] [Sources: income.json, info.json] |

### Market Capitalization

FMP reports: $2,138.5B. [info.json: marketCap] This is computed as ADR price × all common shares, overstating the economic market cap by ~5x for this ADR. TWD-basis market cap: NT$49,387.4B (~$1,558B at 31.7 TWD/USD). [enterprise_value.json: marketCapitalization]

### Debt Composition (FY2025)

| Item | Value (TWD) | Approx USD (@31.7) | Source |
|---|---|---|---|
| Short-term debt | NT$136.9B | ~$4.3B | [balance.json: shortTermDebt: 136,925,700,000] |
| Long-term debt | NT$896.1B | ~$28.3B | [balance.json: longTermDebt: 896,062,000,000] |
| Capital lease obligations | NT$31.6B | ~$1.0B | [balance.json: capitalLeaseObligations: 31,595,000,000] |
| **Total debt** | **NT$1,064.6B** | **~$33.6B** | [balance.json: totalDebt: 1,064,582,700,000] |

**Convertible debt:** None identified. EDGAR full-text search returned no TSMC-specific convertible instruments. [convertible_search.json]

**Debt maturity profile:** [Data gap] Specific maturity schedules are not available without 20-F full text. Only short-term vs. long-term breakdown is available.

### Cash and Equivalents

| Item | Value (TWD) | Approx USD (@31.7) | Source |
|---|---|---|---|
| Cash and equivalents | NT$2,767.9B | ~$87.3B | [balance.json: cashAndCashEquivalents: 2,767,856,400,000] |
| Short-term investments | NT$360.4B | ~$11.4B | [balance.json: shortTermInvestments: 360,441,300,000] |
| **Cash + ST investments** | **NT$3,128.3B** | **~$98.7B** | [balance.json: cashAndShortTermInvestments: 3,128,297,700,000] |

### Minority Interest

NT$41.2B (~$1.3B) [balance.json: minorityInterest: 41,180,500,000]

### Enterprise Value

NT$47,684.2B (~$1,504B at 31.7 TWD/USD) [enterprise_value.json: enterpriseValue: 47,684,170,854,093]

### Net Debt / EBITDA

**−0.62x** [metrics.json: netDebtToEBITDA: -0.6188] — TSMC is in a substantial net cash position, with cash exceeding total debt by 2.9x.

See **Appendix D** for full capital structure detail.

---

## Cross-Reference Discrepancies

1. **FY2025 revenue (FMP vs. 20-F):** FMP income.json reports total revenue of NT$3,848,511M; the 20-F net revenue (via StockTitan summary) is NT$3,809,054M — a 1.0% gap. [Inference: likely definitional (total revenue vs. net revenue after deductions)] [Sources: income.json, claim_verification.json: C045]

2. **Apple customer share:** TechPowerUp reports 17%; some other sources report 18%. A 1 percentage point discrepancy. [claim_verification.json: C014]

3. **North America geographic share:** TSMC's own 4Q25 Management Report states 75%; Motley Fool secondary source says 76%. [claim_verification.json: C023]

4. **Samsung 2nm yields:** Estimates range from 50% to >60% depending on source and date. TrendForce/PhoneArena report ~55% (April 2026); LinkedIn/Fudzilla report >60% (March 2026). [claim_verification.json: C018]

5. **CoWoS capacity:** Contradicted across sources — TastyLive says 90K WPM by end-2025; SMBOM.com says 75K WPM; others cite 65K WPM. [claim_verification.json: C102]

6. **FMP market cap for ADR:** FMP's $2,138.5B USD market cap is computed as ADR price × all common shares (not ADR-equivalent shares). Financial data analysis flagged this as a ~5x overstatement vs. economic market cap. The TWD-basis market cap is NT$49,387.4B (~$1,558B). [enterprise_value.json, info.json]

7. **Net cash (risk_factors vs. balance.json):** Risk_factors.md states net cash of TWD 2,063.7B; balance.json shows netDebt of −NT$1,703.3B. The discrepancy: balance.json netDebt = totalDebt − cashAndCashEquivalents (not cashAndShortTermInvestments). Risk_factors used cash + short-term investments. Both are factually correct with different definitions.

## Data Gaps

1. **20-F full text unavailable.** TSMC files 20-F (foreign private issuer), not 10-K. No latest_10k.json exists. Debt maturities, covenants, contract terms, full risk factors are not directly readable.
2. **FMP short interest returned 404.** Short interest data is sourced only from MarketBeat (Tier 5 web source, Single-Source).
3. **AI accelerator revenue not separately disclosed.** "High-teens %" is management commentary from media, not audited.
4. **Customer names come from third-party reporting,** not directly from TSMC's 20-F text available in this dataset.
5. **Samsung foundry revenue not separately reported.** Direct margin comparison impossible.
6. **Wafer ASPs and unit volumes not disclosed.** Revenue growth cannot be decomposed into price vs. volume precisely.
7. **Debt type breakdown unavailable.** Whether TSMC's debt is bonds, bank loans, or credit facilities cannot be determined.
8. **China revenue percentage** beyond "North America 75%" is not in the raw files.
9. **Capacity utilization rate** is not disclosed as a specific percentage.
10. **CHIPS Act subsidy amounts** received by TSMC are not quantified in this dataset.
11. **Filing events empty** — filing_events.json returned 0 events, possibly because TSMC files 6-K (not 8-K) as a foreign private issuer. [filing_events.json]
12. **EDGAR search returned wrong entity** for risk factor search — "Triple-S Management Corp" instead of TSMC. [edgar_search_risks.json]

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

# Appendix A: Competitive Position — TSMC (TSM)

## Market Share

### Overall Foundry Market Share

TSMC held an estimated 70–72% share of the global pure-play semiconductor foundry market in 2025:
- **TrendForce (Q4 2025):** 70.4% foundry market share. [claim_verification.json: C066 — Corroborated: 4 independent sources]
- **Counterpoint Research (Q3 2025):** 72% pure-play foundry share. [claim_verification.json: C104 — Corroborated: 2 sources]
- **IndexBox (H2 2025):** 72% market share. [claim_verification.json: C067 — Corroborated]
- **Yahoo Finance:** "about 70% market share in 2025." [competitive_history.md]

Outlier: matrixbcg.com cited 64% (Q4 2025), possibly reflecting a broader market definition. [claim_verification.json: C070 — Contradicted]. CSIMarket shows 23.60% — this uses total semiconductor industry as denominator, not foundry-specific market. [claim_verification.json: C025 — Unverifiable]

### Advanced Node Market Share

TSMC's share at advanced nodes (≤5nm) is estimated at ~90% of application processor manufacturing. [claim_verification.json: C086 — Corroborated: 3 independent sources] Samsung is the only other foundry producing at 3nm and below.

### Market Share Trajectory

TSMC's share has been stable to slightly gaining over 5 years:
- ~54% (2021) → ~72% (2025), capturing the majority of AI-driven demand growth. [competitive_position.md]
- Revenue growth has been organic — goodwill was NT$5.9B at FY2025 year-end, flat from prior years. [balance.json: goodwill: 5,891,100,000]

**Revenue trajectory (TWD):**

| Year | Revenue (TWD T) | YoY Growth | Gross Margin |
|---|---|---|---|
| FY2020 | 1.34T | — | 53.1% |
| FY2021 | 1.59T | +18.5% | 51.6% |
| FY2022 | 2.26T | +42.6% | 59.6% |
| FY2023 | 2.16T | −4.5% | 54.4% |
| FY2024 | 2.89T | +33.9% | 56.1% |
| FY2025 | 3.85T | +33.0% | 59.9% |

[income.json: revenue, grossProfit, all periods]

In USD: FY2025 revenue was $122.42B (+35.9% YoY). [claim_verification.json: C036 — Verified]

### Competitor Market Shares

- **Samsung Foundry:** Estimated ~10–12% of pure-play + Samsung IDM foundry market. Samsung does not separately report foundry revenue; DS Division reported Q4 2025 revenue of KRW 44.0T (includes Memory and System LSI alongside Foundry). [ecosystem_signals.md]
- **Intel Foundry Services (IFS):** ASML noted "significant existing capacity" but "limited 2026 shipments expected." Third-party customer revenue remains immaterial. [ecosystem_signals.md]
- **Other (GlobalFoundries, UMC, SMIC):** Compete primarily in mature nodes (≥28nm). SMIC is under U.S. export controls limiting EUV access. [competitive_position.md]

---

## TAM Analysis

### Semiconductor Foundry Market Size

- **DIGITIMES:** Taiwan wafer foundry revenue US$133.2B in 2025, projected US$171.7B in 2026 (+30%). [claim_verification.json: C101 — Corroborated]
- **TSMC management ("Foundry 2.0"):** Forecasts industry growth of ~14% YoY in 2026. [claim_verification.json: C099 — Verified]
- **Deloitte (global semiconductor industry):** Total semiconductor sales projected US$975B in 2026, up from ~$770B in 2025 (+26%). [claim_verification.json: C039 — Corroborated; C095 — Corroborated: 4 sources]

The DIGITIMES (+30% foundry) vs. TSMC "Foundry 2.0" (+14%) discrepancy reflects different market definitions. "Foundry 2.0" includes IDM internal manufacturing, backend/packaging, and IC design services. [competitive_position.md]

### TAM Skepticism

TSMC management guided ~20% CAGR over the next five years. [claim_verification.json: C085 — Single-Source: attributed to management but original transcript location not independently confirmed] The 5-year CAGR from FY2020–FY2025 was 23.5% in TWD terms. [Inference: calculated from income.json FY2020 rev TWD 1.34T and FY2025 TWD 3.85T] [Sources: income.json] FY2023 contraction (−4.5% TWD) demonstrates semiconductor demand cyclicality.

### Bottom-Up TAM Construction

1. **HPC/AI (61% of Q1 2026):** AI accelerator wafer demand from Nvidia, AMD, Broadcom, and hyperscaler custom silicon. Hyperscaler aggregate capex ~$650B in 2026. [claim_verification.json: C075 — Corroborated]
2. **Smartphone (26%):** Apple A/M-series, Qualcomm Snapdragon, MediaTek Dimensity. Apple iPhone revenue grew 21.7% YoY in Q2 FY2026. [ecosystem_signals.md: C008 — Verified]
3. **IoT (6%), Automotive (4%), DCE (1%):** Primarily mature-node wafers, more price-sensitive. [transcript_segments.json]

---

## Competitive Landscape by Product

### Leading-Edge Wafer Fabrication (≤7nm)

**TSMC:** N3 in volume production, N2 ramping since Q4 2025, A14/A16 in development. 74% of Q1 2026 wafer revenue from advanced nodes. [transcript_segments.json]

**Samsung:** SF2 (2nm) in early production since Q4 2025. Yields ~55% vs. TSMC ~60–70%. Not profitable at scale on advanced nodes (provisioned costs in Q4 2025). [claim_verification.json: C018, C028]

**Intel IFS:** 18A process announced but "limited 2026 shipments." [ecosystem_signals.md]

### Mature Node Fabrication (>7nm)

More competitive market with UMC, GlobalFoundries, and SMIC competing on price. TSMC's mature node revenue was 26% of Q1 2026 wafer revenue. [transcript_segments.json]

### Advanced Packaging

**TSMC CoWoS:** ~8% of FY2025 revenue (~$9.8B), expected >10% in FY2026. Capacity "very tight." [claim_verification.json: C038 — Corroborated]

**Competitors:** Intel eMIP, OSAT companies (Amkor, ASE). TSMC developing CoWoS-L, CoPoS (pilot line, production in "a couple of years"), System on Wafer. [transcript_segments.json: C.C. Wei]

---

## Switching Costs and Customer Lock-in

### Technical Switching Costs

Chip designs are process-specific. Porting from TSMC N5 to Samsung 5nm requires:
- EDA tool re-configuration
- Physical design re-layout (months of engineering)
- New photomask sets ($1–5M+ per layer)
- Silicon validation/qualification (3–6+ months)

### Financial Switching Costs

Re-designing a leading-edge SoC for a different foundry: estimated $200M–$500M+. [Inference: based on publicly discussed chip design costs at advanced nodes] [Sources: competitive_by_product.md]

### Contractual Lock-in

Major customers negotiate multi-year capacity commitments. Apple reportedly secured >50% of TSMC's 2nm capacity for 2026. [claim_verification.json: C012 — Corroborated: 6+ sources; supply chain estimate, not official disclosure]

### Evidence of Switching

- Galaxy S26 Ultra uses TSMC-made Qualcomm chip; standard S26 uses Samsung 2nm Exynos in some markets. [claim_verification.json: C019 — Contradicted on distribution detail]
- Tesla signed Samsung foundry deal but remains a TSMC customer. [transcript_segments.json: C.C. Wei]
- Nvidia LPU currently at Samsung; TSMC working on next-gen LPU. [transcript_segments.json: C.C. Wei]

---

## Competitive Threats

### Samsung Foundry

- 2nm mass production commenced Q4 2025. [claim_verification.json: C021 — Verified]
- Yields ~55% vs. TSMC ~60–70%. [claim_verification.json: C018 — Contradicted: range varies]
- Samsung improved yields from ~20% to ~55% in under a year.
- Expanding capacity in Taylor, Texas with "real shipment plans" per ASML. [claim_verification.json: C027 — Corroborated]
- Targets double-digit foundry revenue growth in 2026. [ecosystem_signals.md]

### Intel Foundry Services

- "Significant existing capacity" but "limited 2026 shipments." [ecosystem_signals.md]
- No top-tier third-party customers secured.
- C.C. Wei: "formidable competitor" that should not be underestimated. [transcript_segments.json]

### Customer Self-Supply

- Tesla Terafab initiative (Samsung foundry deal). [transcript_segments.json]
- Hyperscaler custom silicon programs increase TSMC customer count (design, not fabrication).

### Advanced Packaging Competition

Intel eMIP competes with CoWoS. TSMC developing CoPoS and SoW. [transcript_segments.json]

---

## Design Win Tracking

TSMC does not disclose individual design wins. Key proxies:
- **N2:** "Strong demand from both smartphone and HPC AI." Apple >50% of N2 capacity. [claim_verification.json: C012]
- **3nm expansion:** Three new N3 fabs announced due to "severe undersupply." [transcript_segments.json]
- **LPU:** Working with Nvidia on next-gen (currently at Samsung). [transcript_segments.json]
- **CoWoS:** Capacity "very tight" with demand from Nvidia, AMD, Broadcom, hyperscalers. [transcript_segments.json]

---

## ASP Trend Analysis

TSMC does not disclose wafer ASPs or unit shipment volumes.

**Mix shift evidence:** Advanced nodes grew from 64% of wafer revenue (mid-2025) to 74% (Q1 2026). [transcript_segments.json]

**Pricing power:** 5–10% price increases on advanced nodes for 2026. [claim_verification.json: C013 — Corroborated] Gross margin expansion (56.1% → 59.9% → 66.2%) implies ASPs rising faster than unit costs. [income.json; transcript_segments.json]

[Inference: FY2025 USD revenue grew ~38%. With 5–10% price increases and mix shift, volume growth was ~25–30%.] [Sources: income.json, claim_verification.json: C013]

---

## Peer Financial Benchmarking

| Metric | TSM (FY2025) | Source |
|---|---|---|
| Gross Margin | 59.9% | [income.json] |
| Operating Margin | 50.8% | [income.json] |
| Net Margin | 45.1% | [income.json] |
| ROIC | 25.1% | [metrics.json] |
| ROE | 32.4% | [metrics.json] |
| Revenue Growth (TWD) | +33.0% | [income.json] |
| Capex/Revenue | 33.4% | [metrics.json] |
| Piotroski Score | 9/9 | [scores.json] |
| Altman Z-Score | 17.0 | [scores.json] |

ROIC trajectory: 18.8% (FY2021) → 24.4% (FY2022) → 17.4% (FY2023) → 20.0% (FY2024) → 25.1% (FY2025). [metrics.json: returnOnInvestedCapital]

No directly comparable publicly-traded pure-play foundries exist at TSMC's scale. Samsung Foundry does not report separately. [competitive_position.md]

---

## Competition Evolution (5-Year Landscape Change)

- **2021–2022:** TSMC ~54% foundry share. Samsung #2 at ~17%.
- **2023:** AI demand accelerating. TSMC experienced cyclical revenue dip (−4.5% TWD) from smartphone/PC weakness.
- **2024–2025:** AI demand expansion. TSMC share rose to 70–72%. Nvidia overtook Apple as largest customer.
- **2026 (current):** Highest gross margins (66.2% Q1 2026), highest market share (70–72%), tightest capacity (sold out through 2027), widest technology lead (2nm yields ~60–70% vs Samsung ~55%).

**Direction of travel:** Market is more concentrated than 5 years ago. Capital barriers rising ($15–20B+ per leading-edge fab vs. $10–15B five years ago). Advanced packaging (CoWoS) creates additional competitive moat. [competitive_position.md]

---

## Regulatory Asymmetries (Foreign-Listed Traits)

- TSMC is Taiwanese (not mainland China); **not subject to HFCAA delisting risk.** [claim_verification.json: C080 — Corroborated]
- **No VIE structure.** Directly lists ADRs backed by common shares on TWSE. [claim_verification.json: C081 — Corroborated]
- 20-F filing discloses FX risk: NT$ fluctuations affect margins by ~30bps per 1% change. [claim_verification.json: C050 — Verified; C052 — Verified]
- U.S. CHIPS Act subsidies support Arizona fabs. U.S. export controls restrict sales to certain Chinese entities.

---

## Industry Capacity Curves

### Installed Capacity by Player (2026)

| Player | Advanced Node Status | Notes |
|---|---|---|
| TSMC | N3 volume, N2 ramping, CoWoS expanding | 70–72% foundry share; "very tight" through 2027 |
| Samsung | SF2 (2nm) early production | Yields ~55%; not profitable at scale |
| Intel (IFS) | 18A announced | "Limited 2026 shipments" per ASML |

### ASML Equipment as Capacity Gate

- 2026: ≥60 Low NA EUV systems. [claim_verification.json: C004 — Corroborated]
- 2027: ≥80 Low NA EUV systems. [claim_verification.json: C004 — Corroborated]
- ASML backlog: €38.8B at end-2025. [claim_verification.json: C002 — Verified]
- High NA EUV: >$380–400M per system. [claim_verification.json: C006 — Corroborated]

### Capacity Addition Timeline

- TSMC Arizona Fab 2 (3nm): H2 2027. [business_profile.md]
- TSMC Kaohsiung GAFAB (N3): H1 2027. [business_profile.md]
- TSMC Japan Fab 2 (3nm): 2028. [business_profile.md]
- Samsung Taylor, TX: "real shipment plans" per ASML. [claim_verification.json: C027]
- TSMC advanced capacity CAGR: ~30% from 2025 to 2028. [claim_verification.json: C103 — Corroborated]

---

## Silence Analysis

### Management Silence

- TSMC does not disclose individual customer names, wafer ASPs, unit volumes, or fab-level utilization rates.
- TSMC does not separately report foundry vs. packaging vs. other services revenue.

### Deflected Questions

- Nvidia LPU at Samsung: C.C. Wei said "Jeff already gave me enough warning" and confirmed work on next-gen without addressing the competitive loss directly. [transcript_segments.json]
- FY2026 growth above 30%: C.C. Wei deferred to July. [transcript_segments.json]
- Capex breakdown: CFO said "we don't have a number to share with you." [transcript_segments.json]

### Filing Gaps

- No audited segment data (single segment). [segments.json]
- Customer names anonymized in 20-F. [claim_verification.json: C014]
- No AI-specific revenue disclosure. [claim_verification.json: C015]
- No 20-F full text available in workspace. [business_profile.md]

---

## Data Gaps

1. Exact Samsung foundry revenue (not separately reported)
2. TSMC wafer ASPs and volumes (not disclosed)
3. CoWoS exact capacity (conflicting estimates: 65K–90K WPM)
4. Intel Foundry customer pipeline (not disclosed)
5. TSMC N2 yield vs. Samsung SF2 yield (both are industry estimates)
6. Full 20-F text (not in workspace)
7. Advanced packaging revenue by product type (CoWoS, InFO not separately disclosed)
8. Competitor design win pipeline (no systematic tracking available)

# Appendix B: Supply/Demand Analysis — TSMC (TSM)

## Demand Analysis

### Revenue Trajectory as Demand Proxy

| Quarter | Revenue (USD) | QoQ | YoY |
|---|---|---|---|
| Q1 2024 | $18.32B | — | — |
| Q2 2024 | $20.66B | +12.8% | — |
| Q3 2024 | $23.60B | +14.2% | — |
| Q4 2024 | $26.38B | +11.8% | — |
| Q1 2025 | $25.80B | −2.2% | +40.8% |
| Q2 2025 | $31.75B | +23.1% | +53.7% |
| Q3 2025 | $32.36B | +1.9% | +37.1% |
| Q4 2025 | $33.14B | +2.4% | +25.6% |
| Q1 2026 | $35.98B | +8.6% | +39.5% |

[earnings.json: revenueActual, all quarters]

### HPC/AI Demand

- HPC grew from 40% of revenue (2022) → 55% (Q4 2025) → 61% (Q1 2026). [claim_verification.json: C015 — Corroborated; transcript_segments.json]
- AI accelerators specifically: "high-teens" percentage of FY2025 sales (~$20–22B at 16–18%). [claim_verification.json: C015 — Corroborated — note CAGR projection is forward guidance]
- CEO C.C. Wei: AI accelerator CAGR "toward higher 50s" through 2029. [transcript_segments.json]

### Customer Demand Signals

- Hyperscaler aggregate capex ~$650B in 2026. [claim_verification.json: C075 — Corroborated: Yahoo Finance $650B; Futurum $690B; Goldman Sachs >$500B]
- Apple iPhone revenue +21.7% YoY in Q2 FY2026 (Mar quarter), Greater China +28.1%. [ecosystem_signals.md: C008 — Verified; C009 — Corroborated]
- Apple secured >50% of TSMC's 2nm capacity for 2026. [claim_verification.json: C012 — Corroborated: 6+ sources; supply chain estimate]
- Broadcom CEO: TSMC capacity "a bottleneck" that "choked the supply chain in 2026." [claim_verification.json: C077 — Corroborated: 3 sources]

### Forward Guidance

- Q2 2026: Revenue $39.0–40.2B, gross margin 65.5–67.5%. [claim_verification.json: C064 — Verified: TSMC IR page]
- FY2026: Revenue growth "above 30%" in USD. [claim_verification.json: C063 — Verified]
- FY2026 capex: Toward high end of $52–56B. [claim_verification.json: C071 — Verified]
- Analyst consensus FY2026 revenue: TWD 5.26T (~$166B at 31.7 TWD/USD). [ratings.json: revenueAvg FY2026]

### Demand Durability

CEO C.C. Wei: "demand continues to be robust and the number continues to be increased, and we double check with our customers, customers' customers, or those CSPs. They gave us a very positive outlook." [transcript_segments.json]

C.C. Wei confirmed capacity constraint extends beyond 2026: "'27 is also very tight." [transcript_segments.json]

---

## Supply Analysis

### Current Supply Constraints

- CEO C.C. Wei: "Still, our supply is very tight. Demand is continuing to increase." [transcript_segments.json]
- 3nm in "severe undersupply" per analyst Haas Liu's characterization (not disputed by management). [transcript_segments.json]
- Advanced packaging (CoWoS) "is very tight also." [transcript_segments.json]

### CoWoS Advanced Packaging Capacity

CoWoS capacity for FY2025: estimated 65,000–90,000 WPM, with conflicting sources:
- TastyLive: 90K WPM by end-2025
- SMBOM.com: 75K WPM
- Other sources: 65K WPM
[claim_verification.json: C102 — Contradicted]

CoWoS accounted for ~8% of FY2025 revenue (~$9.8B), expected >10% in FY2026. [claim_verification.json: C038 — Corroborated]

### How Supply Gets Added

1. **Wafer fab capacity:** 2–3 years to build + 1–2 years to ramp. [transcript_segments.json: C.C. Wei]
2. **EUV equipment:** ASML plans ≥60 Low NA EUV in 2026, ≥80 in 2027. Supply chain prepared for 90 Low NA and 600 DUV annually. [claim_verification.json: C004 — Corroborated]
3. **Advanced packaging:** TSMC expanding CoWoS. One source claims 60% expansion by 2027. [claim_verification.json: C078 — Single-Source: Electronics Weekly] CoPoS pilot line with production "a couple of years" away. [transcript_segments.json]

### Capital Intensity

| Metric | FY2025 | FY2024 | FY2023 |
|---|---|---|---|
| Capex (TWD) | NT$1,285.6B | NT$956.0B | NT$955.4B |
| Capex / Revenue | 33.4% | 33.0% | 44.2% |
| Capex / D&A | 1.85x | 1.44x | 1.80x |

[cashflow.json; metrics.json]

- FY2026 guidance: $52–56B (high end), ~33–35% of expected revenue. [claim_verification.json: C071 — Verified]
- Past 3 years' cumulative capex: $101B. Next 3 years "significantly higher." [transcript_segments.json: Jen-Chau Huang]
- Capex per incremental $ of revenue: FY2024→FY2025 = ~$1.20 capex per $1 incremental annual revenue. [Inference: $40.8B capex / ~$34B revenue increase] [Sources: cashflow.json, earnings.json]

### N2 Ramp

2nm entered high-volume manufacturing Q4 2025. Ramping at Hsinchu and Kaohsiung. Capacity scaling to >100,000 WPM in 2026. [claim_verification.json: C012 — Corroborated] Expected 2–3% gross margin dilution in FY2026. [transcript_segments.json: Jen-Chau Huang]

### Aletheia Capital Estimate

Advanced capacity (5nm to 1.4nm) could more than double from 2025 to 2028, at ~30% CAGR. [claim_verification.json: C103 — Corroborated: 2 sources]

### Contrarian Supply View

One LinkedIn analyst claimed TSMC "is not adding overall capacity in 2026" measured in 12-inch wafer equivalents. [claim_verification.json: C079 — Single-Source: individual analyst post] This is labeled "contrary to the general narrative" by the author and should not be treated as established fact.

---

## Supply/Demand Synthesis

### Net Balance

Demand exceeds supply at leading-edge nodes through at least 2027. CEO C.C. Wei confirmed 2026 "very tight" and 2027 "also very tight." [transcript_segments.json] ASML CEO characterized demand as outpacing supply with constraints "beyond 2026." [claim_verification.json: C033 — Corroborated]

### Pricing Implications

- 5–10% price increases on advanced nodes for 2026. [claim_verification.json: C013 — Corroborated]
- Gross margin expansion: 56.1% (FY2024) → 59.9% (FY2025) → 66.2% (Q1 2026). [income.json; transcript_segments.json]
- Q2 2026 guided gross margin: 65.5–67.5%, slightly below Q1's 66.2%. [Inference: slight sequential decline reflects N2 ramp dilution and 1% forex headwind] [Sources: transcript_segments.json]
- FX sensitivity: ~30bps of gross margin per 1% exchange rate change. [claim_verification.json: C050 — Verified]

### Risks to Current Balance

The main risk to the supply shortage narrative is demand deceleration (e.g., AI capex pullback) or faster-than-expected competitor capacity additions.

---

## AI Value Chain Positioning

**Position:** Foundry/manufacturing layer — TSMC manufactures (but does not design) AI training and inference chips.

**AI revenue quantification:**
- HPC platform: $21.95B Q1 2026 (61% of total). FY2025: NT$2,192,931M (57.6% of net rev). [transcript_segments.json; claim_verification.json: C045]
- AI accelerators specifically: "high-teens" % of FY2025 (~$20–22B). [claim_verification.json: C015 — Corroborated]
- Advanced packaging (CoWoS): ~8% of FY2025 (~$9.8B). [claim_verification.json: C038 — Corroborated]

**Competitive position within AI:** TSMC has ~90% share of advanced processor manufacturing at ≤5nm nodes. [claim_verification.json: C086 — Corroborated] Nvidia (largest customer at ~19%) uses TSMC exclusively for AI GPU manufacturing.

---

## Bargaining Power

### Demand-Side (Customer) Bargaining Power

- Top 2 customers = ~36% of revenue (Nvidia ~19%, Apple ~17%). [claim_verification.json: C014]
- Switching costs are $200M–$500M+ per chip redesign. [Inference] [Sources: competitive_by_product.md]
- In a supply-constrained environment, customers compete for TSMC capacity allocation.

### Supply-Side (Supplier) Bargaining Power

- ASML EUV: sole-source, monopoly supplier. TSMC is ASML's largest customer. Bilateral dependency. [ecosystem_signals.md]
- ASML FY2025 gross margin: 52.8%. [claim_verification.json: C001 — Verified]
- Other equipment suppliers (AMAT, LRCX, TEL, KLA): multiple alternatives, lower concentration risk. [peers.json]
- Raw materials: multi-source, safety stock maintained. [transcript_segments.json: Jen-Chau Huang]

---

## Ecosystem Signals

### ASML (Upstream — Equipment Supplier)

- Record €38.8B backlog; "demand continues to outpace supply." [ecosystem_signals.md; claim_verification.json: C001–C006 — Verified/Corroborated]
- Plans to ship ≥80 EUV systems by 2027. [claim_verification.json: C004]
- Revenue guidance raised to €36–40B for FY2026. [claim_verification.json: C003 — Corroborated]

### Apple (Downstream — Key Customer)

- iPhone revenue +21.7% YoY in Mar 2026 quarter. [ecosystem_signals.md: C008 — Verified]
- Secured >50% of TSMC 2nm capacity. [claim_verification.json: C012 — Corroborated]
- 5–10% wafer price increase for A-series through M5 chips in 2026. [ecosystem_signals.md — Single-Source: TweakTown]

### Samsung (Competitor)

- 2nm mass production commenced Q4 2025, yields ~55% trailing TSMC's ~60–70%. [ecosystem_signals.md]
- Top-tier clients remain on TSMC. [ecosystem_signals.md]
- Galaxy S26 Ultra uses TSMC-made Qualcomm chip — Samsung's own flagship prefers TSMC technology. [ecosystem_signals.md]

---

## Data Gaps

1. TSMC does not report a formal backlog figure — demand characterized qualitatively only.
2. CoWoS exact current capacity vs. planned capacity utilization rates not disclosed.
3. Exact supply/demand equilibrium timing cannot be determined from available data.
4. Volume vs. price decomposition of revenue growth not possible (no ASP/unit data).
5. CoWoS expansion by 2027 (60% claim) is Single-Source. [claim_verification.json: C078]
6. Hyperscaler capex breakdown (semiconductor content as fraction of total) not available.

# Appendix C: Value Chain Analysis — TSMC (TSM)

## Value Chain Map

```
[1] Raw Materials → [2] Equipment → [3] TSMC: Wafer Fabrication → [4] TSMC: Advanced Packaging → [5] Testing → [6] Fabless Designers → [7] End Customers
```

TSMC occupies stages [3] and [4], and partially [5]. [info.json: description]

### Stage Participants

| Value Chain Stage | Key Participants | Approx # Players at Scale | TSMC's Role |
|---|---|---|---|
| Silicon wafers | Shin-Etsu, SUMCO, Siltronic, SK Siltron, GlobalWafers | 5–6 | Buyer |
| Photoresists/chemicals | Shin-Etsu Chemical, Tokyo Ohka Kogyo, JSR, Fujifilm | 4–6 | Buyer |
| Specialty gases | Air Liquide, Linde, Air Products | 3 | Buyer (multi-source) |
| Lithography equipment | ASML (EUV monopoly) | 1 (EUV), 2–3 (DUV) | Buyer (largest customer) |
| Deposition/etch/metrology | Applied Materials, Lam Research, Tokyo Electron, KLA | 4–5 | Buyer |
| **Wafer fabrication (≤7nm)** | **TSMC (~70%), Samsung (~15%), Intel (~5%)** | **3** | **Core business** |
| Wafer fabrication (mature) | TSMC, GlobalFoundries, UMC, SMIC, others | 10+ | In-house |
| Advanced packaging | TSMC (CoWoS), ASE, Amkor, Samsung | 3–4 | In-house (expanding) |
| Testing | TSMC, ASE, Amkor | 3–4 | Partial in-house |
| Photomasks | TSMC (in-house), Photronics | 2 | In-house |

[info.json; ecosystem_signals.md; value_chain.md; claim_verification.json: C053 — Corroborated]

---

## Upstream: Suppliers

### Equipment Suppliers

**ASML (EUV — sole source):**
- Sole manufacturer of EUV lithography for ≤7nm nodes. TSMC is ASML's largest customer. [ecosystem_signals.md]
- FY2025 net sales: €32.7B (+15.5% YoY); backlog: €38.8B; bookings: €28.0B (+48% YoY). [claim_verification.json: C001, C002 — both Verified]
- FY2026 guidance: €36B–€40B revenue. Plans ≥60 Low NA EUV in 2026, ≥80 in 2027. [claim_verification.json: C003, C004 — Corroborated]
- High NA EUV: >$380–400M each. [claim_verification.json: C006 — Corroborated: TechPowerUp ~$380M, CNBC ~$400M]
- Switching costs: effectively zero alternatives for EUV. Bilateral dependency. [ecosystem_signals.md]

**Other equipment:** Applied Materials, Lam Research, Tokyo Electron, KLA. C.C. Wei: "we try very hard to speed it up and pull in all the equipment as we can." [transcript_segments.json]

### Raw Materials

CFO Jen-Chau Huang: "For specialty chemicals and gases, including helium and hydrogen, we source from multiple suppliers in different regions, and we have prepared safety stock inventory on hand." [transcript_segments.json]

Identified suppliers: Shin-Etsu Chemical (wafers, photoresists), SUMCO (wafers), Tokyo Ohka Kogyo (photoresists), Photronics (photomasks), MKS Instruments (confirmed as TSMC supplier). [claim_verification.json: C053 — Corroborated]

### Energy

- TSMC depends on Taipower for Taiwan operations. [transcript_segments.json: Jen-Chau Huang]
- Taiwan government secured sufficient LNG through at least May 2026. [transcript_segments.json]
- Single-geography dependency for the majority of manufacturing.

### Supplier Concentration Summary

| Input Category | # Sources | Single-Source Risk | Evidence |
|---|---|---|---|
| EUV lithography | 1 (ASML) | Yes | [ecosystem_signals.md] |
| DUV lithography | 2–3 | Low | [Inference] |
| Deposition/etch | 3–4 | Low | [peers.json] |
| Silicon wafers | 5–6 | Low | [claim_verification.json: C053] |
| Chemicals/gases | Multiple | Low (per mgmt) | [transcript_segments.json] |
| Energy | 1 (Taipower) | Yes (Taiwan) | [transcript_segments.json] |
| Photomasks | In-house + Photronics | Low | [info.json] |

**China supply chain auditing:** TSMC reportedly auditing suppliers with high China reliance, may exclude some in 2026. [claim_verification.json: C055 — Single-Source: social media post; DigiTimes reported partial confirmation but TSMC declined to comment]

---

## Downstream: Customers

### Customer Concentration

| Customer | FY2025 Share | Est. Revenue | FY2024 Share |
|---|---|---|---|
| Nvidia | ~19% | ~$23.4B | ~12% |
| Apple | ~17% | ~$20.9B | ~22% |

[claim_verification.json: C014 — Corroborated]

Projected FY2026: Nvidia ~22% (~$33B), Apple ~18% (~$27B). [ecosystem_signals.md]

Other customers: AMD, Qualcomm, Broadcom, MediaTek, Intel (customer and competitor), Tesla. [transcript_segments.json]

### Geographic Revenue

North America: 75% of FY2025 net revenue. [claim_verification.json: C023] This reflects customer headquarters, not chip end-use location. [Inference: standard industry practice] [Sources: info.json, claim_verification.json: C023]

### Customer Switching Costs

1. Design-in lock-in (12–18+ months re-design). [Inference] [Sources: transcript_segments.json]
2. Yield dependency (TSMC ~60–70% vs Samsung ~55% at 2nm). [ecosystem_signals.md; claim_verification.json: C016]
3. Advanced packaging integration (CoWoS tighter front-end/back-end coupling).
4. Capacity allocation risk in supply-constrained environment.

### Contract Structure

- Deferred revenue: NT$0 in both FY2025 and FY2024. [balance.json: deferredRevenue: 0]
- Accounts receivable days: 26 days Q1 2026. [transcript_segments.json]
- No disclosed long-term take-or-pay contracts in available data. [Data gap: 20-F text not available]

---

## Margin Capture Analysis

### TSMC Margin Trajectory

| Fiscal Year | Revenue (NT$B) | Gross Margin | Operating Margin |
|---|---|---|---|
| FY2019 | 1,070.0 | 46.0% | 34.8% |
| FY2020 | 1,339.3 | 53.1% | 42.3% |
| FY2021 | 1,587.4 | 51.6% | 40.9% |
| FY2022 | 2,263.9 | 59.6% | 49.5% |
| FY2023 | 2,161.7 | 54.4% | 42.6% |
| FY2024 | 2,894.3 | 56.1% | 45.7% |
| FY2025 | 3,848.5 | 59.9% | 50.8% |
| **Q1 2026** | **1,134.1 (qtr)** | **66.2%** | **58.1%** |

[income.json; transcript_segments.json]

### Margin Drivers (Q1 2026)

- Cost improvement efforts. [transcript_segments.json: Jen-Chau Huang]
- Higher overall capacity utilization (exceeded guidance by 120bps). [transcript_segments.json]
- Favorable foreign exchange rate. [transcript_segments.json]

### Margin Headwinds/Tailwinds

- **Headwind:** 2nm ramp: 2–3% GM dilution for FY2026. [transcript_segments.json]
- **Headwind:** Overseas fabs: 2–3% dilution initially, 3–4% later. [transcript_segments.json]
- **Tailwind:** N3 crossing corporate average GM in H2 2026. [transcript_segments.json]

### Where Margin Sits in the Chain

| Stage | Company | FY2025 Gross Margin |
|---|---|---|
| EUV equipment | ASML | 52.8% [claim_verification.json: C001 — Verified] |
| **Foundry** | **TSMC** | **59.9%** [income.json] |
| Fabless (GPU) | Nvidia | ~73–75% [Data gap: not in workspace] |

### Pricing Power Evidence

- 5–10% price increases for 2026 on advanced nodes. [claim_verification.json: C013 — Corroborated]
- C.C. Wei: "Of course, we know our value; of course, we know our position." [transcript_segments.json]

### Margin Migration

Advanced technologies (≤7nm) grew from 64% to 74% of wafer revenue (mid-2025 to Q1 2026). [transcript_segments.json] In FY2025, advanced technologies were 77% of total wafer revenue. [claim_verification.json: C057 — Verified]

---

## Integration Direction

### Forward (Toward Customers)

TSMC is NOT integrating into chip design. Pure-play foundry model is a strategic principle. [transcript_segments.json: C.C. Wei]

### Backward (Toward Suppliers)

1. **Advanced Packaging:** CoWoS grew from minimal to ~8% of FY2025 revenue (~$9.8B). CoPoS pilot line built. System on Wafer in development. [claim_verification.json: C038; transcript_segments.json]
2. **Photomask Manufacturing:** In-house. [info.json: description]

### Customer/Supplier Integration Toward TSMC

- Intel: operating IFS (customer + competitor). [transcript_segments.json]
- Tesla: Terafab + Samsung deal (customer + competitor). [transcript_segments.json]
- Hyperscalers: designing custom chips but manufacturing at TSMC (increases customer base). [transcript_segments.json]

---

## Vertical Integration Assessment

| Stage | Level | Change Over 3Y |
|---|---|---|
| Raw materials | Outsourced | Stable |
| Equipment | Outsourced | Stable |
| Photomasks | In-house | Stable |
| Wafer fabrication | In-house (core) | Expanding (new fabs) |
| Advanced packaging | In-house (expanding) | **Integrating** — CoWoS grew to ~8% of rev |
| Testing | Partial in-house | Stable |
| Chip design | Not integrated | Stable (by design) |

---

## Dependencies and Vulnerabilities

### Single Points of Failure

| Dependency | Evidence |
|---|---|
| ASML EUV | Sole source; no alternative [ecosystem_signals.md] |
| Taiwan manufacturing concentration | Prioritizes Taiwan for newest nodes [transcript_segments.json] |
| Taipower energy | Single utility for Taiwan ops [transcript_segments.json] |
| Advanced node capacity | Supply < demand through ≥2027 [transcript_segments.json] |

### Technology Dependencies

- EUV lithography (ASML sole source). [ecosystem_signals.md]
- High NA EUV for future nodes (>$400M each). [claim_verification.json: C006]
- HBM integration in CoWoS (produced by SK Hynix, Samsung, Micron). [Inference: known AI accelerator architecture] [Sources: transcript_segments.json]

### Cross-Border Regulatory Risks

- U.S. export controls restrict equipment/technology flows to China. [claim_verification.json: C055]
- U.S. CHIPS Act subsidies support Arizona expansion.
- Taiwan Strait geopolitical risk is the most frequently cited risk but not quantifiable from financial data.
- FX sensitivity: ~30bps gross margin per 1% exchange rate change. [claim_verification.json: C050 — Verified]

---

## Capex and Capacity Investment

| FY | Capex (NT$B) | Capex/Revenue | Capex/D&A |
|---|---|---|---|
| 2019 | 469.8 | 43.9% | 1.64x |
| 2020 | 521.5 | 38.9% | 1.57x |
| 2021 | 849.4 | 53.5% | 2.01x |
| 2022 | 1,089.6 | 48.1% | 2.49x |
| 2023 | 955.4 | 44.2% | 1.80x |
| 2024 | 956.0 | 33.0% | 1.44x |
| 2025 | 1,285.6 | 33.4% | 1.85x |
| **2026E** | **~$52–56B** | **~33%** | **~2.3–2.5x** |

[cashflow.json; transcript_segments.json]

---

## Data Gaps

1. No 20-F filing text — contract terms, detailed risk factors unverifiable.
2. Supplier revenue concentration — whether ASML exceeds 10% of TSMC's COGS not known.
3. No formal backlog/order book — demand characterized qualitatively only.
4. EDGAR search returned wrong entity (Triple-S Management Corp). [edgar_search_risks.json]
5. Samsung Foundry revenue not separately reported.
6. Wafer pricing data not disclosed; 5–10% price increase claim is Single-Source in ecosystem_signals.md.
7. CoWoS capacity specifics contradicted across sources.

# Appendix D: Capital Structure — TSMC (TSM)

All financial statement data is denominated in TWD (New Taiwan Dollar) unless noted. TSMC reports under IFRS as a foreign private issuer (20-F). 1 ADR = 5 ordinary shares. [info.json: isAdr]

---

## Equity Composition

| Item | Value | Source |
|---|---|---|
| Share class | Single class of ordinary shares | [balance.json: preferredStock: 0] |
| Preferred stock | None (NT$0) | [balance.json: preferredStock: 0] |
| Dual-class | No | [balance.json: commonStock single entry] |
| Ordinary shares outstanding (diluted, FY2025) | 5,186,200,000 | [income.json: weightedAverageShsOutDil] |
| Ordinary shares outstanding (basic, FY2025) | 5,186,949,600 | [income.json: weightedAverageShsOut] |
| ADR ratio | 1 ADR = 5 ordinary shares | [info.json: isAdr] |
| ADR-equivalent share count | ~1,037,240,000 | [Inference: 5,186.2M / 5] [Sources: income.json, info.json] |
| Treasury stock | NT$0 | [balance.json: treasuryStock: 0] |
| Common stock (par value) | NT$259.3B | [balance.json: commonStock: 259,325,300,000] |
| Additional paid-in capital | NT$73.4B | [balance.json: additionalPaidInCapital: 73,445,600,000] |
| Retained earnings | NT$5,038.9B | [balance.json: retainedEarnings: 5,038,944,200,000] |
| AOCI | NT$0 | [balance.json: accumulatedOtherComprehensiveIncomeLoss: 0] |
| Other stockholders' equity | −NT$16.7B | [balance.json: otherTotalStockholdersEquity: -16,676,400,000] |
| **Total stockholders' equity** | **NT$5,355.0B** | [balance.json: totalStockholdersEquity: 5,355,038,700,000] |

Share dilution is negligible: diluted shares (5,186.2M) are virtually identical to basic shares (5,186.9M). SBC was NT$0 in FY2025, NT$1.6B in FY2024 (0.057% of revenue). [cashflow.json: stockBasedCompensation; metrics.json: stockBasedCompensationToRevenue]

---

## Market Capitalization

| Measure | Value | Source |
|---|---|---|
| FMP USD market cap | $2,138.5B | [info.json: marketCap] |
| TWD-basis market cap (year-end FY2025) | NT$49,387.4B | [enterprise_value.json: marketCapitalization] |
| Approx USD market cap (NT$49,387B ÷ 31.7) | ~$1,558B | [Inference: TWD mktcap / mgmt FX rate] [Sources: enterprise_value.json, transcript.json] |

Note: FMP computes USD market cap as ADR price ($412.32) × all common shares (5,186.5M) = $2,138.5B. Since 1 ADR = 5 ordinary shares, this overstates the economic USD market cap by ~5x. The TWD-basis figure converted at 31.7 TWD/USD gives ~$1,558B. [financial_data.md]

---

## Debt Composition (FY2025)

| Item | Value (TWD) | Approx USD (@31.7) | Source |
|---|---|---|---|
| Short-term debt | NT$136,925,700,000 | ~$4.3B | [balance.json: shortTermDebt] |
| Long-term debt | NT$896,062,000,000 | ~$28.3B | [balance.json: longTermDebt] |
| Capital lease obligations (current) | NT$0 | $0 | [balance.json: capitalLeaseObligationsCurrent: 0] |
| Capital lease obligations (non-current) | NT$31,595,000,000 | ~$1.0B | [balance.json: capitalLeaseObligationsNonCurrent] |
| **Total debt** | **NT$1,064,582,700,000** | **~$33.6B** | [balance.json: totalDebt] |

### Debt Type Breakdown

[Data gap] Whether TSMC's debt is bonds, bank loans, or credit facilities cannot be determined without 20-F full text, which is not available in this workspace.

### Debt Maturity Profile

[Data gap] Specific maturity schedules by year are not available. Only the short-term (NT$136.9B, due within 1 year) vs. long-term (NT$896.1B, due beyond 1 year) split is known. [balance.json]

### Debt Trajectory

| FY | Total Debt (NT$B) | Short-term (NT$B) | Long-term (NT$B) |
|---|---|---|---|
| 2025 | 1,064.6 | 136.9 | 896.1 |
| 2024 | 1,047.0 | 59.9 | 962.0 |
| 2023 | 956.3 | — | — |
| 2022 | 888.2 | — | — |
| 2021 | 753.6 | — | — |

[balance.json: totalDebt, shortTermDebt, longTermDebt — FY2025 and FY2024]

---

## Convertible Securities

No convertible debt outstanding. EDGAR full-text search (convertible_search.json) returned 112 results, none pertaining to TSMC. [convertible_search.json]

---

## Cash and Equivalents

| Item | FY2025 (TWD) | FY2024 (TWD) | Source |
|---|---|---|---|
| Cash and equivalents | NT$2,767,856,400,000 | NT$2,127,627,000,000 | [balance.json: cashAndCashEquivalents] |
| Short-term investments | NT$360,441,300,000 | NT$357,520,000,000 | [balance.json: shortTermInvestments] |
| **Cash + ST investments** | **NT$3,128,297,700,000** | **NT$2,485,147,000,000** | [balance.json: cashAndShortTermInvestments] |
| Long-term investments | NT$172,189,000,000 | NT$148,867,000,000 | [balance.json: longTermInvestments] |

Net cash position: NT$2,063.7B ($65.1B at 31.7 TWD/USD). Cash exceeds total debt by 2.9x. [Inference: 3,128.3 / 1,064.6 = 2.94x] [Sources: balance.json]

balance.json reports netDebt = −NT$1,703,273,700,000, which uses the narrower definition: totalDebt − cashAndCashEquivalents (excluding short-term investments). [balance.json: netDebt]

---

## Minority Interest

NT$41,180,500,000 (~$1.3B) [balance.json: minorityInterest]

Total equity (including minority): NT$5,396,219,200,000. [balance.json: totalEquity]

---

## Enterprise Value

| Component | Value (TWD) | Source |
|---|---|---|
| Market capitalization | NT$49,387,444,554,093 | [enterprise_value.json: marketCapitalization] |
| Plus: Total debt | NT$1,064,582,700,000 | [enterprise_value.json: addTotalDebt] |
| Less: Cash and equivalents | NT$2,767,856,400,000 | [enterprise_value.json: minusCashAndCashEquivalents] |
| **Enterprise Value** | **NT$47,684,170,854,093** | [enterprise_value.json: enterpriseValue] |

Approximate USD: ~$1,504B at 31.7 TWD/USD. [Inference: NT$47,684B / 31.7] [Sources: enterprise_value.json, transcript.json]

---

## Net Debt / EBITDA

**−0.62x** [metrics.json: netDebtToEBITDA: -0.6188]

FY2025 EBITDA: NT$2,752.5B. [income.json: ebitda: 2,752,481,885,000]

TSMC is in a substantial net cash position. The negative Net Debt/EBITDA ratio reflects cash exceeding debt. [Inference: net debt is negative because cash > debt] [Sources: metrics.json, balance.json]

---

## Interest Expense

FY2025 interest expense: NT$0 as reported in income.json. [income.json: interestExpense: 0] This may reflect IFRS netting against interest income (NT$94.3B) or reclassification. Interest paid per cash flow statement: NT$18.3B in FY2025, NT$18.8B in FY2024. [cashflow.json: interestPaid]

FY2024 interest expense on income statement: NT$10.5B. Interest coverage ratio FY2024: 126.0x. [ratios.json: interestCoverageRatio]

---

## Debt-to-Equity and Leverage Ratios

| Ratio | FY2025 | FY2024 | FY2023 | Source |
|---|---|---|---|---|
| Debt/Equity | 0.199 | 0.247 | 0.279 | [ratios.json: debtToEquityRatio] |
| Debt/Assets | 0.134 | 0.156 | 0.173 | [ratios.json: debtToAssetsRatio] |
| Financial leverage | 1.481 | 1.577 | 1.613 | [ratios.json: financialLeverageRatio] |
| Current ratio | 2.507 | 2.360 | 2.329 | [metrics.json: currentRatio] |

Leverage is declining over time as equity grows from retained earnings. [balance.json: totalStockholdersEquity]

# Appendix E: Key Stats — TSMC (TSM)

## Price and Technicals

| Metric | Value | Computation | Source |
|---|---|---|---|
| ADR Price | $412.32 | — | [quote.json: price] |
| 52-week High | $421.97 | — | [quote.json: yearHigh] |
| 52-week Low | $190.56 | — | [quote.json: yearLow] |
| Day High | $416.49 | — | [quote.json: dayHigh] |
| Day Low | $410.07 | — | [quote.json: dayLow] |
| Previous Close | $404.52 | — | [quote.json: previousClose] |
| ADV (30d, notional) | $5,331.7M | avg_volume_30d × current price | [technicals.json: adv_30d: 5,331,733,206] |
| ADV (from info.json) | $5,676.2M | 13,766,381 × $412.32 | [info.json: averageVolume; quote.json: price] |
| Avg Volume (30d) | 13,210,581 shares | — | [technicals.json: avg_volume_30d] |
| RSI (14) | 58.8 | — | [technicals.json: rsi_14] |
| 21d EMA | $399.0 | — | [technicals.json: ema_21d] |
| 50d SMA | $374.59 | — | [quote.json: priceAvg50] |
| 200d SMA | $318.69 | — | [quote.json: priceAvg200] |
| Beta | 1.264 | — | [info.json: beta] |

---

## Valuation Multiples (Recalculated at Current Price)

| Metric | Value | Calculation | Source |
|---|---|---|---|
| **Trailing P/E (TTM)** | **34.2x** | $412.32 ÷ $12.04 TTM EPS | TTM EPS = Q1'26 $3.49 + Q4'25 $3.09 + Q3'25 $2.85 + Q2'25 $2.61. [quote.json; earnings.json] |
| **FY2025 Annual P/E** | **38.6x** | $412.32 ÷ $10.69 | FY2025 EPS = sum of FY2025 quarterly actuals: $2.14 + $2.61 + $2.85 + $3.09. [earnings.json; income.json: epsDiluted 334.65 TWD — FMP USD EPS used] |
| **Forward P/E (FY2026E)** | **~25.8x** | $412.32 ÷ ~$16.00 est. | [Inference: FY2025 USD EPS $10.69 × (FY2026 TWD consensus EPS 500.99 / FY2025 TWD actual 334.65)] [Sources: earnings.json, ratings.json, income.json] |
| EV/EBITDA (year-end FY2025) | 17.3x | NT$47,684B ÷ NT$2,752B | [metrics.json: evToEBITDA] |
| EV/Revenue (year-end FY2025) | 12.4x | — | [metrics.json: evToSales] |
| P/FCF (year-end FY2025) | 45.0x | — | [ratios.json: priceToFreeCashFlowRatio: 44.997] |
| FCF Yield (year-end) | 2.22% | — | [metrics.json: freeCashFlowYield] |
| Earnings Yield | 3.51% | — | [metrics.json: earningsYield] |
| P/B (year-end FY2025) | 9.22x | — | [ratios.json: priceToBookRatio] |
| Dividend Yield | ~0.95% | — | [ratios.json: dividendYieldPercentage: 0.955] |
| Last ADR Dividend | $3.1728 | — | [info.json: lastDividend] |
| Graham Number | TWD 557.6 | — | [metrics.json: grahamNumber] |

**Note:** EV/EBITDA, EV/Revenue, P/FCF, P/B are based on year-end market pricing (TWD 9,521.48 per share). At the current ADR price of $412.32 (near 52-week high), these multiples would be proportionally higher. [enterprise_value.json; quote.json]

---

## Earnings History (Beat/Miss)

| Quarter | EPS Actual | EPS Est. | EPS Diff | Rev Actual | Rev Est. | Rev Diff |
|---|---|---|---|---|---|---|
| Q1 2026 | $3.49 | $3.31 | +$0.18 (Beat) | $35.98B | $35.35B | +$628M |
| Q4 2025 | $3.09 | $2.90 | +$0.19 (Beat) | $33.14B | $33.01B | +$130M |
| Q3 2025 | $2.85 | $2.63 | +$0.22 (Beat) | $32.36B | $32.07B | +$287M |
| Q2 2025 | $2.61 | $2.38 | +$0.23 (Beat) | $31.75B | $30.21B | +$1,541M |
| Q1 2025 | $2.14 | $2.07 | +$0.07 (Beat) | $25.80B | $25.46B | +$344M |
| Q4 2024 | $2.19 | $2.20 | −$0.01 (Miss) | $26.38B | $26.24B | +$138M |
| Q3 2024 | $1.95 | $1.79 | +$0.16 (Beat) | $23.60B | $23.31B | +$293M |
| Q2 2024 | $1.47 | $1.41 | +$0.06 (Beat) | $20.66B | $20.33B | +$332M |
| Q1 2024 | $1.34 | $1.30 | +$0.04 (Beat) | $18.32B | $18.32B | +$5M |

[earnings.json: epsActual, epsEstimated, revenueActual, revenueEstimated]

EPS beat in 8 of 9 quarters; revenue beat in 9 of 9 quarters. The one EPS miss (Q4 2024: −$0.01) was negligible (0.5% below estimate).

---

## Short Interest

| Metric | Value | Source |
|---|---|---|
| Float shares | 4,727,211,727 | [shares_float.json: floatShares] |
| Free float % | 91.14% | [shares_float.json: freeFloat] |
| Outstanding shares | 5,186,500,000 | [shares_float.json: outstandingShares] |
| Short interest (shares) | ~26.71M | [short_interest.md — MarketBeat, Tier 5, Single-Source] |
| SI % of float | ~0.57% | [Inference: 26.71M / 4,727.2M] [Sources: short_interest.md, shares_float.json] |
| Days to cover | ~1.7 | [short_interest.md — MarketBeat, Tier 5, Single-Source] |

FMP short_interest.json returned 404 error. Short interest data sourced only from MarketBeat web snippet. [short_interest.json; short_interest.md]

Note: competitive_position.md cites 26.71M shares and 0.52% of public float (from claim_verification.json: C096, C097 — Corroborated: MarketBeat, MarketWatch, FinViz report identical figures). The computed 0.57% using floatShares of 4,727M vs. the 0.52% reported by MarketBeat may reflect a difference in float definition. Both indicate minimal short interest.

---

## Financial Quality Scores

| Score | Value | Source |
|---|---|---|
| Altman Z-Score | 17.0 | [scores.json: altmanZScore: 17.007] |
| Piotroski F-Score | 9/9 | [scores.json: piotroskiScore: 9] |

Z-Score of 17.0 is well above the 3.0 threshold. Piotroski 9/9 indicates passing all nine financial strength criteria. [scores.json]

Note: scores.json appears to use TTM figures (revenue NT$4,113.8B) rather than FY2025 annual (NT$3,848.5B). [Inference: scores.json includes Q1 2026 in TTM] [Sources: scores.json, income.json]

---

## Returns on Capital

| Metric | FY2025 | FY2024 | FY2023 | FY2022 | FY2021 |
|---|---|---|---|---|---|
| ROIC | 25.1% | 20.0% | 17.4% | 24.4% | 18.8% |
| ROCE | 30.5% | 24.6% | 20.1% | 28.2% | 21.9% |
| ROA | 21.9% | 17.3% | 15.4% | 20.0% | 15.9% |
| ROE | 32.4% | 27.3% | 24.8% | 34.2% | 27.6% |

[metrics.json]

### ROIC vs. WACC

| Component | Value | Source |
|---|---|---|
| Cost of equity (CAPM) | ~10.5% | [Inference: 4.2% RF + 1.264β × 5.0% ERP] [Sources: info.json: beta] |
| After-tax cost of debt | ~0.84% | [Inference: ~1.0% pre-tax × (1 − 16%)] [Sources: income.json, balance.json] |
| Estimated WACC | ~10.3% | [Inference: 97.9% equity × 10.5% + 2.1% debt × 0.84%] |
| **ROIC − WACC spread (FY2025)** | **+14.8pp** | [Sources: metrics.json, calculated WACC] |

Spread has been positive in every year: FY2021 +8.5pp, FY2022 +14.1pp, FY2023 +7.1pp, FY2024 +9.7pp, FY2025 +14.8pp. [Inference] [Sources: metrics.json]

---

## Cash Flow Summary

| Metric | FY2025 | FY2024 | FY2023 |
|---|---|---|---|
| Operating CF (NT$T) | 2.38 | 1.83 | 1.24 |
| CapEx (NT$T) | 1.29 | 0.96 | 0.96 |
| FCF (NT$T) | 1.10 | 0.87 | 0.29 |
| FCF margin | 28.5% | 30.1% | 13.3% |
| Income quality (OCF/NI) | 1.37x | 1.56x | 1.48x |

[cashflow.json; income.json; metrics.json]

---

## Margin Summary

| Metric | FY2025 | FY2024 | FY2023 | Q1 2026 |
|---|---|---|---|---|
| Gross margin | 59.9% | 56.1% | 54.4% | 66.2% |
| Operating margin | 50.8% | 45.7% | 42.6% | 58.1% |
| Net margin | 45.1% | 40.0% | 39.4% | — |
| EBITDA margin | 71.5% | 68.6% | 70.5% | — |
| R&D / revenue | 6.5% | 7.1% | 8.4% | — |

[income.json; ratios.json; transcript_segments.json]

---

## Greenwald Value Decomposition

| Component | Value (TWD) | USD Approx |
|---|---|---|
| Tangible book value | NT$5,371.3B | ~$169.4B |
| EPV (owner earnings / WACC) | NT$16,355B | ~$516B |
| Market cap | NT$49,387B | ~$1,558B |
| **Franchise value** | **NT$33,032B** | **~$1,042B** |
| Franchise % of market cap | 66.9% | — |

[Inference: all computed from balance.json, income.json, cashflow.json, enterprise_value.json]

---

## Analyst Estimates

| Year | Revenue Avg (TWD) | EPS Avg (TWD) | Net Income Avg (TWD) |
|---|---|---|---|
| FY2026E | NT$5,258.8B | 500.99 | NT$2,598.4B |
| FY2027E | NT$6,689.2B | 637.12 | NT$3,304.9B |
| FY2028E | NT$8,235.2B | 800.74 | NT$4,154.5B |

[ratings.json: estimates]

Price target consensus: $427.50 (median $450, range $330–$480). [ratings.json: price_target_consensus]

# Appendix F: Risk Factors — TSMC (TSM)

## 1. Customer Concentration

| Customer | FY2025 % Revenue | Est. Revenue | FY2024 % | Source |
|---|---|---|---|---|
| Nvidia | ~19% | ~$23.4B | ~12% | [claim_verification.json: C014 — Corroborated] |
| Apple | ~17% | ~$20.9B | ~22% | [claim_verification.json: C014 — Corroborated; 17% vs 18% discrepancy] |
| Top 2 combined | ~36% | ~$44.3B | ~34% | [Inference: sum] [Sources: claim_verification.json: C014] |

**Revenue impact if Nvidia reduces spend 50%:** −$11.7B (9.5% of FY2025 total revenue). [Inference: 19% × $123.1B ÷ 2] [Sources: earnings.json, claim_verification.json: C014]

**End-market concentration:** HPC platform = 61% of Q1 2026 revenue. AI accelerators = "high-teens" % of FY2025. [transcript_segments.json; claim_verification.json: C015]

**Geographic concentration:** North America = 75% of FY2025 net revenue. [claim_verification.json: C023]

## 2. Cyclicality

TSMC experienced one revenue decline in 10 years (FY2023: −4.5% TWD). [income.json]

Current AI-driven growth cycle: two consecutive years of 33%+ revenue growth (FY2024–2025). Management guiding FY2026 "above 30%." [transcript.json]

Beta: 1.264. 52-week range: $190.56–$421.97 (121% spread). [info.json; quote.json]

**Macro sensitivities cited by management:** Rising component prices in consumer/price-sensitive segments; Middle East situation bringing macro uncertainties; "a little bit softer market" in PC and smartphone due to memory price hikes. [transcript.json: C.C. Wei]

## 3. Technology/Disruption Risk

**Node transitions:**
- N2: ramping, 2–3% GM dilution in FY2026. [transcript.json: Jen-Chau Huang]
- A14: 10–15% speed or 25–30% power improvement vs N2; 2028 volume production. [transcript.json: C.C. Wei]

**Samsung 2nm threat:** Yields ~55% vs TSMC ~60–70%. Top-tier clients (Apple, Nvidia, AMD) not committed to Samsung foundry. Samsung improved from ~20% to ~55% yields in <1 year. [claim_verification.json: C018, C020]

**Intel IFS:** "Formidable competitor" per C.C. Wei, but "limited 2026 shipments" per ASML. [transcript.json; ecosystem_signals.md]

**Tesla Terafab:** Signed Samsung deal, remains TSMC customer. [transcript.json: C.C. Wei]

**Huawei chipmaking breakthrough claim:** Bloomberg (May 26, 2026) reported Huawei claims a new pathway to shorten gap with TSMC. [news.json — Tier 5, unverified]. SMIC currently operates at 7nm; gap to TSMC's 2nm/3nm is substantial.

**Advanced packaging competition:** Intel eMIP vs. TSMC CoWoS. TSMC developing CoPoS and System on Wafer. [transcript.json]

## 4. Geopolitical/Regulatory Risk (Foreign-Listed Trait)

### 4a. Listing Structure

- **Not subject to HFCAA delisting risk.** Audited by Deloitte & Touche (Taiwan). [claim_verification.json: C080 — Corroborated]
- **No VIE structure.** Direct ADR backed by common shares. [claim_verification.json: C081 — Corroborated]

### 4b. Taiwan Strait Geopolitical Risk

Manufacturing concentrated in Taiwan (Hsinchu, Tainan/Kaohsiung). Geographic diversification is multi-year: Arizona Fab 2 production H2 2027, Japan Fab 2 2028. Leading-edge capacity will remain predominantly in Taiwan through at least 2028. [transcript.json: C.C. Wei]

### 4c. U.S. CHIPS Act and Export Controls

TSMC benefits from CHIPS Act subsidies for Arizona fabs (amount not quantified in data). Export controls restrict advanced chip sales to certain Chinese entities. Revenue impact not separately disclosed. [transcript.json; claim_verification.json: C055 — Single-Source]

### 4d. Middle East Energy Supply Risk

- Material supply: multi-source, safety stock maintained. "We do not expect any near-term impact." [transcript.json: Jen-Chau Huang]
- Energy: Taiwan government secured LNG through at least May 2026. [transcript.json]
- Cost: Chemical/gas prices likely to increase; profitability impact "too early to quantify." [transcript.json]

## 5. Execution Risk

**Global fab expansion:** Simultaneously building/ramping fabs in Arizona (2), Japan (2), Germany (1), and Taiwan (multiple). Unprecedented geographic expansion. [transcript.json]

**Capex execution:** FY2026 guided ~$52–56B (38% increase from FY2025). Equipment supply tightness (EUV) is a constraint. [transcript.json; cashflow.json]

**Overseas fab cost:** 2–3% gross margin dilution initially, widening to 3–4% later. [transcript.json: Jen-Chau Huang]

**Key person:** CEO C.C. Wei. No succession plan disclosed. [info.json; Data gap] CEO purchased 160 shares May 8, 2026. [insider.json]

## 6. Financial Risk

**Balance sheet strength:**
- Net cash: NT$2,063.7B ($65.1B). [balance.json]
- Debt/equity: 0.199 (declining). [ratios.json]
- Current ratio: 2.51. [metrics.json]
- Altman Z-Score: 17.0. Piotroski: 9/9. [scores.json]

**Currency exposure:** Costs primarily TWD, revenue largely USD. 30bps gross margin impact per 1% FX change. [claim_verification.json: C050 — Verified]

**Tax rate:** FY2025 ETR 16.0%; FY2026 guided 17–18%. If normalized to 21%, NI would decline ~6.1%. [Inference: (0.21−0.16) × EBT NT$2,062.8B] [Sources: income.json]

**Earnings quality signals:**
- AR grew 4.2% vs revenue +33.0% in FY2025 (favorable). [balance.json; income.json]
- Income quality (OCF/NI): 1.37x (consistently >1.3x). [metrics.json]
- SBC immaterial (NT$0 FY2025). [cashflow.json]

**Insider activity (May 2026):** 12 officers purchased shares. One VP (Chuang Tzu-Sou) sold 200,000 shares (~$14M). [insider.json; news.json]

## 7. Earnings Consistency

EPS beat in 8/9 quarters; revenue beat in 9/9 quarters. Beat magnitudes widening over time. One EPS miss (Q4 2024: −$0.01, negligible). [earnings.json]

## 8. Base Rate Calibration

- **Revenue growth persistence:** Two consecutive years of 33%+. Third year at >30% would have few historical precedents at $100B+ revenue scale. [income.json; ratings.json]
- **Cyclicality:** One revenue decline in 10 years. AI capex cycle ~3 years old, approaching historical average length (3–5 years). Management and ASML indicate constraints persist through ≥2027. [transcript.json; ecosystem_signals.md]
- **Margin reversion:** FY2025 gross margin (59.9%) at high end of 10-year range (46.0%–59.9%). Q1 2026 (66.2%) exceeds prior peak. Management raised long-term guidance to "56% and higher through the cycle." [transcript.json; income.json]

## 9. Notable Non-Disclosures

- Wafer ASPs, unit volumes, fab utilization rates: not disclosed. Peers in semiconductor industry (e.g., memory companies) disclose utilization; TSMC does not.
- Customer names in earnings calls: anonymized. Peers Samsung and Intel discuss customer wins more openly.
- Foundry vs. packaging vs. other services revenue: single-segment reporting only.
- Backlog/order book: no dollar amount disclosed. Only qualitative characterization provided.
- CHIPS Act subsidy amounts: not quantified.
- China revenue breakdown: not disclosed beyond "North America 75%."

## 10. Deflected Analyst Questions

- **Nvidia LPU at Samsung:** C.C. Wei stated "Jeff already gave me enough warning, very specific" and confirmed work on next-gen but did not directly address the competitive loss. [transcript.json]
- **FY2026 growth potential >30%:** C.C. Wei: "we will share with you in July." [transcript.json]
- **Capex breakdown details:** CFO: "we don't have a number to share with you." [transcript.json]
- **Specific capacity numbers:** Management declined to provide precise CoWoS or node-level capacity figures.

---

## Data Gaps

1. 20-F full text (risk factors, debt maturities, contract terms not directly readable)
2. China revenue percentage (beyond "North America 75%")
3. Capacity utilization rate (referenced but not disclosed as %)
4. Customer contractual terms (minimum commitments, take-or-pay)
5. Insurance/catastrophe coverage for Taiwan fabs
6. Water supply risk (historically an issue; no current data)
7. Succession plan for CEO C.C. Wei
8. Samsung foundry profitability (not separately reported)
9. Congressional trading data (FMP returned 404)
10. Advanced packaging geographic split (Taiwan vs. overseas)

# Appendix G: Transcript Highlights — TSMC (TSM)

**Source:** Q1 2026 Earnings Call (reported April 15, 2026). [transcript.json; transcript_segments.json; transcript_competitors.json]

---

## Revenue and Guidance

**CFO Jen-Chau Huang (prepared remarks):**
- "First quarter revenue was approximately US$35.98 billion, an increase of 6.4% QoQ and 40.6% YoY in U.S. dollar terms, while in NT dollar terms, first quarter revenue increased 8.4% QoQ and 44.5% YoY." [transcript_segments.json]
- Q2 2026 guidance: "Revenue between US$39.0 billion and US$40.2 billion. Based on the exchange rate assumption of USD 1 equal to TWD 31.7. Gross margin between 65.5% and 67.5%. Operating margin between 56.5% and 58.5%." [transcript_segments.json]
- "For the full year, we now expect revenue in 2026 to grow close to 30% in US dollar terms." [transcript_segments.json]

## Platform Revenue Mix

**CFO Jen-Chau Huang (prepared remarks):**
- "HPC accounted for 61% of our first quarter revenue, smartphone 26%, IoT 6%, automotive 4%, and DCE 1%." [transcript_segments.json]
- "In terms of technology, 3-nanometer process technology contributed 25% of wafer revenue, 5-nanometer accounted for 36%, and 7-nanometer accounted for 13%. Advanced technologies, defined as 7-nanometer and below, accounted for 74% of wafer revenue." [transcript_segments.json]

## AI Demand

**CEO C.C. Wei (Q&A):**
- On AI accelerator CAGR: "it is toward higher 50s of CAGR that we observe." [transcript_competitors.json: response to Bruce Lu]
- "Demand continues to be extremely robust and the number continues to be increased, and we double check with our customers, customers' customers, or those CSPs. They gave us a very positive outlook." [transcript_competitors.json: response to Gokul Hariharan]
- On supply tightness extending to 2027: Analyst Gokul Hariharan: "That's very clear. So '27 is also very tight." C.C. Wei confirmed. [transcript_competitors.json]

## Capacity and CapEx

**CEO C.C. Wei:**
- "It takes 2 to 3 years to build a new fab, no shortcuts. And it takes another 1 to 2 years to ramp it up." [transcript_competitors.json: response to Gokul Hariharan]
- On Arizona fabs: "We acquired the second land because we need it. We want to build more fabs in Arizona." [transcript_competitors.json]
- On N3 expansion: "We now announce three of them. The first one is in Taiwan Tainan, which is a greenfield. And the second one is the second fab in Arizona. And the third one is also in Japan." [transcript_competitors.json]

**CFO Jen-Chau Huang:**
- FY2026 capex: "towards the high end of our range of between USD 52 billion and USD 56 billion." [transcript_segments.json]
- "The past 3 years, the total number is about $101 billion. And then the next 3 years, the total number, of course, is going to be significantly higher." [transcript_competitors.json]

## Margins

**CFO Jen-Chau Huang:**
- Q1 2026 margins: "First quarter gross margin was 66.2%, which exceeded the high end of our guidance by 120 basis points. Operating margin was 58.1%." [transcript_segments.json]
- N2 dilution: "N2 technology ramp-up to be dilutive to our gross margin by 2% to 3% for the full year of 2026." [transcript_segments.json]
- Overseas fabs: "overseas fab ramp-up will dilute our gross margin by 2% to 3% in the early stages and widen to 3% to 4% in the latter stages." [transcript_segments.json]
- N3 crossover: "N3 is crossing the corporate average gross margin in the second half." [transcript_competitors.json: response to Haas Liu]
- FX sensitivity: "every percent change in the exchange rate" affects margins by 30 basis points. [claim_verification.json: C050 — Verified]

## Competition

**CEO C.C. Wei:**
- On Intel and Tesla: "both Intel and Tesla, they are TSMC's customers. But again, they are our competitors, and we view Intel as our formidable competitor and do not underestimate them." [transcript_competitors.json]
- On Tesla specifically: "they are still our customer. And we are very confident in our technology position, and we work hard to capture every piece of business possible." [transcript_competitors.json]
- On foundry fundamentals: "There are no shortcuts. The fundamental rules of the foundry game never change. They need the technology leadership, manufacturing excellence and customer trust, and most of all, the service." [transcript_competitors.json]
- On Nvidia LPU at Samsung: "we are working with our customer for their next-generation LPU anyway. And we are very confident in our technology position." [transcript_competitors.json]
- On packaging competition (eMIP): "today, TSMC is supplying the largest reticle size packaging... we don't leave any business on the table." [transcript_competitors.json]

## Pricing Philosophy

**CEO C.C. Wei:**
- "We always view our customers as our partners... we don't change our pricing dramatically... we just try to make sure that our customers can be successful in their market. And at the same time, we grow together, and we also earn our value." [transcript_competitors.json: response to Bruce Lu]
- "Of course, we know our value; of course, we know our position." [transcript_segments.json]

## Supply Chain

**CFO Jen-Chau Huang:**
- On materials: "For specialty chemicals and gases, including helium and hydrogen, we source from multiple suppliers in different regions, and we have prepared safety stock inventory on hand." [transcript_segments.json]
- On Middle East: "Prices for certain chemicals and gases are likely to increase. Based on our current assessment, there may be impact to our profitability, but it is too early to quantify." [transcript_segments.json]
- On Taiwan energy: "The Taiwan government has announced it has secured sufficient LNG supply through at least May." [transcript_segments.json]

## Supplier Relationships

**CEO C.C. Wei:**
- "In TSMC's culture, we're always working with our suppliers, because we view them as our partners." [transcript_competitors.json: response to Charlie Chan]
- On OSAT collaboration: "we have to work with our OSAT partners. We hope that we can increase the capacity to support our customers." [transcript_competitors.json: response to Laura Chen]

## Tax Guidance

**CFO Jen-Chau Huang:**
- "For the full year 2026 tax rate, we expect to be between 17% and 18%. For second quarter, the tax rate is about 20% because of the accrual of the 5% tax on undistributed retained earnings." [transcript_segments.json]

## Dividend Policy

**CFO Jen-Chau Huang:**
- "We are committed to sustainable and steadily increasing cash dividend per share on both annual and quarterly basis." [transcript.json]

## Deflected Questions

- **FY2026 growth >30%:** C.C. Wei to Sunny Lin: "we will share with you in July, how about that." [transcript_competitors.json]
- **Capex breakdown:** CFO to analysts: "we don't have a number to share with you." [transcript_competitors.json]
- **Specific customer details:** C.C. Wei: "Jeff already gave me enough warning, very specific and very specific customer, very specific area." [transcript_competitors.json: re: Nvidia LPU question]

---

**Speaker Attribution Note:** All quotes above are attributed to the specific speaker. Analyst questions and assertions are distinguished from management responses. Analyst Haas Liu described 3nm as in "severe undersupply" — this was his characterization, not management's words, though management did not dispute it. [transcript_competitors.json]

# Appendix H: Source Index — TSMC (TSM)

## Source Classification

| Tier | Category | Description |
|---|---|---|
| Tier 1 | SEC filings / company announcements | 20-F, 6-K, XBRL facts, EDGAR filings |
| Tier 2 | Financial data API | FMP-derived statements, metrics, quotes |
| Tier 3 | Earnings transcript | Management statements and analyst Q&A |
| Tier 4 | Third-party research | Web research, industry analysis, expert reports |
| Tier 5 | News/blogs/commentary | Context and timing only |

---

## Raw Data Files Used

### Tier 1: SEC Filings / Company Disclosures

| File | Provider | Data Date | Content |
|---|---|---|---|
| facts.json | EDGAR XBRL | Multi-year | XBRL concept data, financial metrics from SEC filings |
| filing_events.json | EDGAR | — | 8-K events (returned 0; TSMC files 6-K as FPI) |
| filings.json | EDGAR | Multi-year | SEC filing list |
| filing_search.json | EDGAR | — | Full-text search of EDGAR filings |
| convertible_search.json | EDGAR | — | Convertible note search (no TSMC results) |
| edgar_search_risks.json | EDGAR | — | Risk factor search (returned wrong entity: Triple-S Management) |
| trait_filing_search_*.json | EDGAR | — | Filing searches for specific traits |
| insider_detail.json | EDGAR | — | Form 4 insider transactions |
| holders_detail.json | EDGAR | — | 13F institutional holdings |
| presentations.json | Company IR | 2026 | Investor presentation links from TSMC IR page |
| company_site_ir.json | Company IR | 2026 | IR page content from taiwansemi.com |

### Tier 2: Financial Data API (FMP)

| File | Provider | Period End | Content |
|---|---|---|---|
| info.json | FMP | Current | Company profile, price, market cap, CEO, employees |
| quote.json | FMP | 2026-05-26 | Real-time quote, 52-week range |
| income.json | FMP | FY2025 (12 years) | Income statements (TWD) |
| balance.json | FMP | FY2025 (12 years) | Balance sheets (TWD) |
| cashflow.json | FMP | FY2025 (12 years) | Cash flow statements (TWD) |
| metrics.json | FMP | FY2025 (5 years) | Key metrics: ROIC, ROE, EV/EBITDA, working capital |
| ratios.json | FMP | FY2025 (5 years) | Financial ratios: margins, leverage, dividends |
| earnings.json | FMP | Q1 2024–Q2 2026E | EPS and revenue actuals vs. estimates |
| enterprise_value.json | FMP | FY2025 (5 years) | Enterprise value components (TWD) |
| technicals.json | FMP | 2026-05-26 | RSI, SMA, EMA, ADV |
| scores.json | FMP | Current | Altman Z-Score, Piotroski F-Score |
| dcf.json | FMP | 2026-05-26 | DCF model output |
| ratings.json | FMP | Current | Analyst estimates, price targets, grades |
| insider.json | FMP | 2026 | Insider trading activity (20 transactions) |
| holders.json | FMP | Current | Institutional holders |
| holders_analytics.json | FMP | Current | Holder analytics |
| peers.json | FMP | Current | Peer company list |
| peer_compare.json | FMP | Current | Peer comparison profiles |
| shares_float.json | FMP | 2026-05-26 | Float shares, outstanding shares |
| short_interest.json | FMP | — | Short interest (404 error — unavailable) |
| segments.json | FMP | — | Segment data (404 error — single segment) |
| price_history.json | FMP | 1 year | 251 daily price records |
| dividends.json | FMP | — | Dividend history (404 error) |
| options.json | FMP | — | Options data (unavailable) |
| government.json | FMP | — | Congressional trading (404 — empty) |
| sector_perf.json | FMP | Current | Sector performance |
| computed_metrics.json | Derived | 2026-05-27 | Deterministic calculations from raw files |

### Tier 3: Earnings Transcript

| File | Provider | Period | Content |
|---|---|---|---|
| transcript.json | FMP | Q1 2026 | Full earnings call transcript |
| transcript_segments.json | FMP | Q1 2026 | Segment/platform mentions extracted |
| transcript_competitors.json | FMP | Q1 2026 | Competitor/customer mentions extracted |

### Tier 4: Web Research

| File | Provider | Pulled | Content |
|---|---|---|---|
| business_overview.md | Serper | 2026-05-27 | Company overview web search |
| segment_financials.md | Serper | 2026-05-27 | Segment financial data web search |
| competitive_by_product.md | Serper | 2026-05-27 | Product-level competitive landscape |
| competitive_history.md | Serper | 2026-05-27 | Market share history |
| competitor_data.md | Serper | 2026-05-27 | Competitor financial comparison |
| customer_alternatives.md | Serper | 2026-05-27 | Switching cost analysis |
| customer_capex.md | Serper | 2026-05-27 | Customer spending guidance |
| supply_demand.md | Serper | 2026-05-27 | Supply/demand dynamics |
| supplier_capacity.md | Serper | 2026-05-27 | Equipment/capacity constraints |
| supply_indicators.md | Serper | 2026-05-27 | Capacity utilization indicators |
| backlog_breakdown.md | Serper | 2026-05-27 | Order pipeline analysis |
| revenue_mix.md | Serper | 2026-05-27 | Revenue breakdown analysis |
| company_ir.md | Serper | 2026-05-27 | IR page content |
| convertible_detail.md | Serper | 2026-05-27 | Convertible debt search |
| short_interest.md | Serper | 2026-05-27 | Short interest data (MarketBeat) |
| press_releases.md | Serper | 2026-05-27 | Recent press releases |
| ecosystem_signals.md | Hermes | 2026-05-27 | ASML, Apple, Samsung ecosystem signals |
| trait_search_0.md – trait_search_4.md | Serper | 2026-05-27 | Trait-specific searches (HFCAA, VIE, FX, etc.) |
| industry.json | Serper | 2026-05-27 | Industry research |
| news.json | Serper | 2026-05-27 | 20 recent news articles |

### Derived / Navigation

| File | Category | Content |
|---|---|---|
| claim_verification.json | Derived | Confidence tags for web-sourced claims (C001–C104) |
| gather_status.json | Derived | Data gathering task status and timing |

---

## Confidence Tag Summary

From claim_verification.json, web-sourced claims carry these tags:

| Tag | Count | Treatment |
|---|---|---|
| Verified | Multiple (C001, C002, C003, C008, C036, C043, C050, C052, C057, C063, C064, C071, C099) | Cited normally |
| Corroborated | Multiple (C004, C006, C012, C013, C014, C015, C038, C045, C053, C066, C067, C075, C077, C086, C095, C096, C097, C101, C103, C104) | Cited with corroboration note |
| Single-Source | Multiple (C020, C028, C051, C055, C078, C079, C085) | Cited with caveat |
| Contradicted | Multiple (C018, C019, C023, C025, C065, C070, C080, C081, C102) | All versions presented |
| Unverifiable | C025 (CSIMarket methodology) | Omitted or flagged |

---

## Key Data Gaps in Source Coverage

1. **No 20-F full text** — latest_10k.json does not exist. All 20-F data via secondary reporting.
2. **FMP short interest 404** — short interest from Tier 5 web source only.
3. **FMP segments 404** — single-segment company; platform breakdowns from transcript.
4. **FMP dividends 404** — dividend data from cashflow.json and ratios.json only.
5. **FMP options unavailable** — no options chain data.
6. **FMP government trading 404** — Congressional trading data not available.
7. **EDGAR risk search wrong entity** — returned Triple-S Management Corp, not TSMC.
8. **Filing events empty** — TSMC files 6-K (not 8-K) as foreign private issuer.
