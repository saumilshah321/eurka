# Section 2: Comprehensive Thermodynamic Database

## **Executive Overview**

This document presents a comprehensive thermodynamic and physical property database for carbon dioxide (CO₂) absorption in aqueous amine systems, synthesized from a rigorous review of scientific literature published between 2015 and 2025. The data compiled herein are essential for the accurate design, simulation, and optimization of CO₂ capture processes, which are critical for industrial decarbonization efforts. The database is structured to provide chemical engineers and process modelers with readily accessible information on Vapor-Liquid Equilibria (VLE), thermodynamic model parameters, Henry's Law constants, key transport properties (density, viscosity, diffusivity, thermal conductivity), and crucial thermal properties (heat of absorption, heat capacity).

The primary objective of this compilation is to consolidate disparate experimental data and modeling efforts from high-impact journals such as *Fluid Phase Equilibria*, *Industrial & Engineering Chemistry Research*, and the *Journal of Chemical & Engineering Data*. By organizing this information into a series of structured, publication-quality tables, this document serves as a foundational reference for validating existing process models, developing new solvent formulations, and identifying knowledge gaps for future research. Each data entry is meticulously cited to ensure traceability and facilitate further in-depth investigation. The following sections detail the available data, the models used for their correlation, and the operational conditions under which they were obtained.

---

## **2.1 Vapor-Liquid Equilibria (VLE) Data**

### **2.1.1 Analytical Context**

Vapor-Liquid Equilibrium (VLE) data, which describe the relationship between the partial pressure of CO₂ in the gas phase (P_CO₂) and the CO₂ loading (α, mol CO₂ / mol amine) in the liquid solvent, are the cornerstone of absorption process design. This equilibrium dictates the theoretical maximum solvent capacity and the driving force for mass transfer in both the absorber and the stripper. Accurate VLE data across a wide range of temperatures, amine concentrations, and CO₂ loadings are indispensable for:
-   **Designing Absorption and Stripping Columns:** Determining the number of theoretical stages or the required packing height.
-   **Evaluating Solvent Performance:** Assessing the cyclic capacity and energy requirements for regeneration.
-   **Validating Thermodynamic Models:** Providing the fundamental experimental basis for regressing parameters for activity coefficient models (e.g., e-NRTL) and equations of state (e.g., PC-SAFT).

Recent research has focused on generating new experimental VLE data for both conventional amines like Monoethanolamine (MEA) and promising new solvents and blends, such as Piperazine (PZ) activated 2-amino-2-methyl-1-propanol (AMP) and N,N-Diethylethanolamine (DEEA). The data presented in Table 2.1 summarize these efforts, providing a critical overview of the available VLE information from the recent literature.

### **2.1.2 VLE Data Compilation**

The following table synthesizes the VLE data and modeling studies identified in the literature review from 2015-2025. Due to the nature of review articles, specific data points are often summarized rather than tabulated in full. This table captures the essence of the available information, including the systems studied, conditions, and the models used for correlation.

**Table 2.1: Compilation of Recent Vapor-Liquid Equilibrium (VLE) Data for CO₂-Amine Systems**

