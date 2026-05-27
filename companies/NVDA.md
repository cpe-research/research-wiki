---
type: company
ticker: NVDA
name: NVDA
updated: "2026-05-27"
sources:
  - info.json
  - value_chain.md
  - segments.json
  - insider.json
  - holders.json
  - transcript_competitors.json
---

# NVDA (NVDA)

## Competitors

- [AVGO](AVGO.md) (AVGO)
- [Advanced Micro Devices, Inc.](AMD.md) (AMD)

## Key Insiders

- GAWEL SCOTT (officer)
- Kress Colette (officer: EVP & Chief Financial Officer)
- Puri Ajay K (officer: EVP, Worldwide Field Ops)
- Robertson Donald F Jr (officer: Principal Accounting Officer)
- STEVENS MARK A (director)
- Shah Aarti S. (director)
- Shoquist Debora (officer: EVP, Operations)
- Teter Timothy S. (officer: EVP, General Counsel and Sec)

---

> **⚠️ DRAFT — this report did not pass the citation audit.** Some claims may lack source verification. Treat as preliminary research.

# NVIDIA Corporation (NVDA) — Research Report

**Report Date:** May 25, 2026
**Data As Of:** May 22, 2026 (price), FY2026 (ended January 25, 2026) for annual financials, Q1 FY2027 (ended April 26, 2026) for most recent quarter
**Ticker:** NVDA | NASDAQ Global Select | Technology | Semiconductors
**Price:** $215.33 [info.json: price]
**ADV:** $36,882MM [info.json: averageVolume 171,279,452 × price $215.33]
**Market Cap:** $5,215.5B [info.json: marketCap]
**Net Debt:** −$51.1B (−1.0% of mkt cap) [balance.json: totalDebt $11,412M − cashAndShortTermInvestments $62,556M]
**Net Cash:** $51.1B (1.0% of mkt cap) [balance.json: cashAndShortTermInvestments $62,556M − totalDebt $11,412M]
**Enterprise Value:** $5,164.4B [Inference: $5,215.5B mktcap + $11.4B debt − $62.6B cash+STI] [Sources: quote.json, balance.json]; $4,532.8B at FY2026 closing price [enterprise_value.json: enterpriseValue]
**Short Interest:** ~1.22% of float (282,930,000 shares short / 23,270,042,400 float) [short_interest.md: shortsqueeze.com + shares_float.json: floatShares; Tier 5 web source, treat as approximate]

---

## Section 1: Business Overview

<!-- IC Question: What does this company do, how is it organized, and how large is each piece? What would change the answer: major divestiture, acquisition, segment reclassification, revenue mix shift. -->

### Company Identity

NVIDIA Corporation is a fabless semiconductor company headquartered at 2788 San Tomas Expressway, Santa Clara, CA 95051. It employs 36,000 people, trades on the NASDAQ Global Select under the ticker NVDA, and has a market capitalization of $5.216 trillion. CEO: Jen-Hsun (Jensen) Huang. CIK: 0001045810. IPO: January 22, 1999. [info.json: companyName, address, fullTimeEmployees, exchangeFullName, ceo, cik, ipoDate, marketCap]

### Reportable Segments

NVIDIA reports two reportable segments: **Compute & Networking** and **Graphics**. Starting Q1 FY2027, the company also introduced a **market platform** disclosure framework with two market platforms: **Data Center** and **Edge Computing**. [latest_10k.json: segment disclosure, Q1 FY2027 10-Q]

**Reportable Segments — Q1 FY2027 (quarter ended April 26, 2026):**

| Segment | Q1 FY2027 Revenue | % of Total | Q1 FY2026 Revenue | YoY Growth | Q1 FY2027 Op. Income | Op. Margin |
|---------|-------------------|------------|-------------------|------------|---------------------|------------|
| Compute & Networking | $74,550M | 91.3% | $39,589M | +88% | $53,335M | 71.5% |
| Graphics | $7,065M | 8.7% | $4,473M | +58% | $2,941M | 41.6% |
| **Total** | **$81,615M** | **100%** | **$44,062M** | **+85%** | **$56,276M** | **69.0%** |

[latest_10k.json: Revenue by Reportable Segments table, Q1 FY2027 10-Q]

**Market Platforms — Q1 FY2027:**

| Market Platform | Q1 FY2027 Revenue | % of Total | Q1 FY2026 Revenue | YoY Growth |
|-----------------|-------------------|------------|-------------------|------------|
| **Data Center** | **$75,246M** | **92.2%** | **$39,112M** | **+92%** |
| — Hyperscale | $37,869M | 46.4% | $17,599M | +115% |
| — AI Clouds, Industrial & Enterprise (ACIE) | $37,377M | 45.8% | $21,513M | +74% |
| **Edge Computing** | **$6,369M** | **7.8%** | **$4,950M** | **+29%** |
| **Total** | **$81,615M** | **100%** | **$44,062M** | **+85%** |

[latest_10k.json: Revenue by Market Platform table, Q1 FY2027 10-Q; comparable periods recast]

**Annual Revenue:**

| Fiscal Year | Total Revenue | YoY Growth | Operating Income | Op. Margin |
|-------------|---------------|------------|------------------|------------|
| FY2026 | $215,938M | +65.5% | $130,387M | 60.4% |
| FY2025 | $130,497M | +114.2% | $81,453M | 62.4% |
| FY2024 | $60,922M | +125.9% | $32,972M | 54.1% |
| FY2023 | $26,974M | +0.2% | $4,224M | 15.7% |

[income.json: revenue, operatingIncome for FY2023–FY2026]

**Annual FY2026 segment breakdown data gap:** The FY2026 annual 10-K is not in the raw files (latest_10k.json contains the Q1 FY2027 10-Q). One web source (Bullfincher, via business_overview.md) reports Data Center as 89.72% of FY2026 revenue (~$193.7B); this is a [Single-Source] estimate and should be treated with that caveat. [business_overview.md: Bullfincher snippet]

### Key Products by Segment

**Compute & Networking** includes: [info.json: description; latest_10k.json: segment description; transcript.json: Colette Kress prepared remarks]
1. **Data Center GPU platforms** — Blackwell (B200, GB200, GB300) and Hopper (H100, H200). Blackwell contributed nearly 70% of data center compute revenue in Q1 FY2026. [transcript.json: Colette Kress]
2. **Networking** — InfiniBand, Spectrum-X Ethernet, NVLink interconnect. Networking revenue ~$5B in Q1 FY2026 (+64% QoQ). NVLink shipments exceeded $1B. Spectrum X annualizing >$8B. [transcript.json: Colette Kress]
3. **Automotive AI platforms** — Revenue $567M in Q1 FY2026 (+72% YoY). [transcript.json: Colette Kress]
4. **DGX systems** — DGX Spark (1 petaflop) and DGX Station (20 petaflops, GB300). [transcript.json: Colette Kress]
5. **AI Enterprise software** — NVIDIA AI Enterprise, NIMS, Nemo, Omniverse, Isaac, Cosmos. [transcript.json: Colette Kress]
6. **Jetson** — Edge AI/robotics embedded platforms. [info.json: description]

**Graphics** includes: [latest_10k.json: segment description; transcript.json: Colette Kress]
1. **GeForce GPUs** — RTX 5090/5080/5070 Ti/5070/5060 Ti/5060. 100M installed base. Record $3.8B gaming revenue in Q1 FY2026 (+42% YoY). [transcript.json: Colette Kress]
2. **Quadro/NVIDIA RTX professional GPUs** — $509M professional visualization revenue in Q1 FY2026 (+19% YoY). [transcript.json: Colette Kress]
3. **vGPU software** — Cloud-based virtual computing. [info.json: description]
4. **GeForce NOW** — Game streaming service. [info.json: description]

### Narrative vs. Reality

Data Center revenue was $75,246M in Q1 FY2027 (92.2% of total), up 92% YoY. [latest_10k.json] AI/Data Center is both the market narrative and the dominant P&L driver. Edge Computing (gaming, pro viz, automotive) was $6,369M (7.8% of total), representing 8.5% the size of Data Center. [latest_10k.json]

Within Data Center: Hyperscale ($37,869M, 50.3% of DC) and ACIE ($37,377M, 49.7% of DC) are approximately equal. Hyperscale grew faster YoY (+115% vs. +74%), while ACIE grew faster QoQ (+31% vs. +12%). [latest_10k.json]

Networking revenue (~$5B/quarter) and Spectrum X (annualizing >$8B) are called out as growth vectors within Data Center but are not separately reported in the 10-Q; these figures come from management commentary. [transcript.json: Colette Kress]

### Historical Context

NVIDIA was founded in 1993 and originally competed in PC graphics. The $6.9B acquisition of Mellanox Technologies (2020) brought networking in-house. Revenue grew 8x from FY2023 ($27.0B) to FY2026 ($215.9B). [income.json] [Inference: Revenue growth was driven by AI infrastructure demand, as Data Center rose from ~60% of revenue (FY2023 est.) to 92.2% (Q1 FY2027).] [Sources: income.json, latest_10k.json] Goodwill increased $15.6B in FY2026 (from $5.2B to $20.8B), indicating a major undisclosed acquisition during FY2026. [balance.json: goodwill]

### Major Customers

Three direct customers represented 21%, 17%, and 16% of Q1 FY2027 revenue ($81,615M), totaling 54% (~$44.1B). All three are primarily attributable to Compute & Networking. In Q1 FY2026, two direct customers represented 16% and 14% (30% combined). Names are not disclosed in SEC filings. [latest_10k.json: Concentration of Revenue]

One unnamed indirect customer (an "AI research and deployment company") contributed "a meaningful amount" of revenue by purchasing cloud services from NVIDIA's direct customers. [latest_10k.json: Indirect Customers] [Inference: Widely understood to refer to OpenAI purchasing via Microsoft Azure.] [Sources: latest_10k.json, transcript.json]

---

## Section 2: Competitive Position

<!-- IC Question: For each product, who competes with this company and what are their relative strengths? What would change: loss of a top customer, entry of a well-capitalized competitor, customer building in-house alternative, technology disruption. -->

### Data Center AI Accelerators (92.2% of Revenue)

