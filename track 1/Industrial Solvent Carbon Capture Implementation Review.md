# **Industrial Implementation Review: Solvent-Based Carbon Capture**

This document provides a comparative analysis of key industrial and pilot-scale carbon capture projects, synthesizing performance data, economic realities, and operational lessons. The review bridges theoretical solvent properties with practical, large-scale application data, offering a foundational understanding of the current state of solvent-based CO₂ capture technology.

### **High-Level Project Comparison**

The following table summarizes the core attributes and performance benchmarks of the reviewed projects.

| Project | Location | Type | Operational Status | Key Solvent Technology | Stated Regeneration Energy (GJ/tonne CO₂) | Target Capture Efficiency (%) |
| :--- | :--- | :--- | :--- | :--- | :--- | :--- |
| **Sleipner** | Offshore Norway | Gas Processing | Operational (since 1996) | Amine (MEA/MDEA) | Not Applicable | Reduces CO₂ from 9% to <2.5% |
| **Boundary Dam** | Saskatchewan, Canada | Commercial | Operational (since 2014) | Shell CANSOLV | Not specified (claimed "low") | 90% |
| **Petra Nova** | Texas, USA | Commercial | Operational (Restarted 2023) | MHI KS-1 | 2.94 | 90% |
| **TCM** | Mongstad, Norway | Pilot Plant | Operational (since 2012) | Various (MEA, CANSOLV, CESAR-1, etc.) | MEA: 3.5-6.0, CESAR-1: 3.4-3.5 | Varies (up to 99%) |
| **CESAR** | EU Pilot Tests | R&D Project | Completed (2008-2011) | AMP / Piperazine (CESAR1) | ~2.6 (with optimization) | ≥90% |
| **CASTOR** | EU Pilot Tests | R&D Project | Completed (2004-2008) | "CASTOR-2" | ~3.2 (with integration) | 90% |

---

## **1. Sleipner CO₂ Injection Project**

As the world's first industrial offshore CCS project, Sleipner's primary function is not post-combustion capture from a power plant but rather separating CO₂ from a natural gas stream to meet product specifications. It remains a cornerstone for understanding long-term geological storage.

| Category | Details |
| :--- | :--- |
| **Project Overview** | **Name:** Sleipner CO₂ Injection Project<br>**Location:** North Sea, offshore Norway<br>**Operational Status:** Active since September 1996. Injection volumes have declined in recent years due to waning natural gas production. |
| **Solvent System** | Conventional amine-based separation. Sources cite either **Monoethanolamine (MEA)** or an MDEA-based (methyldiethanolamine) process. |
| **Performance Metrics** | **CO₂ Capture Efficiency:** N/A (Gas sweetening process). Reduces CO₂ content in the natural gas stream from ~9% to below the 2.5% export specification.<br>**Annual Capture Volume:** Designed for ~1 million tonnes/year. However, recent data shows a significant drop (e.g., 0.106 million tonnes in 2023), and Equinor admitted to over-reporting volumes by ~30% from 2017-2021 due to faulty monitoring equipment.<br>**Regeneration Energy:** No specific value is reported. The process incorporates energy recovery via Pelton turbines on the amine loop, generating ~5 MW of power. |
| **Economic Data** | **CAPEX:** ~$100 million (1996 USD) for the additional CO₂ injection equipment.<br>**OPEX:** ~$17 USD per tonne of CO₂ injected. The project was economically driven by avoiding Norway's CO₂ tax (~$40/tonne at project inception). |

### **Key Findings & Lessons Learned**

- **Pioneering Long-Term Storage:** Sleipner has unequivocally demonstrated the technical feasibility of large-scale, long-term CO₂ injection and storage in a saline aquifer.
- **The Criticality of Monitoring:** The project highlights the complexity of tracking subsurface plumes. Unexpected upward migration of the CO₂ plume (though contained by a caprock) and multi-year over-reporting due to equipment failure underscore the absolute necessity for robust, redundant, and continuously validated monitoring, reporting, and verification (MRV) systems.
- **Economic Driver:** The project's existence is a direct result of a strong, clear economic penalty on emissions (the Norwegian CO₂ tax), proving that policy is a powerful catalyst for CCS deployment.

---

## **2. Boundary Dam CCS Project**

Boundary Dam was the world's first commercial-scale, post-combustion CCS facility on a coal-fired power plant. Its operational history provides a crucial, albeit cautionary, tale about the gap between design specifications and real-world performance.

