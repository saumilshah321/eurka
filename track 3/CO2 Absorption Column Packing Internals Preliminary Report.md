### **Preliminary Report: CO₂ Absorption Column Internals**

This report synthesizes data on various packing types for CO₂ absorption columns based on the provided research documents. The information is structured to serve as a foundational knowledge base for subsequent analysis and decision-making.

---

### **1. Packing Categories and Types**

The following table categorizes the specific packing types identified in the source material.

| Category | Specific Packing Types Identified |
| :--- | :--- |
| **Conventional Structured** | Mellapak (250Y, 250X, CC, Evo, Plus), Flexipac (Standard, 250Y, 350Y), Montz (B1-250, B1-250M) |
| **Advanced Metallic Structured** | Sulzer BX (Gauze), Sulzer DX (Gauze), Sulzer BXPlus, Flexipac HC (High Capacity), Flexipac CP (Carbon Capture) |
| **Ceramic/Plastic** | Koch-Glitsch Flexeramic (Type 48, Type 88), General Plastic Packings, General Ceramic Packings, Carbon Raschig Rings |
| **3D-Printed / TPMS** | Gyroid, Diamond, Primitive, Schwarz-D, Schwarz-P, XW-Pak, Rombopak 9M (3D-printed version), Dynamic Polarity (DP) Packings |
| **Membrane Contactors** | Hollow Fiber Membrane Contactors (PVDF, PP, PTFE), Ceramic Hollow Fiber Membrane Contactors |
| **Random** | Norton IMTP (Intalox Metal Tower Packing), Intalox Saddles (INTALOX® ULTRA, INTALOX® SNOWFLAKE®), Cascade Mini Rings (CMR), Pall Rings, Raschig Rings |

---

### **2. Extracted Data by Packing Type**

The following tables present detailed data extracted for each packing type. *Note: "Not available" indicates the information was not present in the provided source documents.*

#### **2.1 Conventional Structured Packings**

**Mellapak Series (Sulzer)**
| Data Point | Extracted Information |
| :--- | :--- |
| **Geometric Properties** | - **Specific Surface Area:** 250 m²/m³ for 250Y/250X; 125 m²/m³, 500 m²/m³ also mentioned. |
| **Mass Transfer** | - **kGae:** Generally lower kGae values for Mellapak 250Y compared to gauze packings like Sulzer BX. <br> - **HETP:** Pressure drop per theoretical stage is 0.3-1.0 mbar. |
| **Fluid Dynamics** | - **Pressure Drop:** 0.3-1.0 mbar per theoretical stage. Approx. 2 mbar/m at 70-80% flooding. For CO₂ absorption, 10-15 mbar at optimal gas velocities (2.0-2.5 m/s). MellapakPlus offers up to 50% higher capacity and lower pressure drop than conventional Mellapak. <br> - **Flooding/Loading:** Minimum liquid load ~0.2 m³/m²h; maximum can exceed 200 m³/m²h. |
| **Industrial/Economic** | - **Manufacturer:** Sulzer. <br> - **Commercial Use:** Widely used industry standard. Mellapak CC and Evo are specifically designed for CO₂ capture. Available in stainless steel, alloys, and thermoplastics. <br> - **Software:** SULCOL software available for sizing. |

**Flexipac Series (Koch-Glitsch)**
| Data Point | Extracted Information |
| :--- | :--- |
| **Geometric Properties** | - **Specific Surface Area:** 250 m²/m³ for Flexipac 250Y. |
| **Mass Transfer** | - **CO₂ Absorption Efficiency:** Flexipac 250Y noted for high CO₂ loading. Effective surface area modeled for Flexipac 350Y using CO₂ absorption into MEA. <br> - **kLa / KGa:** KG-TOWER™ software can provide KGa values. |
| **Fluid Dynamics** | - **Pressure Drop:** Generally provides lower pressure drop per theoretical stage compared to trays and random packings. |
| **Industrial/Economic** | - **Manufacturer:** Koch-Glitsch. <br> - **Commercial Use:** Industry standard. Available in various metals and plastics. |

**Montz B1 Series**
| Data Point | Extracted Information |
| :--- | :--- |
| **Geometric Properties** | Not available. |
| **Mass Transfer** | - **kG:** Corrugation orientation angle (45° vs. 60°) can impact the gas-side mass transfer coefficient (kG). |
| **Fluid Dynamics** | - **Pressure Drop:** Hydrodynamic parameters for B1-250M align with literature correlations for F-factors below 3. |
| **Industrial/Economic** | - **Manufacturer:** Montz. <br> - **Commercial Use:** Mentioned in benchmarking studies for mass transfer correlations. |

#### **2.2 Advanced Metallic Structured Packings**

