# DS-final-project

# 📊 Workforce Optimization and Prediction Using Machine Learning

This project presents a full end-to-end data science pipeline for workforce optimization and incident risk prediction. It simulates realistic operational data from a technical services company and explores how predictive models can support strategic decisions in workforce planning, safety, and resource deployment.

---

## 🔍 Project Overview

In many industries, optimizing workforce allocation and predicting potential health and safety risks are crucial for efficiency, cost-effectiveness, and employee wellbeing. This project explores how machine learning can be applied to:

- Predict likelihood of workplace incidents based on workforce and project data.
- Identify key drivers of high-risk work environments.
- Support strategic HR decisions with data-driven insights.

---

## 🛠️ Key Features

- 💡 **Realistic Dataset**: Synthetic dataset modeled after real-world structures (staff records, HSE incidents, project logs, equipment, and materials).
- 🧹 **Data Preprocessing**: Missing values, outliers, and temporal inconsistencies handled.
- 🔎 **Exploratory Data Analysis**: Visual insights into workforce trends, safety incidents, and resource usage.
- 🤖 **Machine Learning Models**: Supervised models like Random Forest and XGBoost applied for prediction tasks.
- 📈 **Performance Evaluation**: Accuracy, precision, recall, and feature importance metrics.
- 📊 **Dashboard-Ready Outputs**: Clean datasets and predictions suitable for visualization in Power BI or Tableau.

---

## 📁 Folder Structure
📦Workforce-Optimization-Project
├── data/
│ ├── Workforce.csv
│ ├── HSE.csv
│ ├── Projects.csv
│ ├── Equipment_Log.csv
│ └── Materials.csv
├── notebooks/
│ ├── 01_data_cleaning.ipynb
│ ├── 02_eda.ipynb
│ ├── 03_modeling.ipynb
│ └── 04_results_and_dashboard.ipynb
├── models/
│ ├── random_forest_model.pkl
│ └── xgboost_model.pkl
├── visuals/
│ ├── eda_charts/
│ └── model_performance/
├── README.md
└── requirements.txt


---

## 📊 Dataset Description

| Table             | Description                                                                 |
|------------------|-----------------------------------------------------------------------------|
| `Workforce`       | Staff profiles with employment details, man hours, and contract timelines   |
| `HSE`             | Health, Safety & Environment incidents linked to staff and project activity |
| `Projects`        | Project lifecycle data including duration, status, and location             |
| `Equipment_Log`   | Equipment tracking and deployment status                                    |
| `Materials`       | Material inventory, condition, type, and warehouse details                  |

---

## 🤖 Models Used

| Model           | Use Case                                | Reason for Selection                      |
|----------------|------------------------------------------|-------------------------------------------|
| Random Forest   | Incident prediction                     | High interpretability, handles imbalance  |
| XGBoost         | Model comparison for prediction tasks   | Fast, regularized, often better accuracy  |