| Amine System(s) | Amine Conc. (wt%) & Conditions | VLE Data Description & Key Findings | Thermodynamic Model Used for Correlation | Source(s) |
| :--- | :--- | :--- | :--- | :--- |
| **Monoethanolamine (MEA)** | 30 wt% at 40°C & 120°C | New experimental VLE data (P_CO₂ vs. loading) reported. Data were validated against existing literature. | - Extended UNIQUAC<br>- Electrolyte NRTL (e-NRTL) | *AIChE Journal* (AX19P), *I&EC Research* (2Z2HW) |
| **Monoethanolamine (MEA)** | 15, 30, 45, 60 wt% | Experimental data illustrating P_CO₂ vs. CO₂ loading curves. | - Chemical equilibrium model with ionic activity coefficients.<br>- Kent & Eisenberg model (for loading 2.0-7.0 mol ratio). | *AP5O4-search* |
| **Monoethanolamine (MEA)** | 30, 40, 50 wt% at 40°C | New experimental VLE data presented and validated against literature. | Not specified in source. | *AP5O4-search* |
| **2-Amino-2-methyl-1-propanol (AMP) & Piperazine (PZ)** | 30-50 wt% total amines; various AMP/PZ ratios | New experimental VLE data reported, especially at low T and low amine concentrations for water wash section modeling. | - Open-access e-NRTL model developed in Aspen Plus.<br>- Modified Clegg-Pitzer equations. | *T3GXQ-search*, *D72DX-search* |
| **2-Amino-2-methyl-1-propanol (AMP)** | Not specified | VLE data used to regress parameters for CPA EoS and modified Kent-Eisenberg models to determine CO₂ solubility. | - CPA Equation of State<br>- Modified Kent-Eisenberg | *AP5O4-search* |
| **Piperazine (PZ)** | 0.1 to 6.2 mol/L | A large dataset of 517 experimental points for CO₂ solubility vs. P_CO₂ (0.03 to 7399 kPa) from 298-373 K. | - Modified Kent-Eisenberg model<br>- Modified Pitzer's model | *4II85-search*, *N0TH8-search*, *D72DX-search* |
| **N,N-Diethylethanolamine (DEEA)** | 2 M and 5 M (approx. 23 & 58 wt%) | Experimental VLE data collected from 40-120°C using both atmospheric and high-pressure apparatus. | Extended UNIQUAC model (AARD of 26.5%). | *YWV49-search*, *I7WZ0-search* |
| **N-(2-Hydroxyethyl) Piperazine (HEPZ)** | 5, 15, 30 wt% | New experimental CO₂ solubility data at T = 313.15–393.15 K. Used for e-NRTL parameter regression. | e-NRTL model. | *4II85-search* |
| **N-methyldiethanolamine (MDEA)** | Not specified | Isobaric VLE measurements of aqueous MDEA solutions reported. VLE data also used for e-NRTL model development for MDEA/PZ blends. | e-NRTL model. | *D72DX-search* |
| **Novel Blend (HS3): 3-amino-1-propanol & 1-(2-hydroxyethyl) pyrrolidine** | Not specified | VLE data collected over relevant loading and temperature ranges for industrial capture. | ELECNRTL model in Aspen Plus. | *T3GXQ-search*, *YWV49-search* |

### **2.1.3 Analytical Summary of VLE Data Landscape**

The period between 2015 and 2025 has seen a concerted effort to both expand the VLE database for emerging amine systems and refine the models used to describe established ones.

> **Key Insight:** There is a clear trend moving from simple empirical models like the Kent-Eisenberg model towards more rigorous, thermodynamically consistent frameworks such as the electrolyte-NRTL (e-NRTL) and extended UNIQUAC models. While simpler models are useful for quick correlations, the e-NRTL framework is now the *de facto* standard for detailed process simulation, as it can simultaneously predict VLE, speciation, and thermal properties.

**Identified Trends and Gaps:**
1.  **Focus on Blended Amines:** A significant portion of new VLE data is for blended amine systems (e.g., AMP/PZ, MDEA/PZ). This reflects the industry's drive to find solvents that combine the high absorption rate of primary/secondary amines with the low regeneration energy of tertiary/hindered amines.
2.  **High-Concentration Data:** Research is pushing into higher amine concentrations (e.g., 60 wt% MEA, 5 M DEEA), which are relevant for advanced, intensified capture processes. However, models often show larger deviations at these high concentrations, indicating a need for improved parameterization.
3.  **Data for Ancillary Processes:** A notable gap identified in the literature is the scarcity of VLE data at low temperatures and low amine concentrations, which is crucial for accurately designing and modeling water wash sections of capture plants.
4.  **Data Quality and Consistency:** Multiple sources report new "validated" data for 30 wt% MEA, suggesting its role as a benchmark system for qualifying new experimental setups. However, discrepancies among datasets for other systems (e.g., AMP/PZ viscosity) highlight the ongoing need for high-quality, consistent experimental work.

**Implication for Process Modeling:** The development of open-access, validated e-NRTL models for systems like AMP/PZ in platforms like Aspen Plus is a major step forward, enabling more reliable and accessible process simulations for the broader engineering community. However, the accuracy of any simulation remains heavily dependent on the quality and range of the underlying VLE data used for parameter regression.

---

## **2.2 Thermodynamic Model Parameters**

### **2.2.1 Analytical Context**

