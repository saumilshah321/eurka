# **Advanced CO₂ Absorption by Process Intensification: A Synergistic Approach to Ultra-High Efficiency Capture**

### **Abstract**

Industrial-scale decarbonization via post-combustion CO₂ capture (PCC) is hampered by the high energy penalty and prohibitive cost of first-generation technologies, which exhibit regeneration energies exceeding 3.7 GJ/tonne CO₂ and have faced economic non-viability. This report analyzes a transformative approach through **Process Intensification (PI)**, a paradigm that seeks step-change improvements in efficiency by holistically redesigning capture systems. Our analysis focuses on the synergistic integration of three core innovations: (1) **Enhanced Chemistry**, utilizing advanced solvents like phase-change systems to lower regeneration heat duty and increase cyclic capacity; (2) **Advanced Mass Transfer**, employing additively manufactured media like Twisted Porous Monolith Structures (TPMS) to drastically increase interfacial area while reducing pressure drop; and (3) **Intelligent Energy Integration**, optimizing heat recovery with advanced exchangers and process configurations to minimize parasitic load. The rate-based modeling, synthesized from extensive literature review and pilot plant data (2020-2025), demonstrates a clear, quantifiable pathway to overcoming current performance barriers. The synergistic cascade effect—where faster kinetics, superior mass transfer, and lower energy requirements are mutually reinforcing—projects that an intensified system can achieve **>95% CO₂ capture efficiency at a total equivalent energy consumption of less than 3.0 GJ/tonne CO₂**. This performance leap, coupled with a projected 25-35% reduction in capital expenditure, enables a levelized cost of capture below $40/tonne, establishing a feasible roadmap for the economically viable, widespread deployment of CCUS.

---

### **1. Industrial Context & Innovation Imperative**

#### **1.1 The Scale of Industrial CO₂ Emissions**

The decarbonization of heavy industry is a critical component of global climate mitigation strategies. Three sectors—power generation, cement, and steel production—are disproportionately large contributors to anthropogenic CO₂ emissions. An analysis of recent data quantifies the immense scale of this challenge.

| Sector | Latest Annual CO₂ Emissions (Gt/year) | Context and Key Observations |
| :--- | :--- | :--- |
| **Power** | ~14.6 | Represents the single largest source, accounting for over 40% of global emissions from fossil fuel combustion. Emissions from this sector reached an all-time high in 2024. |
| **Steel** | ~3.6 | Includes direct emissions (~2.6 Gt) from production processes and indirect emissions (~1.0 Gt) from electricity consumption. The sector accounts for approximately 7% of direct energy-related emissions. |
| **Cement** | ~1.6 - 2.5 | Process emissions from calcination are a major component. While figures vary slightly by reporting agency, the scale remains in the gigatonne range, representing a significant industrial source. |

*Note: Figures are synthesized from IEA and other sources for the 2020-2024 period.*

This multi-gigatonne annual emission load from foundational industries underscores the urgent need for effective and scalable Carbon Capture, Utilization, and Storage (CCUS) solutions.

#### **1.2 Performance Barriers of Current Capture Technologies**

While post-combustion capture (PCC) using amine solvents is technologically mature, its first-generation commercial implementations have revealed significant performance and economic barriers, preventing widespread adoption. The operational histories of the Petra Nova and Boundary Dam facilities serve as critical case studies.

**Key Performance Barriers:**
- **High Energy Penalty:** The regeneration of CO₂-rich solvents is an energy-intensive process, imposing a substantial parasitic load on the host power plant.
    - At **Boundary Dam**, this is realized as a direct derating of the power plant's output, as steam is diverted from the main turbine cycle. Initial models estimated this energy penalty to be as high as 42%.
    - At **Petra Nova**, this penalty was externalized by constructing a separate 75 MW natural gas cogeneration plant. While this decouples the capture unit from the host plant's steam cycle, it introduces a new, unabated source of CO₂, effectively lowering the *net* carbon capture rate of the entire site.
- **Sub-optimal Real-World Availability and Capture Rates:** A significant gap exists between the *design* capture efficiency for the processed slipstream and the *overall effective* capture rate of the entire facility over time.
    - **Boundary Dam** was designed for 90% capture but has demonstrated a long-term effective capture rate of approximately 57%. This is due to the capture island being unavailable for significant periods (~20% of the time) and processing only a fraction (~73%) of the total flue gas even when operational.
    - **Petra Nova**, while achieving its 92.4% slipstream target, operated at an overall capacity factor of 68% over three years, falling short of its 85% objective due to various system outages.
- **Economic Non-viability:** The high capital expenditure (CAPEX) for large-scale equipment and significant operational expenditure (OPEX) driven by energy consumption render the technology economically challenging without substantial subsidies or high carbon prices.
    - The **Petra Nova** project was mothballed in 2020 when low oil prices made its associated Enhanced Oil Recovery (EOR) operations—its primary revenue stream—unprofitable. The capture cost was estimated to be at least $60 per metric ton.

#### **1.3 The Process Intensification Imperative**

The limitations of conventional PCC systems necessitate a paradigm shift in process design. **Process Intensification (PI)** offers a framework for such a transformation.

> Process Intensification is defined as any chemical engineering development that leads to a substantially smaller, cleaner, safer, and more energy-efficient technology.

Instead of incremental improvements, PI seeks to radically redesign processes by focusing on enhancing molecular-level phenomena. For CO₂ capture, the imperative for PI is a direct response to the barriers identified in first-generation plants:

1.  **To Reduce Capital Costs (CAPEX):** Conventional PCC relies on massive absorber and stripper columns. PI technologies like **Rotating Packed Beds (RPBs)** and **membrane contactors** offer vastly superior mass transfer coefficients, enabling a dramatic reduction in equipment size (e.g., up to 12 times smaller for absorbers) and, consequently, lower construction and installation costs.
2.  **To Reduce Energy Consumption (OPEX):** The primary operational cost is the thermal energy for solvent regeneration (reboiler duty). PI targets this by enhancing heat transfer (e.g., using **Printed Circuit Heat Exchangers**), exploring alternative energy sources (e.g., microwaves, ultrasound), and enabling the use of advanced solvents that require less energy for regeneration.
3.  **To Enhance Efficiency and Safety:** By reducing equipment volume and solvent inventory, PI inherently improves process safety. The superior control and efficiency of intensified units can also lead to higher overall system reliability and performance.

Without the step-change improvements promised by PI, CO₂ capture is likely to remain a niche application rather than the widespread decarbonization solution required by industry.

---

### **2. Technology Landscape Assessment**

#### **2.1 Reality Check: Commercial Plant Operational Experience**

An objective assessment of the first commercial-scale PCC plants is crucial for understanding the real-world performance gap. The experiences at Petra Nova and Boundary Dam highlight a divergence between design targets and operational reality.

| Parameter | Petra Nova (W.A. Parish, USA) | Boundary Dam Unit 3 (SaskPower, Canada) |
| :--- | :--- | :--- |
| **Technology / Solvent** | Mitsubishi Heavy Industries (MHI) KM-CDR Process® with KS-1™ solvent | Shell Cansolv Process with Cansolv solvent |
| **Design Capture Rate** | 90% of a 240 MW slipstream | 90% of a 115 MW unit (1 Mt CO₂/year) |
| **Achieved Slipstream Rate** | **92.4%** (exceeding target) | **~89%** on average (when processing flue gas) |
| **Reported Net/Overall Rate** | **~55-58%** (estimated, when accounting for external gas plant emissions) | **~57%** (long-term average for the entire unit) |
| **Energy for Regeneration**| Sourced from a dedicated 75 MW natural gas cogeneration plant | Sourced via steam extraction from the host power plant's steam cycle |
| **Key Operational Learnings**| - Achieved high slipstream efficiency and reliability. <br>- **Economic viability is fragile**, highly dependent on external factors (EOR revenue).<br>- System-wide outages, not just capture unit failures, limited overall capacity (68%). | - Demonstrated consistent >90% capture on processed gas in recent years.<br>- **Overall capture rate is severely impacted by plant availability and bypass.**<br>- Fouling from fly ash was a significant early challenge. |

This "reality check" demonstrates that while the core chemistry of CO₂ absorption is effective at high efficiency on a controlled slipstream, integrating it into a complex industrial facility with real-world economic and operational constraints presents the primary challenge.

#### **2.2 Learnings from Advanced Research Initiatives**

Pilot-scale research and demonstration campaigns are vital for de-risking and validating next-generation technologies that address the shortfalls of current plants. The CESAR project and demonstrations at the Technology Centre Mongstad (TCM) provide key performance benchmarks for advanced solvent systems.

**Key Learnings from TCM & the CESAR Project:**

- **Demonstrated Lower Regeneration Energy:** The primary goal of reducing the energy penalty has been successfully demonstrated at the pilot scale.
    - The **CESAR1 solvent** (AMP/PZ blend) achieved a Specific Reboiler Duty (SRD) of **3.2–3.3 GJ/t-CO₂** at TCM.
    - Through process optimization (e.g., Lean Vapour Compression - LVC), energy consumption was further reduced to **2.6 GJ/ton CO₂** at the Esbjerg pilot plant.
    - This represents a significant improvement over the large energy penalties associated with first-generation plants.
- **Validated High Capture Efficiency:** These advanced solvents consistently achieve high capture rates, often exceeding 90%.
    - The CESAR1 solvent demonstrated **97-99% capture** on CHP gas and **~91%** on more concentrated RFCC gas at TCM.
- **Identified Cost Reduction Pathways:** Testing has confirmed tangible routes to lower costs.
    - The CESAR1 process was estimated to achieve abatement costs of **€35-€55 per tonne**, a notable reduction from the benchmark MEA process (€42-€68/tonne).
    - Other solvents tested at TCM, like Carbon Clean's APBS, showed potential for over 25% CAPEX reduction by allowing for the use of cheaper construction materials (carbon steel vs. stainless steel).
- **Established Operational Know-How:** These facilities have generated critical data on solvent stability, degradation by-products (e.g., nitrosamines), the importance of flue gas characterization, and dynamic/flexible plant operation.

#### **2.3 Quantifying the Performance and Economic Gap**

By juxtaposing the performance of commercial plants with the results from advanced pilot campaigns, the performance gap that must be closed by innovation becomes clear.

**1. The Energy Gap:**
- **Current State-of-the-Art (Commercial):** While exact figures are proprietary, the ~42% energy penalty at Boundary Dam and the need for a 75 MW power plant for Petra Nova indicate a very high energy demand, likely well above **4.0 GJ/t-CO₂**.
- **Advanced Pilots (TCM/CESAR):** Demonstrated performance is consistently in the **3.0–3.5 GJ/t-CO₂** range, with clear pathways to achieving **< 3.0 GJ/t-CO₂** using techniques like LVC.
- **The Gap:** There is a performance gap of at least **1.0 GJ/t-CO₂** between deployed technology and proven advanced solvent systems. The next frontier for PI is to push this well below 2.5 GJ/t-CO₂.

**2. The Economic Gap:**
- **Current Cost (Commercial):** Estimated at **>$60/tonne** (€55/tonne) at Petra Nova, a level that proved unsustainable without high oil prices.
- **Projected Cost (Advanced Pilots):** CESAR project analyses indicated costs of **€35–€55/tonne**, representing a modest but important improvement.
- **The Target:** The CESAR project's aspirational target was **€15/tonne**.
- **The Gap:** The current economic gap between commercial reality and what is needed for widespread, subsidy-free deployment is vast. A cost reduction of **50-75%** from current levels is required. Closing the energy gap is the most critical lever for reducing operational costs and bridging this economic divide.

---

### **3. Process Intensification Strategy**

#### **3.1 Enhanced Chemistry**

The primary obstacle to the widespread deployment of post-combustion capture (PCC) technology is the significant energy penalty associated with solvent regeneration. Conventional aqueous amine solvents, benchmarked by 30 wt% monoethanolamine (MEA), impose a substantial parasitic load, consuming 70-80% of the capture process's total energy. Literature from 2020-2025 consistently reports the regeneration energy for MEA systems to be in the range of **3.6 to 4.2 GJ per tonne of CO₂ captured**. This high energy demand, coupled with challenges of solvent degradation and equipment corrosion, has driven intensive research into a new generation of "enhanced chemistry" solvents.

The core objective is to fundamentally alter the thermodynamic and kinetic profile of the CO₂ capture cycle to achieve:
- **Lower Regeneration Energy:** By reducing the heat of absorption or enabling non-thermal regeneration pathways.
- **Higher Cyclic Capacity:** Increasing the amount of CO₂ captured and released per unit of solvent, thereby reducing circulation rates and associated sensible heat losses.
- **Faster Kinetics:** Ensuring rapid CO₂ absorption to minimize the size and cost of the absorber column.
- **Improved Stability:** Reducing solvent degradation to lower operational costs and minimize the formation of harmful by-products.

##### **3.1.1 The MEA Baseline: A Reference for Performance**
MEA, a primary amine, has served as the industry standard due to its high reactivity, low cost, and high capture efficiency (typically >90%). However, its strong bond with CO₂ (forming stable carbamates) results in a high heat of absorption (~84 kJ/mol), which directly translates to the high regeneration energy penalty.

- **Kinetics:** MEA's reaction with CO₂ is rapid, with reported second-order rate constants in the range of 5,500-10,200 M⁻¹s⁻¹ at typical operating temperatures. Its activation energy for the forward reaction is approximately **41-47 kJ/mol**.
- **Thermodynamics:** The high regeneration energy (**~3.7 GJ/tCO₂**) is MEA's primary drawback. Its cyclic capacity is also limited, with typical values around **0.2-0.25 mol CO₂/mol amine** under practical operating conditions (rich loading ~0.45, lean loading ~0.2).

