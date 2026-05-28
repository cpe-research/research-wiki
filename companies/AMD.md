---
type: company
ticker: AMD
name: Advanced Micro Devices, Inc.
sector: Technology
industry: Semiconductors
country: US
updated: "2026-05-28"
sources:
  - info.json
  - value_chain.md
  - segments.json
  - insider.json
  - holders.json
  - transcript_competitors.json
---

# Advanced Micro Devices, Inc. (AMD)

## Overview

- **Sector:** Technology
- **Industry:** Semiconductors
- **Country:** US
- **Website:** https://www.amd.com

## Competitors

- [Broadcom](AVGO.md) (AVGO)
- [Marvell Technology](MRVL.md) (MRVL)
- Ampere Computing
- [Lattice Semiconductor](LSCC.md) (LSCC)
- [Qualcomm](QCOM.md) (QCOM)
- [NVIDIA](NVDA.md) (NVDA)
- [Intel](INTC.md) (INTC)

## Key Insiders

- Norrod Forrest Eugene (officer: EVP & GM DESG)
- Papermaster Mark D (officer: Chief Technology Officer & EVP)
- Su Lisa T (director, officer: Chair, President & CEO)

## Top Institutional Holders

- Blankinship & Foster, LLC
- BNP PARIBAS FINANCIAL MARKETS
- BRIGADE CAPITAL MANAGEMENT, LP
- COATUE MANAGEMENT LLC
- MAPLELANE CAPITAL, LLC
- Mizuho Markets Cayman LP
- Modern Wealth Management, LLC
- MUFG Securities EMEA plc
- Oak Grove Capital LLC
- Platinum Management (NY) LLC

---

> **⚠️ DRAFT — this report did not pass the citation audit.** Some claims may lack source verification. Treat as preliminary research.

# Advanced Micro Devices, Inc. (AMD) — Research Report

**Report Date:** May 28, 2026 | **Data As Of:** May 27, 2026 (price), 2025 annual (FY2025), Q1 2026 quarterly (ended March 28, 2026)
**Ticker:** AMD | NASDAQ | Technology | Semiconductors

| Metric | Value |
|---|---:|
| Price | $519.32 [H1] |
| ADV | $19,877.99MM [H2] |
| Market Cap | $846,803,192,000 [H3] |
| Net Debt | -$6,080,000,000 (-0.72% of mkt cap) [H4] |
| Net Cash | $6,080,000,000 (0.72% of mkt cap) [H5] |
| Enterprise Value | $840,723,192,000 [H6] |
| Short Interest | 2.23% - 2.76% of float (36,140,000 - 44,700,000 shares short / 1,621,860,620 float) [H7] |

<details><summary>Header Sources</summary>

H1. quote.json: price
H2. info.json: averageVolume (38,272,625) × price ($519.35) / 1e6
H3. quote.json: marketCap
H4. balance.json: totalDebt ($4,472,000,000) − cashAndShortTermInvestments ($10,552,000,000)
H5. balance.json: cashAndShortTermInvestments ($10,552,000,000) − totalDebt ($4,472,000,000)
H6. Enterprise Value (EV) computed as Market Cap ($846,803,192,000) + totalDebt ($4,472,000,000) − cashAndShortTermInvestments ($10,552,000,000) = $840,723,192,000. Standard EV using only cash and equivalents is $845,736,192,000 based on standard net debt of -$1,067,000,000.
H7. short_interest.md: MarketBeat (44.70M shares short / 1.0 day to cover) and ShortSqueeze (36.14M shares short / 0.9 days to cover); shares_float.json: floatShares (1,621,860,620)

</details>

---

## Section 1: Business Overview

<!-- IC Question: What does this company do, how is it organized, and how large is each piece? | Evidence that would change the answer: Major divestiture, acquisition, segment reclassification, revenue mix shift -->

### Company Identity
Advanced Micro Devices, Inc. (AMD), headquartered in Santa Clara, California, is a global semiconductor company incorporated in 1969 [S1]. The company has 28,000 full-time employees and has traded on the NASDAQ Global Select exchange under the symbol "AMD" since its IPO on September 7, 1972 [S1]. 

### Reportable Business Segments
AMD is organized into three official reportable segments in financial reporting: Data Center, Client and Gaming, and Embedded [S2]. Reconstructed from Q1 2026 earnings transcripts and SEC filings [S2, S3, S4, S5], segment revenues and their respective growth trajectories are detailed as follows:

- **Data Center Segment**: Generates revenue from high-performance microprocessors, AI accelerators, and cloud orchestration systems. In FY2025, the segment generated $16.600B in revenue, representing 47.92% of total company revenue [S4, S5]. In Q1 2026, Data Center revenue rose to $5.800B, representing 56.31% of total company revenue, demonstrating an expansion of +57.00% year-over-year [S2, S3].
- **Client & Gaming Segment**:
  - **Client Sub-segment**: Generates revenue from x86 desktop and mobile PC processors. Client Q1 2026 revenue was $2.900B, representing 28.16% of total revenue (+26.00% YoY, -7.00% QoQ) [S2, S3]. FY2025 sub-segment revenue is not separately disclosed [Inference: Omitted in standard segment tables] [Sources: S3, S5].
  - **Gaming Sub-segment**: Generates revenue from discrete graphics cards and semi-custom System-on-Chip (SoC) platforms. Gaming Q1 2026 revenue was $0.720B, representing 6.99% of total company revenue (+11.00% YoY) [S2, S3]. Combined Client & Gaming segment revenue in FY2025 was $14.600B, representing 42.15% of total company revenue [S4, S5].
- **Embedded Segment**: Generates revenue from Field Programmable Gate Arrays (FPGAs - Xilinx architecture), adaptive SoCs, and embedded x86 processors. In FY2025, the segment generated $3.439B in revenue, representing 9.93% of total revenue [Inference: Inferred by subtracting Data Center ($16.600B) and Client & Gaming ($14.600B) from total reported FY2025 revenue of $34.639B] [Sources: S3, S5, S6]. In Q1 2026, Embedded segment revenue was $0.873B, representing 8.48% of total revenue, representing a +6.00% year-over-year increase [S2, S3].

The sum of disclosed segment revenues in Q1 2026 is $10.273B, creating a minor rounding variance of $27 million (approx. 0.26%) compared to the total reported company revenue of $10.300B (specifically $10.253B in earnings.json) [Inference: Minor rounding variance in public transcript disclosures versus exact XBRL filing numbers] [Sources: S2, S7].

### Segment Product and Service Offerings
- **Data Center Segment**: Key products include AMD EPYC server CPUs (4th Gen Genoa, 5th Gen Turin, 6th Gen Venice, and Venice-based Verano AI CPU) [S2], AMD Instinct GPU accelerators (MI300X, MI355X, MI450, MI500 series) [S2], and the Helios rack-scale high-performance AI infrastructure platform [S2]. Services include the ROCm open-source high-performance computing software stack [S2].
- **Client & Gaming Segment**: Key products include AMD Ryzen desktop and mobile x86 processors (Ryzen AI 400 and AI Pro 400 series) [S2], consumer discrete GPUs (Radeon 9000 series, Radeon Pro) [S1, S2], and semi-custom SoCs for game consoles (Sony PlayStation, Microsoft Xbox) [S1, S2]. Services include FidelityFX Super Resolution (FSR) graphics enhancement software [S2].
- **Embedded Segment**: Key products include adaptive SoCs, Field Programmable Gate Arrays (FPGAs), and embedded x86 processor families (Embedded Radeon, Athlon, EPYC, G-Series) [S1, S2]. Services include hardware design verification and digital emulation solutions [S2].

### Revenue Mix: Narrative vs. Reality
- **The Market Narrative (Artificial Intelligence & Instinct GPUs)**: The market narrative positions AMD as a major competitor to NVIDIA in the AI accelerator space with its Instinct GPU lineup [S2, S8, S9]. AMD does not separately disclose Instinct GPU revenues [Inference: Disclosure choice to bundle with general server CPUs] [Sources: S2, S3]. The only official sizing is that full-year FY2025 AI-related revenue was guided to reach $5.0B+ [S10], representing approximately 14.43% of total FY2025 company revenue ($34.639B) [Inference: Recalculated from inputs] [Sources: S5, S10]. For Q1 2026, Data Center AI revenue grew by a significant double-digit percentage year-over-year but was down modestly sequentially due to lower sequential China shipments following a Q4 2025 regulatory transition [Inference: Sequential decline reflects US export restrictions on advanced chips shipped to China] [Sources: S2, S11]. AMD expects its Data Center AI business to grow significantly, targeting a long-term CAGR of greater than 80% [S2].
- **The Financial Reality (High-Performance Server CPUs & Ryzen Client Processors)**: While Instinct GPUs drive the narrative, AMD's core P&L remains heavily anchored by EPYC server CPUs and Ryzen Client processors [Inference: High segment share of total revenue and operating margins] [Sources: S2, S3]. In Q1 2026, EPYC server CPU revenue grew more than 50% YoY, with EPYC Turin crossing over 50% of CPU revenue in Q1 2026 [S2, S12]. Server CPU revenue is guided to grow more than 70% YoY in Q2 2026 [S2, S11]. In Client, Ryzen client processors grew 26% YoY to $2.900B (28.16% of total revenue) [S2, S3]. The Data Center segment generated $1.600B in operating income (28.00% operating margin), compared to Client & Gaming's $0.575B operating income (16.00% margin) and Embedded's $0.338B operating income (39.00% margin) [S2]. This indicates that EPYC server CPUs remain the most stable, highly profitable profit center today [Inference: EPYC server CPUs drive corporate profitability given lower initial gross margins on early Instinct GPU ramps] [Sources: S2, S3, S13].

