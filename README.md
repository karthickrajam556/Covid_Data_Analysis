# Covid_Data_Analysis

# 🦠 COVID-19 Data Analysis & Prediction Pipeline

## 📌 Project Overview
This project delivers **end-to-end COVID-19 data analytics** by combining **big data processing**, **machine learning prediction**, and **interactive dashboard visualization**.

The goal is to:
- Process and clean large-scale COVID-19 datasets.
- Generate key statistical insights.
- Predict COVID-19 deaths based on multiple features.
- Present findings through an interactive Power BI dashboard.

---

## 🚀 Features
- **Big Data Processing (PySpark)**
  - Cleans and filters massive datasets for reliable analysis.
  - Computes global statistics, mortality, and recovery rates.
- **Machine Learning Prediction (Scikit-learn)**
  - Trains a Linear Regression model to predict deaths from confirmed/recovered cases.
  - Evaluates performance with R², RMSE, and MAE metrics.
- **Interactive Dashboard (Power BI)**
  - Displays global trends, top affected countries, and key rates.
  - Interactive filters for exploring regions and time periods.

---

## 🛠️ Tech Stack
| Component             | Technology Used |
|-----------------------|-----------------|
| Big Data Processing   | PySpark         |
| Data Analysis         | Pandas, NumPy   |
| Machine Learning      | Scikit-learn    |
| Visualization         | Power BI        |

---

## 📂 Project Structure
📁 Covid_Analysis_Project
├── covid_analysis_task_1.py # PySpark-based big data analysis
├── covid_analysis_task_2.py # Machine learning prediction
├── Covid_Dashboard_Task-3.pbix # Power BI dashboard
└── README.md # Project documentation

---

## 📊 Workflow
```mermaid
graph LR
    A[Big Data Processing<br>(PySpark)] --> B[Machine Learning<br>Prediction<br>(Scikit-learn)]
    B --> C[Interactive Dashboard<br>(Power BI)]