**Sulzer BX / DX Series (Gauze)**
| Data Point | Extracted Information |
| :--- | :--- |
| **Geometric Properties** | - **Structure:** Gauze/wire mesh packing. DX has a coarser structure than BX. |
| **Mass Transfer** | - **kGae:** Sulzer BX has demonstrated higher kGae values (more efficient) than Mellapak 250Y in CO₂ absorption. <br> - **HETP:** Known for high separation efficiency (low HETP). DXM/DYM variants have constant HETP over a wide range of loads. |
| **Fluid Dynamics** | - **Pressure Drop:** BXPlus offers 20% lower pressure drop than standard BX. Known for very low pressure drop, suitable for vacuum applications. |
| **Industrial/Economic** | - **Manufacturer:** Sulzer. <br> - **Commercial Use:** Milestone for difficult separation tasks and heat-sensitive substances. DX is suitable for lab columns. |

**Flexipac HC / CP (Koch-Glitsch)**
| Data Point | Extracted Information |
| :--- | :--- |
| **Geometric Properties** | - **Flexipac CP:** Patented geometry optimized for carbon capture. <br> - **Flexipac HC:** Modified corrugation geometry to eliminate abrupt changes in flow direction. |
| **Mass Transfer** | - **CO₂ Absorption Efficiency:** Flexipac CP offers superior capture efficiency, allowing for reduced column height and solvent recirculation. |
| **Fluid Dynamics** | - **Pressure Drop:** Flexipac CP claims up to a 65% reduction in pressure drop compared to existing structured packings in CO₂ service. Flexipac HC maintains low pressure drop at maximum capacity. |
| **Industrial/Economic** | - **Manufacturer:** Koch-Glitsch. <br> - **Commercial Use:** Flexipac CP is specifically developed for post-combustion carbon capture. |

#### **2.3 Ceramic and Plastic Packings**

**Flexeramic (Koch-Glitsch)**
| Data Point | Extracted Information |
| :--- | :--- |
| **Geometric Properties** | - **Specific Surface Area:** Type 48: 208 m²/m³; Type 88: 125 m²/m³. |
| **Mass Transfer** | - **Efficiency:** Natural wettability improves efficiency in aqueous systems over metal/plastic. Higher efficiency than random packing. <br> - **kLa / HETP:** Not available. |
| **Fluid Dynamics** | - **Pressure Drop:** 50% lower pressure drop compared to ceramic saddles at the same gas flow. Very low resistance due to vertically oriented sheets. |
| **Industrial/Economic** | - **Manufacturer:** Koch-Glitsch. <br> - **Commercial Use:** Designed for corrosive environments (e.g., sulfuric acid), heat/mass transfer. Economical alternative to exotic alloys. |

**General Plastic Packings**
| Data Point | Extracted Information |
| :--- | :--- |
| **Geometric Properties** | - **Void Fraction:** Can achieve high void ratios, up to 95% for plastic Intalox saddles. |
| **Mass Transfer** | - **Chemical Compatibility:** Extends lifetime of amine solvents by avoiding metal-induced degradation. Challenge with wetting due to hydrophobic surfaces. |
| **Fluid Dynamics** | - **Pressure Drop:** Generally higher capacity and lower pressure drop than ceramic equivalents. |
| **Industrial/Economic** | - **Benefit:** Less susceptible to fouling and corrosion. Can reduce operational costs related to solvent degradation. |

#### **2.4 3D-Printed / TPMS Packings**

**TPMS (Gyroid, Diamond, Primitive, Schwarz)**
| Data Point | Extracted Information |
| :--- | :--- |
| **Geometric Properties** | - **Structure:** Triply Periodic Minimal Surfaces with high surface-area-to-volume ratio. Fabricated via additive manufacturing (e.g., SLM). |
| **Mass Transfer** | - **kLa:** Showed 49–61% increase in effective kLa compared to Mellapak 250Y. <br> - **Interfacial Area:** 91–140% increase in effective gas-liquid interfacial area vs. Mellapak 250Y. |
| **Fluid Dynamics** | - **Pressure Drop:** Performance varies by type. Primitive structures often show the lowest pressure drop. Some studies note higher pressure drop than conventional packings, which can be optimized by adjusting unit cell size. |
| **Industrial/Economic** | - **Scalability:** Additive manufacturing allows for precise control and optimization. <br> - **Cost:** Can lead to over 30% reduction in absorber capital costs. <br> - **Material:** Fabricated from polymers and metals (e.g., SS 316L, Al-10Si-0.3Mg). Corrosion of aluminum alloys in MEA is a concern. |

#### **2.5 Membrane Contactors**

**Hollow Fiber Membrane Contactors**
| Data Point | Extracted Information |
| :--- | :--- |
| **Geometric Properties** | - **Surface Area:** Offers substantially more surface area (up to 30 times) than traditional packed columns. |
| **Mass Transfer** | - **Mass Transfer Coefficient:** Ceramic hollow fibers demonstrated overall gas mass transfer coefficients 1.8 times higher than conventional packed columns. <br> - **Challenges:** Wetting of membrane pores by liquid absorbent drastically reduces mass transfer rates. |
| **Fluid Dynamics** | - **Benefits:** Mitigates issues like weeping, flooding, entrainment, and foaming. |
| **Industrial/Economic** | - **Cost:** Lower operating power consumption (0.78 GJ/ton CO₂) than packed columns (1.16 GJ/ton CO₂). <br> - **Size:** Reduced weight (by 66%) and smaller dimensions (by 72%). <br> - **Limitations:** Limited membrane lifetime requires periodic replacement. |