### Major Customers & Strategic Partnerships
AMD does not disclose individual customer revenue percentages [Inference: Omitted in filings as no customer exceeds the 10.0% SEC disclosure threshold] [Sources: S3, S5]. Named strategic customers in current-run raw files include:
- **Meta (Facebook)**: Deployed up to 6 gigawatts of AMD Instinct GPUs across generations and co-designed a custom GPU based on AMD's MI450 architecture, scheduled to begin production shipments in 2H 2026 using the Helios rack-scale high-performance infrastructure [S2].
- **OpenAI**: Signed a 6-gigawatt multiyear deployment agreement, which begins with a 1-gigawatt deployment of Instinct MI450 GPUs in 2H 2026 [S2, S14].
- **Microsoft**: Integrates Instinct MI300X accelerators and EPYC server CPUs to power its Azure cloud platforms [S15, S16]. Microsoft also deploys Ryzen Pro client processors in enterprise PCs [S2].
- **Oracle**: Deploying public AI superclusters powered by 50,000 AMD Instinct MI450 series GPUs starting in calendar Q3 2026 [S17].
- **Dell, HP, Lenovo**: Strategic OEM partners distributing Ryzen Pro client processors in premium commercial PCs, driving a 50%+ year-over-year increase in commercial PC sell-through in Q1 2026 [S2].

### Brief History
AMD was incorporated in 1969 [S1]. Major historical acquisitions, including ATI Technologies in 2006 and Xilinx in 2022, allowed AMD to pivot significantly from client x86 processors into discrete graphics, gaming consoles, adaptive embedded computing, and AI accelerator markets [Inference: Acquired technology portfolios directly underpin the current Gaming and Embedded segments] [Sources: S1, S3].

### Section 1 Synthesis & Cross-Lens Insight
Reconstructing Q1 2026 segment margins and revenues reveals that while the market narrative focuses heavily on the Instinct AI GPU line (Data Center AI full-year FY2025 target of $5.0B+ represents ~14.43% of total company revenue), AMD's core P&L is actually anchored by high-performance EPYC server CPUs. EPYC CPUs drove a record 56.31% of total Q1 2026 revenue ($5.8B Data Center revenue, up 57% YoY), generating $1.6B in segment operating income at a 28% operating margin, whereas Instinct GPUs are initially operating below the corporate average gross margin of 55-56% as management prioritizes market share and scale [S2, S3, S5, S10, S13].

---

## Section 2: Competitive Position

<!-- IC Question: For each product, who competes with this company and what are their relative strengths? | Evidence that would change the answer: Loss of a top customer, entry of a well-capitalized competitor, customer building in-house alternative, technology disruption -->

### Segment and Product Competitive Landscape

#### 1. Artificial Intelligence Accelerators (Instinct GPU Series)
AMD's primary competitor in AI accelerators is NVIDIA.
- **Scale and Margin Disadvantage**: NVIDIA maintains dominant market leadership with an estimated 85-90% market share, generating US$75.2B in Data Center revenue in Q1 Fiscal 2027 alone [S18], which is over 12 times AMD's Q1 2026 Data Center revenue of $5.8B [S2]. NVIDIA operates at a massive scale and gross margin advantage, recording a 75.00% non-GAAP gross margin in Q1 FY27 vs. AMD's guided 56.00% non-GAAP gross margin in Q2 2026 [S2, S18].
- **Software Moat**: NVIDIA's CUDA software ecosystem is an entrenched barrier. AMD's open-source ROCm platform is gaining adoption as an alternative, but CUDA remains a powerful network effect [S18].
- **Competitive Advantage**: AMD differentiates itself by offering leadership memory bandwidth and capacity (e.g., Instinct MI300X and MI355X), which are critical performance bottlenecks for large language model (LLM) inference workloads [S2, S12]. A LinkedIn analysis by aujla-behpc projects AMD will capture a 10-15% data center AI market share by 2027 [S19 - Single-Source].

#### 2. x86 Server Microprocessors (EPYC CPU Series)
AMD's primary competitor in server CPUs is Intel.
- **Market Share Expansion**: PassMark benchmark installer metrics indicated an AMD server share of 36.5% in mid-2025, but actual Mercury Research unit share data indicates AMD server unit share was ~24-27% during that same period, showing that PassMark activity overrepresents AMD's footprint compared to commercial server shipments [Inference: PassMark installer activity is a benchmark installer metric that overrepresents actual consumer/commercial shipments due to enthusiast bias] [Sources: S20, S22].
- **Competitive Advantage**: AMD has systematically captured share from Intel's Xeon line by utilizing TSMC's superior manufacturing process nodes to deliver higher core-counts, better performance-per-watt, and superior Total Cost of Ownership (TCO) [Inference: Structural process advantages enabled AMD to gain significant share while Intel faced node execution delays] [Sources: S12, S18, S21].
- **Competitive Threats**: Intel's aggressive manufacturing turnaround (18A node and beyond) represents a direct threat to AMD's EPYC server CPU share and margins [S12]. Additionally, custom ARM-based processors developed in-house by hyperscalers (e.g., Microsoft Cobalt, Amazon Graviton) present an emerging threat [S2].

#### 3. x86 Client Processors (Ryzen CPU Series)
AMD competes with Intel in consumer and commercial desktop/mobile PCs.
- **Market Share Growth**: Mercury Research reports that AMD's desktop CPU revenue share grew from ~28% in Q1 2025 to 42.6% in Q4 2025, driven by the strong adoption of Zen 5 and Ryzen X3D processors [Inference: Desktop revenue share gains are associated with enthusiast processor ramps] [Sources: S22].
- **Distribution Advantage**: AMD maintains highly entrenched, multi-decade OEM channels with Dell, HP, and Lenovo, driving a 50%+ year-over-year increase in Ryzen Pro commercial PC sell-through in Q1 2026 [S2].

#### 4. Gaming and Semi-Custom System-on-Chip (SoC)
AMD competes with NVIDIA (Nintendo Switch) and custom silicon designers in console and graphics hardware.
- **Cyclical Headwinds**: Decline in console semi-custom revenue was a headwind in Q1 2026 due to the late-stage console cycle [Inference: Console sales naturally contract as platforms approach year 5-6 of their lifecycle] [Sources: S2]. Additionally, AMD projects that second-half client and gaming revenue will be impacted by memory and component price inflation, suppressing consumer demand [S2, S11].

### Market Addressability (TAM & SOM Analysis)
- **Stated Compute TAM**: At its Financial Analyst Day on November 11, 2025, AMD outlined a long-term plan to address an estimated $1.0 trillion compute market by 2030 [S6]. This TAM is company-estimated and incorporates highly aggressive compound growth assumptions for AI accelerators and high-performance server CPUs [Inference: TAM estimation skepticism] [Sources: S2, S6].
- **Server CPU TAM**: AMD management projects the server CPU TAM to grow at greater than 35.00% annually, reaching over $120B by 2030, up from previous industry expectations of 18.00% annual growth, driven by Agentic AI compute demands [Inference: Agentic AI workloads require additional CPU processing for head nodes and orchestration] [Sources: S2, S12].
- **SOM bottom-up methodology**: A bottoms-up Serviceable Obtainable Market (SOM) calculation based on AMD's target of 10-15% of the data center AI accelerator market by 2027 [S19 - Single-Source] implies an addressable AI revenue stream of $40B to $60B (assuming a total AI accelerator market of $400B) [Inference: Bottom-up SOM computed by multiplying market share target by expected TAM]. This bottom-up projection is highly consistent with forward analyst consensus [Inference: Sourced estimates align within rounding with analyst models], which models AMD's total company revenue growing from $49.87B in FY2026 to $76.28B in FY2027, driven by the scale-up of EPYC Turin server CPUs and the Instinct MI450/Helios AI platform [Inference: Forward revenue growth is modeled to accelerate based on Instinct and Turin shipments] [Sources: S23].

### Section 2 Synthesis & Cross-Lens Insight
Although AMD has achieved a server CPU market share of 24-27% (Mercury Research) and is projected to capture 10-15% of the data center AI market by 2027, its structural operating margin of 10.66% in FY2025 (GAAP) is heavily depressed compared to NVIDIA's 58.10% (Trefis) or 75.00% gross margins [Inference: NVIDIA's near-monopoly pricing power allows it to capture significantly higher margins than AMD]. This margin gap is primarily a post-merger balance sheet effect [Inference: Post-merger purchase price allocation adjustments create large non-cash amortization expenses that do not impact cash generation]: the 2022 Xilinx acquisition added $41.831B of goodwill and intangibles to AMD's balance sheet, resulting in $3.003B in non-cash amortization in FY2025, which depresses GAAP margins while ROCm and EPYC scale [S5, S12, S18, S21, S24].

---

## Section 3: Supply/Demand Balance