**NVIDIA vs. AMD:**
- NVIDIA Data Center Q1 FY2027: $75,246M (+92% YoY). [latest_10k.json]
- AMD Data Center Q1 CY2026: $5,780M (+57% YoY), including EPYC CPUs in addition to Instinct GPUs. [ecosystem_signals.md; Verified per claim_verification.json C014]
- NVIDIA's Data Center revenue is approximately 13x AMD's Data Center revenue. [Inference: $75,246M / $5,780M = 13.0x] [Sources: latest_10k.json, ecosystem_signals.md]
- AMD MI350 launched June 12, 2025 (Q2 2025) with 288GB HBM3e. MI400 confirmed for 2026 with 432GB HBM4. MI500 on 2027 roadmap. [ecosystem_signals.md; claim_verification.json C020: Contradicted on launch timing — AMD's own product page shows MI350X launch date 6/12/2025, which is Q2 2025, not Q3 as some sources claim]
- AMD Instinct GPU line estimated at $7–8B revenue in 2025, capturing approximately 5–7% AI GPU market share. [ecosystem_signals.md: siliconanalysts.com; Single-Source per claim_verification.json C023]

**NVIDIA vs. Custom ASICs (Google TPU, Amazon Trainium, Microsoft Maia):**
- Google, Amazon, and Microsoft each develop custom AI accelerators for internal workloads. [customer_alternatives.md; Tier 5 sources]
- Google added as Spectrum X networking customer in Q1 FY2026, suggesting continued NVIDIA procurement alongside TPU deployment. [transcript.json: Colette Kress]
- Microsoft simultaneously deploying "tens of thousands of Blackwell GPUs" and planning to "ramp to hundreds of thousands of GB200s." [transcript.json: Colette Kress]
- NVIDIA's NVLink Fusion enables ASIC and CPU partners (MediaTek, Alchip, Astera Labs, Qualcomm) to connect to NVLink fabric — positioning NVIDIA as the platform layer even when customers deploy custom silicon. [transcript.json: Colette Kress]

**NVIDIA vs. Intel Gaudi:** Not mentioned in the Q1 FY2026 earnings call or competitor analysis, indicating minimal market impact. [Inference: Absence of Intel competitive commentary in transcript.json suggests negligible competitive relevance.] [Sources: transcript.json, competitive_history.md]

**Market share estimates:** Third-party estimates range from 70% to 95% for NVIDIA's AI accelerator share, but no Tier 1 or Tier 2 source provides a definitive figure with disclosed methodology. [competitive_history.md: Wikipedia; competitive_by_product.md: CNBC June 2024; Single-Source per claim_verification.json C042] The 13:1 revenue ratio between NVDA and AMD Data Center segments is the most concrete comparison available, though AMD's segment includes non-GPU products.

### Gaming GPUs (Within 7.8% Edge Computing)

GeForce RTX 50-series competes with AMD Radeon RX series. NVIDIA's gaming revenue reached a record $3.8B in Q1 FY2026 (+42% YoY) with a 100M installed base. [transcript.json: Colette Kress] Professional visualization revenue was $509M (+19% YoY). [transcript.json: Colette Kress]

### Competitive Advantages

1. **CUDA ecosystem** — 18+ years of software libraries, frameworks, and developer tools. AI researchers are trained on CUDA. Porting production AI training pipelines to alternatives requires months of engineering effort.
2. **NVLink interconnect** — Proprietary scale-up networking with 130 TB/s bandwidth per rack. Creates system-level switching costs for the lifetime of deployments. [transcript.json: Jensen Huang]
3. **Performance leadership** — Blackwell NVL72 delivered 30x higher inference throughput vs. H200 on Llama 3.1 (MLPerf). GB300 provides 50% more HBM and 50% more FP4 inference compute vs. B200 for drop-in upgrade. [transcript.json: Colette Kress]
4. **Annual product cadence** — Blackwell → Blackwell Ultra → Rubin roadmap through 2028. [transcript.json: Colette Kress]
5. **Supply chain position** — >50% of TSMC CoWoS capacity reserved through 2027. [ecosystem_signals.md; Corroborated]

### Competitive Risks

- OpenAI reportedly "unsatisfied with some of Nvidia's latest artificial intelligence chips" and has "sought alternatives since last year." [customer_alternatives.md: Reuters, Feb 2, 2026; Single-Source]
- Customer concentration increasing from 30% (top 2) to 54% (top 3) in one year. [latest_10k.json]
- Open-source models making AI capabilities broadly accessible, potentially deployed on competitor platforms. [latest_10k.json: Recent Developments]

---

## Section 3: Supply/Demand Balance

<!-- IC Question: Is industry supply sufficient to meet demand at current prices, and when does that change? What would change: major capacity announcement, demand shock, policy change (tariffs, export controls). -->

### Demand Decomposition

**Backlog:** Management confirmed ">$500 billion in combined Blackwell and Rubin GPU orders stretching into the end of 2026." [backlog_breakdown.md: investing.com, Nov 2025; Corroborated by Yahoo Finance, techbuzz.ai — all Tier 5 sources] NVIDIA does not disclose formal backlog in SEC filings. [Data gap]

**Customer mapping (Q1 FY2027):** Three direct customers at 21%, 17%, 16% of revenue. Named customers from transcript: Microsoft, Google Cloud, Meta, Coreweave, Oracle Cloud, XAI, GM, Mercedes-Benz, AT&T, BYD, Capital One, Foxconn, MediaTek, Telenor. Sovereign AI: Saudi Arabia (500MW project), UAE (5GW campus), Taiwan, Sweden, Japan, Korea, India, Canada, France, UK, Germany, Italy, Spain. [latest_10k.json; transcript.json: Jensen Huang, Colette Kress]

**Customer capex as demand proxy:** Combined 2026 capex guidance from major hyperscalers: ~$630B. [customer_capex.md: Reuters; Corroborated per claim_verification.json] Microsoft Q3 FY2026 capex: $31.9B (+49% YoY), annualized ~$128B, with capacity described as "still tight." [ecosystem_signals.md; Verified per claim_verification.json C029]

The $630B figure represents total capex across all infrastructure (not all GPU purchases). NVIDIA's share of that capex is a subset. [Inference: NVIDIA's FY2027 consensus revenue of $387.3B would represent ~61% of $630B, which is implausible since GPUs are one component alongside networking, storage, power, cooling, and real estate.] [Sources: customer_capex.md, ratings.json]

**Contradicted data point:** Seeking Alpha (Apr 2026) cited 2025 combined capex of $415B. This conflicts with CNBC's $320B combined 2025 guidance and IO Fund's $113.4B in Q3 2025 alone. The $630B 2026 figure is more widely corroborated. [claim_verification.json C084: Contradicted on $415B 2025 baseline]

### Demand Durability

1. **Inference scaling:** Microsoft processed >100 trillion tokens in Q1 (5x YoY). Jensen Huang: "Reasoning AI requires hundreds to thousands more tokens per task." [transcript.json]
2. **Enterprise AI:** ~800 AI factories planned, 100 in flight (2x YoY). [transcript.json: Colette Kress, Jensen Huang]
3. **Sovereign AI:** Countries building national AI platforms. [transcript.json: Jensen Huang]
4. **China demand lost:** China (including HK) fell from $9,659M (21.9% of total) in Q1 FY2026 to $4,550M (5.6%) in Q1 FY2027 following H20 export ban. [latest_10k.json: Geographic Revenue table]

### Supply Constraints

1. **CoWoS Advanced Packaging (primary bottleneck):** NVIDIA reserved >50% of TSMC's CoWoS capacity for 2026, with reservations through 2027. [ecosystem_signals.md; Corroborated] CoWoS capacity projected at 90,000–110,000 wafers per month for 2026. [ecosystem_signals.md: semiwiki.com; Single-Source per claim_verification.json C013 — TSMC does not disclose WPM figures]
2. **HBM Memory:** 2026 HBM supply described as "sold out" across SK Hynix, Micron, and Samsung. [supplier_capacity.md; Corroborated] GB300 requires 50% more HBM than B200. [transcript.json: Colette Kress]
3. **System Assembly:** GB200 NVL72 racks contain 1.2 million components and weigh ~2 tons. [transcript.json: Jensen Huang]

### Supply Addition Timeline

- TSMC building 6 fabs and 2 advanced packaging plants in Arizona. Volume production expected by year-end. [transcript.json: Jensen Huang]
- Foxconn building million-sq-ft factory in Houston. Wistron building in Fort Worth, TX. Spil and Amkor building in Arizona. [transcript.json: Jensen Huang]
- TSMC full-year 2026 revenue growth guided >30% YoY. [ecosystem_signals.md; Verified]
- CEO Huang characterized manufacturing constraints as "scalable two-to-three year problems, not permanent barriers." [supplier_capacity.md: 247wallst.com; Single-Source per claim_verification.json C099]

### Supply/Demand Synthesis

Demand exceeds supply. Orders exceed production capacity per management commentary. The $500B+ reported backlog (Q3 FY2026) against FY2026 actual revenue of $215.9B implies multi-year demand visibility. [Inference: Backlog/revenue ratio >2.3x suggests demand extended well beyond current production.] [Sources: backlog_breakdown.md, income.json]

Gross margin trending from 61.0% GAAP in Q1 FY2026 (impacted by $4.5B H20 write-down; 71.3% ex-write-down) toward management's target of "mid-seventies range late this year." [transcript.json: Colette Kress] No evidence of price concessions. Margins expanding despite massive volume growth. [Inference: Consistent with demand-pull pricing environment.] [Sources: transcript.json, latest_10k.json]

**Contradictory signal:** Inventory rose from $10.1B (FY2025) to $21.4B (FY2026) with DIO at 125 days. [balance.json: inventory; metrics.json: daysOfInventoryOutstanding] A Seeking Alpha article (Feb 2026) flagged this as suggesting "a shift from scarcity to potential overcapacity." [supply_indicators.md; Single-Source per claim_verification.json C108] Year-end inventory includes effects of the $4.5B H20 write-down. [Inference: The inventory build may reflect either pre-positioning for continued growth (Blackwell/GB300 ramp) or early demand moderation; the $4.5B H20 write-down distorts FY2026 inventory figures, and the data does not resolve this ambiguity.] [Sources: balance.json, supply_indicators.md, transcript.json]

### Bargaining Power

**Supply-side:** TSMC has bargaining power as the sole foundry for leading-edge AI GPUs. TSMC's Q1 2026 gross margin was 66.2% (above guidance of 63–65%). [ecosystem_signals.md: investor.tsmc.com; Verified] NVIDIA's long-term commitments provide some contractual protection.

**Demand-side:** Customer concentration (54% from top 3) gives those customers theoretical bargaining power, but NVIDIA's Compute & Networking segment operating margin of 71.5% and expanding gross margin trajectory indicate pricing power is retained by NVIDIA. [latest_10k.json: Operating Income by Reportable Segments]

---

## Section 4: Value Chain

<!-- IC Question: Where is value captured, and is it migrating toward or away from this company? What would change: vertical integration by customer or supplier, margin compression, technology enabling disintermediation. -->

### Value Chain Map

NVIDIA is a **fabless semiconductor company** at the chip design and platform layer. The full chain: [info.json: description; latest_10k.json]

1. **Chip Design & IP** (NVIDIA) — GPU architecture, CUDA, networking IP
2. **Foundry** (TSMC) — Wafer fabrication at advanced nodes
3. **Advanced Packaging** (TSMC CoWoS, ASE, Amkor) — Critical bottleneck
4. **HBM Memory** (SK Hynix, Micron, Samsung) — Sold-out supply
5. **Assembly & Systems** (Foxconn, Quanta, Wistron) — Lowest margin stage
6. **Cloud / End Customer** (Microsoft, Google, Meta, Amazon, Oracle, sovereign entities)

### Margin Capture Across Chain

| Stage | Company | Revenue | Gross Margin | Op. Margin |
|-------|---------|---------|-------------|------------|
| Chip Design (AI GPU) | NVIDIA | $215.9B (FY2026) | 71.1% | 60.4% |
| Chip Design (Competitor) | AMD | $34.6B (CY2025) | 49.5% | 10.7% |
| Chip Design (Custom ASIC) | Broadcom | $63.9B (FY2025) | 67.8% | 39.9% |
| Foundry | TSMC | NT$3,849B (CY2025) | 59.9% | 50.8% |

[income.json; /tmp/tsm_income.json; /tmp/amd_income.json; /tmp/avgo_income.json]

NVIDIA captures the highest margins in the chain. TSMC's 59.9% gross margin (rising to 66.2% in Q1 CY2026) is second, reflecting advanced-node scarcity pricing. [Inference: Both NVIDIA and TSMC are simultaneously expanding margins, indicating the AI compute demand surge creates pricing power at multiple chain stages.] [Sources: income.json, /tmp/tsm_income.json, ecosystem_signals.md]

