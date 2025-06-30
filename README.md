# Soil Carbon Trend Analysis by Region
The goal of this project is to analyze soil carbon data from 5 Indian regions (2023–2024) to identify where regenerative practices had the most impact. Used Python to explore trends by region, season, crop, and method. Applied statistical tests to validate changes, supporting Varaha’s MRV process and carbon credit strategy.

---

## Objective

To determine where regenerative farming practices have shown the most improvement in soil carbon content, and to generate actionable insights for Varaha ClimateAg's MRV (Monitoring, Reporting, and Verification) process.

---

## Dataset Overview

The dataset contains:
- Soil carbon percentages at different depths (15cm, 30cm, 45cm)
- Farm IDs, crop types, districts, and regions
- Measurement methods (manual vs remote vs mixed)
- Sampling season and date (Rabi/Kharif 2023–2024)
- Field notes and conditions

---

## 🧰 Tools & Libraries

- **Python:** Pandas, NumPy, Seaborn, Matplotlib, Scipy, Statsmodels
---

## 📊 Key Analyses Performed

- Regional trends in soil carbon % over time
- Seasonal comparison: Rabi 2023 vs Kharif 2024
- Crop-type impact on soil health
- Depth-wise consistency of soil carbon levels
- Statistical testing:
  - Independent t-tests (e.g., manual vs remote)
  - Linear regression (year-wise trend modeling)
  - Correlation analysis (depth vs carbon %)
- Outlier detection and quality check via remarks field

---

## Business Questions Answered

- Which regions show the highest average soil carbon % and which show the lowest?
- How has soil carbon changed over time in each region (Rabi 2023 to Kharif 2024)?
- Which crop types are associated with the greatest improvements in soil carbon %?
- How consistent are measurements at different soil depths (15 cm vs. 30 cm vs. 45 cm)?
- Are there outlier farms with unusually low soil carbon levels? What conditions were noted in remarks?
- Which districts saw the most improvement from Rabi 2023 to Rabi 2024?
- How do smallholder carbon trends differ by crop type and method?
- What percentage of the total farms sampled are meeting the ideal carbon threshold (e.g., >0.6%)?

---

## Sample Insights

- Punjab and Madhya Pradesh showed the most consistent gains in soil carbon %.
- Wheat and rice crops were associated with higher soil health improvements.
---

## Deliverables

- ✅ Cleaned dataset (`CSV`)
- ✅ Python notebook (`.ipynb`) with full analysis and plots
---

## 🚀 Skills Demonstrated

- Data Cleaning & Preprocessing  
- Exploratory Data Analysis (EDA)  
- Statistical Validation (t-test, ANOVA, Regression)  
- Dashboard Building in Power BI  
- Business-Oriented Insight Generation  
---

## 📌 Project Outcome

This project enables data-driven targeting for regenerative agriculture programs and supports Varaha’s climate reporting with validated insights. The methodology is scalable and can be extended to integrate geospatial or yield data for deeper impact forecasting.