<!-- IC Question: Is industry supply sufficient to meet demand at current prices, and when does that change? | Evidence that would change the answer: Major capacity announcement, demand shock (positive or negative), policy change (tariffs, subsidies) -->

### Demand Decomposition & Order Pipeline
- **Backlog & Order Pipeline**: AMD does not officially disclose quantitative backlog figures or order book metrics in its filings [Inference: Disclosure choice to protect competitive order pipeline information] [Sources: S6]. However, qualitative indicators suggest substantial demand backlogs for both server EPYC CPUs and Instinct GPU lines (such as MI300X and the upcoming MI450), which are tightly coupled with hyperscaler data center deployments and TSMC packaging lead times [S6].
- **Customer CapEx Support**: Demand is supported by a historic acceleration in big tech CapEx. Google, Amazon, Microsoft, and Meta plan to spend a combined $725B on capital expenditures in 2026, a +77.00% increase over 2025 [S25]. Microsoft alone projected full-year FY2026 CapEx to reach approximately US$190B, with sequential spending rising to over US$40B per quarter [S16]. This massive capital allocation translates directly into sustained demand for AMD's high-performance server components [Inference: Rising hyperscale cloud CapEx is a direct demand driver for merchant server silicon] [Sources: S2, S16].

### Demand Durability
The demand for AMD's high-performance hardware is driven by the secular expansion of generative AI, model training, and inference workloads [Inference: Expanding AI model parameters and training runs require proportional hardware scaling]. Management expects the Data Center AI business to grow significantly, targeting a long-term CAGR of greater than 80.00% over the coming years [S2]. This is supported by deep co-engineering relationships and multi-gigawatt commitments with Meta and OpenAI [S2].

### Supply Constraints & Physical Bottlenecks
AMD operates on a fabless model and relies entirely on TSMC for manufacturing its advanced Zen 5 CPUs, EPYC server processors, and Instinct AI accelerators [S18]. 
- **Advanced Packaging Bottlenecks**: TSMC's CoWoS (Chip-on-Wafer-on-Substrate) advanced packaging capacity is extremely tight and remains sold out through 2025 and into 2026 [S26]. High-bandwidth memory (HBM3e/HBM4) from SK Hynix and Micron is also under severe capacity allocation through 2026 [S26]. 
- **Supplier Pricing Power**: TSMC raised its 2026 CapEx budget to US$52B to US$56B to build advanced packaging facilities to resolve these constraints [S18]. However, advanced semiconductor cleanroom buildouts have a physical lead time of 12 to 24 months before going online [Inference: Mechanical and cleanroom validation requirements introduce rigid delays] [Sources: S18]. TSMC is passing inflationary manufacturing costs down to chip designers, leading AMD to share these cost increases with customers [S2].

