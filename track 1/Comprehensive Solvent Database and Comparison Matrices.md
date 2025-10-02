# **Comprehensive Solvent Database and Comparison Matrices**

### **1. Master Solvent Property Matrix**

This matrix provides a detailed compilation of physical, chemical, and performance properties for various CO₂ absorption solvents, categorized by their chemical class. The data is synthesized from multiple analytical reports, with "Data Not Found" indicating information not present in the source materials.

| Category | Solvent | Molecular Weight (g/mol) | Typical Conc. (wt%) | Theoretical CO₂ Loading (mol/mol) | Regeneration Energy (GJ/tonne CO₂) | Heat of Absorption | Corrosion Profile | Stability Profile |
| :--- | :--- | :--- | :--- | :--- | :--- | :--- | :--- | :--- |
| **Primary Amines** | **MEA** (Monoethanolamine) | 61.08 | 15 - 30 | 0.5 | 3.5 - 6.0 (TCM Benchmark)<br>~3.87 (Optimized) | High | High | Lower thermal & oxidative stability |
| **Secondary Amines** | **DEA** (Diethanolamine) | 105.14 | Various (often blended) | 0.5 | High | High | High | Lower stability, forms nitrosamines |
| | **DIPA** (Diisopropanolamine) | 133.19 | Various (often blended) | 0.5 | High (inferred) | High | Data Not Found | Lower stability, forms nitrosamines |
| | **PZ** (Piperazine) | 86.14 | 5 - 20 (as activator) | 1.0 (complex mechanism) | High (when used alone) | High | Data Not Found | Moderate; can form nitrosamines |
| **Tertiary Amines** | **MDEA** (N-methyldiethanolamine) | 119.16 | 20 - 50 | 1.0 | Low (improved in blends) | Low | Low | High thermal & oxidative stability |
| | **TEA** (Triethanolamine) | 149.19 | Data Not Found | 1.0 | Low (inferred) | Low | Low (inferred) | High (inferred) |
| | **DEAE / DEEA** | 117.19 | Data Not Found | 1.0 | Low (inferred) | Low | Low (inferred) | Good (inferred) |
| **Sterically Hindered** | **AMP** (2-amino-2-methyl-1-propanol) | 89.14 | Various (often blended) | 1.0 | Low (~25% lower than MEA) | Low | Data Not Found | High chemical & thermal stability |
| **Advanced Blends** | **MDEA + PZ** | N/A | ~45% MDEA, ~5% PZ | ~0.75 (mol CO₂/kg sol) | 3.22 - 3.6 | Low | Very Low | High; MDEA/PZ > MDEA > PZ |
| | **AMP + PZ (CESAR-1)**| N/A | Various | High | **2.6 - 3.5** | Low | Lower than MEA | Good |
| | **MEA + BEA + AMP** | N/A | Various | High | **~2.4** | Very Low | Data Not Found | Data Not Found |
| | **TETA + PZ + MDEA** | N/A | ~5% TETA, ~5% PZ, ~20% MDEA | High | Significantly lower than MEA | Low | Data Not Found | Data Not Found |
| **Advanced Solvents**| **Ionic Liquids (ILs)** | N/A | N/A | Tunable (High potential) | Potentially Low | Tunable | Generally Low | High Thermal Stability |
| | **Phase-Change (MEA/1-propanol)** | N/A | N/A | High | **~2.4** | Low | Data Not Found | Moderate |
| | **Deep Eutectic (DES)** | N/A | N/A | Lower (Physisorption) | Low (-14.7 kJ/mol ∆H) | Very Low | Low | Data Not Found |

---

### **2. Performance Ranking of Promising Solvents**

This table ranks a selection of the most promising solvents based on key performance indicators critical for economic viability and operational efficiency. The ranking highlights the trade-offs between different solvent technologies, with the benchmark MEA included for comparison.

