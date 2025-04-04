# 🚗 Real-World EV and Grid Storage Field Datasets

This section lists real-world battery usage datasets (mainly for EVs or grid storage conditions):

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
---
- **RWTH M5BAT Large-Scale Battery Storage System Dataset (unlabeled)**
  - 📍 *Chemistry*: Lead-acid, LMO, LFP, LTO
  - 🧪 *Test Type*: Field (Grid-scale hybrid stationary storage system)
  - 🔋 *Battery Format*: 10 battery units (Pb, LMO, LFP, LTO); 6.19 MW / 7.78 MWh system
  - 📄 *Summary*: Operational data from a 10-unit 6.2 MW hybrid battery system in Germany. Includes high-frequency (1Hz) measurements such as active/reactive power, SOC, voltage, current, inverter modes, and grid signals. Designed for FCR service, including performance data across technologies. Data spans April 2023 and is part of ongoing evaluations.
  - 📅 *Year*: 2023 (report published 2024)
  - 🔗 [Download Dataset](https://doi.org/10.18154/RWTH-2024-04895)
  - 📚 *Related Reports*:  
    - *M5BAT Large-Scale Battery Storage System Dataset: Evaluation Operation Report 04/2023*
    - [M5BAT Research Portal](https://m5bat.isea.rwth-aachen.de/Projekt/Forschungsergebnisse/)
---
- **RWTH Commercial Fleet EV Battery Dataset**
  - 📍 *Chemistry*: Lithium-ion (EV application)
  - 🧪 *Test Type*: Field (Multi-year real-world EV operation and battery aging)
  - 🔋 *Battery Format*: EV battery packs (9 vehicles, 2014–2016 field test)
  - 📄 *Summary*: Dataset includes time-series data from onboard loggers of 9 electric vehicles operating in commercial geriatric care fleets in Germany. It features vehicle mobility patterns, driving behavior, state-of-charge, plug-in timing, and battery capacity fade data over 3 years. Batteries experienced 3.1–13% capacity fade. Also includes non-intrusive capacity test data from chassis dynamometer.
  - 📅 *Year*: 2024 (Data from 2014–2016)
  - 🔗 [Download Dataset](https://publications.rwth-aachen.de/record/979878/files/Electric_Vehicle_and_Battery_Data.zip)
  - 📚 *Related Article*:  
    - [Battery Electric Vehicles in Commercial Fleets: Use profiles, battery aging, and open-access data (J. Energy Storage, 2024)](https://doi.org/10.1016/j.est.2024.111030)
---

- **Retired Lithium-Ion Batteries Dataset**
  - 📍 *Chemistry*: Lithium-ion (mixed, second-life modules)
  - 🧪 *Test Type*: Field data (retired batteries with real-world charging segments)
  - 🔋 *Battery Format*: Mixed (EV-grade retired modules)
  - 📄 *Summary*: Dataset includes massive real-world charging segments used for estimating capacity in retired lithium-ion batteries. Enables state-of-health inference without full discharge testing. Useful for second-life applications and battery recycling logistics.
  - 📅 *Year*: 2025
  - 🔗 [Download Dataset](https://zenodo.org/records/14562266)
  - 📚 *Related Article*:  
    - [Capacity estimation using random charging segments (Cell Reports Physical Science, 2025)](https://doi.org/10.1016/j.xcrp.2025.102444)
---
- **Multi-Modal EV SOH Dataset (Nature Communications, 2025)**
  - 📍 *Chemistry*: NCM and LFP
  - 🧪 *Test Type*: Field (Real-world EV fleet)
  - 🔋 *Battery Format*: Full EV packs, 96 cell modules
  - 📄 *Summary*: Data collected over 3 years from 300 EVs operating under diverse and random usage conditions. Dataset includes full drive-cycle discharge data and charging data. Health indicators (HIs) include 2D voltage maps (96 cells), 1D charge capacity sequences, and 15 statistical parameters (e.g. mileage, current, temperature). Enables training of deep multimodal SOH estimation models.
  - 📅 *Year*: 2025
  - 🔗 [Download Dataset](http://ivstskl.changan.com.cn/?p=2697)
  - 💾 [Code on GitHub](https://github.com/HoraceLiu1010/Multi-modal-SOH-estimation-framework)
  - 📚 *Related Article*:  
    - [Multi-modal framework for battery state of health evaluation using open-source electric vehicle data (Nature Communications)](https://doi.org/10.1038/s41467-025-56485-7)
---
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
---      
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

---

- **On-Road EV Charging Dataset (BAIC EU500, CATL NCM)**
  - 📍 *Chemistry*: NCM
  - 🧪 *Test Type*: Field (Commercial EV fleet)
  - 🔋 *Battery Format*: 90 cells in series, 145Ah, with 32 temperature sensors
  - 📄 *Summary*: Charging data collected over 29 months from 20 BAIC EU500 EVs equipped with CATL NCM battery packs. Data recorded via CAN every 8 seconds during charging. Used for battery capacity prognostics via Seq2Seq + GPR models. Includes raw data and code for capacity estimation.
  - 📅 *Year*: Published 2023
  - 🔗 [Download Dataset](https://doi.org/10.1016/j.apenergy.2023.120954)
  - 📚 *Related Article*:  
    - [Prognostics of battery capacity based on charging data and data-driven methods for on-road vehicles (Applied Energy)](https://doi.org/10.1016/j.apenergy.2023.120954)

---

- **BMS Fault Diagnosis Dataset (Model-Constrained Deep Learning)**
  - 📍 *Chemistry*: Lithium-ion (EV-grade, mixed manufacturers)
  - 🧪 *Test Type*: Field (Vehicle onboard BMS data, cloud-aggregated)
  - 🔋 *Battery Format*: EV modules from DTI, QAS, GIS (anonymized)
  - 📄 *Summary*: Dataset includes 18.2 million entries from 515 EVs collected via cloud-based BMS systems. Contains both normal operation data and four rare critical fault types: thermal runaway, electrolyte leakage, internal short circuit, and excessive aging. Used for deep learning-based online fault diagnosis under stochastic real-world conditions.
  - 📅 *Year*: 2025
  - 🔗 [Download Dataset](https://zenodo.org/records/10656500)
  - 📚 *Related Article*:  
    - [Model-constrained DL for fault diagnosis (Nature Communications, 2025)](https://doi.org/10.1038/s41467-025-56832-8)
---

- **EV Real-World Driving Cycle Aging Dataset**
  - 📍 *Chemistry*: Lithium-ion
  - 🧪 *Test Type*: Lab (Real-world EV driving profiles)
  - 🔋 *Battery Format*: Cylindrical (INR21700-M50T cells)
  - 📄 *Summary*: Dataset includes aging data for lithium-ion battery cells subjected to Urban Dynamometer Driving Schedule (UDDS) discharge profiles and CC-CV charging, simulating realistic EV conditions. Monitors capacity fade, HPPC, and EIS across a 28-month testing period.
  - 📅 *Year*: 2022
  - 🔗 [Download Dataset]([https://www.sciencedirect.com/science/article/pii/S2352340922002062?via%3Dihub](https://osf.io/qsabn/?view_only=2a03b6c78ef14922a3e244f3d549de78)
  - 📚 *Related Article*:  
    - [Lithium-ion battery aging dataset based on EV real-world driving cycles (Data in Brief, 2022)](https://doi.org/10.1016/j.dib.2022.107995)

---

- **Realistic Fault Detection Dataset for Li-ion Batteries**
  - 📍 *Chemistry*: Lithium-ion
  - 🧪 *Test Type*: Field (Real-world EV operation, anomaly detection)
  - 🔋 *Battery Format*: EV battery packs (347 vehicles)
  - 📄 *Summary*: Dataset contains over 690,000 real-world charging snippets collected from 347 electric vehicles. Designed for evaluating safety conditions and enabling fault detection in Li-ion batteries using deep learning techniques. Supports benchmarking of anomaly detection algorithms under realistic conditions.
  - 📅 *Year*: 2024
  - 🔗 [Download Dataset](https://zenodo.org/record/10656500) *(example placeholder)*
  - 📚 *Related Article*:  
    - *Realistic fault detection of Li-ion battery via dynamical deep learning approach (Nature Communications, 2024)(https://doi.org/10.1038/s41467-023-41226-5)
