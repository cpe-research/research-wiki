---
type: company
ticker: AAPL
name: Apple Inc.
sector: Technology
industry: Consumer Electronics
country: US
updated: "2026-05-31"
sources:
  - info.json
  - value_chain.md
  - segments.json
  - insider.json
  - holders.json
---

# Apple Inc. (AAPL)

## Overview

- **Sector:** Technology
- **Industry:** Consumer Electronics
- **Country:** US
- **Website:** https://www.apple.com

## Competitors

- [Samsung Electronics](SSNLF.md) (SSNLF)
- [Microsoft](MSFT.md) (MSFT)
- [Alphabet](GOOGL.md) (GOOGL)
- [Amazon](AMZN.md) (AMZN)
- [Sony Group](SONY.md) (SONY)
- [Meta Platforms](META.md) (META)

## Key Insiders

- Borders Ben (officer: Principal Accounting Officer)
- LEVINSON ARTHUR D (director)
- O'BRIEN DEIRDRE (officer: Senior Vice President)
- Parekh Kevan (officer: Senior Vice President, CFO)

## Top Institutional Holders

- Axiom Investment Management LLC
- BERKSHIRE HATHAWAY INC  (BRK-A, BRK-B)
- Blankinship & Foster, LLC
- BlueMountain Capital Management, LLC
- BSN Capital Partners Ltd
- CHILDRESS CAPITAL ADVISORS, LLC
- COLUMBIA CAPITAL LLC
- First Trust Investment Solutions L.P.
- Foresight Wealth Management, LLC
- Founders Financial Alliance, LLC

---

> **⚠️ DRAFT — this report did not pass the citation audit.** Some claims may lack source verification. Treat as preliminary research.

# Apple Inc. (AAPL) Research Compilation

Scope: this report compiles four independent analyses and raw workspace files for AAPL as of 2026-05-14, the quote and technical-data date in the workspace [File: raw/quote.json -- timestamp; File: raw/technicals.json -- date]. It does not contain an investment recommendation.

## Cross-Reference Check

- Market-share data: `analysis/competitive_position.md` states that reliable segment market-share data is not available locally and treats CSIMarket 14.91% company share and a Henry Fund/PDF U.S. PC share claim as [Single-Source] [File: analysis/competitive_position.md -- Market Share; File: raw/claim_verification.json -- C025/C029]. No other analysis supplies verified segment share, so the report does not state a verified company rank by share.
- Mobile OS share: `analysis/competitive_position.md` states a U.S. mobile OS share claim of 58.1% for Apple and 41.6% for Android is [Contradicted] because methods and geographies differ across sources [File: analysis/competitive_position.md -- Market Share; File: raw/claim_verification.json -- C067]. This report presents that as a disputed web claim, not as established share.
- Geography disclosure: `analysis/value_chain.md` cites 2025 10-K geography sales of Americas $178.353B, Europe $111.032B, Greater China $64.377B, Japan $28.703B, and Rest of Asia Pacific $33.696B [File: analysis/value_chain.md -- Value Chain Map]. `analysis/risk_factors.md` states the configured FMP segment/geography endpoint returned no geography data [File: analysis/risk_factors.md -- Regulatory/Geopolitical; File: raw/segments.json -- geography_message]. These statements use different sources: EDGAR excerpt versus FMP endpoint.
- Net cash/debt timing: `analysis/financial_data.md` states FY2025 balance-sheet net debt was $76.443B [File: raw/balance.json -- netDebt]. The same analysis states management later said Q1 FY2026 ended with $145B cash and marketable securities, $91B total debt, and $54B net cash [File: analysis/financial_data.md -- Capital Structure; File: raw/transcript.json -- Kevan Parekh]. These are different period measurements.
- Customer concentration: `analysis/risk_factors.md` states no raw file discloses top-customer revenue concentration [File: analysis/risk_factors.md -- Customer Concentration]. `analysis/value_chain.md` states a Q1 FY2026 10-Q search snippet referenced two customers at 15% and 10% of trade receivables, not revenue [File: analysis/value_chain.md -- Downstream: Customers]. The denominator differs: trade receivables versus net sales.
- Peer-set correction: `raw/peers.json` contains GOOGL / Alphabet Inc., META / Meta Platforms, Inc., MSFT / Microsoft Corporation, NVDA / NVIDIA Corporation, NXT / Nextpower Inc., RIME / Algorhythm Holdings, Inc., SONY / Sony Group Corporation, TBCH / Turtle Beach Corporation, and TSM / Taiwan Semiconductor Manufacturing Company Limited; it does not contain Dell, Intel, IBM, HP, Super Micro Computer, or NetApp [File: raw/peers.json -- symbol, companyName].

## Competitive Position
<!-- IC question: Where does Apple rank vs peers, and is its position improving or deteriorating? Evidence that would change the answer: verified segment share by product/geography, loss of a top customer, entry of a well-capitalized competitor, or technology disruption that nullifies current advantages. Base-rate consideration: the workspace does not include a multi-year peer rank-transition dataset. -->

