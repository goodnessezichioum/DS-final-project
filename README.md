# DS-final-project

readme_content = """# Exploring Multivariate Socioeconomic Trends in Nigeria Using Machine Learning

## 1. Project Overview
This project investigates long-term socioeconomic trends in Nigeria using machine learning methods applied to World Bank Development Indicators (WDI) data.
The goal is to identify and forecast key development indicators through a multivariate analysis of economic, demographic, and trade variables spanning 1960–2024.

The study combines traditional regression and modern ensemble learning techniques to evaluate how different socioeconomic factors co-evolve and to predict short-term future outcomes.

---

## 2. Objectives
1. Explore multivariate relationships among socioeconomic indicators in Nigeria.
2. Develop predictive models for key indicators (e.g., GDP per capita, CPI, urbanisation rate).
3. Evaluate and compare model performance across linear, tree-based, and neural approaches.
4. Interpret feature importance to uncover dominant socioeconomic drivers.

---

## 3. Data Source
- **Dataset:** World Bank – World Development Indicators (WDI)
- **File:** `API_NGA_DS2_en_csv_v2_130484.zip`
- **Country:** Nigeria
- **Time range:** 1960–2024
- **Update date:** 07 October 2025
- **Variables:** ~1,500 indicators across economic, demographic, and environmental domains.

---

## 4. Methodology
1. **Data Cleaning & Preprocessing**
   - Handle missing values, select indicators with ≥25 years of continuous coverage (ending ≥2022).
   - Normalise and transform numeric features (log, difference, percentage change).

2. **Exploratory Data Analysis (EDA)**
   - Assess indicator coverage and continuity.
   - Visualise long-term socioeconomic trends and correlations.
   - Identify potential predictor–target relationships.

3. **Modelling Approach**
   - **Linear Regression (Ridge, Lasso)** – baseline interpretability.
   - **Random Forest** – non-linear feature interactions and variable importance.
   - **XGBoost** – high-performance gradient boosting for precise forecasting.

4. **Evaluation**
   - Chronological **train/test split** (train: up to 2022; test: 2023–2024).
   - Metrics: RMSE, MAE, MAPE, directional accuracy.
   - Real predictions extended to 2025–2027 for forecast validation.

---

## 6. Tools and Libraries
- Python
- Pandas, NumPy, Scikit-learn
- XGBoost, TensorFlow/Keras (for LSTM)
- Matplotlib, Seaborn, SHAP

---

## 7. Key Findings (to be updated after analysis)
- Indicators with the most continuous coverage: population, CPI, trade, reserves, urbanisation.
- Expected relationships: rising urbanisation correlates with GDP growth and CPI acceleration.
- Machine learning models (especially XGBoost) are expected to outperform linear baselines for short-horizon forecasts.

---

## 9. Citation
> The World Bank (2025). *World Development Indicators – Nigeria Dataset (API_NGA_DS2_en_csv_v2_130484)*.  
> Retrieved from: [https://data.worldbank.org/country/nigeria](https://data.worldbank.org/country/nigeria)
"""

# Write README.md file
with open("README.md", "w", encoding="utf-8") as f:
    f.write(readme_content)


