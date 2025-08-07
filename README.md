# ev-insights-washington-bigdata

# Electric Vehicle Insights: Washington State | Big Data & Predictive Analytics

Final Project for ALY-6110: Data Management & Big Data  
**Professor**: Daya Rudhramoorthi  
**Date**: 06/30/2023  
**Group Members**: Anoushka Hazari, Xuanyu Bao  

---

## 📌 Project Overview

This project leverages big data analytics to uncover key insights into the electric vehicle (EV) population in Washington state. Using a dataset provided by the Washington State Department of Licensing, we conducted a detailed exploration and predictive modeling of EV trends, with the objective of promoting sustainable transportation and understanding the factors influencing EV adoption.

---

## 📊 Business Problem

We aim to address several key business questions:
- How did the COVID-19 pandemic affect EV adoption?
- Which companies dominate the EV market and why?
- What factors influence the popularity of top EV models?
- What are the fastest and highest performing EVs in Washington?
- How do MSRP, model year, and range affect adoption patterns?
- What regional differences exist in EV adoption?
- How can rivalry between top 5 EV models boost statewide EV adoption?

---

## 📂 Dataset

- **Source**: [Electric Vehicle Population Data - data.wa.gov](https://catalog.data.gov/dataset/electric-vehicle-population-data)
- **Size**: ~130,000 rows × 17 columns
- **Attributes**: Make, Model, Year, Electric Range, VIN, License Plate, County, etc.

---

## ⚙️ Methodology

1. **Data Cleaning**: Python (pandas) was used to preprocess the data: renaming columns, removing missing values, and basic statistical exploration.
2. **EDA & Visualization**: Tableau dashboards provided dynamic insights into temporal, geographic, and manufacturer-related trends.
3. **Modeling**: Regression models (Random Forest & Gradient Boosting) were built to predict EV model year using electric range.
4. **Evaluation**: Model performance was measured using MSE and Accuracy metrics.
5. **Insights**: Combined dashboard visuals and model outputs to derive actionable insights for stakeholders.

---

## 📈 Visualizations

Two Tableau dashboards were developed:

### Dashboard 1:
- Trend of EV registrations over time
- Top 10 EV manufacturers
- Histogram of top 5 EV models
- Range and performance analysis
- MSRP vs model year insights

### Dashboard 2:
- Sales performance by model and manufacturer
- EV type distribution
- Geographic and county-level adoption
- Rivalry among top EV models

> 📸 *See screenshots in the `/screenshots/` folder*

---

## 🧠 Modeling Summary

| Model                  | MSE   | Accuracy |
|-----------------------|-------|----------|
| Random Forest Regressor | 1.16  | 86.94%   |
| Gradient Boosting Regressor | 1.306 | 85.29%   |

- **Input (X)**: Electric Range  
- **Target (y)**: Model Year  

---

## 📌 Tools & Technologies

- **Languages**: Python (pandas, sklearn)
- **Visualization**: Tableau
- **Libraries**: pandas, matplotlib, sklearn
- **IDE**: Jupyter Notebook

---

## 📬 Key Insights

- EV adoption increased significantly during the pandemic.
- Tesla and Nissan lead the market due to high range and reliability.
- Top EV models exhibit strong brand loyalty and regional dominance.
- Electric range is a strong predictor of model year evolution.
- Regional disparities suggest opportunity for targeted marketing and incentives.

---

## 🚀 Conclusion

This project successfully utilized big data analytics and predictive modeling to analyze Washington’s EV population. Our findings provide actionable insights for manufacturers, policymakers, and sustainability advocates to enhance EV adoption and improve infrastructure planning.

---

## 📚 References

- [Electric Vehicle Population Dataset](https://catalog.data.gov/dataset/electric-vehicle-population-data)
- Tableau Documentation: [Calculated Fields](https://help.tableau.com/current/pro/desktop/en-us/calculations_calculatedfields_formulas.htm)
- GeeksForGeeks: [Random Forest Regression](https://www.geeksforgeeks.org/random-forest-regression-in-python/)
- VitalFlux: [Gradient Boosting Example](https://vitalflux.com/gradient-boosting-regression-python-examples/)

---

---

## 👥 Authors

- Anoushka Hazari  
- Xuanyu Bao

---



