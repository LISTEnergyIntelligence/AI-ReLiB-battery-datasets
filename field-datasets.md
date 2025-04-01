# 🚗 Real-World EV Field Datasets

This section lists real-world battery usage datasets (mainly for EVs or emulated EV conditions):

---
- **RWTH Multi-Year Home Storage Dataset (unlabeled)**
  - 📍 *Chemistry*: Not specified (Residential ESS)
  - 🧪 *Test Type*: Field
  - 🔋 *Battery Format*: Home storage systems
  - 📄 *Summary*: 21 residential PV-coupled battery systems in Germany, measured over 8 years (2015–2022); includes current, voltage, power, housing and room temperature at 1s resolution. Total: 14B data points, 106 system-years.
  - 📅 *Year*: 2022
  - 🔗 [Download Dataset](https://zenodo.org/records/12091223)
  - 📚 *Related Articles*:
    - *Multi-year field measurements of home storage systems and their use in capacity estimation*
    - *Nature Energy, DOI 10.1038/s41560-024-01620-9* 

- **LFP Battery Systems Field Dataset**
  - 📍 *Chemistry*: LFP
  - 🧪 *Test Type*: Field (Returned units)
  - 🔋 *Battery Format*: 24V Systems, 8 prismatic cells in series
  - 📄 *Summary*: 28 LFP battery systems with nominal 160Ah capacity; used in RVs, solar storage, etc. Data spans 1 month to 5 years per system, totaling 133 million rows. Includes cell voltages, temperatures (shared), load current, and active balancing behavior. All units were returned due to perceived faults, introducing bias.
  - 📅 *Year*: Not specified (Field period ~5 years)
  - 🔗 [Download Dataset](https://zenodo.org/records/13715694)
  - 📚 *Related Article*:  
    - *Gaussian Process-based Online Health Monitoring and Fault Analysis of Lithium-Ion Battery Systems from Field Data*  
      *(Cell Reports Physical Science, DO 10.1016/j.xcrp.2024.102258)*
      
- **EVBattery Dataset (labeled)**
  - 📍 *Chemistry*: NMC (Mixed)
  - 🧪 *Test Type*: Field (Real-world EV usage)
  - 🔋 *Battery Format*: EV Pack
  - 📄 *Summary*: 1.2M charging sessions from 464 EVs across 3 manufacturers
  - 📅 *Year*: 2023
  - 🔗 [Link to Dataset](https://figshare.com/articles/dataset/EVBattery_A_Large-Scale_Electric_Vehicle_Dataset_for_Battery_Health_and_Capacity_Estimation/23301881)

---

- **Off-Grid Solar Field Dataset (unlabeled)**
  - 📍 *Chemistry*: Lead-Acid
  - 🧪 *Test Type*: Field
  - 🔋 *Battery Format*: Solar off-grid systems
  - 📄 *Summary*: Field data from 1,027 lead-acid batteries powering lighting, phone charging, and small appliances in sub-Saharan Africa. Useful for studying SoH, runtime, and predicting end-of-life.
  - 📅 *Year*: Published 2021
  - 🔗 [Download Dataset](https://ora.ox.ac.uk/objects/uuid:e41d3d4c-f74e-4d76-81fd-0caa77ec6cec)
  - 📚 *Related Article*:  
    - [Predicting battery end of life from solar off-grid system field data using machine learning (Joule)](https://www.cell.com/joule/fulltext/S2542-4351(21)00532-8)
"""

---

- **Jaguar Land Rover (JLR) Fleet Dataset**
  - 📍 *Chemistry*: NMC
  - 🧪 *Test Type*: Field (proprietary)
  - 🔋 *Battery Format*: EV Pack
  - 📄 *Summary*: Real-world usage and SoH monitoring of commercial EV fleet (not publicly available)
  - 📅 *Year*: 2022
  - 🔗 Not publicly released