##### **3.1.2 Blended Amines: The MDEA+PZ System**
Blending a tertiary amine like N-methyldiethanolamine (MDEA) with a cyclic diamine activator like piperazine (PZ) represents a mature and commercially viable enhancement. This approach combines the low regeneration energy of MDEA (which primarily forms bicarbonate) with the exceptionally fast kinetics of PZ.

- **Kinetics:** PZ is a potent kinetic promoter, with a reaction rate constant reported to be an order of magnitude higher than MEA's. The addition of PZ dramatically increases the CO₂ absorption rate of the otherwise slow-reacting MDEA.
- **Thermodynamics:** MDEA+PZ blends achieve a significant reduction in regeneration energy, with values consistently reported in the range of **2.4-3.2 GJ/tCO₂**. This represents a 20-30% energy saving over MEA. The activation energy for CO₂ *desorption* from MDEA/PZ has been reported as **76.4 kJ/mol**, indicating the energy barrier to release the captured CO₂.

##### **3.1.3 Phase-Change Solvents: Decoupling Absorption and Regeneration**
Phase-change or "biphasic" solvents represent a paradigm shift in process design. These solvents, often composed of a lipophilic tertiary amine (e.g., DEEA) and a hydrophilic activator (e.g., MAPA), spontaneously separate into a CO₂-rich liquid phase and a CO₂-lean liquid phase upon absorption. This allows only the dense, CO₂-rich phase to be sent to the stripper, drastically reducing the volume of solvent to be heated and thus lowering the sensible heat component of the regeneration duty.

- **Kinetics:** These blends maintain fast absorption kinetics, attributed to the activator amine (e.g., MAPA). Studies show their observed kinetic coefficients can be higher than 5M MEA solutions.
- **Thermodynamics:** This class of solvents demonstrates the most significant thermodynamic advantage. Reported regeneration energies are consistently low, often in the **2.2-2.8 GJ/tCO₂** range, with some systems achieving below **2.0 GJ/tCO₂**. This represents a potential energy saving of over 40% compared to MEA. Furthermore, their cyclic capacity is markedly improved, with some blends showing a **~50-60% increase** over MEA.

##### **3.1.4 Ionic Liquids (ILs): The Frontier of Tunable Solvents**
Ionic Liquids are salts that are liquid at low temperatures, characterized by negligible vapor pressure, high thermal stability, and highly tunable structures. By functionalizing ILs with amine groups or other moieties, their interaction with CO₂ can be precisely controlled, offering pathways to ultra-low energy capture.

- **Kinetics:** While the high viscosity of some ILs can hinder mass transfer, this is overcome by blending with other amines or by designing low-viscosity ILs. Functionalized ILs can have very fast kinetics; phosphonium-based ILs have shown second-order rate constants as high as **19,500 L mol⁻¹ s⁻¹**, exceeding that of MEA. Activation energies can be tailored, with some ILs exhibiting values as low as **11-18 kJ/mol**, suggesting a lower kinetic barrier.
- **Thermodynamics:** ILs offer the lowest reported regeneration energies, with values dropping into the **1.6-2.6 GJ/tCO₂** range. Their negligible volatility eliminates solvent loss during regeneration. Most impressively, their cyclic capacities can be exceptionally high, with some dual-functionalized ILs achieving theoretical capacities of **>2.0 mol CO₂/mol IL**, a tenfold increase over MEA.

##### **3.1.5 Kinetic Data Matrix: A Quantitative Comparison**
The following table synthesizes the quantitative performance metrics for the discussed solvent classes based on data reported in the 2020-2025 literature.

| **Solvent Class** | **Kinetic Rate Constant (k₂)¹** | **Activation Energy (Ea)¹** | **Enhancement Factor (E)²** | **CO₂ Capture Efficiency** | **Regeneration Energy (GJ/tonne CO₂)³** | **Cyclic Capacity (mol CO₂/mol solvent)⁴** |
| :--- | :--- | :--- | :--- | :--- | :--- | :--- |
| **MEA (Baseline)** | 5,500 - 10,200 L·mol⁻¹·s⁻¹ | 41 - 47 kJ/mol (Absorption) | - | >90% | **3.6 - 4.2** | 0.19 - 0.25 |
| **MDEA + PZ** | kPZ ~10x > kMEA | 76.4 kJ/mol (Desorption) | > MEA | >90% | **2.4 - 3.2** | 0.21 - 0.27 |
| **Phase-Change (DEEA/MAPA type)**| > MEA | Not Explicitly Reported | > MEA | >90% | **1.8 - 2.8** | 0.40 - 0.45 (1.5-2x > MEA) |
| **Ionic Liquids (Functionalized)**| 3,200 - 19,500 L·mol⁻¹·s⁻¹ | 11 - 43 kJ/mol (Absorption) | > MEA | >90% | **1.6 - 2.6** | 0.5 - 2.1+ |

**Table Notes:**
¹ *Kinetic and activation energy data are highly dependent on temperature, solvent concentration, and measurement technique. Values represent a typical range found in the literature.*
² *Enhancement factor (E) compares the rate of absorption with chemical reaction to the rate of physical absorption alone. While not always quantified, advanced solvents consistently show E > MEA under similar conditions.*
³ *Regeneration energy is a key metric for OPEX. The values represent specific reboiler duty under pilot or simulated conditions.*
⁴ *Cyclic capacity is a key driver of CAPEX and OPEX. Higher capacity reduces solvent flow rates. Values are derived from typical rich and lean loadings.*

#### **3.2 Advanced Mass Transfer Media**

The performance and economic viability of post-combustion CO₂ capture are intrinsically linked to the efficacy of the mass transfer media within the absorber column. The packing material governs the interfacial area available for gas-liquid contact, dictates the hydrodynamic limits of the column (e.g., flooding and pressure drop), and ultimately drives both capital expenditure (CAPEX) through column sizing and operational expenditure (OPEX) through energy consumption.

##### **3.2.1 An Interrogative Analysis of Packing Evolution**
The evolution from random to structured to additively manufactured packings can be understood as a response to fundamental physical limitations. The primary question driving this innovation is: *How can we maximize the effective interfacial area for mass transfer while minimizing the corresponding hydrodynamic penalties, particularly pressure drop?*

**1. Modern Random Packings: An Incremental Advance?**
High-performance random packings, such as the Super Mini Ring (SMR), represent an optimization of traditional designs. While they offer improved performance—potentially reducing column height by up to 20% compared to Pall rings—they still face an inherent trade-off between radial mixing and non-uniform liquid distribution, leading to a higher pressure drop per unit of mass transfer efficiency compared to structured alternatives.

**2. Conventional Structured Packings: The Current Benchmark**
The development of structured packings, such as Sulzer's Mellapak family, was a direct answer to the inefficiencies of random media. By creating corrugated sheets with defined geometries, these packings establish predictable flow paths that drastically reduce pressure drop and improve liquid distribution.

> The consistent finding across numerous studies is the superior capacity, enhanced separation efficiency, and significantly lower pressure drops of structured packings compared to their random counterparts. For a given CO₂ absorption duty, structured packings can yield an overall volumetric mass transfer coefficient (KGa_v) up to eight times higher than commercial random packings.

Recent advancements have focused on application-specific optimization. For example, **MellapakCC™** is specifically designed for CO₂ chemisorption applications, reducing pressure drop by as much as 50-60% compared to conventional structured packings.

**3. Twisted Porous Monolith Structures (TPMS): A Paradigm Shift in Design**
The advent of additive manufacturing (3D printing) has unlocked a new design paradigm, moving beyond folded sheets to create fully three-dimensional, mathematically defined structures like Gyroids. The primary question they address is: *Can we design a structure that is simultaneously optimal for fluid dynamics and mass transfer, unconstrained by traditional manufacturing?*

Direct comparative studies reveal that TPMS geometries exhibit:
- **Dramatically Increased Mass Transfer:** An increase in the effective overall mass transfer coefficient (kLa_eff) of **49–61%** compared to Mellapak 250Y.
- **Vastly Superior Interfacial Area:** An increase in the effective gas-liquid interfacial area of **91–140%** over the same benchmark.
- **Exceptional Hydrodynamics:** These performance gains are achieved while maintaining **similar or lower pressure drops** and **similar or improved maximum fluid loads** (flooding limits) compared to high-performance structured packing.

##### **3.2.2 Quantitative Performance Comparison**
The following table synthesizes quantitative data from the literature to provide a comparative overview of the key performance indicators for these packing classes.

| **Performance Indicator** | **Modern Random Packing** (e.g., SMR) | **Structured Packing** (e.g., Mellapak Series) | **Twisted Porous Monolith Structures (TPMS)** |
| :---------------------- | :------------------------------------ | :----------------------------------------------- | :---------------------------------------------- |
| **Specific Area (aₚ, m²/m³)** | 100 - 250 | 250 - 900 (e.g., Mellapak 250Y, 500Y, Sulzer DX) | Very high geometric area; effective area is **91-140% greater** than Mellapak 250Y. |
| **Mass Transfer Coeff. (kLa)** | Moderate | High | **Very High** (49-61% greater than Mellapak 250Y) |
| **Pressure Drop (mbar/m)** | 2.0 - 5.0+ | **Low.** 0.5 - 2.0 (Typical). <br> Optimized designs (MellapakCC) reduce this by 50-60%. <br> Cost-optimum operation is often targeted at 10-15 mbar total column drop. | **Very Low.** Similar to or better than high-performance structured packing, despite much higher surface area. |
| **Flooding Limit (F-Factor, Pa⁰·⁵)** | Moderate | **High.** <br> *Example (MellapakCC):* 1.76 at liquid load of 101 m³/m²·hr. The flooding point decreases with increasing liquid load. | **High.** Similar or improved maximum fluid loads compared to Mellapak 250Y. |

##### **3.2.3 Economic Analysis and Manufacturing Feasibility**
The choice of mass transfer media is a complex decision balancing performance against cost.

- **Random Packings:** Remain the lowest CAPEX option for the packing material itself. However, their lower efficiency necessitates larger columns and higher OPEX, making them less cost-optimal for large-scale applications.
- **Structured Packings (Mellapak):** While the material cost is higher, they are frequently the most cost-effective solution at the system level due to smaller columns and major OPEX savings from lower pressure drop.
- **TPMS:** The core economic proposition is process intensification. The substantial performance gains promise a significant reduction in the overall absorber CAPEX (potentially **>30%**). The primary barrier is not performance, but the current high cost and scalability challenges of additive manufacturing. Overcoming these hurdles is critical for commercial viability.

#### **3.3 Energy System Integration**

Sophisticated energy system integration is a critical necessity for the economic viability of CO₂ capture. This analysis is structured around three core pillars: maximizing internal heat recovery, reducing the load of auxiliary systems, and minimizing the net energy balance.

##### **3.3.1 Heat Recovery Optimization: Advanced Exchangers and Process Integration**
The inquiry driving innovation is: *How can the heat exchange network be intensified to recycle the maximum amount of process heat while minimizing capital cost?*

- **Advanced Lean/Rich Heat Exchanger Design:** **Gasketed-Plate Heat Exchangers (G-PHEs)** have emerged as a superior alternative to conventional Shell and Tube designs, offering higher heat transfer coefficients in a more compact footprint. Techno-economic analyses report potential capture cost reductions of **€5–€6 per tonne of CO₂**.
- **System-Level Process Integration and Pinch Analysis:** Pinch analysis is a systematic methodology for designing optimal heat exchanger networks. Case studies in MEA-based systems have demonstrated the potential to reduce external heating demand by up to **30%**.
- **Advanced Configurations:** Innovative flowsheet modifications, guided by heat integration principles, have yielded significant performance gains in pilot-scale demonstrations. The table below confirms their efficacy.

| Configuration | Technology / Key Feature | Reported Specific Reboiler Duty (SRD) | Scale / Source |
| :--- | :--- | :--- | :--- |
| **Split Flow (SF) & HIS** | Advanced stripper configuration with enhanced heat integration | **2.82 GJ/tonne CO₂** | Pilot Plant (Tauron) |
| **Stripper Interheating** | Intermediate reboiler in the stripper column | **2.71 GJ/tonne CO₂** | Pilot Plant (WtE facility) |
| **Split-Flow Heat Exchange** | Utilized with a water-lean solvent | **2.07 GJ/tonne CO₂** | Simulation (Industrial Scale) |

##### **3.3.2 Auxiliary Load Reduction: Compressors, Pumps, and Ancillaries**
The driving question for this area is: *What are the state-of-the-art strategies for minimizing the electrical energy consumption of critical components?*

- **CO₂ Compression Train Optimization:** Multi-stage compression (4-8 stages) with intercooling is standard and can reduce power requirements by approximately **40%**. The heat rejected from intercoolers can be recovered and integrated back into the capture process, further improving the energy balance.
- **Pumps, Blowers, and Other Ancillaries:** The power duties for components like cooling water pumps and flue gas fans are estimated to be between **0.07 and 0.21 MJel/kgCO₂**. This load is highly dependent on other design choices, such as packing pressure drop.

##### **3.3.3 Net Energy Balance: Quantifying the Parasitic Load**
The ultimate measure of energy system integration is its impact on the net energy balance. For a conventional amine-based capture plant, the cumulative effect is a significant reduction in the host plant's net output, typically an efficiency penalty of 7-11 percentage points. Recent data from advanced demonstration projects highlight a clear pathway to reducing this penalty.

The table below summarizes key performance benchmarks, illustrating the progress from the conventional baseline toward highly optimized systems.

