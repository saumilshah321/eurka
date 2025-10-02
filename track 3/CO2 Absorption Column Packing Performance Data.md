### **Knowledge Base: CO₂ Absorption Column Packing**

This document synthesizes comprehensive data on various packing types for CO₂ absorption columns, consolidating information from extensive research. It is designed to be the definitive data repository for performance analysis, comparison, and decision-making.

---

### **1. Conventional Structured Packing**

Conventional structured packings are the established industry standard, offering a balance of efficiency, capacity, and pressure drop. They are typically made from corrugated metal or plastic sheets.

#### **1.1 Mellapak Series (Sulzer)**

| Data Point | Extracted Information & Data |
| :--- | :--- |
| **Geometric Properties** | - **Specific Surface Area (a_p):** Common types are 125, 250, 500, and 750 m²/m³. Mellapak 250Y has a_p = 250 m²/m³. <br> - **Material:** Available in stainless steel, various alloys, and thermoplastics. |
| **Mass Transfer (kLa, HETP)** | - **Mass Transfer Coefficient (kGae, kLa):** Generally shows lower `kGae` values compared to gauze packings (e.g., Sulzer BX). A model exists for predicting `kL` for 250Y and 500Y, indicating `kL` increases with liquid/gas flow and decreases with packing geometric area. `kLae` values are higher for structured packings than random packings. <br> - **HETP:** Typical pressure drop per theoretical stage is 0.3-1.0 mbar. HETP depends on liquid load and gas velocity. |
| **Hydrodynamics** | - **Pressure Drop (ΔP/m):** Approx. 2 mbar/m at 70-80% flooding. For CO₂ absorption, 10-15 mbar is typical at optimal gas velocities (2.0-2.5 m/s). <br> - **Flooding/Loading:** Min. liquid load ~0.2 m³/m²h; max. can exceed 200 m³/m²h. <br> - **Correlations:** Pressure drop can be described by the Stichlmair equation using packing-specific constants. The Spiegel and Meier (1992) model is also specific to Mellapak. |
| **Industrial & Economic** | - **Manufacturer:** Sulzer. <br> - **CO₂ Specific Variants:** **Mellapak CC** and **Mellapak Evo** are specifically designed for CO₂ capture. **MellapakPlus** offers up to 50% higher capacity and lower pressure drop than standard Mellapak. <br> - **Case Study:** Used at the **Boundary Dam Power Plant**, with MellapakCC to be implemented from 2025, promising significant energy savings (~CAD$500,000 annually). <br> - **Software:** SULCOL™ software for sizing and hydraulic rating. |

#### **1.2 Flexipac Series (Koch-Glitsch)**

| Data Point | Extracted Information & Data |
| :--- | :--- |
| **Geometric Properties** | - **Specific Surface Area (a_p):** 250 m²/m³ for Flexipac 250Y. Also available in 1Y, 2Y, 3Y, 4Y sizes. <br> - **Structure:** "Y" series have 45° corrugation inclination; "X" series (60°) provide lower pressure drop per stage. <br> - **Material:** Available in various metals and plastics. |
| **Mass Transfer (kLa, HETP)** | - **Mass Transfer Coefficient (KGa):** Values can be obtained via KG-TOWER™ software. Effective surface area has been modeled for Flexipac 350Y using CO₂ absorption into MEA. `kLa` data is not explicitly available. <br> - **HETP:** Estimated values for distillation are available but vary significantly by size and material (e.g., Plastic Flexipac 2Y ≈ 19.2", General Flexipac 2Y ≈ 13.8"). These are reference values and not specific to CO₂ absorption. |
| **Hydrodynamics** | - **Pressure Drop (ΔP/m):** Generally provides lower pressure drop than trays and random packings. In one study, Flexipac 2Y HC showed higher pressure drop than Mellapak 2X and Montz B1-250M. <br> - **Correlations:** Data is insufficient to specify constants for standard correlations. |
| **Industrial & Economic** | - **Manufacturer:** Koch-Glitsch. <br> - **CO₂ Specific Variants:** **Flexipac CP™** is a patented packing for post-combustion capture, claiming up to a 65% reduction in pressure drop and superior capture efficiency. **Flexipac HC®** (High Capacity) is a variant with modified corrugations for increased capacity. <br> - **Case Study:** A Koch Modular pilot plant used Koch-Glitsch internals to test CO₂ capture from flue gas. A 2025 publication characterizes Flexipac CP™ with ION Clean Energy solvents. |

#### **1.3 Montz B1 Series**