ODM margins (Foxconn/Hon Hai) historically 6–8% gross margin. [Data gap: No Foxconn financial data in raw files; general knowledge]

### Upstream Dependencies

- **TSMC (foundry):** Single-source dependency. Effectively infinite switching cost in the near-to-medium term. TSMC Q1 2026: revenue $35.9B (+35.1% YoY), gross margin 66.2%, capex $11.1B. [ecosystem_signals.md; Verified]
- **HBM suppliers (SK Hynix, Micron, Samsung):** Multi-source but constrained. HBM is standardized (JEDEC), so switching between suppliers is technically feasible, but qualification cycles and allocation constraints limit flexibility during shortage. [supplier_capacity.md; Corroborated]
- **Manufacturing commitments:** $119B total ($95B payable in remainder of FY2027, balance through FY2031). Additional $30B in cloud service commitments and $6B in other commitments. [latest_10k.json: Note 10]

### Integration Direction

**Backward (toward suppliers):** Networking fully integrated via Mellanox (2020). Grace ARM CPU in-house. Software stack (CUDA, NIMS, Omniverse) in-house. No foundry integration (fabless). [transcript.json; info.json]

**Forward (toward customers):** DGX systems (DGX Spark, DGX Station) are NVIDIA-branded systems sold directly. DGX Cloud is a partnership model (not direct competition with CSPs). NIM software/services extend forward into the application layer. [transcript.json: Colette Kress]

**Customer backward integration:** Google (TPU), Amazon (Trainium), Microsoft (Maia), Meta (custom silicon) are developing alternatives. NVIDIA's NVLink Fusion strategy aims to co-opt these ASICs into the NVIDIA platform rather than compete against them. [transcript.json: Colette Kress]

### Geographic Vulnerability

Taiwan produces substantially 100% of NVIDIA's GPU wafers today. TSMC's Arizona expansion is a partial mitigation but will not reach meaningful scale for several years. [transcript.json: Jensen Huang; ecosystem_signals.md]

---

## Section 5: Capital Structure

<!-- IC Question: How does the company raise money to spend on its business? What would change: major debt issuance or repayment, M&A financing, credit rating change, new equity issuance. -->

### Equity Composition

- **Share class:** Common stock only, no preferred. [EDGAR: Q1 FY2027 10-Q Balance Sheet]
- **Shares outstanding:** 24,221M (April 26, 2026). [EDGAR: Q1 FY2027 10-Q]
- **Diluted shares:** 24,391M (Q1 FY2027 weighted average). [EDGAR: Q1 FY2027 10-Q]
- **Market Cap:** $5,215.5B at $215.33/share. [quote.json: marketCap, price]

### Debt Composition

**Gross debt (unsecured senior notes): $8,500M face value.** Net carrying amount: $8,470M. [EDGAR: Q1 FY2027 10-Q Note 9]
- Short-term portion: $1,000M (3.20% Notes Due 2026, 0.4 years remaining)
- Long-term portion: $7,470M

**Debt Maturity Schedule (face values):**

| Note | Rate | Effective Rate | Maturity | Amount | Remaining |
|------|------|---------------|----------|--------|-----------|
| Due 2026 | 3.20% | 3.31% | Calendar 2026 | $1,000M | 0.4 years |
| Due 2028 | 1.55% | 1.64% | Calendar 2028 | $1,250M | 2.1 years |
| Due 2030 | 2.85% | 2.93% | Calendar 2030 | $1,500M | 3.9 years |
| Due 2031 | 2.00% | 2.09% | Calendar 2031 | $1,250M | 5.1 years |
| Due 2040 | 3.50% | 3.54% | Calendar 2040 | $1,000M | 13.9 years |
| Due 2050 | 3.50% | 3.54% | Calendar 2050 | $2,000M | 23.9 years |
| Due 2060 | 3.70% | 3.73% | Calendar 2060 | $500M | 34.0 years |

[EDGAR: Q1 FY2027 10-Q Note 9]

All notes are unsecured senior obligations with semi-annual interest, redeemable at make-whole premium. Covenants are non-financial in nature; in compliance as of April 26, 2026. [EDGAR: Q1 FY2027 10-Q Note 9]

**Capital lease obligations:** $2,944M (FY2026 end). [balance.json: capitalLeaseObligations]
**Total debt (incl. leases):** $11,412M (FY2026 end). [balance.json: totalDebt]
**Commercial paper program:** $25.0B capacity, $0 outstanding. [EDGAR: Q1 FY2027 10-Q Note 9]

### Convertible Securities

No convertible debt outstanding. The 1.00% Convertible Senior Notes Due 2018 matured/converted previously. [convertible_search.json; convertible_detail.md]

### Cash and Equivalents

**As of FY2026 end (January 25, 2026):**
- Cash and cash equivalents: $10,605M [balance.json: cashAndCashEquivalents]
- Cash and short-term investments: $62,556M [balance.json: cashAndShortTermInvestments]

**As of Q1 FY2027 end (April 26, 2026):**
- Cash and cash equivalents: $13,237M [EDGAR: Q1 FY2027 10-Q]
- Marketable debt securities: $37,098M [EDGAR: Q1 FY2027 10-Q]
- Marketable equity securities: $30,237M [EDGAR: Q1 FY2027 10-Q]
- Total liquid securities: $80,572M [Inference: sum of above] [Sources: EDGAR Q1 FY2027 10-Q]
- Non-marketable securities: $43,364M [EDGAR: Q1 FY2027 10-Q]

### Minority Interest

$0. [balance.json: minorityInterest]

### Enterprise Value

- At FY2026 closing price ($186.47): $4,532.8B [enterprise_value.json: enterpriseValue]
- At current price ($215.33): $5,164.4B [Inference: $5,215.5B mktcap + $11.4B debt − $62.6B cash+STI] [Sources: quote.json, balance.json]

### Net Debt / EBITDA

0.006x [metrics.json: netDebtToEBITDA]. Using FMP's net debt ($807M) / EBITDA ($144.6B). Leverage is negligible. [Inference: FMP net debt = totalDebt − cashAndCashEquivalents ($11,412M − $10,605M = $807M), which differs from the cash+STI-based net cash of $51.1B because FMP uses cash-only in the numerator.] [Sources: balance.json, income.json]

**Share repurchase authorization:** As of April 26, 2026, $38.5B remained. On May 18, 2026, the Board approved an additional $80.0B, bringing total authorization to ~$118.5B (no expiration). [EDGAR: Q1 FY2027 10-Q Note 12]

---

## Discrepancies and Data Gaps

### Cross-Reference Conflicts

1. **Market platform vs. segment revenue mismatch:** Data Center ($75,246M) and Edge Computing ($6,369M) sum to $81,615M, matching total revenue. Compute & Networking ($74,550M) and Graphics ($7,065M) also sum to $81,615M. However, the boundaries differ: Compute & Networking is $696M less than Data Center, and Graphics is $696M more than Edge Computing. [Inference: Some Data Center products (likely professional visualization GPUs used in AI workloads) are in the Graphics reportable segment but classified under Data Center in the market platform view.] [Sources: latest_10k.json]

2. **FMP net debt vs. cash+STI-based net cash:** FMP reports net debt of $807M (totalDebt − cashAndCashEquivalents). Using cash+STI, the company has net cash of $51.1B. The discrepancy is definitional: FMP excludes $52.0B in short-term investments from the net debt calculation. [balance.json]

3. **Goodwill increase vs. acquisition cash outflow:** Goodwill rose $15.6B in FY2026, but acquisition cash outflows were only $1.5B. The gap suggests non-cash deal structures (stock consideration) or timing differences. [Inference: Acquisition may have been paid primarily in stock.] [Sources: balance.json, cashflow.json]

### Data Gaps

1. **FY2026 annual segment breakdown:** Not available from filing data. Web estimate of 89.72% Data Center is Single-Source.
2. **Customer identities:** Top 3 direct customers (21%, 17%, 16%) are unnamed in SEC filings.
3. **Formal backlog:** NVIDIA does not disclose backlog in SEC filings. The $500B+ figure is management commentary from Q3 FY2026. [Data gap]
4. **CoWoS WPM capacity:** 90,000–110,000 WPM estimate is Single-Source (semiwiki.com forum). TSMC does not disclose WPM publicly.
5. **Acquisition target(s):** The $15.6B goodwill increase in FY2026 is unexplained in available filings.
6. **ODM margins:** No Foxconn financial data in raw files.
7. **Annual Data Center revenue for FY2026:** Not separately disclosed in available raw files.
8. **CEO succession plan:** No disclosure in available filings. [latest_10k.json; info.json: ceo]
9. **EDGAR data sources (proxy, facts, exhibits, insider-detail, holders-detail) all returned command_failed** during data gathering. [memory_context.md: Prior source behavior]
10. **Short interest data from FMP was unavailable (404).** Web-sourced short interest (282.9M shares, 1.22% of float) is Tier 5; treat as approximate. [short_interest.md]

---

## Appendix

# Appendix A: Competitive Position — Expanded Analysis

## Market Share and Revenue Comparison

### AI Accelerator Market (Data Center)

| Company | Q1 2026 DC Revenue | YoY Growth | Estimated GPU Share | Source |
|---------|-------------------|------------|-------------------|--------|
| NVIDIA | $75,246M | +92% | 70–95% (wide range) | [latest_10k.json; competitive_by_product.md: CNBC; Single-Source per C042] |
| AMD | $5,780M (incl. EPYC CPUs) | +57% | ~5–7% (GPU only) | [ecosystem_signals.md; Verified C014; siliconanalysts.com Single-Source C023] |
| Intel (Gaudi) | Not separately disclosed | N/A | Minimal | [Inference: absence in transcript.json and competitive data] |
| Broadcom (custom ASIC) | Not separately disclosed | N/A | N/A | [peers.json: AVGO mkt cap $1.96T] |

**Market share data quality caveat:** No Tier 1 or Tier 2 source provides a definitive AI accelerator market share figure with disclosed methodology. The range across sources is 70–95% for NVIDIA. The 13:1 revenue ratio between NVDA and AMD Data Center segments is the most concrete comparison, though AMD's segment includes non-GPU products (EPYC CPUs). [competitive_history.md; competitive_by_product.md; ecosystem_signals.md]

### Revenue Trajectory (NVIDIA)

| Period | Total Revenue | Data Center Rev | DC % of Total | YoY Total Growth |
|--------|--------------|----------------|---------------|-----------------|
| FY2023 | $27.0B | N/A (est. ~60%) | ~60% | +0.2% |
| FY2024 | $60.9B | N/A | N/A | +125.9% |
| FY2025 | $130.5B | N/A | N/A | +114.2% |
| FY2026 | $215.9B | ~$193.7B (est.) | ~89.7% (est.) | +65.5% |
| Q1 FY2027 | $81.6B | $75.2B | 92.2% | +85% |

[income.json; latest_10k.json; business_overview.md for FY2026 DC estimate — Single-Source]

### Earnings Beat History

