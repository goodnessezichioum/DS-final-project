# DS-final-project

### Exploring Multivariate Socioeconomic Trends in Nigeria Using Machine Learning

## 1. Project Overview
This project investigates long-term socioeconomic trends in Nigeria using machine learning methods applied to World Bank Development Indicators (WDI) data.
The goal is to identify and forecast key development indicators through a multivariate analysis of economic, demographic, and trade variables spanning 1960–2024.

The study combines traditional regression and modern ensemble learning techniques to evaluate how different socioeconomic factors co-evolve and to predict short-term future outcomes.

---

## 2. Objectives
1. Explore multivariate relationships among socioeconomic indicators in Nigeria.
2. Develop predictive models for GDP growth
3. Evaluate and compare model performance across linear and tree-based models
4. Interpret feature importance to uncover dominant socioeconomic drivers.

---

## 3. Data Source
- **Dataset:** World Bank – World Development Indicators (WDI)
- **File:** `API_NGA_DS2_en_csv_v2_130484.zip`
- **Country:** Nigeria
- **Time range:** 1960–2024
- **Update date:** 6th January 2025
- **Variables:** ~1,500 indicators across economic, demographic, and environmental domains.

---

## 4. Methodology
1. **Data Cleaning & Preprocessing**
   - Handle missing values, select indicators with ≥25 years of continuous coverage (ending ≥2022).
   - Normalise and transform numeric features ( difference, percentage change).

2. **Exploratory Data Analysis (EDA)**
   - Assess indicator coverage and continuity.
   - Visualise long-term socioeconomic trends and correlations.
   - Identify potential predictor–target relationships.

3. **Modelling Approach**
   - **Linear Regression (Ridge)** – baseline interpretability.
   - **Random Forest** – non-linear feature interactions and variable importance.
   - **XGBoost** – high-performance gradient boosting for precise forecasting.

4. **Evaluation**
   - Metrics: RMSE, CV Ratio.
   - Real predictions extended to 2025–2026 for forecast validation.

---

## 6. Tools and Libraries
- Python
- Pandas, NumPy, Scikit-learn
- XGBoost
- Matplotlib, Seaborn

---

## 7. Citation
> The World Bank (2025). *World Development Indicators – Nigeria Dataset (API_NGA_DS2_en_csv_v2_130484)*.  
> Retrieved from: [https://data.worldbank.org/country/nigeria](https://data.worldbank.org/country/nigeria)
"""