| Data Point | Extracted Information & Data |
| :--- | :--- |
| **Geometric Properties** | - **Structure:** Corrugation angle (45° vs. 60°) impacts gas-side mass transfer coefficient (`kG`). |
| **Mass Transfer (kLa, HETP)** | - **Mass Transfer Coefficient (kG):** Varies with corrugation orientation. The Delft model has been used to predict efficiency. <br> - **HETP:** For well-wetting liquids, Montz packings can achieve 5 to 20 theoretical stages per meter. B1-250MN achieved an HETP of 0.25 m at a pressure drop < 1 mbar/m in total reflux distillation. |
| **Hydrodynamics** | - **Pressure Drop (ΔP/m):** Hydrodynamic parameters for B1-250M align with literature correlations for F-factors below 3. The Delft model closely predicts pressure drop. |
| **Industrial & Economic** | - **Manufacturer:** Montz (a Koch Engineered Solutions business). <br> - **Advanced Variants:** **Type M** series offers 30% higher throughput. **Type MN** series provides 30% more separation efficiency. <br> - **Case Study:** Partnered with Carbon Clean (Nov 2024) to supply patented metal packing for CycloneCC™ rotating packed beds (RPBs), intensifying CO₂ absorption. |

---

### **2. Advanced Metallic Structured Packing**

This category includes packings with specialized geometries or materials, such as wire gauze, designed for high efficiency or specific process conditions.

#### **2.1 Sulzer BX / DX Series (Gauze Packing)**

| Data Point | Extracted Information & Data |
| :--- | :--- |
| **Geometric Properties** | - **Structure:** Woven wire mesh/gauze. This provides excellent wettability and high surface area. DX has a coarser structure than BX. |
| **Mass Transfer (kLa, HETP)** | - **Mass Transfer Coefficient (kGae):** Sulzer BX demonstrates **higher `kGae` values** (more efficient) than Mellapak 250Y in CO₂ absorption studies. <br> - **HETP:** Known for very high separation efficiency (low HETP), making it ideal for difficult separations. DXM/DYM variants have a constant HETP over a wide load range. |
| **Hydrodynamics** | - **Pressure Drop (ΔP/m):** Known for very low pressure drop, suitable for vacuum applications. **BXPlus** offers a 20% lower pressure drop than standard BX for the same efficiency. |
| **Industrial & Economic** | - **Manufacturer:** Sulzer. <br> - **Application:** A milestone technology for difficult separation tasks and heat-sensitive substances. DX is often used in laboratory columns. |

---

### **3. Ceramic and Plastic Packing**

These packings are chosen for their unique material properties, primarily corrosion resistance and chemical compatibility.

#### **3.1 Flexeramic (Koch-Glitsch)**

| Data Point | Extracted Information & Data |
| :--- | :--- |
| **Geometric Properties** | - **Specific Surface Area (a_p):** Type 48: 208 m²/m³; Type 88: 125 m²/m³. <br> - **Material:** Ceramic. |
| **Mass Transfer (kLa, HETP)** | - **Efficiency:** Natural wettability improves efficiency in aqueous systems over metal/plastic. Higher efficiency than random packing. <br> - **Data Gap:** Specific `kLa` and HETP values for CO₂ absorption are not available. |
| **Hydrodynamics** | - **Pressure Drop (ΔP/m):** Very low resistance due to vertical orientation. Offers 50% lower pressure drop compared to ceramic saddles at the same gas flow. |
| **Industrial & Economic** | - **Manufacturer:** Koch-Glitsch. <br> - **Niche Application:** Designed for highly corrosive environments (e.g., sulfuric acid towers) and high temperatures. An economical alternative to exotic alloys. |

#### **3.2 General Plastic & Ceramic Packings**

| Category | Key Characteristics & Considerations for CO₂ Absorption |
| :--- | :--- |
| **Plastic** | - **Chemical Compatibility:** A key advantage is the extension of amine solvent lifetime by **avoiding metal-induced degradation**. Less susceptible to corrosion and fouling. <br> - **Challenges:** Achieving good wettability is a challenge, as many plastics are hydrophobic. Requires careful design to ensure good liquid film formation. <br> - **Hydrodynamics:** Generally offers higher capacity and lower pressure drop than ceramic equivalents. |
| **Ceramic** | - **Chemical Compatibility:** Exceptional resistance to aggressive media and thermal stability. Carbon Raschig rings are noted for use with most acids and caustics at high temperatures. <br> - **Application:** Best suited for extreme corrosive or high-temperature niche applications where metal or plastic would fail. |

---

### **4. 3D-Printed / TPMS Packing**

Additive manufacturing enables the creation of highly complex and optimized geometries, such as Triply Periodic Minimal Surfaces (TPMS), that are unachievable with traditional methods.