| Report Date | EPS Actual | EPS Est. | Beat % | Rev Actual | Rev Est. | Beat % |
|-------------|-----------|----------|--------|-----------|---------|--------|
| 2026-05-20 (Q1 FY2027) | $1.87 | $1.76 | +6.3% | $81.6B | $78.4B | +4.1% |
| 2026-02-25 (Q4 FY2026) | $1.62 | $1.54 | +5.2% | $68.1B | $66.1B | +3.0% |
| 2025-11-19 (Q3 FY2026) | $1.30 | $1.26 | +3.2% | $57.0B | $55.0B | +3.7% |
| 2025-08-27 (Q2 FY2026) | $1.05 | $1.01 | +4.0% | $46.7B | $46.0B | +1.5% |
| 2025-05-28 (Q1 FY2026) | $0.81 | $0.74 | +9.9% | $44.1B | $43.3B | +1.7% |
| 2025-02-26 (Q4 FY2025) | $0.89 | $0.85 | +5.0% | $39.3B | $38.1B | +3.2% |
| 2024-11-20 (Q3 FY2025) | $0.81 | $0.75 | +8.0% | $35.1B | $33.2B | +5.8% |
| 2024-08-28 (Q2 FY2025) | $0.68 | $0.65 | +5.4% | $30.0B | $28.8B | +4.4% |
| 2024-05-22 (Q1 FY2025) | $0.61 | $0.56 | +8.9% | $26.0B | $24.6B | +5.9% |

[earnings.json: epsActual, epsEstimated, revenueActual, revenueEstimated]

9 out of 9 quarters beat on both EPS and revenue. Average EPS beat: +6.2%. Average revenue beat: +3.7%.

## Product-by-Product Competitive Landscape

### Data Center GPUs (Blackwell/Hopper)

**Competitors:**
- **AMD Instinct MI350/MI400/MI500:** MI350 launched Q2 2025 with 288GB HBM3e. MI400 confirmed for 2026 with CDNA 5 architecture and 432GB HBM4. MI500 on 2027 roadmap. AMD ROCm software ecosystem is an alternative to CUDA but has lower developer adoption. [ecosystem_signals.md; C020 Contradicted on MI350 launch timing]
- **Google TPU (v5p, Trillium):** Custom silicon for Google's internal workloads. Cannot run CUDA. [customer_alternatives.md]
- **Amazon Trainium/Inferentia:** Custom chips for AWS. [customer_alternatives.md]
- **Microsoft Maia 100:** Early-stage custom accelerator. [customer_alternatives.md]

**NVIDIA performance claims:**
- Blackwell NVL72 delivered 30x higher inference throughput vs. H200 on Llama 3.1 (MLPerf). [transcript.json: Colette Kress]
- Software optimizations improved Blackwell performance 1.5x in one month. [transcript.json: Colette Kress]
- Hopper inference performance improved 4x over two years through software updates. [transcript.json: Colette Kress]

### Networking (InfiniBand, Spectrum-X, NVLink)

- NVLink is proprietary; no direct competitor at the scale-up interconnect layer.
- Spectrum-X competes with traditional Ethernet solutions for AI workloads. Annualizing >$8B. Customers include Coreweave, Microsoft Azure, Oracle Cloud, XAI, Google Cloud, Meta. [transcript.json: Colette Kress]
- InfiniBand competes with high-speed Ethernet for HPC/AI networking.

### Gaming (GeForce RTX 50-series)

- Competes with AMD Radeon RX series.
- NVIDIA's gaming revenue: record $3.8B in Q1 FY2026 (+42% YoY). 100M installed base. [transcript.json: Colette Kress]
- RTX 5060 starts at $299, extending AI-capable GPUs to mainstream price points. [transcript.json: Colette Kress]

## Switching Costs

**Technical:** CUDA (18+ years), NVLink (proprietary interconnect, 130 TB/s/rack), software stack (NIMS, Nemo, Omniverse). [transcript.json]

**Financial:** GB200 NVL72 racks contain 1.2M components, weigh ~2 tons. Major hyperscalers deploying ~1,000 NVL72 racks/week (72,000 GPUs/week each). [transcript.json: Jensen Huang, Colette Kress]

**Evidence of switching attempts:** OpenAI reportedly seeking alternatives (Reuters, Feb 2, 2026). Hyperscalers developing custom ASICs. NVIDIA's NVLink Fusion is the counter-strategy. [customer_alternatives.md; transcript.json]

## Competition Evolution (5-Year)

- FY2022 (pre-AI boom): NVIDIA ~$27B revenue, gaming-led. AMD was the primary GPU competitor.
- FY2024–FY2026 (AI explosion): Revenue surged 8x. Data Center overtook gaming (now 92%+). AMD Instinct emerged but gap widened in absolute terms. Custom ASIC programs accelerated. [income.json; ecosystem_signals.md]
- Startup competitors (Graphcore, SambaNova, Cerebras) have not achieved meaningful scale. Graphcore was acquired by SoftBank. [competitive_by_product.md; Tier 5 source]
- Barriers to entry have increased: larger CUDA ecosystem, NVLink rack-scale lock-in, CoWoS capacity reservations, R&D at $18.5B/year. [income.json; ecosystem_signals.md; transcript.json]

# Appendix B: Supply/Demand Analysis — Expanded

## Demand Analysis

### Backlog

- Management confirmed ">$500 billion in combined Blackwell and Rubin GPU orders stretching into the end of 2026." [backlog_breakdown.md: investing.com, Nov 25, 2025; Tier 5 source; Corroborated by Yahoo Finance, techbuzz.ai]
- Jensen Huang at Q1 FY2026 earnings: "We have more orders today than we did at the last time I spoke about orders at GTC." [transcript.json: Jensen Huang, Q&A response to C.J. Muse]
- NVIDIA does not disclose formal backlog numbers in SEC filings. The $500B figure comes from management commentary, not a filed document. [Data gap]
- Backlog-to-revenue ratio: $500B+ / $215.9B FY2026 revenue = >2.3x. [Inference: ratio calculation] [Sources: backlog_breakdown.md, income.json]

### Customer Capex Corroboration

| Customer | Capex Data Point | Source | Verification |
|----------|-----------------|--------|-------------|
| Microsoft | Q3 FY2026 capex $31.9B (+49% YoY) | ecosystem_signals.md | Verified C029 |
| Big 4 Tech combined | 2026 capex guidance ~$630B | customer_capex.md (Reuters) | Corroborated |
| Big 4 Tech combined | 2025 capex $415B | customer_capex.md (Seeking Alpha) | Contradicted C084 — conflicts with CNBC's $320B |
| IO Fund | Big Tech Q3 2025 capex $113.4B (+75% YoY) | customer_capex.md | Single-Source C077 |
| Microsoft | Azure grew 39–40% across FY26 Q1-Q3, capacity "still tight" | ecosystem_signals.md (futurumgroup.com) | Tier 4 |

### Demand Drivers

1. **Inference scaling:** Microsoft processed >100 trillion tokens in Q1 (5x YoY). Jensen Huang: "Reasoning AI requires hundreds to thousands more tokens per task than previous one-shot inference." [transcript.json: Jensen Huang, Colette Kress]
2. **Enterprise AI:** ~800 AI factories planned. 100 NVIDIA-powered AI factories in flight (2x YoY), with average GPU count per factory also doubling. [transcript.json: Colette Kress, Jensen Huang]
3. **Sovereign AI:** Saudi Arabia (500MW project), UAE (5GW campus), Taiwan, Sweden, Japan, Korea, India, Canada, France, UK, Germany, Italy, Spain. [transcript.json: Jensen Huang]
4. **Automotive:** Revenue $567M in Q1 FY2026 (+72% YoY). Partnerships with GM, Mercedes-Benz, BYD. [transcript.json: Colette Kress]

### China Demand Loss

- April 9, 2025: H20 export controls enacted with no grace period. [transcript.json: Colette Kress]
- Q1 FY2026 impact: $4.6B H20 revenue recognized (pre-April 9) + $4.5B inventory write-down + $2.5B planned shipments unfulfilled. [transcript.json: Colette Kress]
- China (incl. HK) Q1 FY2027: $4,550M (5.6% of total), down from $9,659M (21.9%) in Q1 FY2026 — a 53% YoY decline. [latest_10k.json: Geographic Revenue table]
- Management estimate of China AI market: ~$50B total. [transcript.json: Colette Kress]
- CEO Huang: "the new limits pretty much makes it impossible for us to reduce Hopper any further...for any productive use...We have some limited options...We don't have anything at the moment." [transcript.json: Jensen Huang, Q&A response to Tim Arcuri, UBS]
- H200 licensing program: "To date, we have not generated any revenue under the H200 licensing program." [latest_10k.json: Recent Developments]

## Supply Analysis

### Constraint 1: CoWoS Advanced Packaging (Primary Bottleneck)

- NVIDIA reserved >50% of TSMC's CoWoS capacity for 2026, extending through 2027. [ecosystem_signals.md: cnbc.com Apr 8, 2026; Astute Group Aug 2025 reports 60%; Corroborated]
- CoWoS capacity projected at 90,000–110,000 WPM for 2026. [ecosystem_signals.md: semiwiki.com; Single-Source per C013 — TSMC does not publicly disclose WPM figures]
- Broadcom CEO confirmed TSMC capacity will be a bottleneck through 2027. [supplier_capacity.md: Yahoo Finance, Mar 23, 2026]

### Constraint 2: HBM Memory

- "Sold-out capacity from SK Hynix & Micron." [supplier_capacity.md; Corroborated by Micron CEO statement and SK Hynix reports]
- Lead times for H100/H200 running 36–52 weeks. [supply_indicators.md: spheron.network; Tier 5 source; Corroborated by 3 sources per claim_verification.json]
- GB300 requires 50% more HBM than B200. [transcript.json: Colette Kress]

### Constraint 3: System Assembly

- GB200 NVL72 racks: 1.2 million components, ~2 tons each. "No one has produced supercomputers on this scale." [transcript.json: Jensen Huang]
- Manufacturing yields have shown "significant improvement." [transcript.json: Colette Kress]

### Supply Addition Timeline

| Initiative | Detail | Timeline | Source |
|-----------|--------|----------|--------|
| TSMC Arizona fabs | 6 fabs + 2 packaging plants | Volume production by year-end 2026 | [transcript.json: Jensen Huang] |
| Foxconn Houston | 1M sq ft factory for NVIDIA AI supercomputers | Under construction | [transcript.json: Jensen Huang] |
| Wistron Fort Worth | Assembly facility | Under construction | [transcript.json: Jensen Huang] |
| Spil + Amkor Arizona | Packaging/assembly/test | Under construction | [transcript.json: Jensen Huang] |
| TSMC revenue growth | >30% YoY guided for full-year 2026 | Calendar 2026 | [ecosystem_signals.md; Verified] |

### Capacity Gap Timeline

Jensen Huang characterized manufacturing bottlenecks as "scalable two-to-three year problems, not permanent barriers." [supplier_capacity.md: 247wallst.com, Apr 21, 2026; Single-Source per C099]

New fab construction typically takes 2–3 years from announcement to volume production. CoWoS capacity additions at TSMC are expanding to est. 90K–110K WPM by 2026. [ecosystem_signals.md; Single-Source]

## Inventory Signal Analysis

Inventory rose from $10.1B (FY2025) to $21.4B (FY2026), with DIO at 125 days (up from 113 days). [balance.json: inventory; metrics.json: daysOfInventoryOutstanding]

A Seeking Alpha article (Feb 2026) flagged inventory at $19.7B and 105 days as suggesting "a shift from scarcity to potential overcapacity." [supply_indicators.md; Single-Source per C108 — refers to an interim quarter, not year-end]

Countervailing evidence: Q1 FY2027 revenue was $81.6B (+85% YoY, +20% QoQ), suggesting demand remains robust. The inventory build may reflect supply chain pre-positioning for continued growth (building ahead of Blackwell/GB300 ramp) rather than demand softening. The $4.5B H20 write-down in Q1 FY2026 distorts FY2026 inventory figures. [Inference: Inventory build is consistent with both demand strength and potential over-ordering; the data does not resolve this ambiguity.] [Sources: balance.json, earnings.json, transcript.json]