Thermodynamic models are mathematical frameworks used to calculate the physical and chemical properties of a system at equilibrium. For CO₂-amine systems, these models must account for the highly non-ideal behavior arising from electrolyte solutions, where ions are formed via chemical reactions. The parameters within these models are not physical constants but are regressed from experimental data to best represent the system's behavior. Key model categories include:
-   **Activity Coefficient Models:** These models, like NRTL, e-NRTL, and UNIQUAC, describe deviations from ideal behavior in the liquid phase. The binary interaction parameters (BIPs) are the adjustable components. The e-NRTL model is particularly powerful as it explicitly handles molecule-molecule, molecule-ion, and ion-ion interactions.
-   **Equations of State (EoS):** Models like PC-SAFT and CPA describe the P-V-T behavior of fluids. They are often combined with activity coefficient models or use their own association terms to model reactive systems.

The parameters compiled in this section are the "tunable" elements that allow these generalized models to be applied to specific chemical systems. The quality of these parameters directly determines the predictive accuracy of process simulations.

### **22.2 Master Thermodynamic Parameter Matrix**

The following table consolidates information on thermodynamic model parameters that have been regressed or discussed in the recent literature. As full parameter sets are rarely published in review articles, this matrix describes the *scope* of the parameterization effort—the system, model, and type of parameters determined—to guide users to the original source for detailed values.

**Table 2.2: Master Thermodynamic Parameter Matrix for CO₂-Amine Systems (2015-2025)**

| Amine System(s) | Model | Parameter Type & Details | Temperature / Pressure Dependence | Source(s) |
| :--- | :--- | :--- | :--- | :--- |
| **MEA, DEA, MDEA, AMP** | Extended UNIQUAC | Binary interaction parameters (BIPs) regressed against experimental VLE, excess enthalpy (Hᴱ), and freezing point data. | Parameters fitted over a broad T range (-20 to 200°C), implying temperature dependency is captured. | *6XG01-search* |
| **MEA / H₂O / CO₂** | Extended UNIQUAC | Full model parameters fitted using VLE data, physical CO₂ solubility, Hᴱ, and speciation data. Symmetrical activity coefficients for H₂O, unsymmetrical for all solutes. | Validated over 40-120°C, indicating temperature-dependent parameters. | *BUD8T-search* |
| **AMP / PZ / H₂O / CO₂** | Electrolyte NRTL (e-NRTL) | A comprehensive, open-access model with ~100 parameters for the PZ system and ~39 for the AMP system, regressed sequentially. Includes molecule-molecule and molecule-electrolyte BIPs. | Regressed over 20-160°C. Temperature dependence is explicitly formulated in the e-NRTL model, often via a Gibbs-Helmholtz expression. | *T3GXQ-search*, *4II85-search* |
| **HEPZ / H₂O / CO₂** | Electrolyte NRTL (e-NRTL) | e-NRTL parameters regressed alongside standard-state properties (ΔfG, ΔfH, Cp) for ionic species. Non-randomness factor (α) fixed at 0.2. | Parameters were regressed from data at 313.15–393.15 K. BIPs expressed as a function of temperature: `τij = aij + bij * T`. | *I7WZ0-search*, *4II85-search* |
| **1MPZ / H₂O / CO₂** | Electrolyte NRTL (e-NRTL) | NRTL and e-NRTL interaction parameters, along with standard state properties of amine ions, were regressed from experimental and literature data. | Temperature dependency is a core feature of the e-NRTL parameterization. | *T7MVT-search* |
| **DEA / H₂O / CO₂** | Pitzer Model | Interaction parameters for the Pitzer model were used to evaluate species concentrations and activity coefficients. | Temperature dependence is implicitly included through VLE data fitting. | *W9H4U-search* |
| **DEEA / H₂O / CO₂** | Extended UNIQUAC | Binary interaction parameters were fitted to experimental partial and total pressures from VLE data. | BIPs noted as temperature-dependent, fitted over a 40-120°C range. | *I7WZ0-search* |
| **Various Alkanolamines** | PC-SAFT | Cross-interaction parameters (kᵢⱼ) for binary pairs. Some studies assume kᵢⱼ is temperature-independent, but performance is validated across T ranges. | Temperature dependence is a subject of study; some models incorporate it, while others use a single optimized value. | *ED9D6-search*, *C6UST-search* |
| **2-methylimidazole / H₂O / CO₂** | CPA EoS | Temperature-dependent BIPs between 2-methylimidazole and CO₂ were found to be necessary for accurate VLE representation. | Explicitly temperature-dependent BIPs were used, valid from 293.15–393.15 K. | *I7WZ0-search* |
| **General Amines** | Aspen Plus (AMINES Package) | ELECNRTL model requires BIPs for molecule-molecule and molecule-electrolyte pairs, regressed from VLE data. Custom regression often needed for accuracy. | Aspen's model can handle temperature-dependent parameters. Regression is performed over relevant industrial T & P ranges. | *MF1N4-search* |
| **MDEA-PZ Blend** | E-NRTL & PC-SAFT | E-NRTL parameters for activity coefficients and PC-SAFT parameters for fugacity coefficients. | Parameters validated over a broad operating range, implying temperature dependence is captured. | *N0TH8-search* |

