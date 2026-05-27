---
type: company
ticker: AVGO
name: Broadcom Inc.
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
edges:
  - { type: competes_with, target: ADI, confidence: 0.6 }
  - { type: competes_with, target: AMD, confidence: 0.7 }
  - { type: competes_with, target: ASML, confidence: 0.5 }
  - { type: competes_with, target: META, confidence: 0.4 }
  - { type: competes_with, target: MU, confidence: 0.5 }
  - { type: competes_with, target: MRVL, confidence: 0.85 }
  - { type: competes_with, target: NVDA, confidence: 0.9 }
  - { type: competes_with, target: QCOM, confidence: 0.6 }
  - { type: competes_with, target: TSM, confidence: 0.4 }
  - { type: competes_with, target: INTC, confidence: 0.7 }
  - { type: competes_with, target: MRVL, confidence: 0.9, description: "Competes head-to-head in custom AI ASIC design services for hyperscaler customers" }
  - { type: competes_with, target: NVDA, confidence: 0.85, description: "Competes in AI accelerator market (custom XPUs vs GPUs) and data center networking (Ethernet switching vs NVLink/Spectrum)" }
  - { type: competes_with, target: INTC, confidence: 0.5, description: "Competes in data center Ethernet networking silicon products" }
  - { type: competes_with, target: MSFT, confidence: 0.55, description: "Competes with Broadcom's VMware via Hyper-V and Azure Stack in enterprise virtualization" }
  - { type: competes_with, target: AMZN, confidence: 0.5, description: "In-house AI chip development (Trainium/Inferentia) competes with Broadcom's custom XPU design model" }
  - { type: competes_with, target: Cerebras Systems, confidence: 0.45, description: "Competes for AI training/inference compute workloads with wafer-scale AI accelerator chips" }
  - { type: competes_with, target: AMD, confidence: 0.55, description: "Competes in data center AI accelerators with MI300 series GPUs and custom silicon" }
  - { type: competes_with, target: NTNX, confidence: 0.65, description: "Competes with Broadcom's VMware in hyperconverged infrastructure and private cloud platforms" }
  - { type: competes_with, target: CSCO, confidence: 0.65, description: "competes in data center Ethernet switch ASICs (Cisco Silicon One vs. Broadcom Tomahawk)" }
  - { type: competes_with, target: Red Hat, confidence: 0.6, description: "Competes with Broadcom's VMware via OpenShift in enterprise containerization and private cloud" }
  - { type: partners_with, target: OpenAI, confidence: 0.85, description: "Multi-year strategic co-development partnership for 10 GW of custom AI XPU compute capacity through 2029" }
  - { type: partners_with, target: NEC Corporation, confidence: 0.6, description: "Partnership for VMware Cloud Foundation enterprise deployment and integration" }
  - { type: partners_with, target: 6701.T, confidence: 0.6, description: "Partners on VMware Cloud Foundation enterprise deployment and go-to-market" }
  - { type: sells_to, target: Google, confidence: 0.92 }
  - { type: sells_to, target: Meta, confidence: 0.88 }
  - { type: sells_to, target: OpenAI, confidence: 0.9, description: "Developing and supplying custom AI accelerator (XPU) chips for OpenAI's compute infrastructure" }
  - { type: sells_to, target: Anthropic, confidence: 0.85, description: "Supplies TPU compute infrastructure (custom AI accelerator capacity) for Anthropic's AI workloads" }
  - { type: sells_to, target: Microsoft, confidence: 0.7 }
  - { type: sells_to, target: GOOGL, confidence: 0.95, description: "Designs and supplies custom TPU AI accelerators (7th-gen Ironwood) for Google's AI infrastructure" }
  - { type: sells_to, target: META, confidence: 0.9, description: "Designs and manufactures custom MTIA AI accelerator chips for Meta's data centers" }
  - { type: sells_to, target: AAPL, confidence: 0.9, description: "Supplies 5G RF front-end modules, Wi-Fi/Bluetooth combo chips, and GPS receivers for Apple devices" }
  - { type: sells_to, target: CSCO, confidence: 0.6, description: "Supplies Tomahawk Ethernet switching ASICs used in Cisco networking equipment" }
  - { type: sells_to, target: NEC Corporation, confidence: 0.6, description: "Enterprise customer and integration partner for VMware Cloud Foundation infrastructure software" }
  - { type: sells_to, target: Lenovo, confidence: 0.55, description: "Enterprise customer for VMware Cloud Foundation infrastructure software" }
  - { type: sells_to, target: DELL, confidence: 0.55, description: "purchases server storage connectivity components (SAS/SATA HBAs, RAID controllers, Fibre Channel HBAs)" }
  - { type: sells_to, target: HPQ, confidence: 0.5, description: "Enterprise customer for VMware Cloud Foundation infrastructure software" }
  - { type: sells_to, target: GOOGL, confidence: 0.95, description: "designs custom TPU AI accelerators (Ironwood 7th gen), Tomahawk switch ASICs, and optical DSPs for Google's AI infrastructure" }
  - { type: sells_to, target: HPE, confidence: 0.55, description: "purchases server storage connectivity components (SAS/SATA HBAs, RAID controllers, Fibre Channel HBAs)" }
  - { type: sells_to, target: ANET, confidence: 0.65, description: "Supplies Tomahawk Ethernet switching ASICs used in Arista's data center switches" }
  - { type: supplied_by, target: TSMC, confidence: 0.95 }
  - { type: supplied_by, target: ASE, confidence: 0.8 }
  - { type: supplied_by, target: SPIL, confidence: 0.7 }
  - { type: supplied_by, target: UMC, confidence: 0.5 }
  - { type: supplied_by, target: GlobalFoundries, confidence: 0.5 }
  - { type: supplied_by, target: Amkor, confidence: 0.6 }
  - { type: supplied_by, target: Foxconn, confidence: 0.5, description: "Manufacturing partner for hardware assembly" }
  - { type: supplied_by, target: TSM, confidence: 0.95, description: "Primary foundry for leading-edge semiconductor fabrication (advanced node wafers and CoWoS packaging)" }
  - { type: supplied_by, target: UMC, confidence: 0.5, description: "Secondary foundry providing wafer fabrication services" }
  - { type: supplied_by, target: GFS, confidence: 0.5, description: "Secondary foundry providing wafer fabrication services" }
  - { type: supplied_by, target: ASX, confidence: 0.7, description: "Provides semiconductor assembly, test, and packaging (OSAT) services" }
  - { type: supplied_by, target: SPIL (Siliconware Precision Industries), confidence: 0.8, description: "Provides semiconductor assembly and test services" }
  - { type: supplied_by, target: AMKR, confidence: 0.6, description: "Provides semiconductor assembly and packaging services" }
  - { type: supplied_by, target: Foxconn Technology Group, confidence: 0.8, description: "Provides assembly, test, and contract manufacturing services" }
  - { type: supplied_by, target: SMIC, confidence: 0.45, description: "Minor secondary foundry providing wafer fabrication services" }
  - { type: supplied_by, target: Siliconware Precision Industries, confidence: 0.6, description: "Provides semiconductor assembly, test, and packaging services" }
  - { type: supplied_by, target: SNPS, confidence: 0.65, description: "provides electronic design automation (EDA) tools for chip design" }
  - { type: supplied_by, target: CDNS, confidence: 0.65, description: "provides electronic design automation (EDA) tools for chip design" }
  - { type: supplied_by, target: ARM, confidence: 0.55, description: "Provides processor IP cores licensed for chip design" }
  - { type: supplied_by, target: Samsung Electronics, confidence: 0.5, description: "Supplies memory and semiconductor components" }
  - { type: supplied_by, target: FCX, confidence: 0.5, description: "Supplies copper used in semiconductor manufacturing" }
  - { type: supplied_by, target: EMN, confidence: 0.45, description: "Supplies specialty chemicals used in semiconductor manufacturing" }
  - { type: supplied_by, target: SKYT, confidence: 0.45, description: "US-based foundry providing wafer fabrication services" }
  - { type: supplied_by, target: 000660.KS, confidence: 0.8, description: "supplies high-bandwidth memory (HBM) integrated into custom AI accelerator packages" }
  - { type: supplied_by, target: 005930.KS, confidence: 0.7, description: "supplies high-bandwidth memory (HBM) for custom AI accelerator packages" }
  - { type: supplied_by, target: MU, confidence: 0.7, description: "supplies high-bandwidth memory (HBM) for custom AI accelerator packages" }
