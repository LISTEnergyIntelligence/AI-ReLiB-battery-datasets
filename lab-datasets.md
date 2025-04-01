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