### **2.2.3 Analytical Summary of Thermodynamic Parameterization**

The literature review reveals a clear and sophisticated approach to thermodynamic modeling, dominated by the **e-NRTL framework**.

> **Key Insight:** Parameterization is no longer a simple curve-fitting exercise. Modern approaches involve a *simultaneous regression* of parameters against a diverse set of experimental data, including VLE, heat of absorption (enthalpy), heat capacity, and even liquid-phase speciation data (from NMR or Raman spectroscopy). This multi-property fitting ensures the resulting model is thermodynamically consistent and more robust for extrapolation.

**Identified Trends and Challenges:**
1.  **Temperature Dependency is Standard:** Virtually all advanced models (e-NRTL, extended UNIQUAC, CPA) now incorporate temperature-dependent binary interaction parameters. This is crucial for accurately modeling both the low-temperature absorber and the high-temperature stripper within the same framework. Simple linear relationships (`A + B*T`) or more complex Gibbs-Helmholtz forms are common.
2.  **Lack of Publicly Available Parameter Sets:** A major challenge for the engineering community is that while many studies *describe* the regression of comprehensive parameter sets (e.g., "100 parameters for the PZ system"), the full parameter matrices are rarely published. They often remain proprietary or embedded within commercial software packages (e.g., Aspen Plus, DWSIM Pro).
3.  **Rise of EoS Models:** While activity coefficient models like e-NRTL dominate, there is growing interest in molecular-based Equations of State like PC-SAFT and CPA. These models offer a more theoretical foundation and have the potential to be more predictive, requiring fewer adjustable parameters, especially for blended amine systems.
4.  **Data-Driven Parameterization:** The quality of any parameter set is entirely dependent on the quality and breadth of the experimental data it was regressed against. The most robust models are those validated against VLE, thermal, and transport property data across a wide operational window.

---

## **2.3 Henry's Law Constants**

### **2.3.1 Analytical Context**

Henry's Law describes the physical solubility of a gas in a liquid. In CO₂-amine systems, the overall absorption is a combination of physical dissolution and chemical reaction. The Henry's Law constant (H_CO₂) is the proportionality factor that relates the partial pressure of CO₂ to its concentration in the liquid phase *in a physically dissolved state*. It is a critical parameter because:
-   It defines the baseline physical absorption, which is particularly relevant at high CO₂ partial pressures.
-   It is a necessary input for rigorous thermodynamic models (like e-NRTL) and kinetic models.

Directly measuring H_CO₂ in a reactive amine solution is challenging. Therefore, the **N₂O analogy** is a widely accepted technique. This method involves measuring the solubility of nitrous oxide (N₂O), a gas with physical properties similar to CO₂, which does not react with the amine. The Henry's constant for CO₂ is then estimated using a well-established ratio:

`H_CO₂,amine = H_N₂O,amine * (H_CO₂,water / H_N₂O,water)`

Accurate, temperature-dependent correlations for the Henry's constants of both gases in pure water are thus essential for this method.

### **2.3.2 Henry's Law Constant Database**

The table below summarizes the available information on Henry's Law constants for CO₂ in amine solutions.

**Table 2.3: Henry's Law Constant (H_CO₂) Database and Correlations**