# Appendix C: Value Chain — Expanded Analysis

## Full Value Chain Map

### Stage 1: Chip Design & IP (NVIDIA)

- GPU architecture design: Blackwell (B200, GB200, GB300), Hopper (H100, H200), Ada Lovelace (consumer GPUs)
- CUDA software ecosystem, NIM microservices, Omniverse, Isaac (robotics), Cosmos (world models)
- Networking IP: NVLink, InfiniBand, Spectrum-X Ethernet
- Grace ARM CPU (in-house design)
- Other participants: AMD, Intel, Broadcom (custom ASICs), Google/Amazon/Microsoft (in-house ASICs)
[info.json: description; latest_10k.json; transcript.json]

### Stage 2: Foundry / Wafer Fabrication (TSMC)

- TSMC fabricates NVIDIA's advanced-node chips (4nm, 3nm processes)
- TSMC Q1 2026: revenue $35.9B (+35.1% YoY), gross margin 66.2%, operating margin 58.1%, capex $11.1B [ecosystem_signals.md: investor.tsmc.com; Verified]
- TSMC full-year 2026 revenue growth guided >30% YoY [ecosystem_signals.md; Corroborated]
- TSMC Q2 2026 guidance: revenue $39.0–40.2B, gross margin 65.5–67.5% [ecosystem_signals.md; Verified]
- TSMC building 6 fabs + 2 advanced packaging plants in Arizona; volume production expected by year-end [transcript.json: Jensen Huang]
- Other participants: Samsung Foundry, Intel Foundry — not viable alternatives for Blackwell/Rubin at current scale

### Stage 3: Advanced Packaging (TSMC CoWoS, ASE, Amkor)

- CoWoS (Chip-on-Wafer-on-Substrate) critical for HBM integration
- NVIDIA reserved >50% of TSMC CoWoS capacity for 2026, extending through 2027 [ecosystem_signals.md; Corroborated]
- CoWoS capacity: est. 90,000–110,000 WPM for 2026 [ecosystem_signals.md: semiwiki.com; Single-Source per C013]
- Amkor and SPIL investing in Arizona packaging facilities [transcript.json: Jensen Huang]

### Stage 4: High Bandwidth Memory (SK Hynix, Micron, Samsung)

- Three suppliers for HBM3e/HBM4
- 2026 HBM supply described as "sold out" [supplier_capacity.md; Corroborated]
- GB300 requires 50% more HBM than B200 [transcript.json: Colette Kress]
- HBM is a known bottleneck alongside CoWoS [supplier_capacity.md; Corroborated]

### Stage 5: Assembly, Test, System Integration

- ODMs/OEMs: Foxconn, Quanta, Wistron
- Foxconn building million-sq-ft factory in Houston for NVIDIA AI supercomputers [transcript.json: Jensen Huang]
- Wistron building similar plant in Fort Worth, Texas [transcript.json: Jensen Huang]
- ODM margins typically 6–8% gross [Data gap: general knowledge, no Foxconn data in raw files]

### Stage 6: Cloud Deployment / End Customer

- CSPs: Microsoft, Google, Meta, Amazon, Oracle
- Sovereign AI entities: Saudi Arabia, UAE, Taiwan, Sweden, Japan, Korea, India, etc.
- Enterprise customers via CSPs
- Direct customers include AIBs, distributors, ODMs, OEMs, CSPs, system integrators [latest_10k.json: customer classification]

## Margin Capture Comparison

| Value Chain Stage | Company | Revenue | Gross Margin | Op. Margin | R&D % Rev |
|-------------------|---------|---------|-------------|------------|-----------|
| Chip Design (AI GPU) | NVIDIA | $215.9B (FY2026) | 71.1% | 60.4% | 8.6% |
| Chip Design (Competitor) | AMD | $34.6B (CY2025) | 49.5% | 10.7% | 23.4% |
| Chip Design (Custom ASIC) | Broadcom | $63.9B (FY2025) | 67.8% | 39.9% | 17.2% |
| Foundry | TSMC | NT$3,849B (CY2025) | 59.9% | 50.8% | 6.5% |
| ODM/Assembly | Foxconn | N/A | ~6–8% (est.) | N/A | N/A |

[income.json; /tmp/tsm_income.json; /tmp/amd_income.json; /tmp/avgo_income.json; Foxconn: data gap]

## Historical Margin Migration

