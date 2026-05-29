---
type: company
ticker: META
name: Meta Platforms
updated: "2026-05-29"
sources:
  - info.json
  - value_chain.md
  - segments.json
  - insider.json
  - holders.json
  - transcript_competitors.json
---

# Meta Platforms (META)

## Competitors

- [Apple Inc.](AAPL.md) (AAPL)

## Key Insiders

- Mahoney Curtis J. (officer: Chief Legal Officer)
- Olivan Javier (officer: Chief Operating Officer)
- Powell Dina H. (officer: President and Vice Chairman)

## Top Institutional Holders

- AAF Wealth Management, LLC
- Adams Wealth Management
- ADAPT Investment Managers SA
- AKUNA SECURITIES LLC
- ALKEON CAPITAL MANAGEMENT LLC
- Axiom Investment Management LLC
- BloombergSen Inc.
- BNP PARIBAS ARBITRAGE, SNC
- BNP PARIBAS FINANCIAL MARKETS
- BRANT POINT INVESTMENT MANAGEMENT LLC

---

# Meta Platforms, Inc. (META) — Research Report

**Report Date:** 2026-05-22 [File: quote.json -- timestamp]
**Data As Of:** 2026-05-21 (price), FY2025 for annual financials, Q1 2026 for most recent quarter [File: quote.json -- timestamp; income.json -- FY2025; earnings.json -- Q1 2026]
**Ticker:** META | NASDAQ | Communication Services | Internet Content & Information
**Price:** $607.38 [File: info.json -- price]
**ADV:** $9,361MM [File: info.json -- averageVolume 15,411,547 × price $607.38]
**Market Cap:** $1,541.8B [File: info.json -- marketCap]
**Net Debt:** $2.3B (0.1% of mkt cap) [File: balance.json -- totalDebt $83,897M − cashAndShortTermInvestments $81,592M]
**Net Cash:** −$2.3B (−0.1% of mkt cap) [File: balance.json -- cashAndShortTermInvestments $81,592M − totalDebt $83,897M]
**Enterprise Value:** $1,712.1B [File: enterprise_value.json -- enterpriseValue, at FY2025-end price $660.09]
**Short Interest:** 1.32% of float (28.98M shares short / 2,192.7M float) [File: claim_verification.json -- C060: Corroborated via MarketBeat and Fintel citing NASDAQ as of Apr 30, 2026; shares_float.json: floatShares]

**Note on Net Debt methodology:** The compiler formula (totalDebt − cashAndShortTermInvestments = $2.3B) includes $45.7B in short-term investments as offsets to debt. FMP's balance.json `netDebt` field reports $48.0B, computed as totalDebt − cashAndCashEquivalents only. The $45.7B difference is short-term investments, which may have varying liquidity. Both figures are sourced from [File: balance.json].

---

## Section 1: Business Overview

<!-- IC Question: What does this company do, how is it organized, and how large is each piece? What would change: major divestiture, acquisition, segment reclassification, or revenue mix shift. -->

### Company Identity

Meta Platforms, Inc. is a digital advertising and technology company headquartered at 1 Meta Way, Menlo Park, CA 94025. The company operates in the Communication Services sector within the Internet Content & Information industry, and trades on the NASDAQ Global Select Market. As of year-end FY2025, Meta employed 76,834 full-time employees [File: info.json -- fullTimeEmployees]. As of Q1 2026, headcount was approximately 77,900, down 1% from Q4 2025 [File: transcript_segments.json -- Susan Li]. The CEO is Mark Elliot Zuckerberg [File: info.json -- ceo], who also serves as Chairman and controls majority voting power through a dual-class share structure (Class B shares carry 10 votes per share vs. 1 vote for Class A) [File: info.json -- description; financial_data.md: Capital Structure].

### Reportable Segments

Meta reports financial results under two segments: **Family of Apps (FoA)** and **Reality Labs (RL)** [File: info.json -- description; segment_financials.md: SEC filing reference]. FMP segments.json returned empty (API error 404); segment data is reconstructed from the Q1 2026 earnings call transcript and third-party financial aggregators [File: segments.json -- error; business_overview.md; transcript_segments.json: Susan Li].

| Segment | FY2025 Revenue | % of FY Total | Q1 2026 Revenue | % of Q1 Total | Q1 2026 YoY Growth | [File: income.json; transcript_segments.json; earnings.json]
|---------|---------------|---------------|-----------------|---------------|-------------------|
| **Family of Apps (FoA)** | $198.75B | 98.9% | $55.9B | 99.3% | +33% | [File: business_overview.md; transcript_segments.json -- Susan Li]
| — Advertising | $196.17B | 97.6% | $55.0B | 97.7% | +33% (+29% cc) | [File: business_overview.md; transcript_segments.json -- Susan Li]
| — Other | $2.58B | 1.3% | $885M | 1.6% | +74% | [File: business_overview.md; transcript_segments.json -- Susan Li]
| **Reality Labs (RL)** | $2.21B | 1.1% | $402M | 0.7% | −2% | [File: business_overview.md; transcript_segments.json -- Susan Li]
| **Total** | **$200.97B** | **100%** | **$56.3B** | **100%** | **+33%** | [File: income.json -- revenue; earnings.json -- revenueActual; transcript_segments.json]

Sources: FY2025 total revenue $200,966M [File: income.json -- revenue]. FY2025 segment split from Stock Analysis aggregator [File: business_overview.md]; sum = $200,960M vs. income.json $200,966M — $6M gap from rounding [Single-Source caveat: Stock Analysis is a third-party aggregator]. Q1 2026 totals from [File: transcript_segments.json -- Susan Li] and [File: earnings.json -- revenueActual $56,311M]. Q1 2026 segment sum ($55.9B + $0.402B = $56.302B) vs. earnings.json $56.311B — $9M gap from transcript rounding [Inference: transcript uses rounded figures] [Sources: earnings.json, transcript_segments.json]. FY2024 total revenue: $164,501M [File: income.json]; FY2025 YoY growth: +22.2% [File: income.json].

**Data gap:** FY2025 segment-level operating income/loss is not available in current raw data. FY2025 Reality Labs operating loss was $19,193M per [File: claim_verification.json -- C042, Verified: "FoA operating income $102,469M, RL operating loss ($19,193M)"]. FoA operating income was $102,469M. The Q1 2026 transcript provides only consolidated operating income ($22.9B, 41% margin) without FoA vs. RL breakout [File: transcript_segments.json -- Susan Li].

### Key Products

**Family of Apps:** (1) Facebook — social networking, News Feed, Groups, Marketplace, Video; Facebook video time increased 8%+ globally in Q1 2026 (largest QoQ gain in 4 years) [File: transcript_segments.json -- Susan Li]. (2) Instagram — photo/video sharing including Feed, Stories, Reels; Reels time spent increased 10% in Q1 2026 from ranking improvements [File: transcript_segments.json -- Susan Li]. (3) Messenger — cross-platform messaging. (4) WhatsApp — encrypted messaging for individuals and businesses; primary driver of FoA Other revenue growth (+74% YoY in Q1 2026) through paid messaging and subscriptions [File: transcript_segments.json -- Susan Li]. (5) Threads — text-based social app; no revenue separately disclosed [File: transcript_segments.json -- Mark Zuckerberg]. (6) Meta AI — AI assistant across Meta apps and standalone app; no revenue separately disclosed [File: transcript_segments.json -- Mark Zuckerberg].

**Reality Labs:** (1) Meta Quest — VR headset line; Q1 2026 headset sales declined YoY [File: transcript_segments.json -- Susan Li]. (2) Meta Ray-Ban Smart Glasses — AI-enabled smart glasses via partnership with EssilorLuxottica; "continued strong growth" in Q1 2026 [File: transcript_segments.json -- Susan Li]. (3) AR/VR software and content platform [File: info.json -- description].

### AI: Narrative vs. Reality

Meta does not separately disclose AI-specific revenue. There is no "AI segment" or "AI revenue" line item [Inference: AI revenue is not separately measurable from Meta's disclosures] [Sources: transcript_segments.json, segment_financials.md]. AI is embedded in the FoA advertising business as an enabler of ad performance. Advertising revenue was $196.17B in FY2025 (97.6% of total) and $55.0B in Q1 2026 (97.7% of total) [business_overview.md; transcript_segments.json: Susan Li]. AI's impact is observable indirectly: ad impressions increased 19% YoY and average price per ad increased 12% YoY in Q1 2026 [File: transcript_segments.json -- Susan Li]. Revenue growth accelerated from +16% (Q1 2025) to +33% (Q1 2026), driven by multiple factors including AI-enhanced ad performance, macro improvement, and engagement gains; the AI contribution cannot be isolated [Inference: acceleration reflects multiple factors] [Sources: earnings.json, transcript_segments.json].

Meta has raised 2026 capex guidance to $125B–$145B (from prior $115B–$135B), the largest single-year AI infrastructure investment by any company [File: transcript_segments.json -- Susan Li]. For context, NVIDIA's entire FY2026 revenue was $215.9B [File: claim_verification.json -- C013, Verified], meaning Meta's planned capex approaches 58–67% of NVIDIA's annual revenue [Inference: $135B midpoint / $215.9B = 62.5%] [Sources: transcript_segments.json, claim_verification.json C013].

### Historical Context

Meta Platforms, Inc. was incorporated in 2004 as Facebook, Inc. and IPO'd on NASDAQ on May 18, 2012 [File: info.json -- ipoDate]. Major acquisitions include Instagram (2012, ~$1B), WhatsApp (2014, ~$19B), and Oculus VR (2014, ~$2B). The company renamed to Meta Platforms, Inc. in October 2021 and reorganized reporting into FoA and RL segments [File: info.json -- description; segment_financials.md].

---

## Section 2: Competitive Position

<!-- IC Question: For each product, who competes and what are relative strengths? What would change: loss of a top customer, entry of a well-capitalized competitor, customer building in-house alternative, technology disruption. Base rate: What % of companies in Internet Content & Information lost competitive position to a new entrant in the past 5 years? TikTok is the one meaningful recent entrant; Meta's response (Reels) recovered engagement, suggesting incumbents in this market have been able to defend position. -->

### Digital Advertising (FoA — 97.7% of Q1 2026 revenue)

**Competitor landscape (Q1 2026):** [File: claim_verification.json; transcript_segments.json]

| Company | Q1 2026 Ad Revenue | YoY Growth | Source | [File: income.json; transcript_segments.json; earnings.json]
|---------|-------------------|-----------|--------|
| Alphabet (Google Advertising) | $77.25B | +15.5% | [File: claim_verification.json -- C022, Verified] |
| Meta (FoA Advertising) | $55.0B | +33% (+29% cc) | [File: transcript_segments.json -- Susan Li] |
| YouTube (subset of Google) | $9.88B | +11% | [File: claim_verification.json -- C023, Corroborated] |
| Snap | $1.24B | +3% | [File: claim_verification.json -- C002, Verified] |

Meta's Q1 2026 ad revenue of $55.0B represents 41.6% of the combined Google Advertising + Meta FoA Advertising total of $132.25B [Inference: $55.0B / ($77.25B + $55.0B) = 41.6%] [File: transcript_segments.json] [Sources: transcript_segments.json, claim_verification.json C022]. Meta is growing at approximately 2x Alphabet's rate (33% vs. 15.5%) and 11x Snap's rate (33% vs. 3%) [ecosystem_signals.md; earnings.json].

**Revenue growth decomposition (Q1 2026):** Ad impressions increased 19% YoY and average price per ad increased 12% YoY. The multiplicative decomposition (1.19 × 1.12 = 1.333) reconciles with 33% total ad revenue growth [File: transcript_segments.json -- Susan Li].

**Competitive advantages:** (a) Scale — 3.56B DAP across four apps; no competitor matches this multi-app daily reach [File: transcript_segments.json -- Susan Li]. (b) AI-powered ad targeting — Lattice modeling and GEM architecture drove >6% increase in conversion rates; adaptive ranking model +1.6% off-site conversion improvement [File: transcript_segments.json -- Susan Li]. (c) Creator commerce — partnership ads ($10B ARR, doubling YoY) and value optimization suite ($20B+ ARR, more than doubling YoY) [File: transcript_segments.json -- Susan Li]. (d) AI translation — over 0.5 billion users on each of Facebook and Instagram watching AI-translated videos weekly [File: transcript_segments.json -- Susan Li].

**Competitive disadvantages vs. Alphabet:** Google has search intent data, YouTube's video platform, and Cloud/AI infrastructure. Google Cloud backlog nearly doubled QoQ to >$460B [File: claim_verification.json -- C025, C026, Verified].

**ByteDance/TikTok:** TikTok's U.S. MAU is estimated at 136M–183M (estimates diverge widely) [File: claim_verification.json -- C029, Single-Source — TikTok's self-reported 183M U.S. MAU from September 2025 per Motley Fool; Backlinko estimated 136M in January 2026]. TikTok faces ongoing U.S. regulatory uncertainty. Meta's response (Reels) has driven engagement gains: same-day posts represent >30% of recommended Reels (doubled YoY) [File: transcript_segments.json -- Susan Li].