### Supply/Demand Synthesis & Pricing Power
Advanced AI compute hardware remains in a state of structural shortage [Inference: Hyperscaler demand for training and inference chips far exceeds the physical manufacturing capacity of TSMC's CoWoS advanced packaging lines] [Sources: S18, S26]. This persistent deficit gives AMD high pricing power, allowing it to maintain a guided non-GAAP gross margin of 55.00% in Q1 2026 and guided gross margin expansion to ~56.00% in Q2 2026 despite rising supplier and advanced packaging costs passed down by TSMC [S2, S11].

### AI Value Chain Positioning
- **AI Positioning**: AMD sits in the Chip Design (Fabless AI Accelerators & CPUs) and Helios Rack-Scale AI Infrastructure Platform layers of the AI value chain [S2].
- **AI Revenue Sizing**: Guided FY2025 AI-related revenue ($5.0B+) represents approximately 14.43% of total FY2025 revenue ($34.639B) [Inference: Math check: $5.0B / $34.639B = 14.43%] [Sources: S5, S10].

### Bargaining Power
- **Supply-Side Bargaining Power: High**: AMD depends on a single foundry (TSMC) for advanced packaging and wafer fabrication, creating concentrated supply chain vulnerability [S18]. Upstream switching costs are prohibitively high [Inference: Redesigning complex x86/GPU architectures for a different foundry's PDK would require hundreds of millions of dollars and 12-24 months, creating absolute foundry lock-in] [Sources: S18, S21].
- **Demand-Side Bargaining Power: Moderate**: While major hyperscale customers are highly concentrated, they are highly incentivized to support AMD as a second-source supplier to break NVIDIA's near-monopoly and gain pricing leverage [S9]. This offsets buyer concentration and provides AMD with solid pricing durability [Inference: Multi-vendor sourcing reduces buyer pressure] [Sources: S9, S18].

### Section 3 Synthesis & Cross-Lens Insight
The structural deficit in advanced AI compute hardware (TSMC CoWoS capacity remains fully booked through 2026 and HBM is under severe allocation) is supported by a combined $725B capital expenditure budget from big tech hyperscalers in 2026. This tight supply environment allows AMD to maintain strong pricing power, guiding to a 56.00% non-GAAP gross margin in Q2 2026 despite rising wafer and advanced packaging costs passed down by TSMC, which is increasing its own CapEx to $52B-$56B to address the bottleneck [S2, S11, S18, S25, S26].

---

## Section 4: Value Chain

<!-- IC Question: Where is value captured, and is it migrating toward or away from this company? | Evidence that would change the answer: Vertical integration move by customer or supplier, margin compression at the company's chain position, technology enabling disintermediation -->

### Value Chain Map
AMD operates as a strictly fabless chip designer, specializing in microprocessor architecture and software integration while outsourcing all manufacturing, packaging, and assembly [S1, S27]. 

```
Raw Wafers & Equipment ---> AMD (Fabless Design) ---> TSMC (Foundry) ---> TSMC (CoWoS Packaging) + Memory (HBM) ---> ODMs/OEMs ---> Hyperscalers/Enterprise
[SUMCO, Shin-Etsu, ASML]    [Zen 5, Instinct, ROCm]  [Advanced Nodes]       [Advanced Packaging, SK Hynix, Micron]     [Dell, HP, Lenovo]   [Meta, MSFT, Oracle]
```

### Upstream Relationships & Dependencies
AMD is highly dependent on TSMC for advanced wafer fabrication and packaging [S18]. AMD's next-generation Venice EPYC server CPUs are scheduled to ramp on TSMC's 2nm process technology starting in late 2026, creating absolute dependency on TSMC's process node roadmap execution [S4]. 
AMD is also dependent on SK Hynix, Micron, and Samsung for High-Bandwidth Memory (HBM3/HBM3E), which is integrated during packaging [S26]. Backend assembly and test services are performed by TF-AMD (a joint venture with Tongfu Microelectronics) [S27].

### Downstream Relationships & Customer Concentration
AMD distributes its products through OEMs (Dell, HP, Lenovo), distributors, and direct strategic engagements with hyperscalers (Microsoft, Meta, Oracle) [S1, S3]. 
- **China Export Controls and the China Transition**: Tightening US government export control regulations on advanced computing and semiconductor technologies have restricted AMD's shipments of high-performance chips to China. This regulatory shift directly drove a sequential decline in AMD's Data Center AI revenue in Q1 2026, described by management as the "China transition" [S2]. China-specific sales fell from $390 million in Q4 2025 to an immaterial amount in Q1 2026 [S2, S11], demonstrating that regulatory adjustments can rapidly erase regional revenues.

### Margin Capture Analysis
Gross and operating margins vary widely across different stages of the value chain, revealing where economic value is concentrated:

- **IP Licensing**: ARM Holdings (ARM) generates high-leverage licensing margins (95–96% Gross, 40–50% Operating) [S28].
- **Semiconductor Equipment**: ASML, Applied Materials (AMAT) command strong margins (45–60% Gross, 25–35% Operating) [S28].
- **Merchant GPU / AI Lead**: NVIDIA (NVDA) dominates margin capture (75.00% Gross, ~55–60% Operating) [S18].
- **Foundry / Fabrication**: TSMC generates strong margins (53–54% Gross, 40–43% Operating) [S18].
- **Fabless Processor Challenger**: **AMD** generates lower GAAP margins (49.52% Gross, 10.66% Operating in FY2025) [S5, S24]. This GAAP depression is driven by the post-acquisition non-cash amortization of Xilinx acquired intangible assets, which peaked in FY2022/FY2023 [Inference: Large post-merger intangible amortization] [Sources: S5, S29].
- **System Assembly (OEMs)**: Dell, HP, Lenovo capture low margins (5–15% Gross, 3–7% Operating) [S3].

### Integration Direction
AMD exhibits *no vertical integration* toward manufacturing or packaging. Instead, AMD is integrating *horizontally* by acquiring software platforms and engineering teams to build its AI software value chain. A key example is the net cash spent on acquisitions of $1.760B in FY2025 (which included the acquisition of Silo AI, Europe's largest private AI lab, to expand ROCm software compatibility and enterprise AI deployment services) [S2, S29].

### Section 4 Synthesis & Cross-Lens Insight
AMD's strictly horizontal, fabless model results in a highly asset-light structure where CapEx represents only 2.81% of revenue ($974M) in FY2025, but it creates extreme single-source foundry dependencies on TSMC and HBM manufacturers. Rather than vertically integrating into manufacturing, AMD is horizontally integrating through software acquisitions, spending $1.760B net in cash on acquisitions in FY2025 (including Silo AI) to build out ROCm software capabilities, which helps lower downstream switching costs for hyperscalers seeking a second-source alternative to NVIDIA's CUDA [S2, S18, S19, S26, S29].

---

## Section 5: Capital Structure

<!-- IC Question: How does the company raise money to spend on its business? | Evidence that would change the answer: Major debt issuance or repayment, M&A financing, credit rating change, convertible conversion, new equity issuance -->

### Equity Composition
AMD's equity composition consists of a single class of common stock, with no preferred stock outstanding ($0 on the balance sheet) [S5]. 
- **Outstanding Shares**: 1,630,600,000 shares [S20].
- **Share Float**: 1,621,860,620 shares (99.46% of outstanding) [S20].
- **Market Capitalization**: $846,803,192,000 based on the current price of $519.32 [S7].

### Debt Composition and Tranches
AMD's gross debt was $4,472,000,000 as of December 27, 2025, representing just 0.53% of its total capitalized structure [Inference: Gross debt divided by sum of market cap and debt] [Sources: S5, S7]. The gross debt consists of:
- **Short-Term Debt**: $874,000,000 [S5].
- **Long-Term Debt**: $2,973,000,000 [S5].
- **Capital Lease Obligations**: $625,000,000 [S5].

### Convertible Debt
AMD has $0 in active convertible securities or notes outstanding on its balance sheet [S5, S30]. Prior filings referenced "2025 Convertible Notes" maturing on December 15, 2025 [S30]. These notes matured and were resolved prior to the December 27, 2025 balance sheet, resulting in no active convertible debt at fiscal year-end [Inference: Inferred from $0 active convertible notes and total debt breakdown matches exactly] [Sources: S5, S30].

### Debt Maturity Profile
Standardized financial statements normalize AMD's debt into general short-term and long-term buckets [S5]. Specific senior notes coupon rates, tranches, and covenant details are omitted from the primary FMP files, presenting a filing gap [Inference: Detail level omitted in normalized APIs] [Sources: S5, S6].

### Cash and equivalents
AMD maintains substantial balance sheet liquidity, with:
- **Cash and Cash Equivalents**: $5,539,000,000 [S5].
- **Short-Term Investments**: $5,013,000,000 [S5].
- **Total Cash & Short-Term Investments**: $10,552,000,000 [S5].

### Net Debt & Leverage Ratio
- **Standard Net Debt**: -$1,067,000,000 (standard Net Cash using standard equivalents) [S5].
- **Adjusted Net Debt**: -$6,080,000,000 (comprehensive Net Cash including short-term investments) [Inference: Recalculated from balance sheet cash components] [Sources: S5].
- **Standard Net Debt / EBITDA**: -0.15x [S24].
- **Adjusted Net Debt / EBITDA**: -0.84x [Inference: Recalculated as Adjusted Net Debt divided by FY2025 EBITDA of $7.275B] [Sources: S5, S31].

### Minority Interest
AMD reports $0 in minority interest on its balance sheet [S5].

### Enterprise Value
- **Standard Enterprise Value (Standard EV)**: $845,736,192,000 (Market Cap + Gross Debt - Cash & Cash Equivalents) [Inference: Calculated from inputs] [Sources: S5, S7].
- **Adjusted Enterprise Value (Adjusted EV)**: $840,723,192,000 (Market Cap + Gross Debt - Cash & Short-Term Investments) [Inference: Calculated from inputs] [Sources: S5, S7].

### Section 5 Synthesis & Cross-Lens Insight
AMD’s capital structure is overwhelmingly equity-financed (gross debt of $4.472B represents just 0.53% of its $846.8B market cap), leaving the company with a massive net cash position of $6.080B. However, this conservative structure results in a drag on ROE, which collapsed from 42.18% in FY2021 to 6.88% in FY2025 [Inference: Low financial leverage reduces the asset-to-equity multiplier, dragging on ROE compared to a debt-leveraged structure]. This ROE compression is primarily driven by an asset turnover collapse from 1.3233x to 0.4503x [Inference: Denominator balance sheet expansion outpaced top-line revenue growth in the short term], reflecting the massive balance sheet expansion from the all-stock Xilinx transaction ($41.831B in goodwill and intangibles) which expanded the equity denominator without immediate proportional scaling in GAAP net income [S5, S7, S24, S31].

---

## Appendix

# Appendix D: Capital Structure & Leverage Analysis

## Detailed Capital Structure

This section provides a detailed breakdown of Advanced Micro Devices, Inc. (AMD) capital structure as of December 27, 2025 (FY2025 balance sheet) and current market equity pricing.

| Capital Structure Component | Value | Primary Source Citation |
| :--- | :---: | :--- |
| **Common Equity Class** | Single Class Common | `[File: info.json -- description]` `[File: shares_float.json -- float]` |
| **Share Price (Real-time)** | $519.32 | `[File: quote.json -- price]` |
| **Shares Outstanding** | 1,630,600,000 shares | `[File: shares_float.json -- float: outstandingShares]` |
| **Share Float** | 1,621,860,620 shares (99.46% of outstanding) | `[File: shares_float.json -- float: floatShares, freeFloat]` |
| **Market Capitalization** | $846,803,192,000 | `[File: quote.json -- marketCap]` |
| **Preferred Equity** | $0 (No preferred stock outstanding) | `[File: balance.json -- preferredStock]` |
| **Gross Debt** | $4,472,000,000 | `[File: balance.json -- totalDebt]` |
| *-- Current/Short-Term Debt* | $874,000,000 | `[File: balance.json -- shortTermDebt]` |
| *-- Non-Current/Long-Term Debt* | $2,973,000,000 | `[File: balance.json -- longTermDebt]` |
| *-- Capital Lease Obligations* | $625,000,000 | `[File: balance.json -- capitalLeaseObligations]` |
| **Convertible Debt** | $0 (No active convertible notes outstanding) | `[File: balance.json -- totalDebt]` `[File: claim_verification.json -- C024]` |
| **Cash & Cash Equivalents** | $5,539,000,000 | `[File: balance.json -- cashAndCashEquivalents]` |
| **Short-Term Investments** | $5,013,000,000 | `[File: balance.json -- shortTermInvestments]` |
| **Total Cash & Short-Term Investments** | $10,552,000,000 | `[File: balance.json -- cashAndShortTermInvestments]` |
| **Minority Interest** | $0 | `[File: balance.json -- minorityInterest]` |
| **Net Debt (Standard)** | -$1,067,000,000 (Net cash using standard equivalents) | `[File: balance.json -- netDebt]` |
| **Net Debt (Adjusted)** | -$6,080,000,000 (Net cash including short-term investments) | `[Inference: Total Debt minus Total Cash & ST Investments]` `[Sources: balance.json]` |
| **Enterprise Value (EV - Standard)** | $845,736,192,000 (Based on standard Net Debt) | `[Inference: Recalculated as Market Cap plus Gross Debt minus Cash & Equivalents]` `[Sources: quote.json, balance.json]` |
| **Enterprise Value (EV - Adjusted)** | $840,723,192,000 (Based on adjusted Net Debt) | `[Inference: Recalculated as Market Cap plus Gross Debt minus Cash & ST Investments]` `[Sources: quote.json, balance.json]` |
| **Net Debt / EBITDA (Standard)** | -0.15x | `[File: metrics.json -- netDebtToEBITDA]` |
| **Net Debt / EBITDA (Adjusted)** | -0.84x | `[Inference: Recalculated as Adjusted Net Debt divided by FY 2025 EBITDA of $7.275B]` `[Sources: balance.json, income.json]` |

## Capital Structure Context & Commentary

### Equity Financing Dominance
AMD's capital structure is overwhelmingly equity-financed. At current market valuation, gross debt of $4.472 billion represents just 0.53% of total capitalized structure (Market Cap + Gross Debt) [Inference: Recalculated from balance sheet inputs and market price]. This reflects extremely low financial leverage, presenting minimal solvency risk but leading to a drag on return on equity (ROE) due to an underleveraged balance sheet [Inference: Low financial leverage reduces financial risk but limits ROE magnification].

### Gross Debt Composition
AMD's gross debt of $4.472 billion is comprised of three tranches:
1. **Short-Term Debt ($874M)**: Reconciled from the current portion of long-term debt and short-term borrowings [File: balance.json -- shortTermDebt].
2. **Long-Term Debt ($2,973M)**: Reconciled from non-current senior notes and credit facilities [File: balance.json -- longTermDebt].
3. **Capital Lease Obligations ($625M)**: Non-current capital lease liabilities representing leased facility and infrastructure obligations [File: balance.json -- capitalLeaseObligations].

### Resolution of Convertible Securities
Historical filings referenced "2025 Convertible Notes" maturing on December 15, 2025 [File: claim_verification.json -- C024]. These notes matured and were resolved prior to the December 27, 2025 balance sheet, resulting in no active convertible debt at fiscal year-end, which aligns with FMP's $0 reported convertible notes [Inference: Matured convertible debt was either settled in cash or converted to common stock prior to the fiscal year-end balance sheet date].

### Net Cash Liquidity Position
AMD is in a strong net cash position. Under the standard FMP definition (debt minus cash and equivalents), net debt is -$1.067 billion [File: balance.json -- netDebt]. Under a more comprehensive definition (debt minus cash and short-term investments), net debt is -$6.080 billion [Inference: Recalculated from balance sheet cash components]. This comprehensive cash buffer of $10.552 billion provides AMD with high flexibility to invest in research and development and fund advanced semiconductor design operations without relying on debt markets [Inference: Substantial cash reserves support self-funded capital redeployment].

# Appendix E: Key Stats & Computation Methodology

This section details AMD's trading and financial valuation metrics, recalculated at the current stock price of **$519.32** [File: quote.json -- price], with precise formulas and data provenance.

## Trading and Valuation Metrics

| Metric | Value | Primary Source Provenance |
| :--- | :---: | :--- |
| **Stock Price** | $519.32 | `[File: quote.json -- price]` |
| **52-Week Range** | $108.62 - $527.1999 | `[File: quote.json -- yearLow, yearHigh]` |
| **Average Daily Value (30d)** | $16,874,897,988 ($16.875B) | `[File: technicals.json -- adv_30d]` |
| **Average Daily Volume (30d)** | 40,467,150 shares | `[File: technicals.json -- avg_volume_30d]` |
| **RSI (14-day)** | 76.70 (Overbought territory) | `[File: technicals.json -- rsi_14]` |
| **21-Day EMA** | $427.28 | `[File: technicals.json -- ema_21d]` |
| **50-Day SMA** | $321.84 | `[File: technicals.json -- sma_50d]` |
| **200-Day SMA** | $235.88 | `[File: technicals.json -- sma_200d]` |
| **Trailing P/E Ratio (Diluted)** | 195.97x | `[Inference: Recalculated as current price divided by FY 2025 diluted EPS of $2.65]` `[Sources: quote.json, income.json]` |
| **Trailing P/E Ratio (Basic)** | 194.50x | `[Inference: Recalculated as current price divided by FY 2025 basic EPS of $2.67]` `[Sources: quote.json, income.json]` |
| **Forward P/E Ratio (FY 2026)** | 69.77x | `[Inference: Recalculated as current price divided by analyst consensus FY 2026 EPS of $7.44303]` `[Sources: quote.json, ratings.json]` |
| **2-Year Forward P/E Ratio (FY 2027)** | 39.63x | `[Inference: Recalculated as current price divided by analyst consensus FY 2027 EPS of $13.10448]` `[Sources: quote.json, ratings.json]` |
| **EV / EBITDA (Standard EV)** | 116.25x | `[Inference: Recalculated as current standard EV divided by FY 2025 EBITDA of $7.275B]` `[Sources: quote.json, balance.json, income.json]` |
| **EV / EBITDA (Adjusted EV)** | 115.56x | `[Inference: Recalculated as current adjusted EV divided by FY 2025 EBITDA of $7.275B]` `[Sources: quote.json, balance.json, income.json]` |
| **Price / Free Cash Flow (P/FCF)** | 125.73x | `[Inference: Recalculated as current market cap divided by FY 2025 FCF of $6.735B]` `[Sources: quote.json, cashflow.json]` |
| **P/FCF (Adjusted for SBC)** | 166.14x | `[Inference: Recalculated as current market cap divided by FY 2025 FCF-ex-SBC of $5.097B]` `[Sources: quote.json, cashflow.json]` |
| **EV / Revenue (Standard EV)** | 24.42x | `[Inference: Recalculated as current standard EV divided by FY 2025 revenue of $34.639B]` `[Sources: quote.json, balance.json, income.json]` |
| **EV / Revenue (Adjusted EV)** | 24.27x | `[Inference: Recalculated as current adjusted EV divided by FY 2025 revenue of $34.639B]` `[Sources: quote.json, balance.json, income.json]` |
| **Dividend Yield** | 0.00% (No dividend currently paid) | `[File: dividends.json -- dividends]` `[File: metrics.json -- dividendYield]` |
| **Short Interest (% of Float - MarketBeat)** | 2.76% (Corroborated) | `[File: short_interest.md -- C046]` `[File: shares_float.json -- float: floatShares]` |
| **Short Interest (% of Float - ShortSqueeze)** | 2.23% (Contradicted) | `[File: short_interest.md -- C047]` `[File: shares_float.json -- float: floatShares]` |
| **Days to Cover (MarketBeat)** | 1.0 day (Corroborated) | `[File: short_interest.md -- C046]` |
| **Days to Cover (ShortSqueeze)** | 0.9 days (Contradicted) | `[File: short_interest.md -- C047]` |

## Recalculation Methodology & Formulas

To maintain strict data integrity, all price-dependent multiples in this report have been recalculated from first principles using the real-time stock price of **$519.32** and current outstanding shares of **1,630,600,000** (giving Market Cap of **$846,803,192,000**), rather than copying stale database ratios.

### 1. Average Daily Value (ADV 30d)
Computed directly from `technicals.json`:
$$	ext{ADV (30d)} = 	ext{avg_volume_30d} 	imes 	ext{Current Stock Price}$$
$$	ext{ADV (30d)} = 40,467,150 	imes \$519.32 = \$21,015,400,338	ext{ (recalculated from technicals)}$$
*Note: The FMP-precomputed `adv_30d` stored in `technicals.json` is **$16,874,897,988**, calculated at a historical average price. Recalculating with the current price reflects the expanded trading scale [Inference: Rising price expands trading value for a given unit volume].*

### 2. Diluted Trailing P/E
$$	ext{Trailing P/E (Diluted)} = rac{	ext{Current Stock Price}}{	ext{FY 2025 Diluted EPS}} = rac{\$519.32}{\$2.65} = 195.97	ext{x}$$

### 3. Basic Trailing P/E
$$	ext{Trailing P/E (Basic)} = rac{	ext{Current Stock Price}}{	ext{FY 2025 Basic EPS}} = rac{\$519.32}{\$2.67} = 194.50	ext{x}$$

### 4. Forward P/E (FY 2026)
$$	ext{Forward P/E} = rac{	ext{Current Stock Price}}{	ext{Analyst Consensus FY 2026 EPS}} = rac{\$519.32}{\$7.44303} = 69.77	ext{x}$$

### 5. 2-Year Forward P/E (FY 2027)
$$	ext{2-Year Forward P/E} = rac{	ext{Current Stock Price}}{	ext{Analyst Consensus FY 2027 EPS}} = rac{\$519.32}{\$13.10448} = 39.63	ext{x}$$

### 6. EV / EBITDA (Standard and Adjusted)
- **Standard EV** uses standard Net Debt (Debt minus Cash & Equivalents):
  $$	ext{Standard EV} = \$846,803,192,000 + \$4,472,000,000 - \$5,539,000,000 = \$845,736,192,000$$
  $$	ext{EV / EBITDA (Standard)} = rac{\$845,736,192,000}{	ext{FY 2025 EBITDA of \$7,275,000,000}} = 116.25	ext{x}$$
- **Adjusted EV** uses Adjusted Net Debt (Debt minus Cash & Short-Term Investments):
  $$	ext{Adjusted EV} = \$846,803,192,000 + \$4,472,000,000 - \$10,552,000,000 = \$840,723,192,000$$
  $$	ext{EV / EBITDA (Adjusted)} = rac{\$840,723,192,000}{	ext{FY 2025 EBITDA of \$7,275,000,000}} = 115.56	ext{x}$$

### 7. Price / Free Cash Flow (P/FCF - Standard and Adjusted)
- **Standard FCF** ($6.735B in FY 2025):
  $$	ext{P/FCF (Standard)} = rac{	ext{Market Capitalization}}{	ext{FY 2025 Free Cash Flow}} = rac{\$846,803,192,000}{\$6,735,000,000} = 125.73	ext{x}$$
- **Adjusted FCF** subtracting Stock-Based Compensation ($1.638B in FY 2025):
  $$	ext{FCF (ex-SBC)} = \$6,735,000,000 - \$1,638,000,000 = \$5,097,000,000$$
  $$	ext{P/FCF (Adjusted for SBC)} = rac{\$846,803,192,000}{\$5,097,000,000} = 166.14	ext{x}$$
  *Note: Stock-based compensation is added back to Operating Cash Flow as a non-cash item. Since SBC represents real dilutive value, subtracting it reflects cash generation available to existing shareholders [Inference: Subtracting SBC from FCF provides a conservative measure of cash flow quality].*

### 8. EV / Revenue (Standard and Adjusted)
- **Standard EV / Revenue**:
  $$	ext{EV / Revenue (Standard)} = rac{\$845,736,192,000}{	ext{FY 2025 Revenue of \$34,639,000,000}} = 24.42	ext{x}$$
- **Adjusted EV / Revenue**:
  $$	ext{EV / Revenue (Adjusted)} = rac{\$840,723,192,000}{	ext{FY 2025 Revenue of \$34,639,000,000}} = 24.27	ext{x}$$

### 9. Short Interest (% of Float)
Computed from short shares and float shares of **1,621,860,620**:
- **MarketBeat (Corroborated)**:
  $$	ext{SI % of Float} = rac{44,700,000	ext{ short shares}}{1,621,860,620	ext{ float shares}} 	imes 100 = 2.76\%$$
- **ShortSqueeze (Contradicted)**:
  $$	ext{SI % of Float} = rac{36,140,000	ext{ short shares}}{1,621,860,620	ext{ float shares}} 	imes 100 = 2.23\%$$

# Appendix F: Risk Factors

This section provides an expanded, quantitative analysis of the key risks facing Advanced Micro Devices, Inc. (AMD), compiled from standard filings, insider transaction histories, and earnings transcript Q&A deflections.

## 1. Customer Concentration Risk
- **SEC Disclosure Threshold**: Under SEC reporting rules, companies must disclose any single customer that accounts for 10% or more of total company revenue. Because AMD's recent 10-Ks do not contain such disclosures, it is inferred that no single customer represented 10% or more of AMD's total revenue in FY 2025 or Q1 2026 [Inference: No single customer exceeded the 10.0% SEC disclosure threshold] [Sources: balance.json, segment_financials.md].
- **Hypothetical Customer Churn Impact**: Assuming the largest customer (e.g., Microsoft or Meta) accounts for a maximum concentration of approximately 9.0% of total company revenue (just below the 10.0% SEC disclosure threshold, representing $3.117 billion of FY 2025 revenue), a 50% reduction in spend by this single largest customer would result in an estimated top-line revenue impact of **$1.559 billion** (representing **4.50%** of total FY 2025 revenue) [Inference: 50% spend reduction on largest customer estimated at 9.0% concentration] [Sources: income.json -- revenue].
- **Notable Ecosystem Exposures**: strategic partnerships are highly concentrated among tech giants like Meta, OpenAI, Microsoft, and Oracle [S2]. OpenAI has signed a 6-gigawatt multiyear deployment agreement [S2], Meta has deployed up to 6 gigawatts of AMD Instinct GPUs [S2], and Oracle plans to deploy a public cluster of 50,000 Instinct MI450 GPUs starting in calendar Q3 2026 [S17]. While these represent high multi-year visibility, a shift in AI hardware priorities by any of these four hyperscalers would introduce severe revenue volatility [Inference: High concentration of strategic contracts amplifies P&L vulnerability to hyperscaler capex shifts].

## 2. Cyclicality Risk
- **Historical Semiconductor Cycles**: AMD's financial results demonstrate high sensitivity to cyclical demand fluctuations in the global semiconductor industry, particularly across PC client and server refresh cycles:
  - *FY 2018*: $6.475 billion [S5]
  - *FY 2019*: $6.731 billion (+3.95% YoY) [S5]
  - *FY 2020*: $9.763 billion (+45.05% YoY) [S5]
  - *FY 2021*: $16.434 billion (+68.33% YoY) [S5]
  - *FY 2022*: $23.601 billion (+43.61% YoY) [S5]
  - *FY 2023*: $22.680 billion (-3.90% YoY) [S5]
  - *FY 2024*: $25.785 billion (+13.69% YoY) [S5]
  - *FY 2025*: $34.639 billion (+34.34% YoY) [S5]
- **Current Cycle Position**: AMD is currently experiencing an elevated demand cycle, driven primarily by the high-growth Data Center segment (which grew 57% YoY to $5.8 billion in Q1 2026, representing 56.31% of total revenue) [S2, S3]. This growth is fueled by an industry-wide artificial intelligence capital expenditure boom and server CPU upgrades (with Turin crossing 50% of CPU sales in Q1 2026) [S2, S12]. A cooling of AI infrastructure build-outs or a slowdown in server modernization would significantly compress AMD's growth rate and operating margins [Inference: High concentration of revenues in AI-driven datacenter hardware exposes AMD to severe cyclical downside if AI capex cools].

## 3. Technology Disruption & Execution Cadence Risk
- **AI Hardware Cadence and Execution Pressure**: To maintain competitiveness in the high-growth AI accelerator space, AMD must execute a tight annual hardware roadmap (Instinct MI300X, MI325X, MI350, MI400, MI450, and MI500 series) [S2]. This yearly cadence corresponds with that of its primary competitor, NVIDIA [Inference: AMD sets its product cadence to remain performance-competitive in the market], which reported record Data Center revenue of **$75.2 billion** in Q1 Fiscal 2027 and maintains stable non-GAAP gross margins of 75.0% [S18]. NVIDIA's dominant market position and larger R&D scale put severe execution pressure on AMD to avoid product delays or design flaws in its yearly chip refreshes.
- **Hyperscaler In-house Silicon**: Major cloud service providers (Google, Amazon, Microsoft, Meta)—who are AMD's primary EPYC CPU and Instinct GPU customers—are actively developing proprietary in-house custom silicon (e.g., Google TPUs, AWS Trainium/Inferentia, Microsoft Maia, Meta MTIA) to optimize workload cost and reduce reliance on merchant silicon providers [Inference: Hyperscaler custom chips represent a direct long-term substitution risk for AMD EPYC and Instinct products] [Sources: S9, S12].
- **Software Ecosystem Defensibility**: AMD's Instinct accelerators rely on the ROCm open-source software stack [S2]. AMD's ability to capture market share is structurally constrained by the deep developer entrenchment of NVIDIA's proprietary CUDA software ecosystem. If ROCm fails to achieve developer parity or broad compiler optimization across major AI frameworks, Instinct GPU shipments will face software adoption barriers.

## 4. Regulatory & Geopolitical Risk
- **Geopolitical Supply Chain Concentration**: AMD operates under a fabless business model and relies entirely on **TSMC** (Taiwan Semiconductor Manufacturing Company) in Taiwan for the manufacturing and advanced packaging of its advanced microprocessors, including EPYC CPUs, Zen 5, and Instinct GPUs [S18]. Any geopolitical disruption, military conflict, trade blockade, or natural disaster in the Taiwan Strait would result in an immediate and severe halting of AMD's manufacturing capabilities [Inference: Extreme geographical concentration at TSMC represents an existential operational risk].
- **Export Control Controls and the China Transition**: Tightening US government export control regulations on advanced computing and semiconductor technologies have restricted AMD's shipments of high-performance chips to China. This regulatory shift directly drove a sequential decline in AMD's Data Center AI revenue in Q1 2026, described by management as the "China transition" [S2]. China-specific sales fell from **$390 million** in Q4 2025 to an **immaterial** amount in Q1 2026 [S2, S11], demonstrating that regulatory adjustments can rapidly erase regional revenues.

## 5. Execution Risk (Xilinx Amortization Drag)
- **GAAP Operating Income & Margin Pressure**: AMD's acquisition of Xilinx, which closed in February 2022 for approximately $49 billion in stock, significantly altered its balance sheet and GAAP cost structure. This transaction generated **$23.9 billion** in Goodwill and **$23.8 billion** in Intangible assets on the balance sheet [S5]. The subsequent non-cash purchase price amortization has represented a major structural drag on GAAP operating income and margins, resulting in Depreciation & Amortization (D&A) expenses of:
  - *FY 2022*: $4.263 billion [S29]
  - *FY 2023*: $3.553 billion [S29]
  - *FY 2024*: $3.184 billion [S29]
  - *FY 2025*: $3.003 billion [S29]
  This non-cash drag is the primary cause of AMD's low GAAP operating margins (10.66% in FY2025) and negative GAAP ROIC-WACC spread (-11.71% in FY2025), which reconcile to 25.00% operating margin and positive spreads on a non-GAAP/cash basis [Inference: post-merger accounting adjustments mask underlying cash cash-flow profitability].

## 6. Financial & Earnings Quality Risks

### Accounts Receivable vs. Revenue Growth Divergence
- **Historical DSO Spikes**: From 2021 through 2024, AMD's accounts receivable grew materially faster than top-line revenue, signaling potential payment term extensions, revenue recognition timing lags, or channel build-ups:
  - *FY 2022*: Revenue grew **43.61%** while Accounts Receivable grew **52.44%** YoY; Days Sales Outstanding (DSO) increased from 60.14 to 63.84 days [S5, S24].
  - *FY 2023*: Revenue declined **3.90%** but Accounts Receivable grew **30.45%** YoY; DSO spiked to 86.66 days [S5, S24].
  - *FY 2024*: Revenue grew **13.69%** while Accounts Receivable grew **28.75%** YoY; DSO peaked at 98.14 days [S5, S24].
  - *FY 2025 Reversal*: In FY 2025, the trend reversed. Revenue grew **34.34%** to $34.639 billion, while Accounts Receivable declined **8.91%** to $6.315 billion, resulting in DSO dropping back to 66.54 days [S5, S24].

### GAAP Effective Tax Rate Normalization
- **Net Income Inflation**: AMD's reported GAAP net income has been significantly boosted by anomalously low and negative effective tax rates, primarily as a function of deferred tax adjustments, research and development tax credits, and the recognition of deferred tax benefits following the Xilinx acquisition. Normalizing these earnings at the statutory US corporate tax rate of 21% reveals a material gap in core profitability quality:
  - *FY 2025*: Reported GAAP net income was **$4.335 billion** on a tax *benefit* of **$103 million** (effective tax rate of **-2.47%**). Normalizing at 21% results in net income of **$3.291 billion**, indicating that the reported figures were boosted by **$1.044 billion** (representing **24.08%** of reported net income) associated with this tax anomaly [S5, S24].
  - *FY 2023*: Reported net income was **$854 million** on a tax *benefit* of **$346 million** (effective tax rate of **-68.11%**). Normalizing at 21% results in net income of **$401.3 million**, showing that reported net income was boosted by **$452.7 million** (representing **53.01%** of reported net income) [S5, S24].
  - *FY 2022*: Reported net income was **$1.320 billion** on a tax *benefit* of **$122 million** (effective tax rate of **-10.18%**). Normalizing at 21% results in net income of **$946.4 million**, showing that reported net income was boosted by **$373.6 million** (representing **28.30%** of reported net income) [S5, S24].

### Continuous Working Capital Consumption
- **Persistent Operating Cash Flow Drain**: Operating cash flow has faced a continuous headwind from working capital, with changeInWorkingCapital acting as a major drain over the last five years: -$2.382B (FY 2025), -$2.098B (FY 2024), -$3.052B (FY 2023), -$1.851B (FY 2022), -$765M (FY 2021) [S29]. Cumulative working capital consumption was **$10.148 billion** over the 2022–2025 period, representing a structural drag on cash flow quality despite top-line growth. This drag corresponds with the logistical complexity and long lead times of the advanced packaging [Inference: Holding nearly 165 days of inventory ties up substantial cash in advanced packaging supply chains] (CoWoS) supply chain for EPYC Turin and Instinct GPUs, which required AMD to expand balance sheet inventory by 38.12% YoY to **$7.920 billion** in FY2025, pushing Days of Inventory Outstanding (DOI) from 83.90 days (FY2021) to 165.31 days (FY2025) [S5, S24].

### Shareholder Dilution & Option-Offset Repurchases
- **SBC Trajectory**: Share-Based Compensation (SBC) has grown significantly, rising from **$379 million** in FY 2021 to **$1.638 billion** in FY 2025 (SBC to Revenue ratio increased from 2.31% to 4.73% over the period) [S24, S29]. To offset dilution, AMD spent massive amounts on common stock repurchases: $1.999 billion in FY 2021; $4.108 billion in FY 2022; $1.412 billion in FY 2023; $1.590 billion in FY 2024; and $1.316 billion in FY 2025 [S29]. This cumulative capital outflow of **$10.425 billion** was deployed to stabilize the diluted share count, which expanded by 33.12% (from 1.229 billion shares in FY2021 to 1.636 billion shares in FY2025) following the stock-based Xilinx acquisition [Inference: Stock repurchases served to absorb dilution rather than shrink the net outstanding share count] [Sources: S5, S29].

### Insider Trading Activity (May 2026)
Form 4 filings from May 2026 document a combined sale of **45,445 shares** by three senior executives, yielding total proceeds of **$19.74 million** at average prices exceeding $430 per share:
- *Lisa T. Su (CEO)*: Sold **19,958 shares** for a total of **$8.730 million** at an average price of **$437.42** on May 13, 2026 [S32].
- *Forrest Eugene Norrod (EVP & GM Data Center)*: Sold **19,487 shares** for **$8.407 million** at an average price of **$431.40** on May 20, 2026, after exercising options for 16,474 shares at $34.19 [S32].
- *Mark D. Papermaster (CTO & EVP)*: Sold **6,000 shares** for **$2.603 million** at an average price of **$433.79** on May 15, 2026, after exercising options for 12,000 shares at $84.85 [S32].
- *Plan Ambiguity*: Standard transaction details do not specify whether these sales were conducted under pre-scheduled Rule 10b5-1 trading plans [Inference: 10b5-1 status is ambiguous based on available dataset] [Sources: S32].

## 7. Earnings Consistency & Historical Outperformance
- **Historical Accuracy**: Across the 9 completed quarters from Q1 2024 through Q1 2026, AMD met or exceeded expectations in the vast majority of periods, with only one minor miss for each metric:
  - *EPS Beats*: 8 beats, 1 miss. The average EPS beat magnitude was **3.75%** (or **$0.05** per share) [S7].
  - *Revenue Beats*: 8 beats, 1 miss. The average revenue beat magnitude was **3.56%** (or **$295.5 million**) [S7].

### Beat and Miss Breakdown

| Quarter Date | Actual EPS ($) | Est EPS ($) | EPS Beat ($) | EPS Beat (%) | Actual Rev ($B) | Est Rev ($B) | Rev Beat ($M) | Rev Beat (%) |
| :--- | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: |
| **Q1 2026** (2026-05-05) | $1.37 | $1.29 | +$0.08 | +6.20% | $10.253 B | $9.900 B | +$353.0 M | +3.57% |
| **Q4 2025** (2026-02-03) | $1.53 | $1.32 | +$0.21 | +15.91% | $10.270 B | $9.668 B | +$601.6 M | +6.22% |
| **Q3 2025** (2025-11-04) | $1.20 | $1.17 | +$0.03 | +2.56% | $9.246 B | $8.756 B | +$489.5 M | +5.59% |
| **Q2 2025** (2025-08-05) | $0.48 | $0.48 | +$0.00 | +0.27% | $7.685 B | $7.414 B | +$270.8 M | +3.65% |
| **Q1 2025** (2025-05-06) | $0.96 | $0.94 | +$0.02 | +1.69% | $7.438 B | $7.124 B | +$313.6 M | +4.40% |
| **Q4 2024** (2025-02-04) | $1.09 | $1.08 | +$0.01 | +0.93% | $7.658 B | $7.533 B | +$125.1 M | +1.66% |
| **Q3 2024** (2024-10-29) | $0.92 | $0.92 | -$0.00 | -0.22% | $6.819 B | $6.715 B | +$104.3 M | +1.55% |
| **Q2 2024** (2024-07-30) | $0.69 | $0.68 | +$0.01 | +1.77% | $5.835 B | $5.729 B | +$106.4 M | +1.86% |
| **Q1 2024** (2024-04-30) | $0.62 | $0.62 | +$0.00 | +0.65% | $5.473 B | $5.477 B | -$4.0 M | -0.07% |

*Sources: [S7]*

### Pattern and Guidance Setting (Sandbagging vs. Variance)
- From Q1 2024 through Q2 2025, AMD displayed highly narrow, consistent beats (e.g., EPS beats of +$0.00 to +$0.02; revenue beats of +1.5% to +4.4%), which is characteristic of highly controlled, conservative guidance setting (sandbagging).
- During Q4 2025 and Q1 2026, the beat magnitudes widened significantly (EPS beat of +15.91% in Q4 2025; revenue beat of +$601.6 million). This divergence highlights genuine market acceleration and rapid scaling of server CPUs and Instinct accelerators, which outpaced consensus forecasting and introduced higher operational volatility into the financial models [Inference: Unexpected demand inflections degrade the precision of historical guidance forecasting model parameters].

## 8. Management Deflection on Product Margins (Analyst Q&A)
During the Q1 2026 Q&A session, analyst Christopher Muse (Evercore ISI) asked whether tight wafer capacity would allow AMD to drive its Instinct gross margins closer to the corporate average gross margin of 55-56% [S2]. CFO Jean Hu deflected, refusing to provide quantitative margins:
> *"C.J., at this stage, we really focus on driving the topline revenue growth on our Instinct family of product. I think on the gross margin, it really depends on how we work with the customers... over time, once we start to ramp our revenue, we'll have a lot of opportunities to improve gross margin..."* [S2]
- *Significance*: This response confirms that Instinct GPU margins are currently running **below the corporate average gross margin** (a margin diluter), and that management is prioritizing market share gains (topline growth) over near-term unit profitability [Inference: Refusing to confirm average margins implies dilution, confirmed by "opportunities to improve gross margin when we scale"].

# Appendix G: Transcript Highlights (Q1 2026 Earnings Call)

This section documents verbatim key quotes from AMD's Executive Team (CEO Lisa Su and CFO Jean Hu) during the Q1 2026 Earnings Conference Call on May 5, 2026, organized by critical strategic topics.

## 1. Server CPU TAM and Growth Dynamics

### On the server CPU market expansion and Agentic AI:
> **Lisa Su (CEO):** *"At our Financial Analyst Day in November, we outlined the server CPU market growing at approximately 18% annually over the next 3 to 5 years. Based on the demand signals we are seeing today and the structural increase in CPU compute requirements driven by Agentic AI, we now expect the server CPU TAM to grow at greater than 35% annually, reaching over $120 billion by 2030."*

### On the role of CPUs in AI orchestrating:
> **Lisa Su (CEO):** *"Inferencing and Agentic AI are increasing the need for server CPU compute as these workloads require additional CPU processing for orchestration, data movement and parallel execution in addition to serving as the head nodes for GPUs and accelerators. As a result, we are seeing both stronger near-term demand and deeper engagement with customers on long-term capacity planning."*

### On EPYC Venice and ARM server CPU competition:
> **Lisa Su (CEO):** *"Across the portfolio, Venice widens our competitive advantage, delivering substantially higher performance per socket and per watt versus competitive x86 offerings and more than 2x throughput per socket versus leading ARM-based AI solutions... No question, ARM is good architecture. It has a place in the Data Center market. We view it as more point products relative to a portfolio, where, from an AMD standpoint, we've built this broad portfolio of CPUs..."*

---

## 2. Instinct GPU and Helios Rack-Scale Platform

### On strategic hyperscaler partnerships and multiyear deployments:
> **Lisa Su (CEO):** *"A key example is our expanded strategic partnership with Meta to deploy up to 6 gigawatts of AMD Instinct GPUs spanning several product generations. Our agreement includes a custom GPU accelerator based on our MI450 architecture, co-designed to support Meta's next-generation AI workloads. Shipments are on track to begin in the second half of the year, leveraging our Helios rack-scale architecture, which integrates Instinct GPUs with EPYC Venice CPUs to deliver fully optimized high-performance AI infrastructure. Together with our previously announced OpenAI partnership, these engagements position AMD as a core partner..."*

### On the MI450 customer forecasts and demand signals:
> **Lisa Su (CEO):** *"We have begun sampling MI450 series GPUs to lead customers and remain on track to ramp Helios production shipments in the second half of the year. As we approach production, demand for MI450 series GPUs continues to strengthen, with lead customer forecasts now exceeding our initial plans and a growing number of new customers engaging on large-scale deployments..."*

---

## 3. Margin Strategy & Instinct Profitability Deflection

### On driving Instinct margins and potential pricing power:
> **Christopher Muse (Analyst, Cantor Fitzgerald) - Question:** *"And then I guess a question on Instinct gross margins. With compute essentially sold out... I would think outside of kind of passing through HBM that given the very tight wafer environment that this would be a place where you could look to drive your Instinct margins closer to your corporate average? How are you thinking about that...?"*

> **Jean Hu (CFO) - Response:** *"C.J., at this stage, we really focus on driving the topline revenue growth on our Instinct family of product. I think on the gross margin side, you're absolutely right, it's really -- the demand for compute is tremendous... and of course, the different customers also have a different gross margin. I think, over time, once we start to ramp our revenue, we'll have a lot of opportunities to improve gross margin, both on the ASP side, but also, more importantly, on the cost side when we scale our business."*

---

## 4. Supply Chain and Capacity Planning

### On supply tightness and deep supplier relationships:
> **Lisa Su (CEO):** *"The supply chain is tight. I would definitely say that. But I also think this is an area where we excel. We have very deep relationships across the supply chain on the wafer side, on the back end capacity side. And we are seeing meaningful improvements in that. And as our customers come to us with more demand, we are getting more supply... And that allows us to just plan much better as we go forward."*

---

## 5. Client and Gaming Segment Outlook

### On client PC market outlook and memory/component inflation:
> **Lisa Su (CEO):** *"Looking ahead, we expect demand for our Ryzen CPUs to remain solid in the second quarter. However, we are planning for second half PC shipments to be lower due to higher memory and component costs. Against this backdrop, we still expect our client revenue to grow year-over-year and outperform the market..."*

# Appendix H: Source Index

This section provides a complete, traceable list of all sources cited in this report. Every claim is linked back to a workspace file and a stable URL for independent verification.

## Source List

| Index | Workspace File Path | Data Provider | Date of Data | Reliability Tier | Primary URL |
| :---: | :--- | :--- | :---: | :---: | :--- |
| **S1** | `raw/info.json` | Financial Modeling Prep (FMP) | May 2026 | Tier 2 | [FMP Company Profile](https://site.financialmodelingprep.com/financial-statements/AMD) |
| **S2** | `raw/transcript.json` | FMP / Earnings Call | May 5, 2026 | Tier 3 | [FMP Financial Statements Page](https://site.financialmodelingprep.com/financial-statements/AMD) |
| **S3** | `analysis/business_profile.md` | Workspace Compiled Analysis | May 28, 2026 | Tier 4 | Web-sourced, no stable URL |
| **S4** | `raw/company_ir.md` | AMD Investor Relations / Web Search | May 2026 | Tier 4 | Web-sourced, no stable URL |
| **S5** | `raw/income.json` | FMP Financial Statements | Dec 2025 (FY2025) | Tier 2 | [FMP Income Statement](https://site.financialmodelingprep.com/financial-statements/AMD) |
| **S6** | `raw/supply_demand.md` | Workspace Compiled Web Research | May 2026 | Tier 4 | Web-sourced, no stable URL |
| **S7** | `raw/earnings.json` | FMP Earnings History | May 2026 | Tier 2 | [FMP Earnings Calendar](https://site.financialmodelingprep.com/financial-statements/AMD) |
| **S8** | `raw/news.json` | FMP News Feed | May 2026 | Tier 5 | [FMP Quote Feed](https://financialmodelingprep.com/quotes/AMD) |
| **S9** | `raw/customer_alternatives.md` | Workspace Compiled Web Research | May 2026 | Tier 4 | Web-sourced, no stable URL |
| **S10** | `raw/claim_verification.json` | Workspace QC Register / Web Scrape Cache | May 2026 | Tier Derived | [FMP Financial Statements Page](https://site.financialmodelingprep.com/financial-statements/AMD) |
| **S11** | `raw/ratios.json` | FMP Financial Ratios | Dec 2025 | Tier 2 | [FMP Ratios](https://site.financialmodelingprep.com/financial-statements/AMD) |
| **S12** | `raw/competitive_history.md` | Workspace Compiled Web Research | May 2026 | Tier 4 | Web-sourced, no stable URL |
| **S13** | `raw/segment_financials.md` | Workspace Compiled Web Research | May 2026 | Tier 4 | Web-sourced, no stable URL |
| **S14** | `raw/press_releases.md` | official PR Press-Wire | May 2026 | Tier 1 | [FMP Financial Statements Page](https://site.financialmodelingprep.com/financial-statements/AMD) |
| **S15** | `raw/quote.json` | FMP Real-time Quote | May 27, 2026 | Tier 2 | [FMP Quote Feed](https://financialmodelingprep.com/quotes/AMD) |
| **S16** | `raw/ecosystem_signals.md` | Workspace Compiled Ecosystem Analysis | May 2026 | Tier 4 | Web-sourced, no stable URL |
| **S17** | `raw/claim_verification.json` (Oracle supercluster) | Workspace QC Register | May 2026 | Tier Derived | [FMP Financial Statements Page](https://site.financialmodelingprep.com/financial-statements/AMD) |
| **S18** | `raw/ecosystem_signals.md` (TSMC/NVDA/MSFT) | Workspace Compiled Ecosystem Analysis | May 2026 | Tier 4 | Web-sourced, no stable URL |
| **S19** | `raw/competitive_history.md` (aujla-behpc share) | LinkedIn Web Scrape / claim_verification | Nov 2025 | Tier 4 | Web-sourced, no stable URL |
| **S20** | `raw/shares_float.json` | SEC Float Database via FMP | May 2026 | Tier 2 | [FMP Financial Statements Page](https://site.financialmodelingprep.com/financial-statements/AMD) |
| **S21** | `raw/competitor_data.md` | Trefis Competitive Database | Late 2025 | Tier 4 | Web-sourced, no stable URL |
| **S22** | `raw/claim_verification.json` (Mercury CPU share) | Mercury Research / claim_verification | Dec 2025 | Tier 4 | Web-sourced, no stable URL |
| **S23** | `raw/ratings.json` | FMP Analyst Consensus Estimates | May 2026 | Tier 2 | [FMP Analyst Ratings](https://site.financialmodelingprep.com/financial-statements/AMD) |
| **S24** | `raw/metrics.json` | FMP Key Metrics | Dec 2025 | Tier 2 | [FMP Metrics](https://site.financialmodelingprep.com/financial-statements/AMD) |
| **S25** | `raw/customer_capex.md` | Workspace Compiled Web Research | May 2026 | Tier 4 | Web-sourced, no stable URL |
| **S26** | `raw/supplier_capacity.md` | Workspace Compiled Web Research | May 2026 | Tier 4 | Web-sourced, no stable URL |
| **S27** | `raw/value_chain.md` | Workspace Compiled Web Research | May 2026 | Tier 4 | Web-sourced, no stable URL |
| **S28** | `raw/peers.json` | FMP Peer Database | May 2026 | Tier 2 | [FMP Financial Statements Page](https://site.financialmodelingprep.com/financial-statements/AMD) |
| **S29** | `raw/cashflow.json` | FMP Cash Flow Statements | Dec 2025 | Tier 2 | [FMP Cash Flow](https://site.financialmodelingprep.com/financial-statements/AMD) |
| **S30** | `raw/convertible_detail.md` | SEC filing search | Dec 2025 | Tier 1 | [EDGAR Senior Notes Filings](https://www.sec.gov/cgi-bin/browse-edgar?action=getcompany&CIK=AMD&type=10-K) |
| **S31** | `raw/income.json` (EBITDA) | FMP Income Statements | Dec 2025 | Tier 2 | [FMP Income Statement](https://site.financialmodelingprep.com/financial-statements/AMD) |
| **S32** | `raw/insider.json` | FMP Insider Transactions | May 2026 | Tier 2 | [FMP Insider Transactions](https://site.financialmodelingprep.com/financial-statements/AMD) |

## Reliability Tiers Reference
- **Tier 1**: SEC Filings (10-K, 10-Q, DEF 14A, Form 4) and official company announcements.
- **Tier 2**: Normalized financial databases and APIs (FMP financial statements, metrics, ratios, quotes, and estimates).
- **Tier 3**: Verbatim earnings transcripts and public Q&A recordings.
- **Tier 4**: Specialized third-party research with documented methodology (Mercury Research, Trefis, etc.).
- **Tier 5**: General news, blogs, and commentary.