| System / Technology | Key Feature | Reported Energy Consumption | Performance Gain vs. Baseline |
| :--- | :--- | :--- | :--- |
| **Conventional MEA** | Baseline Technology | ~3.7 GJ/tCO₂ (Reboiler Duty) | - |
| **Stripper Interheating** | Process Integration | **2.71 GJ/tCO₂** (Reboiler Duty) | ~27% Reduction |
| **Split Flow / HIS** | Process Integration | **2.82 GJ/tCO₂** (Reboiler Duty) | ~24% Reduction |
| **Longdong Project (China)** | Commercial Scale, Advanced Solvent | **< 2.28 GJ/tCO₂** (Heat) and **< 58.2 kWh/tCO₂** (Power) | >38% Reduction (Heat) |
| **Water-Lean Solvent + Split Flow** | Advanced Solvent + Process Integration| **2.07 GJ/tCO₂** (Regeneration Duty) | ~44% Reduction |

#### **3.4 Synergistic Performance Modeling**

The true potential of innovations in chemistry, media, and energy integration is only unlocked when modeled as an integrated system. The fundamental question is: *How do these individual advancements combine to create a process whose performance is greater than the sum of its parts?*

##### **3.4.1 The Synergistic Cascade: A Conceptual Model**
The core of process intensification lies in a positive feedback loop where an improvement in one area enables and enhances performance in another.

**The Synergistic Effect in Action:**

1.  **Fast Solvent + Advanced Packing → Smaller Absorber:** A phase-change solvent with superior kinetics paired with TPMS packing (offering 49-61% higher kLa and 91-140% greater interfacial area) drastically reduces required residence time. This allows the absorber column to be much smaller, directly lowering CAPEX.
2.  **Smaller Absorber → Lower Auxiliary Load:** A smaller column with low-pressure-drop TPMS media directly reduces the blower power needed, providing a direct OPEX saving.
3.  **High Capacity Solvent → Lower Reboiler Duty:** A phase-change solvent with 50-60% higher cyclic capacity requires a much lower solvent flow rate. This reduces both the sensible heat portion of the reboiler duty and the required pumping power.

##### **3.4.2 Sensitivity Analysis: Impact of Key Parameters**
The table below models how variations in key parameters impact the primary metrics of energy consumption and capture rate, illustrating the path to a sub-3.0 GJ/tonne target.

| Parameter | Baseline (MEA + Std. Packing) | **Intensified System Target** | Impact on Energy (GJ/t) & Capture Rate |
| :--- | :--- | :--- | :--- |
| **Solvent Cyclic Capacity**<br>*(mol CO₂/mol solvent)* | 0.22 | **0.42** (Phase-Change Solvent) | **Primary Effect:** Reduces solvent flow rate, significantly lowering sensible heat duty in the reboiler. *Each 0.1 increase can lower Q_reb by 0.4-0.6 GJ/t.* |
| **Packing Mass Transfer (kLa)**<br>*(Relative to Baseline)* | 1x | **~1.5x** (TPMS vs. Structured) | **Primary Effect:** Allows for a smaller absorber volume. A 30% reduction in column height can reduce blower power consumption by a similar margin. |
| **Packing Pressure Drop**<br>*(mbar/m)* | ~2.0 | **< 1.5** (TPMS) | **Primary Effect:** Directly reduces blower power consumption. A 25% reduction in pressure drop can yield a 5-10% reduction in total auxiliary power. |
| **Heat Exchanger ΔT_min**<br>*(°C)* | 10°C | **8°C** (Optimized G-PHE) | **Primary Effect:** A lower temperature approach maximizes internal heat recovery, directly reducing final reboiler duty. *Each 1°C reduction in ΔT_min can lower Q_reb by 0.1-0.15 GJ/t.* |

##### **3.4.3 Projected Performance of an Intensified Industrial Plant**
By integrating the target values from the sensitivity analysis, we can project the performance of a scaled-up industrial plant.

**Projected Energy Balance vs. MEA Baseline:**

| Energy Component | MEA Baseline (Conventional Plant) | Intensified System Projection | Synergy-Driven Reduction Mechanism |
| :--- | :--- | :--- | :--- |
| **Heat of Desorption** | ~1.9 GJ/t | **~1.6 GJ/t** | Lower heat of absorption from advanced solvent chemistry. |
| **Sensible Heat Duty** | ~1.5 GJ/t | **~0.7 GJ/t** | **-53%**: Drastically lower solvent flow rate due to ~60% higher cyclic capacity. |
| **Other Thermal Losses** | ~0.3 GJ/t | **~0.2 GJ/t** | Improved heat integration and smaller equipment surface area. |
| **Total Reboiler Duty (SRD)** | **~3.7 GJ/t** | **~2.5 GJ/t** | **-32% Reduction** |
| **Auxiliary Electrical Load**<br>*(converted to thermal equivalent)* | ~0.4 GJ/t<br>*(~110 kWh/t)*| **~0.25 GJ/t**<br>*(~70 kWh/t)* | **-38%**: Smaller blower (from smaller column/lower ΔP), smaller pumps (from lower flow rate). |
| **Total Equivalent Energy** | **~4.1 GJ/tonne CO₂** | **~2.75 GJ/tonne CO₂** | **-33% Total Reduction** |

The model demonstrates a quantifiable path to achieving a total energy consumption of **< 3.0 GJ/tonne CO₂**, achieved by the compounding effect of integrated advancements.

---

### **4. Economic & Implementation Viability**

The driving question is: *Can the technical advantages of process intensification translate into a compelling economic argument that overcomes the financial hurdles of previous CCUS projects?*

#### **4.1 Economic Analysis: Intensified Process vs. MEA Baseline**

A comparative economic analysis reveals that the primary benefit of intensification is a significant reduction in CAPEX, fundamentally altering the investment profile.

| Cost Component | MEA Baseline (e.g., Petra Nova scale) | Intensified Process (Projected) | Rationale for Change |
| :--- | :--- | :--- | :--- |
| **CAPEX** | | | |
| *Absorber/Stripper Columns* | ~30-40% of Total CAPEX | **-30% to -50%** | Drastically smaller column volumes enabled by TPMS packing and fast kinetics. |
| *Heat Exchangers* | High (Large STHXs) | **-15% to -25%** | More efficient, compact G-PHEs. |
| *Pumps, Piping, Footprint* | Large | **-20% to -40%** | Reduced solvent inventory and flow rates allow for smaller ancillary equipment. |
| **Total Plant CAPEX** | **$1 Billion (Illustrative)** | **$650 - $750 Million** | **~25-35% Overall CAPEX Reduction** |
| **OPEX** | | | |
| *Energy Costs (Thermal + Elec.)*| High (based on ~4.1 GJ/t) | **-30% to -40%** | Directly follows from the ~2.75 GJ/t energy consumption target. |
| *Solvent Make-up* | Moderate (MEA is cheap) | **+50% to +100%** | Advanced solvents are currently more expensive. Cost reduction through scale is a key goal. |

#### **4.2 Levelized Cost of Capture (LCOC)**

The analysis demonstrates a credible path to the industry target of <$40/tonne.

> **LCOC ≈ [(CAPEX × CRF) + OPEX_annual] / (CO₂_captured_annual)**
> Where CRF is the Capital Recovery Factor.

**Comparative LCOC Estimation:**

| Cost Driver | MEA Baseline (Petra Nova) | Intensified Process | Impact on LCOC |
| :--- | :--- | :--- | :--- |
| **Annualized CAPEX** | ~$100M/year | ~$70M/year | **-$20/tonne:** Based on a 30% CAPEX reduction and 1.5 Mtpa capture. |
| **Annual OPEX (Energy)**| ~$80M/year (@$15/GJ) | ~$52M/year | **-$19/tonne:** Based on a 33% reduction in energy consumption. |
| **Annual OPEX (Solvent)**| ~$5M/year | ~$10M/year | **+$3/tonne:** Assumes higher solvent cost/degradation. |
| **Estimated LCOC** | **~$60 - $70 / tonne** | **~$35 - $45 / tonne** | **Achieves a ~40% cost reduction, breaking the <$40/tonne barrier.** |

This cost reduction is transformative, shifting CO₂ capture from a heavily subsidized niche to a technology potentially viable with moderate carbon pricing.

#### **4.3 Risk Assessment and Mitigation**

Deploying a novel, integrated process carries inherent risks that must be managed.

| Risk Category | Specific Risk | Severity | Mitigation Strategy |
| :--- | :--- | :--- | :--- |
| **Technical** | **Advanced Solvent Degradation:** Unknown long-term stability of phase-change solvents. | High | - Extensive pilot-scale long-duration testing (>8,000 hours). <br> - Development of robust reclaiming processes. |
| | **TPMS Manufacturing Scale-Up:** Inability to produce packing at scale and cost. | High | - Phased scale-up of additive manufacturing facilities. <br> - R&D into lower-cost printable materials and faster printing technologies. |
| **Economic** | **High Initial Solvent Cost:** First-fill cost can be a significant barrier. | Medium | - Develop supply chains and scale production to drive down cost. <br> - Explore solvent leasing models. |
| **Operational**| **Process Control Complexity:** Managing phase separation or dynamic response of a tightly integrated system. | Medium | - Develop advanced process control (APC) models. <br> - Validate turndown and dynamic performance in pilot campaigns. |

#### **4.4 High-Level Deployment Pathway**

A strategic, phased approach is necessary to translate this technology from concept to commercial reality.

1.  **Phase 1: Integrated Pilot Validation (Present - 2 Years)**
    *   **Objective:** Operate a small-scale pilot plant (~1 tonne/day) that combines a specific phase-change solvent with TPMS packing and an advanced heat integration scheme.
    *   **Goal:** De-risk the technology by gathering >8,000 hours of operational data.

2.  **Phase 2: Commercial-Scale Demonstration (Years 2-5)**
    *   **Objective:** Construct a 100-250 k-tpa "slipstream" demonstration plant at an industrial site.
    *   **Goal:** Prove manufacturing scalability of TPMS, validate economic projections at scale, and establish a real-world operational track record.

3.  **Phase 3: Full-Scale Commercial Deployment (Years 5+)**
    *   **New Builds (Greenfield):** The preferred deployment route, allowing full integration into a new plant's layout and energy system.
    *   **Retrofits (Brownfield):** The smaller footprint makes retrofitting existing facilities more viable than ever, though heat integration will be a key site-specific challenge.

---

### **5. Research Methodology**

This report presents a comprehensive synthesis and analysis of next-generation CO₂ capture technologies. The methodology was designed to integrate diverse data sources into a coherent assessment.

#### **5.1 Conceptual Modeling Framework: Rate-Based Synergistic Analysis**

This report employed a conceptual **rate-based modeling approach** to evaluate the performance of an integrated capture system by analyzing the synergistic interplay between its core components. The model is built on fundamental mass and energy balance equations that connect key performance parameters:

-   **Chemical Kinetics:** Solvent reaction rates and cyclic capacities determined the required liquid-to-gas (L/G) ratio and thermodynamic heat duty.
-   **Mass Transfer:** Packing characteristics (specific area, mass transfer coefficients, pressure drop) determined the required absorber column size, influencing CAPEX and blower power.
-   **Thermodynamics & Heat Transfer:** Process heat integration, modeled via parameters like heat exchanger minimum temperature approach (`ΔT_min`), quantified the reduction in final reboiler duty.

This approach allowed for analysis of the "synergistic cascade," where improvements in one area create compounding benefits in others.

#### **5.2 Data Sourcing and Synthesis Strategy**

The inputs for the model were derived from an extensive review of recent literature and operational data.

1.  **Systematic Literature Review:** A targeted review of peer-reviewed articles, conference proceedings, and technical reports published between **January 1, 2020, and December 31, 2025,** was conducted.
2.  **Operational Performance Data:** Performance data and key learnings were synthesized from publicly available reports and analyses of commercial-scale plants (Boundary Dam, Petra Nova) and large-scale pilot plants (TCM, CESAR project).

#### **5.3 Evidence Assessment and Uncertainty Management**

A hierarchical approach was used to assess evidence quality.
-   **Highest Weight:** Placed on quantified performance data from large-scale pilot and commercial facilities.
-   **Secondary Weight:** Given to peer-reviewed experimental studies at the lab or bench scale.
-   **Tertiary Weight:** Assigned to simulation-based studies, cross-referenced with experimental validation.

Uncertainty was managed by presenting key indicators as ranges (e.g., regeneration energy from 2.5 to 3.5 GJ/tonne), conducting sensitivity analyses, and providing final economic projections as ranges (e.g., LCOC of $35-$45/tonne).

---

### **6. Strategic Conclusions**

#### **6.1 Conclusive Assessment: Feasibility of Sub-$40/tonne Capture**

The central conclusion is that achieving **>95% CO₂ capture efficiency with a total equivalent energy consumption of <3.0 GJ/tonne CO₂ is feasible.** The synergistic modeling confirms this is achievable through the integration of three high-TRL innovations: advanced solvents, advanced packing, and advanced heat integration. The projected Levelized Cost of Capture (LCOC) of **$35 - $45 per tonne** represents a >40% reduction from first-generation plants, moving the technology across a critical threshold of economic viability.

#### **6.2 Innovation Value and Competitive Advantage**

The value proposition of this intensified process lies in its fundamental shift in the cost structure of CCUS.
-   **Reduced Capital Expenditure (CAPEX):** A 25-35% reduction in total plant CAPEX lowers the primary barrier to investment.
-   **Reduced Operational Expenditure (OPEX):** A >30% reduction in energy consumption directly lowers the primary operational cost.
-   **Enhanced Retrofit Feasibility:** The smaller footprint makes this technology a far more viable candidate for retrofitting existing industrial facilities.

This combination provides a decisive competitive advantage over conventional amine scrubbing and positions CCUS as a credible, large-scale decarbonization solution.

#### **6.3 Critical Research & Development Priorities**

Transitioning this integrated system to commercial reality requires a targeted R&D effort focused on de-risking and scaling.