### Smart Glasses (Reality Labs — 0.7% of revenue)

Counterpoint Research reports Meta held 73% of global smart glasses sales in H1 2025 and 82% in H2 2025 [File: claim_verification.json -- C030, Contradicted — Counterpoint Research via Barron's, Feb 16, 2026, vs. a Tier 5 source claiming ~15%]. Meta Ray-Ban Smart Glasses experienced "continued strong growth" in Q1 2026 [File: transcript_segments.json -- Susan Li], while Quest headset sales declined YoY [File: transcript_segments.json -- Susan Li].

### Competition Evolution (5-Year View)

FY2022 revenue declined 1.1% — the first and only annual decline [File: income.json]. The decline coincided with Apple's ATT privacy changes (iOS 14.5, April 2021) and a broader macro advertising downturn [Inference: ATT and macro conditions were the widely attributed causes; Meta estimated a $10B+ annual revenue impact from ATT at the time] [Sources: income.json, competitive_position.md]. Meta responded by rebuilding ad targeting using on-platform signals and AI, executing the "Year of Efficiency" (headcount reduced from ~87K to ~66K in 2023), and expanding R&D investment in AI [income.json; ratios.json]. Revenue has since accelerated from $134.9B (FY2023, +15.7%) to $201.0B (FY2025, +22.2%) to a Q1 2026 run-rate of $56.3B (+33%) [income.json; earnings.json].

The digital advertising market is becoming more concentrated: Meta is growing 2x faster than Alphabet and 11x faster than Snap. The number of meaningful competitors has not increased; the gap between Meta/Alphabet and smaller players is widening [Inference: based on relative growth rates] [File: earnings.json] [Sources: earnings.json, claim_verification.json C001, C002, C022].

---

## Section 3: Supply/Demand Balance

<!-- IC Question: Is industry supply sufficient to meet demand at current prices, and when does that change? What would change: major capacity announcement, demand shock, policy change. Base rate: Digital advertising supply is elastic (more engagement = more impressions), but AI compute infrastructure has 18-36 month build cycles. -->

### Demand Decomposition

Meta's "demand" is advertising demand from businesses seeking to reach 3.56B daily active users. Revenue growth has accelerated from +16% (Q1 2025) to +33% (Q1 2026) [File: earnings.json].

| Period | Revenue | YoY Growth | Ad Impressions Growth | Avg Price/Ad Growth |
|--------|---------|-----------|----------------------|-------------------|
| Q1 2026 | $56.3B | +33% | +19% | +12% | [File: earnings.json -- revenueActual; transcript_segments.json -- Susan Li]
| Q4 2025 | $59.9B | +24% | N/A | N/A | [File: earnings.json -- revenueActual; transcript_segments.json -- Susan Li]
| Q3 2025 | $51.2B | +23% | N/A | N/A | [File: earnings.json -- revenueActual; transcript_segments.json -- Susan Li]
| Q2 2025 | $47.5B | +22% | N/A | N/A | [File: earnings.json -- revenueActual; transcript_segments.json -- Susan Li]
| Q1 2025 | $42.3B | +16% | N/A | N/A | [File: earnings.json -- revenueActual; transcript_segments.json -- Susan Li]

[File: earnings.json -- revenueActual, all quarters]

**Q2 2026 guidance:** $58B–$61B, implying +22–28% YoY growth (vs. Q2 2025 actual of $47.5B) [File: transcript_segments.json -- Susan Li].

**Demand durability drivers:** (1) Engagement gains: Facebook video time +8% QoQ (largest gain in 4 years); Reels time +10% [File: transcript_segments.json -- Susan Li]. (2) AI-driven ad performance: conversion rate improvements (+6% from Lattice/GEM, +1.6% from adaptive ranking, +3% from video generation) [File: transcript_segments.json -- Susan Li]. (3) New ad inventory: Threads ads expanding; WhatsApp Status ads; business AIs driving 10M+ weekly conversations (up from 1M in January 2026) [File: transcript_segments.json -- Susan Li]. (4) CFO attributed part of price/ad growth to "better macro conditions versus Q1 of last year" [File: transcript_segments.json -- Susan Li].

**Demand-side bargaining power:** Advertisers accepted 12% higher prices while simultaneously increasing volume 19% in Q1 2026 [Inference: this pattern is consistent with advertisers seeing positive ROI at current pricing levels] [File: transcript_segments.json] [Sources: transcript_segments.json].

### Supply Constraints

Meta's ad inventory supply is elastic (more engagement = more impressions). The binding constraint is AI compute infrastructure:

**GPU supply:** TSMC's CoWoS advanced packaging capacity is a documented bottleneck through 2027 [File: claim_verification.json -- C014, Corroborated from 4 independent sources]. **HBM memory:** flagged as a supply crisis in 2026 [supplier_capacity.md — Single-Source caveat: EnkiAI blog]. **Component pricing:** Meta raised capex guidance by $10B due to "higher component pricing this year" [File: transcript_segments.json -- Susan Li].

**How supply gets added:** Meta is building data centers, "striking deals throughout the supply chain to secure necessary components" [File: transcript_segments.json -- Susan Li]. Multi-year cloud deals "come online over the course of this year and 2027" [File: transcript_segments.json -- Susan Li]. $107B step-up in contractual commitments in Q1 2026 [File: transcript_segments.json -- Susan Li]. Custom silicon diversification: >1 GW of custom silicon with Broadcom, plus AMD chips alongside NVIDIA [File: transcript_segments.json -- Mark Zuckerberg].

### Supply/Demand Synthesis

Ad inventory supply is not constrained: Meta grew impressions 19% YoY while raising prices 12%, indicating demand exceeds supply at current prices [File: transcript_segments.json -- Susan Li]. AI infrastructure is the binding constraint: capex increasing from 34.7% of revenue (FY2025) to an estimated 49–57% of revenue (FY2026E). GPU supply (TSMC CoWoS) and memory supply (HBM shortage) limit deployment pace [transcript_segments.json; supplier_capacity.md; claim_verification.json C014].

Meta is simultaneously a beneficiary of demand-side pricing power (ad market) and subject to supply-side pricing power from its suppliers (GPU/memory market) [Inference: dual position in supply chain] [Sources: transcript_segments.json, supplier_capacity.md]. CFO stated: "Our experience so far has been that we have continued to underestimate our compute needs even as we have been ramping capacity significantly" [File: transcript_segments.json -- Susan Li].

### AI Value Chain Positioning

Meta occupies three positions: (1) **AI Application Layer** (primary): AI powers ad targeting, content recommendation, and engagement across 3.56B DAP [File: transcript_segments.json -- Susan Li]. (2) **AI Model Training** (emerging): Meta Super Intelligence Labs released MuSpark in Q1 2026 [File: transcript_segments.json -- Mark Zuckerberg]. (3) **AI Infrastructure / Custom Silicon** (emerging): >1 GW of custom silicon with Broadcom [File: transcript_segments.json -- Mark Zuckerberg].

---

## Section 4: Value Chain

<!-- IC Question: Where is value captured, and is it migrating toward or away from this company? What would change: vertical integration by customer/supplier, margin compression, technology disintermediation. Base rate: How often does value chain position shift in Internet Content & Information within 5 years? The ATT disruption in 2021 is the clearest example; Meta recovered within 2 years. [File: info.json] -->

### Value Chain Map

```
[Chip suppliers: NVIDIA, Broadcom, AMD]
  → [Data center infrastructure: self-built + JV + cloud leases]
    → [AI/ML systems: recommendation engines, ad ranking, Meta AI models]
      → [Social media platforms: Facebook, Instagram, WhatsApp, Messenger, Threads]
        → [User engagement: 3.56B DAP]
          → [Ad inventory: impressions across surfaces]
            → [Advertisers: millions of businesses globally]
```

[File: transcript_segments.json -- Mark Zuckerberg, Susan Li; info.json: description]

### Upstream: Key Suppliers

**NVIDIA (GPUs):** Primary supplier of AI training/inference GPUs. NVIDIA Data Center revenue was $75.2B in Q1 FY2027, +92% YoY [ecosystem_signals.md; claim_verification.json: C012, Verified]. Meta is one of NVIDIA's largest hyperscaler customers [File: ecosystem_signals.md]. **Broadcom (custom silicon):** Meta developing MTIA chips with Broadcom; deploying >1 GW of custom silicon [File: transcript_segments.json -- Mark Zuckerberg]. **AMD:** "Significant amount of AMD chips to complement the new NVIDIA systems" [File: transcript_segments.json -- Mark Zuckerberg]. **TSMC (indirect):** All three chip suppliers rely on TSMC for advanced-node manufacturing. CoWoS packaging is a bottleneck through 2027 [supplier_capacity.md; claim_verification.json: C014, Corroborated]. **Memory (SK Hynix, Samsung, Micron):** Higher memory pricing drove the $10B capex guidance increase [File: transcript_segments.json -- Mark Zuckerberg]. **EssilorLuxottica:** Manufacturing partner for Ray-Ban Meta smart glasses [info.json; transcript_segments.json].

### Downstream: Customers

Meta's revenue customers are **millions of individual advertisers**. No single advertiser exceeds 10% of revenue [Inference: absence of SEC-required disclosure implies no customer ≥10%] [Sources: segment_financials.md; claim_verification.json: C044, Verified]. Key metrics: >8M advertisers using GenAI creative tools; value optimization suite >$20B ARR (doubling YoY); partnership ads >$10B ARR; >10M weekly business AI conversations (10x from Jan 2026) [File: transcript_segments.json -- Susan Li].

### Margin Capture

Meta captures margin at the platform/monetization layer. FY2025 gross margin was 82.0% and operating margin was 41.4% [income.json; ratios.json]. Gross margin has been stable at 78–83% for a decade due to near-zero marginal cost of serving ads on user-generated content [File: income.json -- costOfRevenue FY2025 $36.2B vs. revenue $201.0B].

**Margin migration direction:** Margin is concentrating at the largest ad platforms. Meta's Q1 2026 ad revenue grew +33% at a 41% operating margin, while Snap's Q1 2026 net loss was $89M on $1.53B revenue (approximately −6% net margin) [ecosystem_signals.md; claim_verification.json: C001, Verified]. Simultaneously, margin is migrating toward chip suppliers: NVIDIA's operating margin expanded from ~37% (FY2022) to ~62% (FY2026) as AI compute demand surged [Inference: approximate from NVIDIA public results] [File: ecosystem_signals.md] [Sources: ecosystem_signals.md].

### Integration Direction

Meta is **backward-integrating** into infrastructure: (1) Custom silicon (MTIA) with Broadcom reduces NVIDIA dependence for inference. (2) Data center buildout: PP&E grew from $70.0B (FY2021) to $196.8B (FY2025), +181% [File: balance.json -- propertyPlantEquipmentNet]. (3) AI model development in-house via Meta Super Intelligence Labs [File: transcript_segments.json -- Mark Zuckerberg].

Meta is **selectively forward-integrating** toward commerce: affiliate partnerships on Facebook/Instagram, >10M weekly business AI conversations on WhatsApp/Messenger, and Meta AI personal agent with future "commission structures or a premium offering" [File: transcript_segments.json -- Susan Li].

### Single Points of Failure

(1) **TSMC:** All three chip suppliers rely on TSMC; single foundry-level dependency. (2) **Advertising revenue concentration:** 97.6% of FY2025 revenue. (3) **Mobile OS gatekeepers:** Apple iOS and Google Android control app distribution and data collection policies; Apple's ATT caused a documented multi-billion dollar revenue headwind in 2022 [Inference: from FY2022 revenue decline pattern] [File: income.json] [Sources: income.json].

---

## Section 5: Capital Structure

<!-- IC Question: How does the company raise money to spend on its business? What would change: major debt issuance or repayment, M&A financing, credit rating change, new equity issuance. -->

### Equity Composition

- **Dual-class structure:** Class A (1 vote/share, publicly traded) and Class B (10 votes/share, held by insiders). Mark Zuckerberg controls majority voting power [File: info.json -- description].
- **Preferred stock:** $0 [File: balance.json -- preferredStock]
- **Market cap:** $1,541.8B [File: quote.json -- marketCap]
- **Shares outstanding:** 2,538.4M (as of 3/31/2026) [File: shares_float.json -- outstandingShares]
- **Diluted shares (FY2025 weighted avg):** 2,574M [File: income.json -- weightedAverageShsOutDil]

### Debt Composition

| Component | Amount | Source |
|-----------|--------|--------|
| Total Debt | $83.9B | [File: balance.json -- totalDebt] |
| — Short-term debt | $0 | [File: balance.json -- shortTermDebt] |
| — Long-term debt (bonds) | $58.7B | [File: balance.json -- longTermDebt] |
| — Capital leases (current) | $2.2B | [File: balance.json -- capitalLeaseObligationsCurrent] |
| — Capital leases (non-current) | $22.9B | [File: balance.json -- capitalLeaseObligationsNonCurrent] |
| Total capital lease obligations | $25.2B | [File: balance.json -- capitalLeaseObligations] |

Meta had no long-term debt prior to 2022. Three major bond offerings: [File: balance.json -- longTermDebt]

1. **May 2023 (~$8.5B):** Including 4.600% Senior Notes due 2028 and other tranches [File: claim_verification.json -- C061, C064, Verified: SEC 424B2 prospectus].
2. **August 2024 ($10.5B):** Including $2.5B at 4.75% due 2034 and $3.25B at 5.40% due 2054 [File: claim_verification.json -- C062, Corroborated].
3. **November 2025 ($30.0B):** Six tranches: $4.0B at 4.200% due 2030; $4.0B at 4.600% due 2032; $6.5B at 4.875% due 2035; $4.5B at 5.500% due 2045; $6.5B at 5.625% due 2055; $4.5B at 5.750% due 2065 [File: claim_verification.json -- C063, Verified: SEC 8-K filing Oct 30, 2025].

Maturity profile spans 2028–2065. No bonds mature before 2028. Coupons range from 4.200% to 5.750%. [File: claim_verification.json -- C061, C062, C063]

**Convertible debt:** None outstanding [File: convertible_search.json -- no META results].

### Debt Maturity Profile

Known bond tranches aggregate to approximately $49B ($8.5B + $10.5B + $30.0B). The difference vs. $58.7B long-term debt on the balance sheet may reflect earlier issuances, FMP classification differences, or bond tranches not captured in claim verification [Data gap: complete maturity schedule requires 10-K Note on Debt]. [File: claim_verification.json -- C061, C062, C063; balance.json -- longTermDebt]

### Cash and Equivalents

| Item | Amount | Source |
|------|--------|--------|
| Cash & equivalents | $35.9B | [File: balance.json -- cashAndCashEquivalents] |
| Short-term investments | $45.7B | [File: balance.json -- shortTermInvestments] |
| Cash + ST investments | $81.6B | [File: balance.json -- cashAndShortTermInvestments] |

### Minority Interest

$0 [File: balance.json -- minorityInterest]

### Enterprise Value

$1,712.1B at FY2025-end price of $660.09 [File: enterprise_value.json -- enterpriseValue]. At current price of $607.38: approximately $1,544.1B using compiler net debt formula ($1,541.8B market cap + $2.3B net debt), or $1,589.8B using FMP net debt ($1,541.8B + $48.0B) [Inference: EV computed at current price] [Sources: quote.json, balance.json].

### Net Debt / EBITDA

FY2025 EBITDA: $104.5B [File: income.json -- ebitda]. Net Debt / EBITDA: 0.02x using compiler net debt ($2.3B / $104.5B), or 0.46x using FMP net debt ($48.0B / $104.5B) [Inference: ratio depends on whether short-term investments offset debt] [Sources: balance.json, income.json].

---

## Source Index

See Appendix H for the complete source list with reliability tiers. Key sources for this report:

- [File: income.json] — FMP, FY2015–FY2025 annual income statements. Tier 2.
- [File: balance.json] — FMP, FY2015–FY2025 annual balance sheets. Tier 2.
- [File: cashflow.json] — FMP, FY2015–FY2025 annual cash flow statements. Tier 2.
- [File: transcript_segments.json] — Q1 2026 earnings call transcript (Apr 29, 2026), keyword-matched segments. Tier 3.
- [File: earnings.json] — FMP, Q1 2024–Q1 2026 quarterly actuals vs. estimates. Tier 2.
- [File: claim_verification.json] — 106 web-sourced claims: 48 Verified, 32 Corroborated, 9 Single-Source, 7 Contradicted, 10 Unverifiable.
- [File: enterprise_value.json] — FMP, FY2021–FY2025 enterprise value history. Tier 2.
- [File: ecosystem_signals.md] — SNAP, NVDA, GOOGL peripheral Q1 2026 data. Tier 4–5.

## Discrepancies & Data Gaps

### Cross-Reference Conflicts

1. **Net debt calculation:** The compiler formula (totalDebt − cashAndShortTermInvestments = $2.3B) differs from FMP's `netDebt` field ($48.0B, which uses totalDebt − cashAndCashEquivalents). The $45.7B difference is short-term investments. Both are sourced from [File: balance.json]. The financial_data.md analysis used FMP's $48.0B figure.

2. **Interest expense:** income.json reports $0 interest expense for FY2025 despite $58.7B in long-term bond debt at coupons of 4.2%–5.75%. FY2024 showed $715M interest expense on $28.8B long-term debt. The $0 figure is inconsistent; it may reflect FMP netting interest income against expense or capitalization of interest during construction [Data gap: gross interest expense requires 10-K]. [File: income.json -- interestExpense; balance.json -- longTermDebt]

3. **Short interest data divergence:** claim_verification.json C060 reports 28.98M shares short (Corroborated: MarketBeat and Fintel citing NASDAQ, Apr 30, 2026). short_interest.md via shortsqueeze.com reports 26.47M shares with 1.21% of float [Single-Source]. The report uses the Corroborated figure. [File: claim_verification.json -- C060; short_interest.md]

4. **TikTok U.S. MAU:** Estimates range from 136M (Backlinko, Jan 2026) to 183M (TikTok self-reported, Sep 2025). Both figures carry [Single-Source] caveats [File: claim_verification.json -- C029].

### Data Gaps

- **10-K filing text:** Not retrieved in this run. Customer concentration disclosures, debt maturity schedules, geographic revenue breakdown, and specific risk factor language are unavailable from the primary filing.
- **Segment-level operating income for Q1 2026:** FoA vs. RL operating income/loss not disclosed in Q1 2026 transcript prepared remarks. [File: transcript_segments.json]
- **Geographic revenue split:** FMP segments.json returned empty; no geographic breakdown available.
- **MTIA custom silicon details:** Percentage of workloads on MTIA vs. NVIDIA/AMD not disclosed.
- **Advertiser concentration metrics:** No data on top 10/100/1000 advertiser revenue share. [File: segment_financials.md -- data gap]
- **Proxy statement:** Not available; Zuckerberg's exact voting power percentage unverified.
- **Options chain data:** FMP API error 404. Put/call ratio and implied volatility unavailable.
- **Dividend history detail:** dividends.json returned FMP API error 404.
- **FY2025 gross interest expense:** Reported as $0 in income.json, inconsistent with $58.7B debt. Estimated range: $2B–$4B annually based on bond coupons [Inference] [File: claim_verification.json C061–C063] [Sources: claim_verification.json C061–C063].
- **Reality Labs cumulative losses:** Only FY2025 RL operating loss ($19.2B) is verified. Prior years estimated at ~$60B+ cumulative since 2021 [Inference: approximate from general knowledge] [File: claim_verification.json C042] [Sources: claim_verification.json C042].
- **Congressional trading data:** FMP API error 404 [File: government.json].

### Inference Chain Summary

All inferences in this report are labeled with `[Inference:]` tags and supporting `[Sources:]`. Key inference chains:
1. Segment sum verification: transcript uses rounded figures; $9M gap explained by rounding [File: earnings.json] [Sources: earnings.json, transcript_segments.json].
2. No single customer ≥10%: inferred from absence of SEC-required disclosure [File: segment_financials.md] [Sources: segment_financials.md].
3. Net Debt computation: two valid methods yield different results ($2.3B vs. $48.0B); difference is $45.7B in short-term investments [File: balance.json] [Sources: balance.json].
4. Revenue growth acceleration (16% → 33%) attributed to multiple factors; AI contribution cannot be isolated [File: earnings.json] [Sources: earnings.json, transcript_segments.json].
5. Margin migration toward large platforms inferred from relative growth rates and margin levels [Sources: ecosystem_signals.md, earnings.json, claim_verification.json].

---

## Appendix

# Appendix A: Competitive Position — Meta Platforms (META)

## Market Position Summary

Meta's FoA advertising platform generated $55.0B in Q1 2026 ad revenue (+33% YoY, +29% constant currency), placing it as the second-largest digital advertising platform behind Alphabet's Google Advertising ($77.25B, +15.5% YoY) [transcript_segments.json: Susan Li; claim_verification.json: C022, Verified].

## Competitor Detail by Product

### Digital Advertising (97.7% of Q1 2026 revenue)

**Alphabet/Google:** Q1 2026 total revenue $109.9B (+22% YoY). Google Advertising revenue $77.25B (+15.5%). YouTube ads $9.88B (+11%). Google Cloud $20B (+63% YoY). Google Cloud backlog nearly doubled QoQ to >$460B. Google's competitive advantages: search intent data, YouTube video platform, Cloud/AI infrastructure (TPUs). Google's disadvantage vs. Meta: slower ad revenue growth (15.5% vs. 33%). [ecosystem_signals.md; claim_verification.json: C021–C026, Verified/Corroborated]

**ByteDance/TikTok:** U.S. MAU estimated at 136M–183M (estimates diverge widely). TikTok claimed 183M U.S. MAU in September 2025 [claim_verification.json: C029, Single-Source]; Backlinko estimated 136M in January 2026 [Single-Source]. TikTok competes directly with Instagram Reels and Facebook Video for short-form video engagement. TikTok faces U.S. regulatory uncertainty (forced divestiture proceedings). TikTok's ad revenue is not publicly disclosed (ByteDance is private). Meta's Reels response: same-day content >30% of recommended Reels (doubled YoY); Reels time +10% in Q1 2026 [transcript_segments.json: Susan Li]. No mention of TikTok in Q1 2026 earnings call [transcript_competitors.json: no matches].

**Snap:** Q1 2026 total revenue $1.53B (+12% YoY); advertising revenue $1.24B (+3%). Net loss of $89M. North America ad revenue growth decelerated to +2% YoY. Geopolitical events (Middle East conflict) caused an estimated $20M–$25M monthly impact on ad revenue. Meta's Q1 ad revenue is 44x Snap's. [claim_verification.json: C001, C002, C004, Verified; ecosystem_signals.md]

**Amazon Ads:** Growing competitor with purchase intent data and closed-loop measurement. Competes for commerce-related ad dollars. Amazon's ad revenue not available in this dataset. [Data gap]

**Microsoft/LinkedIn:** Competes for B2B advertising and professional engagement. Microsoft's AI investments (Copilot, OpenAI partnership) are in adjacent but distinct markets.

### Smart Glasses (0.7% of Q1 2026 revenue)

Meta Ray-Ban Smart Glasses: Counterpoint Research reports Meta held 73% of global smart glasses sales in H1 2025 and 82% in H2 2025 [claim_verification.json: C030, Contradicted — Counterpoint via Barron's vs. Tier 5 source claiming ~15%; Counterpoint is more credible]. Primary competitor: Apple Vision Pro (different price segment, ~$3,500+ vs. Ray-Ban Meta at ~$300). No unit volumes disclosed by Meta.

### VR Headsets (within 0.7% of Q1 2026 revenue)

Meta Quest: Sales declined YoY in Q1 2026 [transcript_segments.json: Susan Li]. Competitors: Sony PlayStation VR2, Apple Vision Pro. Meta is "focused on making our VR business sustainable" [transcript_segments.json: Mark Zuckerberg].

## Five-Year Revenue Trajectory

| Year | Revenue | YoY Growth |
|------|---------|-----------|
| FY2020 | $86.0B | +21.6% |
| FY2021 | $117.9B | +37.2% |
| FY2022 | $116.6B | −1.1% |
| FY2023 | $134.9B | +15.7% |
| FY2024 | $164.5B | +21.9% |
| FY2025 | $201.0B | +22.2% |

[income.json: revenue, all years]

3-year CAGR (FY2022–FY2025): 19.9%. 5-year CAGR (FY2020–FY2025): 18.5%. [Inference: calculated from income.json]

## Switching Costs

**User-side:** Social graph lock-in (friend networks, messaging history, group memberships across 4 apps). Engagement metrics rising: Facebook video time +8% QoQ, Reels time +10% QoQ [transcript_segments.json: Susan Li].

**Advertiser-side:** Performance data accumulation (conversion history, audience segments, lookalike models); tool adoption (>8M advertisers using GenAI tools; value optimization suite >$20B ARR; partnership ads >$10B ARR); business AI integration (>10M weekly conversations via business AIs, up from 1M in Jan 2026); Meta Ads AI Connectors (open beta) deepening integration into advertiser tech stacks [transcript_segments.json: Susan Li].

## Silence Analysis

**Topics NOT discussed in Q1 2026 earnings call:**
1. Reality Labs operating losses (Q1 2026 segment-level not quantified)
2. TikTok / ByteDance (no mention at all)
3. Advertiser churn or concentration metrics
4. Geographic revenue breakdown (beyond "lower monetizing regions")
5. MTIA custom silicon specifics (performance benchmarks, % of workloads)

**Deflected questions:**
- 2027 capex: Susan Li responded "We aren't providing a specific outlook for 2027 CapEx" [transcript_segments.json: Susan Li, Q&A]
- AI glasses unit sales: Susan Li discussed engagement trends but did not provide a unit sales figure [transcript_segments.json: Susan Li, Q&A]

## Sources

[income.json], [earnings.json], [transcript_segments.json], [ecosystem_signals.md], [claim_verification.json], [competitive_by_product.md], [competitive_history.md], [competitor_data.md], [customer_alternatives.md], [short_interest.md]

# Appendix B: Supply/Demand Balance — Meta Platforms (META)

## Demand Analysis

### Advertising Demand Decomposition

Meta's demand is a function of: (a) user engagement (time spent, impressions served), and (b) advertiser willingness to pay (conversion value, ROI).

**Q1 2026 demand drivers (all from transcript_segments.json: Susan Li):**
- Ad impressions increased 19% YoY
- Average price per ad increased 12% YoY
- Multiplicative decomposition: 1.19 × 1.12 = 1.333, reconciling with 33% ad revenue growth
- Video time on Facebook increased >8% globally QoQ (largest gain in 4 years)
- Reels time spent increased 10% from ranking improvements
- Same-day content >30% of recommended Reels (doubled YoY)
- More than 8 million advertisers using at least one GenAI creative tool
- Value optimization suite ARR >$20B (more than doubling YoY)
- Partnership ads ARR >$10B (doubling YoY)
- Business AIs: >10M weekly conversations on WhatsApp/Messenger (up from 1M in Jan 2026)

### Advertiser Beat Pattern

| Quarter | Revenue ($B) | Consensus Est ($B) | Beat |
|---------|-------------|-------------------|------|
| Q1 2026 | $56.3 | $55.6 | +1.4% |
| Q4 2025 | $59.9 | $58.3 | +2.7% |
| Q3 2025 | $51.2 | $49.5 | +3.5% |
| Q2 2025 | $47.5 | $44.8 | +6.0% |
| Q1 2025 | $42.3 | $41.3 | +2.4% |

[earnings.json: revenueActual, revenueEstimated]

8 consecutive revenue beats with average beat of 2.4%.

### Demand Durability Assessment

**Secular drivers:** Digital advertising's share of total advertising spend continues to grow. Meta's 3.56B DAP represents the largest global audience on any platform family [transcript_segments.json: Susan Li]. AI-driven ad performance improvements (conversion rates, creative tools, recommendation quality) create a flywheel: better targeting → higher ROI → more ad spend → more data → better targeting.

**Cyclical sensitivity:** FY2022 revenue declined 1.1% during the combined ATT + macro headwind period [income.json]. This is the only annual decline in Meta's history. CFO attributed part of Q1 2026 acceleration to "better macro conditions versus Q1 of last year" [transcript_segments.json: Susan Li], indicating some cyclical component.

**Customer capex corroboration:** Meta's own capex guidance of $125B–$145B for 2026 represents Meta as both a customer (of NVIDIA, Broadcom, AMD) and a supplier (of ad inventory) [transcript_segments.json: Susan Li]. On the customer side, Meta's advertisers span millions of businesses; their individual capex signals cannot be tracked.

## Supply Analysis

### Ad Inventory Supply

Meta's ad inventory supply is elastic: more user engagement creates more impressions. Q1 2026 impression growth of 19% YoY was driven by:
- New surfaces (Threads ads expanding to more markets, WhatsApp Status ads)
- Engagement gains (video time, Reels time)
- AI-translated content reaching new audiences (>0.5B users watching translated videos weekly on each of Facebook and Instagram)
[transcript_segments.json: Susan Li]

### AI Infrastructure Supply Constraints

This is the binding constraint on Meta's growth trajectory:

**TSMC CoWoS capacity:** Advanced packaging bottleneck through 2027 [claim_verification.json: C014, Corroborated from 4 independent sources including Broadcom CEO flagging]. All three of Meta's chip suppliers (NVIDIA, Broadcom, AMD) rely on TSMC.

**HBM memory:** Characterized as a supply crisis in 2026, with SK Hynix and Micron production sold out [supplier_capacity.md — Single-Source caveat: EnkiAI blog, not independently verified]. Zuckerberg cited "higher component costs, particularly memory pricing" as the key driver of the $10B capex guidance increase [transcript_segments.json: Mark Zuckerberg].

**Lead times for capacity addition:**
- Data center construction: 18–36 months typical for hyperscale facilities
- Meta JV with Blue Owl Capital for Hyperion data center (announced October 2025) [press_releases.md; claim_verification.json: C096, Verified]
- Multi-year cloud deals "come online over the course of this year and 2027" [transcript_segments.json: Susan Li]
- NVIDIA CEO stated manufacturing constraints are "scalable two-to-three year problems, not permanent" [supplier_capacity.md; claim_verification.json: C071, Corroborated from 3 sources]

### Capital Intensity of Supply

| Year | Capex ($B) | Capex/Revenue | PP&E ($B) |
|------|-----------|---------------|-----------|
| FY2021 | $18.6 | 15.7% | $70.0 |
| FY2022 | $31.4 | 27.0% | $79.5 |
| FY2023 | $27.3 | 20.2% | $109.9 |
| FY2024 | $37.3 | 22.6% | $136.3 |
| FY2025 | $69.7 | 34.7% | $196.8 |
| FY2026E | $125–145B | ~49–57% | N/A |

[cashflow.json: capitalExpenditure; balance.json: propertyPlantEquipmentNet; transcript_segments.json: guidance]

$107B step-up in contractual commitments in Q1 2026, reflecting pre-purchased supply agreements [transcript_segments.json: Susan Li].

## Supply/Demand Synthesis

**Net balance:** Ad inventory supply is growing (impressions +19%) with positive pricing (+12%), indicating demand exceeds supply at current prices. The bottleneck is AI compute infrastructure, not ad inventory.

**Pricing implications:** Meta is capturing value from the ad supply/demand imbalance. Its suppliers (NVIDIA, memory vendors) are also capturing value from the AI infrastructure supply/demand imbalance. The $10B capex guidance increase reflects supplier pricing power being passed through to Meta.

**When the gap closes:** NVIDIA CEO's statement of "two-to-three year" timeline for manufacturing constraints suggests GPU supply tightness persists through 2027–2028 [claim_verification.json: C071, Corroborated]. Meta's custom silicon (MTIA) and multi-vendor strategy (NVIDIA + AMD + Broadcom) provide partial mitigation, but exact timeline for capacity sufficiency is unknown.

**CFO optionality statement:** If demand for compute doesn't materialize as projected, "we can choose to bring it online more slowly or reduce our spending in future years" [transcript_segments.json: Susan Li].

## Sources

[transcript_segments.json], [earnings.json], [cashflow.json], [balance.json], [supplier_capacity.md], [supply_demand.md], [supply_indicators.md], [ecosystem_signals.md], [claim_verification.json], [press_releases.md], [customer_capex.md]

# Appendix C: Value Chain — Meta Platforms (META)

## Full Value Chain Map

### Advertising Value Chain (98.9% of FY2025 revenue)

```
[Chip suppliers: NVIDIA, Broadcom/MTIA, AMD]
  → [Foundry: TSMC (indirect; Meta's chip suppliers are TSMC's customers)]
    → [Memory: SK Hynix, Samsung, Micron (HBM, DRAM)]
      → [Data center infrastructure: self-built + Blue Owl JV + third-party cloud]
        → [AI/ML systems: GEM, Lattice, adaptive ranking, MuSpark foundation model]
          → [Social media platforms: Facebook, Instagram, WhatsApp, Messenger, Threads]
            → [User engagement: 3.56B DAP (March 2026)]
              → [Ad inventory: impressions across Feed, Stories, Reels, Video, Status]
                → [Ad auction system: real-time bidding, value optimization]
                  → [Advertisers: millions of businesses globally]
```

### Hardware Value Chain (1.1% of FY2025 revenue)

```
[Component suppliers: Qualcomm chipsets (inferred), other hardware components]
  → [EssilorLuxottica: glasses manufacturing, brand licensing, distribution]
    → [Meta: AI software, hardware design, OS]
      → [Products: Meta Quest VR headsets, Meta Ray-Ban smart glasses]
        → [Consumer end users]
```

[Sources: transcript_segments.json: Mark Zuckerberg, Susan Li; info.json: description; supplier_capacity.md; ecosystem_signals.md]

## Upstream Supplier Detail

### NVIDIA Corporation — GPU Supplier
- NVIDIA Data Center revenue: $75.2B in Q1 FY2027 (ended Apr 2026), +92% YoY [ecosystem_signals.md; claim_verification.json: C012, Verified]
- Meta is one of NVIDIA's largest hyperscaler customers
- CUDA ecosystem creates high switching costs for model training workloads
- Meta deploying NVIDIA GPUs alongside AMD chips and custom MTIA silicon [transcript_segments.json: Mark Zuckerberg]
- Exact allocation of Meta's capex to NVIDIA vs. AMD vs. Broadcom not disclosed [Data gap]

### Broadcom Inc. — Custom Silicon Partner
- Meta developing MTIA (Meta Training and Inference Accelerator) with Broadcom
- Deploying "more than 1 gigawatt of our own custom silicon that we're developing with Broadcom" [transcript_segments.json: Mark Zuckerberg]
- Broadcom CEO flagged TSMC CoWoS as bottleneck through 2027 [ecosystem_signals.md; claim_verification.json: C014, Corroborated]

### AMD — Complementary GPU Supplier
- "Significant amount of AMD chips to complement the new NVIDIA systems" [transcript_segments.json: Mark Zuckerberg]
- Serves as second-source strategy to reduce NVIDIA concentration risk
- Volume and dollar share vs. NVIDIA not disclosed [Data gap]

### TSMC — Foundry (Indirect)
- Manufactures chips for NVIDIA, Broadcom, and AMD
- CoWoS advanced packaging capacity documented as bottleneck through 2027 [claim_verification.json: C014, Corroborated from 4 sources; C069, Corroborated; C072, Corroborated from 3 sources]
- Meta has no direct TSMC relationship; constraint is mediated through chip suppliers

### Memory Suppliers (SK Hynix, Samsung, Micron)
- HBM supply characterized as a crisis in 2026 [supplier_capacity.md — Single-Source: EnkiAI blog]
- Higher memory pricing drove $10B capex guidance increase [transcript_segments.json: Mark Zuckerberg: "higher component costs, particularly memory pricing"]

### EssilorLuxottica — Glasses Partner
- Manufacturing, distribution, and brand licensing for Ray-Ban Meta smart glasses
- Partnership economics (revenue sharing, minimums, exclusivity terms) not disclosed [Data gap]
- Analyst asked about expanding to additional EssilorLuxottica brands; CFO discussed demand for existing lineup without naming new brand launches [transcript_segments.json: Q&A, analyst Youssef Squali]

## Downstream Customer Detail

### Advertiser Base Metrics (Q1 2026)

| Metric | Value | Source |
|--------|-------|--------|
| Advertisers using GenAI tools | >8M | [transcript_segments.json: Susan Li] |
| Value optimization suite ARR | >$20B (doubling YoY) | [transcript_segments.json: Susan Li] |
| Partnership ads ARR | >$10B (doubling YoY) | [transcript_segments.json: Susan Li] |
| Business AI conversations/week | >10M (10x from Jan 2026) | [transcript_segments.json: Susan Li] |
| Family DAP | 3.56B (March 2026) | [transcript_segments.json: Susan Li] |

No single advertiser exceeds 10% of revenue [Inference: absence of SEC-required disclosure] [Sources: segment_financials.md; claim_verification.json: C044, Verified].

### Revenue by Geography

FMP segments.json returned empty for geographic data. The Q1 2026 transcript noted "impression growth was healthy across all regions" and ~4pp currency tailwind (33% reported vs. 29% constant currency) [transcript_segments.json: Susan Li]. Internet outages in Iran and WhatsApp restrictions in Russia reduced DAP in Q1 2026 [transcript_segments.json: Susan Li]. Geographic revenue split (US&Canada, Europe, APAC, RoW) is available in the 10-K but not in current raw data [Data gap].

## Margin Capture Analysis

### Historical Operating Margin by Chain Stage

| Stage | Company | FY2021 Op Margin | FY2025 Op Margin | Change |
|-------|---------|-----------------|-----------------|--------|
| GPU supplier | NVIDIA | ~37%* | ~62%* | +25pp |
| Ad platform (large) | **Meta** | **39.6%** | **41.4%** | **+1.8pp** |
| Ad platform (small) | Snap | ~−25%* | ~−2%* | +23pp |

*NVIDIA and Snap figures approximate from general knowledge/ecosystem signals, not from raw data files. Meta figures from [income.json; ratios.json].

### Pricing Pass-Through Analysis

Meta's ad pricing is set by competitive auction dynamics, not cost-plus pricing. Input cost increases (memory pricing → $10B capex guidance increase) are absorbed by Meta rather than passed through to advertisers [Inference: auction-based pricing is demand-driven] [Sources: transcript_segments.json]. FY2026 total expense guidance ($162B–$169B) was maintained despite the capex increase, suggesting cost offsets from planned May 2026 layoffs [transcript_segments.json: Susan Li].

## Vertical Integration Assessment

| Value Chain Stage | Integration Level | Direction (3Y) |
|---|---|---|
| Chip design | Partial (MTIA + NVIDIA/AMD) | Integrating |
| Chip fabrication | Outsourced (TSMC) | Stable |
| Data centers | In-house + supplementary cloud | Integrating |
| AI models/algorithms | In-house (MSL, GEM, Lattice) | Integrating |
| Social platforms | In-house | Stable |
| Content | Outsourced (UGC) | Stable |
| Ad serving/auction | In-house | Stable |
| Commerce/transactions | Partial (emerging) | Integrating |
| Hardware (VR/AR) | Partial (EssilorLuxottica) | Stable |

[transcript_segments.json; info.json; balance.json: propertyPlantEquipmentNet]

## Sources

[income.json], [balance.json], [cashflow.json], [transcript_segments.json], [ecosystem_signals.md], [supplier_capacity.md], [claim_verification.json], [value_chain.md], [press_releases.md], [info.json], [segments.json], [customer_alternatives.md]

# Appendix D: Capital Structure — Meta Platforms (META)

## Equity Composition

**Share Class Structure:**
- Class A common stock: 1 vote per share, publicly traded on NASDAQ
- Class B common stock: 10 votes per share, held by insiders (primarily Mark Zuckerberg)
- Mark Zuckerberg controls majority voting power through Class B holdings
- Preferred stock: $0 [balance.json: preferredStock]

[info.json: description; Data gap: exact voting power percentage requires proxy statement, which is not available in this run]

**Share Count:**

| Metric | Value | Source |
|--------|-------|--------|
| Shares outstanding (3/31/2026) | 2,538.4M | [shares_float.json: outstandingShares] |
| Free float | 2,192.7M (86.4% of outstanding) | [shares_float.json: floatShares, freeFloat] |
| Diluted shares (FY2025 weighted avg) | 2,574M | [income.json: weightedAverageShsOutDil] |

**Diluted share count trajectory:**

| Year | Diluted Shares (M) | YoY Change |
|------|-------------------|-----------|
| FY2021 | 2,859 | −1.0% |
| FY2022 | 2,702 | −5.5% |
| FY2023 | 2,629 | −2.7% |
| FY2024 | 2,614 | −0.6% |
| FY2025 | 2,574 | −1.5% |

[income.json: weightedAverageShsOutDil]

4-year diluted share CAGR (FY2021–FY2025): −2.6%. Buybacks exceed SBC dilution.

**Market Capitalization:** $1,541.8B [quote.json: marketCap]

## Debt Composition

### Summary

| Component | Amount (FY2025) | Source |
|-----------|----------------|--------|
| Total Debt | $83,897M | [balance.json: totalDebt] |
| — Short-term debt | $0 | [balance.json: shortTermDebt] |
| — Long-term debt (bonds) | $58,744M | [balance.json: longTermDebt] |
| — Capital leases (current) | $2,213M | [balance.json: capitalLeaseObligationsCurrent] |
| — Capital leases (non-current) | $22,940M | [balance.json: capitalLeaseObligationsNonCurrent] |
| Total capital lease obligations | $25,153M | [balance.json: capitalLeaseObligations] |

### Bond Tranches (Known)

**Offering 1 — May 2023 (~$8.5B total):**
- $1.5B of 4.600% Senior Notes due 2028
- Additional tranches at various maturities
- [claim_verification.json: C061, C064; Verified: SEC 424B2 prospectus dated May 1, 2023]

**Offering 2 — August 2024 ($10.5B total):**
- $2.5B of 4.75% notes due August 2034
- $3.25B of 5.40% notes due 2054
- Additional tranches
- [claim_verification.json: C062; Corroborated: Bloomberg, MarketWatch, Yahoo Finance]

**Offering 3 — November 2025 ($30.0B total, six tranches):**

| Tranche | Amount | Coupon | Maturity |
|---------|--------|--------|----------|
| 1 | $4.0B | 4.200% | 2030 |
| 2 | $4.0B | 4.600% | 2032 |
| 3 | $6.5B | 4.875% | 2035 |
| 4 | $4.5B | 5.500% | 2045 |
| 5 | $6.5B | 5.625% | 2055 |
| 6 | $4.5B | 5.750% | 2065 |

[claim_verification.json: C063; Verified: SEC 8-K filing Oct 30, 2025]

**Maturity profile:** Spans 2028–2065. No bonds mature before 2028. Coupons range from 4.200% to 5.750%.

**Reconciliation note:** Known bond tranches aggregate to approximately $49B ($8.5B + $10.5B + $30.0B). The balance sheet shows $58.7B long-term debt. The ~$9.7B difference may reflect earlier issuances, accrued interest, or other long-term debt not captured in the three known offerings [Data gap: complete maturity schedule requires 10-K Note on Debt].

**Debt market signal:** A Meta bond maturing 08/15/2062 was trading at a 6.43% yield [claim_verification.json: C065, Single-Source: attributed to Public.com bond listing].

### Convertible Securities

No convertible debt outstanding. EDGAR full-text search returned 0 results for Meta Platforms, Inc. convertible indentures [convertible_search.json: no META results].

### Debt Trajectory

| Year | Total Debt ($B) | Net Debt ($B)* | Long-Term Debt ($B) |
|------|---------------|---------------|-------------------|
| FY2018 | $0.5 | Net cash | $0 |
| FY2019 | $10.6 | Net cash | $10.0 |
| FY2020 | $10.7 | Net cash | $10.0 |
| FY2021 | $13.9 | Net cash | $0 |
| FY2022 | $26.6 | $11.9 | $9.9 |
| FY2023 | $37.2 | Net cash | $18.4 |
| FY2024 | $49.1 | $5.2 | $28.8 |
| FY2025 | $83.9 | $48.0 | $58.7 |

*Net debt as reported by FMP (totalDebt − cashAndCashEquivalents). Including short-term investments, FY2025 net debt is $2.3B.

[balance.json: totalDebt, netDebt, longTermDebt]

The $34.8B year-over-year increase in total debt in FY2025 ($49.1B → $83.9B) aligns with the $30.0B November 2025 bond offering plus capital lease growth [Inference: $83.9B − $49.1B = $34.8B] [Sources: balance.json, claim_verification.json C063].

## Cash and Equivalents

| Item | Amount (FY2025) | Source |
|------|----------------|--------|
| Cash & cash equivalents | $35,873M | [balance.json: cashAndCashEquivalents] |
| Short-term investments | $45,719M | [balance.json: shortTermInvestments] |
| **Cash + ST investments** | **$81,592M** | [balance.json: cashAndShortTermInvestments] |
| Long-term investments | $27,524M | [balance.json: longTermInvestments] |
| **Total investments** | **$73,243M** | [balance.json: totalInvestments] |

Q1 2026 end: $81.2B in cash and marketable securities; $58.7B in debt [transcript_segments.json: Susan Li].

## Minority Interest

$0 [balance.json: minorityInterest]

## Enterprise Value

| Computation | Amount | Source |
|------------|--------|--------|
| EV (FY2025-end price $660.09) | $1,712.1B | [enterprise_value.json] |
| EV (current price, compiler net debt) | $1,544.1B | [Computed: $1,541.8B + $2.3B] |
| EV (current price, FMP net debt) | $1,589.8B | [Computed: $1,541.8B + $48.0B] |

## Net Debt / EBITDA

FY2025 EBITDA: $104,548M [income.json: ebitda]

| Method | Net Debt | Net Debt / EBITDA |
|--------|---------|-------------------|
| Compiler formula (totalDebt − cash+ST inv) | $2,305M | 0.02x |
| FMP formula (totalDebt − cash only) | $48,024M | 0.46x |

[balance.json; income.json]

Both ratios indicate low leverage relative to EBITDA. The difference is entirely attributable to the $45.7B in short-term investments.

Gross Debt / EBITDA: 0.80x ($83,897M / $104,548M) [balance.json; income.json].

## Interest Expense Anomaly

FY2025 interest expense is recorded as $0 in income.json [income.json: interestExpense], despite $58.7B in long-term bond debt at coupons of 4.2%–5.75%. FY2024 showed $715M interest expense on $28.8B long-term debt. FY2025 net interest income was $2,656M [income.json: netInterestIncome]. Estimated gross interest expense based on bond coupons: $2B–$4B annually [Inference: rough estimate from known coupon rates and principal amounts] [Sources: claim_verification.json C061–C063]. The gross figure likely nets against the $2.7B interest income [Data gap: requires 10-K].

## Sources

[balance.json], [income.json], [cashflow.json], [enterprise_value.json], [shares_float.json], [quote.json], [info.json], [convertible_search.json], [transcript_segments.json], [claim_verification.json]

# Appendix E: Key Stats — Meta Platforms (META)

## Valuation Metrics (All Computed at Current Price)

| Metric | Value | Computation | Sources |
|--------|-------|-------------|---------|
| Price | $607.38 | — | [quote.json: price] |
| 52-week range | $520.26–$796.25 | — | [quote.json: yearLow, yearHigh] |
| Market Cap | $1,541.8B | — | [quote.json: marketCap] |
| ADV (30d, notional) | $9.4B | avg_volume_30d × price; 15,411,547 × $607.38 | [info.json: averageVolume; technicals.json: adv_30d $9.8B] |
| Avg Volume (30d) | 15,730,215 shares | — | [technicals.json: avg_volume_30d] |
| Trailing P/E | 25.9x | $607.38 / $23.49 FY2025 diluted EPS | [quote.json; income.json: epsDiluted] |
| Forward P/E (FY2026E) | 18.5x | $607.38 / $32.81 consensus EPS | [quote.json; ratings.json: epsAvg 2026] |
| Forward P/E (FY2027E) | 17.4x | $607.38 / $34.89 consensus EPS | [quote.json; ratings.json: epsAvg 2027] |
| EV/EBITDA (trailing) | 14.8x | $1,544.1B EV / $104.5B EBITDA | [quote.json; balance.json; income.json] |
| EV/Revenue (trailing) | 7.7x | $1,544.1B / $201.0B | [quote.json; balance.json; income.json] |
| P/FCF | 33.4x | $1,541.8B / $46.1B | [quote.json; cashflow.json] |
| P/FCF ex-SBC | 60.0x | $1,541.8B / ($46.1B − $20.4B SBC) | [quote.json; cashflow.json] |
| P/Book | 7.1x | $1,541.8B / $217.2B equity | [quote.json; balance.json] |
| Dividend Yield | 0.35% | $2.10 / $607.38 | [info.json: lastDividend; quote.json] |
| Earnings Yield | 3.87% | $23.49 / $607.38 | [income.json; quote.json] |
| FCF Yield | 2.99% | $46.1B / $1,541.8B | [cashflow.json; quote.json] |

**Note on ADV:** info.json reports averageVolume of 15,411,547 shares, giving ADV of $9,361M. technicals.json reports adv_30d of $9,806M and avg_volume_30d of 15,730,215 shares. The discrepancy reflects different averaging windows. Report header uses info.json (averageVolume × price).

## Technical Indicators

| Indicator | Value | Source |
|-----------|-------|--------|
| RSI (14) | 43.8 | [technicals.json: rsi_14] |
| 21d EMA | $618.12 | [technicals.json: ema_21d] |
| 50d SMA | $618.37 | [technicals.json: sma_50d] |
| 200d SMA | $670.24 | [technicals.json: sma_200d] |
| Beta | 1.243 | [info.json: beta] |
| Historical Volatility (annualized) | 36.6% | [options.json: historical_volatility] |

Price ($607.38) is 1.8% below the 50d SMA ($618.37), 9.3% below the 200d SMA ($670.24), and 23.7% below the 52-week high ($796.25). RSI of 43.8 is in neutral territory.

## Profitability Metrics

| Year | Revenue ($B) | Gross Margin | Op Margin | Net Margin | EBITDA Margin | ROIC | ROE |
|------|-------------|-------------|-----------|-----------|---------------|------|-----|
| FY2025 | $201.0 | 82.0% | 41.4% | 30.1% | 52.0% | 20.3% | 27.8% |
| FY2024 | $164.5 | 81.7% | 42.2% | 37.9% | 52.8% | 27.3% | 34.1% |
| FY2023 | $134.9 | 80.8% | 34.7% | 29.0% | 43.8% | 20.9% | 25.5% |
| FY2022 | $116.6 | 78.3% | 24.8% | 19.9% | 32.3% | 14.6%* | 18.5% |
| FY2021 | $117.9 | 80.8% | 39.6% | 33.4% | 46.9% | 26.7%* | 31.5% |

[income.json; ratios.json; metrics.json -- returnOnInvestedCapital, returnOnEquity]
*FY2021-FY2022 ROIC from metrics.json directly.

**FY2025 ROIC computation:** NOPAT = Operating Income ($83,276M) × (1 − Effective Tax Rate 29.6%) = $58,630M. Invested Capital = $288,200M [metrics.json: investedCapital]. ROIC = $58,630M / $288,200M = 20.3%.

**ROIC vs. estimated WACC:** WACC estimated at 10.3% (CAPM: risk-free 4.5%, beta 1.243, ERP 5.0%, after-tax cost of debt ~3.5%, debt/total cap ~5.2%). FY2025 ROIC-WACC spread: +10.0pp [Inference: WACC estimation] [Sources: info.json: beta; balance.json; income.json].

## Cash Flow Metrics

| Year | OCF ($B) | CapEx ($B) | FCF ($B) | FCF Margin | CapEx/Rev | SBC ($B) | SBC/Rev |
|------|----------|-----------|---------|------------|-----------|---------|---------|
| FY2025 | $115.8 | $69.7 | $46.1 | 22.9% | 34.7% | $20.4 | 10.2% |
| FY2024 | $91.3 | $37.3 | $54.1 | 32.9% | 22.6% | $16.7 | 10.1% |
| FY2023 | $71.1 | $27.3 | $43.8 | 32.5% | 20.2% | $14.0 | 10.4% |
| FY2022 | $50.5 | $31.4 | $19.0 | 16.3% | 27.0% | $12.0 | 10.3% |
| FY2021 | $57.7 | $18.6 | $39.1 | 33.2% | 15.7% | $9.2 | 7.8% |

[cashflow.json: operatingCashFlow, capitalExpenditure, freeCashFlow, stockBasedCompensation; income.json: revenue]

**OCF/NI (income quality):** 1.92x in FY2025 [metrics.json: incomeQuality]. OCF significantly exceeds net income due to $20.4B SBC and $18.6B D&A non-cash add-backs.

## Capital Returns

| Year | Buybacks ($B) | Buybacks/NI | Dividends* | Total Return |
|------|-------------|------------|-----------|-------------|
| FY2025 | $26.2 | 43% | ~$5.3B | ~$31.5B |
| FY2024 | $30.1 | 48% | ~$5.5B | ~$35.6B |
| FY2023 | $19.8 | 51% | $0 | $19.8B |
| FY2022 | $28.0 | 120% | $0 | $28.0B |
| FY2021 | $44.5 | 113% | $0 | $44.5B |

[cashflow.json: commonStockRepurchased; income.json: netIncome]

*FY2025 dividend: payout ratio 8.8% × $60.5B NI ≈ $5.3B [ratios.json: dividendPayoutRatio; income.json]. Dividend initiated in early 2024.

## Financial Health Scores

| Score | Value | Source |
|-------|-------|--------|
| Altman Z-Score | 8.08 | [scores.json: altmanZScore] |
| Piotroski Score | 4 of 9 | [scores.json: piotroskiScore] |

Altman Z-Score of 8.08 is well above the 3.0 safe-zone threshold. Piotroski Score of 4 reflects mechanical penalties from: declining ROA (16.5% FY2025 vs. 22.6% FY2024, driven by tax rate swing), declining current ratio, and negative working capital change [Inference: sub-score drivers] [Sources: scores.json, metrics.json].

## Balance Sheet Summary

| Item | FY2025 | Source |
|------|--------|--------|
| Total Assets | $366,021M | [balance.json: totalAssets] |
| PP&E (net) | $196,804M | [balance.json: propertyPlantEquipmentNet] |
| Goodwill | $24,534M | [balance.json: goodwill] |
| Intangible Assets | $0 | [balance.json: intangibleAssets] |
| Total Current Assets | $108,722M | [balance.json: totalCurrentAssets] |
| Total Liabilities | $148,778M | [balance.json: totalLiabilities] |
| Total Equity | $217,243M | [balance.json: totalStockholdersEquity] |
| Retained Earnings | $121,179M | [balance.json: retainedEarnings] |
| Additional Paid-in Capital | $95,793M | [balance.json: additionalPaidInCapital] |
| Current Ratio | 2.6x | $108,722M / $41,836M | [balance.json] |
| Tangible Book Value/Share | $76.44 | [ratios.json: tangibleBookValuePerShare] |

## Greenwald Value Decomposition

**Asset Reproduction Value:**
- Total equity: $217,243M [balance.json]
- Less goodwill: $24,534M [balance.json]
- Less intangible assets: $0 [balance.json]
- **Tangible book value: $192,709M ($76.44/share)**

**Earnings Power Value (no-growth):**
- Normalized net income (FY2025): $60,458M [income.json]
- Estimated WACC: 10.3%
- **EPV = $60,458M / 0.103 = $587B ($231/share)**
- Sensitivity: at 14.5% tax rate (management guidance midpoint), normalized NI ≈ $73.4B, EPV ≈ $712B ($281/share)

**Franchise Value:**
- Market cap: $1,541.8B − EPV: $587B = **Franchise value: $955B (62% of market cap)**

[Inference: these are mechanical calculations, not valuations] [Sources: income.json, balance.json, quote.json, info.json: beta]

## Consensus Estimates

| Year | Revenue Est ($B) | # Analysts | EPS Est | # Analysts | Rev Growth |
|------|-----------------|-----------|---------|-----------|-----------|
| FY2026E | $252.8 | 43 | $32.81 | 41 | +25.8% |
| FY2027E | $301.2 | 44 | $34.89 | 44 | +19.1% |
| FY2028E | $345.5 | 39 | $40.22 | 35 | +14.7% |
| FY2029E | $393.0 | 18 | $48.49 | 13 | +13.8% |
| FY2030E | $465.1 | 4 | N/A | N/A | +18.3% |

[ratings.json: estimates -- revenueAvg, epsAvg, numAnalystsRevenue, numAnalystsEps]

Price target consensus: $821.80 (range $700–$910) [ratings.json: price_target_consensus].

## Sources

[quote.json], [info.json], [income.json], [balance.json], [cashflow.json], [metrics.json], [ratios.json], [technicals.json], [earnings.json], [ratings.json], [scores.json], [enterprise_value.json], [shares_float.json], [options.json], [claim_verification.json]

# Appendix F: Risk Factors — Meta Platforms (META)

## 1. Revenue Model Concentration

Advertising revenue represented $196.17B of $200.97B FY2025 total revenue (97.6%) [income.json: revenue; business_overview.md]. In Q1 2026, advertising was $55.0B of $56.3B (97.7%) [transcript_segments.json: Susan Li]. Non-advertising revenue (FoA Other $885M + Reality Labs $402M = $1.3B quarterly) cannot offset advertising declines.

A 10% decline in advertising revenue from the Q1 2026 annualized run-rate (~$220B) would represent ~$22B in lost revenue [Inference: 10% of ~$220B annualized ad revenue] [Sources: transcript_segments.json, income.json].

## 2. Capex Trajectory and FCF Compression

| Year | Capex ($B) | Capex/Revenue | FCF ($B) | FCF Margin |
|------|-----------|---------------|---------|------------|
| FY2021 | $18.6 | 15.7% | $39.1 | 33.2% |
| FY2022 | $31.4 | 27.0% | $19.0 | 16.3% |
| FY2023 | $27.3 | 20.2% | $43.8 | 32.5% |
| FY2024 | $37.3 | 22.6% | $54.1 | 32.9% |
| FY2025 | $69.7 | 34.7% | $46.1 | 22.9% |
| FY2026E | $125–145B | ~49–57% | TBD | TBD |

[cashflow.json; income.json; transcript_segments.json: guidance]

2026 capex midpoint ($135B) exceeds FY2025 OCF ($115.8B). Additional debt issuance may be required to fund capex, buybacks ($26.2B in FY2025), and dividends (~$5.3B) [Inference: capex exceeds OCF] [Sources: cashflow.json, transcript_segments.json].

Contractual commitments increased by $107B in Q1 2026. These are binding obligations regardless of ROI realization [transcript_segments.json: Susan Li].

## 3. AI Investment ROI Uncertainty

When asked about ROIC signposts, CEO Zuckerberg responded: "I don't think we have a very precise plan for exactly how each product is going to scale month-over-month... The formula for our company has always been build experiences that can get to billions of people and focus on monetizing them once you get to scale" [transcript_segments.json: Mark Zuckerberg, Q&A].

CFO stated: "Our experience so far has been that we have continued to underestimate our compute needs even as we have been ramping capacity significantly" [transcript_segments.json: Susan Li, Q&A]. Optionality: "we can choose to bring it online more slowly or reduce our spending in future years" [transcript_segments.json: Susan Li].

## 4. Regulatory and Litigation Risk

**Youth safety litigation:** "We continue to see scrutiny on youth-related issues and have additional trials scheduled for this year in the U.S., which may ultimately result in a material loss" [transcript_segments.json: Susan Li]. Meta settled the first federal bellwether case (Breathitt County School District, Kentucky) on May 21, 2026; settlement terms not disclosed [news.json]. Aggregate potential liability across hundreds of school district cases is not quantified [Data gap].

**Texas AG lawsuit (May 21, 2026):** Texas Attorney General sued Meta and WhatsApp alleging misleading encryption claims. Meta denied the claims. Financial exposure not quantified [news.json].

**EU regulatory headwinds:** CFO referenced "headwinds in the EU and the U.S. that could significantly impact our business and financial results" without specifics [transcript_segments.json: Susan Li]. Prior EU fines include: €1.2B (May 2023, data transfers), €390M (January 2023, targeted advertising), and €265M (November 2022, data scraping) [Inference: publicly known fines, not in current raw data; should be verified against 10-K risk factors] [Data gap: 10-K not available].

**FTC consent decree (2019):** Meta operates under restrictions from the Cambridge Analytica investigation. Compliance status not available in raw data [Data gap].

**Digital Markets Act (DMA):** Designates Meta as a gatekeeper in the EU, imposing interoperability and data-sharing requirements.

**Management did not provide specific answers to analyst questions on:** (a) 2027 capex outlook, (b) AI glasses unit sales targets. These deflections are noted as informational gaps.

## 5. Technology Disruption Risk

**TikTok/short-form video:** TikTok has 136M–183M U.S. MAU [claim_verification.json: C029, Single-Source]. TikTok competes for user attention and ad budgets. Meta's Reels response has driven engagement gains (+10% time spent QoQ) [transcript_segments.json: Susan Li]. TikTok faces U.S. forced divestiture proceedings (regulatory uncertainty).

**AI-native competitors:** AI-powered search (Google AI Overviews, Perplexity, ChatGPT) could divert user attention. Meta's ads are embedded in social feeds, not web search, making this less directly relevant.

**Open-source AI strategy:** Meta's Llama and Muse model families are partially open-source, allowing competitors to build on Meta's research. Whether this builds or erodes competitive advantage is not yet measurable [Inference: long-term impact uncertain].

## 6. Platform Dependency

Meta's apps run on Apple iOS and Google Android. Both can impose restrictions on data collection, app distribution, or ad tracking. Apple's ATT framework (April 2021) caused Meta's FY2022 revenue to decline 1.1% — the only annual decline in the company's history [income.json]. A similar platform-level restriction could recur.

## 7. Reality Labs Operating Losses

FY2025 Reality Labs operating loss: $19,193M [claim_verification.json: C042, Verified]. FY2025 RL revenue: $2.21B. RL spends approximately $21.4B annually to generate $2.2B in revenue [Inference: RL costs ≈ revenue + operating loss] [Sources: claim_verification.json C042]. Cumulative RL operating losses since 2021 estimated at ~$77B [Inference: approximate sum of annual losses from general knowledge; only FY2025 verified in this dataset] [Data gap: prior-year segment losses require 10-K].

## 8. Effective Tax Rate Volatility

| Year | Pre-Tax Income ($B) | Tax ($B) | Effective Rate |
|------|-------------------|---------|---------------|
| FY2024 | $70.7 | $8.3 | 11.8% |
| FY2025 | $85.9 | $25.5 | 29.6% |
| Q1 2026 | — | — | −23% (reflects $8.03B benefit) |

[income.json; transcript_segments.json: Susan Li]

FY2025's 29.6% rate includes a $15.93B noncash charge (Q3 2025) for capitalized R&D expenditures. Q1 2026's negative rate reflects a partial reversal ($8.03B benefit). Guidance for remaining 2026 quarters: 13%–16% [transcript_segments.json: Susan Li]. The 17.8pp swing between FY2024 (11.8%) and FY2025 (29.6%) reduced GAAP net income by $12.4B relative to a constant rate, obscuring operational improvement.

## 9. Key Person and Governance Risk

Mark Zuckerberg serves as CEO, Chairman, and controls majority voting power through dual-class share structure. He cannot be removed by other shareholders [info.json: description]. Exact voting power percentage unverified [Data gap: proxy statement not available].

## 10. Debt Growth Trajectory

Total debt: $0.5B (FY2018) → $83.9B (FY2025). FY2025 net debt (FMP method): $48.0B, the largest-ever net debt position [balance.json]. Net Debt/EBITDA remains low at 0.46x (FMP method) or 0.02x (compiler method), but the trajectory is rapidly upward. If 2026 capex exceeds OCF growth, additional borrowing is likely.

## 11. Cyclicality

FY2022 demonstrated Meta's vulnerability to advertising downturns: revenue −1.1%, stock declined from ~$384 to ~$88 (approximately −77% peak-to-trough) [income.json; price_history.json approximate]. Beta of 1.243 indicates above-market volatility [info.json: beta].

## 12. Supply Chain Concentration

All three chip suppliers (NVIDIA, Broadcom, AMD) rely on TSMC for advanced-node manufacturing. TSMC CoWoS packaging capacity is constrained through 2027 [claim_verification.json: C014, Corroborated from 4 sources]. HBM memory supply characterized as a crisis [supplier_capacity.md — Single-Source]. This single-foundry dependency creates supply risk for Meta's AI infrastructure buildout.

## Notable Non-Disclosures (Negative Space)

- **Geographic revenue breakdown:** Not disclosed in Q1 2026 earnings call, though peers (Alphabet, Snap) provide regional breakdowns
- **Segment operating income (Q1 2026):** Not disclosed in prepared remarks; FY2025 segment operating income is available only via claim verification of prior filings
- **Customer concentration metrics:** No data on top advertiser revenue share, advertiser retention, or churn
- **Backlog/bookings data:** Not applicable to Meta's business model (ad auction, not order-based)
- **MTIA performance vs. NVIDIA/AMD:** No benchmarks or deployment percentages disclosed
- **TikTok:** Zero mentions in Q1 2026 transcript despite being a direct competitor

## Sources

[income.json], [balance.json], [cashflow.json], [transcript_segments.json], [earnings.json], [claim_verification.json], [news.json], [info.json], [scores.json], [metrics.json], [ratios.json], [supplier_capacity.md], [ecosystem_signals.md], [price_history.json]

# Appendix G: Transcript Highlights — Meta Platforms (META)

**Source:** Q1 2026 Earnings Conference Call, April 29, 2026
**Speakers:** Mark Zuckerberg (CEO), Susan Li (CFO), Kenneth Dorell (VP of IR)
**Transcript file:** transcript_segments.json, transcript.json

---

## Revenue and Financial Performance

**Susan Li (CFO), prepared remarks:**
- "First quarter total revenue was $56.3 billion, up 33% or 29% on a constant currency basis"
- "FoA total revenue was $55.9 billion, up 33% year-over-year. Advertising revenue increased by 33% year-over-year or 29% on a constant currency basis"
- "Other revenue of $885 million was up 74% year-over-year, driven primarily by WhatsApp paid messaging and subscriptions revenue"
- "Reality Labs revenue was $402 million, down 2% year-over-year, driven by lower Quest headset sales partially offset by continued strong growth in AI glasses revenue"
- "Operating income was $22.9 billion, representing a 41% operating margin"

## AI Infrastructure and Capex

**Susan Li (CFO), prepared remarks:**
- "We now expect 2026 capital expenditures, including principal payments on finance leases, to be in the range of $125 billion to $145 billion, increased from our prior expectation of $115 billion to $135 billion"
- "Higher component pricing this year and to a lesser extent, additional data center costs to support future year capacity"
- "Our experience so far has been that we have continued to underestimate our compute needs even as we have been ramping capacity significantly"
- "If we end up not needing as much as we anticipate, we can choose to bring it online more slowly or reduce our spending in future years"

**Mark Zuckerberg (CEO), prepared remarks:**
- "Rolling out more than 1 gigawatt of our own custom silicon that we're developing with Broadcom, as well as significant amount of AMD chips to complement the new NVIDIA systems"
- "Most of that is due to higher component costs, particularly memory pricing"

## Advertising Performance and AI Impact

**Susan Li (CFO), prepared remarks:**
- "Ad impressions increased 19% year-over-year" and "average price per ad increased 12% year-over-year"
- "Lattice modeling and GEM architecture drove more than 6% increase in conversion rates for landing page view ads"
- "Adaptive ranking model... drove an incremental 1.6% increase in off-site conversion rates"
- "More than 8 million advertisers use at least one of our GenAI ad creative tools"
- "Our value optimization suite annual revenue run rate has now surpassed $20 billion, more than doubling year-over-year"
- "Partnership ads annual revenue run rate has more than doubled year-over-year to $10 billion"

## User Engagement

**Susan Li (CFO), prepared remarks:**
- "Family daily active people was 3.56 billion in March, down slightly from December... primarily due to internet outages in Iran and restrictions on WhatsApp in Russia"
- "Total video time increased more than 8% globally in Q1, the largest quarter-over-quarter gain in 4 years"
- "Ranking improvements... drove a 10% lift in Reels time spent"
- "Same-day posts now represent more than 30% of recommended Reels on both Instagram and Facebook, more than double the levels one year ago"
- "Over half a billion people on each of Facebook and Instagram are watching AI translated videos each week"

## AI Products

**Mark Zuckerberg (CEO), prepared remarks:**
- Meta Super Intelligence Labs established; released MuSpark model
- "Meta AI sessions per user increased by double-digit percent" following MuSpark rollout
- "Business AIs on messaging... now have more than 10 million weekly conversations, up from about 1 million at the beginning of the year"
- "Leading app in its category" (referring to Threads)

## Capital Allocation

**Susan Li (CFO), prepared remarks:**
- "We recently shared internally that we plan to reduce the size of our employee base in May"
- "$107 billion step-up in contractual commitments"
- "Multiyear cloud deals... will come online over the course of this year and 2027"
- Q1 2026 end: "$81.2 billion in cash and marketable securities" and "$58.7 billion in debt"

## Tax Rate

**Susan Li (CFO), prepared remarks:**
- Q1 2026 tax rate "favorably impacted by an $8.03 billion tax benefit related to a partial relief of $15.93 billion capitalized R&D expenditure" from Q3 2025
- "Absent this benefit, the Q1 tax rate would have been 14%"
- Guidance for remaining 2026 quarters: "13% to 16% absent any changes to our tax landscape"

## Guidance

**Susan Li (CFO), prepared remarks:**
- Q2 2026 revenue: "$58 billion to $61 billion"
- FY2026 total expenses: "$162 billion to $169 billion" (unchanged from prior guidance)
- FY2026 operating income expected above FY2025 ($83.3B)
- FY2026 capex: $125B–$145B (increased from $115B–$135B)

## Deflected / Non-Answer Responses (Q&A)

**2027 Capex (analyst: Mark Shmulik, Bernstein):**
- Susan Li: "We aren't providing a specific outlook for 2027 CapEx. We are, frankly, undergoing a very dynamic planning process"

**AI Glasses Unit Sales Target (analyst: Youssef Squali, Truist):**
- Susan Li discussed engagement trends and demand for existing lineup but did not provide a unit sales figure or target

**AI Investment ROI (analyst question):**
- Mark Zuckerberg: "I don't think we have a very precise plan for exactly how each product is going to scale month-over-month... The formula for our company has always been build experiences that can get to billions of people and focus on monetizing them once you get to scale"

**VR Strategy:**
- Mark Zuckerberg: "We remain the biggest investors in the VR space across the industry, but we are focused on making our VR business sustainable as we invest more in other areas like AI and glasses"

## Regulatory/Legal Commentary

**Susan Li (CFO), prepared remarks:**
- "We continue to monitor active legal and regulatory matters, including headwinds in the EU and the U.S. that could significantly impact our business and financial results"
- "We continue to see scrutiny on youth-related issues and have additional trials scheduled for this year in the U.S., which may ultimately result in a material loss"

## Attribution Notes

All quotes above are from **management speakers** (Susan Li, CFO, or Mark Zuckerberg, CEO) unless otherwise noted. No analyst assertions are presented as management statements. In the Q&A section, analyst names and firms are identified where they asked questions that received non-specific responses.

## Sources

[transcript_segments.json], [transcript.json], [transcript_competitors.json]

# Appendix H: Source Index — Meta Platforms (META)

**Report Date:** 2026-05-22
**Data Collection Date:** 2026-05-22 (Phase 1 gather)

## Tier 1: SEC Filings and Company Announcements

| File | Provider | Content | Date | Notes |
|------|----------|---------|------|-------|
| filings.json | EDGAR | SEC filing list (10-Q, 10-K, 8-K) | Pulled 2026-05-22 | Lists recent filings; does not contain filing text |
| filing_search.json | EDGAR EFTS | Full-text search for "META 10-K" | Pulled 2026-05-22 | Search results only |
| edgar_search_risks.json | EDGAR EFTS | Full-text search for "META risk factors" | Pulled 2026-05-22 | Search results only |
| convertible_search.json | EDGAR EFTS | Search for "META convertible notes indenture" | Pulled 2026-05-22 | No META results found |
| claim_verification.json | Multiple (Serper, Firecrawl, EDGAR) | 106 web-sourced claims verified against primary sources | 2026-05-22 | 48 Verified, 32 Corroborated, 9 Single-Source, 7 Contradicted, 10 Unverifiable |
| press_releases.md | PRNewswire, BusinessWire | Company press release search results | Pulled 2026-05-22 | Blue Owl JV announcement (Oct 2025) verified |
| company_ir.md | Meta IR (investor.atmeta.com) | IR press release search | Pulled 2026-05-22 | Q4 2025 results reference |
| presentations.json | Meta IR | Investor events and presentations | Pulled 2026-05-22 | Q1 2026 earnings call, shareholder meeting |

**Missing Tier 1 sources (Data gaps):**
- latest_10k.json — Not retrieved. 10-K filing text would provide risk factors, segment operating income, geographic revenue, debt maturity schedules.
- proxy.json — Not retrieved. Proxy would provide executive compensation, governance detail, Zuckerberg voting power percentage.
- facts.json — Not retrieved. XBRL data would provide precise financial metrics.
- filing_events.json — Not retrieved. 8-K material events not reviewed.

## Tier 2: Standardized Financial APIs (FMP)

| File | Provider | Content | Date | Notes |
|------|----------|---------|------|-------|
| info.json | FMP | Company profile, price, market cap, employees | 2026-05-21 | Price as of market close |
| income.json | FMP | Income statements FY2015–FY2025 | Pulled 2026-05-22 | 11 annual periods |
| balance.json | FMP | Balance sheets FY2015–FY2025 | Pulled 2026-05-22 | 11 annual periods |
| cashflow.json | FMP | Cash flow statements FY2015–FY2025 | Pulled 2026-05-22 | 11 annual periods |
| metrics.json | FMP | Key metrics (ROIC, EV, ratios) FY2021–FY2025 | Pulled 2026-05-22 | 5 annual periods |
| ratios.json | FMP | Financial ratios FY2021–FY2025 | Pulled 2026-05-22 | 5 annual periods |
| earnings.json | FMP | Quarterly EPS/revenue actuals vs. estimates | Pulled 2026-05-22 | Q1 2024–Q2 2026E |
| quote.json | FMP | Real-time quote | 2026-05-21 | $607.38 close |
| ratings.json | FMP | Analyst estimates and price targets | Pulled 2026-05-22 | FY2026E–FY2030E |
| enterprise_value.json | FMP | Enterprise value history FY2021–FY2025 | Pulled 2026-05-22 | |
| shares_float.json | FMP/EDGAR | Float shares, outstanding shares | 2026-05-20 | From 10-Q filing |
| technicals.json | FMP | RSI, SMA, EMA, ADV | 2026-05-21 | |
| price_history.json | FMP | Daily prices (1 year) | Through 2026-05-21 | |
| scores.json | FMP | Altman Z-Score, Piotroski Score | Pulled 2026-05-22 | |
| dcf.json | FMP | DCF model output | 2026-05-21 | $278.12 DCF vs. $606.19 price |
| peers.json | FMP | Peer company list | Pulled 2026-05-22 | Contains non-comparable peers |
| peer_compare.json | FMP | Peer company profiles | Pulled 2026-05-22 | |
| insider.json | FMP | Insider transactions | Pulled 2026-05-22 | ~20 transactions, May 2026 only |
| holders.json | FMP/EDGAR | 13F-HR filings | Pulled 2026-05-22 | |
| holders_analytics.json | FMP | Institutional ownership analytics | Pulled 2026-05-22 | Q1 2026 |
| computed_metrics.json | Pipeline | Pre-computed margins and EV | Generated 2026-05-22 | Cross-check values |
| news.json | FMP | Recent news articles | Pulled 2026-05-22 | Texas AG lawsuit, youth-safety settlement |

**FMP API failures (404 errors):**
- segments.json — Segment and geographic revenue unavailable
- short_interest.json — Short interest data unavailable
- options.json — Options chain unavailable (historical vol fallback only)
- dividends.json — Dividend history unavailable
- sector_perf.json — Sector performance unavailable
- government.json — Congressional trading data unavailable

## Tier 3: Earnings Transcripts

| File | Provider | Content | Date | Notes |
|------|----------|---------|------|-------|
| transcript.json | FMP | Full Q1 2026 earnings call transcript | 2026-04-29 | Single-line JSON format |
| transcript_segments.json | FMP | Keyword-matched transcript excerpts | 2026-04-29 | 22 segment/revenue matches |
| transcript_competitors.json | FMP | Competitor keyword matches | 2026-04-29 | 7 competitive mentions |

## Tier 4: Third-Party Research

| File | Provider | Content | Date | Notes |
|------|----------|---------|------|-------|
| ecosystem_signals.md | Multiple (Serper, web-verify) | SNAP, NVDA, GOOGL Q1 2026 signals | Generated 2026-05-22 | Key competitor data |

## Tier 5: Web Search / News / Commentary

| File | Provider | Content | Date | Notes |
|------|----------|---------|------|-------|
| business_overview.md | Serper/Firecrawl | Segment revenue breakdown | Pulled 2026-05-22 | Stock Analysis aggregator |
| segment_financials.md | Serper/Firecrawl | SEC filing and web segment references | Pulled 2026-05-22 | |
| revenue_mix.md | Serper/Firecrawl | Revenue breakdown search | Pulled 2026-05-22 | |
| competitive_by_product.md | Serper/Firecrawl | Competitive landscape by product | Pulled 2026-05-22 | |
| competitive_history.md | Serper/Firecrawl | Market share history | Pulled 2026-05-22 | |
| competitor_data.md | Serper/Firecrawl | Top competitor financials | Pulled 2026-05-22 | |
| customer_alternatives.md | Serper/Firecrawl | Customer switching costs | Pulled 2026-05-22 | |
| customer_capex.md | Serper/Firecrawl | Customer capex guidance | Pulled 2026-05-22 | |
| supply_demand.md | Serper/Firecrawl | Industry supply/demand | Pulled 2026-05-22 | Mostly irrelevant to META |
| supply_indicators.md | Serper/Firecrawl | Capacity utilization indicators | Pulled 2026-05-22 | Generic; zero META-specific data |
| supplier_capacity.md | Serper/Firecrawl | GPU/HBM supply constraints | Pulled 2026-05-22 | TSMC CoWoS, HBM supply data |
| backlog_breakdown.md | Serper/Firecrawl | Backlog/pipeline search | Pulled 2026-05-22 | Not applicable to ad business |
| value_chain.md | Serper/Firecrawl | Value chain / supplier data | Pulled 2026-05-22 | Includes sustainability data |
| convertible_detail.md | Serper/Firecrawl | Convertible debt search | Pulled 2026-05-22 | No convertibles found |
| short_interest.md | Serper/Firecrawl | Short interest web data | Pulled 2026-05-22 | shortsqueeze.com data |
| industry.json | Serper/Firecrawl | Industry market outlook | Pulled 2026-05-22 | |
| company_site_ir.json | Serper | Site-specific IR search | Pulled 2026-05-22 | |

## Claim Verification Summary

| Confidence Level | Count | Treatment in Report |
|-----------------|-------|-------------------|
| Verified | 48 | Cited normally |
| Corroborated | 32 | Cited with corroboration note |
| Single-Source | 9 | Cited with caveat |
| Contradicted | 7 | All versions presented |
| Unverifiable | 10 | Omitted or noted with explicit caveat |

[claim_verification.json: summary statistics]

## Sources NOT Available

- latest_10k.json (10-K filing text)
- proxy.json (DEF 14A proxy statement)
- facts.json (XBRL concept data)
- filing_events.json (8-K material events)
- insider_detail.json (Form 4 detailed transactions)
- holders_detail.json (13F position details)
- Options chain data (put/call ratio, implied volatility)
- Congressional trading data
- Dividend history detail
- Segment and geographic revenue via FMP API
