# Refugees Needs Analysis Dashboard

## 📊 Overview

This repository contains a comprehensive **Refugees Needs Analysis Dashboard** built with **Microsoft Power BI**. The project, developed under the **DEPI (Data Analysis Using Power BI)** initiative, provides a deep dive into the living conditions, housing situations, and essential needs of refugee families across the Middle East and North Africa region.

The dashboard analyzes data from **1,701 families** across **4 countries** (Syria, Yemen, Iraq, and Libya) to help humanitarian organizations and stakeholders understand where aid is needed most.

**Last Update:** August 2025
**Author:** Shireen Talaat

---

## 🖼️ Dashboard Preview

### 1. Overview Page 
![overview.jpg](https://github.com/ShireenTalaat/Refugees-Needs-Analysis-Dashboard/blob/main/overview.jpg)
*Focuses on high-level KPIs, income distribution, and family demographics.*

### 2. Housing Page
![housing.jpg](https://github.com/ShireenTalaat/Refugees-Needs-Analysis-Dashboard/blob/main/housing.jpg)
*Analyzes geographic distribution, housing types, and family composition.*

### 3. Needs Page
![needs.jpg](https://github.com/ShireenTalaat/Refugees-Needs-Analysis-Dashboard/blob/main/needs.jpg)
*Breaks down specific needs: Food, Education, Clothes, and Money.*

### 4. Detailed Income & Demographics 
![refugees.jpg](https://github.com/ShireenTalaat/Refugees-Needs-Analysis-Dashboard/blob/main/refugees.jpg)
*Features a decomposition tree for income analysis and detailed gender/country splits.*

---

## 📑 Dashboard Sections

### 🏠 1. Overview
The main landing page provides a snapshot of the refugee crisis data.
*   **Key Metrics:**
    *   **Total Families:** 1,701
    *   **Total Cities:** 19
    *   **Total Countries:** 4 (Syria, Yemen, Iraq, Libya)
    *   **Avg. Family Size:** 7.00
    *   **Average Income:** $133.3
*   **Visualizations:**
    *   **Income by Family Size:** Area chart showing average income trends relative to family size.
    *   **Breadwinner Demographics:** Pie chart showing that **Fathers (66.41%)** are the primary breadwinners compared to Mothers (33.59%).
    *   **Income by Country:** Bar chart highlighting that **Syria ($54K)** and **Yemen ($53K)** have the highest total income sums, while Libya and Iraq are lower ($18K).
    *   **Income by City:** Funnel chart detailing income distribution across specific cities like Atma, Khantumun, and Ta'izz.

### 🏘️ 2. Housing Analysis
This section focuses on living conditions and shelter types.
*   **Map Visualization:** An interactive map (Azure Maps) showing refugee locations across the region (Syria, Yemen, Egypt, etc.).
*   **House Type by Breadwinner:** Stacked bar chart comparing housing types (Flat, Room, Tent, House) between Fathers and Mothers.
*   **Housing Distribution:** Pie chart showing **Rooms (36.86%)** and **Flats (34.51%)** are the most common housing types.
*   **Families with Children:** A detailed breakdown of housing types based on the age and gender of children (Under 5, 6-18).

### 🆘 3. Needs Analysis
This section identifies critical gaps in essential resources.
*   **KPIs:** Tracks binary needs (0/1) for Food, Education, Clothes, and Money.
*   **Sum of Need by Breadwinner & Country:** An area chart revealing massive spikes in needs for **Syria** and **Yemen**, particularly for Fathers.
*   **Needs by Category:** Four pie charts breaking down Food, Money, Clothes, and Education needs by country.
    *   *Observation:* Syria and Yemen consistently show the highest demand for Food and Money.
*   **Needs by Family Size:** A stacked bar chart showing how needs scale with family size (from 4 to 10 members). As family size grows to 6, the need for Education and Money peaks.

### 💰 4. Detailed Demographics & Income (Purple View)
A specialized view focusing on gender splits and income decomposition.
*   **Gender Split:** Total Females (5,395) vs. Total Males (6,510).
*   **Decomposition Tree:** A visual breaking down the **Total Income ($143,339)** by Country $\rightarrow$ House Type.
    *   *Insight:* Syria generates the most income ($54,464), primarily through Flats ($19,895).

---

##  Key Insights

1.  **Geographic Concentration:** The majority of the refugee population and critical needs are concentrated in **Syria** and **Yemen**.
2.  **Economic Disparity:** While Syria and Yemen have higher total income sums in the dataset, the average income per family remains low ($133.3), indicating a need for financial aid.
3.  **Housing Crisis:** The most common living situations are **Rooms (36%)** and **Flats (34%)**, with a significant portion living in **Tents (20%)**, highlighting the need for shelter support.
4.  **Breadwinners:** Fathers are the primary breadwinners in nearly two-thirds of the families (66%).
5.  **Critical Needs:** Food and Money are the most pressing needs, particularly for larger families (6+ members).

---

## 🛠️ Tools & Technologies

*   **Microsoft Power BI:** Dashboard development and visualization.
*   **DAX (Data Analysis Expressions):** Used for calculating KPIs (Total Income, Average Family Size).
*   **Power Query:** Data cleaning and transformation.
*   **Azure Maps / TomTom:** For geographic visualizations.

---