Apple is classified as Technology / Consumer Electronics, and its disclosed scope includes iPhone, Mac, iPad, wearables/accessories, App Store distribution, cloud services, advertising, licensing, AppleCare, and subscriptions [File: raw/info.json -- sector, industry, description]. FY2025 revenue was $416.161B, up 6.43% from FY2024, with FY2021-FY2025 revenue CAGR of 3.28% [File: raw/income.json -- revenue; Calculation: income.json].

Verified segment market share is unavailable in the raw files [File: raw/segments.json -- segments_message, geography_message]. The CSIMarket company-share claim of 14.91% and the U.S. PC share claim of about 16% are [Single-Source] claims, so they are not used as established rank data [File: raw/competitive_history.md -- results; File: raw/claim_verification.json -- C025/C029]. The U.S. mobile OS share claim of 58.1% for Apple versus 41.6% for Android is [Contradicted]; claim verification states geography and methodology differ across sources [File: raw/supply_demand.md -- results; File: raw/claim_verification.json -- C067].

Porter observations: Apple spent $34.550B on R&D in FY2025, 8.3% of revenue, and employed 164,000 people [File: raw/income.json -- researchAndDevelopmentExpenses, revenue; File: raw/info.json -- fullTimeEmployees]. Apple’s supply chain includes thousands of supplier facilities in over 60 countries [Verified: File: raw/claim_verification.json -- C020]. Apple publishes a supplier list covering at least 98% of direct spend [Verified: File: raw/claim_verification.json -- C019]. Apple distributes through direct stores/online/direct channels and through carriers, wholesalers, retailers, and other third-party channels [File: raw/info.json -- description; File: analysis/value_chain.md -- Markets and Distribution].

Key competitors cannot be reduced to one peer set from the local files. The FMP peer file lists GOOGL / Alphabet Inc., META / Meta Platforms, Inc., MSFT / Microsoft Corporation, NVDA / NVIDIA Corporation, NXT / Nextpower Inc., RIME / Algorhythm Holdings, Inc., SONY / Sony Group Corporation, TBCH / Turtle Beach Corporation, and TSM / Taiwan Semiconductor Manufacturing Company Limited [File: raw/peers.json -- symbol, companyName]. A Motley Fool list naming Samsung, Google, Microsoft, and Amazon is [Single-Source] and not treated as a verified top-competitor list [File: raw/claim_verification.json -- C049].

## Supply/Demand Balance
<!-- IC question: Is industry supply sufficient to meet demand at current prices, and when does that change? Evidence that would change the answer: major capacity announcements, demand shocks, tariff/subsidy changes, verified channel-through/unit data, or management stating supply-demand balance. Base-rate consideration: the workspace does not include a dataset on typical consumer-electronics imbalance duration. -->

Management said Q1 FY2026 revenue was $143.8B, up 16% year over year; iPhone revenue was $85.3B, up 23%; Services revenue was up 14%; and Greater China grew 38% [File: raw/transcript.json -- Timothy Cook prepared remarks]. Management also said March-quarter revenue was expected to grow 13%-16% year over year and included constrained iPhone supply [File: raw/transcript.json -- Kevan Parekh prepared remarks].

Supply data are transcript-level rather than unit-level. Tim Cook said Apple was in “supply chase mode,” was “currently constrained,” and could not predict when supply and demand would balance; he attributed the constraint to availability of advanced nodes for Apple SoCs [File: raw/transcript.json -- Amit Daryanani Q&A / Timothy Cook response]. [Inference: the latest transcript documents an iPhone supply constraint rather than balanced supply because management explicitly described current constraints and unavailable timing for balance.] [Sources: raw/transcript.json -- Amit Daryanani Q&A / Timothy Cook response].

Pricing dynamics: Tim Cook said memory market pricing was “increasing significantly,” had minimal Q1 FY2026 gross-margin effect, and would have more Q2 effect inside the 48%-49% gross-margin guide [File: raw/transcript.json -- Timothy Cook response]. Product ASPs, channel inventory by units, capacity utilization, backlog, and verified shipment shares are not disclosed in the local files [File: raw/segments.json -- segments_message; File: analysis/competitive_position.md -- Data Gaps].

## Value Chain
<!-- IC question: Where is value captured, and is it migrating toward or away from Apple? Evidence that would change the answer: vertical integration by customers/suppliers, margin compression at Apple’s chain position, or technology enabling disintermediation. Base-rate consideration: the workspace does not include a multi-year value-chain migration dataset. -->

The chain map in the value-chain analysis is: raw inputs and components -> Apple-controlled hardware/software/silicon design -> outsourced manufacturing/assembly -> direct and indirect distribution -> consumers, SMB, education, enterprise and government customers -> services and developer/content ecosystem [File: analysis/value_chain.md -- Value Chain Map]. Apple’s 2025 10-K states a significant majority of manufacturing is performed in whole or in part by outsourcing partners located primarily in China mainland, India, Japan, South Korea, Taiwan, and Vietnam [EDGAR: 2025 10-K excerpt in analysis/value_chain.md -- manufacturing outsourcing].

