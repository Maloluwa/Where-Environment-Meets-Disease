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

![Map 1 - Malaria Prevalence](maps/Map 1_Malaria_Prevalence.png)

**Key Findings:**
- Northern states carry the highest malaria burden — **Kebbi (75.6%)** and **Yobe (62.5%)** top the list
- Southern states like **Lagos (3.2%)** and **Kwara (17.6%)** show significantly lower prevalence
- A clear **north-south gradient** is visible, likely driven by environmental and healthcare access differences

---

## 🌡️ Map 2 — Bivariate Analysis: Malaria Prevalence vs Temperature

![Map 2 - Bivariate Analysis](maps/Map2_Bivariate_Analysis.png)

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
├── maps/
│   ├── Map1_Malaria_Prevalence.png       # Choropleth map of malaria prevalence
│   ├── Map1_Malaria_Prevalence.pdf
│   ├── Map2_Bivariate_Analysis.png       # Temperature vs prevalence bivariate map
│   └── Map2_Bivariate_Analysis.pdf
├── qgis/
│   ├── Map1_Malaria_Prevalence.qgz       # QGIS project file — Map 1
│   └── Bivariate_Analysis.qgz            # QGIS project file — Map 2
├── presentation/
│   └── QGIS_Project_Tiwa_Daodu.pptx      # Full project presentation
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

## 👤 About the Author

**Tiwa Daodu** — GIS Analyst & Healthcare Data Analyst  
📧 *daodutiwaloluwa@gmail.com*  
🔗 *linkedin.com/in/tiwaloluwadaodu31*  
🌍 Lagos, Nigeria