| Year | NVDA Gross Margin | TSMC Gross Margin | AMD Gross Margin | Broadcom Gross Margin |
|------|------------------|------------------|-----------------|---------------------|
| FY/CY 2021 | 62.3% | 51.6% | 48.2% | 61.4% |
| FY/CY 2022 | 64.9% | 59.6% | 44.9% | 66.5% |
| FY/CY 2023 | 56.9% | 54.4% | 46.1% | 68.9% |
| FY/CY 2024 | 72.7% | 56.1% | 49.4% | 63.0% |
| FY/CY 2025 | 75.0% | 59.9% | 49.5% | 67.8% |
| FY/CY 2026 / Latest | 71.1% (FY26) | 66.2% (Q1'26) | — | — |

[income.json; /tmp/tsm_income.json; /tmp/amd_income.json; /tmp/avgo_income.json]

Both NVIDIA and TSMC margins have expanded simultaneously during the AI cycle. [Inference: The AI compute demand surge creates pricing power at multiple chain stages simultaneously.] [Sources: income.json, /tmp/tsm_income.json, ecosystem_signals.md]

## Integration Analysis

### Backward Integration (Toward Suppliers)
- **Networking: Fully integrated** — Mellanox acquired 2020 ($6.9B). Networking revenue ~$5B/quarter.
- **CPU: Integrated** — Grace ARM CPU designed in-house for GB200 "superchip."
- **Software: Fully integrated** — CUDA, NIMS, Omniverse, Isaac, Cosmos all in-house.
- **Foundry: No integration** — Remains fabless. No evidence of plans to build foundries.

### Forward Integration (Toward Customers)
- **Systems: Partial** — DGX systems (Spark: 1 petaflop, Station: 20 petaflops) sold directly.
- **Cloud: Minimal** — DGX Cloud is partnership model, not direct CSP competition.
- **Software/AI services** — NIM, NVIDIA AI Enterprise extends into application layer.

### Customer Backward Integration (Key Competitive Dynamic)
- Google: TPU (multiple generations deployed internally)
- Amazon: Trainium, Inferentia
- Microsoft: Maia 100
- Meta: Custom silicon investment

NVIDIA's NVLink Fusion counter-strategy enables custom ASICs to connect to NVIDIA's NVLink fabric, converting potential displacement into platform expansion. Partners: MediaTek, Marvell, Alchip, Astera Labs, Qualcomm. [transcript.json: Colette Kress]

## Dependencies and Vulnerabilities Summary

| Dependency | Severity Quantification | Mitigation |
|-----------|------------------------|------------|
| TSMC foundry | 100% of advanced GPU wafers | Arizona fabs under construction; no near-term alternative |
| CoWoS packaging | >50% of TSMC capacity reserved | Amkor, SPIL expanding; 2–3 year constraint per CEO |
| HBM memory | 3 suppliers, all sold out for 2026 | Multi-sourced but constrained; GB300 needs 50% more |
| Top 3 customers | 54% of Q1 FY2027 revenue | No minimum purchase commitments disclosed |
| China market | Lost ~$50B TAM from H20 export ban | H200 licensing program generating $0 to date |
| Taiwan geography | All GPU wafers produced in Taiwan today | TSMC Arizona fabs partial mitigation |

# Appendix D: Capital Structure — Full Detail

## Equity Composition

- **Share class:** Common stock only. No preferred stock. [EDGAR: Q1 FY2027 10-Q Balance Sheet]
- **Shares outstanding:** 24,221M (as of April 26, 2026) [EDGAR: Q1 FY2027 10-Q]
- **Diluted shares (weighted average):** 24,391M (Q1 FY2027) [EDGAR: Q1 FY2027 10-Q]
- **Float:** 23,270M (96.1% of outstanding) [shares_float.json: floatShares, freeFloat]
- **Dual-class:** No. Single class of common stock. [info.json; EDGAR 10-Q]

### Diluted Share Count Trend

| Period | Diluted Shares (M) | Change |
|--------|-------------------|--------|
| FY2022 | 25,350 | — |
| FY2023 | 25,070 | -1.1% |
| FY2024 | 24,940 | -0.5% |
| FY2025 | 24,804 | -0.5% |
| FY2026 | 24,432 | -1.5% |
| Q1 FY2027 | 24,391 | -0.2% (QoQ) |

[income.json: weightedAverageShsOutDil; EDGAR Q1 FY2027 10-Q]

4-year CAGR: approximately -0.9% annualized. Buybacks exceed SBC dilution.

## Market Cap

$5,215.5B at $215.33/share (as of May 22, 2026). [quote.json: marketCap, price]

## Debt Composition and Tranches

### Senior Unsecured Notes: $8,500M face value

| Note | Coupon | Effective Rate | Maturity | Face Value | Carrying Value | Remaining Term |
|------|--------|---------------|----------|------------|---------------|----------------|
| Due Sep 2026 | 3.20% | 3.31% | Calendar 2026 | $1,000M | Short-term | 0.4 years |
| Due Jun 2028 | 1.55% | 1.64% | Calendar 2028 | $1,250M | Long-term | 2.1 years |
| Due Apr 2030 | 2.85% | 2.93% | Calendar 2030 | $1,500M | Long-term | 3.9 years |
| Due Jun 2031 | 2.00% | 2.09% | Calendar 2031 | $1,250M | Long-term | 5.1 years |
| Due Apr 2040 | 3.50% | 3.54% | Calendar 2040 | $1,000M | Long-term | 13.9 years |
| Due Apr 2050 | 3.50% | 3.54% | Calendar 2050 | $2,000M | Long-term | 23.9 years |
| Due Apr 2060 | 3.70% | 3.73% | Calendar 2060 | $500M | Long-term | 34.0 years |

[EDGAR: Q1 FY2027 10-Q Note 9]

- Net carrying amount: $8,470M (after unamortized discount/issuance costs)
- Fair value of all notes: ~$7.4B (vs. $8.5B face) as of April 26, 2026
- All notes are unsecured senior obligations, semi-annual interest, redeemable at make-whole premium
- Covenants: Non-financial in nature; in compliance as of April 26, 2026
- Weighted average coupon: approximately 2.7% [Inference: weighted by face value] [Sources: EDGAR Q1 FY2027 10-Q Note 9]

### Capital Lease Obligations

$2,944M (FY2026 end). [balance.json: capitalLeaseObligations]

### Total Debt (Including Leases)

$11,412M (FY2026 end). [balance.json: totalDebt]

Note: FMP totalDebt includes capital lease obligations alongside notes payable.

### Debt Maturity Profile

- Within 1 year: $1,000M (3.20% Due 2026)
- 1–3 years: $1,250M (1.55% Due 2028)
- 3–5 years: $1,500M (2.85% Due 2030)
- 5–10 years: $1,250M (2.00% Due 2031)
- 10+ years: $3,500M (Due 2040/2050/2060)

The only near-term maturity is $1.0B due in Calendar 2026. The remaining $7.5B in notes is distributed across maturities through 2060.

## Commercial Paper Program

$25.0B capacity, $0 outstanding as of April 26, 2026. [EDGAR: Q1 FY2027 10-Q Note 9]

## Convertible Debt

No convertible debt outstanding. The 1.00% Convertible Senior Notes Due 2018 matured/converted previously. [convertible_search.json; convertible_detail.md]

## Cash and Equivalents

### As of FY2026 End (January 25, 2026)

| Component | Amount |
|-----------|--------|
| Cash and cash equivalents | $10,605M |
| Short-term investments | $51,951M |
| Cash and short-term investments | $62,556M |
| Long-term investments | $22,251M |

[balance.json]

### As of Q1 FY2027 End (April 26, 2026)

| Component | Amount |
|-----------|--------|
| Cash and cash equivalents | $13,237M |
| Marketable debt securities | $37,098M |
| Marketable equity securities | $30,237M |
| **Total liquid securities** | **$80,572M** |
| Non-marketable securities | $43,364M |

[EDGAR: Q1 FY2027 10-Q Balance Sheet]

Non-marketable securities surged from $22.3B (FY2026 end) to $43.4B (Q1 FY2027 end), reflecting $18.6B in purchases during the quarter. NVIDIA disclosed: "Some of these investments include AI model makers that may indirectly purchase or use our products in the cloud." [latest_10k.json: Recent Developments]

Marketable equity securities of $30.2B include $8.9B subject to lock-up restrictions through December 2027. [latest_10k.json: Note 7]

## Minority Interest

$0. [balance.json: minorityInterest]

## Enterprise Value

| Basis | Amount | Components |
|-------|--------|-----------|
| At FY2026 close ($186.47) | $4,532.8B | MktCap $4,532.0B + Debt $11.4B − Cash $10.6B |
| At current price ($215.33) | $5,164.4B | MktCap $5,215.5B + Debt $11.4B − Cash&STI $62.6B |

[enterprise_value.json for FY2026; Inference for current: quote.json, balance.json]

## Net Debt / EBITDA

0.006x [metrics.json: netDebtToEBITDA]

Computation: FMP net debt $807M (totalDebt $11,412M − cashAndCashEquivalents $10,605M) / EBITDA $144,552M. [balance.json; income.json]

Using cash+STI basis: Net cash of $51,144M (cashAndShortTermInvestments $62,556M − totalDebt $11,412M). Leverage is negligible by any measure.

## Share Repurchase and Capital Return

- FY2026: $40.1B in share repurchases + $974M dividends = $41.1B total return. [cashflow.json]
- Q1 FY2027: $19.3B repurchases + $2.1B tax withholding + $243M dividends = $21.6B total return. [EDGAR Q1 FY2027 10-Q]
- Remaining authorization: $38.5B as of Apr 26, 2026. Additional $80.0B approved May 18, 2026. Total: ~$118.5B (no expiration). [EDGAR Q1 FY2027 10-Q Note 12]
- Dividend: $0.04/share annual ($0.01/quarter). Yield: 0.02%. [EDGAR Q1 FY2027 10-Q]

## Off-Balance Sheet Commitments

- Manufacturing, supply, and capacity commitments: $119B total ($95B in remainder of FY2027, balance through FY2031). [latest_10k.json: Note 10]
- Multi-year cloud service commitments: $30B total ($6B FY2027, $7B FY2028, $7B FY2029, $5B FY2030, $3B FY2031, $2B FY2032+). [latest_10k.json: Note 10]
- Facility lease guarantees: $3.5B maximum gross exposure. Partners placed $712M in escrow. [latest_10k.json: Note 8]

# Appendix E: Key Stats — Full Detail with Computation Methodology

## Price and Trading

| Metric | Value | Source |
|--------|-------|--------|
| Price | $215.33 (May 22, 2026) | [quote.json: price] |
| 52-Week Range | $132.92–$236.54 | [quote.json: yearLow, yearHigh] |
| ADV (30d, $) | $35.0B | [technicals.json: adv_30d] |
| Avg Volume (30d, shares) | 162,651,462 | [technicals.json: avg_volume_30d] |
| ADV (computed) | $36,882M | [Inference: 171,279,452 × $215.33 / 1e6] [Sources: info.json averageVolume, price] |
| RSI (14) | 53.7 | [technicals.json: rsi_14] |
| 21d EMA | $214.12 | [technicals.json: ema_21d] |
| 50d SMA | $196.81 | [technicals.json: sma_50d] |
| 200d SMA | $187.03 | [technicals.json: sma_200d] |
| Beta | 2.244 | [info.json: beta] |

Note: Two ADV figures available. technicals.json reports $35.0B using a 30-day lookback. info.json averageVolume × current price yields $36.9B. The difference reflects that technicals.json ADV was computed using the 30-day price-volume product, while the info.json method uses current price × average volume.

## Valuation Multiples

All multiples computed from raw data. Not copied from third-party sources.

| Metric | Value | Computation | Sources |
|--------|-------|-------------|---------|
| Trailing P/E | 43.9x | $215.33 / $4.90 FY2026 diluted EPS | [quote.json, income.json: epsDiluted] |
| Forward P/E (FY2027E) | 24.4x | $215.33 / $8.84 consensus EPS | [quote.json, ratings.json: epsAvg FY2027] |
| Forward P/E (FY2028E) | 17.5x | $215.33 / $12.34 consensus EPS | [quote.json, ratings.json: epsAvg FY2028] |
| Q1 FY2027 Run-Rate P/E | 22.5x | $215.33 / ($2.39 × 4 = $9.56) | [Inference: EDGAR Q1 FY2027 diluted EPS annualized] |
| Q1 FY2027 Operating P/E | 29.3x | $215.33 / ($1.84 × 4 = $7.36) | [Inference: Ex-equity gains; $15.9B gains × (1−16.6%) / 24,391M = $0.545/sh from equity gains; $2.39 − $0.55 = $1.84] [Sources: EDGAR Q1 FY2027 10-Q] |
| EV/EBITDA (FY2026 close) | 31.4x | $4,532.8B / $144.6B | [enterprise_value.json, income.json: ebitda] |
| EV/EBITDA (current price) | 35.7x | $5,164.4B / $144.6B | [Inference: computed EV / FY2026 EBITDA] [Sources: quote.json, balance.json, income.json] |
| EV/Revenue (current) | 23.9x | $5,164.4B / $215.9B | [Inference: computed] [Sources: quote.json, balance.json, income.json] |
| P/FCF (FY2026) | 53.9x | $5,215.5B / $96.7B | [quote.json: marketCap; cashflow.json: freeCashFlow] |
| P/FCF ex-SBC | 57.8x | $5,215.5B / ($96.7B − $6.4B SBC) | [quote.json; cashflow.json: freeCashFlow, stockBasedCompensation] |
| Dividend Yield | 0.02% | $0.04 annual / $215.33 | [EDGAR Q1 FY2027 10-Q; quote.json] |
| Earnings Yield | 2.6% | $4.90 / $215.33 | [metrics.json: earningsYield] |

## Short Interest

| Metric | Value | Source |
|--------|-------|--------|
| Shares Short | 282,930,000 | [short_interest.md: shortsqueeze.com; Tier 5] |
| Short % of Float | ~1.22% | [short_interest.md: Benzinga 1.22%] |
| Float Shares | 23,270,042,400 | [shares_float.json: floatShares] |
| Free Float % | 96.1% | [shares_float.json: freeFloat] |
| Days to Cover | ~1.2–1.9 | [short_interest.md: Benzinga 1.88, Webull 1.23] |

Note: FMP short_interest endpoint returned 404. Web sources are Tier 5; treat as approximate.

## Profitability

| Fiscal Year | Revenue | Gross Margin | Operating Margin | Net Margin | EBITDA Margin |
|-------------|---------|-------------|-----------------|-----------|--------------|
| FY2026 | $215.9B | 71.1% | 60.4% | 55.6% | 66.9% |
| FY2025 | $130.5B | 75.0% | 62.4% | 55.8% | 66.0% |
| FY2024 | $60.9B | 72.7% | 54.1% | 48.8% | 58.4% |
| FY2023 | $27.0B | 56.9% | 15.7% | 16.2% | 22.2% |
| FY2022 | $26.9B | 64.9% | 37.3% | 36.2% | 42.2% |

[income.json: grossProfit/revenue, operatingIncome/revenue, netIncome/revenue, ebitda/revenue]

Q1 FY2027: Gross margin 74.9%, operating margin 65.6%, reported net margin 71.5% (includes $15.9B equity gains). Operating-level net margin ~55%. [EDGAR: Q1 FY2027 10-Q]

## Returns on Capital

| Fiscal Year | ROIC | ROE | ROCE | WACC (est.) | ROIC-WACC Spread |
|-------------|------|-----|------|-------------|-----------------|
| FY2026 | 62.9% | 76.3% | 74.7% | ~15.6% | +47.3 pp |
| FY2025 | 75.3% | 91.9% | 87.1% | ~15.6% | +59.7 pp |
| FY2024 | 51.3% | 69.2% | 59.8% | ~15.6% | +35.7 pp |
| FY2023 | 11.7% | 19.8% | N/A | ~15.6% | −3.9 pp |
| FY2022 | 24.6% | 36.6% | N/A | ~15.6% | +9.0 pp |

[metrics.json: returnOnInvestedCapital, returnOnEquity, returnOnCapitalEmployed]

WACC estimate: Cost of equity 15.6% (risk-free 4.4% + beta 2.244 × ERP 5.0%); cost of debt after-tax 1.9% ($259M/$11.4B × (1−15.1%)); debt weight 0.2% of total capital. [Inference: CAPM-based] [Sources: info.json, income.json, balance.json]

## Cash Flow

| Fiscal Year | Revenue | Operating CF | CapEx | FCF | FCF Margin | FCF/NI |
|-------------|---------|-------------|-------|-----|------------|--------|
| FY2026 | $215.9B | $102.7B | $6.0B | $96.7B | 44.8% | 80.5% |
| FY2025 | $130.5B | $64.1B | $3.2B | $60.9B | 46.6% | 83.5% |
| FY2024 | $60.9B | $28.1B | $1.1B | $27.0B | 44.4% | 90.8% |
| FY2023 | $27.0B | $5.6B | $1.8B | $3.8B | 14.1% | 87.2% |

[cashflow.json: netCashProvidedByOperatingActivities, capitalExpenditure, freeCashFlow; income.json]

## Greenwald Value Decomposition

### Asset Reproduction Value

| Component | Amount | Source |
|-----------|--------|--------|
| Total stockholders' equity | $157,293M | [balance.json: totalStockholdersEquity] |
| Less: Goodwill | ($20,832M) | [balance.json: goodwill] |
| Less: Intangible assets | ($3,306M) | [balance.json: intangibleAssets] |
| **Tangible Book Value** | **$133,155M** | [Inference: equity − goodwill − intangibles] |
| TBV per share | $5.50 | [Inference: $133.2B / 24,221M shares] [Sources: balance.json, shares_float.json] |

### Earnings Power Value (EPV)

Normalized earnings (FY2026 net income): $120,067M. [income.json: netIncome]
Capitalization rate (cost of equity): 15.6%. [Inference: CAPM]
EPV: $769B ($120.1B / 0.156). EPV per share: $31.74. [Inference: earnings power calculation] [Sources: income.json, info.json]

Sensitivity: At 12% CoE → EPV $1,001B ($41.34/sh). At 10% CoE → EPV $1,201B ($49.59/sh).

### Franchise Value

Market Cap $5,215.5B − EPV $769B = Franchise Value $4,447B (85.3% of market cap). [Inference: calculation] [Sources: quote.json, income.json, info.json]

## Analyst Estimates

| Fiscal Year | Revenue Consensus | EPS Consensus | # Analysts (Rev) | # Analysts (EPS) |
|-------------|------------------|--------------|-------------------|------------------|
| FY2027 | $387.3B | $8.84 | 46 | 46 |
| FY2028 | $499.0B | $12.34 | 44 | 44 |
| FY2029 | $577.8B | $14.65 | 33 | 33 |
| FY2030 | $665.3B | $16.71 | 24 | 15 |

[ratings.json: estimates]

Price target consensus: median $307.12 (mean $300.05), range $140–$500. Last month average: $313.20 (25 analysts). [ratings.json: price_target_consensus, price_target_summary]

## Scoring

| Score | Value | Source |
|-------|-------|--------|
| Altman Z-Score | 53.8 | [scores.json: altmanZScore] |
| Piotroski Score | 7 of 9 | [scores.json: piotroskiScore] |

# Appendix F: Risk Factors — Expanded Enumeration

## Customer Concentration

**Three direct customers represented 54% of Q1 FY2027 revenue.** In Q1 FY2027, three direct customers individually represented 21%, 17%, and 16% of total revenue ($81,615M), combining for approximately $44.1B. All three were primarily attributable to the Compute & Networking segment. [latest_10k.json: Concentration of Revenue section]

**Concentration is increasing.** In Q1 FY2026, two direct customers represented 16% and 14% of total revenue ($44,062M), combining for 30% ($13.2B). The number of >10% customers rose from two to three, and total concentration increased from 30% to 54% in one year. [latest_10k.json: Q1 FY2026 comparatives]

**Indirect customer concentration:** One unnamed "AI research and deployment company" contributed to "a meaningful amount of our revenue" by purchasing cloud services from direct customers. [latest_10k.json: Indirect Customers] [Inference: Widely understood to refer to OpenAI purchasing via Microsoft Azure.] [Sources: latest_10k.json, transcript.json]

**AR concentration:** Three direct customers accounted for 30%, 18%, and 16% of accounts receivable ($38.5B balance at Q1 FY2027). [latest_10k.json: AR concentration]

**No minimum purchase commitments** or multi-year deal terms disclosed. [latest_10k.json: Concentration of Revenue section]

## Cyclicality

Revenue increased 8x from FY2023 trough ($27.0B) to FY2026 ($215.9B) in 3 fiscal years. [income.json]

FY2023 demonstrated that operating leverage works in both directions: revenue was flat (+0.2% YoY) but operating income fell 58% ($10.0B → $4.2B), with operating margin collapsing from 37.3% to 15.7%. [income.json]

Hyperscaler AI capex cycle dependency: Data Center revenue (92.2% of total) is tied to customer infrastructure spending. Any reduction in AI spending would directly impact NVIDIA. [latest_10k.json; customer_capex.md]

## Technology Disruption

**Custom ASICs from hyperscaler customers:**
- Google TPU (multiple generations). [customer_alternatives.md]
- Amazon Trainium and Inferentia. [customer_alternatives.md]
- Microsoft Maia 100. [customer_alternatives.md]

**OpenAI seeking alternatives.** Reuters (Feb 2, 2026): "OpenAI is unsatisfied with some of Nvidia's latest artificial intelligence chips, and it has sought alternatives since last year." [customer_alternatives.md: Reuters; Single-Source]

**AMD competition.** MI350X launched Q2 2025, MI400 confirmed 2026, MI500 on 2027 roadmap. AMD Data Center revenue $5.78B in Q1 CY2026. [ecosystem_signals.md; Verified C014; C020 Contradicted on MI350 launch timing]

**Open-source model risk.** The 10-Q discloses: "The recent rise in high-quality, open-source foundation models is making advanced AI capabilities broadly accessible. Open-source AI is dependent on developer adoption, and if deployed on our competitors' platforms, it could reduce demand for our products and services." [latest_10k.json: Recent Developments]

## Regulatory / Geopolitical

**China export controls:**
- H20 banned April 9, 2025 (no grace period). [transcript.json: Colette Kress]
- Q1 FY2026 impact: $4.6B revenue + $4.5B write-down + $2.5B unable to ship. [transcript.json: Colette Kress]
- China revenue: $4,550M (5.6% of total) in Q1 FY2027, down from $9,659M (21.9%) in Q1 FY2026. [latest_10k.json: Geographic Revenue]
- China TAM: ~$50B (management estimate). [transcript.json: Colette Kress]
- CEO: "the new limits pretty much makes it impossible for us to reduce Hopper any further." [transcript.json: Jensen Huang]
- H200 licensing program: $0 revenue to date. [latest_10k.json]

**Tariff exposure:** Cost of revenue includes tariffs. Pricing "generally does not fluctuate with short-term changes in our costs." Full tariff impact not separately quantified. [latest_10k.json: MD&A]

**Israel operations:** ~5,900 employees supporting networking products. Global supply chain "has not been significantly impacted by the conflict in the Middle East." [latest_10k.json: Recent Developments]

**Taiwan geographic risk:** 100% of advanced GPU wafers produced in Taiwan today. TSMC Arizona expansion is a partial mitigation. [transcript.json; ecosystem_signals.md]

## Execution Risks

**Manufacturing complexity:** The 10-Q discloses: "The complexity of bringing up our product architecture and sophisticated system configurations has caused and may in the future cause delays in production and create challenges in managing supply and demand." [latest_10k.json: Recent Developments]

**Warranty liabilities rising:** $2.9B as of April 26, 2026, up from $1.3B a year earlier (+126% YoY). Q1 FY2026 warranty additions were $870M in a single quarter. [latest_10k.json: Accrual for Product Warranty Liabilities]

**Manufacturing commitments: $119B total,** $95B due in remainder of FY2027. Additional $30B cloud service commitments and $6B other commitments (~$155B total). Manufacturing commitments ≈ 1.5x annualized COGS ($82B). [Inference: Q1 FY2027 COGS $20.5B × 4] [Sources: latest_10k.json: Note 10]

**Rapid product cadence:** Annual cadence through 2028. GB300 (Blackwell Ultra) sampling May 2026. Rubin expected H2 FY2027. Generation transitions can cause customer order pauses. [transcript.json: Colette Kress; latest_10k.json]

**Goodwill: $20.8B,** up $15.6B in FY2026 from an undisclosed major acquisition. Integration success not yet measurable. [balance.json: goodwill]

**Key person risk:** CEO Jensen Huang has led NVIDIA since co-founding in 1993 (33 years). No succession planning disclosed. [info.json: ceo; latest_10k.json]

## Financial Risks

**Investment portfolio volatility:** Q1 FY2027 "Other income (expense), net" was $15.9B, compared to −$180M in Q1 FY2026. Includes $13.4B in net unrealized gains on publicly-held equity securities and $2.6B on non-marketable equity. [latest_10k.json: Note 7] Publicly-held equity securities: $30.2B (with $8.9B subject to lock-up through Dec 2027). These holdings subject GAAP earnings to market volatility unrelated to operations.

**$18.6B investment in private companies in Q1 FY2027.** "Some of these investments include AI model makers that may indirectly purchase or use our products in the cloud." [latest_10k.json: Recent Developments] Creates potential conflict-of-interest dynamics and concentration risk.

**Effective tax rate trending toward statutory:** FY2022 1.9% → FY2023 -4.5% → FY2024 12.0% → FY2025 13.3% → FY2026 15.1% → Q1 FY2027 16.6%. At a normalized 21% rate, FY2026 net income would be $111.7B rather than $120.1B (−6.9%). [income.json; ratios.json]

**Working capital consumption:** Cumulative $38.6B absorbed FY2022–FY2026. FY2026 alone: −$15.9B (AR +$15.4B, inventory +$11.3B). [cashflow.json: changeInWorkingCapital]

**Facility lease guarantees:** $3.5B maximum gross exposure, $712M in escrow. [latest_10k.json: Note 8]

## Pending Litigation

Securities class action: *In Re NVIDIA Corporation Securities Litigation* (filed Dec 2018, crypto-era channel inventory disclosures). District court granted class certification March 25, 2026. NVIDIA petitioned Ninth Circuit to appeal April 8, 2026. Multiple derivative lawsuits stayed pending resolution. [latest_10k.json: Note 10, Litigation]

## Notable Non-Disclosures

- **Backlog:** NVIDIA does not disclose formal backlog in SEC filings. The $500B+ figure is management commentary only. Peers (e.g., Broadcom) disclose multi-year AI backlog in filings. [Data gap]
- **Customer identities:** Top 3 customers unnamed in filings. [latest_10k.json]
- **AI-specific revenue by product:** No filing-level breakdown of Blackwell vs. Hopper vs. networking within Data Center. [Data gap]
- **Segment-level margins at market platform level:** Margins disclosed for Compute & Networking vs. Graphics, but not for Data Center vs. Edge Computing. [Data gap]
- **Management did not provide a specific answer** to analyst Harlan Sur's (JPMorgan) question about competitive dynamics from custom ASICs — Jensen Huang reframed it as a networking and platform opportunity via NVLink Fusion rather than addressing share loss risk. [transcript.json: Q&A]

# Appendix G: Transcript Highlights — Key Management Quotes by Topic

Source: transcript.json (Q1 FY2026 earnings call, May 28, 2025 — for the quarter ended April 27, 2025)

Note: The transcript covers the Q1 FY2026 quarter (ended April 27, 2025), not the Q1 FY2027 quarter (ended April 26, 2026). The Q1 FY2027 financial results are from the 10-Q filing (latest_10k.json). Speaker attribution verified against transcript.json.

## Revenue and Financial Results (CFO Colette Kress, Prepared Remarks)

**Record revenue:** "Record revenue of $81.6 billion, up 85% from a year ago." — Note: This figure corresponds to Q1 FY2027 as reported in the press release, but the transcript covers the Q1 FY2026 earnings call where management discusses Q1 FY2026 results. The transcript data actually references Q1 FY2026 results ($44.1B quarter). Reconciliation: transcript_segments.json confirms period = Q1 2026.

**Data Center:** "Data center revenue was a record $39.1 billion, up 427% year-over-year and up 1% sequentially." [transcript.json: Colette Kress — for Q1 FY2026]

**Blackwell ramp:** "We had a very strong start to Blackwell...Blackwell revenue contributed nearly 70% of data center compute revenue." [transcript.json: Colette Kress]

**Networking:** "Data center networking revenue in Q1 was approximately $5 billion, up 64% sequentially...NVLink shipments exceeded $1 billion in Q1...Spectrum X is now annualizing at over $8 billion." [transcript.json: Colette Kress]

**Gaming:** "Gaming revenue was a record $3.8 billion, up 42% year-over-year." [transcript.json: Colette Kress]

**Automotive:** "Automotive revenue was $567 million, up 72% year-over-year." [transcript.json: Colette Kress]

## China / Export Controls (CFO Colette Kress & CEO Jensen Huang)

**H20 impact:** "On April 9, we were informed by the U.S. government of new export controls on H20, effective immediately...new export controls on H20 did not provide a grace period." [transcript.json: Colette Kress]

**Financial impact:** "During Q1, we recognized approximately $4.6 billion in H20 revenue...we incurred a charge of $4.5 billion related to H20 inventory and outstanding purchase obligations...Q2 expected a meaningful decrease with approximately $8 billion in H20 orders lost." [transcript.json: Colette Kress]

**Market size:** "Losing access to the China AI accelerator market, which we believe will grow to nearly $50 billion, would have a material adverse impact on our business going forward and benefit our foreign competitors in China and worldwide." [transcript.json: Colette Kress]

**Limited options:** "The new limits pretty much makes it impossible for us to reduce Hopper any further...for any productive use...We have some limited options...We don't have anything at the moment." [transcript.json: Jensen Huang, Q&A response to Tim Arcuri, UBS]

## AI Demand and Market Opportunity (CEO Jensen Huang)

**Reasoning AI:** "Reasoning AI requires hundreds to thousands more tokens per task than previous one-shot inference." [transcript.json: Jensen Huang]

**AI factories:** "Nearly 100 NVIDIA-powered AI factories in flight this quarter, a twofold increase year over year." [transcript.json: Colette Kress] "There are about 800 AI factories that are being built." [transcript.json: Jensen Huang, Q&A response to C.J. Muse]

**Sovereign AI:** Jensen Huang referenced projects in Saudi Arabia (500MW), UAE (5GW campus), Taiwan, Sweden, Japan, Korea, India, Canada, France, UK, Germany, Italy, Spain. [transcript.json: Jensen Huang]

**TAM framing:** "The world is spending $1 trillion a year on traditional infrastructure...we're at the beginning of the build-out." [transcript.json: Jensen Huang, response to Vivek Arya, BofA — framing AI as comparable to electricity/Internet build-out]

## Supply Chain (CEO Jensen Huang)

**US manufacturing build-out:** "TSMC is building six fabs and two advanced packaging plants in Arizona...Spil and Amkor are constructing state-of-the-art packaging, assembly and test facilities in Arizona. Foxconn is constructing a one million square foot factory in Houston, Texas...Wistron is constructing a similar plant in Fort Worth, Texas." [transcript.json: Jensen Huang]

**NVLink rack scale:** "NVLink72 carries 130 terabytes per second of bandwidth per rack." [transcript.json: Jensen Huang]

**GB200 complexity:** "GB200 NVL72 racks contain 1.2 million components and weigh nearly two tons." [transcript.json: Jensen Huang]

**Manufacturing bottlenecks:** "Scalable two-to-three year problems, not permanent barriers." [supplier_capacity.md: 247wallst.com quoting Jensen Huang; Single-Source per C099]

## Product Roadmap (CFO Colette Kress)

**GB300:** "GB300 provides 50% more HBM and 50% more FP4 inference compute vs. B200, using the same rack form factor for drop-in upgrade." [transcript.json: Colette Kress]

**Annual cadence:** Blackwell → Blackwell Ultra (GB300) → Rubin, with roadmap through 2028. [transcript.json: Colette Kress]

**TSMC Arizona:** "Process qualification for TSMC's Arizona fabs underway, with volume production expected by year-end." [transcript.json: Jensen Huang]

## NVLink Fusion / Custom ASIC Strategy (CFO Colette Kress)

"Hyperscale customers can now build semi-custom CPUs and accelerators that connect directly to the NVIDIA platform with NVLink...NVLink Fusion partners include MediaTek, Marvell, Alchip Technologies, Astera Labs, Qualcomm." [transcript.json: Colette Kress]

## Margin Guidance (CFO Colette Kress)

**Gross margin:** "We are continuing to work towards achieving gross margins in the mid-seventies range late this year." Q2 FY2027 non-GAAP gross margin guidance: 72% ±50bps. [transcript.json: Colette Kress]

**Blackwell profitability:** "We expect better Blackwell profitability to drive modest sequential improvement in gross margins." [transcript.json: Colette Kress]

**OpEx:** Full-year FY2027 opex growth guided in the "mid-thirty percent range." [transcript.json: Colette Kress]

**Tax rate:** Q2 FY2027 guidance: 16.5% ±1%. [transcript.json: Colette Kress]

## Customer Deployment (CFO Colette Kress)

**Hyperscaler deployment rate:** "Major hyperscalers are each deploying nearly 1,000 NVL72 racks, or 72,000 Blackwell GPUs per week." [transcript.json: Colette Kress]

**Microsoft:** "Deployed tens of thousands of Blackwell GPUs...expected to ramp to hundreds of thousands of GB200s with OpenAI as one of its key customers." "Processed over 100 trillion tokens in Q1, a 5x YoY increase." [transcript.json: Colette Kress]

**Spectrum X customers:** Coreweave, Microsoft Azure, Oracle Cloud, XAI, Google Cloud, Meta. [transcript.json: Colette Kress]

## Analyst Q&A — Notable Exchanges

**Vivek Arya (BofA):** Referenced Jensen's GTC comment about "a path towards almost a trillion dollars of AI spending over the next few years." Jensen responded by framing AI as essential infrastructure: "We're at the beginning of the build-out." [transcript.json: Q&A]

**C.J. Muse (Cantor Fitzgerald):** Asked about order visibility. Jensen: "We have more orders today than we did at the last time I spoke about orders at GTC." [transcript.json: Q&A]

**Tim Arcuri (UBS):** Asked about China alternatives. Jensen: "We have some limited options...We don't have anything at the moment." [transcript.json: Q&A]

**Harlan Sur (JPMorgan):** Asked about competitive dynamics from custom ASICs. Jensen reframed the question around NVLink Fusion as a networking/platform opportunity rather than directly addressing share loss risk. [transcript.json: Q&A]

# Appendix H: Source Index

## Tier 1: SEC Filings and Company Announcements

| File | Description | Period | Provider | Date |
|------|-------------|--------|----------|------|
| latest_10k.json | Q1 FY2027 10-Q filing (NVIDIA) | Q ended Apr 26, 2026 | EDGAR | Filed May 2026 |
| convertible_search.json | Historical convertible note filings | Historical | EDGAR | Various |

Note: Multiple EDGAR data sources (proxy, facts, exhibits, insider-detail, holders-detail, filing_events) returned command_failed during data gathering. [memory_context.md: Prior source behavior]

## Tier 2: Standardized Financial API (FMP)

| File | Description | Period | Provider | Pulled |
|------|-------------|--------|----------|--------|
| info.json | Company profile, market cap, price | Current | FMP | 2026-05-25 |
| quote.json | Real-time quote, 52-week range | May 22, 2026 | FMP | 2026-05-25 |
| income.json | Income statements (FY2014–FY2026) | Annual | FMP | 2026-05-25 |
| balance.json | Balance sheets (FY2014–FY2026) | Annual | FMP | 2026-05-25 |
| cashflow.json | Cash flow statements (FY2014–FY2026) | Annual | FMP | 2026-05-25 |
| metrics.json | Key metrics (ROIC, EV/EBITDA, etc.) | FY2014–FY2026 | FMP | 2026-05-25 |
| ratios.json | Financial ratios | FY2014–FY2026 | FMP | 2026-05-25 |
| earnings.json | Earnings history and estimates | Quarterly | FMP | 2026-05-25 |
| ratings.json | Analyst estimates and price targets | Forward | FMP | 2026-05-25 |
| technicals.json | Technical indicators (RSI, SMA, EMA, ADV) | May 22, 2026 | FMP | 2026-05-25 |
| enterprise_value.json | Enterprise value history | Annual | FMP | 2026-05-25 |
| shares_float.json | Float shares, free float % | Apr 26, 2026 | FMP/SEC | 2026-05-23 |
| segments.json | Segment data (empty — 404) | N/A | FMP | 2026-05-25 |
| peers.json | Peer companies | Current | FMP | 2026-05-25 |
| scores.json | Altman Z-Score, Piotroski Score | FY2026 | FMP | 2026-05-25 |
| insider.json | Insider transactions | Historical | FMP | 2026-05-25 |

Note: FMP segments.json returned empty (404 error). Segment data sourced from EDGAR 10-Q (latest_10k.json).

## Tier 3: Earnings Transcripts

| File | Description | Period | Provider | Pulled |
|------|-------------|--------|----------|--------|
| transcript.json | Q1 FY2026 earnings call | May 28, 2025 | FMP | 2026-05-25 |
| transcript_segments.json | Keyword-matched transcript segments | Q1 FY2026 | FMP | 2026-05-25 |

## Tier 4: Third-Party Research

| File | Description | Key Sources | Pulled |
|------|-------------|-------------|--------|
| ecosystem_signals.md | Peripheral company signals (TSMC, AMD, MSFT) | investor.tsmc.com, ir.amd.com, futurumgroup.com, cnbc.com | 2026-05-25 |
| supplier_capacity.md | Supply chain analysis | EnkiAI, 247wallst.com, Yahoo Finance | 2026-05-25 |
| supply_indicators.md | Supply/demand indicators | spheron.network, Seeking Alpha | 2026-05-25 |
| customer_capex.md | Customer spending data | Reuters, IO Fund, Seeking Alpha | 2026-05-25 |
| industry.json | Industry context | Seeking Alpha, various | 2026-05-25 |
| backlog_breakdown.md | Backlog analysis | investing.com, Yahoo Finance, techbuzz.ai | 2026-05-25 |

## Tier 5: News, Blogs, Commentary

| File | Description | Key Sources | Pulled |
|------|-------------|-------------|--------|
| business_overview.md | Company overview | Bullfincher, macrotrends.net | 2026-05-25 |
| competitive_by_product.md | Product competition | CNBC, pestel-analysis.com | 2026-05-25 |
| competitive_history.md | Historical competition | Wikipedia, various | 2026-05-25 |
| competitor_data.md | Competitor financials | Web sources | 2026-05-25 |
| customer_alternatives.md | Customer ASIC programs | Reuters, pestel-analysis.com, swottemplate.com | 2026-05-25 |
| convertible_detail.md | Convertible note research | Web sources | 2026-05-25 |
| company_ir.md | Investor relations page | nvidia.com | 2026-05-25 |
| press_releases.md | Company press releases | nvidianews.nvidia.com | 2026-05-25 |
| revenue_mix.md | Revenue mix analysis | Web sources | 2026-05-25 |
| segment_financials.md | Segment data (web) | SEC.gov, macrotrends.net | 2026-05-25 |
| short_interest.md | Short interest data | shortsqueeze.com, Benzinga, Nasdaq | 2026-05-25 |
| supply_demand.md | Supply/demand context | Web sources | 2026-05-25 |
| value_chain.md (raw) | Value chain research | Medium.com, various | 2026-05-25 |

## Derived / Verification Files

| File | Description | Stats |
|------|-------------|-------|
| claim_verification.json | Confidence tags on web-sourced claims | 109 claims: 53 Verified, 32 Corroborated, 14 Single-Source, 5 Contradicted, 5 Unverifiable |

## Peer Financial Data (Temporary Files)

| File | Description |
|------|-------------|
| /tmp/tsm_income.json | TSMC income statements for value chain comparison |
| /tmp/amd_income.json | AMD income statements for competitive comparison |
| /tmp/avgo_income.json | Broadcom income statements for ASIC comparison |

## Presentations

| Title | URL | Source |
|-------|-----|--------|
| NVIDIA 1st Quarter FY27 Financial Results | investor.nvidia.com | [presentations.json] |
| NVIDIA 2026 Annual Meeting of Stockholders | investor.nvidia.com | [presentations.json] |

## Context Files (Operational, Not Cited as Evidence)

| File | Description |
|------|-------------|
| memory_context.md | Prior run context; notes EDGAR source failures |
| wiki_context.md | Knowledge graph context (empty for this run) |
| source_map.json | Navigation map for raw files (not cited as evidence) |