| Category | Details |
| :--- | :--- |
| **Project Overview** | **Name:** Boundary Dam Unit 3 CCS Project<br>**Location:** Saskatchewan, Canada<br>**Operational Status:** Active since October 2014. SaskPower decided against expanding CCS to other units, citing economic non-viability. |
| **Solvent System** | **Shell CANSOLV DC-103™**, an advanced amine-based solvent. |
| **Performance Metrics** | **CO₂ Capture Efficiency:** *When online*, the facility demonstrates high capture rates averaging **89%**. However, its long-term operational availability has been poor, resulting in an overall capture rate of only ~57% of the design target over its life.<br>**Annual Capture Volume:** Target of 1 million tonnes/year. Consistently underperformed, capturing 786,539 tonnes in 2023.<br>**Regeneration Energy:** No specific value reported. CANSOLV is marketed as a "low energy" solvent, but regeneration remains the largest parasitic load. The system was designed with heat integration. |
| **Economic Data** | **CAPEX:** ~$1.5 billion CAD.<br>**OPEX:** Precise figures are not public, but the project is understood to be a net financial loss. The cost of electricity is high (~$140/MWh).<br>**Total Cost of Capture:** Not explicitly reported, but financial analyses indicate it is uneconomical. Underperformance led to penalty payments and reduced revenue from CO₂ sales for EOR. |

### **Key Findings & Lessons Learned**

- **Availability is the Achilles' Heel:** Boundary Dam's primary lesson is that *capture efficiency* during uptime is meaningless if the plant is frequently offline. Its struggles to meet an 85% availability target highlight that reliability and maintenance of the entire system—from the capture unit to the compressors—are paramount for success.
- **Operational Complexity:** The project faced numerous "real-world" challenges, including equipment malfunctions (compressor motor), fouling, scaling in heat exchangers, and solvent issues. This indicates that integrating a complex chemical plant with a power station is a significant engineering challenge that was underestimated.
- **Economic Fragility:** The high CAPEX and failure to meet operational targets rendered the project economically unviable for expansion, demonstrating that first-of-a-kind (FOAK) projects carry immense financial risk without sustained policy support or dramatic cost reductions.

---

## **3. Petra Nova CCS Project**

Petra Nova, attached to a large coal plant in Texas, applied MHI's advanced solvent technology. Its history demonstrates both the potential of high-performance solvents and the vulnerability of CCS economics to external market forces.

| Category | Details |
| :--- | :--- |
| **Project Overview** | **Name:** Petra Nova CCS Project<br>**Location:** Thompsons, Texas, USA<br>**Operational Status:** Started Jan 2017; mothballed May 2020 due to low oil prices; restarted Sept 2023 and is currently operational. |
| **Solvent System** | Mitsubishi Heavy Industries (MHI) **KM-CDR Process®** using the proprietary **KS-1** amine solvent. |
| **Performance Metrics** | **CO₂ Capture Efficiency:** Exceeded the 90% design target, achieving **>92.4%** on the processed flue gas slipstream.<br>**Annual Capture Volume:** Target of 1.4 million tonnes/year. Experienced a 16% shortfall in its first three years due to significant downtime.<br>**Regeneration Energy:** A specific value of **2.94 GJ/tonne CO₂** is reported, positioning KS-1 as a highly efficient second-generation solvent. |
| **Economic Data** | **CAPEX:** ~$1 billion USD.<br>**OPEX / Total Cost of Capture:** Estimated at **~$60/tonne** (capture only). The project's economics were critically dependent on high oil prices (requiring ~$75/barrel to break even) for its CO₂ sales revenue, leading to its 2020 shutdown. Its restart was supported by enhanced 45Q tax credits. |

### **Key Findings & Lessons Learned**

- **Advanced Solvents Perform:** The project successfully demonstrated the high efficiency and lower energy demand (2.94 GJ/tonne) of the KS-1 solvent at a commercial scale, a significant improvement over first-generation MEA systems.
- **Downtime Remains a Major Hurdle:** Similar to Boundary Dam, Petra Nova suffered extensive downtime (367 days in its first three years), not just from the capture island but also from the host plant, CO₂ pipeline, and the receiving oilfield. This reinforces the lesson that CCS is a *system* where the entire value chain must be reliable.
- **Commodity Price Dependency is a Risk:** Tying the economic viability of a capital-intensive environmental project to a volatile commodity like oil proved to be a critical flaw. The project's shutdown and subsequent restart underscore the need for stable, long-term financial incentives (like the 45Q tax credit) independent of commodity markets.

---

## **4. Technology Centre Mongstad (TCM)**