#### **2.6 Random Packings**

**Norton IMTP (Intalox Metal Tower Packing)**
| Data Point | Extracted Information |
| :--- | :--- |
| **Geometric Properties** | Not available. |
| **Mass Transfer** | - **KGa / HETP:** Performance data provided in terms of KGa values for CO₂ absorption and HETP for distillation. |
| **Fluid Dynamics** | - **Pressure Drop:** Lower pressure drop compared to many plastic packings. |
| **Industrial/Economic** | - **Manufacturer:** Norton (Koch-Glitsch). <br> - **Software:** KG-TOWER™ Software available for hydraulic rating. |

**Intalox Saddles**
| Data Point | Extracted Information |
| :--- | :--- |
| **Geometric Properties** | - **Void Fraction:** Plastic variants can achieve void ratios up to 95%. <br> - **Structure:** Non-nesting shape for even porosity and fluid distribution. |
| **Mass Transfer** | - **Efficiency:** Improved efficiency compared to Raschig rings. INTALOX® ULTRA can increase tower capacity by 10%. |
| **Fluid Dynamics** | - **Pressure Drop:** Lower pressure drop than Raschig rings. INTALOX® SNOWFLAKE® offers the lowest pressure drop among certain plastic random packings. |
| **Industrial/Economic** | - **Manufacturer:** Implied to be Koch-Glitsch. |

**Cascade Mini Rings (CMR)**
| Data Point | Extracted Information |
| :--- | :--- |
| **Geometric Properties** | - **Structure:** Low aspect ratio (height is 1/3 of diameter) promotes preferential vertical orientation. |
| **Mass Transfer** | - **Efficiency:** Higher mass transfer efficiency and better separation effect than metal Intalox saddles and Raschig rings. |
| **Fluid Dynamics** | - **Pressure Drop:** Specifically engineered to reduce pressure drop and increase plant capacity. |
| **Industrial/Economic** | - **Benefit:** Good fouling resistance. |

---

### **3. Innovation Frontier (2023-2025)**

Findings from recent and forward-looking research highlight significant advancements in packing technology, especially through additive manufacturing.

- **TPMS Outperforming Conventional Packings:** Research demonstrates that 3D-printed TPMS structures (e.g., Gyroid, Schwarz-D) achieve superior mass transfer performance for CO₂ absorption compared to the industrial standard Mellapak 250Y. Key improvements include:
    - **49–61% increase** in effective mass transfer performance ($k_La_{eff}$).
    - **91–140% increase** in the effective gas–liquid interfacial area.

- **Hybrid and Advanced Material Systems:**
    - **Dynamic Polarity (DP) Packings:** 3D-printed packings using multiple polymeric materials have shown a **22.7% increase in absorption** over conventional steel packings by promoting turbulence and refreshing the liquid film.
    - **Hybrid Membrane-Solvent Systems:** These systems show potential for significantly lower energy consumption (up to 49% less) compared to conventional MEA absorption with packed columns. Regeneration energy as low as 1.54–1.56 GJ/tCO₂ is reported.

- **Process Intensification and Economic Impact:**
    - The design flexibility of 3D printing allows for process intensification, potentially reducing absorber capital costs by **over 30%**.
    - Integration of cooling channels within 3D-printed packings allows for *in-situ* heat removal, improving CO₂ uptake by managing the exothermic absorption reaction.
    - A 2025 publication discusses ongoing HETP evaluation and correlation development for advanced packings like Sulzer DX, indicating continued refinement of performance prediction models.

---

### **4. Gap Analysis**

The initial information search revealed several gaps in the available data:

- **Missing Mass Transfer Coefficients (kLa):** Specific liquid-phase mass transfer coefficients (`kLa`) are not consistently available across many packing types, especially for conventional and ceramic packings. Overall coefficients like `KGa` or `kGae` are more commonly cited.

- **Incomplete Data for Membrane Contactors:**
    - A targeted search for detailed economic analysis and wetting resistance data for hollow fiber membrane contactors in the *Journal of Membrane Science* after 2020 yielded no direct results.
    - While performance benefits are mentioned, detailed techno-economic data and long-term stability studies appear scarce in the provided context.

- **Lack of Explicit Pressure Drop Correlations:** While many sources claim "lower pressure drop," the explicit mathematical correlations (e.g., constants for the Stichlmair or Robbins equations) are not provided for most packing types in the documents.

- **Limited Data on Modern Random Packings:** Comprehensive comparative data tables with specific `kLa`, HETP, and pressure drop values for modern random packings (Intalox Saddles, Cascade Mini Rings) were not found, making a direct quantitative baseline comparison against structured packings difficult.

- **Scarcity of Recent, High-Impact Industrial Case Studies:** The search did not yield detailed industrial case studies published in high-impact journals between 2020-2025 that provide comprehensive operational data (`kLa`, HETP, pressure drop) for CO₂ absorption applications. Much of the data is from manufacturer brochures or older papers.