| Amine System(s) | Correlation / Expression for H_CO₂ | Temperature & Concentration Dependence | Methodology / Notes | Source(s) |
| :--- | :--- | :--- | :--- | :--- |
| **General Aqueous Amines** | New expressions developed for H_CO₂ as a function of T and amine concentration. | Validity extended to higher temperatures (up to 393 K), which is crucial for stripper modeling. H_CO₂ generally increases with temperature. | Often derived using the N₂O-CO₂ analogy. Relies on accurate HLC correlations for CO₂ and N₂O in pure water (e.g., from Carroll et al. or Harvey). | *NCL9D-search*, *DMSLS-search*, *ILL7Y-search* |
| **Mixed Amine Solutions** | Semi-empirical equations (e.g., by Monteiro and Svendsen, 2015) provide correlations for HLC over various T and P ranges. | Correlated as a function of T and solvent composition. Amine concentration has a significant influence. | Models often use an "excess Henry's law constant" approach to predict solubility in binary and ternary amine solutions. | *4GECU-search*, *DMSLS-search*, *XDQOV-search* |
| **Ionic Liquids (ILs)** | Specific HLC values reported for ILs that do not react chemically with CO₂. | Temperature dependence is a key parameter in the correlations. | Direct solubility measurements are possible in non-reactive ILs, providing a direct route to HLC. | *4GECU-search* |
| **Various Alkanolamines** | Empirical relations, often in the form of `ln(K) = A/T + B`, are used for Henry's constant in models like the modified Kent-Eisenberg. | HLC is explicitly treated as a temperature-dependent parameter in thermodynamic models. | Integrated as a parameter within broader VLE models. | *3UQF8-search*, *XDQOV-search* |

### **2.3.3 Analytical Summary of Henry's Law Data**

> **Key Insight:** The N₂O analogy remains the state-of-the-art method for estimating the physical solubility of CO₂ in reactive amine solutions. The accuracy of this technique is highly dependent on the quality of the underlying correlations for the Henry's constants of CO₂ and N₂O in pure water.

**Identified Trends:**
1.  **Push to Higher Temperatures:** A clear trend is the development of HLC correlations valid at higher temperatures (up to 393 K / 120°C). This is a direct response to the need for more accurate stripper modeling, where physical solubility can still play a role in the overall energy balance.
2.  **Focus on Blends:** Models are being extended to predict HLC in blended amine solutions, which is more complex than for single amines. This often involves mixture-specific interaction parameters.
3.  **Integration into Models:** The Henry's Law constant is rarely considered in isolation. It is an integral parameter within comprehensive thermodynamic frameworks like e-NRTL, where its value is often regressed or calculated as part of the overall model fitting.

---

## **2.4 Physical and Transport Properties**

### **2.4.1 Analytical Context**

While thermodynamic properties dictate equilibrium, transport properties (density, viscosity, diffusivity) and thermal properties (thermal conductivity) govern the *rates* of heat and mass transfer. They are essential for the mechanical and thermal design of a CO₂ capture plant, impacting:
-   **Equipment Sizing:** Column diameter, pump power, and heat exchanger area.
-   **Hydrodynamics:** Pressure drop, liquid hold-up, and flooding in packed columns.
-   **Mass Transfer Efficiency:** The rate of CO₂ absorption is directly influenced by liquid-phase diffusivity.

The viscosity of loaded amine solutions is a particularly critical parameter, as high viscosity can dramatically increase pumping costs and reduce mass transfer coefficients, hindering overall process efficiency.

### **2.4.2 Density (ρ)**

**Table 2.4.1: Density Correlations and Data for Aqueous Amine Systems (2015-2025)**

| Amine System(s) | Correlation / Model Type | Data & Validity Range | Source(s) |
| :--- | :--- | :--- | :--- |
| **Piperazine (PZ)** | New density model using Redlich-Kister expansion for excess molar volume. | New data for up to 65 wt% PZ from 20-70°C. Model correlates density as a function of T and concentration. | *RZBL7-search*, *B7XQX-search* |
| **AMP + Hexamethylenediamine (HMDA)** | Redlich-Kister equation for excess molar volume. | New density measurements reported in 2023 for aqueous mixtures. | *RZBL2-search*, *E9VKN-search* |
| **2-dimethylaminoethanol or 2-diethylaminoethanol (Partially Carbonated)** | Specific density correlations developed. | Accurate to within ± 0.2%. Covers T = 298.15 K to 353.15 K. | *RZBL7-search* |
| **MDEA + AMP (Unloaded & Loaded)** | Setschenow-type or modified Weiland's correlations. | New experimental data reported for various temperatures, mass fractions, and CO₂ loadings. | *B95S7-search*, *5DM8U-search* |
| **Monoethylethanolamine (EMEA) & Diethylethanolamine (DEEA)** | Correlations for binary aqueous mixtures. | Density correlations examined. | *B95S7-search* |
| **MEA + Potassium Lysinate (K-Lys)** | Experimental measurements. | Density data measured as part of kinetic and thermodynamic investigation. | *B95S7-search* |