FY2025 net revenue by category was iPhone $209.586B (50.4%), Services $109.158B (26.2%), Wearables/Home/Accessories $35.686B (8.6%), Mac $33.708B (8.1%), and iPad $28.023B (6.7%) [File: analysis/value_chain.md -- net revenue by category; File: raw/income.json -- revenue; Calculation: category revenue / $416.161B]. FY2025 distribution was 40% direct and 60% indirect, or about $166.5B direct and $249.7B indirect on $416.161B total revenue [File: analysis/value_chain.md -- Markets and Distribution; File: raw/income.json -- revenue; Calculation].

Apple’s FY2025 gross margin was 46.9%, operating margin was 32.0%, and Services gross margin was 74.0% versus Products gross margin of 38.5% according to the 10-K excerpt cited in the value-chain analysis [File: raw/ratios.json -- grossProfitMargin/operatingProfitMargin; EDGAR: 2025 10-K excerpt in analysis/value_chain.md -- product/services gross margin]. [Inference: Services captures higher gross margin per revenue dollar than Products because the cited Services gross margin exceeds the cited Products gross margin by 35.5 percentage points.] [Sources: EDGAR: 2025 10-K excerpt in analysis/value_chain.md -- product/services gross margin].

Dependencies include advanced-node SoCs, memory, cover glass, outsourced assembly, and app/platform regulation [File: analysis/value_chain.md -- Upstream: Suppliers; File: analysis/risk_factors.md -- Technology Disruption, Regulatory/Geopolitical].

## Capital Structure
<!-- IC question: How is Apple funded, and what are its financial obligations? Evidence that would change the answer: major debt issuance/repayment, M&A financing, credit-rating change, or convertible conversion. Base-rate consideration: N/A. -->

| Item | Amount | Source |
| --- | ---: | --- |
| Market cap | $4.380T | [File: raw/quote.json -- marketCap] |
| Cash & equivalents | $35.934B | [File: raw/balance.json -- cashAndCashEquivalents] |
| Cash + short-term investments | $54.697B | [File: raw/balance.json -- cashAndShortTermInvestments] |
| Short-term debt | $20.329B | [File: raw/balance.json -- shortTermDebt] |
| Long-term debt | $78.328B | [File: raw/balance.json -- longTermDebt] |
| Capital lease obligations | $13.720B | [File: raw/balance.json -- capitalLeaseObligations] |
| Total debt | $112.377B | [File: raw/balance.json -- totalDebt] |
| Net debt | $76.443B | [File: raw/balance.json -- netDebt] |
| Minority interest | $0 | [File: raw/balance.json -- minorityInterest] |
| Current enterprise value | $4.456T | [Inference: market cap + total debt - cash] [File: raw/quote.json -- marketCap; File: raw/balance.json -- totalDebt, cashAndCashEquivalents] |
| Total assets | $359.241B | [File: raw/balance.json -- totalAssets] |
| Total equity | $73.733B | [File: raw/balance.json -- totalEquity] |

Gross debt was 31.3% of FY2025 total assets [Inference: totalDebt / totalAssets] [Sources: raw/balance.json -- totalDebt, totalAssets]. FY2025 operating cash flow was $111.482B, equal to 0.99x FY2025 total debt [Inference: operating cash flow / total debt] [Sources: raw/cashflow.json -- operatingCashFlow; raw/balance.json -- totalDebt]. `convertible_search.json` did not provide conversion prices, conversion ratios, or dilutive-share terms for a convertible instrument [File: raw/convertible_search.json -- query/results]. A note maturity claim for Apple 2022, 2024, 2026, and 2029 Notes maturing on September 11 of those years is [Verified] against an SEC prospectus supplement [File: raw/claim_verification.json -- C069].

## Key Stats
<!-- IC question: What does the market currently price, and how does it compare to historical patterns? Evidence that would change the answer: significant price move, multiple expansion/compression, technical breakout/breakdown, or updated financial statements. Base-rate consideration: historical multiple range is available only from the annual FMP metric series in the workspace. -->

