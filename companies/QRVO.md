---
type: company
ticker: QRVO
name: Qorvo, Inc.
sector: Technology
industry: Semiconductors
country: US
updated: "2026-05-27"
sources:
  - info.json
  - value_chain.md
  - segments.json
  - insider.json
  - holders.json
  - transcript_competitors.json
---

# Qorvo, Inc. (QRVO)

## Overview

- **Sector:** Technology
- **Industry:** Semiconductors
- **Country:** US
- **Website:** https://www.qorvo.com

## Competitors

- [Skyworks Solutions](SWKS.md) (SWKS)
- [Broadcom](AVGO.md) (AVGO)
- [Qualcomm](QCOM.md) (QCOM)
- Murata Manufacturing
- [Analog Devices](ADI.md) (ADI)
- [NXP Semiconductors](NXPI.md) (NXPI)
- [MACOM Technology Solutions](MTSI.md) (MTSI)

## Key Insiders

- Brown Grant (officer: SVP & Chief Financial Officer)
- BRUGGEWORTH ROBERT A (director, officer: President and CEO)
- Chesley Philip (officer: SVP, High Performance Analog)
- CREVISTON STEVEN E (officer: SVP, Connectivity & Sensors)
- FEGO PAUL J (officer: SVP, Global Operations)
- Harrison Gina (officer: VP and Corporate Controller)
- Stewart Frank P. (officer: SVP, Advanced Cellular)

---

> **⚠️ DRAFT — this report did not pass the citation audit.** Some claims may lack source verification. Treat as preliminary research.

# Qorvo, Inc. (QRVO) — Research Report

**Report Date:** 2026-05-27
**Data As Of:** 2026-05-26 (price), FY2026 (ended March 28, 2026) for annual financials, Q4 FY2026 for most recent quarter
**Ticker:** QRVO | NASDAQ Global Select | Technology | Semiconductors
**Price:** $108.23 [info.json: price]
**ADV:** $130.5MM [info.json: averageVolume (1,206,149) × price ($108.23)]
**Market Cap:** $9.53B [info.json: marketCap]
**Net Debt:** $330.1M (3.5% of mkt cap) [balance.json: totalDebt ($1,549,154,000) − cashAndShortTermInvestments ($1,219,015,000)]
**Net Cash:** -$330.1M (-3.5% of mkt cap) [balance.json: cashAndShortTermInvestments − totalDebt]
**Enterprise Value:** $9.86B [Computed: $9.53B mkt cap + $1,549M debt − $1,219M cash]
**Short Interest:** N/A [Data gap — FMP returned 404 for short_interest.json; float shares: 79,546,758 (90.4% free float) per shares_float.json]

---

## Section 1: Business Overview

<!-- IC Question: What does this company do, how is it organized, and how large is each piece? What would change the answer: major divestiture, acquisition, segment reclassification, revenue mix shift. The pending Skyworks merger is the primary change catalyst. -->

### Company Identity

Qorvo, Inc. is a semiconductor company headquartered at 7628 Thorndike Road, Greensboro, NC 27409. The company designs, manufactures, and sells radio frequency (RF) solutions for wireless, wired, and power markets. Qorvo operates as an integrated device manufacturer (IDM) with proprietary compound semiconductor fabs (GaAs, GaN-on-SiC, BAW, SAW, SOI). The company has 6,200 full-time employees and trades on the NASDAQ Global Select exchange. CEO is Robert A. Bruggeworth. [info.json: all fields]

**Pending merger:** On October 27, 2025, Skyworks Solutions (SWKS) announced a definitive merger agreement to acquire Qorvo for $32.50 cash + 0.960 SWKS shares per QRVO share, implying a combined enterprise value of ~$22B. Shareholders of both companies approved the deal on February 11, 2026. The FTC issued a Second Request on February 6, 2026, and China's SAMR is conducting a Phase 2 review. Expected close is late 2026 or early 2027. [ecosystem_signals.md: Skyworks IR merger announcement; news.json: GlobeNewsWire]

### Reportable Segments

Qorvo reorganized from two segments (Mobile Products; Infrastructure and Defense Products) into three reportable operating segments in Q2 FY2023: **Advanced Cellular Group (ACG)**, **High Performance Analog (HPA)**, and **Connectivity & Sensors Group (CSG)**. [claim_verification.json: C095, Verified]

**Note:** info.json (FMP) still lists the outdated two-segment structure. FMP segments.json returned 404. The three-segment structure is confirmed by the FY2023 10-K and Q4 FY2026 press release. [claim_verification.json: C004, Contradicted; segments.json: API error 404]

| Segment | Q4 FY2026 Revenue | Q4 FY2026 % of Total | Q4 FY2026 YoY | FY2026 Annual Revenue | FY2026 % of Total |
|---------|------------------|---------------------|---------------|----------------------|-------------------|
| Advanced Cellular Group (ACG) | $512.3M | 63.4% | -11.7% | ~$2.55B | ~69.3% |
| High Performance Analog (HPA) | $202.7M | 25.1% | +7.9% | Not individually disclosed | — |
| Connectivity & Sensors Group (CSG) | $93.3M | 11.5% | -7.9% | Not individually disclosed | — |
| **Total** | **$808.3M** | **100.0%** | **-7.0%** | **$3,678.5M** | **100%** |

*Q4 FY2026 segment data: [claim_verification.json: C098, Verified — sum of segments matches $808.3M total]. FY2026 total: [income.json: revenue $3,678,517,000]. ACG FY2026 ~$2.55B: [claim_verification.json: C048, Corroborated — TradingView data cross-checked with Q3 and Q4 press releases]. Full-year HPA and CSG individual revenue: [Data gap — not separately disclosed in available data].*

**Segment sum check (Q4 FY2026):** $512.3M + $202.7M + $93.3M = $808.3M. Matches reported Q4 total of $808.3M. Percentages: ACG 63.4% + HPA 25.1% + CSG 11.5% = 100.0%. ✓

### Key Products by Segment