### **2.4.3 Viscosity (μ)**

**Table 2.4.2: Viscosity Correlations and Data for Aqueous Amine Systems (2015-2025)**

| Amine System(s) | Correlation / Model Type | Key Findings & Validity Range | Source(s) |
| :--- | :--- | :--- | :--- |
| **MDEA + AMP (Unloaded & Loaded)** | New correlations developed from experimental data. | For T = 303.15-343.15 K, various mass fractions, and CO₂ loading (α = 0.11 to 0.80). Viscosity increases with loading, decreases with T. | *RZBL7-search*, *B95S7-search* |
| **MEA (50-80 wt%) & 3A1P (30, 50 wt%)** | Specific models regressed for experimental data. | Data measured from 298.15 K to 373.15 K at various CO₂ loadings. | *B95S7-search* |
| **AMP + PZ (Unloaded & Loaded)** | Modified Redlich–Kister equation for viscosity deviation. | Investigated across T = 20-80°C. Viscosity depends on AMP/PZ ratio and CO₂ loading. Noted discrepancies in existing datasets. | *RZBL7-search*, *B95S7-search* |
| **2-dimethylaminoethanol or 2-diethylaminoethanol (Partially Carbonated)** | Specific correlations developed. | Covers T = 298.15 K to 353.15 K. | *RZBL7-search* |
| **MDEA-based Blends (MDEA+DIPA, MEA, DEA)** | Artificial Intelligence (AI) / Machine Learning (ML) models (ANFIS, MLPANN, SVM, LSSVM). | ML models developed to estimate viscosity as a function of T, loading, pressure, and MW. Showed satisfactory agreement with experimental data. | *B95S7-search* |
| **General Amine-Water Mixtures** | - Eyring's viscosity model<br>- McAllister's kinematic viscosity model | Provide theoretical/semi-empirical foundation for viscous flow. Loaded amine mixtures typically exhibit Newtonian fluid behavior. | *B95S7-search* |

### **2.4.4 Diffusivity (D)**

**Table 2.4.3: Diffusivity Data and Modeling Approaches (2015-2025)**

| Amine System(s) | Modeling Approach / Method | Key Findings & Observations | Source(s) |
| :--- | :--- | :--- | :--- |
| **MEA-Water-CO₂** | Molecular Dynamics (MD) Simulations. | Diffusivity of CO₂ increases with temperature (highest at 318 K vs. 298/313 K). D_CO₂ > D_H₂O > D_MEA due to smaller MW. | *EKEYQ-search*, *5DM8U-search* |
| **General Reactive Amines** | N₂O Analogy. | A common experimental practice to estimate D_CO₂ using inert N₂O. Fick diffusion coefficients can be derived from Maxwell-Stefan diffusivities. | *EKEYQ-search*, *5DM8U-search* |
| **MEA Solutions** | Wilke-Chang Equation. | Empirical correlation used to calculate diffusivity of MEA and H₂O, and adapted to estimate D_CO₂. | *EKEYQ-search* |
| **Diamine-based water-lean absorbents** | Experimental investigation. | Diffusivity increases with temperature. Enhanced diffusivity of carbamates in water-lean solvents can improve CO₂ mass transfer rates. | *RZBL7-search* |

### **2.4.5 Thermal Conductivity (k)**

**Table 2.4.4: Thermal Conductivity Data and Correlations (2015-2025)**

| Amine System(s) | Data & Conditions | Key Findings & Observations | Source(s) |
| :--- | :--- | :--- | :--- |
| **MEA, DEA, AMP, NaOH, K₂CO₃, Potassium Glycinate (PG)** | Experimental measurements at 294.82 K, 102.02 kPa. Mole fraction range 0.00 to 0.0825. | Measured thermal conductivity with uncertainty of ±0.001 Wm⁻¹K⁻¹. Satisfactory agreement with literature for most, except PG (no prior data). | *0P9SG-search* |
| **General CO₂-Amine Systems** | General Acknowledgment. | While few specific models were found from 2015-2025, the importance of thermal conductivity for heat exchanger design is widely recognized. | *RZBL7-search*, *L15TT-search* |