---

# Broadcom Inc. (AVGO)

## Overview

- **Sector:** Technology
- **Industry:** Semiconductors
- **Country:** US
- **Website:** https://www.broadcom.com

## Competitors

- [ADI](ADI.md) (ADI)
- [AMD](AMD.md) (AMD)
- [ASML](ASML.md) (ASML)
- [META](META.md) (META)
- [MU](MU.md) (MU)
- [MRVL](MRVL.md) (MRVL)
- [NVDA](NVDA.md) (NVDA)
- [QCOM](QCOM.md) (QCOM)
- [TSM](TSM.md) (TSM)
- [INTC](INTC.md) (INTC)
- [Marvell Technology](MRVL.md) (MRVL)
- [NVIDIA](NVDA.md) (NVDA)
- [Intel](INTC.md) (INTC)
- [Microsoft](MSFT.md) (MSFT)
- [Amazon](AMZN.md) (AMZN)
- Cerebras Systems
- [Advanced Micro Devices](AMD.md) (AMD)
- [Nutanix](NTNX.md) (NTNX)
- [Cisco Systems](CSCO.md) (CSCO)
- Red Hat

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
- Broderick Brian C
- COATUE MANAGEMENT LLC
- CTC LLC
- Capital Advisory Group Advisory Services, LLC
- DAI ICHI MUTUAL LIFE INSURANCE CO