| Data Point | Extracted Information & Data |
| :--- | :--- |
| **Geometric Properties** | - **Structure:** TPMS geometries include **Gyroid, Diamond, Primitive, Schwarz-D, and Schwarz-P**. Fabricated via additive manufacturing (e.g., Selective Laser Melting - SLM). <br> - **Material:** Polymers (resins, PLA, nylon) and metals (SS 316L, Al-10Si-0.3Mg). |
| **Mass Transfer (kLa, HETP)** | > **Key Insight:** TPMS packings have demonstrated superior mass transfer performance compared to the industrial standard Mellapak 250Y.<br><br> - **Mass Transfer Coefficient (kLa):** Showed a **49–61% increase** in effective `kLa` vs. Mellapak 250Y. <br> - **Interfacial Area (a_e):** Achieved a **91–140% increase** in effective gas-liquid interfacial area vs. Mellapak 250Y. <br> - **Advanced Concepts:** **Dynamic Polarity (DP)** packings (3D-printed with multiple polymers) showed a **22.7% increase in absorption** over steel packings. |
| **Hydrodynamics** | - **Pressure Drop (ΔP/m):** Performance varies by geometry. Primitive structures often show the lowest pressure drop. Some studies note higher pressure drops, which can be optimized by adjusting unit cell size. <br> - **Example Data:** A Schwarz-D structure (70% porosity, 2mm unit cell) exhibited a pressure drop of 655 Pa/m. <br> - **Correlations:** Ergun-type equations are used, but specific modified constants for 3D-printed packings are a **data gap**. |
| **Industrial & Economic** | - **Manufacturing:** Additive manufacturing allows for process intensification and precise optimization. *In-situ* cooling channels can be integrated to manage exothermic heat. <br> - **Economic Impact:** Potential for **over 30% reduction** in absorber capital costs. <br> - **Challenges:** Corrosion of certain materials (e.g., aluminum alloys) in amine solvents is a significant concern that requires careful material selection. |

---

### **5. Membrane Contactors**

Membrane contactors are a process intensification technology that uses a porous membrane to provide a high-surface-area interface for mass transfer without dispersing the phases.

| Data Point | Extracted Information & Data |
| :--- | :--- |
| **Geometric Properties** | - **Structure:** Typically hollow fiber modules made from polymers (PVDF, PP, PTFE) or ceramics. <br> - **Surface Area:** Offers a vast surface area-to-volume ratio, up to **30 times more** than traditional packed columns. |
| **Mass Transfer** | - **Mass Transfer Coefficient:** Ceramic hollow fiber membranes have demonstrated overall gas mass transfer coefficients **1.8 times higher** than conventional packed columns. <br> - **Key Challenge (Wetting):** The primary obstacle to long-term stability and commercial adoption. Wetting of membrane pores by the liquid absorbent drastically increases mass transfer resistance and reduces CO₂ flux. Even marginal wetting (<5%) can severely degrade performance. PTFE offers the best wetting resistance but is more expensive. |
| **Hydrodynamics** | - **Operational Benefits:** Mitigates traditional column issues like weeping, flooding, foaming, and entrainment. Allows independent control of gas and liquid flow rates. |
| **Industrial & Economic** | - **Economic Data:** Lower operating power consumption (0.78 GJ/ton CO₂) reported compared to packed columns (1.16 GJ/ton CO₂). <br> - **Process Intensification:** Leads to significantly smaller and lighter equipment (e.g., 66% weight reduction, 72% smaller dimensions). <br> - **Operational Stability:** PTFE membranes have shown stability over 6600 hours. However, comprehensive long-term stability data, especially regarding wetting and fouling, is still underreported. <br> - **Data Gap:** A targeted search for recent (post-2020) techno-economic analyses in high-impact journals that explicitly integrate wetting resistance data was unsuccessful. |

---

### **6. Random Packing**

Random packings consist of discrete pieces with specific geometry that are randomly dumped into the column. Modern designs offer significant improvements over older types like Raschig rings.

#### **6.1 Norton IMTP (Intalox Metal Tower Packing)**

| Data Point | Extracted Information & Data |
| :--- | :--- |
| **Mass Transfer** | - **Mass Transfer Coefficient (KGa):** Performance data is provided in terms of `KGa` values for CO₂ absorption. <br> - **HETP:** HETP values are available for distillation contexts. |
| **Hydrodynamics** | - **Pressure Drop:** Lower pressure drop compared to many plastic packings. |
| **Industrial & Economic** | - **Manufacturer:** Norton (Koch-Glitsch). <br> - **Software:** KG-TOWER™ Software is available for hydraulic rating. |

#### **6.2 Intalox Saddles**