### **2.4.6 Analytical Summary of Physical & Transport Properties**

The period of 2015-2025 has been characterized by a strong push to generate new, high-quality experimental data for density and viscosity, particularly for promising blended and concentrated amine systems.

> **Key Insight:** A significant trend is the increasing use of **Machine Learning (ML) and Artificial Intelligence (AI)** to develop predictive correlations for complex transport properties like viscosity. Traditional semi-empirical models (e.g., Redlich-Kister) are still prevalent, but for multi-parameter systems (blends, varying T, P, loading), ML models are proving to be powerful tools for interpolation and prediction.

**Identified Trends and Gaps:**
1.  **Viscosity is a Major Focus:** The majority of transport property research is dedicated to viscosity, reflecting its critical impact on operational costs (pumping) and mass transfer efficiency. The general observation that viscosity increases with CO₂ loading and decreases with temperature is consistently confirmed.
2.  **Diffusivity Remains a Challenge:** Direct experimental measurement of CO₂ diffusivity in reactive solutions remains difficult. Consequently, modeling relies heavily on indirect methods like the N₂O analogy and computational methods like Molecular Dynamics (MD) simulations.
3.  **Data Scarcity for Thermal Conductivity:** Compared to density and viscosity, there is a relative scarcity of new experimental data and models for thermal conductivity. This represents a significant data gap, given its importance for the design of heat exchangers, which are major capital cost components in a capture plant.
4.  **Model Diversity:** A wide array of models are used, from fundamental theory (Eyring's viscosity model) to semi-empirical polynomials (Redlich-Kister) and purely data-driven approaches (AI/ML). This reflects a pragmatic approach where the best tool is chosen for the specific system and available data.

---

## **2.5 Enthalpy and Heat Capacity**

### **2.5.1 Analytical Context**

The thermal properties of the amine solvent are arguably the most critical factors influencing the overall economic viability of CO₂ capture technology.
-   **Heat of Absorption (ΔH_abs):** This is the heat released during the exothermic absorption of CO₂. A lower heat of absorption is generally desirable, as the heat required for solvent regeneration (stripping) is closely related to it. ΔH_abs is a key component in the energy balance of both the absorber and the stripper.
-   **Heat Capacity (C_p):** This property determines the "sensible heat" portion of the regeneration energy demand—the energy required to heat the solvent from the absorber temperature to the stripper temperature. A lower solvent heat capacity reduces this energy penalty.

Accurate data and models for both ΔH_abs and C_p are therefore essential for estimating the regeneration energy, which is the largest operating cost in most amine-based capture processes.

### **2.5.2 Heat of Absorption (ΔH_abs) and Heat Capacity (C_p) Data**

The following tables compile recent findings on the heat of absorption and heat capacity of various CO₂-amine systems.

**Table 2.5.1: Heat of Absorption (ΔH_abs) Data and Correlations (2015-2025)**

| Amine System(s) | ΔH_abs Value / Correlation | Conditions & Dependencies | Methodology / Notes | Source(s) |
| :--- | :--- | :--- | :--- | :--- |
| **MEA (30 wt%)** | New experimental data measured. Weak T dependence found (lower than previous reports). Data at 80°C & 120°C were 5% & 10% lower than older findings. | 30 wt% at T=40, 80, 120°C. Data also for 10 & 70 wt% at 120°C. Differential in loading. | Measured using a reaction calorimeter. Data used to develop Extended UNIQUAC model. | *AX19P-search* |
| **MEA & MDEA** | Temperature-dependent correlations for deprotonation, carbamate formation, and overall ΔH_abs calculated. | Calculated for use in UNIQUAC and NRTL models. | Theoretical study using computational chemistry and the Gibbs-Helmholtz equation. | *RZBL7-search*, *2Z2HW-search* |
| **MDEA (50 wt%)** | ΔH_abs = -80 kJ/mol CO₂ | At initial absorption, 40°C, 12 kPa P_CO₂. | Data used in a model to predict CO₂ capacity and enthalpy. | *RZBL7-search* |
| **MEA + Additives (MEG, Urea)** | MEG increased ΔH_abs at 40°C, decreased it at 120°C. Urea lowered ΔH_abs at both temps. | 30 wt% MEA at 40°C and 120°C. | Experimental measurement using a Setaram C-80 Calorimeter. | *AX19P-search*, *2Z2HW-search* |
| **Phase Change Solvent (AEP-DPA)** | Reduced absorption heat by >35% and regeneration heat by >31% compared to MEA. | Reaction heat increases with concentration, decreases with pressure. | Experimental quantification of reaction heat. | *RZBL7-search* |
| **Phase Change Solvents (DEEA, MAPA)** | ΔH_abs increases with temperature. Depends on CO₂ loading, T, and amine composition. | Isothermal measurements from 40-120°C. | Compared with 30 mass% MEA baseline. | *029MV-search* |
| **Piperazine (PZ)** | Temperature-dependent correlations for equilibrium constants and ΔH_abs developed. | Applicable in 273.15–373 K range. | Computational chemistry (DFT) calculations. | *029MV-search* |
| **Blended Amine Solvent** | CO₂ absorption heat of 72 kJ/mol. | A 2017 study cited this value. | Calorimetry for a blended amine. | *RZBL7-search* |
| **1-methylpiperazine (1MPZ) + H₂O** | Excess enthalpy (Hᴱ) data obtained alongside CO₂ solubility measurements. | T and concentration dependent. | Calorimetry measurements. | *RZBL7-search* |

**Table 2.5.2: Heat Capacity (C_p) Data and Models (2015-2025)**

| Amine System(s) | Model / Correlation | Data & Validity Range | Source(s) |
| :--- | :--- | :--- | :--- |
| **MEA, DEA, TEA, MDEA, DMAE, PZ** | Empirical equations fitted to isobaric heat capacities. | New experimental C_p data at pressures up to 25 MPa. Fits C_p as a function of T and P. | *RZBL7-search* |
| **1-methylpiperazine (1MPZ) + H₂O** | Electrolyte NRTL (eNRTL) model. | eNRTL model used to simultaneously represent vapor pressure and heat capacity data. | *RZBL7-search* |
| **N-(2-Hydroxyethyl) piperazine (HEPZ) + H₂O** | eNRTL model and specific correlations. | The dependence of C_p on temperature is expressed through specific functional forms for model development. | *XIF58-search*, *W9H4U-search* |
| **Hybrid Solvent (MDEA-[TBPA][TFA])** | Response Surface Methodology (RSM) and COSMO-RS. | Optimized solvent ratio achieved a 26% reduction in heat capacity compared to standard MDEA. | *XIF58-search* |

### **2.5.3 Analytical Summary of Thermal Properties**

The focus of thermal property research is overwhelmingly on reducing the energy penalty of solvent regeneration, which is directly tied to the heat of absorption and the sensible heat (governed by heat capacity).

> **Key Insight:** A major theme is the exploration of **novel solvent systems** to lower the heat of absorption. Phase-change solvents (like AEP-DPA) and optimized blends are showing significant promise, with reported reductions in regeneration heat of over 30% compared to the MEA benchmark.

**Identified Trends:**
1.  **Differential Calorimetry:** There is a move towards experimental techniques that measure the heat of absorption *differentially* with respect to temperature and *semi-differentially* with respect to loading. This provides much richer data for model validation compared to single-point, integral heat of reaction measurements.
2.  **Computational Chemistry as a Predictive Tool:** Quantum mechanical calculations (DFT) combined with thermodynamic relations (Gibbs-Helmholtz) are being used to *predict* temperature-dependent heats of reaction for individual reaction steps (e.g., carbamate formation, deprotonation). These theoretical values can then be fed into macroscopic thermodynamic models like e-NRTL.
3.  **Heat Capacity Optimization:** While ΔH_abs gets more attention, studies are now also explicitly targeting the reduction of solvent heat capacity (C_p). The use of optimization methods like RSM to design hybrid solvents with lower C_p is an innovative approach to reducing the sensible heat portion of the regeneration duty.
4.  **Robust Modeling:** Thermodynamic models (e.g., e-NRTL, Extended UNIQUAC) are increasingly expected to represent both VLE and thermal properties (ΔH_abs, C_p) simultaneously and consistently. This ensures that the model used for process simulation accurately captures the plant's energy balance.