| Metric | Value | Source |
| --- | ---: | --- |
| Price | $298.21 | [File: raw/quote.json -- price] |
| 52-week range | $193.46-$300.92 | [File: raw/quote.json -- yearLow/yearHigh] |
| Volume | 33.673M shares | [File: raw/quote.json -- volume] |
| 30d average volume | 48.458M shares | [File: raw/technicals.json -- avg_volume_30d] |
| 30d ADV | $13.462B | [File: raw/technicals.json -- adv_30d] |
| RSI (14) | 74.48 | [File: raw/technicals.json -- rsi_14] |
| 21d EMA | $281.42 | [File: raw/technicals.json -- ema_21d] |
| 50d SMA | $265.39 | [File: raw/technicals.json -- sma_50d] |
| 200d SMA | $258.68 | [File: raw/technicals.json -- sma_200d] |
| Trailing P/E | 39.97x | [Inference: price / FY2025 diluted EPS] [File: raw/quote.json -- price; File: raw/income.json -- epsDiluted] |
| Forward P/E FY2026 estimate | 34.25x | [Inference: price / FY2026 epsAvg] [File: raw/quote.json -- price; File: raw/ratings.json -- estimates FY2026 epsAvg] |
| Current EV/Revenue | 10.71x | [Inference: current EV / FY2025 revenue] [File: raw/quote.json; File: raw/balance.json; File: raw/income.json] |
| Current EV/EBITDA | 30.86x | [Inference: current EV / FY2025 EBITDA] [File: raw/quote.json; File: raw/balance.json; File: raw/income.json] |
| P/FCF | 44.35x | [Inference: market cap / FY2025 FCF] [File: raw/quote.json -- marketCap; File: raw/cashflow.json -- freeCashFlow] |
| Dividend yield (FMP) | 0.404% | [File: raw/ratios.json -- dividendYieldPercentage] |

Short interest: Finviz reported 134.68M shares short, 14.67B shares float, 0.92% short float, and 2.99 short ratio for settlement date Apr. 30, 2026; claim verification tags this [Corroborated] because Benzinga independently reported 134.68M shares and 0.92% short float [File: raw/short_interest.md -- Finviz snippet; File: raw/claim_verification.json -- C036]. Days-to-cover values differ across MarketBeat 2.9, ORTEX 2.97, The Online Investor 2.25, and Finviz 2.99 [File: raw/claim_verification.json -- C035/C036/C037/C038].

## Risk Factors
<!-- IC question: What specific events could materially alter Apple’s financial performance? Evidence that would change the answer: new regulation, customer concentration change, supply-chain disruption, executive departure, refinancing change, or updated filings. Base-rate consideration: the workspace does not include a decade-long peer event-frequency dataset for each risk. -->

Customer concentration: no provided raw file discloses top-1, top-5, or top-10 customer revenue concentration, and no raw file states that any customer exceeds 10% of net sales [File: analysis/risk_factors.md -- Customer Concentration; File: raw/segments.json -- segments_message]. A Q1 FY2026 10-Q search snippet cited two customers at 15% and 10% of trade receivables; that is not revenue concentration [File: analysis/value_chain.md -- Downstream: Customers].

Regulatory/geopolitical exposure: the Q1 FY2026 call safe-harbor language named macroeconomic conditions, tariffs and other measures, and legal and regulatory proceedings [File: raw/transcript.json -- Suhasini Chandramouli]. FY2025 geography sales were Americas $178.353B, Europe $111.032B, Greater China $64.377B, Japan $28.703B, and Rest of Asia Pacific $33.696B [EDGAR: 2025 10-K excerpt in analysis/value_chain.md -- net sales by reportable segment].

Supply-chain dependencies: Apple’s 2025 10-K states certain components are obtained from single or limited sources and new products often use custom components available from only one source [EDGAR: 2025 10-K excerpt in analysis/value_chain.md -- Supply of Components risk factor]. Management specifically cited advanced-node SoC supply constraints and memory price increases in Q1 FY2026 Q&A [File: raw/transcript.json -- Timothy Cook responses].

Insider activity: `raw/insider.json` lists 20 Form 4 transactions, with the latest filing dated 2026-05-12 for Ben Borders, Principal Accounting Officer, showing a sale of 1,274 common shares at $290 and 38,713 securities owned after the transaction [File: raw/insider.json -- filingDate, reportingName, transactionType, securitiesTransacted, price, securitiesOwned].

Accounting/cash-flow observations: FY2025 net income was $112.010B; operating cash flow was $111.482B; free cash flow was $98.767B; and working capital used $25.000B of cash [File: raw/income.json -- netIncome; File: raw/cashflow.json -- operatingCashFlow, freeCashFlow, changeInWorkingCapital]. [Inference: FY2025 FCF was below FY2024 FCF while FY2025 revenue was above FY2024 revenue because OCF declined and working capital moved from a cash source in FY2024 to a cash use in FY2025.] [Sources: raw/income.json -- revenue; raw/cashflow.json -- operatingCashFlow, freeCashFlow, changeInWorkingCapital].

Debt/refinancing exposure: FY2025 total debt was $112.377B, including $20.329B short-term debt and $78.328B long-term debt [File: raw/balance.json -- totalDebt, shortTermDebt, longTermDebt]. Convertible terms are a data gap because conversion prices, ratios, and dilutive-share terms were not located [File: raw/convertible_search.json -- query/results].

Notable non-disclosures: verified product-unit shipments, ASPs, backlog, design wins, capacity utilization, customer revenue concentration, churn, and segment/geography endpoint data are unavailable in the local raw files [File: raw/segments.json -- segments_message, geography_message; File: analysis/competitive_position.md -- Data Gaps; File: analysis/risk_factors.md -- Data Gaps].

## Discrepancies, Data Gaps, and Inference-Dependent Claims