| Data Point | Extracted Information & Data |
| :--- | :--- |
| **Geometric Properties** | - **Void Fraction:** Plastic variants can achieve void ratios up to 95%. <br> - **Structure:** Non-nesting shape promotes even porosity and fluid distribution. |
| **Mass Transfer** | - **Efficiency:** **INTALOX® ULTRA** can increase tower capacity by 10%. HETP is generally lower than for Raschig rings. |
| **Hydrodynamics** | - **Pressure Drop:** Significantly lower pressure drop than Raschig rings. **INTALOX® SNOWFLAKE®** offers the lowest pressure drop among certain plastic random packings. |
| **Industrial & Economic** | - **Manufacturer:** Koch-Glitsch. |

#### **6.3 Cascade Mini Rings (CMR)**

| Data Point | Extracted Information & Data |
| :--- | :--- |
| **Geometric Properties** | - **Structure:** Low aspect ratio (height is 1/3 of diameter) promotes a preferential vertical orientation in the bed. |
| **Mass Transfer** | - **Efficiency:** Higher mass transfer efficiency and better separation effect compared to metal Intalox saddles and Raschig rings. Can provide capacity improvements of up to 15% without loss of efficiency. |
| **Hydrodynamics** | - **Pressure Drop:** Engineered to reduce pressure drop and increase plant capacity, moving the operating point further from flooding. |
| **Industrial & Economic** | - **Benefit:** Good fouling resistance and high mechanical strength. |

#### **6.4 Performance Comparison: Structured vs. Random**

> **Key Insight:** While modern random packings like CMR and Intalox Saddles are far superior to older generations, **structured packings generally outperform random packings** in most key metrics for CO₂ absorption.

- **Efficiency & HETP:** Structured packings have higher efficiency (lower HETP, typically < 0.5 m).
- **Pressure Drop:** Structured packings exhibit significantly lower pressure drop (~100 Pa/m).
- **CO₂ Loading:** Structured packings tend to achieve higher rich CO₂ loading.
- **Energy Consumption:** The combination of higher loading and lower pressure drop results in a lower reboiler duty for solvent regeneration, reducing overall energy consumption.

---

### **7. Summary of Pressure Drop Correlations**

Predicting pressure drop is critical for column design. The following correlations are widely used for packed beds.

| Correlation | Description & Key Features |
| :--- | :--- |
| **Stichlmair** | - Widely referenced model, often used in process simulators (e.g., ASPEN Plus). <br> - Requires three packing-specific empirical constants (C1, C2, C3) fitted to dry pressure drop data. <br> - Can be unreliable at high gas velocities and low liquid rates. |
| **Robbins** | - A simpler method developed in 1991 as an alternative to GPDC charts. <br> - Requires only one empirical constant (the packing factor, Fp). <br> - Not suitable for pressures above 3 bar absolute. Shows large deviations for packings with Fp < 7. |
| **GPDC** | - The Generalized Pressure Drop Correlation (e.g., by Kister and Gill) is a graphical method. <br> - Modified charts exist for structured packings, but specific charts for individual packing types are more accurate. |
| **Ergun** | - A fundamental equation for packed beds. Often used as a basis for more complex models. <br> - Mentioned in the context of 3D-printed packings, but modified constants are a **data gap**. |
| **Other Models** | - **Billet & Schultes (1999)** and **Rocha, Bravo, & Fair (1993)** are also well-regarded. <br> - **Spiegel & Meier (1992)** developed a model specifically for Mellapak packings. |
| **Data Source Note** | Vendor-specific correlations (often proprietary and embedded in software like SULCOL™ or KG-TOWER™) are generally the most accurate. |

---

### **8. Gaps and Inconsistencies**

- **Missing `kLa` Data:** Specific liquid-phase mass transfer coefficients (`kLa`) are not consistently available across many packing types, especially for conventional and ceramic packings. Overall coefficients like `KGa` or `kGae` are more common.
- **Incomplete Pressure Drop Correlations:** While many sources claim "lower pressure drop," the explicit mathematical correlations and their required constants (e.g., for Stichlmair, Robbins, Ergun) are not provided for most packing types.
- **Membrane Contactor Economics:** Detailed techno-economic analyses for membrane contactors that rigorously account for long-term operational stability and wetting resistance are scarce in recent (post-2020) high-impact journal literature.
- **Modern Random Packing Data:** Comprehensive tables directly comparing modern random packings (Intalox Saddles, CMR) with specific `kLa`, HETP, and pressure drop values under identical CO₂ absorption conditions are limited, making a direct quantitative baseline difficult.
- **Recent Industrial Case Studies:** While some case studies were identified, detailed operational data (`kLa`, HETP, ΔP) from high-impact journals (2021-2025) for large-scale CO₂ capture units remains limited in the public domain.