**ACG (63.4% of Q4 revenue):** Antenna tuners, BAW/SAW filters, integrated RF front-end modules, envelope tracking PMICs (custom-developed to pair with largest customer's internal baseband). ACG serves smartphone OEMs, primarily Apple and Samsung. [transcript_segments.json: CEO Bruggeworth Q1 FY26]

**HPA (25.1% of Q4 revenue):** GaN high-power amplifiers for defense radar (AESA), electronic warfare, and SATCOM; programmable PMICs and motor controls for consumer, defense, industrial, and enterprise; compound semiconductor foundry services. Defense & aerospace is HPA's largest market by revenue. [transcript_segments.json: CEO Bruggeworth Q1 FY26]

**CSG (11.5% of Q4 revenue):** Wi-Fi 7/8 front-end modules; ultra-wideband (UWB) SoC/SiP solutions for automotive and IoT; Matter/smart home SoCs; MEMS sensors. UWB SoC generates ~$60M annual revenue with ~$100M in operating expenses. [transcript_segments.json: CFO Brown Q1 FY26]

**Q4 FY2026 segment operating margins (non-GAAP):** HPA 34.7%, ACG 25.5%, CSG -7.4% (operating loss). [claim_verification.json: C098, Verified]

### Narrative vs. Reality

Qorvo does **not** separately disclose AI-specific revenue. CEO Bruggeworth listed "enterprise and AI data centers" among HPA growth applications, but no dollar figures or growth rates were provided. [transcript_segments.json: CEO Bruggeworth Q1 FY26]

**What drives the P&L:** ACG (smartphone RF) represented ~69% of FY2026 revenue (~$2.55B of $3.68B). Apple alone represented 47% of FY2025 annual revenue (~$1.75B) and ~41% of Q1 FY2026 quarterly revenue (~$336M). [income.json; claim_verification.json: C005, Corroborated; transcript_segments.json: CFO Brown Q1 FY26 — Single-Source for the 41% quarterly figure per C008]

AI data center power management remains a small and undisclosed portion of HPA's $202.7M quarterly revenue (Q4 FY2026), with defense & aerospace as HPA's stated primary market. [Inference: AI revenue is not material to current financials based on absence of disclosure and HPA's D&A focus] [Sources: transcript_segments.json, claim_verification.json: C098]

### Major Customers

| Customer | FY2025 % of Revenue | FY2024 % of Revenue | Source |
|----------|-------------------|-------------------|--------|
| Apple | 47% (~$1.75B) | 46% (~$1.73B) | [claim_verification.json: C005, Corroborated — 10-K] |
| Samsung | 10% (~$372M) | 12% (~$452M) | [claim_verification.json: C005, Corroborated — 10-K] |
| Top 2 combined | ~57% | ~58% | [Computed from above] |

### Brief History

Qorvo was formed January 1, 2015, through the merger of RF Micro Devices (RFMD) and TriQuint Semiconductor. In Q2 FY2023, Qorvo reorganized into three segments (ACG, HPA, CSG). In FY2025–FY2026, the company executed restructuring: divesting its SiC business ($30M FY2025 revenue), closing Costa Rica and North Carolina manufacturing sites, and strategically exiting $150M–$200M of low-margin Android 5G business. On October 27, 2025, Skyworks Solutions announced a definitive merger agreement; shareholders approved on February 11, 2026. [info.json: ipoDate; claim_verification.json: C095, Verified; transcript_segments.json: CFO Brown Q1 FY26; ecosystem_signals.md]

---

## Section 2: Competitive Position

<!-- IC Question: For each product, who competes with this company and what are their relative strengths? What would change the answer: loss of a top customer, entry of a well-capitalized competitor, customer building in-house alternative (Apple modem is the key risk), technology disruption. Base rate: the pending SWKS-QRVO merger would fundamentally alter the competitive landscape if completed. -->

### ACG (Cellular RF) Competitive Landscape

Named competitors from Qorvo's 10-K: Analog Devices (ADI), Broadcom (AVGO), M/A-COM Technology Solutions (MTSI), Murata Manufacturing, NXP Semiconductors (NXPI), Qualcomm (QCOM), and Skyworks Solutions (SWKS). [claim_verification.json: C073, Verified — direct 10-K quote]

Four to five companies compete directly in mobile RF front-end: Qorvo, Skyworks, Broadcom (FBAR filters), Qualcomm (integrated modem+RF), and Murata (filters/modules). [competitive_position.md]

**Qorvo vs. Skyworks (pending merger partner):**

| Metric | QRVO (FY2026 / Q4 FY2026) | SWKS (FY2025 / Q2 FY2026) | Source |
|--------|--------------------------|--------------------------|--------|
| Revenue | $3.679B (FY2026) | ~$4.09B (FY2025) | [income.json; ecosystem_signals.md] |
| Non-GAAP Gross Margin | 52.6% (Q4 FY2026) | 45.0% (Q2 FY2026) | [claim_verification.json: C098; ecosystem_signals.md] |
| Apple concentration | ~47% (FY2025) | ~60% | [claim_verification.json: C005; ecosystem_signals.md — Single-Source per C027] |
| Inventory | $554M | $886M (+17% QoQ) | [balance.json; ecosystem_signals.md] |

QRVO's non-GAAP gross margin of 52.6% exceeds SWKS's 45.0% by 760 basis points. SWKS reported negative quarterly free cash flow of -$32.0M in Q2 FY2026. [ecosystem_signals.md: SWKS Q2 FY26 press release]

**Market share:** Qorvo is estimated at 15–18% share of the global mobile RF market, ranking behind Broadcom and Qualcomm. [competitive_history.md — Single-Source per claim_verification.json: C077, no methodology disclosed]. If the SWKS-QRVO merger closes, the combined entity is estimated at "over 34% of the RF market." [competitive_history.md — Single-Source per C103, no base market definition cited]

**Customer-level competitive overlap at Apple:** Apple multi-sources RF components from Qorvo (4 product categories: antenna tuners, filters/switches, integrated modules, envelope tracking PMICs), Skyworks (~60% of SWKS revenue from Apple), Broadcom (FBAR filters), and Qualcomm (modem + RF modules). [transcript_segments.json: CEO Bruggeworth Q1 FY26; ecosystem_signals.md]

### In-House Disruption Threat: Apple Modem

Apple is progressively developing an in-house cellular modem. CEO Bruggeworth stated: "It is our expectations over time that they will use more of their internal modem and the percentage will only grow." Analyst Christopher Rolland (Susquehanna) cited Qualcomm's expectation of 30% internal modem at Apple; Bruggeworth declined to confirm the percentage. [transcript_segments.json: CEO Bruggeworth Q1 FY26, Q&A]

Offsetting factor: Qorvo's envelope tracking PMIC is "custom developed to pair with our internal baseband," creating content growth on Apple's own modem platforms. Management guided >10% content gains on the fall 2025 platform. [transcript_segments.json: CEO Bruggeworth and CFO Brown Q1 FY26]

### HPA (Defense) Competitive Landscape

HPA competes with Analog Devices, M/A-COM (MTSI), and to a lesser extent NXP in GaN defense components. Qorvo differentiates through onshore U.S. manufacturing (Hillsboro OR, Richardson TX) of GaAs, GaN, BAW, and SAW — all ITAR-compliant. [transcript_segments.json: CEO Bruggeworth Q1 FY26]

### CSG (Connectivity) Competitive Landscape

CSG competes with Broadcom (Wi-Fi), NXP (UWB), and Murata in Wi-Fi front-end modules. SWKS secured a "multi-generational Android OEM design win expected to generate $1B+ cumulative revenue through 2030." [ecosystem_signals.md: SWKS Q2 FY26 press release; claim_verification.json: C029]

### Revenue Decline Trajectory

Revenue peaked at $4.646B in FY2022 and has declined 20.8% over 4 fiscal years to $3.679B in FY2026. [income.json: revenue FY2022–FY2026]

| FY | Revenue | YoY Change | GAAP Gross Margin | GAAP Op Margin |
|----|---------|------------|-------------------|----------------|
| FY2022 | $4.646B | +15.7% | 49.2% | 26.4% |
| FY2023 | $3.569B | -23.2% | 36.3% | 5.1% |
| FY2024 | $3.770B | +5.6% | 39.5% | 2.4% |
| FY2025 | $3.719B | -1.3% | 41.3% | 2.6% |
| FY2026 | $3.679B | -1.1% | 45.9% | 11.2% |

[income.json: revenue, grossProfit, operatingIncome]

The decline reflects (a) post-COVID smartphone demand normalization, (b) FY2023 customer inventory correction, and (c) deliberate strategic exit of low-margin Android 5G business. The exit was initially guided at $150M–$200M annually but has been revised. [Inference: initial guidance came from transcript Q1 FY26, revision flagged as Contradicted] [Sources: transcript_segments.json, claim_verification.json: C056 — Contradicted: initial $150M–$200M vs. revised $300M for FY2027 per Yahoo Finance/Investing.com analyst sources]

---

## Section 3: Supply/Demand Balance

<!-- IC Question: Is industry supply sufficient to meet demand at current prices, and when does that change? What would change the answer: Apple modem transition pace, new defense program awards, tariff policy changes, UWB automotive ramp timing. Typical smartphone RF supply/demand imbalances last 2–3 years based on the FY2022–FY2025 cycle. -->

### Demand Decomposition

**Backlog and pipeline:** Qorvo does not disclose order backlog or book-to-bill ratios. Available demand indicators:

| Indicator | Value | Source |
|-----------|-------|--------|
| D&A sales funnel | >$7B (increased ~$2B sequentially in Q1 FY26) | [transcript_segments.json: CEO Bruggeworth Q1 FY26] |
| UWB sales funnel | >$2B qualified opportunities | [transcript_segments.json: CEO Bruggeworth Q1 FY26] |
| Q1 FY27 revenue estimate (consensus) | $743M | [earnings.json: revenueEstimated] |
| FY2027 revenue estimate (consensus) | $3.46B | [ratings.json: FY2027 revenueAvg] |

**Customer demand signals:**
- **Apple (~47% of revenue):** iPhone 17 cycle generated record March quarter revenue of $56.99B (+22% YoY). June quarter guidance of 14–17% YoY growth exceeded analyst expectations of ~9.5%. [ecosystem_signals.md: CNBC AAPL Q2 FY2026 report, Apr 30, 2026]
- **Samsung (~10% of revenue):** QRVO reported share gains in premium-tier Android at Samsung for H2 FY2026. [transcript_segments.json: SVP Fullwood Q1 FY26]
- **Defense primes (within HPA):** U.S. defense spending increasing; $150B in additional funding via recent budget reconciliation. [transcript_segments.json: CEO Bruggeworth Q1 FY26]

### Demand Durability

Positive drivers: Apple iPhone 17 cycle with >10% content gains from envelope tracking PMIC; 5G Advanced specifications (Power Class 2) driving more RF content per phone; U.S./allied defense spending tailwind; DOCSIS 4.0 broadband upgrade cycle. [transcript_segments.json: CEO Bruggeworth, CFO Brown, SVP Stewart Q1 FY26]

Negative drivers: Apple internal modem adoption will grow over time; strategic exit of $150M–$200M (potentially revised to $300M for FY2027 per C056 Contradicted) of low-margin Android business; tariff uncertainty causing demand pushout in motor controls/power tools; automotive UWB program delay to FY2027. [transcript_segments.json; claim_verification.json: C056]

### Supply Position

QRVO operates with **overcapacity** in its current manufacturing footprint. The FY2025 10-K states "prior investments in premium filter capacity exceeding near-term demand, leading to underutilization of manufacturing facilities." [claim_verification.json: C099, Verified — SEC filing rfmd-20250329.htm]

Factory rationalization underway: closing Costa Rica and Greensboro NC sites; consolidating to Hillsboro OR and Richardson TX. Capex of $129M (FY2026) is 50% of D&A ($259M), indicating investment below replacement levels. [cashflow.json: capitalExpenditure, depreciationAndAmortization]

Inventory declined from $797M (FY2023) to $554M (FY2026), a 30.5% reduction, confirming destocking. [balance.json: inventory]

### Supply/Demand Synthesis

QRVO is in a state of supply surplus relative to current demand. Revenue at $3.679B is 20.8% below the FY2022 peak of $4.646B, but the manufacturing footprint has only partially been reduced. The company is rebalancing through: (a) demand-side portfolio restructuring (exiting low-margin Android, growing defense), (b) supply-side rationalization (closing fabs, improving utilization), and (c) content gains per device at Apple (>10% on fall 2025 platform). [Inference: supply is moving toward balance through simultaneous demand-mix improvement and capacity reduction] [Sources: income.json, transcript_segments.json, claim_verification.json: C099]

### Bargaining Power

**Demand-side:** Apple's dominance (47% of revenue) gives it pricing leverage, but RF content is <0.5% of iPhone BOM, making Apple price-insensitive on a per-component basis. The >10% content gain at Apple indicates willingness to pay for differentiated products (custom envelope tracking PMIC). [Inference: Apple exercises bargaining power through volume allocation and multi-sourcing rather than per-unit price pressure] [Sources: transcript_segments.json, claim_verification.json: C005]

**Supply-side:** Qorvo's vertical integration (proprietary compound semiconductor fabs) reduces supplier power for core processes. After divesting SiC, Qorvo depends on third-party SiC substrate suppliers (Wolfspeed, Coherent) for GaN-on-SiC defense products. [transcript_segments.json: CFO Brown Q1 FY26; value_chain.md]

---

## Section 4: Value Chain

<!-- IC Question: Where is value captured, and is it migrating toward or away from this company? What would change the answer: Apple vertical integration into RF, Qualcomm expanding bundled modem+RF, competitor M&A. In semiconductor value chains, value chain position shifts typically take 3–5 years to materialize due to design-in cycles. -->

### Value Chain Map

```
Raw Materials       → Wafer Fabrication     → Assembly/Test       → Module Integration → End-Product OEM
(GaAs, GaN, piezo,   (QRVO internal fabs:    (QRVO internal;       (QRVO integrates    (Apple, Samsung,
Si wafers)            Hillsboro OR,           Costa Rica closing)   filters + PAs)      defense primes)
                      Richardson TX,
                      Greensboro NC closing)
```

Qorvo is an IDM: it designs, fabricates, assembles, tests, and integrates RF semiconductors in-house. This contrasts with fabless competitors like Qualcomm. Qorvo's compound semiconductor processes (GaAs, GaN, BAW, SAW) are not available from standard foundries like TSMC. [info.json: description; transcript_segments.json: CEO Bruggeworth Q1 FY26 — "We offer gas, GaN, BAW, SAW and advanced multichip packaging, all manufactured onshore in the U.S."]

### Margin Capture by Chain Stage

| Value Chain Stage | Representative Company | Gross Margin | Source |
|-------------------|----------------------|-------------|--------|
| RF Component IDM | **QRVO** | 45.9% (GAAP FY2026) | [income.json] |
| RF Component IDM | SWKS | 41.2% (GAAP FY2025) | [ecosystem_signals.md] |
| RF Filters (scale) | AVGO (company-wide) | ~77% (non-GAAP) | [ecosystem_signals.md] |
| End-Product OEM | Apple | ~49.3% (Q2 FY2026) | [ecosystem_signals.md] |

Margins have migrated toward end-product OEMs (Apple expanded GM from ~43% to ~49% since FY2022) and away from mid-chain RF component makers (QRVO GM contracted from 49.2% to 45.9%, SWKS from 47.2% to 41.2% over the same period). [Inference: component suppliers bear more cyclical margin risk than OEMs in the smartphone value chain] [Sources: income.json, ecosystem_signals.md]

### Integration Direction

**Qorvo dis-integrating upstream:** Divested SiC business ($30M FY2025 revenue), increasing reliance on third-party SiC substrate suppliers. [transcript_segments.json: CFO Brown Q1 FY26]

**Qorvo integrating forward:** Expanding from discrete components to integrated front-end modules (FEMs); developing UWB SoC including firmware and application software for automotive/IoT — integration beyond hardware into software. [transcript_segments.json: CEO Bruggeworth Q1 FY26]

**Customers integrating toward Qorvo's position:** Apple is developing an in-house cellular modem (backward integration into baseband). Qualcomm has vertically integrated into RF front-end modules. Samsung periodically uses its own Exynos baseband. CEO Bruggeworth on Samsung's Exynos: "We would love for them to be successful with their internal baseband across business units" — because Samsung's internal chipsets still require Qorvo's RF front-end. [transcript_segments.json: CEO Bruggeworth Q1 FY26]

### Dependencies and Vulnerabilities

1. **Apple customer concentration (47% of FY2025 revenue):** A 10% reduction in Apple revenue would reduce total revenue by ~$175M (~4.7 ppt). Apple purchases across 4 ACG product categories and CSG products. [claim_verification.json: C005; transcript_segments.json: CEO Bruggeworth Q1 FY26]

2. **Manufacturing concentration:** After closures, active manufacturing concentrates at Hillsboro OR (GaAs/GaN, used by all 3 segments) and Richardson TX (BAW/SAW filters). A disruption at Hillsboro would affect all three segments simultaneously. [transcript_segments.json: CEO Bruggeworth Q1 FY26 — "They all use the same Oregon, Hillsboro fab"]

3. **TSMC is NOT a dependency:** Unlike fabless semiconductor companies, Qorvo does not rely on TSMC for core products. Compound semiconductor processes are fabricated in proprietary fabs. [Inference: IDM model confirmed by description and transcript] [Sources: info.json, transcript_segments.json]

---

## Section 5: Capital Structure

<!-- IC Question: How does the company raise money to spend on its business? What would change the answer: merger closing (Skyworks would assume/exchange QRVO debt), new debt issuance, credit rating change. -->

### Equity Composition

- **Share class:** Common stock, single class. No preferred stock. [balance.json: preferredStock $0]
- **Shares outstanding:** 88.0M [shares_float.json: outstandingShares]
- **Diluted shares (FY2026 avg):** 93.5M [income.json: weightedAverageShsOutDil]
- **Float:** 79.5M shares (90.4% free float) [shares_float.json]
- **Market cap:** $9.53B at $108.23/share [info.json: marketCap]

### Debt Composition

| Instrument | Principal | Rate | Maturity | Source |
|-----------|-----------|------|----------|--------|
| Senior Notes due 2029 | $850M | 4.375% | 2029 | [news.json: GlobeNewsWire May 20, 2026] |
| Senior Notes due 2031 | $700M | 3.375% | 2031 | [news.json: GlobeNewsWire May 20, 2026] |
| **Total long-term debt** | **$1,549M** | | | [balance.json: longTermDebt $1,549,154,000] |

- Short-term debt: $0 [balance.json: shortTermDebt]
- Capital lease obligations: $0 [balance.json: capitalLeaseObligations]
- Sum of identified tranches ($1,550M) vs. balance sheet ($1,549M): $1M difference is unamortized discount/issuance costs. [Inference: standard bond accounting] [Sources: news.json, balance.json]
- No near-term maturities. [transcript_segments.json: CFO Brown Q1 FY26 — "no near-term maturities"]
- **Pending merger impact:** Skyworks commenced exchange offers on May 20, 2026 to exchange QRVO's notes for new Skyworks-issued notes with identical terms. [news.json: GlobeNewsWire May 20, 2026]

### Convertible Securities

None outstanding. [convertible_search.json: 0 recent results]

### Cash and Equivalents

$1,219M [balance.json: cashAndCashEquivalents $1,219,015,000]

### Minority Interest

$0 [balance.json: minorityInterest $0]

### Enterprise Value

$9.86B [Computed: $9.53B mkt cap + $1,549M debt − $1,219M cash]

Note: enterprise_value.json reports $7.49B computed at the filing-date stock price of $77.35 (FY2026 period). The $9.86B figure uses the current price of $108.23.

### Net Debt / EBITDA

**Net Debt / Adj. EBITDA: 0.49x** [Computed: $330M net debt / $670M adj. EBITDA]

Adjusted EBITDA = Operating income ($411M) + D&A from cashflow ($259M) = $670M. Note: income.json reports D&A = $0 and EBITDA = $411M for FY2026, which is a FMP data standardization artifact. Cashflow.json correctly shows D&A of $258,648,000. [income.json: depreciationAndAmortization $0; cashflow.json: depreciationAndAmortization $258,648,000]

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

# Appendix A: Competitive Position — Qorvo (QRVO)

## Market Position

### RF Front-End Market Share Estimates

- Qorvo: estimated 15–18% of global mobile RF market [competitive_history.md — Single-Source per claim_verification.json: C077, no methodology disclosed]
- If SWKS-QRVO merger closes: combined "over 34% of the RF market" [competitive_history.md — Single-Source per C103, no base market definition cited]
- Yale SOM report cites market shares of 57.7%, 19.3%, 13.7%, 6.9% for 4 players in an undefined market/time period [competitive_by_product.md — Single-Source per C058]
- CSIMarket comparison includes all semiconductors (NVDA, AVGO, TXN), not RF-specific [competitive_history.md — Unverifiable per C081]

**Data gap:** No methodology-disclosed market share data for the RF front-end sub-market was found in available sources.

### Named Competitors (10-K Disclosure)
Analog Devices (ADI), Broadcom (AVGO), M/A-COM (MTSI), Murata Manufacturing, NXP Semiconductors (NXPI), Qualcomm (QCOM), Skyworks Solutions (SWKS). [claim_verification.json: C073, Verified — direct 10-K quote]

## Product-Level Competitive Analysis

### ACG Products vs. Competitors

**Envelope Tracking PMICs (Apple):**
- QRVO: Custom ET PMIC paired with Apple's internal baseband; "durable multiyear content opportunity" per CEO Bruggeworth [transcript_segments.json: Q1 FY26]
- SWKS: Also supplies Apple RF components (~60% of SWKS revenue from Apple); SWKS CEO Brace expects blended content position "roughly flat" next year [ecosystem_signals.md]
- Broadcom: Competes in FBAR filters for Apple; revenue not separately disclosed [ecosystem_signals.md — Data gap]
- Qualcomm: Provides modem + RF module bundles; Apple progressively replacing with internal modem

**BAW/SAW Filters:**
- QRVO: Both BAW and SAW filter capabilities; SAW production transferring from NC to TX [transcript_segments.json: CFO Brown Q1 FY26]
- Broadcom: FBAR technology (thin-film bulk acoustic resonator); leading position in Apple FBAR filters
- Murata: SAW/BAW filter capabilities; Japanese IDM [competitive_by_product.md]
- No direct revenue comparison available — neither Broadcom nor Murata disclose filter-specific revenue

**Android RF Modules:**
- QRVO: Strategically exiting $150M–$200M of low-margin mass-tier Android 5G; retaining premium tier [transcript_segments.json: CEO Bruggeworth Q1 FY26]
- Qualcomm: Vertically integrated modem + RF modules for Android (Snapdragon platform); dominant in Android through bundling strategy
- SWKS: Secured "multi-generational Android OEM design win expected to generate $1B+ cumulative revenue through 2030" [ecosystem_signals.md: SWKS Q2 FY26]

### HPA Products vs. Competitors

**GaN Defense Amplifiers:**
- QRVO: GaN-on-SiC amplifiers for radar, EW, SATCOM; all manufactured onshore U.S.; $7B+ D&A sales funnel [transcript_segments.json: CEO Bruggeworth, SVP Chesley Q1 FY26]
- Analog Devices (ADI): Competes in defense RF; $12.5B LTM revenue across all segments
- M/A-COM (MTSI): Competes in GaN defense; focused on defense/industrial markets
- QRVO differentiator: Only IDM with onshore U.S. compound semiconductor manufacturing across GaAs, GaN, BAW, SAW

### CSG Products vs. Competitors

**UWB SoC/SiP:**
- QRVO: >$2B qualified sales funnel; ~$60M annual revenue, ~$100M OpEx [transcript_segments.json: CFO Brown Q1 FY26]
- NXP (NXPI): Major UWB competitor; Apple uses NXP UWB for AirTag and device-finding features
- One automotive UWB program delayed to FY2027 [transcript_segments.json: CFO Brown Q1 FY26]

**Wi-Fi 7/8 FEMs:**
- QRVO: Aligned with "market-leading chipset providers to develop next-generation solutions for Wi-Fi 8" [transcript_segments.json: CEO Bruggeworth Q1 FY26]
- Broadcom, Qualcomm, MediaTek: Compete at the Wi-Fi chipset level; QRVO provides complementary front-end modules
- CSG Wi-Fi growth revised down from 10–12% guidance to "low single digits" [transcript_segments.json: CFO Brown Q1 FY26]

## Switching Cost Evidence

- **Apple ET PMIC:** Custom-designed to pair with Apple's internal baseband; switching requires 12–18 months of design and validation [transcript_segments.json: CEO Bruggeworth Q1 FY26]
- **4 product categories at Apple:** Antenna tuners, filters/switches, integrated modules, ET PMICs — breadth creates integration complexity for substitution [transcript_segments.json: CEO Bruggeworth Q1 FY26]
- **Defense GaN:** ITAR-compliant U.S. manufacturing with security clearances; 2–4 year qualification timelines [Inference: standard defense qualification cycle] [Sources: transcript_segments.json, info.json]
- **Long-term supply agreement expiration:** CEO Bruggeworth referenced "the expiration of a certain long-term supply agreement" as "helping us" commercially, implying prior contractual constraints have lifted [transcript_segments.json: CEO Bruggeworth Q1 FY26]

## Competition Evolution (3–5 Year Timeline)

1. **2015:** Qorvo formed (RFMD + TriQuint merger)
2. **2016–2022:** 4-player oligopoly (Qorvo, Skyworks, Broadcom, Qualcomm) plus Murata; growth from 4G→5G transition
3. **2022–2025:** Post-COVID demand normalization; Qualcomm increased vertical integration (modem + RF)
4. **Oct 2025:** Skyworks announced merger agreement with Qorvo (~$22B combined EV)
5. **Feb 2026:** FTC Second Request; China SAMR Phase 2; both shareholder groups approved
6. **May 2026:** Skyworks commenced exchange offers for QRVO senior notes ($850M 2029 + $700M 2031)
7. **Late 2026/Early 2027:** Expected merger close

## Design Win Tracking (Q1 FY2026)

| Design Win | Segment | Customer | Revenue Status |
|-----------|---------|----------|----------------|
| UWB for leading Japanese auto OEM | CSG | Unnamed | Not yet ramped |
| UWB for world's leading EV manufacturer | CSG | Unnamed | Not yet ramped |
| UWB asset tracking for South Korean auto OEM | CSG | Unnamed | Not yet ramped |
| Wi-Fi 7 in augmented reality glasses | CSG | Unnamed | Not yet ramped |
| Wi-Fi 6/7 FEMs for AR/VR | CSG | Unnamed | Not yet ramped |
| >10% content gain at largest customer | ACG | Apple (unnamed) | Ramping FY2026 H2 |
| Samsung premium-tier share gains | ACG | Samsung | Ramping FY2026 H2 |
| S-band switch filter modules for defense | HPA | U.S. defense primes | Active |
| GaN K-band PA for LEO SATCOM | HPA | Unnamed | Active |
| Enterprise UWB in access points | CSG | Unnamed Tier 1 OEM | Shipping |

[transcript_segments.json: CEO Bruggeworth Q1 FY26 prepared remarks]

## Notable Non-Disclosures

Compared to peers, Qorvo does not disclose:
- Geographic revenue breakdown (SWKS discloses China revenue: <$200M annually) [ecosystem_signals.md]
- Order backlog or book-to-bill ratios
- Unit shipment volumes or ASPs by product
- Fab utilization rates (FY2025 10-K confirms overcapacity but no utilization %)
- Product-level revenue within segments
- Full-year HPA and CSG individual revenue for FY2026

# Appendix B: Supply/Demand Balance — Qorvo (QRVO)

## Demand Analysis

### Backlog and Pipeline

Qorvo does not disclose order backlog or book-to-bill ratios. [Data gap]

Available pipeline data (from management commentary, not binding orders):
- **D&A sales funnel:** >$7B, increased ~$2B sequentially in Q1 FY2026. [transcript_segments.json: CEO Bruggeworth, SVP Chesley Q1 FY26]
- **UWB sales funnel:** >$2B qualified opportunities. [transcript_segments.json: CEO Bruggeworth Q1 FY26]
- **Win-to-revenue timeline:** UWB automotive design wins typically take 18–36 months to generate meaningful revenue. [transcript_segments.json: CFO Brown Q1 FY26]

### Quarterly Revenue Trajectory (FY2026)

| Quarter | Revenue | QoQ Change | Seasonal Context |
|---------|---------|------------|-----------------|
| Q1 FY2026 | $818.8M | — | Trough quarter (pre-Apple launch) |
| Q2 FY2026 | $1,058.5M | +29.3% | Apple fall iPhone launch ramp |
| Q3 FY2026 | $993.0M | -6.2% | Post-launch normalization |
| Q4 FY2026 | $808.3M | -18.6% | Seasonal trough |
| **FY2026 Total** | **$3,678.5M** | — | |

[earnings.json: revenueActual; income.json: revenue]

### Customer Demand Corroboration

**Apple (iPhone 17 cycle):**
- Apple Q2 FY2026 iPhone revenue: $56.99B (+22% YoY), record March quarter [ecosystem_signals.md: CNBC Apr 30, 2026]
- June quarter guidance: 14–17% YoY growth, vs analyst expectations of ~9.5% [ecosystem_signals.md]
- Greater China iPhone revenue: $20.5B (+28% YoY) [ecosystem_signals.md]
- QRVO content gains: >10% on fall 2025 platform from ET PMIC [transcript_segments.json: CFO Brown Q1 FY26]

**Defense (U.S. and allied spending):**
- $150B in additional U.S. defense funding via budget reconciliation [transcript_segments.json: CEO Bruggeworth Q1 FY26]
- D&A funnel grew ~$2B sequentially to >$7B [transcript_segments.json: CEO Bruggeworth Q1 FY26]
- Programs cited: radar, communications, SATCOM, missile defense ("Golden Dome") [transcript_segments.json: CEO Bruggeworth Q1 FY26]

**Automotive UWB:**
- One automotive OEM delayed a program ramp to FY2027, pushing CSG growth guidance from 10–12% to "low single digits" [transcript_segments.json: CFO Brown Q1 FY26]

### Consensus Estimates

| Period | Revenue Estimate | EPS Estimate | Analysts |
|--------|-----------------|-------------|----------|
| Q1 FY2027 | $743M | $1.07 | N/A |
| FY2027 | $3.46B (-5.9% YoY) | $6.89 | 13 (rev), 12 (EPS) |
| FY2028 | $3.64B (+5.2% YoY) | $7.73 | 10 (rev), 7 (EPS) |
| FY2029 | $3.91B (+7.4% YoY) | $8.82 | 5 (rev), 2 (EPS) |

[ratings.json: estimates; earnings.json: Q1 FY27 estimate]

**Note:** Consensus FY2027 estimate of $3.46B implies a -5.9% YoY decline from FY2026. This may reflect the accelerated Android exit ($300M revised impact per C056) and/or pre-merger assumptions. It is unclear whether consensus reflects standalone QRVO or merged entity expectations. [Data gap]

## Supply Analysis

### Manufacturing Footprint

| Facility | Location | Function | Status |
|----------|----------|----------|--------|
| Hillsboro fab | Oregon | GaAs, GaN wafer fab (all 3 segments) | Active — primary fab |
| Richardson fab | Texas | BAW/SAW filter fab; new SAW line under construction | Active — expanding |
| Greensboro fab | North Carolina | Wafer fab (SAW) | Closing — SAW transferring to TX |
| Costa Rica site | Costa Rica | Packaging, assembly, test | Closing — completion early CY2027 |

[transcript_segments.json: CEO Bruggeworth, CFO Brown Q1 FY26]

### Capacity Utilization

QRVO does not disclose utilization rates. The FY2025 10-K confirms overcapacity: "prior investments in premium filter capacity exceeding near-term demand, leading to underutilization of manufacturing facilities." [claim_verification.json: C099, Verified — SEC filing rfmd-20250329.htm]

### Capex vs. D&A (Supply Investment Indicator)

| FY | CapEx | D&A | CapEx/D&A | CapEx/Revenue |
|----|-------|-----|-----------|---------------|
| 2022 | $213M | $361M | 0.59x | 4.6% |
| 2023 | $159M | $324M | 0.49x | 4.5% |
| 2024 | $127M | $365M | 0.35x | 3.4% |
| 2025 | $138M | $297M | 0.46x | 3.7% |
| 2026 | $129M | $259M | 0.50x | 3.5% |

[cashflow.json: capitalExpenditure, depreciationAndAmortization; income.json: revenue]

CapEx consistently below D&A indicates the company is deliberately shrinking its capacity footprint. PP&E declined from $1,254M (FY2022) to $710M (FY2026), a 43% reduction. [balance.json: propertyPlantEquipmentNet]

### Inventory Trajectory

| FY | Inventory | DIO (days) | Inventory/Revenue |
|----|-----------|-----------|-------------------|
| 2022 | $756M | 117 days | 16.3% |
| 2023 | $797M | 128 days | 22.3% |
| 2024 | $711M | 114 days | 18.9% |
| 2025 | $641M | 107 days | 17.2% |
| 2026 | $554M | 102 days | 15.1% |

[balance.json: inventory; metrics.json: daysOfInventoryOutstanding]

## AI Value Chain Positioning

Qorvo does **not** have a material AI business. AI-related commentary is limited to "enterprise and AI data centers" listed among HPA power management growth applications. No AI-specific revenue, customer names, or growth rates are disclosed. [transcript_segments.json: CEO Bruggeworth Q1 FY26]

**Primary business:** Smartphone RF semiconductors (~69% of revenue via ACG).
**Primary growth driver:** Defense & aerospace (within HPA; $7B+ sales funnel).

## Depth-First Research Summary

### Questions Answered
- Customer demand drivers: Apple iPhone 17 cycle strong (+22% YoY); defense funnel growing ($7B+) [ecosystem_signals.md, transcript_segments.json]
- Supply rationalization progress: Costa Rica on track; NC SAW transfer underway; savings ≥$10M–$20M annually [transcript_segments.json]
- Inventory normalization: 30.5% reduction from FY2023 peak to FY2026 [balance.json]

### Questions Unanswerable
- Backlog or book-to-bill ratio: Not disclosed
- Fab utilization rates: Not disclosed
- Broadcom wireless/FBAR revenue: Not separately reported
- Net impact of Apple internal modem on QRVO content: Management says content gains offset but no independent verification available

# Appendix C: Value Chain — Qorvo (QRVO)

## Qorvo's IDM Model

Qorvo is an Integrated Device Manufacturer (IDM), meaning it designs, fabricates, assembles, tests, and integrates its own RF semiconductors. This is distinct from fabless models (e.g., Qualcomm for RF modems) and foundry models (e.g., TSMC). Qorvo's compound semiconductor processes — GaAs, GaN-on-SiC, BAW piezoelectric, SOI — are not available from standard CMOS foundries. [info.json: description; transcript_segments.json: CEO Bruggeworth Q1 FY26]

### Full Value Chain

```
Stage 1: Raw Materials     Stage 2: Wafer Fab       Stage 3: Assembly/Test    Stage 4: Module         Stage 5: OEM
(GaAs, GaN substrates,    (QRVO: Hillsboro OR,    (QRVO: formerly          Integration             (Apple, Samsung,
SiC substrates, Si SOI,   Richardson TX;           Costa Rica; moving       (QRVO: integrates       defense primes,
piezo materials,           Greensboro NC closing)   all U.S.)               filters + PAs + SW      enterprise OEMs)
packaging substrates)                                                       into modules/SoCs)
```

**Stages QRVO owns:** IC design, wafer fabrication (GaAs, GaN, BAW, SAW, SOI), die assembly, packaging, testing, module integration, and (for UWB SoC) firmware/software development. [transcript_segments.json: CEO Bruggeworth Q1 FY26]

**Stages QRVO outsources:** Raw substrate procurement (GaAs ingots, SiC substrates from third parties post-divestiture, Si wafers, piezo materials); some CMOS companion die to standard foundries. [value_chain.md; transcript_segments.json: CFO Brown Q1 FY26]

## Upstream: Suppliers

### Key Supplier Categories

| Category | Likely Suppliers | Switching Cost | Source |
|----------|-----------------|---------------|--------|
| GaAs wafers | Sumitomo Electric, Freiberger (inferred) | High (6–12 months qualification) | [Inference: standard industry practice] [Sources: info.json, industry.json] |
| GaN-on-SiC substrates | Wolfspeed, Coherent (post-SiC divestiture) | High | [value_chain.md; transcript_segments.json] |
| Si wafers (SOI) | Multiple standard suppliers | Low (commodity) | [Inference: SOI widely available] [Sources: info.json] |
| Piezoelectric materials | Specialty suppliers | High (process-integrated) | [Inference: BAW thin films likely deposited in-house] |
| Packaging substrates | Asian laminate suppliers | Moderate (3–6 months) | [Inference: industry standard] |
| Capital equipment | AMAT, LRCX, KLA, ASML | Low (standard equipment) | [Inference: industry standard] |

**Data gap:** Qorvo does not disclose specific supplier names in available data. The FY2026 10-K full text (accession 0001628280-26-032873) is not in raw files. Supplier concentration cannot be quantified. [value_chain.md]

### SiC Supply Chain Change

Qorvo divested its SiC business in FY2025 ($30M revenue), eliminating captive SiC substrate production. GaN-on-SiC products for defense now rely entirely on third-party SiC substrates. The SiC substrate market is concentrated among Wolfspeed, Coherent, and a few others. [Inference: SiC supply was partially captive; now fully third-party] [Sources: transcript_segments.json: CFO Brown Q1 FY26]

## Downstream: Customers

### Customer Concentration Detail

| Customer | FY2025 Revenue | % of Total | FY2024 Revenue | % of Total | Source |
|----------|---------------|------------|---------------|------------|--------|
| Apple | ~$1,748M | 47% | ~$1,734M | 46% | [claim_verification.json: C005, Corroborated] |
| Samsung | ~$372M | 10% | ~$452M | 12% | [claim_verification.json: C005, Corroborated] |
| All others | ~$1,599M | 43% | ~$1,583M | 42% | [Computed] |

### Cross-Segment Customer Exposure

Apple purchases across at least 2 of 3 segments:
- **ACG:** Antenna tuners, filters/switches, integrated modules, envelope tracking PMICs (4 product categories) [transcript_segments.json: CEO Bruggeworth Q1 FY26]
- **CSG:** Wi-Fi FEMs, potentially UWB [transcript_segments.json: CEO Bruggeworth Q1 FY26]

Samsung purchases ACG products (premium-tier Android RF). [transcript_segments.json: SVP Fullwood Q1 FY26]

Defense primes (unnamed) purchase HPA GaN amplifiers and foundry services. [info.json: description]

### Customer Switching Costs

- **Apple (ACG):** Moderate to high. Custom ET PMIC paired with Apple's internal baseband creates design-in lock-in. Switching requires 12–18 months. However, "the expiration of a certain long-term supply agreement" suggests prior contractual constraints have lifted. [transcript_segments.json: CEO Bruggeworth Q1 FY26]
- **Android OEMs (ACG):** Low to moderate. Qorvo is voluntarily exiting low-margin mass-tier Android, indicating alternatives exist. [transcript_segments.json: CFO Brown Q1 FY26]
- **Defense (HPA):** High. ITAR-compliant onshore U.S. manufacturing with security clearances creates substantial barriers. [transcript_segments.json: CEO Bruggeworth Q1 FY26]
- **Automotive UWB (CSG):** Moderate. 3–5 year design cycles; once designed in, switching costs are high until next vehicle platform refresh. [transcript_segments.json: CFO Brown Q1 FY26]

## Margin Migration (5-Year Trend)

| Year | QRVO Gross Margin | SWKS Gross Margin | Apple Gross Margin | Source |
|------|-------------------|-------------------|-------------------|--------|
| FY2022 | 49.2% | 47.2% | ~43–44% | [income.json; ecosystem_signals.md] |
| FY2026 | 45.9% | 41.2% (FY2025) | ~49.3% (Q2 FY2026) | [income.json; ecosystem_signals.md] |
| **Change** | **-3.3 ppt** | **-6.0 ppt** | **+5–6 ppt** | |

Margins have migrated toward Apple and away from mid-chain RF component makers. QRVO's margin recovery from the 36.3% FY2023 trough to 45.9% is driven by restructuring (Android exit, site closures, SiC divestiture) rather than improved pricing power. [Inference: restructuring-driven recovery rather than structural pricing improvement] [Sources: income.json, transcript_segments.json]

## Vertical Integration Assessment

| Value Chain Stage | Integration Level | Change Over 3 Years |
|-------------------|------------------|---------------------|
| IC Design | In-house | Stable |
| Wafer Fabrication | In-house (compound semi) | Consolidating (fewer fabs) |
| SiC Substrates | Outsourced (post-divestiture) | Dis-integrating |
| Die Assembly/Packaging | In-house (moving all U.S.) | Consolidating |
| Module Integration | In-house | Stable |
| Firmware/Software | Partial (CSG only: UWB, Matter) | Expanding |
| Foundry Services | In-house (for defense third parties) | Stable |

[transcript_segments.json; info.json; income.json: R&D $726M, 19.7% of revenue FY2026]

## Restructuring vs. Retained

### Parts Being Exited

| Action | Revenue Impact | Margin Impact | Status |
|--------|---------------|---------------|--------|
| Mass-tier Android 5G exit | -$150M to -$200M annually | Margin accretive | ~2/3 of decline in H2 FY2026 |
| SiC business divestiture | -$30M (FY2025) | Margin accretive | Complete |
| Greensboro NC fab closure | No direct revenue loss | +$10M–$20M annual COGS savings | SAW transferring to TX |
| Costa Rica site closure | No direct revenue loss | COGS savings (unquantified) | Completion early CY2027 |
| MEMS force sensing business | ~$20M annual OpEx drag | Currently a drag | Sale process underway |
| Base station PAMs | Exited | Margin accretive | Complete |

[transcript_segments.json: CEO Bruggeworth, CFO Brown Q1 FY26]

### Parts Being Invested

| Business | Investment Direction | Revenue Trajectory |
|----------|---------------------|--------------------|
| ACG (Apple content) | ET PMIC, 10%+ content growth | Stable/growing at Apple |
| HPA Defense & Aerospace | GaN amplifiers, SATCOM, radar; $7B+ funnel | Growth expected |
| HPA Power Management | PMICs for enterprise, AI data centers, drones | Growth applications |
| CSG UWB | SoC/SiP for automotive, enterprise; $2B+ funnel | ~$60M annual revenue; delayed ramp |
| CSG Wi-Fi 7/8 | FEMs for access points and smartphones | Low single-digit growth |

[transcript_segments.json: CEO Bruggeworth, CFO Brown Q1 FY26]

# Appendix D: Capital Structure — Qorvo (QRVO)

## Equity Composition

| Component | Value | Source |
|-----------|-------|--------|
| Share class | Common stock, single class | [info.json: description] |
| Preferred equity | $0 (none outstanding) | [balance.json: preferredStock FY2026] |
| Shares outstanding | 88,013,700 | [shares_float.json: outstandingShares] |
| Diluted shares (FY2026 avg) | 93,547,000 | [income.json: weightedAverageShsOutDil FY2026] |
| Free float | 79,546,758 shares (90.4%) | [shares_float.json: floatShares, freeFloat] |
| Market cap (at $108.23) | $9,525,722,751 | [info.json: marketCap] |

### Diluted Share Count Trajectory

| FY | Diluted Shares (M) | YoY Change |
|----|-------------------|-----------:|
| 2022 | 111.5 | — |
| 2023 | 103.0 | -7.6% |
| 2024 | 97.6 | -5.2% |
| 2025 | 95.5 | -2.2% |
| 2026 | 93.5 | -2.1% |

4-year CAGR: -4.3%. Reduction driven by buybacks: $3.30B gross ($3.12B net) repurchased over FY2022–FY2026. [income.json: weightedAverageShsOutDil; cashflow.json: commonStockRepurchased]

## Debt Composition

### Outstanding Debt Tranches

| Instrument | Principal | Rate | Maturity | Source |
|-----------|-----------|------|----------|--------|
| 4.375% Senior Notes | $850,000,000 | 4.375% | 2029 | [news.json: GlobeNewsWire May 20, 2026 — Exchange Offers and Consent Solicitations] |
| 3.375% Senior Notes | $700,000,000 | 3.375% | 2031 | [news.json: GlobeNewsWire May 20, 2026 — Exchange Offers and Consent Solicitations] |
| **Total identified** | **$1,550,000,000** | | | |
| **Total per balance sheet** | **$1,549,154,000** | | | [balance.json: totalDebt FY2026] |
| **Difference** | **$846,000** | | | [Inference: unamortized discount/issuance costs] [Sources: news.json, balance.json] |

### Debt Classification

| Category | Amount | Source |
|----------|--------|--------|
| Short-term debt | $0 | [balance.json: shortTermDebt FY2026] |
| Long-term debt | $1,549,154,000 | [balance.json: longTermDebt FY2026] |
| Capital lease obligations | $0 | [balance.json: capitalLeaseObligations FY2026] |
| **Total debt** | **$1,549,154,000** | [balance.json: totalDebt FY2026] |

### Debt Maturity Profile

| Year | Amount Due | Instrument |
|------|-----------|-----------|
| 2026–2028 | $0 | No near-term maturities |
| 2029 | $850M | 4.375% Senior Notes |
| 2031 | $700M | 3.375% Senior Notes |

CFO Brown confirmed in Q1 FY2026: "approximately $1.5 billion of long-term debt outstanding and no near-term maturities." [transcript_segments.json: CFO Brown Q1 FY26]

### Debt Trajectory (5 Years)

| FY | Total Debt | Short-term | Long-term | Net Debt |
|----|-----------|-----------|----------|---------|
| 2022 | $2,047M | $0 | $2,047M | $1,075M |
| 2023 | $2,048M | $0 | $2,048M | $1,240M |
| 2024 | $1,988M | $439M | $1,549M | $959M |
| 2025 | $1,549M | $0 | $1,549M | $528M |
| 2026 | $1,549M | $0 | $1,549M | $330M |

[balance.json: totalDebt, shortTermDebt, longTermDebt, netDebt FY2022–FY2026]

The $439M reduction between FY2024 and FY2025 reflects repayment of short-term borrowings ($438.7M classified as short-term in FY2024). [Inference: short-term debt retired, long-term unchanged] [Sources: balance.json FY2024, FY2025]

### Pending Merger Impact on Debt

Skyworks commenced exchange offers on May 20, 2026 to exchange Qorvo's 4.375% Senior Notes due 2029 ($850M) and 3.375% Senior Notes due 2031 ($700M) for new Skyworks-issued notes with identical terms. This is contingent on merger close. [news.json: GlobeNewsWire May 20, 2026]

If the merger fails, Qorvo retains its existing notes with 2029 and 2031 maturities — no refinancing risk.

## Convertible Securities

None outstanding. EDGAR search returned only historical 10-K references from FY2016–2017. [convertible_search.json: 0 recent results]

## Cash and Equivalents

| Component | Amount | Source |
|-----------|--------|--------|
| Cash and cash equivalents | $1,219,015,000 | [balance.json: cashAndCashEquivalents FY2026] |
| Short-term investments | $0 | [balance.json: shortTermInvestments FY2026] |
| **Total cash & short-term investments** | **$1,219,015,000** | [balance.json: cashAndShortTermInvestments FY2026] |

### Cash Trajectory

| FY | Cash & Equivalents |
|----|--------------------|
| 2022 | $973M |
| 2023 | $809M |
| 2024 | $1,029M |
| 2025 | $1,021M |
| 2026 | $1,219M |

[balance.json: cashAndCashEquivalents FY2022–FY2026]

## Minority Interest

$0 in all periods. [balance.json: minorityInterest FY2026]

## Enterprise Value

| Component | Value | Source |
|-----------|-------|--------|
| Market cap | $9,525,722,751 | [info.json: marketCap] |
| + Total debt | $1,549,154,000 | [balance.json: totalDebt FY2026] |
| − Cash & ST investments | $1,219,015,000 | [balance.json: cashAndShortTermInvestments FY2026] |
| **Enterprise Value** | **$9,855,861,751** | [Computed] |

enterprise_value.json reports $7,492,130,199 computed at the filing-date stock price of $77.35 (March 28, 2026). The $9.86B figure above uses the current market price of $108.23.

## Net Debt / EBITDA

| Component | Value | Source |
|-----------|-------|--------|
| Net debt | $330,139,000 | [balance.json: netDebt FY2026] |
| Operating income | $411,424,000 | [income.json: operatingIncome FY2026] |
| D&A (from cash flow) | $258,648,000 | [cashflow.json: depreciationAndAmortization FY2026] |
| **Adjusted EBITDA** | **$670,072,000** | [Computed: OpInc + D&A] |
| **Net Debt / Adj. EBITDA** | **0.49x** | [Computed] |

**Data quality note:** income.json reports FY2026 D&A = $0 and EBITDA = EBIT = $411M. This is a FMP standardization artifact for FY2026 specifically (FY2025 income.json correctly shows D&A of $297M). The cash flow statement ($259M D&A) is the authoritative source. [income.json: depreciationAndAmortization $0; cashflow.json: depreciationAndAmortization $258,648,000]

**Interest coverage:** Operating income ($411M) / interest expense ($73M) = 5.6x. [income.json: operatingIncome, interestExpense FY2026; ratios.json: interestCoverageRatio 5.63]

# Appendix E: Key Stats — Qorvo (QRVO)

## Valuation Metrics

| Metric | Value | Computation | Source |
|--------|-------|-------------|--------|
| Price | $108.23 | Market close May 26, 2026 | [quote.json: price] |
| 52-week range | $74.03 – $108.94 | | [quote.json: yearLow, yearHigh] |
| Market cap | $9.53B | 88.0M shares × $108.23 | [info.json: marketCap] |
| Enterprise value | $9.86B | $9.53B mktcap + $1,549M debt − $1,219M cash | [Computed from balance.json, info.json] |
| ADV (30d, $ notional) | $130.5M | info.json avgVolume (1,206,149) × $108.23 | [info.json: averageVolume] |
| ADV (30d, shares) | 1,217,523 | | [technicals.json: avg_volume_30d] |

**Note on ADV discrepancy:** technicals.json reports adv_30d of $114.4M, computed at a lower average price (~$94 over the 30-day lookback). The $130.5M figure uses info.json averageVolume × current price per report header methodology.

## Earnings Multiples

| Metric | Value | Computation | Source |
|--------|-------|-------------|--------|
| Trailing P/E | 29.9x | $108.23 / $3.62 diluted EPS FY2026 | [quote.json: price; income.json: epsDiluted FY2026] |
| Forward P/E (FY2027E) | 15.7x | $108.23 / $6.887 consensus EPS | [quote.json; ratings.json: epsAvg FY2027] |
| EV/Adj. EBITDA | 14.7x | $9.86B / $670M adj. EBITDA | [Computed; see Appendix D for EBITDA detail] |
| P/FCF | 14.0x | $9.53B / $680M FCF FY2026 | [info.json: marketCap; cashflow.json: freeCashFlow] |
| P/FCF ex-SBC | 17.5x | $9.53B / ($680M − $136M SBC) = $9.53B / $544M | [cashflow.json: freeCashFlow, stockBasedCompensation] |
| EV/Revenue | 2.68x | $9.86B / $3.679B | [Computed] |

## Cash Flow Metrics

| FY | OCF | CapEx | FCF | FCF Margin | SBC | FCF ex-SBC |
|----|-----|-------|-----|------------|-----|------------|
| 2026 | $809M | $129M | $680M | 18.5% | $136M | $543M |
| 2025 | $622M | $138M | $485M | 13.0% | $136M | $348M |
| 2024 | $833M | $127M | $706M | 18.7% | $121M | $585M |
| 2023 | $843M | $159M | $684M | 19.2% | $106M | $579M |
| 2022 | $1,049M | $213M | $836M | 18.0% | $84M | $752M |

[cashflow.json: operatingCashFlow, capitalExpenditure, freeCashFlow, stockBasedCompensation; income.json: revenue for margin]

## Returns on Capital

| FY | ROIC | ROE | ROA | Invested Capital |
|----|------|-----|-----|-----------------|
| 2026 | 6.8% | 10.1% | 5.8% | $4,779M |
| 2025 | 1.6% | 1.6% | 0.9% | $4,849M |
| 2024 | -1.5% | -2.0% | -1.1% | $5,131M |
| 2023 | 2.5% | 2.6% | 1.5% | $5,922M |
| 2022 | 15.7% | 22.7% | 13.8% | $6,479M |

[metrics.json: returnOnInvestedCapital, investedCapital, returnOnEquity, returnOnAssets]

## ROIC vs. WACC

| Component | Value | Computation | Source |
|-----------|-------|-------------|--------|
| Risk-free rate | 4.3% | Approximate 10-year Treasury | [Assumption] |
| Beta | 1.42 | | [info.json: beta] |
| Equity risk premium | 5.5% | Standard assumption | [Assumption] |
| Cost of equity (CAPM) | 12.1% | 4.3% + 1.42 × 5.5% | [Computed] |
| Pre-tax cost of debt | 4.7% | $73M interest / $1,549M debt | [income.json: interestExpense; balance.json: totalDebt] |
| After-tax cost of debt | 4.0% | 4.7% × (1 − 14.9%) | [income.json: effective tax rate FY2026] |
| Equity weight | 86.0% | $9.53B / ($9.53B + $1.55B) | [Computed: market cap basis] |
| Debt weight | 14.0% | $1.55B / ($9.53B + $1.55B) | [Computed] |
| **Estimated WACC** | **11.0%** | 86% × 12.1% + 14% × 4.0% | [Computed] |
| **FY2026 ROIC** | **6.8%** | | [metrics.json] |
| **ROIC – WACC spread** | **-4.1 ppt** | | [Computed] |

**Note:** risk_factors.md uses EV-basis weights (79.3%/20.7%), producing WACC of 10.4% and spread of -3.6 ppt. The difference is methodological (market cap basis vs. EV basis for weights). Both indicate FY2026 ROIC is below estimated WACC.

## DuPont Decomposition (FY2026)

| Component | FY2026 | FY2022 (peak) | Source |
|-----------|--------|---------------|--------|
| Net margin | 9.2% | 22.2% | [income.json: netIncome / revenue] |
| Asset turnover | 0.631x | 0.619x | [income.json: revenue / balance.json: totalAssets] |
| Financial leverage | 1.74x | 1.65x | [balance.json: totalAssets / totalStockholdersEquity] |
| **ROE** | **10.1%** | **22.7%** | [Computed; metrics.json confirms] |

## Greenwald Value Decomposition

### Asset Reproduction Value

| Component | FY2026 | Source |
|-----------|--------|--------|
| Total assets | $5,826M | [balance.json: totalAssets $5,825,590,000] |
| Less: Goodwill | ($2,353M) | [balance.json: goodwill $2,353,226,000] |
| Less: Intangibles | ($122M) | [balance.json: intangibleAssets $121,506,000] |
| Tangible assets | $3,351M | [Computed] |
| Less: Total liabilities | ($2,481M) | [balance.json: totalLiabilities $2,481,291,000] |
| **Tangible book value** | **$870M** | [Computed; metrics.json tangibleAssetValue confirms $870M] |
| **TBV per share** | **$9.88** | [Computed: $870M / 88.0M shares] |

Goodwill of $2,353M represents 40.4% of total assets. Primarily from 2015 RFMD/TriQuint merger with incremental additions from bolt-on acquisitions. Goodwill declined from $2,776M (FY2022) to $2,353M (FY2026) through impairment charges. [balance.json: goodwill FY2022–FY2026; cashflow.json: acquisitionsNet]

### Earnings Power Value

| Component | Value | Source |
|-----------|-------|--------|
| Normalized NI (FY2026) | $339M | [income.json: netIncome $338,989,000] |
| D&A (maintenance capex proxy) | $259M | [cashflow.json: depreciationAndAmortization] |
| Actual capex | $129M | [cashflow.json: capitalExpenditure] |
| Owner earnings (NI + D&A − CapEx) | $469M | [Computed] |
| Estimated WACC | 11.0% | [See WACC computation above] |
| **EPV** | **$4.3B** | [Inference: $469M / 0.110] [Sources: income.json, cashflow.json, info.json] |
| **EPV per share** | **$48** | [Computed: $4.3B / 88.0M shares] |

### Franchise Value

| Component | Value |
|-----------|-------|
| Market cap | $9.53B |
| EPV | $4.3B |
| **Franchise value** | **$5.3B** |

[Computed from quote.json and EPV]

## Technical Indicators (as of May 26, 2026)

| Indicator | Value | Source |
|-----------|-------|--------|
| RSI (14) | 75.6 (above 70 threshold) | [technicals.json: rsi_14] |
| 21d EMA | $94.03 | [technicals.json: ema_21d] |
| 50d SMA | $85.60 | [technicals.json: sma_50d] |
| 200d SMA | $86.38 | [technicals.json: sma_200d] |
| Price vs. 200d SMA | +25.3% | [Computed: ($108.23 − $86.38) / $86.38] |
| Price vs. 50d SMA | +26.6% | [Computed: ($108.23 − $85.60) / $85.60] |
| MACD | N/A | [technicals.json: macd null] |

## Financial Health Scores

| Score | Value | Interpretation | Source |
|-------|-------|---------------|--------|
| Altman Z-Score | 3.53 | Above 2.99 "safe zone" threshold | [scores.json: altmanZScore] |
| Piotroski Score | 9 / 9 | Maximum score | [scores.json: piotroskiScore] |

## Dividend and Capital Return

- **Dividend yield:** 0% (no dividends paid) [info.json: lastDividend $0; dividends.json: no history]
- **Cumulative 5-year gross buybacks (FY2022–FY2026):** $3.30B [cashflow.json: commonStockRepurchased]
- **Cumulative 5-year net buybacks:** $3.12B [cashflow.json: commonStockRepurchased + commonStockIssuance]
- **FY2026 buybacks:** $533M gross ($497M net) — includes $400M supported by Skyworks under merger agreement covenants [cashflow.json; claim_verification.json: C022, Verified]

## Merger Consideration Reference

Deal terms: $32.50 cash + 0.960 SWKS shares per QRVO share. At QRVO $108.23 and SWKS $83.42, the implied deal value is $32.50 + (0.960 × $83.42) = $112.58/share. QRVO trades at a 3.9% discount to deal value. [Inference: ($108.23 − $32.50) / 0.960 = $78.89 implied SWKS breakeven] [Sources: ecosystem_signals.md, quote.json]

## Analyst Consensus

| Metric | Value | Source |
|--------|-------|--------|
| Consensus price target | $88.86 | [ratings.json: targetConsensus] |
| Median price target | $87.00 | [ratings.json: targetMedian] |
| Price target range | $66 – $120 | [ratings.json: targetLow, targetHigh] |
| Current price vs. consensus | +21.8% above | [Computed: $108.23 vs $88.86] |

Recent analyst grades: Citigroup Neutral (May 7), JP Morgan Neutral (May 6), UBS Neutral (May 6), Barclays Overweight (Apr 22), Mizuho Underperform (Apr 20). [ratings.json: grades]

## FMP DCF Fair Value

$52.29 per share [dcf.json: dcf]. This is a FMP-computed mechanical DCF, not independently validated. The $52.29 value at $108.23 market price implies the stock trades at 2.07× FMP's DCF estimate.

# Appendix F: Risk Factors — Qorvo (QRVO)

## 1. Customer Concentration

**Apple:** 47% of FY2025 revenue (~$1.75B), up from 37% in FY2023. Apple purchases across 4 ACG product categories and CSG products. A 10% reduction in Apple revenue = ~$175M (~4.7 ppt) impact on total revenue. A 50% reduction = ~$874M (23.8%). [claim_verification.json: C005, Corroborated — 10-K data; income.json: revenue]

**Samsung:** 10% of FY2025 revenue (~$372M), down from 12% in FY2024. Qorvo is retaining premium-tier Samsung while exiting mass-tier Android. [claim_verification.json: C005, Corroborated]

**Combined top 2:** ~57% of FY2025 revenue.

**Post-merger combined Apple concentration:** If SWKS-QRVO merger closes, Apple would represent ~55% of combined mobile revenue. [Inference: QRVO Apple ~$1.75B + SWKS Apple ~$2.45B = ~$4.2B on combined $7.7B] [Sources: ecosystem_signals.md, claim_verification.json: C005, C021]

**Contractual visibility gap:** Qorvo does not disclose minimum volume commitments, pricing terms, or contract duration with Apple or Samsung. The "expiration of a certain long-term supply agreement" referenced by CEO Bruggeworth introduces re-pricing risk. [transcript_segments.json: CEO Bruggeworth Q1 FY26]

## 2. Apple In-House Modem

The single largest structural risk to QRVO's revenue base. CEO Bruggeworth: "It is our expectations over time that they will use more of their internal modem and the percentage will only grow." [transcript_segments.json: CEO Bruggeworth Q1 FY26]

Analyst Christopher Rolland (Susquehanna) cited "Qualcomm has talked about an expectation of 30% internal modem at your largest customer." CEO Bruggeworth declined to confirm this percentage. [transcript_segments.json: CEO Bruggeworth Q1 FY26, Q&A — note: the 30% figure originated from analyst Rolland citing Qualcomm, not from QRVO management]

**Offsetting factor:** QRVO's custom ET PMIC pairs with Apple's internal baseband, creating content growth on Apple's own modem. Management guided >10% content gains on the fall 2025 platform. [transcript_segments.json: CEO Bruggeworth, CFO Brown Q1 FY26]

**Unquantifiable:** The net impact (content gains from ET PMIC vs. addressable market reduction from modem internalization) cannot be quantified from available data. Management characterizes it as a "durable multiyear content opportunity" but acknowledges the internal modem percentage "will only grow."

## 3. Merger Execution Risk

### Regulatory Status

| Review | Status | Source |
|--------|--------|--------|
| FTC Second Request | Issued Feb 5/6, 2026 | [ecosystem_signals.md; claim_verification.json: C019 — Contradicted on date: receipt Feb 5, disclosure Feb 6] |
| China SAMR Phase 2 | In progress (as of May 2026) | [ecosystem_signals.md] |
| Expected close | Late 2026 / early CY2027 | [ecosystem_signals.md; claim_verification.json: C020, Corroborated] |

### Merger Partner Financial Condition

SWKS Q2 FY2026 data points: revenue -1.0% YoY; non-GAAP GM 45.0% (down 170bps YoY); inventory $885.6M (+17%); negative quarterly FCF (-$32.0M); $147M in merger-related non-GAAP adjustments. [ecosystem_signals.md: SWKS Q2 FY26; claim_verification.json: C024–C026, Verified]

### Post-Merger Integration

$500M+ annual cost synergies expected within 24–36 months on $7.7B combined revenue (6.5% of revenue). Synergies require headcount reductions and facility consolidation. [ecosystem_signals.md; claim_verification.json: C021, Verified]

**Deal value arbitrage:** At QRVO $108.23 and SWKS $83.42, implied deal value is $112.58/share. QRVO trades at a 3.9% discount. [quote.json; ecosystem_signals.md]

## 4. Cyclicality

Revenue peaked at $4.646B (FY2022) and declined to $3.679B (FY2026), -20.8% over 4 years. The FY2023 decline of -23.2% in a single year demonstrates cyclical amplitude. [income.json: revenue]

4-year revenue CAGR (FY2022→FY2026): -5.7%. ACG (~69% of revenue) is directly tied to global smartphone unit volumes and the iPhone product cycle. [income.json; claim_verification.json: C048]

## 5. Restructuring Execution

Multiple simultaneous restructuring initiatives:

| Initiative | Revenue Impact | Status | Risk |
|-----------|---------------|--------|------|
| Mass-tier Android 5G exit | -$150M to -$300M | In progress | Revenue decline rate potentially understated per C056 Contradicted |
| Greensboro NC fab closure | Neutral (transfer) | SAW line building in TX | Execution risk on customer transitions |
| Costa Rica closure | Neutral (transfer) | On track, early CY2027 | Minor |
| MEMS force sensing sale | -$20M OpEx | Active sale process | Buyer uncertainty |

**Android exit revision:** Initial guidance was $150M–$200M annual decline. Per claim_verification.json C056 (Contradicted), Yahoo Finance/Investing.com analyst sources indicate the FY2027 decline has been revised to $300M. This represents a 50–100% increase from original guidance. [claim_verification.json: C056; transcript_segments.json: CFO Brown Q1 FY26]

## 6. Financial Risks

### Tax Rate Volatility

FY2024 effective tax rate of 195.6% produced a $144M tax expense on $74M of pre-tax income, resulting in a -$70M net loss from positive operating income. At a normalized 15% rate, FY2024 NI would have been +$58M instead of -$70M. [income.json: incomeBeforeTax, incomeTaxExpense FY2024]

FY2026 ETR of 14.9% is below the 21% U.S. statutory rate. CFO Brown guided ~15% non-GAAP for FY2026. [transcript_segments.json: CFO Brown Q1 FY26; income.json FY2026]

### AR/Revenue Divergence

FY2024: AR grew +35.6% while revenue grew only +5.6%. DSO expanded from 34 to 41 days. Partially normalized by FY2026 (DSO 40 days) but remains elevated vs. FY2023 (31 days). [balance.json: accountsReceivables; income.json: revenue; metrics.json: daysOfSalesOutstanding]

### SBC Escalation

SBC doubled as a percentage of revenue: 1.8% (FY2022) → 3.7% (FY2026). Absolute SBC increased from $84M to $136M (+62%) while revenue fell 20.8%. [cashflow.json: stockBasedCompensation; income.json: revenue]

### EBITDA Data Quality

FY2026 income.json reports D&A = $0, EBITDA = $411M. Cashflow.json shows D&A = $259M. Adjusted EBITDA = $670M. Any analysis using the unadjusted FMP EBITDA figure will overstate EV/EBITDA (18.2x per metrics.json vs. 14.7x adjusted). [income.json; cashflow.json; metrics.json: evToEBITDA]

## 7. Geopolitical and Tariff

- **China Android:** Revenue declining; ~$100M quarterly in Q1 FY2026, expected to decline further. [transcript_segments.json: CFO Brown Q1 FY26]
- **Tariff buffer:** $15M–$30M of component inventory buffering, mostly China Android. [transcript_segments.json: SVP Fullwood Q1 FY26]
- **Power tools demand pushout:** Battery-operated power tool customers paused due to tariff uncertainty. [transcript_segments.json: CEO Bruggeworth Q1 FY26]
- **U.S. manufacturing advantage:** Onshore manufacturing (OR, TX) may insulate from import tariffs. [Inference: U.S. fabrication reduces tariff exposure on domestic sales] [Sources: transcript_segments.json]

## 8. Manufacturing Concentration

After closures, all wafer fabrication concentrates at two U.S. sites:
- **Hillsboro, OR:** GaAs, GaN — serves all 3 segments [transcript_segments.json: CEO Bruggeworth Q1 FY26]
- **Richardson, TX:** BAW, SAW filters [transcript_segments.json]

A disruption at Hillsboro would affect all three business segments simultaneously.

## 9. Governance

- **Apple CEO transition:** John Ternus succeeds Tim Cook effective September 1, 2026. [ecosystem_signals.md; claim_verification.json: C015, Verified]
- **Post-merger leadership:** Not publicly detailed. [Data gap]
- **Congressional trading:** No Senate or House trading activity in QRVO. [government.json]
- **Insider sales (May 2026):** CFO Brown sold ~$1.4M, SVP Chesley sold ~$1.3M, VP Harrison sold ~$562K, SVP Fego sold $250K — all following equity award vests. CEO Bruggeworth received 102,425 shares but did not execute open-market sales. [insider.json]
- **10b5-1 plan status:** Not determinable from available data. [Data gap]

## 10. Earnings Consistency

EPS beats in 9 of 9 quarters (Q4 FY2024 – Q4 FY2026). Average EPS beat: $0.27. Revenue beats in 8 of 9 quarters; the one miss (Q1 FY2026: -$145M vs estimate) likely reflected analysts' estimates still including divested/exiting businesses. [earnings.json]

## Management Question Deflections

- **Apple modem penetration %:** Analyst Rolland asked about 30% internal modem; CEO Bruggeworth declined to confirm specific percentage. [transcript_segments.json: Q1 FY26 Q&A]
- **Android exit magnitude:** CFO Brown provided range ($150M–$200M) but subsequent revision to $300M came from analyst/media sources, not management confirmation. [claim_verification.json: C056, Contradicted]
- **Apple contract terms:** Management referenced "expiration of a certain long-term supply agreement" but provided no specifics on terms, duration, or pricing. [transcript_segments.json: CEO Bruggeworth Q1 FY26]

## Data Gaps

- **Apple in-house modem timeline:** No specific deployment percentage disclosed by QRVO
- **Geographic revenue breakdown:** FMP segments.json returned empty
- **Product-level revenue:** Not disclosed; segment-level is finest granularity
- **Apple/Samsung contractual terms:** No visibility into minimums, pricing, or duration
- **Post-merger leadership structure:** Not disclosed
- **FTC/SAMR regulatory decision timeline:** No public dates
- **Supplier names and concentration:** 10-K full text not in workspace
- **Patent portfolio:** Not in available data
- **Proxy/governance:** proxy.json returned error ("Ticker not found in EDGAR database")

# Appendix G: Transcript Highlights — Qorvo (QRVO)

*Source: Q1 FY2026 Earnings Call (reported July 29, 2025). Speakers: CEO Robert Bruggeworth, CFO Grant Brown, SVP David Fullwood, SVP Philip Chesley, SVP Frank Stewart.*

[transcript_segments.json; transcript.json]

## Segment Strategy

**CEO Bruggeworth (prepared remarks):**
> "For our largest customer, we supply 4 categories of highly differentiated products. They are antenna tuners, high-performance filters and switches, integrated modules and envelope tracking power management."

> "Qorvo's envelope tracking PMIC for this customer has been custom developed to pair with our internal baseband, and this represents a durable multiyear content opportunity."

> "Defense and aerospace is HPA's largest market by revenue, and we expect durable year-over-year growth in D&A supported by increases in U.S. and allied defense spending."

> "Growth applications include enterprise and AI data centers, wearables, drones, robotics, smartphones and advanced power management solutions for AESA radars."

> "We are engaged broadly across markets and maintain a robust ultra-wideband sales funnel with over $2 billion of qualified opportunities."

## Financial Guidance and Results

**CFO Brown (prepared remarks):**
> "Qorvo's fiscal first quarter revenue of $819 million, non-GAAP gross margin of 44% and non-GAAP diluted earnings of $0.92 per share all compared favorably to guidance."

> "During the quarter, our largest customer represented approximately 41% of revenue."

> "We currently have approximately $1.5 billion of long-term debt outstanding and no near-term maturities."

> "We ended the quarter with a net inventory balance of $638 million. This represents a slight sequential reduction and a decrease of $89 million on a year-over-year basis."

**CFO Brown (on non-GAAP gross margin guidance):**
> Q2 FY2026 non-GAAP gross margin guidance: 48%–50%

> "Non-GAAP tax rate for fiscal '26 is now expected to be approximately 15%, down from previously guided 18%–19%"

## Restructuring and Site Closures

**CFO Brown:**
> "The closure of our Costa Rica site remains on track, and we anticipate a smooth transition."

> "We have also decided to close our manufacturing facility in North Carolina to further consolidate our internal factory footprint."

> "In order to transfer our SAW filter production out of North Carolina, we have begun to bring up a new production line in our Texas location."

> "We expect non-GAAP COGS for each year after the new line goes live will exceed the onetime start-up costs incurred in fiscal '26."

## Apple Modem Discussion

**CEO Bruggeworth (Q&A with analyst Christopher Rolland, Susquehanna):**
> "It is our expectations over time that they will use more of their internal modem and the percentage will only grow."

**Analyst Rolland (question — NOT management statement):**
> "Qualcomm has talked about an expectation of 30% internal modem at your largest customer."

*Note: The 30% figure was stated by analyst Rolland citing Qualcomm, not confirmed by QRVO management. CEO Bruggeworth declined to confirm the specific percentage.*

**CEO Bruggeworth (on content opportunity):**
> "The 16e, iPhone 16e carries the Qorvo envelope tracking PMIC paired with the internal baseband. We believe this represents a durable multiyear content opportunity."

## Android Exit

**CFO Brown:**
> "We have actively managed our product portfolio and pricing strategies to reduce our exposure to mass tier Android 5G."

**SVP Fullwood:**
> China Android revenue was ~$240M in Q1 FY2026 with projected $30M–$40M sequential decline.

> "Share gains that we have in the second half at our large Korean customer" — referring to Samsung premium-tier retention.

## Defense and Aerospace

**CEO Bruggeworth:**
> "We are strategically important to the DoD and leading defense primes."

> Cited $150B in additional U.S. defense funding via budget reconciliation.

> D&A sales funnel increased approximately $2B sequentially to >$7B.

> Programs include "radar, comms, SATCOM and missile defense" including "Golden Dome multilayer defense system."

**SVP Chesley:**
> GaN products are "critical in most comm, radar, satellite, SATCOM systems with the U.S. government."

## UWB and Connectivity

**CEO Bruggeworth:**
> UWB design wins: leading Japanese auto OEM, world's leading EV manufacturer, South Korean auto OEM (asset tracking tags), Wi-Fi 7 in AR glasses.

**CFO Brown:**
> UWB SoC business generates "annual revenues right now of around $60 million" with "around $100 million of OpEx."

> One automotive customer delayed a UWB program ramp, pushing CSG growth from 10–12% guidance to "low single digits."

## Samsung Internal Baseband

**CEO Bruggeworth (Q&A with analyst Chris Caso):**
> "The answer is yes. We would love for them to be successful with their internal baseband across business units, not just ACG."

*Context: Samsung's Exynos chipset using third-party RF benefits Qorvo vs. Qualcomm's integrated modem+RF bundle.*

## Manufacturing Footprint

**CEO Bruggeworth:**
> "We offer gas [GaAs], GaN, BAW, SAW and advanced multichip packaging, all manufactured onshore in the U.S."

> "They all use the same Oregon, Hillsboro fab for gas, all 3 business units."

## Long-Term Supply Agreement

**CEO Bruggeworth (Q&A with analyst Harsh Kumar):**
> Referenced "the expiration of a certain long-term supply agreement" as "helping us" commercially.

*Context: Implies a prior contractual arrangement with Apple (unnamed) has ended, potentially improving QRVO's commercial flexibility for re-pricing.*

## Content Growth at Apple

**CFO Brown:**
> "Content gain that we see of 10% or more on the ramping platform."

## Tariff Impact

**SVP Fullwood:**
> Tariff-related inventory buffering estimated at $15M–$30M, mostly China Android, described as "modest."

**CEO Bruggeworth:**
> Battery-operated power tool customers paused production plans pending tariff clarity.

## 5G Advanced

**SVP Stewart:**
> 5G Advanced specifications requiring higher power levels across more bands will drive "more and better RF" content per phone (Power Class 2 expansion).

# Appendix H: Source Index — Qorvo (QRVO)

## Tier 1: SEC Filings and Company Announcements

| File | Data Provider | Date | Content |
|------|--------------|------|---------|
| claim_verification.json: C005 | EDGAR (10-K FY2025, FY2024) | FY2025 filed May 2025; FY2024 filed May 2024 | Apple 47%/46%, Samsung 10%/12% customer concentration |
| claim_verification.json: C095 | EDGAR (10-K FY2023) | FY2023 filed May 2023 | Three-segment reorganization confirmed |
| claim_verification.json: C098 | Q4 FY2026 press release | May 5, 2026 | Q4 FY2026 segment revenue and operating margins |
| claim_verification.json: C099 | EDGAR (10-K FY2025, rfmd-20250329.htm) | Filed May 2025 | Overcapacity in premium filter manufacturing |
| claim_verification.json: C073 | EDGAR (10-K) | Annual filing | Named competitors list |
| news.json | GlobeNewsWire | May 20, 2026 | Skyworks exchange offers for QRVO senior notes |
| news.json | GlobeNewsWire | May 5, 2026 | Q4 FY2026 earnings release |
| filing_events.json | EDGAR (8-K filings) | Various 2025–2026 | 10 filings identified; items failed to parse |
| edgar_search_risks.json | EDGAR EFTS | Various | 10-K filing list for risk factor analysis |

## Tier 2: Standardized Financial APIs (FMP)

| File | Data Provider | Date | Content |
|------|--------------|------|---------|
| income.json | FMP | FY2015–FY2026 (filed May 8, 2026 for FY2026) | Revenue, gross profit, operating income, net income, EPS, shares |
| balance.json | FMP | FY2019–FY2026 (filed May 8, 2026 for FY2026) | Assets, liabilities, equity, debt, cash, inventory |
| cashflow.json | FMP | FY2016–FY2026 | OCF, capex, FCF, SBC, D&A, buybacks, acquisitions |
| metrics.json | FMP | FY2022–FY2026 | ROIC, margins, working capital metrics, EV/EBITDA |
| ratios.json | FMP | FY2022–FY2026 | Gross margin, operating margin, interest coverage, ETR |
| quote.json | FMP | May 26, 2026 (real-time) | Price $108.23, market cap, 52-week range |
| info.json | FMP | May 26, 2026 | Company profile, beta 1.42, employees 6,200, CEO |
| technicals.json | FMP | May 26, 2026 | RSI, SMAs, EMAs, ADV |
| earnings.json | FMP | Q4 FY2024 – Q1 FY2027E | EPS and revenue actuals vs. estimates |
| ratings.json | FMP | May 2026 | Forward estimates FY2027–FY2029, analyst grades, price targets |
| enterprise_value.json | FMP | FY2022–FY2026 | Historical enterprise value at filing-date prices |
| shares_float.json | FMP / SEC | May 25, 2026 | Outstanding 88.0M, float 79.5M, free float 90.4% |
| scores.json | FMP | Current | Altman Z-Score 3.53, Piotroski 9/9 |
| dcf.json | FMP | Current | FMP DCF fair value $52.29 |
| peers.json | FMP | Current | Peer list: AMKR, CRUS, LSCC, SWKS, etc. |
| peer_compare.json | FMP | Current | Peer company profiles |
| insider.json | FMP | May 2026 | Officer sales and awards |
| dividends.json | FMP | Historical | No dividends paid |
| segments.json | FMP | Error | 404 — FMP segments data unavailable |
| short_interest.json | FMP | Error | 404 — Short interest unavailable |
| options.json | FMP | Error | Options data unavailable |
| convertible_search.json | EDGAR | Historical | No convertible securities found |
| government.json | FMP | Current | No Congressional trading activity |

## Tier 3: Earnings Transcripts

| File | Data Provider | Date | Content |
|------|--------------|------|---------|
| transcript.json | FMP transcript API | Q1 FY2026 (Jul 29, 2025) | Full earnings call: Bruggeworth, Brown, Fullwood, Chesley, Stewart |
| transcript_segments.json | FMP transcript API | Q1 FY2026 | Keyword-matched segments with speaker attribution |

## Tier 4: Third-Party Research / Web Sources

| File | Data Provider | Date | Content |
|------|--------------|------|---------|
| ecosystem_signals.md | Multiple (Apple Newsroom, CNBC, Skyworks IR, Broadcom IR) | Apr–May 2026 | Peripheral company signals |
| competitive_by_product.md | CSIMarket, Yale SOM, industry sources | Various | Competitor identification, market share estimates |
| competitive_history.md | Various web sources | Various | Market share evolution, merger commentary |
| supplier_capacity.md | EDGAR / web research | Various | Overcapacity confirmation |
| business_overview.md | Web research | Various | Company overview data |
| segment_financials.md | Web research | Various | Segment revenue reconstruction |
| industry.json | Web research | Various | Industry context |
| customer_capex.md | Web research | Various | Customer spending data |

## Tier 5: Context Only

| File | Data Provider | Date | Content |
|------|--------------|------|---------|
| claim_verification.json | Cross-referencing engine | May 27, 2026 | 130 claims: 63 Verified, 34 Corroborated, 16 Single-Source, 9 Contradicted, 8 Unverifiable |

## Files Not Available / Errors

| File | Status | Impact |
|------|--------|--------|
| segments.json | FMP 404 error | No FMP segment data; reconstructed from transcripts and press releases |
| short_interest.json | FMP 404 error | Short interest % of float unknown |
| options.json | Empty | No options data available |
| latest_10k.json | Not in workspace | Full 10-K text unavailable for supplier, contract, and covenant detail |
| proxy.json | EDGAR error ("Ticker not found") | Governance and compensation data unavailable |
| facts.json | Partial (concept names only) | XBRL data incomplete — unit counts but not values |
| filing_events.json | Parse failure | All 10 8-K items failed to parse |

## Cross-Reference Discrepancies

| Discrepancy | Source A | Source B | Resolution |
|------------|---------|---------|------------|
| WACC estimate | financial_data.md: 11.0% (mkt cap basis weights) | risk_factors.md: 10.4% (EV basis weights) | Different denominator; both indicate negative ROIC-WACC spread |
| Android exit magnitude | transcript Q1 FY26: $150M–$200M | Yahoo/Investing.com (C056): $300M for FY2027 | Contradicted per C056; original guidance may be understated |
| FY2023 Apple concentration | risk_factors.md: 37% | business_profile.md: not cited for FY2023 | risk_factors.md cites FY2023 Apple at 37% but C005 only confirms FY2025 (47%) and FY2024 (46%) |
| ADV | technicals.json: $114.4M (at ~$94 avg) | info.json × price: $130.5M (at $108.23) | Different computation prices; report uses info.json × current price |
| FY2026 D&A | income.json: $0 | cashflow.json: $258,648,000 | FMP data artifact; cashflow.json is authoritative |
| info.json segments | Two segments listed | Actual: three segments since Q2 FY2023 | info.json reflects outdated FMP classification |