Discrepancies are listed in the Cross-Reference Check. Data gaps include verified segment market share, product-unit shipments, ASPs, customer revenue concentration, backlog, capacity utilization, peer base-rate datasets, and convertible conversion terms [File: raw/segments.json; File: raw/convertible_search.json; File: analysis/* -- Data Gaps]. Inference-dependent calculations in this report are marked inline with `[Inference: ...] [Sources: ...]`.

## Source Index

See `appendix/H_source_index.md` for the complete source list and reliability tiers.

---

## Appendix

# Appendix A: Competitive Position

Apple's verified local data support company scale but not verified segment share. FY2025 revenue was $416.161B, FY2025 R&D was $34.550B, and employee count was 164,000 [File: raw/income.json -- revenue, researchAndDevelopmentExpenses; File: raw/info.json -- fullTimeEmployees]. Segment market-share snippets are caveated: CSIMarket 14.91% company share is [Single-Source] [File: raw/claim_verification.json -- C025], U.S. PC share around 16% is [Single-Source] [File: raw/claim_verification.json -- C029], and U.S. mobile OS share of 58.1% versus Android 41.6% is [Contradicted] [File: raw/claim_verification.json -- C067].

Porter's Five Forces facts are: high observed Apple scale in R&D and headcount; supplier breadth of thousands of facilities in over 60 countries [Verified: raw/claim_verification.json -- C020]; supplier list coverage of at least 98% of direct spend [Verified: raw/claim_verification.json -- C019]; direct and indirect distribution; and a peer set that varies by product category rather than a single verified competitor list [File: raw/peers.json -- symbol, companyName; File: raw/info.json -- description].

The FMP peer file lists GOOGL / Alphabet Inc., META / Meta Platforms, Inc., MSFT / Microsoft Corporation, NVDA / NVIDIA Corporation, NXT / Nextpower Inc., RIME / Algorhythm Holdings, Inc., SONY / Sony Group Corporation, TBCH / Turtle Beach Corporation, and TSM / Taiwan Semiconductor Manufacturing Company Limited [File: raw/peers.json -- symbol, companyName]. A Motley Fool list naming Samsung, Google, Microsoft, and Amazon is [Single-Source] and is not treated as a verified top-competitor list [File: raw/claim_verification.json -- C049].

Competition evolution in the provided files is a timeline of revenue and product-cycle facts rather than verified share migration: FY2021-FY2025 revenue rose from $365.817B to $416.161B [File: raw/income.json -- revenue]. Latest transcript data include Q1 FY2026 revenue of $143.8B, iPhone revenue of $85.3B, and Services growth of 14% year over year [File: raw/transcript.json -- Timothy Cook].

Notable non-disclosures: verified segment share, unit shipments, ASPs, installed-base churn, and a peer rank-transition dataset are unavailable [File: raw/segments.json; File: analysis/competitive_position.md -- Data Gaps].

# Appendix B: Supply/Demand Balance

Management reported Q1 FY2026 revenue of $143.8B, up 16% year over year, iPhone revenue of $85.3B, up 23%, and Services revenue up 14% [File: raw/transcript.json -- Timothy Cook]. March-quarter revenue guidance was 13%-16% year-over-year growth and included constrained iPhone supply [File: raw/transcript.json -- Kevan Parekh].

Tim Cook said Apple was in “supply chase mode,” was “currently constrained,” could not predict when supply and demand would balance, and cited availability of advanced nodes for Apple SoCs [File: raw/transcript.json -- Amit Daryanani Q&A / Timothy Cook response]. [Inference: this points to supply below demand for affected iPhone models because management used current-constraint language and declined to give a balance date.] [Sources: raw/transcript.json -- Amit Daryanani Q&A / Timothy Cook response].

Input-cost data: Tim Cook said memory pricing was “increasing significantly,” with minimal Q1 margin impact and more Q2 impact inside gross-margin guidance of 48%-49% [File: raw/transcript.json -- Timothy Cook response].

Data gaps: product-level demand, unit shipments, ASPs, backlog, capacity utilization, and historical imbalance duration are not disclosed in the local files [File: raw/segments.json; File: analysis/competitive_position.md -- Supply/Demand Balance].

# Appendix C: Value Chain

Value chain map: raw inputs/components -> Apple-controlled design/platform/silicon -> outsourced manufacturing/assembly -> direct and indirect distribution -> end customers -> services/developer/content ecosystem [File: analysis/value_chain.md -- Value Chain Map]. Apple’s 2025 10-K states a significant majority of manufacturing is performed by outsourcing partners located primarily in China mainland, India, Japan, South Korea, Taiwan, and Vietnam [EDGAR: 2025 10-K excerpt in analysis/value_chain.md].

Upstream: Apple reports thousands of supplier facilities in over 60 countries [Verified: raw/claim_verification.json -- C020] and supplier-list coverage of at least 98% of direct spend [Verified: raw/claim_verification.json -- C019]. Certain components are obtained from single or limited sources, and new products often use custom components available from only one source [EDGAR: 2025 10-K excerpt in analysis/value_chain.md -- Supply of Components].

Downstream: Apple distributes to consumers, SMB, education, enterprise, and government markets through retail stores, online stores, direct channels, carriers, wholesalers, retailers, and other third-party channels [File: raw/info.json -- description; File: analysis/value_chain.md -- Markets and Distribution]. FY2025 direct distribution was 40% of revenue and indirect distribution was 60% [File: analysis/value_chain.md -- Markets and Distribution].

Margin capture: FY2025 gross margin was 46.9% and operating margin was 32.0% [File: raw/ratios.json -- grossProfitMargin, operatingProfitMargin]. The value-chain analysis cites 2025 Products gross margin of 38.5% and Services gross margin of 74.0% [EDGAR: 2025 10-K excerpt in analysis/value_chain.md]. [Inference: per-dollar gross margin was higher in Services than Products by 35.5 percentage points.] [Sources: EDGAR: 2025 10-K excerpt in analysis/value_chain.md].

Dependencies and vulnerabilities: advanced-node SoCs, memory, outsourced manufacturing geographies, App Store/platform rules, and distributor relationships [File: analysis/value_chain.md -- Dependencies and Vulnerabilities].

# Appendix D: Capital Structure

| Item | Exact value | Display | Source |
| --- | ---: | ---: | --- |
| Cash and equivalents | 35934000000 | $35.934B | [File: raw/balance.json -- cashAndCashEquivalents] |
| Short-term investments | 18763000000 | $18.763B | [File: raw/balance.json -- shortTermInvestments] |
| Cash + short-term investments | 54697000000 | $54.697B | [File: raw/balance.json -- cashAndShortTermInvestments] |
| Goodwill | 0 | $0 | [File: raw/balance.json -- goodwill] |
| Intangible assets | 0 | $0 | [File: raw/balance.json -- intangibleAssets] |
| Total assets | 359241000000 | $359.241B | [File: raw/balance.json -- totalAssets] |
| Short-term debt | 20329000000 | $20.329B | [File: raw/balance.json -- shortTermDebt] |
| Long-term debt | 78328000000 | $78.328B | [File: raw/balance.json -- longTermDebt] |
| Capital leases | 13720000000 | $13.720B | [File: raw/balance.json -- capitalLeaseObligations] |
| Total debt | 112377000000 | $112.377B | [File: raw/balance.json -- totalDebt] |
| Net debt | 76443000000 | $76.443B | [File: raw/balance.json -- netDebt] |
| Total liabilities | 285508000000 | $285.508B | [File: raw/balance.json -- totalLiabilities] |
| Total equity | 73733000000 | $73.733B | [File: raw/balance.json -- totalEquity] |
| Minority interest | 0 | $0 | [File: raw/balance.json -- minorityInterest] |
| Current market cap | 4379916432760 | $4.380T | [File: raw/quote.json -- marketCap] |
| Current EV | 4456359432760 | $4.456T | [Inference: market cap + total debt - cash] [Sources: raw/quote.json; raw/balance.json] |

Cash-flow coverage: FY2025 operating cash flow of $111.482B equals 0.99x FY2025 total debt of $112.377B [Inference: operating cash flow / total debt] [Sources: raw/cashflow.json -- operatingCashFlow; raw/balance.json -- totalDebt]. FY2025 free cash flow was $98.767B; capex was $12.715B; and common stock repurchases were $90.711B [File: raw/cashflow.json -- freeCashFlow, capitalExpenditure, commonStockRepurchased].

Convertible debt: conversion prices, conversion ratios, and dilutive-share terms were not located in `raw/convertible_search.json` [File: raw/convertible_search.json -- query/results]. Note maturity claims for 2022, 2024, 2026, and 2029 Notes maturing September 11 are [Verified] in claim verification [File: raw/claim_verification.json -- C069].

# Appendix E: Key Stats and Methodology

All multiples below are recalculated at the 2026-05-14 quote where inputs permit.

| Metric | Calculation | Value | Source |
| --- | --- | ---: | --- |
| Price | FMP quote | $298.21 | [File: raw/quote.json -- price] |
| Market cap | FMP quote | $4.380T | [File: raw/quote.json -- marketCap] |
| RSI 14 | FMP technical API | 74.48 | [File: raw/technicals.json -- rsi_14] |
| EMA 21d | FMP technical API | $281.42 | [File: raw/technicals.json -- ema_21d] |
| SMA 50d | FMP technical API | $265.39 | [File: raw/technicals.json -- sma_50d] |
| SMA 200d | FMP technical API | $258.68 | [File: raw/technicals.json -- sma_200d] |
| ADV 30d | FMP technical API | $13.462B | [File: raw/technicals.json -- adv_30d] |
| Avg volume 30d | FMP technical API | 48.458M | [File: raw/technicals.json -- avg_volume_30d] |
| Trailing P/E | $298.21 / $7.46 diluted EPS | 39.97x | [Inference: recalculated] [Sources: raw/quote.json; raw/income.json] |
| Forward P/E | $298.21 / $8.70725 FY2026 epsAvg | 34.25x | [Inference: recalculated] [Sources: raw/quote.json; raw/ratings.json] |
| EV/Revenue | $4.456T / $416.161B | 10.71x | [Inference: recalculated] [Sources: raw/quote.json; raw/balance.json; raw/income.json] |
| EV/EBITDA | $4.456T / $144.427B | 30.86x | [Inference: recalculated] [Sources: raw/quote.json; raw/balance.json; raw/income.json] |
| P/FCF | $4.380T / $98.767B | 44.35x | [Inference: recalculated] [Sources: raw/quote.json; raw/cashflow.json] |

Earnings differences computed from `raw/earnings.json` actual minus estimate:

| Date | EPS difference | Revenue difference |
| --- | ---: | ---: |
| 2026-04-30 | $0.06 | $1.726B |
| 2026-01-29 | $0.18 | $5.365B |
| 2025-10-30 | $0.12 | $238.900M |
| 2025-07-31 | $0.13 | $4.473B |
| 2025-05-01 | $0.02 | $816.820M |
| 2025-01-30 | $0.04 | $42.600M |
| 2024-10-31 | $0.04 | $418.050M |
| 2024-08-01 | $0.06 | $1.296B |
| 2024-05-02 | $0.02 | $386.890M |

Short interest web data: Finviz/Benzinga 134.68M shares short and 0.92% short float is [Corroborated] [File: raw/claim_verification.json -- C036]. Days-to-cover values are disputed across cited web sources [File: raw/claim_verification.json -- C035/C036/C037/C038].

# Appendix F: Risk Factor Enumeration

- Customer/revenue concentration: no raw file provides top-customer revenue concentration or states whether any customer exceeds 10% of revenue [File: analysis/risk_factors.md -- Customer Concentration]. Receivables concentration snippets are not revenue concentration [File: analysis/value_chain.md -- Downstream: Customers].
- Cyclicality: annual revenue was $416.161B in FY2025, $391.035B in FY2024, $383.285B in FY2023, $394.328B in FY2022, $365.817B in FY2021, and $274.515B in FY2020 [File: raw/income.json -- revenue].
- Technology: Apple product categories include iPhone, Mac, iPad, wearables/accessories, App Store, cloud, AppleCare, advertising, licensing, and subscriptions [File: raw/info.json -- description]. Advanced-node SoC availability constrained iPhone supply in Q1 FY2026 Q&A [File: raw/transcript.json -- Timothy Cook].
- Regulatory/geopolitical: call safe-harbor language named macroeconomic conditions, tariffs and other measures, and legal/regulatory proceedings [File: raw/transcript.json -- Suhasini Chandramouli]. FY2025 Greater China sales were $64.377B, 15.5% of total sales [EDGAR: 2025 10-K excerpt in analysis/value_chain.md].
- Supply chain: supplier facilities span over 60 countries [Verified: raw/claim_verification.json -- C020], and certain components are single- or limited-source [EDGAR: 2025 10-K excerpt in analysis/value_chain.md].
- Insider activity: latest listed transaction is Ben Borders, Principal Accounting Officer, sale of 1,274 shares at $290, filing date 2026-05-12 [File: raw/insider.json -- first record].
- Accounting quality: FY2025 net income was $112.010B, OCF was $111.482B, FCF was $98.767B, and working capital used $25.000B of cash [File: raw/income.json -- netIncome; File: raw/cashflow.json].
- Debt/refinancing: total debt was $112.377B, short-term debt $20.329B, long-term debt $78.328B, and capital lease obligations $13.720B [File: raw/balance.json].

Base-rate data gaps: the workspace does not contain peer event-frequency data for customer concentration, disruption, regulation, supply-chain interruptions, executive transitions, or refinancing events [File: raw/_manifest.json -- files].

# Appendix G: Transcript Highlights by Topic

Transcript source: Q1 FY2026 earnings call dated 2026-01-29 [File: raw/transcript.json -- symbol/period/year/date].

## Financial results
- Timothy Cook stated revenue was $143.8B, up 16% year over year; iPhone revenue grew 23%; Services revenue grew 14%; and EPS was $2.84, up 19% [File: raw/transcript.json -- Timothy Cook prepared remarks].
- Kevan Parekh stated Apple ended the quarter with $145B in cash and marketable securities, total debt of $91B, and net cash of $54B [File: raw/transcript.json -- Kevan Parekh prepared remarks].

## Guidance and supply
- Kevan Parekh stated March-quarter revenue was expected to grow 13%-16% year over year and that the outlook included constrained iPhone supply [File: raw/transcript.json -- Kevan Parekh prepared remarks].
- Amit Daryanani asked about iPhone demand and supply duration; Timothy Cook answered that Apple was in “supply chase mode,” was “currently constrained,” and that the constraint related to advanced-node SoC availability [File: raw/transcript.json -- Amit Daryanani question / Timothy Cook response].

## Memory and margin
- In Q&A, Timothy Cook stated memory pricing was “increasing significantly,” with minimal Q1 margin impact and more Q2 impact inside the 48%-49% gross-margin guide [File: raw/transcript.json -- Timothy Cook response].

## AI and product discussion
- Erik Woodring stated in a question that competitors had integrated AI into devices; this is analyst question language, not management confirmation [File: raw/transcript.json -- Erik Woodring question]. Timothy Cook responded that Apple was integrating intelligence across the operating system in a personal and private way [File: raw/transcript.json -- Timothy Cook response].

## Capital allocation
- Kevan Parekh stated Apple returned nearly $30B to shareholders during the quarter, including $3.9B in dividends and equivalents and $25B through open-market repurchases of 105M shares [File: raw/transcript.json -- Kevan Parekh prepared remarks].

## Non-answer flags
- Tim Cook did not provide a specific date for when iPhone supply and demand would balance after Amit Daryanani asked about supply duration [File: raw/transcript.json -- Amit Daryanani Q&A / Timothy Cook response].

# Appendix H: Source Index

| File | Data provider | Date of data | Reliability tier | Use |
| --- | --- | --- | --- | --- |
| raw/balance.json | FMP financial statements | FY2025, filed 2025-10-31 | financial data API | balance sheet, debt, cash, equity |
| raw/income.json | FMP financial statements | FY2025, filed 2025-10-31 | financial data API | revenue, margins, EPS, R&D |
| raw/cashflow.json | FMP financial statements | FY2025, filed 2025-10-31 | financial data API | OCF, capex, FCF, capital returns |
| raw/metrics.json | FMP metrics | FY2021-FY2025 | financial data API | EV multiples, returns, working-capital metrics |
| raw/ratios.json | FMP ratios | FY2021-FY2025 | financial data API | margin ratios, dividend yield, EBITDA margin |
| raw/quote.json | FMP quote | 2026-05-14 timestamp 1778788801 | financial data API | price, market cap, trading range |
| raw/technicals.json | FMP technical-indicators API | 2026-05-14 | financial data API | RSI, EMA, SMA, ADV |
| raw/earnings.json | FMP earnings | last updated through 2026-05-14 | financial data API | EPS and revenue actual/estimated differences |
| raw/ratings.json | FMP estimates/grades | estimates dated FY2026-FY2030 | financial data API | consensus estimates only; not used as evidence of quality |
| raw/info.json | FMP company profile | 2026-05-14 snapshot | financial data API | company scope, sector, employees, CEO field |
| raw/peers.json | FMP peers endpoint | 2026-05-14 run | financial data API | peer symbols and company names; not a segment-specific ranked competitor list |
| raw/transcript.json | Earnings transcript | Q1 FY2026 call dated 2026-01-29 | transcript | management and analyst statements with speaker attribution |
| raw/filings.json | EDGAR filing list | latest listed 2026-05-01 10-Q and 2025-10-31 10-K | filing index | filing dates/accessions |
| 2025 10-K excerpts in analysis/value_chain.md | EDGAR | filed 2025-10-31 | filing | category sales, geography sales, distribution, supply-chain risks |
| raw/segments.json | FMP segments endpoint | 2026-05-14 run | financial data API | absence of segment/geography endpoint data |
| raw/insider.json | FMP insider transactions | latest filing 2026-05-12 | financial data API / SEC Form 4 links | insider activity summary |
| raw/short_interest.md | web extraction (Finviz, Benzinga, others) | settlement Apr. 30, 2026 in cited snippets | web / corroborated | short interest with claim-verification caveats |
| raw/claim_verification.json | internal claim-verification run | 2026-05-14 | verification metadata | confidence tags for web claims, including C049 Motley Fool competitor-list tag |
| raw/computed_metrics.json | internal calculation file from FMP inputs | generated 2026-05-14 | derived calculation from financial data API | margin, net debt, and enterprise-value checks |
| raw/value_chain.md | web extraction, Apple supply-chain pages among sources | 2026-05-14 run | mixed; claim tags applied | supplier-list and supply-chain facility claims |
| raw/competitive_history.md | web extraction | 2026-05-14 run | web | market-share snippets with Single-Source caveats |
| raw/competitor_data.md | web extraction | 2026-05-14 run | web | third-party competitor-list snippets with Single-Source caveats |
| raw/supply_demand.md | web extraction | 2026-05-14 run | web | mobile OS share claim with Contradicted tag |
| raw/convertible_detail.md / raw/convertible_search.json | SEC search and web extraction | 2026-05-14 run | filing/web mixed | note maturity claims; no convertible terms located |
| analysis/competitive_position.md | analyst-generated synthesis | 2026-05-14 workspace | derived analysis | competitive and supply/demand compilation |
| analysis/value_chain.md | analyst-generated synthesis | 2026-05-14 workspace | derived analysis | value-chain compilation |
| analysis/financial_data.md | analyst-generated synthesis | 2026-05-14 workspace | derived analysis | capital structure and key stats compilation |
| analysis/risk_factors.md | analyst-generated synthesis | 2026-05-14 workspace | derived analysis | risk-factor compilation |