| Rank | Solvent System | Regeneration Energy (GJ/tonne CO₂) ▼ | CO₂ Working Capacity ▲ | Corrosion Profile ▲ | Key Advantage |
| :--- | :--- | :--- | :--- | :--- | :--- |
| 1 | **MEA-BEA-AMP (Tri-blend)** | **~2.4** | High | Data Not Found | Lowest reported pilot-scale energy use. |
| 2 | **CESAR-1 (AMP+PZ)** | **~2.6** | High | Low | Proven low energy use and high capture efficiency (up to 99%). |
| 3 | **Phase-Change (e.g., MEA/1-propanol)** | **~2.4** | High | Moderate | Drastically reduces regeneration volume, saving energy. |
| 4 | **MHI KS-1™ (Hindered Amine)** | **2.94** | High | Low | Commercially proven high performance and efficiency at scale (Petra Nova). |
| 5 | **MDEA + PZ** | **3.22 - 3.6** | High | Very Low | Mature, bankable technology with excellent stability and low corrosion. |
| 6 | **CASTOR-2** | **~3.2** | High | Data Not Found | Early EU project proving significant energy reduction. |
| 7 | **Shell CANSOLV™ (Adv. Amine)** | Not specified ("Low") | High | Low | Commercially deployed (Boundary Dam) but real-world data is limited. |
| 8 | **AMP (Standalone)** | Low (~25% < MEA) | Very High (1.0 mol/mol) | Moderate | Excellent thermodynamics but slower kinetics, best in blends. |
| 9 | **MDEA (Standalone)** | Low | Very High (1.0 mol/mol) | Very Low | Excellent stability and capacity but very slow kinetics. |
| 10 | **MEA + PZ** | 3.4 - 8.5 (variable) | High | High | Boosts MEA absorption rate but may not offer significant energy savings. |
| - | *MEA (Benchmark)* | *3.5 - 6.0* | *Low (0.5 mol/mol)* | *Very High* | *Low-cost, well-understood baseline.* |

---

### **3. Industrial Application Summary**

This table summarizes the operational history, performance, and key lessons from major industrial and pilot-scale carbon capture projects utilizing solvent-based technologies.

| Plant Name | Solvent System Used | Capture Efficiency (%) | Key Operational Notes / Learnings | Current Status (as of analysis) |
| :--- | :--- | :--- | :--- | :--- |
| **Sleipner** | Amine (MEA or MDEA-based) | N/A (Gas sweetening) | **Feasibility:** Proved long-term geological storage is viable. <br> **MRV is Critical:** Revealed challenges in subsurface monitoring and reporting accuracy. | Operational (since 1996) |
| **Boundary Dam** | Shell CANSOLV DC-103™ | ~89% (when online) | **Availability is Key:** Frequent downtime led to an overall capture rate of only ~57% of target. <br> **Complexity:** Integration of capture unit with power plant is a major engineering challenge. | Operational (since 2014) |
| **Petra Nova** | MHI KS-1™ | **>92.4%** | **Advanced Solvents Work:** Successfully demonstrated lower energy use (2.94 GJ/t) at scale. <br> **Economic Risk:** Viability was critically tied to volatile oil prices, leading to a temporary shutdown. | Restarted Sept 2023; Operational |
| **TCM (Tech Centre Mongstad)** | Various (MEA, CESAR-1, KS-21™, etc.) | Up to **99%** | **De-risking Hub:** Essential for testing solvents on real flue gas before commercialization. <br> **Practical Hurdles:** Focuses on degradation, emissions, and dynamic operation. | Operational (since 2012) |
| **CESAR Project** | **CESAR-1 (AMP/PZ blend)** | ≥90% | **Energy Reduction:** Proved blended amines could achieve very low regeneration energy (~2.6 GJ/t). <br> **Cost Pathway:** Demonstrated a clear path to reducing capture cost vs. the MEA benchmark. | Completed (2011) |
| **CASTOR Project** | CASTOR-2 | 90% | **Pioneering Blends:** One of the first major projects to validate next-gen solvents beyond MEA. <br> **Energy Milestone:** Achieved ~3.2 GJ/tonne, a significant improvement at the time. | Completed (2008) |

---

### **4. Cost Comparison Matrix**

This matrix compares the key economic indicators for different classes of CO₂ capture solvents, highlighting the trade-offs between raw solvent price, operational costs, and the total cost of capture.

| Solvent / Technology | Estimated Market Price ($/tonne) | Regeneration Energy Cost (as % of OPEX) | Estimated Total Cost of Capture ($/tonne CO₂) |
| :--- | :--- | :--- | :--- |
| **MEA (Benchmark)** | ~$1,250 - $1,550 | **> 50%** | ~$40 - $169 (€37 - €156) |
| **Advanced Amine Blends** | Proprietary (higher than MEA) | Lower than MEA (primary cost saving) | ~$34 - $84 (€31 - €77) |
| **Ionic Liquids (ILs)** | $5,000 - $500,000 (Specialty) <br> ~$40,000 (Future Large-Scale est.) | Potentially Low | ~$88 - $98 (€81 - €90) <br> *(High solvent cost is a major driver)* |
| **Enzyme-Enhanced Systems** | Cost is in the enzyme & process | Low (low-temperature regeneration) | Marketed as "less expensive" alternative; data limited |
| **Hot Potassium Carbonate (HPC)** | Low (inexpensive salt) | Lower than MEA | Data Not Found |