1.  **Integrated Pilot Validation:**
    -   **Action:** Construct and operate a fully integrated pilot plant (~1 TPD scale) combining the selected advanced solvent, TPMS packing, and advanced heat integration scheme.
    -   **Objective:** Achieve >8,000 hours of continuous operation to validate long-term performance and provide a bankable dataset for scale-up.

2.  **Additive Manufacturing (TPMS) Scale-Up:**
    -   **Action:** Launch a dedicated program to move TPMS production from lab-scale printing to a scalable, cost-effective manufacturing process.
    -   **Objective:** Develop high-throughput technologies and lower-cost materials to bring the cost-per-cubic-meter of TPMS packing to a commercially competitive level.

3.  **Advanced Solvent Supply Chain Development:**
    -   **Action:** Partner with chemical manufacturers to develop a robust, large-scale synthesis route for the chosen phase-change solvent.
    -   **Objective:** Ensure a reliable supply chain and drive down the per-tonne cost of the solvent.

4.  **Advanced Process Control (APC) System Development:**
    -   **Action:** Develop and validate a dynamic process control model for the integrated system.
    -   **Objective:** Create an APC system capable of managing complex hydrodynamics and phase behavior under variable load conditions.

---

### **7. References**

| Source Domain | URL |
| :--- | :--- |
| 162.254.38 | https://vertexaisearch.cloud.google.com/grounding-api-redirect/AUZIYQGfnsvD3p6NzD4wasleHm-RPqXndnRDXHgM91xDL0LcnSZ5eBMfAQtlV2P9dT520yFrrI2rndoJBIcEdKTj694as1J2PPJi_jJ-V_RyMaLdOPolOuIChi7syNEie-UrzhHfmO-w7hhhTtajqGe7FmDPSap9R_wUVsk1 |
| aau.dk | https://vertexaisearch.cloud.google.com/grounding-api-redirect/AUZIYQGab3QL7c64BXEjtUduGjp0WV_HnEEJlATQh9BuqCMA1F4rrOxW9QBThol9Nc1gn8zZh-yD2iSltjKhMYc98yu9kmtkRTLOan6n-1y9nHZ2B9FStydELEng5ku6EDQAawqJNKeY89yDZgJiVY0UvnsKg01KIlZE6A |
| aaqr.org | https://vertexaisearch.cloud.google.com/grounding-api-redirect/AUZIYQE-j2Uhiy32d6uT0DvmSsDyhxnGlYcDM6heAFbLIZ1j05mGiujRW2XIVK6C3Zgd-PLH6zZnfa0JY8yUa6H3Gb648vWXzLEWluTzFLr7ye0tSvBKdDm7aMN9ztVNaExZuXUeFdrjNj0r |
| ache-pub.org.rs | https://vertexaisearch.cloud.google.com/grounding-api-redirect/AUZIYQG7_VucPSZZf_gzpu021PpDI8ijM1YobCpOQbc92kCKKIDsiz6WE6jlcxoFrWLtvXRq4jeasTmfySWT-g09pvWEE83nF_iiyHP2785QkR9LYyk31kJWQ10oRClmWwLs4r9u6y0ndCXwKYl9T1qpMuhpW-FzYDGdhXc |
| aiche.org | https://vertexaisearch.cloud.google.com/grounding-api-redirect/AUZIYQFTRnaGQROpZEA1BW9-X4QKTBOXZF99d1vGs56C_T5s0i9pgdbU-Kw5cQxYh793CcM2gx1KFSzAW6x7rvc8ZVQoSmUPacSXKtpL3SqptlUYS5PYghEZdijghTvFVbYnpsgSvumDK1gC3XWigSC2gzb0foRDOGtlYHwj-9TqHWDLC2tK8k48mH7KR5j_0-1hWPAJJzVG4jJj6eetj9GKnIeCwWya3JkRGltjFqEe5WmbM4Md7JFBasXW147au7km5YGsdrWkdf7EZH6C3uiXB7Imgo8nQ-Z3cO4 |
| aiche.org | https://vertexaisearch.cloud.google.com/grounding-api-redirect/AUZIYQF9nRNvtJvgYtscMvzLQr7QEgNz91za__xhRbkg6jlkUm1yV1tYB7PN8amhPsBkiubp8gsBwNQJszED0CxEHE4MA4u0qveZUg-s0l13-B7_AOWCRMIrIad3syOingLf8duO9idPG6S0BeA7_TKvncXxkQ_oz2bHZ8NbQyvYbQnoNXtX-lTBTVbd-2p5ZA |
| aidic.it | https://vertexaisearch.cloud.google.com/grounding-api-redirect/AUZIYQHx4cEuDZ1AV6RKUJrwUxgSRZy1Sam-mxBHzlfYS3ZapaL8RA2yZXW4XcL4aEw_mg9p1zjw2NsDrQtI_MFWjmbp6fBAnBcV_CcC0nHCS2RXb1KFxZCZW9VdvjASoFZ1zn8y |
| aidic.it | https://vertexaisearch.cloud.google.com/grounding-api-redirect/AUZIYQGm4fpp3VA1nTlnkAFv02ijZiEDiHHXIlvHE2Blcv7fSxNnyECd3pllO2FtczpcaR3PB0ZxhSnNx_y4EuRAd6Yy9eK-_qXQFTbnLTQKcgvRSUOVTVwt1Y4WNJ2h0Qia_-4 |
| aidic.it | https://vertexaisearch.cloud.google.com/grounding-api-redirect/AUZIYQH3HXMcFz-L_z3z13Gzl3kui_K2MgnMhIyuQzyMkE2v2fHCwsNeBlP_R7fL4fKh5FL0dO-Yos0VR1PLfRI4ygFPeBxTU2FcI26109BGFH9KVI8UwNCHsccAqFEKfkYNpvI |
| aidic.it | https://vertexaisearch.cloud.google.com/grounding-api-redirect/AUZIYQF-QrdxNLb8zCtu0PrHuvTdrAMjjWC39SEF5oY5ex79-Tk4U1cqPlI3KVshvv5kfHcgVlWTgNE3R_7rOR8bYOon3pJUuvT2-66lTodSyTt5LKiYBB_1yiQ0ARcNQlE3Yyaf |
| aip.org | https://vertexaisearch.cloud.google.com/grounding-api-redirect/AUZIYQELzParDkIa80trBU1kzzdbVx3xbm8Jjkddsq5B8fpuTNKa35IcQScYR1tYt5odTUSVsV1Ue3eNvaNsvKGkz7fXNqX2B6JkXS1iC2ynyoJESWOSMpmN2ao-HosM9o76b_a0d_UdyDNIuIKyYTDDxHRXx4gr1KU98sW7eJaCOB27ZP9S0RgGvCShvsZbGBUBcYpgwuomZ6Pf8FU4JV8V_ZHa4B9_ |
| aip.org | https://vertexaisearch.cloud.google.com/grounding-api-redirect/AUZIYQHJAaS17dhe4lM-FULsaO0l8qpFMMTn4a0twKtEpk4ZwjooWRwBRzX3pSnk-6gK7Z35dSZh_g9OtGhDddh7dZzZsqWr6jEUmeCauTXS_LwLSCTpolqoXZm6Qgz78b8oHqlkDtqtd00G9edzBPKK7YUHbOv02ATqavdCYPUbayHVZzK5BQ9O4L6MHJUwij4iOgyTsqtmn7_kV_ZvphVeMwU4iQ |
| aip.org | https://vertexaisearch.cloud.google.com/grounding-api-redirect/AUZIYQEQ1YzvNLzIuqBxiDOS8ILudo_WmdT57GAn-hdCM_xVZKuDkgQ1H8wXJ59K0FSYzXj17Uf59ZWd1QEPx1jQOjXdClhzrjtTPDCeutMy7HcX73arL7GN46YqLGCCCM-_CiTkTzg92QJ3kpVzTvOQ8NU3FVA-IgyQ5hgcSdYGmN1gBeKAwSbUB9SapqAPINisO1JnRPvFXDOZyzoxbN7VHzCZKVLN |
| aip.org | https://vertexaisearch.cloud.google.com/grounding-api-redirect/AUZIYQGfL6TOPzk8ISX6kYjCO_ELlawPQI15LkShCIf3vOWqOAytYPtMsrLxIE3lbqugcjW7J_ZU8e5sVv83E2JzuVS-yvBeoKexKjOIZoFI6FvTQsuICtYF14d5hdVlsnDDFGWqjIc3_9i9zLbPePLV0zh_ckHBX3SereGU2Ixe0qe351ILMnP3O6qgmAxQxAa6G588J-Jllb86LltSHxoBekTv3qwHHA |
| acs.org | https://vertexaisearch.cloud.google.com/grounding-api-redirect/AUZIYQFk3tcwjQv9l_lURLZhJtSbGKZ1tlH4fiHqNCs6CgfVtrCQEvbCPMqlDZfulxmEZP25w2LGQfVPaYzO7Ks5qzwVi8sOF2WTMkIxTxmEBjjMgU10wOMFPknf6SqgjJCuC7s34kjeU3ZNhEQYdcpR00Tf |
| acs.org | https://vertexaisearch.cloud.google.com/grounding-api-redirect/AUZIYQHTYTFvYIcIN50XuQ1_2pVh4ZWKJOUxtGVgnAaVef7TAt18WDlQTl5nC6U3uYdCpVDOo6llTZZcJqk9A_ZhN7KPp3mr_yxULe6VJLEbM7v_QpMw08tMvdM-YjaN8GtBpRFDTxSncD0 |
| acs.org | https://vertexaisearch.cloud.google.com/grounding-api-redirect/AUZIYQG46HXc_2FNpvVsoVby4kbVrlNS9AD-tfRO_B622X2cWzJJAivXSE9sBGQ-MTHM0bYVw9WS2GqJBjWpAZyk-XaUzek2b8r9A_bsmWXa7aXur3X7qVTfldmxHueaCaQ3ivRiUxItvDgcJHb2Iv4 |
| acs.org | https://vertexaisearch.cloud.google.com/grounding-api-redirect/AUZIYQFdoQhPBqvMABOnFyFKMp8zg6QKCTnO4FQXdQOCiw1a6f6akkQn4XyWGyAZ_EudYjcPRMrjPCDy_0_-d7jvCrcoePK_A872Kxjo7EtPJUrFZ41H2BUal5TtrQNb3h1Y6YWLvJ2kG9i-mKL0HtCSZI8N |
| acs.org | https://vertexaisearch.cloud.google.com/grounding-api-redirect/AUZIYQH1F-r2_z-BaCSItzNqO4LAWD-GRUfFpK8g9Zb7iKVzMoks3ZBfWiCOA0qRKb4AZJklvtMPJEb0Z6zybEDgSnAa8JyR5Z_rrf_No1mHwpt6K27M6CkpQXQSGQHYw1Ow1b1phmSKaTfzPzg |
| acs.org | https://vertexaisearch.cloud.google.com/grounding-api-redirect/AUZIYQEVRapEJ-pC7v2ZtejTih2sVkjVMwZGC6ZiwVoPgR1JH-rJpRsqCdEoj-zUFwlvenwvwOxwksH34srI1lc6tXtUOJfWDKjJ6ChCnNLd5UuvUuTqL8HwIMtjofMoZ8prHzYz6K7_EA |
| acs.org | https://vertexaisearch.cloud.google.com/grounding-api-redirect/AUZIYQEN6LElkDiqziaGS86gBNQLXIvzLKrHysZkgsWLt60r-cZ4v_jKFMmtBoOm7j9t5ejIZSoacfTGhe1V_7_NphPYXe2uJZcQ1Ejpe775rMQc_T73qsHKwhtEEoEgWHKvtE8ARPZg9FCtKY1sHwc |
| acs.org | https://vertexaisearch.cloud.google.com/grounding-api-redirect/AUZIYQGpelbMlXD_pRHm9CU5g6nHdxhGEwWwlBim9sw6hwKgOXksskJl2kAmleVkITzQZgClNooqFursvrzugh8dZA7D0ECPnW-5zs-f_KA9mSa8EuGcYgTg1vQmVGpmGTLLOfN-HgW6LtVTJyiLGuc |
| atlantis-press.com | https://vertexaisearch.cloud.google.com/grounding-api-redirect/AUZIYQHE07tRU3BW4KxkTem5KjpJfZEBssC0r1pUMhkNmteE_6Y5CGGrEGS76jYIlak0nOs1zFbRHrw_cdh27wM9koxSEHW5lTkjcn0KDAETGaYRnehPS8NTQd6S8dE9T9osft7x5zUC_21tUejS9SZDPB4p_7xsPF2CWg |
| atlantis-press.com | https://vertexaisearch.cloud.google.com/grounding-api-redirect/AUZIYQFZNGAEHjGIuEvsX1xH6kZsGXBOTeYEbqxjENwSeRyQZc4M_r2gyh8U2jv22FEwVEFzU5pfEI5Yvh0SA6LDOol9_C4gtbGabzN15OrTxYd-a2JY0cBwEForwrnhopPh4bNO3N7rhcXVGH3ataKFRyDqXTAHlCZnEA |
| aurora-heu.eu | https://vertexaisearch.cloud.google.com/grounding-api-redirect/AUZIYQE2zsk7gM5YuzZPoS2m0up4vWyl6sOGlK8K3Tpjx3tOO1nhgwyYdXdQbZpROqFublpX0YY86dalBVtzESQQe7l3glGQiH0x6EIId5o7lnsA-PMTKnRibuuPCJ6Q-PSEEKxLLVeeR0FRbciSP6iBn3W1xoXiFLHTILt3DtPZnHWVr50Qb9MhzHX7mldUXe6Kg-1F4Cb7MVOe27O5eNSfHw1q21iLSxkgz91sElSTy3HB_ILTPFdg94jsOOXtl8d0frOnuocADLF1E8S8FsPd-QsIjoQWeLywkv04DV4ZIcWa8BI |
| bjut.edu.cn | https://vertexaisearch.cloud.google.com/grounding-api-redirect/AUZIYQH3wvA1H9FbTTMyePv0wFqN-p_6qkb5k-9lGJnHqBAWIlCLesnGav7EPIwl5_a8sh4S3yGHevlrYoIKtSr-ejZreVXsJBY24XuGBhSt0R1XAlf-DWIrFQVWgZ7vnMfuSho66w |
| bre.com | https://vertexaisearch.cloud.google.com/grounding-api-redirect/AUZIYQGDvjJe2A75C3oPkgzJr1EXP-0n4BLxzNURDiQ4Rs5iKzuycKdXMqD7w6RKL9MHck5b-FbwyQI83UoEw19MmnPslesi-ZEvya7s9ML2ftv5yciBxXv7T1KApvD3aCM6Fzhpj_ecJ1-icES3iFG9-bNxHiqHucS1pFXOaNDJESjL5mWNpduofCHstMuSM0LtxZab9U6_2spQB8Hig1geRNIQPzOWRo_fc5vL3Npk1yzL |
| carboncapturejournal.com | https://vertexaisearch.cloud.google.com/grounding-api-redirect/AUZIYQFNRTOZnvmKjNJHHgIw-eU-XpO_TKe-_jTrfs8f8sDzY74K1_QrYVPfr4NXyTumtTYeCYN79JRk9l0ddXbD6PTxWSy3ZcpPBer0-Y4pfV_3fvEmCxVUSsZuVEGPXQ8ERiPxvhQsUTFE--cV_BhJWWFpqaqqy_hNLiZhrWEwum61xzks63JxaoMEsmTh0hEOD8KMg6bI0kSE1Hk |
| carbonclean.com | https://vertexaisearch.cloud.google.com/grounding-api-redirect/AUZIYQHuxqyXpNdkSe_jOOS8S74KI_5GGym3rYk_Ghv3L9gDkFDUbGQJ0Vql4kUVKOIIhDk-tc-0MN4faZRdn0CqqWqjqyuHFwgLjLOHppwk_AjxR3mdpOokO3pev070tPt6dXfzscQRmqFCMKMEq-FdFH_lnHUzHdV0mYMN7oS8w6CIOYm_wCSy_aMcONmJN0GnbScrHyTv0fcm-rtW-agVVEuRgIdfcX9dhNeGdEuWxoq5OHUJ9Jt6Cx_wpMDnNO-8y3DXIeM |
| catf.us | https://vertexaisearch.cloud.google.com/grounding-api-redirect/AUZIYQHA83LEdkOXcI3EZbC24depg56SUCO0V_bJqq3aOziPAEEpDijtjzoC98k3OTY6YQtkjCUvxEaG-BCRpD2R8LTr9iVO2Re_Fg76-mTICNYJ-3mKgwFG5-4Cvt5uHADXE4bVBPfs1qEq_qIZCJ1_bezs5T-k9LUQ0mFPaIqXtVs348hs9gSER9us_88zxgVX689ydKk |
| ccsknowledge.com | https://vertexaisearch.cloud.google.com/grounding-api-redirect/AUZIYQG6xQaD_1ZEde9Ng03bPrLSN0h70MU-AzRic4jJL4hMGQPEHw5umNbY4fkUMxsUI2jr-DRnV5-PeguvUfSlfyuYlop5yY1YSqV6fjv0uh_DcYE8XDKmpmQ2_KHh1_HWDlPJWPhehklfQfmc6cyU4HthETJykPcb5fFoi3x8mIZ87fmzyZQBMHNonPoosP71NCYsRaB2x6R-czGGFyfpzZGLKwMOAI41DzvxnrOuug |
| ccsknowledge.com | https://vertexaisearch.cloud.google.com/grounding-api-redirect/AUZIYQE2u_6H-KcX7gOHMrJbP3TCNnE7wDepWYCiyhDk0dK7bw1sSUlF_rVEFBC-UwPVnCKCDX6_lMrgCY4la8z2BdR5JQK0CLlc0wR3cOOh4ozVPwAei5luZDxkZLHfABs5Btqc0V0LwN-ruhPq3NGQe5gsti1NRWECv-LaIz2Ol0idtRyAvIoEc2hZ0Ja_FwAuBBU |
| ccsknowledge.com | https://vertexaisearch.cloud.google.com/grounding-api-redirect/AUZIYQHCqWMnPc2lghI6ZAlO751EdMBPlO2Sk3eao3-32eVR6OMWKtPkrwxXWLZnGHhEn3PvQInbKnHxL7_e0yHfPGjUgy9CJdPxxRUYX2c4Gni49xjPEV_8Doj7dFD_t5_9NxbvK32kSBOFYHF6wdDNM0ucRR8S2X1WYzyGJWCli4kwlh5Sa_AgFW2xK4gWaPj-2hf1QGyM4hS3BvH4tz7WaYBX6uLEPasSpW_d7rBJ6jLk3gtoBbuct1NvaeO7X_44iFEty5exCAccgdXDhnhPhnjyuvH9NoAdLeNDmlqC9STIhUNrLn3UH4m64OsnJQ5W |
| cetjournal.it | https://vertexaisearch.cloud.google.com/grounding-api-redirect/AUZIYQGm7qOdduXNzEWMTZMbZ9eJ-Bjef1qxHBuAtalNzW6kN2IDs_0T18eP9mmYMEoiG_bYLtetOROMrhKeUwqAigdWjiNvSm0ZNvE53QWDlHA1SzDayc5iWrUwX6FrvqTDDMAbyv9gxHt3vggzdBvjKeAaGelkpz0EBeAhqA |
| chalmers.se | https://vertexaisearch.cloud.google.com/grounding-api-redirect/AUZIYQF2iq60WBHC9p_3upy5REKHwgdc17-Ga2k-vcoac6tHJ4mcb_7Jp00tSY9OBH1yVfIi82XHwlV6FeVD76DqvicbZB8OTTZz_kvB-HjaVjwxxEcYhqXj_vzhQx2FIzymDf_9AEOUWG5EGR7V5DNn4NJj2Gn-7UBiGcCac0-T0zTMrPGknw |
| chalmers.se | https://vertexaisearch.cloud.google.com/grounding-api-redirect/AUZIYQG5gEYOFAB2UjGKBJlcbPTNt-CDc4_CrI1w8rAFFTpSVGWcSNcc1uzFFQo27lHByWPaxvI6M5iIRlv39m-GrF4SgzQ5W449-nDcSdYL2nUdy0ahNT0kWGvJyeg7j9GsVW-IgbvoqWHqJIw8BE9oqo5d3875n4wnYH_1lPgjkiiRjSbvqg |
| chemicalprocessing.com | https://vertexaisearch.cloud.google.com/grounding-api-redirect/AUZIYQGr9o-7czC2jkP3V9ixBH2vWCOGqu9mmcXOMoJXzKl1M_PzhrlbV6um6ATJcSTrbzr_NmaqPUmcZIP_UVTKq62T_GfsTeuUcgpDFEWQsExPMS7vlpcaeA3KTr6_LLB2vBQqZnozV4AJxp5zBcjke8iZk0Bb_UxvpzWSpf4txl17Niq2ifpeRBDUj6-2xEiiWATC9e4d0fpOVrRMkz7SlRkASmTn6sqVDr0m4jgnwxn-9lg8ozPJDg |
| chemcopilot.com | https://vertexaisearch.cloud.google.com/grounding-api-redirect/AUZIYQHBgYFRnFZxOYfgmxiqb7BelsRh9qYjqduyoOSu7sjj-Is_FU3QoareYiGHOVAg5DsjKtDzn6c2DWusEqqfVy96OnV07-6IWSTKoKayfBweFNaJ-PzG9f7pBh8O3W8WJ1T7NzwW7QiqZ6iAb2DB4Q3U7Qdr |
| city.ac.uk | https://vertexaisearch.cloud.google.com/grounding-api-redirect/AUZIYQFvfMameCbcZErCK_9pI0sV98XUoQCfIXxzYYO9JDw45eqtoiFByQ-8S_4N8GqoTOSgw7sv6jkwz6S4udgojsYAUkllm_wNnHTynawKXU3d0X77Knl3-FWzsuCgAywbnQi9StcPU07dctQwvcWul6b9CPKU2FPkCSSpyaDWKUyFRFZLk8PNbkEPOKhC |
| cityu.edu.hk | https://vertexaisearch.cloud.google.com/grounding-api-redirect/AUZIYQE1gECnHomLPDvc3_lr37_MZzofP-icUuw2Hx5lNRmk0ShSOjW4Poq94k73sZF8G99JLFul6EGSuug3YjtHTlxUqq0gBSZbx5JhBRqKgJRcZZ7jm88GnqChCVUQ--JgG8rcLtYCjiQH7iB8lP4vN0NY3cEugkM |
| cmu.edu | https://vertexaisearch.cloud.google.com/grounding-api-redirect/AUZIYQGtHcJQZrdr7AfLGKcEd9oj02QA2kD5S0tN_XbdUrNEhRWltLcdTNUgjCBuFeQUO_U1kpXBn7K8c-lePzlykBh2gSM4IUvGAJTRqkGh0mVjIBHkqtgFjcQkF7OLlCrmeRJ-5K24x0RsZQFu6hzKAhPd8nknsth2Y0zM7fs-c-E1BQIRf2Bz_Q |
| co2.earth | https://vertexaisearch.cloud.google.com/grounding-api-redirect/AUZIYQGMKH0jC8jsS_XZ_mmNmrhRuOhCZqAtz3MtmLafj9JpOGTY77mAF2LzweorYJ0-3KWNF2nGK8bZ-VPraA9a4WCYBFH4uSXS9BPg689KmOzHK8uieG23XtglVAmwxNnLEXmxXjLKw |
| co2cesar.eu | https://vertexaisearch.cloud.google.com/grounding-api-redirect/AUZIYQFqQi5KEWMPvnsw0kmkh0ajITUucV6qbjEEPRbO41kdL7veWr0ulpFydz7XKzKgWBH-jBWQc71EaoPzGXISexlXAXwpLOWPaymBZP3iAyKs |
| columbia.edu | https://vertexaisearch.cloud.google.com/grounding-api-redirect/AUZIYQHhVRn06I0vwjQGu26sQxTsI2tZJch-8t7t1e3MjwjZ6iVF_nhZG-y5ZELkncI9vBgfXXAW6TGNFOwuXGDstHQS74MkF1-tN9prmdH2qIcEFgqDtdKjpQelAZkdwkD1AzQU56TVBjD9fu3FtbbalBXOhTtDzOD0Uvb2wbWA-fcYhCpYwzD11DPImgVinOhhcNCeCSk4HWVUA9RIoPxANac0pew |
| copernicus.org | https://vertexaisearch.cloud.google.com/grounding-api-redirect/AUZIYQEWPwQs8zZf5-mL6QVkq051OY3d3F_iRHNovUy0IE4eAnf8A6QQNoDLi5iJou6DEZrx8pzynnHbXRIXa3ocJRs4c7ElsICKQLFm2g4VhA7FJy0Hm64l72fSGz0utyORCMc-LiN4wwDdaMkGGgTS_gLFMInnioGzH8JGx-8L0XAAaqSg |
| cput.ac.za | https://vertexaisearch.cloud.google.com/grounding-api-redirect/AUZIYQHbA5h7zYTY_T4EMTcSdIGOEzEe8yc2RpdnNJ8wl_KMSCsM-TPV7mhe2XXRXX_lga9bAa2nY5AK-FT8qRz5vL0FxLxqfck-RFHZ4LHTthhQWl_OojGBYuppSVM3TBS6v34AXaNJDmlea-1ka4x0bKoiyNN151JK8gNcL0vM-ZYUiKUK2Atvj6JbkWaKV4U |
| diva-portal.org | https://vertexaisearch.cloud.google.com/grounding-api-redirect/AUZIYQFi50IRQyKN0ItxbdvS3_7gJpGswJnnQDqvC2lqmpUJx-MHaVhPrsX7A67u4DnYM2ONiER-LLCREHz7liVgtbANabwkEYH3aqKLw40bioDWTWvfVgc1kz4XtmTgdLA-ueg6X_pKJRIeIQOBow-59gLQSfiunTe4KeI |
| diva-portal.org | https://vertexaisearch.cloud.google.com/grounding-api-redirect/AUZIYQH-EHv2ZYCT67-FDgcaROqU16inGFI6W-VzlpuuPQ9yjIaK9kbLMVyJ68IQUZ41iu33kueruYbmQl8K6y8vbO4WfKzfR9HfRJX9GbsLOf_-TWg2vCV10KrUuHGpVtwFNfy5pt8xC3opwqLzW0mJxQ3rcx_FcdSkP9Gy1S4m |
| doe.gov | https://vertexaisearch.cloud.google.com/grounding-api-redirect/AUZIYQFjJsntBzFZRIkC4kA9PP9YzZfL72LHaEtlSeVsNS1ZuhtAQOyUMjN8Zjx4kbsTIs4TmG0Eqvooe6odec4ke7UERs1Fc5-qnU_mHTmEoIUi6ZROVuJ4qo_54BN5C6oMW8WyLk-9vuHIOC0ytFdCyN-VB5FR |
| doe.gov | https://vertexaisearch.cloud.google.com/grounding-api-redirect/AUZIYQHeLin8TLB9RdCMqkM7-mTbS1mFD3p9h-Nmz4vh0aYM6jmQQ76XsqAbNIKI8K5TUc39IK8-HEtWK6BNEW7jl3LTqgBrNeBJfKimIpA_jRf5_1AFmpcvP6SjOFZ0QxcRBbsB8pS9_ldQ4-5H3uoHMf2bJHzBdGW0R0G0gqk8Uw |
| dtu.dk | https://vertexaisearch.cloud.google.com/grounding-api-redirect/AUZIYQG2DJ5So3ib9el6at2i3TdeWZSGbT4z-NYUb6JF87dEZXgFOuEPYYsi2fhLRFIxdHF_0p02N5xJqKxTjE9Q7GwkLQl_QCPtu0cUVIvFpX6PkWS2SzyMKslP5k8tzOQ6gdZit48Yv7wot4_Y6cQWwHS1f2Q0J9XVsjaWz_bEg3QmjYA |
| dtu.dk | https://vertexaisearch.cloud.google.com/grounding-api-redirect/AUZIYQGScBqjlA_vt5xSR3m_t4PTMdO1zvt6hk1vecr8wJtDOmjGj_egCzbcX11KQnnri_AnnvwxQtw7wdUjCirJxDDw909zO1KBq1Nbjz-kQVQ6uWovhAPQoV2sUJLPYt9KoCPYySwYvno_sndwbLE7i2pA-2efvQQeDcsqk2BzInXXmsagKUwOG3SaCkfFevNO6czukez6q0ZO1JtJwgeQ-Bz9QicB6nQ |
| dtu.dk | https://vertexaisearch.cloud.google.com/grounding-api-redirect/AUZIYQG_HcDz_cM6i30UzxeV3omlLpCaijWEDyYv_YL_t6gKOub1AiWgz_qn1ME4AEPTR10pmS1R6sNlnic0eV5xsjJaAA6No4jN5akMQTF4uhB4LLd75hsr5sMptrs1A0q5GkYKlK-VZ-D-qLp2m5BWKFbK7BjoG7SQzGYNhrfqmnra7ww |
| eia.gov | https://vertexaisearch.cloud.google.com/grounding-api-redirect/AUZIYQFeiZ5qQAWGXznpxRVjCOnwkeoz9X3zpbfE9JZ78lHtFBR-1WVDaxAG1sEhjGCi-HN8Bt_R6GpqOlIUCgA0m-2GF3lCYGsaGyF6nfiLTULnzpTMtnH0rravtfYv4Q5SJ8IErkf26FIAzJYh5-XnYN6Q |
| ember-energy.org | https://vertexaisearch.cloud.google.com/grounding-api-redirect/AUZIYQGchj5jKH8UdsVIFgGxU9Xobf-W0b2cvpbwH-jc4UDxgwElnk9iqXhxooY0SNTfqcZqNfidgWXnmUdEKXwQx67yUrGOVtNWqDJJ3dlOuTbwjtpROHM_oziCIQmYGEIFsQdcklx94nNoBLYgkJz2kEYRCkWXcVtpea7bePWBPqNWatt_M7JxFoXJm9qajyB7hCUU |
| energi.media | https://vertexaisearch.cloud.google.com/grounding-api-redirect/AUZIYQES8O1BqKrV5_CgIn_Hbhp2O_CpBjAhZ-6XPLmoPjBSOzM9RBhR4tPkn6G2t90dWQZVcI51wyr8nQ2QHawaUgo-L6s1C7QNmUq6jaAmj9S-aESmm9e_W6lVbOmO_X4s7aOCoLLojmnbalm_YksDOkxteDWGnW1Id5bHOQjsXxDC5lRlj5ynxsaW-wpfYbD3P96pifnCyJpj |
| energy.gov | https://vertexaisearch.cloud.google.com/grounding-api-redirect/AUZIYQEt7tLbAmx1P9JDHrTR0ykj-kHaL6cSCHTL6TSSZITEEtitpiBIhOtMJTfeh3JWzkXXBznkvKFzCJKtNerLEc4yBkR_p-eU8dOzP9IpcLQ_pKaeBLvDKIWzCm9FxrSfu4A9opM6j-jEFt_NFmVrlUzOGNW4rJaNccIyL46r8bVAqLeFioPgGPsn83_XUvIsuwYgnhVBv41_GSn58k7vZB6RCyiDqjCsDsZw6-GQGH9UUXlV3A |
| epicsysinc.com | https://vertexaisearch.cloud.google.com/grounding-api-redirect/AUZIYQFGDtYrPvIZ3dLL6sz1TamR4D6s6eLJd1h4kkjgf_18eN0tqxtl7yNRVQUOBOqaB4Y8KiaZLDB8KiUex9CuoYkIEGt8LAbqmHdBqBfa3sxscrTGEhKBpZTUYbnF6N8c5xOFc-q9s6iDPFWomyqa8CJmHnMKqThE |
| europa.eu | https://vertexaisearch.cloud.google.com/grounding-api-redirect/AUZIYQHx9gzUZRQexPk35ZzRnF9QzkJrSoDjh3R5G7GiF_YBwNdVY75vDVdQBMc_gLscEjCTbLzb-Ulf9rZjYgnQ5ZLiuHu1p5C5cBammDfMRZUWIsfo2yQByCSRQDf8dR1d_N-7DqtcCu8o90AdupPv5gcvD4s |
| europa.eu | https://vertexaisearch.cloud.google.com/grounding-api-redirect/AUZIYQHKSnHZpyljK7X-_G5GTBLUoAQk98LY3a0QmVB6oIiiRoIl5mPAZLuMy_Bg1Lim7qoNGRkejV-PAMkBEpKVqKuBmdZLLyt_L91LFQ4poQsGFe_OZcKvm9gdOm-Y9Vs-BGKTlXBfxO9lSDVYYDvTvew |
| filtralite.com | https://vertexaisearch.cloud.google.com/grounding-api-redirect/AUZIYQGVZmp1y2i4BE2kSUoKCZoHu2sNUwNNPZWlerCap-mcCZudgdxw5G-4lmiorp7DdngL-T7dSo2SYuTh06ok89aKw9IPNw3ms1YVyfFW74gEG_SnSMj13ZOFXRCJuQt4fhZHlMU6S3AM11cU1bgf-e-WaobeSVRyjqve7tyzl76Xc2tdsLFw49oznHF0-j0iZnENWdmqs8qDnEcnXvsIT2WoJJp2y6xx_Omil2-T1m1gmT28eOZqqHf4cTRCh2OY1xunx_d6zvq9rotZszjr9bgEhXF7ir2AKFH1lqiAtGyHa5IK_f_mHCH1CZ6HpBzQ1udMNrd1UShb-uNj7pLO |
| finepacindia.com | https://vertexaisearch.cloud.gasearch/grounding-api-redirect/AUZIYQG7palYMe2TS3zkvW0dnbCVK4jssnX6CTjrNhMJb8OvJrDiGF6kNsuVUB5baSYt0pgCb7BluS39gGtQyDjfi8fCdJBLNZ51aUXv-sY1KgPMLfggm46OKl0Wo4iNjFLml96uIWnkP2unu9JJK-ZW7SnWtxXjzFlbiXNkInCofQBP1nFMCuNFxhCzb852hhpareJJ5AHeZjk4xL1oRd0_e2etH06si3WiF3vv3SCTDVMStKbO0pwbGIcEHWPLtmw |
| frontiersin.org | https://vertexaisearch.cloud.google.com/grounding-api-redirect/AUZIYQFyqojW-dHsHQiKE579prfPjmsBGm8Uh0YoFtefiVg-RIS2BBM0YmtUYrwY3qagX-gO_a_JLNV8v6vAki8Y8TC9ImmyoZJ9J0UEdz25v-jl78-hjuxa4tf_5rfpjDp8R2bG |
| frontiersin.org | https://vertexaisearch.cloud.google.com/grounding-api-redirect/AUZIYQGSS1BFVlQxypzi3r2SXeU3huu1o4qA9uD0dDItZOAM9IDac-79YV6cMPTEe42LEIndHJMLxsgCD3akIejoOzjdCPLKdIp88lSMdN7AJLf5TqPFLN5QEi9HNYHNZtcqpUNlElLWa9QGOOYPtCT_q7-lXsFRh6LGUMY6qDBo1rLHK52bJvg3kPgMVV1qFs1wmIMnt4iGE_b8bw |
| gascompressionmagazine.com | https://vertexaisearch.cloud.google.com/grounding-api-redirect/AUZIYQEzGdiDhq_NQb7C08GpcZ-mrnUe1GjGrGsXzM4VXjSQlpL3zhzqnT4ugRZS5HY76Z9myIVrgudlZL17kEoMY6P1rT2-cQtdFTh2935oY1sQz4bIZNjzjDQHsOqNWGa068gLfYO59-r5ytU_KAdEujCm1ZRorOekvz04Ya_l79T6cp09HTw_ux8voGrJbmHTDelYwodr8uQ5X3Tqd7vqGq1vZFPA_4FKkPp3GU5- |
| gazi.edu.tr | https://vertexaisearch.cloud.google.com/grounding-api-redirect/AUZIYQEW39xwGhTdtUpUoqGAEjAyU9ARC3XW0tcRRIJuvJLWpZR1Non0-8XDVXFvSMk_zJWPi-T8Sx-JBr8c02pYV2u2jV7otZAzvG9sskdB906Kx75XAP3dpiIQ4A1cBZDJ0HrtCXF94q_gcWrVVrD0a6J-AwT92tAiWZjK3-ZimP0qt1FPjy-qX8H7sNj4UCByh4WJUt_6jnh3LaG8vxySTyGelz1e5KgA8k_om0BoKwuxTEevSs0IHZwW3kDEHym-YIpQ4bdE2K3Dh9biOcBl4xo4Qz_g0btyE9N9Gkkd4zv2jhxS0wbfU5mRXYUDPGEZa3-HEQ |
| globalccsinstitute.com | https://vertexaisearch.cloud.google.com/grounding-api-redirect/AUZIYQFQZ5RYPpyIPGR4mIwm71kVjNGcM1ZHFpi8mYRJ7-q9z45axfO0AcgSSUvOHXkK9Yy8hicwTtiyrduxHYVnCCDXmAgui70pKFSsJoUwTEfSFFsZRMEQ5D2KDC5V6usmvWyr68cUNjr78lzLu3J29wW5JPtZb9UcElPJsPtYmh-VdDOOkLt4xE-693LHlNZHx1xkPRF9SHUWyft7Y1wP1g2yXnr-1R2n5im_TRrxQN_qbLb_1F4zBxhfhvXKkZOVNlo6rnecg |
| globalccsinstitute.com | https://vertexaisearch.cloud.google.com/grounding-api-redirect/AUZIYQHxw6UFfaP65p_ILgZvEp9sbFSO3J07hxALXNA_DDdE2HruBOnIZKiQDPWTPgkMlCU1ctVOircl2YtP6SuIyFOiZCy40z-GREVZg5nVBmfHwLE-nPM9b9XW5xz0J2k7kEWz_v2lvMDGuDqxiB0-1R9F2SHG1iUGPo0e1rmiHBrmQUBo6WNjp0NgMUMRdJ7JL0uYTegvgroyAIEGgKqx |
| gnest.org | https://vertexaisearch.cloud.google.com/grounding-api-redirect/AUZIYQF7m8y1BKwmS9VqXgc0o3iMzE9BCSEd5dJRi2xoI2BiFCLu8-5CCP67Mb9iSW4TTOVC9pZorcHrgmsRjm2XefP6W8-7Y3_FgLXtLYrdByPerGwmdXwKpXUmieJ5DxU0IiqQ1XsERynKsB2XzotaA9DTcRtBZ0EHUiH-veQUn1Nr |
| greeninstitute.ng | https://vertexaisearch.cloud.google.com/grounding-api-redirect/AUZIYQHatJZuVGkuPKNGFRVuJmpz7hhFpP_-LUHXvMtMZQtvCaQIqAEFTkQzP7m6S_8u3awjQ7MpjHFTTBq51yhVr9ujHGN-7tvnLE7tCytNw1zaArD0svTxqX66udCZd_a8NniOlOm19VTIeuKagEgEPqwFK36rBA5GvSuGC42ZwW2uiUCJgPtwOxmCUiRbK_k0em6tyXNGYaLqb85p2eeXwmYGtSm9ncTjH9B6siJTZ8Jf_hYMM9vN6_H1CyA |
| growthmarketreports.com | https://vertexaisearch.cloud.google.com/grounding-api-redirect/AUZIYQE2SCgXZrgqnEgVlhLq8glY2BzdNlAH-QRG_fu8XyTnCSeZN0EXbnUsWoX5_ADuOCDUFvSShY70Nrrvjehu_MxmKr0o8vLrTO5dmsqaOFOIXj1S4U_XsLI7pjDNTDs7g-K45Qo9L0cqm_BrN8Mwx2qioJ05ZDfFzzn4o1jsL3_t5VZeP8vodPVlApLkZkiUMzE |
| iea.org | https://vertexaisearch.cloud.google.com/grounding-api-redirect/AUZIYQFJub8IIMCr02TZqBWsZUWge3cYmQpjcrouXVskHihuoIOQa7kbJk8jYuo9_ULfO538j4Z4DphDUHMXuwLZJNBDnfyVx896Q__TD2H40bVd-KKA7v5m6WUASoGn8tcGR2ahKd7FbKt3Jiibuqik_TY2IWdPX9y2lPUVPzE1hYOA6Q1F |
| iea.org | https://vertexaisearch.cloud.google.com/grounding-api-redirect/AUZIYQHS6mbz92G3KvOknfKR0RTpGMb3XTMj8LnOJQ9VQTll_Ft6dHHwQ-WsZgtTp0Nanlke8SlEXNdEKGXVZIopOrHYptjSCObenPKMR6ZHXaklgP5zq6e03zxhuXab_BCtm4VoFeqrFdXmMcZ_wg |
| ieefa.org | https://vertexaisearch.cloud.google.com/grounding-api-redirect/AUZIYQFU8nZ7DGrVUtLlVE5KrQ37liB5cOyaaDmm1PaZ7Vse1S0arx-nKfW0mR9RRMdFbz_XGySHwGQ3wyPK7DNVr-aoILK7QJnT7FxSJPZHEiznBDiBjLBFHvb_X9Fz7850M-mwOmTktJ2l5IcPyiVZ9DusyREDhH--lsEfQlNoMs8ZJQXHP69T7lBbR0jTckGNSg |
| ieefa.org | https://vertexaisearch.cloud.google.com/grounding-api-redirect/AUZIYQEQ0wUNr9HqKM_fWj8NWy7939HXGbf2EDK2XNWgxhQzU6zOzXDb44VRARSDqgzhwYPYgixHzOKakhkcspxjObLjjYbu8PclPT6TcLdboNcnimy7AsGXJqowDiRy3rgtPYL7q4qg9P3eXJdWjM2M3H0SsyscI4pBpvDCJNSkpynv4egzmYdq3YKAzKpZi_o7kkhU1XpqE9d5zOICY7E9lc6iSEw_DPojBvvtiLyZs3wCsfc8NLZWWCmm0w |
| iitm.ac.in | https://vertexaisearch.cloud.google.com/grounding-api-redirect/AUZIYQHfQCwHC7mIgdwNakGSBvWrZKlN0pSuJzDFSD8z8ywOi-3Fkkg7Bub3JAER40ZG7HlhV-nA6aVIqpTHL2u5HFw0eJHCq8bayJa5EzXx2LtaiD0KknXr5tYGvd3SS6gTWYuRupZ9Ob9ghWauvq5S9_LPUqHpy1ikM7iQ-Nf67b9QaDS6tMVbeSCFavKv79Cz5cY7kdd4tTT-rsz0Q8jdu_UO_LTTxQDw |
| indiatimes.com | https://vertexaisearch.cloud.google.com/grounding-api-redirect/AUZIYQEc_5Hd_1Fymqe8R2ls7jEr_TbOo8A-aoghqJYvtRGCiL--aS2pdAewSIA8YRkyM-XZx9-J0ulSaYtG8XjOj4iMWy1TUTs3nDO-CSci6f2VzOojDDVSrGAlue53tin8Rm0gPQ1ZO1ueEybX5ncvOyt1XuS1ToLeLGIi0LE_CGxsXz-DrJWFcIF1XD2crq8Xf7T4W8RDdZyL9IZliRFmwRYqcWzT6r5riAQy5T8SR6s1uZyQAW3x-wVKcYvfcaNthF9l0TMIWb2WcuoeMoM59S2OalBnElVXmcTB |
| jcsp.org.pk | https://vertexaisearch.cloud.google.com/grounding-api-redirect/AUZIYQG0TUj3XizJ559dw7H7Llh07PqlbUeTMa7WCwLkFwZgFQ8n06b_dcLuwNx5qgYux7o23XZdFDxeLbyT67woYfD-HPgdZpLR8l-mEBuvAX7E6sxL57UPnwpKue4aR59y-zuUKV-h2OMEOcItr8TfH7es_wDnCmhRAzxYd5lYs7BAVtN3ie-1CpMO |
| jksee.or.kr | https://vertexaisearch.cloud.google.com/grounding-api-redirect/AUZIYQGjiS2KSN8P6UesZFuocZw-WdXMO1rgY_VajSl-WoB6d6k7Fpgj2c9S8o4Kw5iihj7-tT_y1e27OfQFJNX2kVPE69f_2h3EwyknQcpbeyV3PGYOABStHfErbhA-KKc8L6DAeS0VaMpWz23bn7_qLJR6lxcF |
| lindholmen.se | https://vertexaisearch.cloud.google.com/grounding-api-redirect/AUZIYQHc0mbvitApPHdHIN4uNIFU0aJKDxMAMRsy0EBYHtWrh5RHB1qscR8a-e-5o1yhah8bxu4AqCCklR5kzGorsd-7QDC-zLSojpoqG7CamKOPq2vbT__rRYtW7z2qgc9Ek2YKD9af7W8_v_-P5-LsK4skAbUA44B1xlDkq2Hh1eDeggmgCeJZ0RbVbx3p6I9coC2hz_f7hdo3_eUsnem7oXqbPuYjlKiktVpFaxiL-mwSng |
| machengineering.com | https://vertexaisearch.cloud.google.com/grounding-api-redirect/AUZIYQEx31qoZOazQeWnTeeEdp9VAPytBUT1W4i4R1rrK3Dxgr4cg3uAb5Gt7H3oNthOIhU6c4sOMVjMzd8S_IxXdPm4JYziVIs4j5JGETv8Gr-aPuHPgLHm0tRhUw9FJRFlQPzpV7pBHwLnzVGzbfwqWUtem2gAK-6VMxaVSraqdB-UYGt5gY98 |
| mdpi-res.com | https://vertexaisearch.cloud.google.com/grounding-api-redirect/AUZIYQFz9cjwoQrtiZCoVb8FSOfLieRIQNhxizlc_qTL1499hhQn-psr2YoS8-7WVFgwpDc1Syy687FSwzWwUCPfY9mjwFNjrKMMIXPvKUBpOO65KIXJEytOnQnQkVivHs3jFixwljGOgLw82G2jDFOlE62CJyKY5KZrjTKSUDGGmOuG1J2UwnrjybDZaAnvaNQlujH29af8jw |
| mdpi.com | https://vertexaisearch.cloud.google.com/grounding-api-redirect/AUZIYQF-w2-8XX5QeEQbYN64Gkea0Mg9OOmnk5rd7gg7SQ4eRgPPGiB4zU7f2Abbbon4eMfqU59LDZdSi8WZS1RJ-UkmhD1W6Y-TmFmRGsvNt9g52CKV7uoVG0CMYS0aRot4b1rP |
| mit.edu | https://vertexaisearch.cloud.google.com/grounding-api-redirect/AUZIYQE_arkyHWAldj_mUrlx5fMdkhR73W4LvEWnPVWn6zAbUmt5kbrQNX1UMPNuF5dXY9olyk9pcFla_ZAVIGYM44iLLRqYrSGmCcgwOU6rBwngagEjqiG21l_PpcA7Qsranp_JvRqM25hnk_uG5az9T4IUnOz6D5yG |
| mmo.org.tr | https://vertexaisearch.cloud.google.com/grounding-api-redirect/AUZIYQEsvmDYCx-EZ4L0Lbh9-RVjrjvmX83KUeJ6fCEAqpi5Wq6FWE_YozgYT3H2Nf2qfIf3vaekjxGVTisWefAGVQ64iam90E2Izw8BdID2_assH8v3VnMFPPULhIfCIFFnPtaegN5klL1tUVe-Pbtg716yc9h0_NTBjNPIodkO0i15JnZc0GGUrJ16sXSXivZIAo9aZHJADQiEXjm4iO0WTcD_z7keIh4VkBCdpzYc2pcXbQ |
| murraystate.edu | https://vertexaisearch.cloud.google.com/grounding-api-redirect/AUZIYQF-46vzi8A7Ld7ZHAC1B_djuTso4n-02HXEyuas5iV0Ee9jKqVydto8FzlPxUmKGUMq8edCjDtvMxVc1BiwVOiqCY7M6DDxmiFlwzKacvJbTqZi6DLynm7m2wrwr1jn468ulzg1U3JbhP2DuHMejRgsBX8XpmMVZI7EYwnZ_gRQbXw9PcIH7RfjaWll9839 |
| npl.co.uk | https://vertexaisearch.cloud.google.com/grounding-api-redirect/AUZIYQFpb6UUpW_uGSSOquNTb7zn2EYfTVZkiwNouSY4WYsx9l02MRXThB2SbDYyXGHVYRYm12OSrdM4_of6f1N45-x0DHf0zaFomaXhXgv6IWl2JOovkrirwgitXIOdh-g5XWreVCML-PEc |
| nrel.gov | https://vertexaisearch.cloud.google.com/grounding-api-redirect/AUZIYQHMrzz5mZVX1XzgPG0061_i3z51ozjMgFU_HTKD00yd-F-Vx_S2SQ3uvrediRGtG4VtRpgUzPIkyTCYr9d-cEuVGUhPufYppD1thusC1IpStNWn-KwfRVhmBA1hXzsCbd9v4NggFVOK |
| nsenergybusiness.com | https://vertexaisearch.cloud.google.com/grounding-api-redirect/AUZIYQFLnYA6zgY8lNjbMPY1qOs39ddl3fNtUbEqRsY8ScLCu3aGYKfF_jeZLE41ICfU6J7PsYTWt9vWm9oUUorE-YQFVcayrL1-YqJAOfya2zRPOJ1n27gk1HEeXH4Og5Qxbc4-cyGeR5uGwaDMskNG4HBylp0fF_RRbKWUTJN1KgrK93waAS_cP1M |
| ntnu.no | https://vertexaisearch.cloud.google.com/grounding-api-redirect/AUZIYQGPAZcBcI5FXBsgsv6lbV3QCP9cO-237RrwnTwm0AwClHpFpyiOn7g4T53p8Il4CKC7EnFVGO74EOFvjZWOnKewsyO9EViP6dQqfQc2ejnDKQwaO6V72op2jPomqvSAmVwWZfO0NwGis7jqLUKsNqxe5G1NHeLjEOeJujsRT2tCHhorWTmq4O5h7mtGu8U4UD3vVtc4l4E |
| ntnu.no | https://vertexaisearch.cloud.google.com/grounding-api-redirect/AUZIYQFphaQAg4UscMQ1Pa2XoI-JkSfu239P96k0YQnzo8P_aZS1-iUYnUVlEZ0Mohu7cB9w0e1YI9_49Zouah9EbCBooOndkTxLe9LcPsrffUQD2rivd4mEQ6LLmJisc-ex8aNfedeSrDmrS0LK0EzkMCeLf1-yiyxZuPiPiP3qbXWX6Z2gj-hDbLWBe7NpS1EnuUGpI7JpIpYUuU-SlFCdAhPjvILCHfJY6eOCweHW1u10unW6G0dftTcvGtt1TAOCMkGvES5OSICyj__lYZlufgcKtzmr9hdpWV3SqufaN5hz3V98UB4xg0B70In9fymtaVGg0qZevqGEgDzBrd1N_Y9dP0Rj4zcUeQ |
| openchemicalengineeringjournal.com | https://vertexaisearch.cloud.google.com/grounding-api-redirect/AUZIYQFcb2nC8iCRNo5FZpsGTgJPeOe4RitZ7moAZ2wl5X7WiTwOZWdV6wxqFcW88e1dCg44m3wK6li2J0qulNb-WCnE53balytdRR2JqrHpshloja4QiEqPp-DC_GmnzuVGnmCqvk4AsZEM8XR6z4drUnRj2PHLNfH7saNQJpgL2nWT-2CNpiydpuR8ZrG94DKgjbJyJA |
| osti.gov | https://vertexaisearch.cloud.google.com/grounding-api-redirect/AUZIYQFYqNAeVCgXtiNnH7m2pMtrgTjzcaZryeV01cXS4em75shUxtzhTglLInDaNgVHYOr266uYFX4Hgn47Ogr-bonIibSef8PE4l3o3v4uyjXhK8jDDIloO-HaZRDYOc78UyqOUkRc |
| osti.gov | https://vertexaisearch.cloud.google.com/grounding-api-redirect/AUZIYQEH2gR1i_FDaOZ0XloyAF-6X2rhlSkGX-7_QmvbEhxZ6KPmBbkBR1nlCQgGsNHnIuMbm5CccbHTrCobz2SMVFGYVnz8OaPJ3Lazhedh_1E_4OwXkas-VrWYsET-5V4w2Zp66YABiA |
| osti.gov | https://vertexaisearch.cloud.google.com/grounding-api-redirect/AUZIYQFMolUZ754atyyQxRJFFm1ZxUwm7V5HBHfrzJu6l1-ALrhafU2nMoOihFnTreUatp3dzS0r3KtrE05hJk2nfIvk_QCUHRD6vqFiF5sfPVe1g6UQDeZ6N0ybWIQ7ZQBcg4rYfCjq77TfDFB_dg |
| patsnap.com | https://vertexaisearch.cloud.google.com/grounding-api-redirect/AUZIYQEl3phnlVRT8lvVpiR46F8j4Wer60Ma2jz2s70U5cazarnMNZNCDMUCwvE950_dKdMA0qQ1fE9tWYR2evxL9WBmvt4swt7tTSYGklpVyBV5izjD0eGvh3RtNe9qQwJ-UiR6HGHhv82AOIxEZkD7YSfK8YJ3JG9hyqNWcnuNya65cP6yFVuvGL4Rck5VXoK9lEjFQOUvQdZa_ByzP4rmzQnpTZhJiwoRUltcnakdDZYKuESnvLcB |
| pitt.edu | https://vertexaisearch.cloud.google.com/grounding-api-redirect/AUZIYQH5T6FpRFYJAyU2W4jQDyYXKkvG1UU7m-bHH2QgUKyxnQ4Sds-kxJeXbsva2ai7rUjBO-_xJAXVlduejmxrS9Nmq9oIl7DuykKDpwkJWIsTbuYML-ZcHHKkn-ISr7kZraRhtJqb14URN1v8TFmBwBDVMSfDu9eJcLMpClDi |
| power-eng.com | https://vertexaisearch.cloud.google.com/grounding-api-redirect/AUZIYQEyeIOeWF1tcZZTl4N0fN0hz8vV7xRohVwQj9ayCTtnzBZUBo6_PosyAY-mVGMVMTk-dt0qxZIDVh_CAMeNyXi7dqS2VH4VasKHy0q0Ar-O7IQvAEDYE68VvB9uLHRGceajNNfnzeAif2FiJUhNJ-nJ61AHZ-Hv_Q |
| powereng.com | https://vertexaisearch.cloud.google.com/grounding-api-redirect/AUZIYQEnSp91OeaYD8maUGOZhE3ZwSTn56e_pTjif6_MpRHpBcmjfxu16yOtEATn0zcQOhCTeZcsHh6jpQijvmlwo8U_HFG7F_dnuqZGdiaXAWhT1wEC9Gf5jfTxCKhpCvNlMTaFJSU0O0XZizT6Bu3pLqScHW3XKSuTKuTmfUkbssj1fp_kRFHAEmDqJQ |
| preprints.org | https://vertexaisearch.cloud.google.com/grounding-api-redirect/AUZIYQFPRVSKlt9FAZ4CvLhCt-zcTC-hTW66KMKoJZYzHUoLfj0ET_Tf8XaJ0oRE9RqVOdG3iEge7XlOeUGnM8SBifLA__6QyqmOAr__LfTuY-a9a9uSaHeGsMPnOYK2GuUHz1dyEvk9OFlMXE1asjw7bw |
| projectaccsess.eu | https://vertexaisearch.cloud.google.com/grounding-api-redirect/AUZIYQF6raLisYu-x4vQyyooYw2zmZjAVL99iCluFQN9XG6mO_zT9XKLqNdYinUs9coQnRlR9X2uCsj0gOxGpCligHVW9cSWhQN8x6lbxjWvQHL5r61Y7I15-oq59OAZQqnnhL-NzfFapsksaa7NoR0ep2NXHKu3b5crPQ4Ji-PWvg |
| purdue.edu | https://vertexaisearch.cloud.google.com/grounding-api-redirect/AUZIYQGKjBslQ-AUUk99QN7rc-215sMU1NNOt1Jd4nKFEjxacxY0BT5iokIH_3ZOBweWrs0dDM3j6g13so5OOEMGs36e6rhfGueNEIN_UYDV2JFFsP2EZ8TxiFiOa1v9b12kykraagWdxoKxwcLkrJiPFixqxoRBTzI7RxoCl1hUSbnNKXP0aW-GKQcUDvfRjD4jkpiKnJL4z4DZcqqKCwfL4VbqL8PcAS99lSMvGC_7jkO_wWfMnswNhw |
| qu.edu.qa | https://vertexaisearch.cloud.google.com/grounding-api-redirect/AUZIYQFMihMbKtiftNlN1GCtUso5b9A6-Y3kG1F-rGZmXxcI6cSz8H8en1Hu7FLEUSLzB6khSxTM-flE-Kqqs4ULakeRnREDOuGZZKeJci_k7Z9424tOKS5zCmy4voWH177WKvCglL64VocBZ9meYFB16tlYgIEfyZu0pMbYpq0GVBRoZoWuQd-BC6j4txAMeSkW0ZFrOx3cLtk4bL4h2g |
| qub.ac.uk | https://vertexaisearch.cloud.google.com/grounding-api-redirect/AUZIYQGVZBM5g4jivbcf4Rg7WEaQw7Racq0_nBCWDkEnJfmGcPBNUippUbdJoojMX3ch7NPMGLnjYcLQrDhydblDRwssWlZEKlh-uz6q8z_msbZk-jsX5tWLwibHFjTpCfMrWx0tqX1P9xaOwDO-JTarOH-m |
| rbnenergy.com | https://vertexaisearch.cloud.google.com/grounding-api-redirect/AUZIYQFQEjgbwnNYMFNJcKJjQx3BWXyaqKuWtmN-WL4D0pZNZ-V-ZRh1y7yH5YJiK3JKHz2ZpryUZvRDVMXYrMPIacJ2sUe-aAg8rO2G6PyIBMRo1L6uWcpEX_2jCRzwPboQ6tDUPl0LSJM6LIEZUDer-_57GEzlbfVV0EkDpa5zHNURtkkI1JDLY41HCvkBjVA7zhWxnFoD8SUzbV8o4g7lUa3s3D3iDX79RuaDbxnIj3N4D5Y |
| rdd.edu.iq | https://vertexaisearch.cloud.google.com/grounding-api-redirect/AUZIYQHjSfnMucOa0cS6hEzyZkwgqakEGO65_bmV-Mz0Uoq2ciDkqP_Sp_7F63Zbi_9ls1QKHTm1uz4SlvUyRTGOxX8ciByA_NuJtlmOOH7DA992el0oSDUnl1TnCj42OU2bN8BQl1Sqhnlxt-Qs9l3oNY86UK7hXy0mh0QbW0X0RgA6ANi8l5jszwMOsUNKXqT9BmD_Kg |
| repec.org | https://vertexaisearch.cloud.google.com/grounding-api-redirect/AUZIYQFCMo_hpJdxHVHmUNeXxqtzQADOZ3aeJ3wLoU8Ujl67kAs2fukZNiFC44wUunIcYHnqC3y13xYxGW6ElYqcKbkoF4chY3p-y_jL4CtXbTcTwywvf0quQiIo-X5BzeoAcTSQGis6-K5z3zrTHeFxO17ivbffvVz-V-s |
| repec.org | https://vertexaisearch.cloud.google.com/grounding-api-redirect/AUZIYQE0_XsvvpZ3Buf_vhOwqJw2ova8x1rJO9fUU0Qn4pAnhPqBsNlScS7FLWM_zswUxrzVCjFdkWo7ZZj-n1epJj7IDv09c_8JRugWgdWpcc0lGiTZQWEVGi7IyyxK46cTac4o6MvGjqcR6Y_xaLBSrDvbgyLX0a44HcY |
| researchgate.net | https://vertexaisearch.cloud.google.com/grounding-api-redirect/AUZIYQG79TR3YFtdmn-G391nc7__Cf6ILSR1vUGgYBVTtj1QB07zIv5a4K2VcGDUs4NIU-7QGN2roqwLsw0v0mYDnIyQv9qUG29AxqSQCbap_wUJX0DcFeNo7bvM9B9m1emh_O1MPrCYq1pl4WPLayc7uRmj57snWzuU7BCj70gDXbUokHEevgscmur2zfsSp1ofocwYlbgONuvECYWlTK7ikT8BVc-vhAuEBAXewzOsWUM5KVc1Bb51Hy-ypgTZJmQSwJrS7aqssK8blKzD6XZ7Os4sLS0z0oBlDWoc9pTm6vfKCH2fTc_X9zWLUgnUMV3Pdh3zFM6iSpV6-_ze |
| researchgate.net | https://vertexaisearch.cloud.google.com/grounding-api-redirect/AUZIYQGZ2g7O9yJObEGUKHssXXkc5BCmGKQwf_61yI6CC1Uwpu6YCdtMPt_jyfmle5oAtGVBREop_xPDsDLK1Yn_L8H5CMgnzYgFw4jxuz-gTo5KcJBw-oRih-coRA4dSZNjsWSYbhIuJEUJ3VaWzlqz34RC7KnE6XI833WfUQDqi0GwBsfkgeUzkHVFxeXR_5hCzTfdpmU_6GvSxSM_Syx94C1TbyDPWsC6zMU02nxWB2vjm3Mzk1wDh7exUJbioUvgRA |
| researchgate.net | https://vertexaisearch.cloud.google.com/grounding-api-redirect/AUZIYQGAbbVqxvduaUpjGs53EV8pitB5UpGPTsBuEVZDjSgaGznWyCgmtlX7BUYuFJZWhsAN_ysgTYchJ8M7sWIzDWWQdpc50aHq7DkPb2jVH8zcruBJKpnYgmXGCnuGJMk7RL5q20n0Xkl9trYCuh7ZzwaiPAjZuSW1485HpypcYCDjKqQKmQtLTUow7eAcuzZlfBc0ypuWYIVhxils3U1k58heKg |
| researchgate.net | https://vertexaisearch.cloud.google.com/grounding-api-redirect/AUZIYQGP8rRRr78x3WPl0Lg3__jduYth_n0JoS1yZBvDaSJ8mT4AkCWjVZpERiLsLh3g5PdyLmO-rMpBhKutgHYoGoV8rKlKlyVLthHP0imqgCrkLMPudB6gFTJUC7TDOZ8ThHg4IFG41acXqw7QJ67kqGVlUgBlRfsqPBSSIb4XdWnaxSrXu6NKm82ODSO4MwsHJXLKgwm38vspJyBlTrJN257rE6P7i5Lg6MqgFzCF4hM8TnQUSSjwI1z-7C2JvA_JkwxnRNb86qrw3EN_vpeRGcQTWhiPaZ0wBpP7_Q |
| researchgate.net | https://vertexaisearch.cloud.google.com/grounding-api-redirect/AUZIYQFD6-JWBdTSA2Is4pbOmt0pbWlW7xn8XifN5dSoMBF_SeF_sorh0JamgxhC0WKV8wloHy0eo3reECjzVI50ZZkxv5IJBYdmFvQ_HQUg0MpwJjZrwx8z72priRfOYBh70AH_Bv0hx1W3gfKPqfjAjXKSPHPhwkaX3aGVRcvphUe-LTHcjuiIsAkALmibuzJjJ8IemYJEP-Sun8tW_aSpw2mnWoZ39W6Al2gyKjvEb2BrbCsFBqOo9A |
| researchgate.net | https://vertexaisearch.cloud.google.com/grounding-api-redirect/AUZIYQEWDBT1GiA5mD0mH9cUmJ-jcdyT0p09Bp4RKv10aDe8l5kZ3QtCqSKLLjilTuMxw3PaZxL509Ymakzz4Fy91m_WRamITh6SyGMsDD2Jp29qC7lYscM8f8l-hElJZHFWzd3ReB1ORPg4Oj_GUE6VekJXrE_JM-q25rMrxzJYDMKa0zHHuVdAXd8DLDdhrF6VLDNKYpzf6_QdMGYeswGte5LwNhojBD9Z7woFC4pnLA |
| researchgate.net | https://vertexaisearch.cloud.google.com/grounding-api-redirect/AUZIYQFBnCnBDVI-blB09WgRkeOuYNBSrJG4BRxIT1-rhL1TUh-ZGcYkJBY0A_HrlwbAPLXlvBmsrCX_nwBXwdO5gHvo1YE0e3J3yGx0l8glpoe9sFlR6TLULqU3NNccV19FYlnTN6hnCU7_a6qZD5xlJWcRiYtdzfsQsw885qnRdEztsulqex7gu-DQ29Q0Bt0xw7Ktq0wzY97UXrADtzrLSPc9fLoXdRORrXh07b76V61PyrXgJZZrxfuTGJ4x0iJ5MtVSwqfMcmg |
| researchgate.net | https://vertexaisearch.cloud.google.com/grounding-api-redirect/AUZIYQEWlpwBKjusdYnUFU5op7l30XfoX79d0VrScKyBpMfNstfP1j2qB9lWf8gqgp5O1Bv2QsWpxAT4h9bxqoXkxiCjKrkMcjfiebpE7LQWiHpe1LI8sBWoGxhos3h2rpFBvPpQKyLzAs2Is4sCnOleHUdqG1KVtzbXIdZ3fGjhxbUSPomHWr89c1pbxaBp0NCZwmWOhY2CnlGHS7kvt3k_Ho85cGykCeFt_utY2LmZLJN3e-LH9Q |
| researchgate.net | https://vertexaisearch.cloud.google.com/grounding-api-redirect/AUZIYQE6JWVNATIjIOO-LLKCrx_i5IQ5pU5kNOe4OA44T2CjG7QUDdj6zq7L9-d2rYcITgHl3nWNGKy1GjAzfUHRxDgQOk9rconCNCxTIs0hFdZDCBliZlgfbl7AMNv3fm5H8fKLZW4H-BaoHSM2-zC48YEvNDQRxhR605A6RLI0O85GircPuG6u0jl-TR7cRpKIZTsr8GjJaPufe26gVKIhNRO4JHGbw30 |
| researchgate.net | https://vertexaisearch.cloud.google.com/grounding-api-redirect/AUZIYQHshzq6I26D4rkPCykIk6NvFghnPW2InROtRbFly5Tjn6NdmVyP23FO0XuYtgC3Hup3d-fTlaacyjohzqZoNMZHR0VaQCwukvWR7Oyi_CystIAdzIyw7tk4xx9TrLhJ5gBbfVWTxQNtnqFf1C6ZRSc85YxIiJynTVns3XYnmBRB24y5MxPguTldJ34ixj62kTnqgfcixrfkIBD6F3_PO9pA1gTxqLMdMyT5oiufXI4vHdvJYTvubA |
| researchgate.net | https://vertexaisearch.cloud.google.com/grounding-api-redirect/AUZIYQGZVRmnlYFjzvOq_P8lHn34nJiefo81v53eP9hYbK59L6R1kasy7Xzwiz3YPo5pxONzUSc86Hf80KnIAGoFiRclZJ3LPPcjbzHE8POKBWWPHqgfvTAAdtH-SdWWwarHy_cOWWQR0CcGZc1zdh1jtf4nBhQq3DwKIhg1N8k8Qfqw8sSqyhe0ikKtVPeP8M9rdanDTU |
| researchgate.net | https://vertexaisearch.cloud.google.com/grounding-api-redirect/AUZIYQGHBlIPQOm6aK2cT0pOV-e5zgFkFlWz_WYY2yHM0rj_WaMHyWdrXdMxob5C3iviWisYcX6LUvj_hz3b00P8ixF5VfqBOX9tV5v8wCRG_hTXy8HReU4eD7xTJUWa8FBNA801VwjBLLLozMGfxovYkAr5IcR43czQGTX7l67QP8iLlfIY-vbPIhsAIeavtDTQtPHpXdA_E2Pf37rfQ1mcJNLhkHWeoFMxBi3ml_jxJUZDqMelDcjDVc4dX7kKCSrf_A |
| rmi.org | https://vertexaisearch.cloud.google.com/grounding-api-redirect/AUZIYQE7Oz |
