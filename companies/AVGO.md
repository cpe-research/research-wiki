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

# Broadcom Inc. (AVGO) — Research Report

**Report Date:** May 27, 2026
**Data As Of:** May 27, 2026 (price), FY2025 (ended Nov 2, 2025) for annual financials, Q1 FY2026 (ended Feb 2, 2026) for most recent quarter
**Ticker:** AVGO | NASDAQ Global Select | Technology | Semiconductors
**Price:** $420.75 [1]
**ADV:** $10,006MM [2]
**Market Cap:** $1,992.1B [3]
**Net Debt:** $48.958B (2.5% of mkt cap) [4]
**Net Cash:** -$48.958B (-2.5% of mkt cap) [5]
**Enterprise Value:** $2,041.0B [6]
**Short Interest:** ~1.10% of float (~51.0M shares short / 4,642.8M float) [7]

<details><summary>Header Sources</summary>

1. [quote.json: price $420.745](https://site.financialmodelingprep.com/financial-statements/AVGO)
2. [info.json: averageVolume 23,781,641 × price $420.75 / 1e6 = $10,006MM](https://site.financialmodelingprep.com/financial-statements/AVGO)
3. [quote.json: marketCap $1,992,088,729,150](https://site.financialmodelingprep.com/financial-statements/AVGO)
4. [balance.json: totalDebt $65,136M − cashAndShortTermInvestments $16,178M = $48,958M](https://site.financialmodelingprep.com/financial-statements/AVGO)
5. [balance.json: cashAndShortTermInvestments $16,178M − totalDebt $65,136M = -$48,958M (net debt position)](https://site.financialmodelingprep.com/financial-statements/AVGO)
6. Computed: $1,992.1B market cap + $65.136B total debt − $16.178B cash = $2,041.0B. Note: enterprise_value.json shows $1,757.3B at FY2025 fiscal year-end price of $362.55, which is stale.
7. [short_interest.md: ShortSqueeze reports 51,010,000 shares short (Tier 5)](https://www.marketbeat.com/stocks/NASDAQ/AVGO/short-interest/) + [shares_float.json: floatShares 4,642,774,789](https://site.financialmodelingprep.com/financial-statements/AVGO). FMP short_interest.json returned 404 (data gap). Days to cover: 2.1–2.6 [Contradicted: C046 — ShortSqueeze reports 2.1, MarketBeat reports 2.6].

</details>

---

## Section 1: Business Overview

<!-- IC Question: What does this company do, how is it organized, and how large is each piece? What would change the answer: Major divestiture, acquisition, segment reclassification, revenue mix shift. -->

### Company Identity

Broadcom Inc. is a global technology company headquartered at 3421 Hillview Ave, Palo Alto, CA 94304. CEO: Hock E. Tan. Employees: 37,000. [info.json: companyName, address, ceo, fullTimeEmployees](https://site.financialmodelingprep.com/financial-statements/AVGO)

### Reportable Segments

Broadcom reports **two segments**: Semiconductor Solutions and Infrastructure Software. [claim_verification.json: Verified, citing SEC filing avgo-20260201]

| Segment | FY2025 Revenue | % of FY2025 Total | Q1 FY2026 Revenue | Q1 FY2026 % | Q1 FY2026 YoY |
|---------|---------------|-------------------|-------------------|-------------|----------------|
| Semiconductor Solutions | $36.86B | 57.7% | $12.5B | 64.7% | +52% |
| Infrastructure Software | $27.03B | 42.3% | $6.8B | 35.2% | +1% |
| **Total** | **$63.887B** | **100%** | **$19.311B** | **100%** | **+29%** |

Sources: FY2025 total from [income.json: revenue](https://site.financialmodelingprep.com/financial-statements/AVGO). FY2025 segment split from [business_overview.md: mlq.ai/bullfincher.io, Corroborated]. Q1 FY2026 segments from [transcript.json: Kirsten Spears](https://site.financialmodelingprep.com/financial-statements/AVGO). Segment sum ($12.5B + $6.8B = $19.3B) reconciles to reported $19.311B within $11M rounding from transcript's rounded figures. [Inference: transcript uses rounded billions; exact figures reconcile through the press release] [Sources: transcript.json, earnings.json]

**FMP segments.json returned 404** — segment data reconstructed from transcript and web sources. [segments.json: segments_message](https://site.financialmodelingprep.com/financial-statements/AVGO)

### Semiconductor Solutions — Key Products

Management further breaks semiconductors into **AI** and **non-AI** sub-categories in earnings commentary [transcript.json: Hock Tan](https://site.financialmodelingprep.com/financial-statements/AVGO):

**AI Semiconductors (Q1 FY2026: $8.4B, 43.5% of total revenue, +106% YoY):**

1. **Custom AI Accelerators (XPUs/TPUs):** ASICs co-designed with hyperscalers for AI training and inference. Google's TPU (7th-gen Ironwood), Meta's MTIA, OpenAI's XPU, and 3 others. ~2/3 of Q1 AI revenue (~$5.6B). Custom accelerator growth was +140% YoY in Q1. [Inference: $8.4B × 2/3 = ~$5.6B; Hock Tan stated AI networking was "1/3 of total AI revenue," implying XPUs were 2/3] [Sources: transcript.json]
2. **AI Networking Semiconductors:** Ethernet switch ASICs (Tomahawk 6, 100 Tbps), 200G/400G SerDes, and DSPs for AI data center connectivity. ~1/3 of Q1 AI revenue (~$2.8B), +60% YoY. Management guided Q2 FY2026 networking to accelerate to 40% of AI revenue (~$4.3B). [transcript.json: Hock Tan](https://site.financialmodelingprep.com/financial-statements/AVGO)

**Non-AI Semiconductors (Q1 FY2026: $4.1B, 21.2% of total, flat YoY):**
Enterprise networking, broadband, server storage connectivity, and wireless communications (Apple is the dominant wireless customer per [claim_verification.json: Corroborated]). Individual sub-category revenues are not disclosed. [transcript.json: Hock Tan](https://site.financialmodelingprep.com/financial-statements/AVGO)

### Infrastructure Software — Key Products

7. **VMware Cloud Foundation (VCF):** Integrated private cloud platform. VMware revenue grew 13% YoY in Q1 FY2026. TCV booked exceeded $9.2B, ARR growth 19% YoY. [transcript.json: Hock Tan](https://site.financialmodelingprep.com/financial-statements/AVGO)
8. **CA Technologies Mainframe Software** (acquired 2018, $18.9B), **Symantec Enterprise Security** (acquired 2019, $10.7B), **Brocade FC SAN** (acquired 2017, $5.9B) — revenue not separately disclosed. The total segment grew only 1% YoY while VMware within it grew 13%, which implies the non-VMware software businesses are in aggregate declining. [Inference: If VMware is the majority of $6.8B and grew 13% while total grew 1%, then non-VMware must be declining] [Sources: transcript.json]

### AI Revenue — Narrative vs. Reality

| Metric | Q1 FY2026 | % of Q1 Total | YoY Growth | Q2 FY2026 Guidance |
|--------|-----------|---------------|------------|-------------------|
| AI Semiconductor | $8.4B | 43.5% | +106% | $10.7B (+140%) |
| Non-AI Semiconductor | $4.1B | 21.2% | Flat | ~$4.1B (+4%) |
| Infrastructure Software | $6.8B | 35.2% | +1% | $7.2B (+9%) |
| **Total** | **$19.311B** | **100%** | **+29%** | **~$22.0B (+47%)** |

[Sources: transcript.json: Hock Tan and Kirsten Spears for Q1 actuals and Q2 guidance](https://site.financialmodelingprep.com/financial-statements/AVGO); [earnings.json: Q1 FY2026 revenueActual](https://site.financialmodelingprep.com/financial-statements/AVGO)

By Q2 FY2026 guidance, AI semiconductor revenue ($10.7B) will represent 48.6% of total revenue ($22.0B). [Inference: $10.7B / $22.0B = 48.6%] [Sources: transcript.json]

**FY2025 annual AI semiconductor revenue:** Not disclosed in available data. Q4 FY2025 AI revenue was $6.5B (+74% YoY) per [segment_financials.md: Forbes snippet]. Full-year figure would require all four quarterly releases; only Q1 FY2026 transcript is in this workspace. **Data gap.**

### Major Customers (6 XPU Customers)

| Customer | Product | Scale |
|----------|---------|-------|
| Google | TPU (7th-gen Ironwood) | Long-term agreement through 2031 [EDGAR: 8-K Apr 6, 2026](https://www.sec.gov/cgi-bin/browse-edgar?action=getcompany&CIK=AVGO&type=8-K) |
| Anthropic | TPU compute (via Google) | 1 GW in 2026, >3 GW in 2027 |
| Meta | MTIA custom accelerator | Shipping now; "multiple gigawatts in '27 and beyond" |
| OpenAI | Custom XPU (1st gen) | >1 GW in 2027 volume deployment |
| Customers 4 & 5 | Custom XPUs (unnamed) | "More than double in 2027" |

[transcript.json: Hock Tan prepared remarks, Q1 FY2026](https://site.financialmodelingprep.com/financial-statements/AVGO). Customer revenue concentration percentages are not disclosed — **data gap** (10-K typically discloses >10% customers but latest_10k.json was empty).

### Brief History

Broadcom was formed when Avago Technologies acquired Broadcom Corporation in 2016 for $37B. Under CEO Hock Tan, the company executed serial acquisitions: Brocade ($5.9B, 2017), CA Technologies ($18.9B, 2018), Symantec Enterprise ($10.7B, 2019), and VMware ($61B, closed Nov 2023). Revenue grew from $6.8B (FY2015) to $63.9B (FY2025). [income.json](https://site.financialmodelingprep.com/financial-statements/AVGO); [claim_verification.json: acquisition history Corroborated]

---

## Section 2: Competitive Position

<!-- IC Question: For each product, who competes and what are relative strengths? What would change: loss of a top customer, entry of a well-capitalized competitor, customer building in-house (COT). Base rate: what % of companies in this industry lost competitive position to a new entrant in the past 5 years? No new merchant custom ASIC company has emerged as a meaningful third competitor. -->

### Custom AI Accelerators (XPUs)

**Broadcom vs. Marvell Technology (MRVL):** The two dominant merchant custom AI ASIC providers. Broadcom has 6 disclosed XPU customers; Marvell's primary disclosed customer is Amazon AWS (Trainium/Inferentia). Broadcom's single-quarter Q1 FY2026 AI semiconductor revenue ($8.4B) exceeds Marvell's entire FY2026 data center revenue ($6.1B for the full year ended Jan 2026). [Inference: This implies Broadcom's custom AI silicon business is materially larger than Marvell's, though not all of each company's data center revenue is custom ASICs specifically] [Sources: transcript.json, ecosystem_signals.md — Verified: C013, Corroborated: C015]

**Broadcom vs. NVIDIA:** Not a direct custom ASIC competitor but competes for the same AI accelerator dollar. CEO Tan characterized XPU vs. GPU as "strategic" vs. "transactional": "[the customer] designs their own architecture to go after a particular type of workload... The one size fits all of a general purpose GPU gets you only that far." [transcript.json: Hock Tan response to C.J. Muse](https://site.financialmodelingprep.com/financial-statements/AVGO)

**Customer-Owned Tooling (COT):** Analyst Harlan Sur (JPMorgan) asserted in Q1 FY2026 Q&A that COT designs are "at least 2x less performant." **This is an analyst assertion, not a verified fact.** [transcript.json: analyst Harlan Sur, question](https://site.financialmodelingprep.com/financial-statements/AVGO). CEO Tan responded: "We will not see competition in COT for many years to come. It will come eventually." He cited four barriers: silicon design expertise ("20+ years"), SerDes IP (200G/400G), advanced packaging, and high-volume yield. [transcript.json: Hock Tan response](https://site.financialmodelingprep.com/financial-statements/AVGO)

### Ethernet Switching ASICs

Market share estimates are **Contradicted** across sources: Linley Group (2022) reported ~80% of the $3B Ethernet switch chip market [competitive_by_product.md — Contradicted: C070]. AIChipLink (May 2026) reports 60-65% current share [claim_verification.json: C070]. No authoritative current figure exists. Broadcom claims networking share gains via Tomahawk 6 (100 Tbps, first-to-market) and 200G SerDes. Tomahawk 7 (200 Tbps) planned for 2027. [transcript.json: Hock Tan](https://site.financialmodelingprep.com/financial-statements/AVGO)

### Infrastructure Software (VMware)

VMware is the dominant hypervisor platform for enterprise private cloud. Competitors: Nutanix (AHV), Red Hat (OpenShift/KVM), Microsoft (Hyper-V). VMware revenue grew 13% YoY in Q1 FY2026 with TCV exceeding $9.2B and ARR growth of 19% YoY. [transcript.json](https://site.financialmodelingprep.com/financial-statements/AVGO). **Data gap:** VMware market share, customer defection rates, and competitive win/loss data vs. Nutanix/Red Hat are not available.

### Switching Costs

- **Custom XPUs:** Each chip is co-designed over 2-3 years with deep integration into the customer's software stack. No disclosed customer has switched away from Broadcom. Customer count has grown from ~3 to 6. [transcript.json: Hock Tan](https://site.financialmodelingprep.com/financial-statements/AVGO)
- **Ethernet switching:** Ecosystem lock-in via MAP, SDK, and Broadcom-specific software stacks at OEMs (Arista, Cisco, Dell). [competitive_by_product.md — Corroborated: C068]
- **VMware:** Multi-year migration required for replacement. Post-acquisition licensing restructured to VCF bundles, increasing bundled switching costs. [customer_alternatives.md — Single-Source: C073, attributed to DCFmodeling.com only]

### Design Win Tracking

| Customer | Design Status | Production | Scale |
|----------|--------------|------------|-------|
| Google (Ironwood 7th gen) | Shipping | FY2026 current | Growth continuing |
| Google (next-gen TPU) | In development | 2027+ | "Even stronger demand" |
| Anthropic (via Google TPU) | Shipping | 2026: 1GW | 2027: >3GW |
| Meta (MTIA) | Shipping now | Current | 2027: "multiple GW" |
| OpenAI (1st gen XPU) | In development | 2027 volume | >1GW |
| Customers 4 & 5 | Shipping | Current | 2027: "more than double" |

[All from transcript.json: Hock Tan prepared remarks, Q1 FY2026](https://site.financialmodelingprep.com/financial-statements/AVGO)

Full competitive analysis in [Appendix A](appendix/A_competitive_position.md).

---

## Section 3: Supply/Demand Balance

<!-- IC Question: Is industry supply sufficient to meet demand at current prices, and when does that change? What would change: major capacity announcement, demand shock, tariff/subsidy policy change. Base rate: typical AI semiconductor cycle duration is uncertain — AI capex buildouts are historically unprecedented at this scale. -->

### Demand Decomposition

**Backlog:** $73B in AI-specific orders as of Q4 FY2025 earnings (Dec 11, 2025), for delivery over ~18 months, representing 45% of Broadcom's $162B consolidated backlog. [backlog_breakdown.md — Corroborated: C078, C080]

**Historical Trajectory:**

| Period | Revenue | YoY Growth | AI Semi (quarterly) |
|--------|---------|-----------|-------------------|
| FY2023 | $35.82B | +7.9% | Not disclosed |
| FY2024 | $51.57B | +44.0% | Not disclosed |
| FY2025 | $63.89B | +23.9% | Q4: $6.5B (+74%) |
| Q1 FY2026 | $19.31B (ann. ~$77B) | +29% | $8.4B (+106%) |
| Q2 FY2026E | ~$22.0B (ann. ~$88B) | +47% | $10.7B (+140%) |

[income.json](https://site.financialmodelingprep.com/financial-statements/AVGO); [earnings.json](https://site.financialmodelingprep.com/financial-statements/AVGO); [transcript.json](https://site.financialmodelingprep.com/financial-statements/AVGO)

The FY2023-FY2024 jump (+44%) reflects VMware consolidation (goodwill increased from $43.7B to $97.9B [balance.json](https://site.financialmodelingprep.com/financial-statements/AVGO)). FY2025-FY2026 acceleration is AI-driven.

**Demand Durability:** Management has "line of sight" to >$100B AI chip revenue in 2027, with ~10 GW of compute shipments. [transcript.json: Hock Tan response to Stacy Rasgon](https://site.financialmodelingprep.com/financial-statements/AVGO). Content per GW is ~$20B (Rasgon framework, Tan confirmed "not far" but "varies, sometimes quite dramatically" by customer). [transcript.json: Stacy Rasgon Q&A](https://site.financialmodelingprep.com/financial-statements/AVGO)

**Customer Capex Corroboration:** Alphabet raised FY2026 capex guidance to $180–$190B. Alphabet Q1 2026 capex was $35.7B [Contradicted: C021 — ecosystem_signals.md initially stated $30.9B, but CNBC confirms $35.7B]. Google Cloud backlog nearly doubled QoQ to >$460B. [ecosystem_signals.md — Verified: C020, C025]

### Supply Constraints

- **TSMC foundry:** A Broadcom executive stated TSMC capacity has "kind of choked the supply chain in 2026" with expansion to 2027. [supplier_capacity.md — Corroborated: C051]. TSMC Q1 2026 revenue was $35.9B (+40.6% YoY), 4th consecutive quarterly record. [ecosystem_signals.md — Verified: C007]
- **CoWoS packaging:** Planned at ~130,000 wafers/month by late 2026, ~4x prior levels. NVIDIA reportedly secures ~60% of CoWoS capacity [ecosystem_signals.md — Corroborated: C010]. Broadcom reportedly raised 2026 CoWoS orders [Corroborated: C011].
- **T-glass substrates and HBM:** Broadcom has "fully secured capacity of these components for '26 through '28" [transcript.json: Hock Tan](https://site.financialmodelingprep.com/financial-statements/AVGO). Charlie Kawwas confirmed supply secured through 2028 and growth can continue in 2028: "Yes." [transcript.json](https://site.financialmodelingprep.com/financial-statements/AVGO)

### Supply/Demand Synthesis

Demand substantially exceeds supply for custom AI ASICs in 2026. The $73B AI backlog represents 2.2x the current annualized AI revenue rate ($8.4B × 4 = $33.6B). [Inference: $73B / $33.6B = 2.17x] [Sources: backlog_breakdown.md, transcript.json]. Semiconductor gross margin held at 68% (+30 bps YoY), and management expects it to remain "fairly consistent," indicating no pricing pressure from customers despite supply constraints flowing from TSMC. [transcript.json: Kirsten Spears](https://site.financialmodelingprep.com/financial-statements/AVGO)

### AI Value Chain Positioning

Broadcom sits at two layers: (1) custom AI silicon design (co-designing XPUs with hyperscalers, managing TSMC fabrication), and (2) AI networking silicon (Tomahawk switch ASICs, SerDes). AI semiconductor revenue has accelerated from $6.5B (Q4 FY2025) to $8.4B (Q1 FY2026) to guided $10.7B (Q2 FY2026) — the growth rate itself is accelerating (+74% → +106% → +140% YoY). [transcript.json](https://site.financialmodelingprep.com/financial-statements/AVGO)

Full supply/demand analysis in [Appendix B](appendix/B_supply_demand.md).

---

## Section 4: Value Chain

<!-- IC Question: Where is value captured, and is it migrating toward or away from this company? What would change: vertical integration by customer/supplier, margin compression, technology enabling disintermediation. Base rate: value chain shifts in semiconductors tend to occur over 5-10 year cycles driven by node transitions and architectural shifts. -->

### Value Chain Map (Semiconductor)

```
EDA/IP Licensing → Chip Design → Wafer Fab → Advanced Packaging → Assembly/Test → End Customer
(Synopsys/Cadence)  (AVGO)        (TSMC)      (TSMC CoWoS)        (OSAT/TSMC)     (Hyperscalers)
```

Broadcom owns the chip design stage (IP leverage, near-zero marginal cost scaling) and outsources all manufacturing. Capex was $623M in FY2025 on $63.9B revenue (1.0% capex/revenue ratio) — the economics of a fabless + software model. [cashflow.json: capitalExpenditure](https://site.financialmodelingprep.com/financial-statements/AVGO)

### Margin Capture by Stage

| Stage | Company | Gross Margin | Operating Margin | Source |
|-------|---------|-------------|-----------------|--------|
| Chip Design (AVGO Semi) | Broadcom | 68% (non-GAAP) | 60% | [transcript.json: Kirsten Spears](https://site.financialmodelingprep.com/financial-statements/AVGO) |
| Wafer Fab | TSMC | 66.2% (Q1 2026) | 58.1% | [ecosystem_signals.md — Verified: C008] |
| Software (AVGO Infra) | Broadcom | 93% (non-GAAP) | 78% | [transcript.json: Kirsten Spears](https://site.financialmodelingprep.com/financial-statements/AVGO) |
| Chip Design (Marvell) | MRVL | 51.0% (GAAP) | 16.3% | [ecosystem_signals.md] |
| Assembly/Test | OSATs | ~20-30% | ~10-15% | Industry estimates |

Broadcom's semiconductor non-GAAP margins (68% gross) exceed TSMC's (66.2%), which is atypical for a fabless designer vs. the foundry manufacturing its chips. This reflects IP pricing power and the custom nature of AI XPU co-designs. [Inference: standard fabless companies typically have lower margins than their foundry partner at the leading edge; Broadcom's exception reflects the co-design premium] [Sources: transcript.json, ecosystem_signals.md]

### TSMC Dependency

TSMC is Broadcom's primary foundry for advanced AI ASICs (3nm/5nm) and CoWoS packaging. The FY2025 10-K discloses: "During fiscal year 2025, we purchased approximately two-thirds of our manufacturing materials from five materials suppliers, some of which are single source suppliers." [supplier_capacity.md — EDGAR 10-K FY2025 snippet](https://www.sec.gov/cgi-bin/browse-edgar?action=getcompany&CIK=AVGO&type=10-K). TSMC's expanding margins (from 59.9% in FY2025 to 66.2% in Q1 2026 [ecosystem_signals.md — Verified]) indicate increasing pricing power on advanced nodes, yet Broadcom's semiconductor margins held at 68% — implying cost pass-through to hyperscaler customers is manageable. [transcript.json](https://site.financialmodelingprep.com/financial-statements/AVGO)

### Integration Direction

- **Not backward-integrating:** Broadcom remains fabless ($623M capex vs. TSMC's ~$30B+).
- **Forward integration via VMware ($61B, Nov 2023):** Moved Broadcom from component supplier to platform spanning hardware and software. VMware is positioned as "the permanent abstraction layer between AI software and physical chips." [transcript.json: Hock Tan](https://site.financialmodelingprep.com/financial-statements/AVGO)
- **Rack-scale solutions (emerging):** Analysts flagged AVGO moving from chips to rack systems. Management downplayed margin impact: "not going to be substantial at all." [transcript.json: Kirsten Spears](https://site.financialmodelingprep.com/financial-statements/AVGO)

Full value chain analysis in [Appendix C](appendix/C_value_chain.md).

---

## Section 5: Capital Structure

<!-- IC Question: How does the company raise money to spend on its business? What would change: major debt issuance/repayment, M&A financing, credit rating change. -->

### Equity Composition

- **Share class:** Common Stock, $0.001 par value [insider.json](https://site.financialmodelingprep.com/financial-statements/AVGO)
- **Preferred stock:** $0 outstanding (Series A Mandatory Convertible Preferred auto-converted Sep 30, 2022) [balance.json: preferredStock](https://site.financialmodelingprep.com/financial-statements/AVGO); [convertible_detail.md — Verified]
- **Shares outstanding:** 4,734.7M [shares_float.json](https://site.financialmodelingprep.com/financial-statements/AVGO)
- **Diluted shares (FY2025):** 4,853M [income.json: weightedAverageShsOutDil](https://site.financialmodelingprep.com/financial-statements/AVGO)
- **Market Cap:** $1,992.1B [quote.json](https://site.financialmodelingprep.com/financial-statements/AVGO)

### Debt Composition

| Component | Amount | Source |
|-----------|--------|--------|
| Short-term debt | $3.152B | [balance.json: shortTermDebt](https://site.financialmodelingprep.com/financial-statements/AVGO) |
| Long-term debt | $61.984B | [balance.json: longTermDebt](https://site.financialmodelingprep.com/financial-statements/AVGO) |
| **Total gross debt** | **$65.136B** | [balance.json: totalDebt](https://site.financialmodelingprep.com/financial-statements/AVGO) |
| Capital lease obligations | $0 | [balance.json: capitalLeaseObligations](https://site.financialmodelingprep.com/financial-statements/AVGO) |

Debt type: predominantly senior unsecured notes. A $5B offering in Nov 2024 included notes maturing Nov 15, 2031 at 5.150% [convertible_detail.md — SEC 424B2 filing](https://www.sec.gov/cgi-bin/browse-edgar?action=getcompany&CIK=AVGO&type=424B2). **Data gap:** Full maturity schedule by tranche requires 10-K Note to Financial Statements (latest_10k.json was empty).

**Debt trajectory:** FY2023 $39.648B → FY2024 $67.566B (+$27.9B, VMware acquisition financing) → FY2025 $65.136B (-$2.4B, began deleveraging). [balance.json: totalDebt](https://site.financialmodelingprep.com/financial-statements/AVGO)

### Convertible Securities

No convertible debt outstanding. Series A Mandatory Convertible Preferred ($3.25B offering Sep 2019) auto-converted Sep 30, 2022. [convertible_detail.md — Verified: C056; convertible_search.json](https://www.sec.gov/cgi-bin/browse-edgar?action=getcompany&CIK=AVGO&type=10-Q)

### Cash and Equivalents

$16.178B as of FY2025 end [balance.json: cashAndCashEquivalents](https://site.financialmodelingprep.com/financial-statements/AVGO)

### Minority Interest

$0 [balance.json: minorityInterest](https://site.financialmodelingprep.com/financial-statements/AVGO)

### Enterprise Value

$2,041.0B (computed: $1,992.1B market cap + $65.136B total debt − $16.178B cash) [quote.json, balance.json](https://site.financialmodelingprep.com/financial-statements/AVGO)

### Net Debt / EBITDA

1.41x ($48.958B net debt / $34.714B FY2025 EBITDA) [balance.json: netDebt; income.json: ebitda](https://site.financialmodelingprep.com/financial-statements/AVGO). Consistent with [metrics.json: netDebtToEBITDA 1.41](https://site.financialmodelingprep.com/financial-statements/AVGO). Down from 2.44x in FY2024, as EBITDA grew 45% ($23.9B → $34.7B) while debt declined $2.4B.

Full capital structure detail in [Appendix D](appendix/D_capital_structure.md).

---

## Source Index

See [Appendix H](appendix/H_source_index.md) for the complete source list with URLs, dates, and reliability tiers.

---

## Discrepancies & Data Gaps

### Cross-Reference Conflicts

1. **Alphabet Q1 2026 capex [Contradicted: C021]:** ecosystem_signals.md initially stated $30.9B; CNBC and other sources confirm $35.7B. This report uses $35.7B.
2. **Ethernet switching market share [Contradicted: C070]:** Linley Group (2022) reported ~80%; AIChipLink (2026) reports 60-65%. Range is 60-80%, with the lower end being more recent. Broadcom does not disclose market share in SEC filings.
3. **Short interest days to cover [Contradicted: C046]:** ShortSqueeze reports 2.1 days; MarketBeat reports 2.6 days.
4. **Employee count discrepancy:** info.json lists 37,000 employees (fullTimeEmployees field) but the description text within the same file states 19,000 (pre-VMware, stale). 37,000 is the current figure.

### Data Gaps

1. **10-K full text unavailable:** FY2025 10-K (filed Dec 18, 2025) not extracted. Prevents analysis of customer concentration (>10% customers), detailed risk factors, geographic breakdown, and debt maturity schedule.
2. **Customer revenue concentration:** No per-customer revenue disclosed. With 6 AI ASIC customers, concentration is inherently high but unquantified.
3. **FY2025 annual AI semiconductor revenue:** Not disclosed in available data. Only quarterly figures available.
4. **FY2024 annual segment-level revenue:** First full VMware year cannot be decomposed into semiconductor vs. software at the annual level.
5. **VMware competitive data:** No market share, churn rate, or net retention data available.
6. **Debt maturity schedule:** Only one tranche identified ($5B 2031 notes at 5.150%). Full schedule requires 10-K.
7. **Proxy statement:** DEF 14A extraction failed (proxy.json ticker-not-found error). Executive compensation and governance data unavailable.
8. **Non-VMware software decline magnitude:** VMware grew 13% while total segment grew 1%, implying non-VMware decline, but individual product line contributions (CA, Symantec, Brocade) are undisclosed.
9. **Apple revenue contribution:** Widely identified as dominant wireless customer but exact revenue percentage undisclosed.
10. **Customers 4 and 5 identity:** Two of six XPU customers are unnamed.

### Inference Registry

All inferred claims in this report carry explicit `[Inference: reasoning] [Sources: files]` tags. Key inferences:
- AI XPU revenue ~$5.6B = $8.4B × 2/3 (from transcript's "1/3 of AI revenue" for networking)
- Non-VMware software declining (from 13% VMware growth vs. 1% total segment growth)
- Q2 FY2026 AI as 48.6% of total ($10.7B / $22.0B)
- Custom AI ASIC market share: Broadcom captures ~84.6% of merchant ASIC revenue ($33.6B annualized / ($33.6B + $6.1B Marvell))
