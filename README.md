# 🦟 Where Environment Meets Disease
### A Bivariate Analysis of Malaria Prevalence in Nigeria

**Tools:** QGIS · Spatial Analysis · Bivariate Mapping  
**Author:** Tiwa Daodu  
**Domain:** Public Health GIS · Environmental Epidemiology

---

## 📌 Project Overview

This project explores the **spatial relationship between temperature and malaria prevalence** across all 36 Nigerian states using QGIS. By layering two variables onto a single bivariate map, the analysis uncovers how environmental conditions interact with disease burden — going beyond a simple prevalence map to reveal *why* certain regions are more affected.

**Core Question:** Do states with higher temperatures show higher malaria prevalence?

---

## 🗺️ Map 1 — Malaria Prevalence by State

![Map 1 - Malaria Prevalence](Map%201_Malaria_Prevalence.png)

**Key Findings:**
- Northern states carry the highest malaria burden — **Kebbi (75.6%)** and **Yobe (62.5%)** top the list
- Southern states like **Lagos (3.2%)** and **Kwara (17.6%)** show significantly lower prevalence
- A clear **north-south gradient** is visible, likely driven by environmental and healthcare access differences

---

## 🌡️ Map 2 — Bivariate Analysis: Malaria Prevalence vs Temperature

![Map 2 - Bivariate Analysis](Map%202_Malaria_Prevalence_Updated.png)

**Key Findings:**
- **High–High combinations dominate the north**, confirming a positive spatial association between temperature and malaria prevalence
- **Borno** is a notable outlier — high temperature but low malaria prevalence (18.6%), possibly explained by its arid climate limiting mosquito breeding habitats and the impact of ongoing security challenges on population movement
- Southern coastal states cluster in **Low–Low** combinations, consistent with lower transmission

---

## 💡 Methodology

| Step | Description |
|------|-------------|
| Data Collection | State-level malaria prevalence and temperature data for Nigeria |
| Classification | Both variables classified into 3 tiers (Low / Medium / High) |
| Bivariate Mapping | Combined classification rendered as a 9-class colour scheme in QGIS |
| Interpretation | Spatial patterns analysed against environmental and socioeconomic context |

---

## 📂 Repository Structure

```
├── Map 1_Malaria_Prevalence.png          # Choropleth map of malaria prevalence
├── Map 1_Malaria_Prevalence.pdf
├── Map 2_Malaria_Prevalence_Updated.png  # Temperature vs prevalence bivariate map
├── Map 2_Malaria_Prevalence_Updated.pdf
├── Map 1-Malaria Prevalence.qgz          # QGIS project file — Map 1
├── Bivariate analysis showing M_prevalence.qgz   # QGIS project file — Map 2
├── QGIS project-Tiwa Daodu.pptx          # Full project presentation
└── README.md
```

---

## 🔍 How to Open the QGIS Project

1. Install [QGIS](https://qgis.org/en/site/forusers/download.html) (version 3.x recommended)
2. Clone or download this repository
3. Open either `.qgz` file directly in QGIS
4. Ensure data layers are linked correctly — re-path if needed via **Layer Properties**

---

## 🧠 Broader Context

While temperature is a significant driver, this project acknowledges that malaria prevalence is also shaped by:
- Access to healthcare facilities
- Population density and movement
- Water management and drainage infrastructure
- Poverty and socioeconomic conditions

This analysis serves as a **starting point** for understanding the spatial epidemiology of malaria in Nigeria, with temperature as the environmental proxy.

---
## ✅ Recommendations

### Policy Recommendations

**1. Prioritise Vector Control in High-Burden Northern States**
States like Kebbi (75.6%), Yobe (62.5%), and Zamfara (59.7%) urgently need scaled-up vector control measures. Evidence from Nigeria's National Malaria Elimination Programme supports expanding Indoor Residual Spraying (IRS) and achieving universal coverage of Long Lasting Insecticidal Nets (LLINs) across high-burden northern states, where seasonal malaria transmission is most intense between April and October.

**2. Expand Seasonal Malaria Chemoprevention (SMC)**
Mathematical modelling of Nigeria's 2021–2025 National Malaria Strategic Plan projects the greatest reduction in malaria burden when SMC is expanded significantly beyond its current reach. Given the strong north-south prevalence gradient identified in this analysis, SMC expansion should be prioritised in the North-West and North-East geopolitical zones.

**3. Strengthen Healthcare Infrastructure in High-Temperature, High-Prevalence Zones**
The High–High clusters identified in the bivariate analysis (states with both high temperature and high malaria prevalence) indicate areas where healthcare access is most critical. Increasing diagnostic equipment and primary health facility coverage in these zones would improve early case detection and reduce progression to severe malaria.

### Research Recommendations

**4. Incorporate Additional Environmental Variables**
Future analysis should extend beyond temperature to include rainfall, humidity, and proximity to water bodies — all of which influence mosquito breeding habitats. A multivariate spatial model would produce a more comprehensive picture of environmental drivers of malaria in Nigeria.

**5. Investigate the Borno Anomaly at a Finer Scale**
Borno's unusually low malaria prevalence (18.6%) despite high temperatures is a compelling outlier worth deeper investigation. A local government area (LGA)-level analysis incorporating security data, population displacement, and healthcare access could help explain this pattern and inform targeted interventions in conflict-affected regions.

---

## 👤 About the Author

**Tiwa Daodu** — GIS Analyst & Healthcare Data Analyst  
📧 *daodutiwaloluwa@gmail.com*  
🔗 *linkedin.com/in/tiwaloluwadaodu31*  
🌍 Lagos, Nigeria

