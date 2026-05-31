---
type: company
ticker: UBER
name: Uber
updated: "2026-05-31"
sources:
  - info.json
  - value_chain.md
  - segments.json
  - insider.json
  - holders.json
  - transcript_competitors.json
---

# Uber (UBER)

## Key Insiders

- Krishnamurthy Balaji (A) (officer: Chief Financial Officer)
- Macdonald Andrew (officer: See Remarks)

## Top Institutional Holders

- Alpha Square Group S, LLC
- Altimeter Capital Management, LP
- Chescapmanager LLC
- Draper Asset Management, LLC
- EMJ Capital Ltd.
- Freshford Capital Management, LLC
- Game Plan Financial Advisors, LLC
- Genesis Financial Group, LLC
- GPI CAPITAL, L.P.
- INVESTMENT MANAGEMENT ASSOCIATES INC /ADV

---

# Uber Technologies, Inc. (UBER) — Research Report

**Report Date:** 2026-05-22 [File: run_config.json — generated date]
**Data As Of:** 2026-05-21 (price), FY2025 for annual financials, Q1 2026 for most recent quarter [File: quote.json — timestamp; income.json — FY2025; earnings.json — Q1 2026]
**Ticker:** UBER | NYSE | Technology | Software - Application [File: info.json — symbol, exchange, sector, industry]
**Price:** $73.61 [File: info.json — price]
**ADV:** $1,250MM [File: info.json — averageVolume 16,987,812 × price $73.61]
**Market Cap:** $149.8B [File: info.json — marketCap $149,840,516,000]
**Net Debt:** $5.2B (3.5% of mkt cap) [File: balance.json — totalDebt $13,470M − cashAndShortTermInvestments $8,264M]
**Net Cash:** -$5.2B (-3.5% of mkt cap) [File: balance.json — cashAndShortTermInvestments $8,264M − totalDebt $13,470M]
**Enterprise Value:** $155.0B [Inference: $149.8B mkt cap + $13.5B debt − $8.3B cash & STI] [File: quote.json — marketCap; balance.json — totalDebt, cashAndShortTermInvestments]; FMP year-end FY2025 EV: $176.1B at $81.71/share [File: enterprise_value.json — enterpriseValue]
**Short Interest:** ~3.8 days to cover [File: short_interest.md — Single-Source: MarketBeat]; shares short N/A [Data gap: short_interest.json returned 404]; float 2,024M shares [File: shares_float.json — floatShares 2,023,955,387]

---

## 1. Business Overview

<!-- IC Question: What does this company do, how is it organized, and how large is each piece? What Would Change the Answer: Major divestiture, acquisition, segment reclassification, revenue mix shift. -->

### Company Identity

Uber Technologies, Inc. is headquartered at 1515 3rd Street, San Francisco, CA 94158. The company operates a multi-sided technology platform in the Technology sector (Software — Application subsector), listed on the NYSE. CEO: Dara Khosrowshahi. Full-time employees: 31,100. IPO date: May 10, 2019. [File: info.json — address, sector, industry, ceo, fullTimeEmployees, ipoDate]

### Reportable Segments

Uber reports three operating and reportable segments: **Mobility**, **Delivery**, and **Freight**. [File: info.json — description] FMP's segments.json returned empty (404 error) [File: segments.json — segments_message], so segment revenue is reconstructed from SEC filings via third-party aggregators and transcript commentary.

**FY2024 Segment Revenue (from 10-K):**

| Segment | Revenue | % of Total | Source |
|---------|---------|------------|--------|
| Mobility | $25.09B | 57.0% | [File: claim_verification.json — Investopedia citing 10-K, Verified] |
| Delivery | $13.75B | 31.3% | [File: claim_verification.json — Investopedia citing 10-K, Verified] |
| Freight | $5.14B | 11.7% | [Inference: $43.978B total − $25.09B − $13.75B = $5.14B] [File: income.json — FY2024 revenue; claim_verification.json] |
| **Total** | **$43.98B** | **100%** | [File: income.json — FY2024 revenue $43,978,000,000] |

**FY2025 Segment Revenue (estimated):**

| Segment | Revenue | % of Total | YoY Growth | Source |
|---------|---------|------------|------------|--------|
| Mobility | ~$29.67B | ~57.0% | +18.3% | [File: segment_financials.md — Single-Source: bullfincher.io FY2025 breakdown; applied to income.json total] |
| Delivery | ~$17.25B | ~33.2% | +25.5% | [File: segment_financials.md — Single-Source: bullfincher.io; FY2024 figure of $13.75B is Verified from 10-K] |
| Freight | ~$5.10B | ~9.8% | −0.8% | [Inference: $52.02B − $29.67B − $17.25B ≈ $5.10B] [File: income.json — FY2025 revenue; segment_financials.md] |
| **Total** | **$52.02B** | **100%** | **+18.3%** | [File: income.json — FY2025 revenue $52,017,000,000] |

**Data quality note:** FY2025 segment-level revenue is not available from primary SEC filings in this workspace. The FY2025 10-K (accession 0001543151-26-000015, filed 2026-02-13) was not fully extracted. Bullfincher.io is the sole source for FY2025 segment breakdown; its FY2024 figures match the verified 10-K data, lending credibility, but FY2025 figures remain [Single-Source]. [File: latest_10k.json — XBRL header only; segment_financials.md]

**Q1 2026 Key Operating Metrics:** [File: earnings.json — Q1 2026; transcript.json — operating metrics]

| Metric | Q1 2026 | YoY Growth | Source [File: earnings.json; transcript.json] |
|--------|---------|------------|--------|
| Revenue | $13.203B | +14.5% | [File: earnings.json — revenueActual $13,203,000,000; claim_verification.json — Verified] |
| Gross Bookings | $53.7B | +25% (+21% cc) | [File: claim_verification.json — Verified vs investor.uber.com] |
| Mobility GB Growth | — | +20% | [File: transcript.json — CEO Dara Khosrowshahi] |
| Delivery GB Growth | — | +23% | [File: transcript.json — CEO Dara Khosrowshahi] |
| Freight | — | Returned to growth | [File: transcript.json — CEO Dara Khosrowshahi: "freight returned to growth for the first time in nearly 2 years"] |
| Trips | 3.6B | +20% | [File: claim_verification.json — Corroborated vs press release] |
| Adjusted EBITDA | $2.5B | +33% | [File: claim_verification.json — Verified vs investor.uber.com] |

Q1 2026 segment-level revenue is a data gap; only segment-level gross bookings growth rates are available. [File: transcript.json — segment commentary only]

### Key Products by Segment

**Mobility** (~57% of FY2025 revenue [File: segment_financials.md — Single-Source: bullfincher.io]): UberX/core rideshare (majority of segment), Uber Reserve (pre-scheduled rides; airports ~15% of Mobility GB [File: transcript.json — CEO Dara]), premium products (Uber Black, Comfort, XL — "3.5x higher profit growth" [File: transcript.json — CFO Balaji Krishnamurthy]), low-cost products (Wait & Save, UberX Share — "75% higher frequency" [File: transcript.json — CFO Balaji]), Uber for Business, and Uber Transit.

**Delivery** (~33% of FY2025 revenue [File: segment_financials.md — Single-Source: bullfincher.io]): Uber Eats restaurant delivery (core), grocery & retail ("led by grocery and retail" per Q1 2026 [File: transcript.json — CEO Dara]), Uber Direct (white-label delivery-as-a-service), and advertising (projected >$1B annual run rate in 2024 [File: claim_verification.json — Single-Source: Mobisoft blog]).

**Freight** (~10% of FY2025 revenue [Inference: $52.02B − $29.67B − $17.25B ≈ $5.10B residual] [File: income.json — FY2025 revenue; segment_financials.md]): Digital freight brokerage marketplace and managed transportation services. Average lead time 4-5 days, as low as 3 hours. [File: claim_verification.json — Verified from Uber engineering blog]

### Gross Bookings vs Revenue (Take Rates)

Uber's revenue is the net take after paying drivers, couriers, and merchants. Q4 2025 take rates: Mobility 29.9%, Delivery 19.2%. [File: claim_verification.json — Corroborated] FY2025 blended take rate: 26.9% ($52.0B revenue / $193.5B Gross Bookings). [File: claim_verification.json — Verified from UBER FY2025 press release; income.json — FY2025 revenue] Q1 2026 blended take rate: 24.6% ($13.203B / $53.7B). [Inference: arithmetic from Q1 2026 revenue and GB] [File: earnings.json — revenueActual; claim_verification.json — GB Verified] The lower Q1 take rate is consistent with seasonal mix shift toward lower-take-rate Delivery and potential Mobility pricing reinvestment. [Inference: mix-shift explanation] [File: transcript.json — CFO Balaji commentary on pricing]

### Narrative vs. Reality

**Autonomous vehicle narrative:** Uber has 30+ AV partners (Waymo, Baidu Apollo Go, Pony.ai, NVIDIA targeting 100K AVs by 2027, Nuro, Lucid). AV Mobility trips grew >10x YoY. Uber targets 15 AV markets by year-end 2026. [File: transcript.json — CEO Dara; claim_verification.json — NVIDIA target Corroborated by 5+ sources; Baidu/Pony.ai Verified via PRNewswire]

**AV revenue disclosure: None.** AV trips are included within Mobility but the absolute volume and revenue are undisclosed. The AV business is pre-meaningful-revenue scale. [Data gap]