TCM is the world's premier open-access test facility for qualifying and de-risking carbon capture technologies. It serves as a critical bridge between laboratory-scale chemistry and industrial-scale deployment, testing a wide array of solvents under real-world conditions.

| Category | Details |
| :--- | :--- |
| **Project Overview** | **Name:** Technology Centre Mongstad (TCM)<br>**Location:** Mongstad, Norway<br>**Operational Status:** Active pilot plant since 2012. Functions as a neutral test facility. |
| **Solvent System** | Tests a wide variety of technologies, including:<br>- **Benchmark:** MEA (30-40 wt%)<br>- **Proprietary:** Shell CANSOLV, MHI KS-21™, ION ICE-31, Aker, Honeywell<br>- **Non-Proprietary:** CESAR-1 (AMP/PZ blend)<br>- **Other:** Chilled Ammonia Process (CAP) |
| **Performance Metrics** | **CO₂ Capture Efficiency:** Highly variable depending on solvent and test campaign. Has demonstrated rates up to **99%** (with CESAR-1).<br>**Regeneration Energy:** Serves as a key test parameter.<br>- **MEA Benchmark:** 3.5 - 6.0 GJ/tonne CO₂<br>- **CESAR-1:** ~3.4 - 3.5 GJ/tonne CO₂<br>- Lean Vapor Compression (LVC) demonstrated energy savings up to 25%. |
| **Economic Data** | **CAPEX:** ~NOK 7 billion (~$1.02 billion) for construction and development.<br>**OPEX:** Annual operating costs reported over NOK 300 million (~$35M USD) in 2014. A 2022 study estimated the cost of capture at TCM at **$47/tonne**. |

### **Key Findings & Lessons Learned**

- **Invaluable De-Risking Hub:** TCM provides an essential platform for technology developers to prove their systems on real flue gas (from both gas and refinery sources), generating crucial data on performance, degradation, and emissions before commercial scale-up.
- **Challenges of Dynamic Operation:** The facility has been instrumental in studying the flexible operation of capture plants, providing data on how systems respond to changes in load, though acquiring reliable dynamic data for model validation remains a challenge.
- **Focus on Practical Hurdles:** Work at TCM goes beyond simple efficiency, focusing on critical operational issues like material corrosion, solvent degradation, foaming, and emissions management, which are essential for long-term commercial viability.

---

## **5. CESAR & 6. CASTOR Projects**

CASTOR and its successor CESAR were foundational European R&D projects that aimed to develop and validate the next generation of post-combustion capture technologies, with a clear focus on reducing the cost and energy penalty compared to the MEA benchmark.

| Category | CASTOR (2004-2008) | CESAR (2008-2011) |
| :--- | :--- | :--- |
| **Project Overview** | R&D project to develop and pilot innovative technologies. The pilot plant was later used by CESAR. | R&D project to validate advanced solvents, notably at the Esbjerg pilot plant. |
| **Solvent System** | Developed new liquids, including **"CASTOR-2"**. Used MEA as a baseline. | Focused on **CESAR1**, a blend of **AMP** (2-amino-2-methyl-1-propanol) and **PZ** (piperazine). |
| **Performance Metrics** | **Capture Efficiency:** 90%<br>**Regeneration Energy:** Target of 2.0 GJ/tonne. Achieved **~3.2 GJ/tonne** with process integration. | **Capture Efficiency:** 90-99%<br>**Regeneration Energy:** **~2.6 GJ/tonne** with advanced process integration (e.g., LVC). |
| **Economic Data** | **Cost Goal:** Reduce capture cost from 50-60 €/tonne to **20-30 €/tonne**. | **Cost Goal:** 15 €/tonne. Assessed cost was **35-55 €/tonne** (still a reduction vs. MEA benchmark). |

### **Key Findings & Lessons Learned**

- **Pioneering Advanced Solvents:** These projects were instrumental in demonstrating the potential of blended amine solvents (like AMP/PZ) to significantly lower regeneration energy requirements compared to the standard MEA process.
- **Setting a Path for Cost Reduction:** While the ambitious cost targets were not fully met, CASTOR and CESAR successfully proved pathways to reduce both CAPEX (through process integration) and OPEX (through lower energy demand), paving the way for the technologies used in later commercial projects.
- **Understanding Solvent Stability:** The long-term campaigns, particularly in CESAR, provided crucial insights into solvent degradation mechanisms, showing that while advanced solvents still degrade, their behavior can be more stable and predictable than MEA, which is vital for solvent management and operational cost.