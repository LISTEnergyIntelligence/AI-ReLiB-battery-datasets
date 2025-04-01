# 🧪 Laboratory Battery Test Datasets

A curated list of lab-tested lithium-ion battery datasets used for aging studies, cycle life, SoH estimation, and EoL prediction.

---

- **NASA PCoE Dataset**
  - 🧪 *Chemistry*: NCA
  - 🔋 *Cell Type*: Cylindrical
  - ⚡ *Profile*: CC–CV charge, CC discharge
  - 📈 *Trend*: Linear capacity fade
  - 📅 *Year*: 2008
  - 🔗 [Link](https://ti.arc.nasa.gov/tech/dash/groups/pcoe/prognostic-data-repository/)

---

- **CALCE Dataset**
  - 🧪 *Chemistry*: LCO
  - 🔋 *Cell Type*: Prismatic
  - ⚡ *Profile*: CC–CV charge, CC discharge at various rates
  - 📈 *Trend*: Sub-linear to super-linear
  - 📅 *Year*: 2014
  - 🔗 [Link](https://web.calce.umd.edu/batteries/data.htm)

---

- **Oxford Dataset 1**
  - 🧪 *Chemistry*: NCA
  - 🔋 *Cell Type*: Pouch
  - ⚡ *Profile*: CC–CV charge with dynamic discharges (urban drive)
  - 📈 *Trend*: Linear
  - 📅 *Year*: 2017
  - 🔗 [Link](https://ora.ox.ac.uk/objects/uuid:03ba4b01-cfed-46d3-9b1a-7d4a7bdf6fac)

---

- **Stanford (Severson) Dataset**
  - 🧪 *Chemistry*: LFP
  - 🔋 *Cell Type*: Cylindrical
  - ⚡ *Profile*: Multi-step fast charge, CC discharge
  - 📈 *Trend*: Super-linear
  - 📅 *Year*: 2019
  - 🔗 [Link](https://data.matr.io/1/projects/5c48dd2bc625d700019f3204)

---

- **RWTH Dataset**
  - 🧪 *Chemistry*: NMC
  - 🔋 *Cell Type*: Cylindrical
  - ⚡ *Profile*: CC–CV charge, CC discharge
  - 📈 *Trend*: Super-linear
  - 📅 *Year*: 2021
  - 🔗 [Link](https://git.rwth-aachen.de/isea/battery-degradation-trajectory-prediction)
- **Continual Learning Battery Aging Dataset**
  - 📍 *Chemistry*: Various (Pouch and prismatic Li-ion cells)
  - 🧪 *Test Type*: Lab (Accelerated and non-accelerated aging)
  - 🔋 *Battery Format*: Pouch and Prismatic
  - 📄 *Summary*: Includes partial Q curves during charging, normalized capacity and SoH trends for different battery types under varied conditions. Dataset supports research into continual learning for generalizable battery health estimation. Dataset 5 includes full raw degradation data.
  - 📅 *Year*: 2023
  - 🔗 [Download Dataset](https://data.mendeley.com/datasets/n3b54nsw8m/9)
  - 📚 *Related Article*:  
    - [Continual learning for generalizing battery health estimation (Cell Reports Physical Science, 2023)](https://doi.org/10.1016/j.xcrp.2023.101743)
- **Galvanostatic Discharge Dataset (C-rates & Temperature Tests)**
  - 📍 *Chemistry*: Lithium-ion (specific chemistry not specified)
  - 🧪 *Test Type*: Lab (Galvanostatic discharge under controlled conditions)
  - 🔋 *Battery Format*: Not specified (3 cells tested)
  - 📄 *Summary*: Dataset includes voltage, current, and skin temperature data from three lithium-ion batteries subjected to various C-rates and temperatures in a thermal chamber. Measurements taken using Arbin system under constant current discharge protocols.
  - 📅 *Year*: 2021
  - 🔗 [Download Dataset](https://data.mendeley.com/datasets/kxsbr4x3j2/2)
  - 📚 *Related Article*:  
    - [Experimental discharge dataset (Data in Brief, 2021)](https://doi.org/10.1016/j.dib.2021.106894)
- **Li-ion Battery Aging Dataset (EV Real-Driving Profiles)**
  - 📍 *Chemistry*: NMC (INR21700-M50T)
  - 🧪 *Test Type*: Lab (Realistic EV simulation)
  - 🔋 *Battery Format*: 21700 Cylindrical Cells
  - 📄 *Summary*: 28-month dataset collected at Stanford Energy Control Lab using UDDS drive cycle discharge and CC-CV charging. Includes periodic HPPC and EIS diagnostics to assess battery aging under EV-realistic conditions.
  - 📅 *Year*: 2022
  - 🔗 [Download Dataset](https://osf.io/qsabn/?view_only=2a03b6c78ef14922a3e244f3d549de78)
  - 📚 *Related Articles*:
    - [Dataset publication (Data in Brief, 2022)](https://doi.org/10.1016/j.dib.2022.107995)
    - [Domain knowledge-guided ML for SoH estimation (Nature Computational Science, 2024)](https://doi.org/10.1038/s44172-024-00304-2)

- **Full Factorial DOE Dataset for Parallel-Connected Li-ion Cells**
  - 📍 *Chemistry*: NCA and NMC
  - 🧪 *Test Type*: Lab (Module-level experimental design)
  - 🔋 *Battery Format*: Ladder-configured parallel strings
  - 📄 *Summary*: Experimental data from a full factorial DOE on parallel-connected Li-ion modules, including 54 conditions spanning cell chemistry, interconnection resistance, temperature, and aging. Measurements include per-cell current and temperature to study variation effects on performance. Cell characterization data included.
  - 📅 *Year*: 2024
  - 🔗 [Download Dataset](https://data.mendeley.com/datasets/zh58byr53c/1)
  - 📚 *Related Article*:  
    - [Unveiling the performance impact of module level features on parallel-connected lithium-ion cells (EST, 2024)](https://doi.org/10.1016/j.est.2024.110783)

- **Lithium-Ion Battery Formation & Structured Aging Dataset**
  - 📍 *Chemistry*: Not specified (Li-ion cells, BEEP-compatible)
  - 🧪 *Test Type*: Lab (Formation and aging cycling)
  - 🔋 *Battery Format*: Cylindrical (assumed from TRI BEEP context)
  - 📄 *Summary*: Includes raw formation data and structured aging cycling data using the BEEP format. Provides interpolated cycling data and summarized metrics to study the impact of electrode utilization on cycle life extension.
  - 📅 *Year*: 2024
  - 🔗 [Download Dataset](https://data.matr.io/8/)
  - 📚 *Related Article*:  
    - [Data-driven analysis of battery formation reveals the role of electrode utilization in extending cycle life (Joule, 2024)](https://www.cell.com/joule/abstract/S2542-4351(24)00353-2)

- **Second-Life Li-ion Battery Grid Storage Dataset**
  - 📍 *Chemistry*: NMC
  - 🧪 *Test Type*: Lab (Grid storage simulation for second-life cells)
  - 🔋 *Battery Format*: Pouch cells (6 second-life cells)
  - 📄 *Summary*: Dataset of second-life NMC cells tested using residential and commercial synthetic duty cycles. Experiments conducted at Stanford Energy Control Lab to simulate realistic grid storage applications. Data available in .zip format.
  - 📅 *Year*: 2024
  - 🔗 [Download Dataset](https://osf.io/8jnr5/)
  - 📚 *Related Article*:  
    - [Second-life lithium-ion battery aging dataset based on grid storage cycling (Data in Brief, 2024)](https://doi.org/10.1016/j.dib.2024.111046)

- **Battery Failure Databank**
  - 📍 *Chemistry*: Various (Li-ion: 18650, 21700, D-cell formats)
  - 🧪 *Test Type*: Abuse Testing (Thermal runaway, nail penetration, internal short circuit)
  - 🔋 *Battery Format*: Cylindrical and D-cell
  - 📄 *Summary*: Open-access dataset from hundreds of abuse tests conducted at ESRF, DLS, and NASA JSC. Includes calorimetry (heat breakdown by cell body vs ejected material), mass loss, and radiographic video data. Extensive data on thermal runaway dynamics for a wide range of commercial lithium-ion cells with varied abuse triggers. Organized by cell type, method, and metadata-rich spreadsheet.
  - 📅 *Year*: Updated February 2024
  - 🔗 [Download Dataset](https://www.nasa.gov/battery-failure-databank) *(exact link placeholder)*
  - 📚 *Related Articles*:  
    - *The Battery Failure Databank: Insights from an Open-Access Database of Thermal Runaway Behaviors of Li-Ion Cells*, Journal of Power Sources (2024)
    - *Decoupling of Heat Generated from Ejected and Non-Ejected Contents of 18650 Cells*, Journal of Power Sources (2019)
    - *Internal Short Circuit Characterization and Radiography*, Energy & Environmental Science (2017), Advanced Science (2017), JES (2017)
"""