**What drives the P&L today:** Mobility is the dominant segment at ~57% of FY2025 revenue (~$29.67B [File: segment_financials.md — Single-Source]) with the highest take rate (29.9% [File: claim_verification.json — Corroborated]). Delivery is the fastest-growing segment (+25.5% FY2025 [File: segment_financials.md — Single-Source] vs Mobility's +18.3%). Freight is the smallest (~10%) and was declining until Q1 2026. [File: transcript.json — CEO Dara on Freight return to growth]

**AI:** Uber uses AI for pricing, matching, routing, destination prediction (3/4 of rides [File: transcript.json — CEO Dara]), code generation (~10% of code from autonomous agents [File: transcript.json — CEO Dara]), and customer service. CFO Balaji noted the company "re-upped" AI investment in 2026 budget planning. AI spending is not separately disclosed. [File: transcript.json — CFO Balaji]

### Consumer Base

No single customer represents a material percentage of consolidated revenue — inherent to the consumer marketplace model. [File: info.json — description] Uber One members: 50M+ (growing 50% YoY), accounting for >50% of bookings, spending 3x more. Audience grew 17% YoY. Drivers/couriers: 10M+ globally. [File: transcript.json — CEO Dara]

### Brief History

Founded 2009 as UberCab, renamed February 2011, IPO'd May 2019. [File: info.json — ipoDate] Acquired Postmates (2020, Delivery) and Transplace (2021, ~$2.25B, Freight). Divested ATG self-driving unit to Aurora Innovation (2021) and Uber Elevate (air taxi), pivoting from proprietary AV development to a platform/partnership model. Recently expanded into hotel bookings via Expedia partnership announced at April 2026 GO-GET event. [File: claim_verification.json — Aurora notes; transcript.json — CEO Dara]

---

## 2. Competitive Position

<!-- IC Question: For each product, who competes with this company and what are their relative strengths? What Would Change: Loss of a top customer, entry of well-capitalized competitor, customer building in-house alternative. Base Rate: What % of companies in this industry lost competitive position to a new entrant in past 5 years? The US rideshare market has had no meaningful new entrant since Lyft established itself. -->

### Mobility (US Rideshare)

**Market share:** Transaction-data-based estimates (Second Measure, Statista, DemandSage) cluster around 74-76% US share for Uber as of mid-2025. An outlier figure of 55% (PESTEL Analysis, Dec 2025) lacks primary methodology. A global 37.2% figure is unverifiable. [File: claim_verification.json — C065, tag: Contradicted — multiple sources cited with no primary SEC filing confirmation]

**Lyft (sole US competitor):** FY2025 Gross Bookings $18.5B (+15% YoY). Q1 2026 GB $4.95B (+19% YoY). Revenue $6.3B (+9% YoY). Net income $2.8B (includes $2.9B tax valuation allowance release, which increased reported net income above operating earnings). [Inference: tax valuation release inflates reported NI above operating level] [File: ecosystem_signals.md — Verified; claim_verification.json — Lyft net income Verified] The Uber/Lyft US duopoly has been stable for several years; both showed accelerating bookings in Q1 2026. [File: ecosystem_signals.md — Q1 2026 data]

**International:** Bolt (Europe), Grab (Southeast Asia), DiDi (China — Uber exited 2016), Ola (India). Geographic revenue breakdown is unavailable. [File: competitive_by_product.md — international competitors; Data gap]

### Delivery (Food/Grocery)

**DoorDash (primary US competitor):** FY2025 revenue $13.7B (+28% YoY). Q1 2026 revenue $4.0B (+33% YoY), 933M orders (+27% YoY), GOV $31.6B (+37% YoY). 56M+ MAUs. Deliveroo acquisition (mid-2025) contributed ~4pp to GOV growth and added European delivery scale. [File: ecosystem_signals.md — Verified; claim_verification.json — Deliveroo 4pp impact Verified]

DoorDash is growing faster than Uber Delivery across all metrics. CFO Balaji noted "incremental level of competitive intensity from both DoorDash and Prosus" in European markets but stated Uber has "held our own quite well." [File: transcript.json — CFO Balaji]

**Instacart:** FY2025 GTV $37.2B (+11% YoY). Q1 2026 GTV $10.29B (+13% YoY). Revenue $3.7B. [File: ecosystem_signals.md — Verified] Growing slower than multi-category platforms; building enterprise grocery technology (Storefront, Caper smart carts). [File: ecosystem_signals.md]

**Data gap:** Neither Uber nor DoorDash discloses US food delivery market share in filings. No reliable third-party share data with primary methodology was located.

### Freight

The North American freight market is estimated at >$800B. [File: claim_verification.json — Single-Source: Mobisoft blog, methodology unknown] Uber Freight at ~$5.1B revenue represents <1% of this market. [Inference: $5.1B / $800B+ = <1%] [File: income.json — FY2025 total; segment_financials.md] The freight brokerage market is highly fragmented with thousands of traditional brokers. Key digital competitors: C.H. Robinson, XPO Logistics. Freight returned to growth for the first time in ~2 years in Q1 2026. [File: transcript.json — CEO Dara]

### Switching Costs

**Consumers:** Low technical/financial switching costs (downloading a competitor app is free). Behavioral lock-in via Uber One (50M+ members, >50% of bookings, 3x spend). Cross-platform usage (Mobility + Delivery) creates deeper engagement; $15B annualized Delivery GB from the Mobility app. [File: transcript.json — CEO Dara, CFO Balaji]

**Drivers/couriers:** Low. Multi-homing across platforms is common. Economic incentive (not contractual barrier) to prioritize Uber's larger demand pool. [File: transcript.json — CEO Dara on driver economics]

### Competitive Threats

1. **DoorDash** — faster Delivery growth (33% vs ~25% [File: ecosystem_signals.md — Verified]). Deliveroo acquisition closes European scale gap. [File: claim_verification.json — Deliveroo 4pp impact]
2. **Waymo/AV direct-to-consumer** — operates own rideshare app. CEO Dara states category position in SF/LA is "higher today than 6 months ago" despite Waymo. [File: transcript.json — CEO Dara]
3. **AI agent intermediation** — third-party agents could abstract away the Uber app. CEO Dara draws analogy to travel metasearch. [File: transcript.json — CEO Dara, response to analyst Michael Morton (MoffettNathanson)]
4. **Regional competitors** — Bolt, Grab, Prosus in various geographies. [File: competitive_by_product.md]
5. **Regulatory** — driver reclassification as employees remains a structural threat. [File: info.json — description references independent providers]

---

## 3. Supply/Demand Balance

<!-- IC Question: Is industry supply sufficient to meet demand at current prices, and when does that change? What Would Change: Major capacity announcement, demand shock, policy change. Base Rate: What is the typical duration of supply/demand imbalances in this industry? The rideshare market is demand-led with responsive supply (drivers self-select based on earnings). -->

### Demand Decomposition

**Platform demand (Q1 2026):** 3.6B trips (+20% YoY), $53.7B Gross Bookings (+25% YoY, +21% cc). Audience +17% YoY. Uber One members: 50M+ (+50% YoY), >50% of bookings. Cross-platform: $15B annualized Delivery GB from Mobility app; 30% of eligible Mobility consumers have never used Uber Eats. [File: transcript.json — CEO Dara, CFO Balaji; claim_verification.json — trips Corroborated, GB Verified]

**Historical trajectory:** Revenue grew from $11.1B (FY2020) to $52.0B (FY2025), a 5-year CAGR of 36.1%. 3-year CAGR (FY2022-FY2025): 17.7%. GB growth accelerating: Q1 2026 +25% YoY vs Q4 2025 +22% YoY. [File: income.json — revenue history FY2020-FY2025; earnings.json — Q1 2026 data; transcript.json — Q4 2025 GB growth]

**Demand durability drivers:** (1) Urbanization and convenience demand — both Uber and Lyft rider growth >16% YoY. [File: ecosystem_signals.md — Lyft rider growth Corroborated] (2) Insurance cost tailwinds — "hundreds of millions" in US savings in 2026, passed to consumers, driving volume. [File: transcript.json — CFO Balaji] (3) Suburban expansion — sparse markets growing 2x faster than urban. [File: transcript.json — CEO Dara] (4) Cross-platform compounding via Uber One. [File: transcript.json — CFO Balaji] (5) New verticals: hotel bookings (Expedia, 700K+ properties, launched Apr 2026). [File: transcript.json — CEO Dara]

### Supply Analysis

**Drivers/couriers:** 10M+ globally. No specific supply constraint identified. In AV markets, "driver earnings are up, more drivers are joining those platforms." [File: transcript.json — CEO Dara] Supply is responsive to demand growth.

**AV supply (constraint):** AV is supply-constrained. AV Mobility trips grew >10x YoY but are limited by vehicle availability and regulatory approvals. CEO Dara: "the blockers are — we just need more cars on the road." 30+ partners; NVIDIA targeting 100K AVs by 2027. Uber Autonomous Solutions launched for fleet management, data, financing (Santander), insurance (Marsh/Apollo). [File: transcript.json — CEO Dara; claim_verification.json — NVIDIA target Corroborated]

**Freight supply:** Contract rates up 5-6% YoY (ex-fuel) as of April 2026. [File: supply_indicators.md — Single-Source: Uber Freight market update, uberfreight.com] Recovering from ~2-year downturn. [File: transcript.json — CEO Dara]

### Supply/Demand Synthesis

**Mobility:** Demand expanding; supply responsive. No acute driver shortage. Constraint is geographic coverage in suburban/sparse markets, being actively expanded. Uber is pricing for growth — passing insurance savings to consumers to drive volume. [File: transcript.json — CFO Balaji on insurance cost leverage]

**Delivery:** No supply constraint. Merchant selection expansion in suburban markets is the growth lever. [File: transcript.json — CEO Dara on suburban expansion]

**AV:** Supply-constrained. AV trips >10x YoY from small base; targeting 15 cities by year-end 2026. Limited by vehicle availability and regulation. [File: transcript.json — CEO Dara]

**Freight:** Recovering. Contract rates climbing, freight returned to growth in Q1 2026. [File: transcript.json — CEO Dara; supply_indicators.md]

**Pricing:** Mobility take rate 29.9% (Q4 2025 [File: claim_verification.json — Corroborated]). Blended take rate declining from 26.9% (FY2025) to 24.6% (Q1 2026) [Inference: mix shift toward lower-take-rate Delivery and potential Mobility price reinvestment] [File: income.json — FY2025 revenue; claim_verification.json — FY2025 GB Verified; earnings.json — Q1 2026 revenue]

### Bargaining Power

**Demand-side:** Consumers are price-elastic (insurance-driven price reductions in California drove trip growth acceleration [File: transcript.json — CFO Balaji]). Uber One members are less price-sensitive (3x spend, higher retention). [File: transcript.json — CEO Dara]

**Supply-side:** Drivers multi-home freely. AV partners are both suppliers and potential competitors (Waymo dual relationship). Restaurants list on multiple platforms. [File: transcript.json — CEO Dara on Waymo; competitive_by_product.md]

### AI Value Chain Positioning

Uber is an application-layer user of AI, not an infrastructure or model provider. AI is embedded in 100% of operations (pricing, matching, routing, customer service, code generation) but generates 0% of revenue as a standalone product. The AV business is adjacent and pre-meaningful-revenue. [File: transcript.json — CEO Dara, CFO Balaji]

---

## 4. Value Chain

<!-- IC Question: Where is value captured, and is it migrating toward or away from this company? What Would Change: Vertical integration by customer/supplier, margin compression, technology disintermediation. Base Rate: How often does value chain position shift materially within 5 years? For platform marketplaces, the dominant platform position is relatively durable once established. -->

### Value Chain Map

Uber owns the platform/matching layer in three two-sided marketplaces. It does NOT own vehicles, prepare food, or haul freight. [File: info.json — "connects consumers with independent providers"]

- **Demand aggregation:** 50M+ Uber One members, 3.6B quarterly trips, 10M+ drivers/couriers [File: transcript.json — CEO Dara, Q1 2026 call]
- **Matching/pricing:** Proprietary AI/ML algorithms (pricing, ETA, routing, destination prediction) [File: transcript.json — CEO Dara]
- **Payment:** Processes payments, manages earner/merchant payouts [File: info.json — description]
- **Revenue model:** FY2025 Gross Bookings $193.5B; Uber retained $52.0B as revenue (26.9% blended take rate). ~$141B flowed through to drivers, couriers, merchants, carriers. [File: income.json — FY2025 revenue $52,017M; claim_verification.json — GB Verified from FY2025 press release]

### Margin Capture by Value Chain Stage (FY2025)

| Stage | Company | Revenue | Gross Margin | Op Margin | Source |
|-------|---------|---------|-------------|-----------|--------|
| Multi-category platform | UBER | $52.0B | 39.8% | 10.7% | [File: income.json — FY2025] |
| Pure-play rideshare | LYFT | $6.3B | 41.5% | −3.0% | [File: peer_compare.json — LYFT income; ecosystem_signals.md] |
| Delivery platform | DASH | $13.7B | 50.9% | 5.3% | [File: peer_compare.json — DASH income; ecosystem_signals.md] |
| Grocery platform | CART | $3.7B | 73.7% | 13.3% | [File: peer_compare.json — CART income; ecosystem_signals.md] |
| Asset-based freight | XPO | $8.2B | 12.0% | 8.9% | [File: peer_compare.json — XPO income] |

Uber's 39.8% gross margin is lower than DASH and CART because it includes Freight (~10% of revenue), which drags down blended margins. Operating margin (10.7%) demonstrates operating leverage at scale — Lyft at $6.3B revenue remains operating-loss-negative. [Inference: operating leverage comparison] [File: income.json — UBER FY2025; peer_compare.json — peer data]

### Operating Margin Trajectory

| Company | FY2023 | FY2024 | FY2025 | Direction | Source |
|---------|--------|--------|--------|-----------|--------|
| UBER | 3.0% | 6.4% | 10.7% | Expanding (+7.7pp in 2 years) | [File: income.json — FY2023-FY2025] |
| LYFT | −10.8% | −2.1% | −3.0% | Still negative | [File: peer_compare.json — LYFT] |
| DASH | −6.7% | −0.4% | 5.3% | Expanding | [File: peer_compare.json — DASH] |
| CART | −70.4% | 14.5% | 13.3% | Stabilized | [File: peer_compare.json — CART] |

### Integration Direction

**Forward (toward customers):** Uber One (50M+ members, cross-platform lock-in), hotel bookings (Expedia partnership, 700K properties, launched April 2026), advertising (in-house ad platform, projected >$1B annual [File: claim_verification.json — Single-Source: Mobisoft blog]), Uber Direct (white-label delivery). [File: transcript.json — CEO Dara]

**Backward (toward suppliers):** Uber Autonomous Solutions (fleet management, depot/charging, data collection, financing via Santander, insurance via Marsh/Apollo). Capital-light model — Uber does not build AV technology. [File: transcript.json — CEO Dara]

**Competitor integration:** DoorDash acquired Deliveroo (2025), adding European scale. Instacart building enterprise grocery tech (Storefront, Caper). Waymo operates both through Uber and independently — a supplier that is also forward-integrating toward consumers. [File: ecosystem_signals.md; transcript.json]

### Dependencies and Vulnerabilities

1. **Independent contractor classification** — 10M+ earners vs 31,100 employees (ratio ~322:1). Reclassification would restructure the cost base. [File: info.json — fullTimeEmployees; transcript.json — earner count]
2. **Geographic concentration** — data gap. Uber operates in 70+ countries but geographic revenue breakdown unavailable. [File: info.json — description; Data gap]
3. **Waymo dual relationship** — simultaneously AV supplier and competing consumer service. CEO Dara: "we don't see any effect of the Waymo launches on our overall business." [File: transcript.json — CEO Dara]
4. **AI agent disintermediation** — third-party agents could bypass the Uber app. Uber claims leverage to "dictate the terms of trade." [File: transcript.json — CEO Dara]
5. **Insurance cost volatility** — material Mobility cost item. FY2026 expected to be "the first year since COVID where we expect to see good leverage on our insurance cost line." [File: transcript.json — CFO Balaji]

---

## 5. Capital Structure

<!-- IC Question: How does the company raise money to spend on its business? What Would Change: Major debt issuance/repayment, M&A financing, credit rating change, convertible conversion, new equity issuance. -->

### Equity Composition

Single class of common stock. No preferred equity outstanding ($0 as of FY2025). [File: balance.json — preferredStock $0] Outstanding shares: 2,036M (Q1 2026 10-Q). Float: 2,024M shares (99.4% free float). [File: shares_float.json — floatShares 2,023,955,387, outstandingShares 2,035,600,000]

**Market Cap:** $149.8B at $73.61/share. [File: quote.json — marketCap $149,840,516,000]

### Debt Composition

| Component | FY2025 | FY2024 | Source |
|-----------|--------|--------|--------|
| Short-term debt | $169M | $1,461M | [File: balance.json — shortTermDebt] |
| Long-term debt | $11,911M | $8,347M | [File: balance.json — longTermDebt] |
| Capital lease obligations | $1,390M | $1,628M | [File: balance.json — capitalLeaseObligations] |
| **Gross Debt** | **$13,470M** | **$11,436M** | [File: balance.json — totalDebt] |

Gross debt increased $2,034M YoY, driven by long-term debt rising $3,564M while short-term debt fell $1,292M. [Inference: debt increase correlates with known issuances including May 2025 $1.0B Aurora Exchangeable Notes and refinancing] [File: balance.json — FY2025 vs FY2024 totalDebt components; claim_verification.json — Aurora notes Verified]

### Convertible/Exchangeable Securities

1. **0.875% Convertible Senior Notes due December 1, 2028:** $1.5B issued November 2023. Conversion price ~$72.54/share. At current price $73.61, these are in-the-money — potential dilution of ~20.7M shares. [File: claim_verification.json — Verified via Uber IR press release and SEC 8-K]
2. **0% Exchangeable Senior Notes due May 15, 2028:** $1.0B issued May 2025. Exchangeable for Aurora Innovation (AUR) Class A common stock. Redeemable for cash on or after May 21, 2027 if Aurora stock ≥130% of exchange price. [File: claim_verification.json — Verified via SEC 8-K]
3. **0% Convertible Senior Notes due December 15, 2025:** $1.0-1.15B — matured/settled in December 2025. [File: claim_verification.json — Verified via SEC indenture]

Total outstanding convertible/exchangeable: ~$2.5B ($1.5B Dec 2028 + $1.0B May 2028). [Inference: sum of outstanding notes after Dec 2025 maturity] [File: claim_verification.json — individual note details Verified]

### Debt Maturity Profile

Specific maturity schedule by year is a **data gap** — the FY2025 10-K was not fully extracted (latest_10k.json contains XBRL header only). Known maturities: $1.5B convertible (Dec 2028) and $1.0B exchangeable (May 2028). [File: latest_10k.json — limited extraction; claim_verification.json — note maturities Verified]

### Cash and Equivalents

| Component | FY2025 | Source |
|-----------|--------|--------|
| Cash & equivalents | $7,736M | [File: balance.json — cashAndCashEquivalents] |
| Short-term investments | $528M | [File: balance.json — shortTermInvestments] |
| **Cash & STI** | **$8,264M** | [File: balance.json — cashAndShortTermInvestments] |

**Undrawn facility:** $2.5B revolving credit facility available. [File: claim_verification.json — Corroborated by Fitch and S&P Global]

**Credit rating:** BBB (Fitch, September 2024). [File: claim_verification.json — Corroborated by 2 sources]

### Minority Interest

$1,042M as of FY2025. [File: balance.json — minorityInterest]

### Enterprise Value

$155.0B at current price ($149.8B mkt cap + $13.5B debt − $8.3B cash & STI). [Inference: EV calculation from components] [File: quote.json — marketCap; balance.json — totalDebt, cashAndShortTermInvestments]

$176.1B at FY2025 year-end price of $81.71. [File: enterprise_value.json — enterpriseValue $176,120,022,630]

### Net Debt / EBITDA

0.82x as of FY2025 ($5.7B net debt / $7.0B EBITDA). [File: metrics.json — netDebtToEBITDA 0.8207; balance.json — netDebt $5,734M; income.json — ebitda $6,987M]

---

## Discrepancies & Data Gaps

### Cross-Reference Conflicts

1. **FY2025 total revenue:** Ecosystem_signals.md references "$51.6B" in one passage. The correct figure is $52,017M from income.json and the Uber FY2025 press release. [File: ecosystem_signals.md — "$51.6B"; income.json — $52,017M; claim_verification.json — Contradicted]
2. **Investopedia segment percentages:** An older Investopedia source cited "Delivery 33% / Mobility 53%" — inconsistent with the more granular FY2024 10-K figures of Mobility 57.04% and Delivery 31.27%. [File: claim_verification.json — Contradicted]
3. **US rideshare market share:** Estimates range from 55% (PESTEL Analysis — outlier, no methodology) to 76% (Second Measure transaction data). The preponderance of data-driven estimates cluster at 74-76%. The 55% and 37.2% (global) figures are unverifiable. [File: claim_verification.json — C065, Contradicted]
4. **Net debt computation:** balance.json reports a "netDebt" field of $5,734M (using cash & equivalents only, $7,736M). The compiler formula (totalDebt $13,470M − cashAndShortTermInvestments $8,264M) yields $5,206M. The $528M difference equals short-term investments. Both figures are factually correct under different definitions. [File: balance.json — netDebt vs totalDebt and cashAndShortTermInvestments]

### Data Gaps

1. **FY2025 segment revenue from primary sources** — relies on [Single-Source: bullfincher.io] [File: segment_financials.md]
2. **Q1 2026 segment-level revenue** — only GB growth rates available from transcript [File: transcript.json]
3. **Geographic revenue breakdown** — not available in workspace (segments.json 404) [File: segments.json]
4. **AV trip volume and revenue** — not disclosed; management references ">10x YoY" with no base [File: transcript.json]
5. **Advertising revenue actual** — projected >$1B in 2024 but unconfirmed [File: claim_verification.json — Single-Source: Mobisoft blog]
6. **Uber One revenue and contribution margin** — not disclosed [Data gap]
7. **Short interest shares** — FMP returned 404; only days-to-cover from [Single-Source: MarketBeat] [File: short_interest.json — 404; short_interest.md]
8. **Debt maturity schedule by year** — 10-K text not extracted [File: latest_10k.json]
9. **Driver payment breakdown within COGS** — prevents precise reclassification impact modeling [Data gap]
10. **Insurance expense absolute figure** — CFO said "hundreds of millions" in savings, no base disclosed [File: transcript.json — CFO Balaji]
11. **SoftBank position size and divestiture pace** — news.json references position reduction but position unquantified [File: news.json]
12. **Debt covenants** — 10-K text not available [File: latest_10k.json — limited extraction]

---

## Appendix

# Appendix A: Competitive Position — Uber Technologies (UBER)

## Market Share Detail

### US Rideshare (Mobility)

| Source | Uber Share | Date | Methodology | Confidence Tag |
|--------|-----------|------|-------------|----------------|
| Second Measure | 76% | Mar 2024 | Transaction data | [Contradicted: multiple sources, no primary filing] |
| Statista | 74% | Apr 2026 | Survey/aggregation | [Contradicted] |
| DemandSage | 74% | Dec 2025 | Aggregation | [Contradicted] |
| PESTEL Analysis | 55% | Dec 2025 | Unknown | [Contradicted: outlier, no primary source] |
| Matrix BCG blog | 76% | Mar 2026 | Cites mid-2025 data | [Single-Source] |

**Assessment:** Data-driven estimates cluster at 74-76%. The 55% figure is an outlier without identified primary methodology. No SEC filing or audited source confirms a specific share figure.

### Global Rideshare

37.2% global share cited by PESTEL Analysis — unverifiable, no methodology located. [claim_verification.json: Contradicted]

### US Food Delivery

Neither Uber nor DoorDash discloses US market share in filings. No reliable third-party market share data with primary methodology was located. [Data gap]

## TAM Analysis

| Market | Estimated TAM | Source | Confidence |
|--------|--------------|--------|------------|
| AV rideshare | $1T+ | CEO Dara (company estimate) | [transcript.json: no methodology disclosed] |
| Global grocery/retail | $1.5T | Matrix BCG blog citing Sacra research | [Single-Source] |
| North American freight | $800B+ | Mobisoft blog | [Single-Source: methodology unknown] |

Uber's current penetration: FY2025 GB ~$193.5B (annualized Q1 2026 ~$215B). Current revenue $52.0B. Penetration of any $1T+ TAM is low single-digit percent.

## Peer Financial Benchmarking

| Metric | UBER (FY2025) | Lyft (FY2025) | DoorDash (FY2025) | Instacart (FY2025) |
|--------|---------------|---------------|--------------------|---------------------|
| Revenue | $52.0B | $6.3B | $13.7B | $3.7B |
| Revenue Growth | +18.3% | +9% | +28% | +11% |
| GAAP Net Income | $10.1B* | $2.8B** | $935M | ~$457M [Contradicted] |
| Gross Bookings / GTV | ~$193.5B | $18.5B | ~$108B (ann.) | $37.2B |
| Gross Margin | 39.8% | 41.5% | 50.9% | 73.7% |
| Operating Margin | 10.7% | -3.0% | 5.3% | 13.3% |

*UBER FY2025 net income includes $5.0B tax valuation release. [claim_verification.json: Verified]
**Lyft FY2025 net income includes $2.9B tax valuation release. [ecosystem_signals.md: Verified]

[Sources: income.json (UBER); ecosystem_signals.md (Lyft, DoorDash, Instacart — all Verified unless noted)]

## Q1 2026 Competitive Metrics

| Metric | UBER | Lyft | DoorDash | Instacart |
|--------|------|------|----------|-----------|
| Revenue | $13.2B | $1.6B | $4.0B | $0.9B |
| Rev Growth | +14.5% | +14% | +33% | — |
| GB/GTV | $53.7B | $4.95B | $31.6B (GOV) | $10.29B |
| GB Growth | +25% | +19% | +37% (GOV) | +13% |
| Trips/Orders | 3.6B | — | 933M | — |

[Sources: earnings.json (UBER); ecosystem_signals.md (all peers, Verified)]

## Porter's Five Forces Summary

| Force | Assessment | Key Evidence |
|-------|-----------|--------------|
| Threat of new entrants | Low in rideshare, moderate in delivery | No new US rideshare entrant has achieved meaningful share since Lyft. Most recent delivery entry: DoorDash's Deliveroo acquisition (2025). 10M+ drivers, 50M+ Uber One members create density barriers. |
| Supplier bargaining power | Low (drivers fragmented) to moderate (AV partners strategic) | 10M+ independent drivers; multi-homing common. AV partners (Waymo, NVIDIA) have strategic leverage as AV technology is concentrated. |
| Buyer bargaining power | Moderate | Consumers price-elastic (insurance savings → trip growth). Uber One reduces price sensitivity for 50M+ members. No single customer material. |
| Threat of substitutes | Moderate | Personal cars, public transit, cooking at home, Waymo direct-to-consumer, AI agent intermediation. |
| Competitive rivalry | Moderate (rideshare duopoly) to high (delivery) | US rideshare: stable duopoly. Delivery: DoorDash growing 33% vs Uber ~25%. Freight: highly fragmented. |

## Competition Evolution (3-5 Year)

**2019-2021 — Consolidation:** Uber exited China (sold to DiDi), Southeast Asia (sold to Grab), Russia (merged with Yandex). Acquired Postmates and Transplace. Divested ATG to Aurora. Goodwill: $167M (FY2019) → $8,420M (FY2021). [balance.json]

**2022-2023 — Path to profitability:** Competitive landscape stabilized. First positive operating income ($1.1B, FY2023). US rideshare consolidated into stable duopoly (~75/25).

**2024-2026 — Platform expansion:** Expansion into grocery, retail, hotels, AV infrastructure. DoorDash's Deliveroo acquisition intensified European delivery competition. AV partnerships grew to 30+.

**Market structure trajectory:** US rideshare is an established duopoly. Delivery has 2-3 global players with competitive intensity remaining high. Freight is highly fragmented. The AV transition is the most significant structural change — whether AV will be platform-mediated or direct-to-consumer remains unresolved.

# Appendix B: Supply/Demand Analysis — Uber Technologies (UBER)

## Demand Decomposition

### Platform Demand Metrics

| Metric | Q1 2026 | Q4 2025 | Q1 2025 (implied) | Source |
|--------|---------|---------|---------------------|--------|
| Total Revenue | $13.203B | $14.366B | ~$11.53B | [earnings.json] |
| Total Gross Bookings | $53.7B | $54.1B (est.) | ~$42.9B | [claim_verification.json: Verified; Q4 est from Q4 2025 blended take rate] |
| Trips | 3.6B | — | 3.0B (implied) | [claim_verification.json: Corroborated; Q1 2025 implied from +20% YoY] |
| Audience Growth | +17% YoY | — | — | [transcript.json: CEO Dara] |
| Uber One Members | 50M+ | 46M | ~33M (implied) | [transcript.json; claim_verification.json: Q4 2025 46M Corroborated] |

### Demand by Segment (Q1 2026 GB Growth)

| Segment | GB Growth YoY | Driver | Source |
|---------|--------------|--------|--------|
| Mobility | +20% | Suburban expansion (2x urban), insurance-driven price reductions, airport travel | [transcript.json: CEO Dara] |
| Delivery | +23% | Grocery & retail led growth; 7 new European markets | [transcript.json: CEO Dara, CFO Balaji] |
| Freight | Returned to growth | Contract rate improvement (+5-6% ex-fuel); first growth in ~2 years | [transcript.json: CEO Dara; supply_demand.md] |

### Historical Revenue Trajectory

| Year | Revenue | YoY Growth | 3-Yr CAGR | Source |
|------|---------|------------|-----------|--------|
| FY2019 | $13.0B | — | — | [income.json] |
| FY2020 | $11.1B | −14.3% | — | [income.json] |
| FY2021 | $17.5B | +56.7% | — | [income.json] |
| FY2022 | $31.9B | +82.6% | 42.0% (FY2019-22) | [income.json] |
| FY2023 | $37.3B | +17.0% | — | [income.json] |
| FY2024 | $44.0B | +18.0% | — | [income.json] |
| FY2025 | $52.0B | +18.3% | 17.7% (FY2022-25) | [income.json] |

### Demand Durability Analysis

**Secular drivers:**
1. Urbanization and convenience demand — rideshare TAM expanding as trip growth in sparse/suburban markets is 2x faster than urban [transcript.json: CEO Dara]
2. Cross-platform compounding — Uber One membership growth (50% YoY) drives frequency across Mobility and Delivery; $15B annualized Delivery GB from Mobility app [transcript.json: CFO Balaji]
3. New verticals — hotel bookings (Expedia, 700K+ properties), advertising, AV platform services [transcript.json: CEO Dara]

**Cyclical risks:**
1. COVID impact: FY2020 revenue −14.3%. Recovery to pre-COVID levels within 1 year. [income.json]
2. Consumer discretionary exposure: rideshare and food delivery are discretionary; macro downturn would reduce spending
3. Freight cyclicality: 2-year downturn (Q2 2023 - Q4 2025); only recovered in Q1 2026

**Consensus estimates:**

| Year | Revenue Est. | YoY Growth | # Analysts | Source |
|------|-------------|------------|------------|--------|
| FY2026E | $58.2B | +11.8% | 38 | [ratings.json] |
| FY2027E | $67.0B | +15.2% | 37 | [ratings.json] |
| FY2028E | $75.9B | +13.3% | 28 | [ratings.json] |
| FY2030E | $90.8B | — | 27 | [ratings.json] |

## Supply Analysis

### Driver/Courier Supply

- 10M+ active drivers and couriers globally [transcript.json: CEO Dara]
- No evidence of structural driver shortage in any market
- Driver supply is responsive to demand — in AV markets, "driver earnings are up, more drivers are joining" [transcript.json: CEO Dara]
- Uber's capex is minimal ($336M or 0.6% of revenue in FY2025) because drivers own vehicles [cashflow.json]

### AV Supply (Primary Constraint)

- 30+ AV partners [transcript.json: CEO Dara]
- AV Mobility trips >10x YoY from undisclosed base [transcript.json: CEO Dara]
- NVIDIA partnership targeting 100,000 AVs globally by 2027 [claim_verification.json: Corroborated by 5+ sources]
- Nuro/Lucid: multi-hundred-million dollar investments; 20,000+ Level 4 Lucid Gravity robotaxis starting 2026 [claim_verification.json: Corroborated, Uber IR Jul 2025]
- CEO Dara: "the blockers are — we just need more cars on the road" and regulatory approvals
- Uber Autonomous Solutions: fleet management, depot/charging, data, financing (Santander), insurance (Marsh/Apollo)

### Restaurant/Merchant Supply

- No constraint identified
- Actively expanding selection in suburban markets
- Launched in Finland during Q1 2026 call, achieved #1 App Store position immediately [transcript.json: CFO Balaji]
- 7 new European Delivery markets announced [transcript.json: CFO Balaji]

### Freight Supply

- Contract rates: +5-6% YoY ex-fuel, expected to climb further [Single-Source: uberfreight.com, Apr 30, 2026]
- Lead times: average 4-5 days, as low as 3 hours [claim_verification.json: Verified from Uber engineering blog]

## Supply/Demand Synthesis

| Segment | Balance | Evidence | Pricing Impact |
|---------|---------|----------|----------------|
| Mobility | Demand-expansionary | Trips +20% YoY; expanding into suburban markets; no driver constraint | Take rate 29.9%; Uber passing insurance savings to consumers to drive volume |
| Delivery | Demand-expansionary | GB +23% YoY; grocery/retail leading growth; 7 new markets | Take rate 19.2%; advertising revenue layered on top |
| AV | Supply-constrained | Trips >10x YoY but from small base; limited by vehicle availability and regulation | N/A — pre-meaningful-revenue |
| Freight | Recovering | First growth in ~2 years; contract rates rising | Improving spot/contract rate environment |

## Depth-First Research Summary

**Asked and answered:**
- Q: How does Lyft's growth compare? → Both accelerating; Uber Mobility +20% YoY vs Lyft +19% YoY in Q1 2026 [ecosystem_signals.md: Verified]
- Q: Is DoorDash gaining delivery share? → DoorDash growing 33% vs Uber's ~25% delivery growth. Deliveroo adds European scale. [ecosystem_signals.md: Verified]
- Q: What are AV deployment timelines? → 15 markets by year-end 2026; NVIDIA 100K target by 2027 [transcript.json; claim_verification.json]

**Asked but unanswerable:**
- Q: What is Uber's market share in specific European markets? → Geographic segment data unavailable
- Q: How many AV trips per day/month? → Absolute figures not disclosed
- Q: What is the insurance cost savings dollar amount? → "Hundreds of millions" with no specific figure

# Appendix C: Value Chain — Uber Technologies (UBER)

## Value Chain Maps

**Mobility:**
```
Consumer demand → Uber App (matching/pricing/routing) → Driver supply → Vehicle operation → Trip fulfillment → Payment → Settlement
```

**Delivery:**
```
Consumer demand → Uber Eats App (discovery/ordering) → Restaurant preparation → Courier matching → Delivery → Payment → Settlement
```

**Freight:**
```
Shipper demand → Uber Freight Platform (pricing/matching) → Carrier matching → Hauling → Delivery → Payment → Settlement
```

## Upstream: Supplier Detail

### 1. Drivers & Couriers (Primary Supply)
- 10M+ globally [transcript.json: CEO Dara]
- Provide own vehicles, fuel, insurance, maintenance
- **Switching costs:** Low. Multi-homing across Uber, Lyft, DoorDash common
- **Economics:** Receive ~70% of Mobility fare value (at 29.9% take rate) and ~81% of Delivery value (at 19.2% take rate) [claim_verification.json: Corroborated]

### 2. AV Partners (Emerging)
- 30+ partners: Waymo, Baidu Apollo Go, Pony.ai, NVIDIA, Nuro, Lucid, Zoox, Hertz, Santander
- [claim_verification.json: Baidu Verified via PRNewswire; Pony.ai Verified; NVIDIA 100K target Corroborated; Nuro/Lucid Corroborated via Uber IR Jul 2025]
- AV supply currently immaterial. Trips >10x YoY from undisclosed base
- Uber Autonomous Solutions: fleet management, data collection, financing (Santander), insurance (Marsh/Apollo) [transcript.json: CEO Dara]

### 3. Restaurants & Merchants
- Extensive, fragmented merchant network across 70+ countries
- Low-to-moderate switching costs (restaurants list on multiple platforms)
- Uber's counter-leverage: $15B annualized Delivery GB from Mobility app — a demand channel competitors lack [transcript.json: CFO Balaji]

### 4. Insurance Providers
- Auto insurance is a material cost in Mobility COGS
- FY2026 savings: "hundreds of millions of dollars" from policy improvements, technology, and favorable renewal conditions [transcript.json: CFO Balaji]
- Uber offloading "more risk to third-party carriers" [transcript.json: CFO Balaji]
- AV insurance: partnership with Marsh/Apollo. "AV insurance is going to be cheaper than human insurance because AVs ultimately will be safer" [transcript.json: CEO Dara]

### 5. Technology/Cloud Infrastructure
- Uber operates own large-scale data platform
- ~10% of code committed by autonomous AI agents [transcript.json: CEO Dara]
- Specific cloud providers and costs: [Data gap]

### 6. Carriers (Freight)
- Independent trucking carriers; highly fragmented market
- Contract rates +5-6% YoY ex-fuel [Single-Source: uberfreight.com, Apr 2026]

## Downstream: Customer Detail

- **Consumer marketplace model:** No single customer represents >10% of revenue. Revenue from millions of individual consumers. [info.json; business_profile.md]
- **Uber One:** 50M+ members, >50% of bookings, 3x spend, growing 50% YoY [transcript.json: CEO Dara]
- **Cross-platform:** 30% of eligible Mobility consumers never used Uber Eats [transcript.json: CFO Balaji]
- **Contract structures:** Mobility/Delivery on-demand per-transaction. Freight: mix of contracted and spot market rates.

## Take Rate Analysis

| Segment | Q4 2025 Take Rate | FY2025 Implied | Source |
|---------|-------------------|----------------|--------|
| Mobility | 29.9% | — | [claim_verification.json: Corroborated] |
| Delivery | 19.2% | — | [claim_verification.json: Corroborated] |
| Freight | ~10% (est.) | — | [Inference: industry digital brokerage margins; Unverifiable from available data] |
| **Blended** | — | **26.9%** | [Inference: $52.0B / $193.5B] [Sources: income.json, claim_verification.json] |

Q1 2026 blended take rate: 24.6% ($13.2B / $53.7B). Lower than FY2025 blended, reflecting seasonal mix shift toward Delivery and potential Mobility price reinvestment. [Inference: arithmetic] [Sources: earnings.json, claim_verification.json]

## Vertical Integration Assessment

| Stage | Integration Level | Evidence | 3-Year Change |
|-------|------------------|----------|---------------|
| Demand aggregation | In-house | Uber app, Uber One (50M+), proprietary algorithms | Expanding (Uber One 30M→50M; hotels added) |
| Matching/pricing | In-house | Core IP; AI/ML models | Stable (deepening AI) |
| Vehicle fleet (Mobility) | Outsourced | Drivers own vehicles | Stable |
| AV fleet operations | Partial (new) | Uber Autonomous Solutions; Hertz, Santander partnerships | Integrating |
| Food preparation | Outsourced | Restaurants/merchants prepare food | Stable |
| Last-mile delivery | Outsourced | Independent couriers | Stable |
| Freight hauling | Outsourced | Independent carriers | Stable |
| Insurance | Partial | Third-party policies; building AV insurance with Marsh/Apollo | Shifting |
| Payment processing | In-house | Processes all payments | Stable |
| Advertising | In-house | Built in-house across Mobility and Delivery | Expanding |
| Travel/hotel | Outsourced (new) | Expedia inventory, 700K properties | New (Apr 2026) |

## Margin Migration (3-Year Gross Margin)

| Company | FY2023 | FY2024 | FY2025 | Direction |
|---------|--------|--------|--------|-----------|
| UBER | 39.8% | 39.4% | 39.8% | Stable |
| LYFT | 42.2% | 42.3% | 41.5% | Stable to slight compression |
| DASH | 46.9% | 48.3% | 50.9% | Expanding |
| CART | 74.9% | 75.3% | 73.7% | Stable to slight compression |
| XPO | 9.9% | 11.3% | 12.0% | Expanding |

[Sources: income.json for UBER; FMP income statements for peers]

Operating margin is concentrating at the largest multi-category platform (UBER, 10.7%) and the specialized grocery platform (CART, 13.3%). Single-segment platforms (LYFT, DASH) operate at lower or negative operating margins.

# Appendix D: Capital Structure — Uber Technologies (UBER)

## Equity Composition

| Component | Value | Source |
|-----------|-------|--------|
| Share class | Common stock, single class | [info.json] |
| Preferred stock outstanding | $0 | [balance.json: preferredStock] |
| Common stock outstanding | 2,036M (Q1 2026 10-Q) | [shares_float.json: outstandingShares] |
| Diluted shares (FY2025) | 2,120M | [income.json: weightedAverageShsOutDil] |
| Float shares | 2,024M (99.4% free float) | [shares_float.json: floatShares, freeFloat] |
| Additional paid-in capital | $38,101M | [balance.json: additionalPaidInCapital] |
| Retained earnings (deficit) | −$10,628M | [balance.json: retainedEarnings] |
| AOCI | −$432M | [balance.json: accumulatedOtherComprehensiveIncomeLoss] |
| Total stockholders' equity | $27,041M | [balance.json: totalStockholdersEquity] |
| Total equity (incl. minority) | $28,083M | [balance.json: totalEquity] |

## Market Cap

$149,841M at $73.61/share as of 2026-05-21. [quote.json: marketCap]

## Debt Composition

### Summary

| Component | FY2025 | FY2024 | FY2023 | FY2022 | Source |
|-----------|--------|--------|--------|--------|--------|
| Short-term debt | $169M | $1,460M | $500M* | — | [balance.json: shortTermDebt] |
| Long-term debt | $11,911M | $8,349M | $9,459M | — | [balance.json: longTermDebt] |
| Capital lease obligations | $1,390M | $1,627M | $1,871M | — | [balance.json: capitalLeaseObligations] |
| **Total debt** | **$13,470M** | **$11,436M** | **$11,830M** | **$11,717M** | [balance.json: totalDebt] |

*FY2023 short-term debt approximated from total debt less long-term debt less capital lease obligations.

### Debt Trajectory

Total debt has been relatively stable in the $11.4-13.5B range from FY2021-FY2025. The FY2025 increase of $2,034M reflects primarily the $1.0B Aurora Exchangeable Notes issued May 2025, net of the December 2025 convertible maturity. [Inference: timing of issuances and maturities] [Sources: balance.json, claim_verification.json]

## Convertible/Exchangeable Securities

### Active Notes

| Issue | Coupon | Maturity | Principal | Conversion Price | Status | Source |
|-------|--------|----------|-----------|-----------------|--------|--------|
| Convertible Senior Notes | 0.875% | Dec 1, 2028 | $1,500M | ~$72.54/share | In-the-money at $73.61; ~20.7M potential diluted shares | [claim_verification.json: Verified via Uber IR and SEC 8-K, Nov 2023] |
| Aurora Exchangeable Notes | 0% | May 15, 2028 | $1,000M | Exchangeable for AUR Class A stock | Redeemable for cash after May 21, 2027 if AUR ≥130% of exchange price | [claim_verification.json: Verified via SEC 8-K, May 2025] |

### Matured Notes

| Issue | Coupon | Maturity | Principal | Source |
|-------|--------|----------|-----------|--------|
| Convertible Senior Notes | 0% | Dec 15, 2025 | $1,000-1,150M | [claim_verification.json: Verified via SEC indenture, Dec 2020] |

**Total outstanding convertible/exchangeable:** ~$2,500M

## Debt Maturity Profile

**Data gap:** Specific debt maturity schedule by year is not available. The FY2025 10-K (accession 0001543151-26-000015) was not fully extracted — latest_10k.json contains XBRL cover page only. Known maturities:

| Year | Known Maturity | Amount |
|------|---------------|--------|
| 2028 | Convertible notes (Dec 1) | $1,500M |
| 2028 | Aurora exchangeable (May 15) | $1,000M |

Remaining $9,970M in debt ($13,470M total − $2,500M convertibles) maturity schedule: [Data gap].

## Cash and Equivalents

| Component | FY2025 | FY2024 | FY2023 | Source |
|-----------|--------|--------|--------|--------|
| Cash & equivalents | $7,736M | $6,438M | $5,485M | [balance.json: cashAndCashEquivalents] |
| Short-term investments | $528M | $1,084M | $727M | [balance.json: shortTermInvestments] |
| **Cash & STI** | **$8,264M** | **$7,522M** | **$6,212M** | [balance.json: cashAndShortTermInvestments] |
| Long-term investments | $9,178M | $5,547M | $4,822M | [balance.json: longTermInvestments] |

Long-term investments increased $3.6B in FY2025, likely reflecting the Delivery Hero stake increase and other strategic investments. [Inference: timing correlation] [Sources: balance.json, news.json]

**Undrawn credit facility:** $2.5B secured revolving credit facility available. [claim_verification.json: Corroborated by 3 sources including Fitch and S&P Global]

**Credit rating:** BBB (Fitch, September 2024). [claim_verification.json: Corroborated by 2 sources]

## Minority Interest

$1,042M as of FY2025 (FY2024: $768M; FY2023: $514M). Minority interest has been growing, likely related to consolidated entities where Uber holds majority but not 100% ownership. [balance.json: minorityInterest]

## Enterprise Value

| Method | Value | Source |
|--------|-------|--------|
| At current price ($73.61) | $155,047M | [Inference: $149,841M mkt cap + $13,470M debt − $8,264M cash & STI] [Sources: quote.json, balance.json] |
| At FY2025 year-end price ($81.71) | $176,120M | [enterprise_value.json: enterpriseValue] |

## Net Debt / EBITDA

| Year | Net Debt | EBITDA | Net Debt/EBITDA | Source |
|------|----------|--------|-----------------|--------|
| FY2025 | $5,734M | $6,987M | 0.82x | [metrics.json: netDebtToEBITDA] |
| FY2024 | $4,998M | $5,385M | 0.93x | [metrics.json] |
| FY2023 | $6,345M | $3,769M | 1.68x | [metrics.json] |

Note: metrics.json netDebt uses cashAndCashEquivalents ($7,736M), not cashAndShortTermInvestments ($8,264M). Using the broader definition: Net Debt = $5,206M, yielding Net Debt/EBITDA of 0.75x. Both definitions are valid.

## Capital Allocation (FY2025)

| Item | Amount | Source |
|------|--------|--------|
| Operating cash flow | $10,099M | [cashflow.json] |
| CapEx | −$336M | [cashflow.json] |
| **Free cash flow** | **$9,763M** | [cashflow.json] |
| Net debt issuance | $852M | [cashflow.json] |
| Share repurchases | −$6,523M | [cashflow.json] |
| Acquisitions | −$120M | [cashflow.json] |
| Dividends | $0 | [cashflow.json] |

Q1 2026: $3.0B in share repurchases — described as "record." [transcript.json: CEO Dara]

# Appendix E: Key Stats — Uber Technologies (UBER)

## Price & Trading

| Metric | Value | Computation | Source |
|--------|-------|-------------|--------|
| Price | $73.61 | — | [quote.json: price] |
| 52-week range | $68.46 – $101.99 | — | [quote.json: yearLow, yearHigh] |
| Price vs 52-week high | −27.8% | ($73.61 − $101.99) / $101.99 | [quote.json] |
| ADV (30d, $MM) | $1,251MM | 16,987,812 avg vol × $73.61 | [info.json: averageVolume × price] |
| ADV (30d, shares) | 17.21M | — | [technicals.json: avg_volume_30d] |
| RSI (14-day) | 45.5 | — | [technicals.json: rsi_14] |
| 21d EMA | $74.88 | — | [technicals.json: ema_21d] |
| 50d SMA | $74.24 | — | [technicals.json: sma_50d] |
| 200d SMA | $84.18 | — | [technicals.json: sma_200d] |
| Beta | 1.158 | — | [info.json: beta] |
| Historical volatility (ann.) | 33.9% | 173 observations | [options.json: historical_volatility] |

## Valuation Multiples (Computed at Current Price $73.61)

| Multiple | Value | Computation | Source |
|----------|-------|-------------|--------|
| Trailing P/E (reported) | 15.6x | $73.61 / $4.73 diluted EPS | [quote.json, income.json] |
| Trailing P/E (normalized) | 34.4x | $73.61 / $2.14 norm. EPS | [Inference: pretax $5,747M × 0.79 / 2,120M diluted shares = $2.14] [Sources: income.json] |
| Forward P/E (FY2026E) | 22.2x | $73.61 / $3.32 consensus EPS | [quote.json, ratings.json] |
| P/FCF | 15.3x | $149,841M / $9,763M | [quote.json, cashflow.json] |
| P/FCF ex-SBC | 18.9x | $149,841M / ($9,763M − $1,826M) | [quote.json, cashflow.json] |
| EV/Revenue | 2.98x | $155,047M / $52,017M | [Inference: current EV / FY2025 rev] [Sources: quote.json, balance.json, income.json] |
| EV/EBITDA | 22.2x | $155,047M / $6,987M | [Inference: current EV / FY2025 EBITDA] [Sources: quote.json, balance.json, income.json] |
| EV/EBIT | 24.8x | $155,047M / $6,240M | [Inference: current EV / FY2025 EBIT] [Sources: quote.json, balance.json, income.json] |
| P/B | 5.5x | $149,841M / $27,041M | [quote.json, balance.json: totalStockholdersEquity] |
| Dividend yield | 0% | No dividends | [dividends.json] |

**Note on trailing P/E:** The 15.6x trailing P/E is misleadingly low because FY2025 net income of $10,053M includes a $5.0B tax valuation allowance release. At a normalized 21% tax rate, EPS would be ~$2.14, producing a normalized P/E of 34.4x. The forward P/E of 22.2x (consensus FY2026 EPS of $3.32) is a more representative multiple because analysts exclude one-time tax benefits. [claim_verification.json: Verified — $5.0B tax benefit confirmed by Uber FY2025 press release]

## Share Count & Float

| Metric | Value | Source |
|--------|-------|--------|
| Shares outstanding | 2,036M | [shares_float.json: outstandingShares] |
| Float shares | 2,024M | [shares_float.json: floatShares] |
| Free float % | 99.4% | [shares_float.json: freeFloat] |
| Diluted shares (FY2025) | 2,120M | [income.json: weightedAverageShsOutDil] |
| Short interest | ~3.8 days to cover | [Single-Source: MarketBeat via short_interest.md] |
| Shares short | N/A | [Data gap: short_interest.json returned 404] |

## Profitability

| Metric | FY2025 | FY2024 | FY2023 | FY2022 | Source |
|--------|--------|--------|--------|--------|--------|
| Revenue | $52,017M | $43,978M | $37,281M | $31,877M | [income.json] |
| Gross profit | $20,679M | $17,327M | $14,831M | $12,217M | [income.json] |
| Operating income | $5,565M | $2,799M | $1,108M | −$1,832M | [income.json] |
| EBITDA | $6,987M | $5,385M | $3,769M | −$7,906M | [income.json] |
| Net income | $10,053M | $9,856M | $1,887M | −$9,141M | [income.json] |
| EPS (diluted) | $4.73 | $4.56 | $0.87 | −$4.65 | [income.json] |
| Gross margin | 39.8% | 39.4% | 39.8% | 38.3% | [ratios.json] |
| Operating margin | 10.7% | 6.4% | 3.0% | −5.7% | [Inference: op inc / rev] [Sources: income.json] |
| EBITDA margin | 13.4% | 12.2% | 10.1% | −24.8% | [ratios.json] |
| Net margin | 19.3%* | 22.4%* | 5.1% | −28.7% | [ratios.json] |

*FY2025 and FY2024 net margins inflated by deferred tax benefits of $4.35B and $5.76B respectively.

## Cash Flow

| Metric | FY2025 | FY2024 | FY2023 | FY2022 | Source |
|--------|--------|--------|--------|--------|--------|
| Operating CF | $10,099M | $7,137M | $3,585M | $642M | [cashflow.json] |
| CapEx | −$336M | −$242M | −$223M | −$252M | [cashflow.json] |
| FCF | $9,763M | $6,895M | $3,362M | $390M | [cashflow.json] |
| SBC | $1,826M | $1,796M | $1,935M | $1,793M | [cashflow.json] |
| FCF ex-SBC | $7,937M | $5,099M | $1,427M | −$1,403M | [cashflow.json] |
| FCF margin | 18.8% | 15.7% | 9.0% | 1.2% | [Inference: FCF / rev] |
| CapEx/Revenue | 0.65% | 0.55% | 0.60% | 0.79% | [Inference] |
| Buybacks | −$6,523M | −$1,248M | $0 | $0 | [cashflow.json] |

## Returns on Capital

| Metric | FY2025 | FY2024 | FY2023 | Source |
|--------|--------|--------|--------|--------|
| ROIC | 11.2% | 6.8% | 3.4% | [metrics.json: returnOnInvestedCapital] |
| ROE | 37.2% | 48.3%* | 8.0% | [metrics.json: returnOnEquity] |
| ROA | 16.3% | 17.1%* | 3.5% | [metrics.json: returnOnAssets] |
| Invested capital | $14,663M | $13,073M | $14,732M | [metrics.json: investedCapital] |

*FY2024 and FY2025 ROE/ROA inflated by one-time tax benefits.

**WACC estimate:** 9.65% [Inference: 10.3% cost of equity (CAPM: 4.5% Rf + 1.158β × 5.0% ERP) × 91.8% equity weight + 2.6% after-tax cost of debt (($440M int / $13,470M debt) × 0.79) × 8.2% debt weight] [Sources: info.json, income.json, balance.json, quote.json]

## Credit Quality

| Metric | Value | Source |
|--------|-------|--------|
| Altman Z-Score | 3.65 | [scores.json: altmanZScore] |
| Piotroski Score | 7/9 | [scores.json: piotroskiScore] |
| Net Debt/EBITDA | 0.82x | [metrics.json: netDebtToEBITDA] |
| Interest coverage (EBIT/Int) | 14.2x | [Inference: $6,240M / $440M] [Sources: income.json] |
| Interest coverage (EBITDA/Int) | 15.9x | [Inference: $6,987M / $440M] [Sources: income.json] |
| Current ratio | 1.14x | [ratios.json: currentRatio] |
| Credit rating | BBB (Fitch, Sep 2024) | [claim_verification.json: Corroborated] |

## Greenwald Value Decomposition

| Component | Value | Per Share | Source |
|-----------|-------|-----------|--------|
| Total assets | $61,802M | — | [balance.json] |
| Less: Goodwill | −$8,931M | — | [balance.json] |
| Less: Intangibles | −$1,048M | — | [balance.json] |
| = Tangible assets | $51,823M | — | — |
| Less: Total liabilities | −$33,719M | — | [balance.json] |
| = **Tangible book value** | **$18,104M** | **$8.54** | [Inference: TBV / 2,120M diluted shares] |
| | | | |
| FY2025 Operating income | $5,565M | — | [income.json] |
| NOPAT (at 21% tax) | $4,396M | — | [Inference: $5,565M × 0.79] |
| Capitalized at 9.65% WACC | $45,554M | $21.49 | [Inference: EPV = NOPAT / WACC] |
| = **Earnings power value** | **$45,554M** | **$21.49** | — |
| | | | |
| Market cap | $149,841M | $73.61 | [quote.json] |
| Less: EPV | −$45,554M | — | — |
| = **Franchise value** | **$104,287M** | **$49.20** | — |
| Franchise as % of mkt cap | 69.6% | — | — |

69.6% of current market value represents growth/franchise expectations beyond the no-growth earnings stream. Sources of franchise value: two-sided network effects across 70+ countries, cross-platform flywheel with 50M+ Uber One members, brand and regulatory licenses, switching costs from user habit formation.

## Earnings Consistency

| Quarter | EPS Actual | EPS Est | Beat/Miss | Rev Actual | Rev Est | Beat/Miss |
|---------|-----------|---------|-----------|-----------|---------|-----------|
| Q1 2024 | −$0.32 | $0.220 | −$0.540 MISS | $10,131M | $10,095M | +$36M BEAT |
| Q2 2024 | $0.47 | $0.310 | +$0.160 BEAT | $10,700M | $10,568M | +$132M BEAT |
| Q3 2024 | $1.20 | $0.410 | +$0.790 BEAT | $11,188M | $10,994M | +$194M BEAT |
| Q4 2024 | $3.21 | $0.500 | +$2.710 BEAT | $11,959M | $11,756M | +$203M BEAT |
| Q1 2025 | $0.83 | $0.508 | +$0.322 BEAT | $11,533M | $11,631M | −$98M MISS |
| Q2 2025 | $0.63 | $0.629 | +$0.001 BEAT | $12,651M | $12,471M | +$180M BEAT |
| Q3 2025 | $3.11 | $0.690 | +$2.420 BEAT | $13,467M | $13,284M | +$183M BEAT |
| Q4 2025 | $0.14 | $0.787 | −$0.647 MISS | $14,366M | $14,323M | +$43M BEAT |
| Q1 2026 | $0.72 | $0.693 | +$0.027 BEAT | $13,203M | $13,280M | −$77M MISS |

[earnings.json: all quarters]

EPS: 7 beats in 9 quarters (78%). Revenue: 7 beats in 9 quarters (78%). EPS variance is extreme (−$0.32 to $3.21 within FY2024) due to non-operating items (equity investment gains/losses, tax benefit timing).

# Appendix F: Risk Factors — Uber Technologies (UBER)

## 1. Customer Concentration

**No individual customer concentration.** Uber operates a consumer marketplace with millions of individual riders, eaters, and shippers. No single customer approaches the 10% SEC disclosure threshold. [info.json: description; business_profile.md]

**Platform dependency concentration:** Uber One members (50M+) account for >50% of gross bookings and spend 3x more. A disruption to Uber One's value proposition could disproportionately affect revenue. [transcript.json: CEO Dara]

**Data gap:** Uber One revenue and contribution margin are not separately disclosed.

## 2. Cyclicality and Macro Sensitivity

| Year | Revenue | YoY Change | Context |
|------|---------|------------|---------|
| 2019 | $13.0B | +24.6% | Pre-COVID |
| 2020 | $11.1B | −14.3% | COVID — rideshare collapsed; Delivery partially offset |
| 2021 | $17.5B | +56.7% | Recovery |
| 2022 | $31.9B | +82.6% | Full recovery + Delivery scale |
| 2023 | $37.3B | +17.0% | Normalization |
| 2024 | $44.0B | +18.0% | Steady growth |
| 2025 | $52.0B | +18.3% | Continued expansion |
[income.json: revenue]

COVID (2020) produced a 14.3% revenue decline. Diversification into three segments (Mobility, Delivery, Freight) provides partial offset: Delivery benefits when consumers stay home; Mobility benefits when they go out. Freight is cyclical and was depressed for ~2 years.

## 3. Technology and Disruption Risk

### 3a. Autonomous Vehicles

**Platform position:** 30+ AV partners, AV trips >10x YoY, targeting 15 markets by year-end 2026. Uber Autonomous Solutions launched for fleet management, financing, insurance. [transcript.json: CEO Dara]

**Disintermediation risk:** Waymo operates its own consumer app. If AV companies build sufficient demand aggregation independently, they could bypass Uber's marketplace. CEO Dara states category position in SF/LA is "higher today than 6 months ago" despite Waymo. [transcript.json]

**Investment risk:** Multi-hundred-million dollar commitments in Nuro and Lucid. If AV timelines slip, these could generate losses. [claim_verification.json: Corroborated via Uber IR]

**AV revenue: undisclosed.** Cannot size the AV business. [Data gap]

### 3b. AI Agent Intermediation

Personal AI agents could abstract away the Uber app. CEO Dara's response: Uber can "dictate the terms of trade" with third-party agents, drawing analogy to travel metasearch. [transcript.json: CEO Dara, response to analyst Michael Morton (MoffettNathanson)]

Quantification is not possible — risk is structural and long-term.

## 4. Regulatory and Geopolitical Risk

### 4a. Driver Classification

Uber's model depends on drivers being independent contractors. Reclassification would add employer taxes, benefits, overtime. 10M+ earners vs 31,100 employees — a 322:1 ratio illustrating model leverage and vulnerability. [info.json; transcript.json]

Key jurisdictions: California (Prop 22), EU Platform Workers Directive (2024, implementation ongoing), UK Supreme Court (2021 ruling).

**Data gap:** Driver payment breakdown within COGS ($31.3B) is not disclosed. Cannot model precise reclassification cost impact.

### 4b. Geographic Exposure

70+ countries [transcript.json: CEO Dara]. Geographic revenue breakdown **not available** [segments.json: 404]. Cannot quantify regional concentration risk.

Known recent geographic activity: Finland expansion (Q1 2026), 7 new European Delivery markets, India (2 new campuses), South Korea (Baemin bid ~$5.34B). [transcript.json; news.json]

### 4c. Baemin Acquisition Risk

The ~$5.34B bid for South Korea's largest food delivery platform represents ~3.6% of current market cap. Integration risk in a new market applies. [news.json: Reuters, May 18, 2026]

### 4d. Delivery Hero Stake

Uber raised stake in Delivery Hero to 19.5% of issued capital. Strategic investment in a European delivery competitor facing intense competition from DoorDash (post-Deliveroo) and Prosus. [news.json: Reuters; transcript.json: CFO Balaji]

## 5. Competitive Risk

### DoorDash (Delivery)

DoorDash is growing faster across all reported metrics: revenue +33% vs Uber's consolidated +14.5% (Q1 2026), GOV +37% vs Uber's total GB +25%. Deliveroo acquisition (mid-2025) adds European scale directly competing with Uber Eats. 56M+ MAUs. [ecosystem_signals.md: Verified]

### Lyft (Rideshare)

Lyft Q1 2026 GB +19% YoY vs Uber Mobility +20%. Revenue growth converging at ~14% for both. US rideshare share gap appears stable at ~75/25. [ecosystem_signals.md: Verified]

### Instacart (Grocery)

Building enterprise grocery technology (Storefront, Caper smart carts) that could create retailer lock-in limiting Uber's grocery expansion. [ecosystem_signals.md: Verified]

## 6. Financial Risk

### Earnings Quality — Tax Benefit Distortion

| Year | Effective Tax Rate | GAAP NI | Normalized NI (21% rate) | Inflation Factor |
|------|-------------------|---------|--------------------------|------------------|
| FY2025 | −75.6% | $10,053M | $4,540M | 2.2x | 
| FY2024 | −140.9% | $9,856M | $3,229M | 3.1x |
| FY2023 | 9.0% | $1,887M | $1,872M | 1.0x |
[income.json: incomeTaxExpense, incomeBeforeTax]

**Trailing P/E at reported EPS:** 15.6x. **At normalized EPS:** 34.4x. The 15.6x multiple on reported earnings understates the true earnings multiple by more than half.

Deferred tax asset: $10,951M (FY2025), up from $6,172M (FY2024) and $170M (FY2023). This reflects recognition of previously unvalued NOL carryforwards. [balance.json: taxAssets]

### Convertible Dilution

$1.5B convertible notes (due Dec 2028) have conversion price ~$72.54, in-the-money at current $73.61. Potential dilution: ~20.7M shares (1.0% of outstanding). [claim_verification.json: Verified]

### SBC Dilution

SBC/Revenue declined from 6.7% (FY2021) to 3.5% (FY2025). FY2025 diluted shares declined 1.4% — first reduction in company history — driven by $6.5B in buybacks exceeding new issuance. Q1 2026 buybacks: $3.0B (record quarter). [cashflow.json; transcript.json]

### SoftBank Divestiture

"SoftBank Dumps Uber Stock" — news headline. Volume, timing, and remaining position unquantified. [news.json: Barchart.com]

## 7. Insider Activity

Only routine RSU vesting transactions (M-Exempt) and tax withholding (F-InKind) for CFO Krishnamurthy and officer Macdonald in May 2026. No open-market sales (S-Sale). Total tax withholding: ~$217K combined. [insider.json]

## 8. Notable Non-Disclosures (Silence Analysis)

1. **Segment-level margins (FY2025):** Uber does not disclose segment-level operating income or Adjusted EBITDA breakdown for FY2025. FY2024 Mobility Adjusted EBITDA ($6.5B) was disclosed by Investopedia citing Uber financials. [Data gap]
2. **Geographic revenue:** Not disclosed in available files, despite operating in 70+ countries. Peers Lyft and DoorDash also have limited geographic disclosure.
3. **AV trip volume and revenue:** Management references ">10x YoY" growth without disclosing absolute numbers.
4. **Advertising revenue:** Projected >$1B but actual not confirmed. [Single-Source: Mobisoft blog]
5. **Insurance expense baseline:** CFO says "hundreds of millions" in savings without disclosing the prior-year insurance cost base.
6. **Uber One revenue:** Only member count and growth rate disclosed; revenue, retention rate, and contribution margin undisclosed.
7. **Management non-answer on specific AV revenue timing:** Analyst questions about AV economics received qualitative responses about partnerships and markets, not financial metrics.

# Appendix G: Transcript Highlights — Uber Technologies (UBER)

**Source:** Q1 2026 earnings call, May 6, 2026. [transcript.json]

## Business Performance

**CEO Dara Khosrowshahi:**
- "Gross bookings were up 21% year-on-year on a constant currency basis and 25% on a reported basis to $53.7 billion"
- "We completed 3.6 billion trips in Q1, up 20% year-on-year"
- "Mobility gross bookings accelerated to 20%"
- "Delivery grew 23%, led by grocery and retail"
- "Freight returned to growth for the first time in nearly 2 years"
- "Adjusted EBITDA was $2.5 billion, up 33% year-on-year"
- "We returned $3 billion to shareholders through buybacks this quarter, a record"

## Uber One & Consumer Engagement

**CEO Dara:**
- "We surpassed 50 million Uber One members in Q1. That's up 50% year-on-year"
- "They spend 3x more and importantly, they churn much less"
- "Uber One now accounts for over 50% of our total gross bookings"
- "About 40% of US riders take trips outside their home city. Over 1.5 billion trips occurred outside users' home cities globally just in 2025"

**CFO Balaji Krishnamurthy:**
- "Nearly $15 billion of run rate gross bookings for our Delivery business coming from our Mobility app"
- "30% of our eligible Mobility consumers have never even used Uber Eats yet"

## Autonomous Vehicles

**CEO Dara:**
- "We have more than 30 autonomous partners across Mobility and Delivery"
- "AV Mobility trips grew more than 10x year-on-year"
- "We're on track to have AVs in 15 markets by the end of this year"
- "The blockers are — we just need more cars on the road"
- "We don't see any effect of the Waymo launches on our overall business"
- "Our category position, both in San Francisco and L.A. is higher today than it was 6 months ago"
- "Another $1 trillion TAM" (referring to AV addressable market)
- Re: Uber Autonomous Solutions: "We're investing in that entire ecosystem — fleet management, depot and charging infrastructure, data collection"
- "AV insurance is going to be cheaper than human insurance because AVs ultimately will be safer"

## AI

**CEO Dara:**
- "We have been using AI tools, whether it's for pricing or matching or routing for years and years"
- "3/4 of the rides on Uber, we have successfully actually predicted with AI algorithms where we think you're likely to go"
- "About 10% of our code now is committed... built by agents, autonomous agents"

**CFO Balaji:**
- "We re-upped" AI investment after "underestimating the amount of impact" during 2026 budget planning
- AI investment being traded off against "incremental headcount growth"

## AI Agent Intermediation Risk

**Analyst Michael Morton (MoffettNathanson), question:**
- Asked about risk of personal AI agents abstracting away Uber's direct consumer relationship

**CEO Dara, response:**
- "We are working and talking to many of these third-party agents. We have a great market position. So we're able to kind of often dictate the terms of trade in those discussions"
- Drew analogy to travel metasearch: "as the Travel business consolidated with an Expedia or Booking and Airbnb... most of the value of those front ends accrued to the large players"

## Insurance & Margins

**CFO Balaji:**
- "This will be the first year since COVID where we expect to see good leverage on our insurance cost line for the U.S. Mobility business"
- "Hundreds of millions of dollars of savings in our insurance line this year"
- Insurance savings from: policy team improvements, technology improvements, and favorable auto insurance market renewals (effective March 2026)
- "Our philosophy has been to return that goodness back to the market" (passing savings to consumers via price reductions)
- "We've seen that price reduction translate to acceleration in trip growth" (referencing California and L.A.)
- Uber is offloading "more risk to third-party carriers" in the current favorable market

## Product Strategy

**CFO Balaji:**
- "Barbell strategy": Premium products (Uber Black, Comfort, Premier) drive "3.5x higher profit growth" vs core; low-cost products (Wait & Save, UberX Share) drive "75% higher frequency"
- Both drive "25% lift in first-time acquisition"

**CEO Dara:**
- Airports are about 15% of Mobility gross bookings
- Hotel bookings launched via Expedia partnership: 700,000+ properties, passes "most of the economics" back to Uber One members as credits
- Uber launched in Finland "this morning" and achieved #1 App Store position

## Competitive Positioning

**CFO Balaji:**
- "We are seeing our Delivery position improving quite substantially across the globe"
- Noted "incremental level of competitive intensity from both DoorDash and Prosus" in European markets
- Stated Uber has "held our own quite well" in Europe
- Announced expansion to 7 new European Delivery markets

## Growth Drivers

**CEO Dara:**
- Sparse/suburban markets: trip growth "growing 2x faster generally in Mobility and Delivery" vs core urban markets
- Cross-platform consumers growing 1.5x faster than overall consumer growth

**CFO Balaji:**
- "One Search" — universal search across Mobility and Delivery products
- Cross-platform expansion headroom: 30% of eligible Mobility consumers haven't used Uber Eats

## Analyst Question Deflections

1. **AV financial metrics:** Analysts asked about AV revenue/margins; management provided partnership count and market targets but no financial specifics
2. **Specific insurance savings figure:** CFO said "hundreds of millions" without providing exact dollar amount
3. **Uber One revenue:** Management disclosed member count and growth but not revenue per member or contribution margin

# Appendix H: Source Index — Uber Technologies (UBER)

## Source Files by Tier

### Tier 1: SEC Filings and Company Announcements

| File | Provider | Date | Description |
|------|----------|------|-------------|
| filings.json | EDGAR via research-cli | 2026-05-22 | SEC filing list (10-K, 10-Q, 8-K) |
| filing_search.json | EDGAR EFTS | 2026-05-22 | Full-text EDGAR search for "UBER 10-K" |
| convertible_search.json | EDGAR EFTS | 2026-05-22 | EDGAR search for "UBER convertible notes indenture" |
| edgar_search_risks.json | EDGAR EFTS | 2026-05-22 | EDGAR search for "UBER risk factors" |
| latest_10k.json | EDGAR | 2026-05-22 | Latest 10-K/10-Q filing text (XBRL cover page only — incomplete extraction) |
| 10k_full.json | EDGAR | 2026-05-22 | 10-K XBRL document (metadata only, not full filing text) |

### Tier 2: Standardized Financial APIs (FMP)

| File | Provider | Date | Description |
|------|----------|------|-------------|
| info.json | FMP | 2026-05-22 | Company profile: name, sector, CEO, employees, market cap |
| quote.json | FMP | 2026-05-21 | Real-time quote: $73.61 |
| income.json | FMP | 2026-05-22 | Income statements FY2016-FY2025 |
| balance.json | FMP | 2026-05-22 | Balance sheets FY2016-FY2025 |
| cashflow.json | FMP | 2026-05-22 | Cash flow statements FY2016-FY2025 |
| metrics.json | FMP | 2026-05-22 | Key metrics: ROIC, EV/EBITDA, FCF yield, DSO |
| ratios.json | FMP | 2026-05-22 | Full ratio suite: margins, leverage, valuation |
| earnings.json | FMP | 2026-05-22 | Quarterly EPS/revenue actuals vs estimates (Q1 2024 – Q1 2026) |
| ratings.json | FMP | 2026-05-22 | Analyst consensus estimates (FY2026-2030), price targets, grades |
| enterprise_value.json | FMP | 2026-05-22 | Enterprise value history FY2021-FY2025 |
| shares_float.json | FMP | 2026-05-22 | Float shares (2,024M), outstanding (2,036M) |
| scores.json | FMP | 2026-05-22 | Altman Z-Score (3.65), Piotroski Score (7) |
| dcf.json | FMP | 2026-05-21 | FMP DCF model value: $141.25 |
| technicals.json | FMP | 2026-05-21 | RSI (45.5), EMAs, SMAs, ADV |
| price_history.json | FMP | 2026-05-22 | Daily prices, 1 year |
| insider.json | FMP | 2026-05-22 | Insider transactions (Form 4): CFO, officer RSU vests |
| holders.json | FMP/EDGAR | 2026-05-22 | 13F institutional holders |
| holders_analytics.json | FMP | 2026-05-22 | Institutional holder analytics (BlackRock, etc.) |
| peer_compare.json | FMP | 2026-05-22 | Peer comparison data |
| peers.json | FMP | 2026-05-22 | FMP peer list (market-cap-based, not operationally similar) |
| news.json | FMP | 2026-05-22 | Recent news headlines with sentiment |
| dividends.json | FMP | 2026-05-22 | Dividend history (none) |
| options.json | FMP | 2026-05-22 | Options data unavailable; historical vol 33.9% |
| segments.json | FMP | 2026-05-22 | Segment/geographic data (404 — unavailable) |
| short_interest.json | FMP | 2026-05-22 | Short interest (404 — unavailable) |
| sector_perf.json | FMP | 2026-05-22 | Sector performance (404 — unavailable) |
| government.json | FMP | 2026-05-22 | Congressional trading (404 — unavailable) |
| computed_metrics.json | research-cli | 2026-05-22 | Computed margins, net debt, EV cross-check |

### Tier 3: Earnings Transcripts

| File | Provider | Date | Description |
|------|----------|------|-------------|
| transcript.json | FMP | 2026-05-06 | Q1 2026 earnings call full transcript |
| transcript_segments.json | FMP | 2026-05-22 | Transcript keyword matches (segment, revenue, AI, etc.) |
| transcript_competitors.json | FMP | 2026-05-22 | Transcript keyword matches (competitor, market, pricing, etc.) |

### Tier 4: Third-Party Research with Methodology

| File | Provider | Date | Description |
|------|----------|------|-------------|
| ecosystem_signals.md | Serper/web-verify | 2026-05-22 | Lyft, DoorDash, Instacart competitive data (primary sources: SEC filings, press releases) |
| claim_verification.json | Serper/Firecrawl | 2026-05-22 | 115 claims verified: 60 Verified, 23 Corroborated, 16 Single-Source, 11 Contradicted, 5 Unverifiable |

### Tier 5: News, Blogs, and Commentary (Web-Searched)

| File | Provider | Date | Description |
|------|----------|------|-------------|
| business_overview.md | Serper/Firecrawl | 2026-05-22 | Web search for segment revenue breakdown |
| segment_financials.md | Serper/Firecrawl | 2026-05-22 | Web search for annual segment operating income |
| revenue_mix.md | Serper/Firecrawl | 2026-05-22 | Web search for revenue breakdown by end market |
| competitive_by_product.md | Serper/Firecrawl | 2026-05-22 | Competitor lists by segment |
| competitive_history.md | Serper/Firecrawl | 2026-05-22 | Market share evolution |
| competitor_data.md | Serper/Firecrawl | 2026-05-22 | Top competitor revenue/margin data |
| customer_alternatives.md | Serper/Firecrawl | 2026-05-22 | Switching costs analysis |
| customer_capex.md | Serper/Firecrawl | 2026-05-22 | Customer spending outlook |
| supply_demand.md | Serper/Firecrawl | 2026-05-22 | Industry supply/demand conditions |
| supply_indicators.md | Serper/Firecrawl | 2026-05-22 | Lead times, capacity utilization |
| supplier_capacity.md | Serper/Firecrawl | 2026-05-22 | Key supplier constraints |
| value_chain.md (raw) | Serper/Firecrawl | 2026-05-22 | Value chain relationships |
| convertible_detail.md | Serper/Firecrawl | 2026-05-22 | Convertible debt details |
| short_interest.md | Serper/Firecrawl | 2026-05-22 | Short interest data (MarketBeat) |
| backlog_breakdown.md | Serper/Firecrawl | 2026-05-22 | Backlog/pipeline information |
| company_ir.md | Serper/Firecrawl | 2026-05-22 | IR press releases |
| company_site_ir.json | Serper | 2026-05-22 | Site-specific IR search |
| press_releases.md | Serper/Firecrawl | 2026-05-22 | PR wire announcements |
| industry.json | Serper/Firecrawl | 2026-05-22 | Industry market outlook |
| presentations.json | FMP IR scraper | 2026-05-22 | Investor presentations and events |

### Analysis Files (Agent-Generated)

| File | Generated | Description |
|------|-----------|-------------|
| analysis/business_profile.md | 2026-05-22 | Business profile synthesis |
| analysis/competitive_position.md | 2026-05-22 | Competitive analysis with Porter's framework |
| analysis/value_chain.md | 2026-05-22 | Value chain mapping and margin analysis |
| analysis/financial_data.md | 2026-05-22 | Financial analysis, Greenwald decomposition, Mauboussin framework |
| analysis/risk_factors.md | 2026-05-22 | Risk factor enumeration and quantification |

## Source Reliability Summary

| Tier | Description | Files Used | Usage Note |
|------|-------------|------------|------------|
| 1 | SEC filings | 6 files | 10-K text incomplete (XBRL only); accession numbers available |
| 2 | FMP financial data | 21 files | Primary quantitative source; 4 endpoints returned 404 |
| 3 | Transcripts | 3 files | Q1 2026 call; speaker attribution verified |
| 4 | Third-party research | 2 files | 115 claims verified with confidence tags |
| 5 | Web-sourced | 18 files | Used only when Tier 1-4 unavailable; caveats applied |

## Claim Verification Summary

From claim_verification.json (115 claims across 19 source files):
- **60 Verified** — confirmed against primary sources
- **23 Corroborated** — multiple sources agree, primary identified
- **16 Single-Source** — one source only, caveat required
- **11 Contradicted** — conflicting information across sources; all versions presented
- **5 Unverifiable** — methodology unknown or data cannot be confirmed
