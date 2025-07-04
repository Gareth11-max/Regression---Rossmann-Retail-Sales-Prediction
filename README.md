# 🧮 Regression: Rossmann Retail Sales Prediction

A machine learning project to predict daily sales for Rossmann stores using historical data and store-specific factors. The goal is to develop a regression model that accurately forecasts sales, helping optimize inventory, staffing, and promotional planning.

---

## 📝 Project Description

Rossmann operates over 1,100 drug stores across several European countries. Accurate sales forecasting is crucial for efficient store operations, inventory control, and business planning. This project involves building a regression-based predictive model using historical sales data along with additional variables such as promotions, holidays, and store information.

Using machine learning techniques like XGBoost and Random Forest, this project aims to predict daily sales and uncover key drivers influencing store performance.

---

## 🎯 Objectives

- Predict daily sales for each store using historical data.
- Identify key factors affecting sales (e.g., promotions, holidays).
- Build and evaluate multiple regression models.
- Improve business decision-making with accurate sales forecasts.

---

## 🗃️ Dataset Overview

- **Source**: Kaggle Rossmann Store Sales Dataset  
  https://www.kaggle.com/competitions/rossmann-store-sales
- **Key Files**:
  - `train.csv` – Historical daily sales data
  - `test.csv` – Store and date information for prediction
  - `store.csv` – Store-level metadata (e.g., competition, promo info)

- **Features**:
  - Store ID, Date, Sales, Customers, Promo, StateHoliday, SchoolHoliday
  - CompetitionDistance, Promo2, PromoInterval, StoreType, Assortment

---

## 🛠️ Tools & Technologies

- Python (Pandas, NumPy, Scikit-learn)
- Machine Learning: XGBoost, Random Forest, Linear Regression
- Data Visualization: Matplotlib, Seaborn
- Jupyter Notebook

---

## 🔍 Key Steps

1. Data Cleaning & Feature Engineering
2. Exploratory Data Analysis (EDA)
3. Time-Series Trends & Seasonality Checks
4. Model Training & Hyperparameter Tuning
5. Model Evaluation using RMSE and R²
6. Feature Importance Analysis

---

## 📈 Model Performance

| Model             | RMSE     | R² Score |
|------------------|----------|----------|
| XGBoost Regressor| 1123.4   | 0.87     |
| Random Forest     | 1250.7   | 0.84     |
| Linear Regression | 1567.8   | 0.72     |

✅ **XGBoost** gave the best performance and is recommended for deployment.

---

## 📌 Business Insights

- **Promotions** significantly impact sales, especially during holidays.
- **Store competition distance** influences local demand.
- **StoreType** and **Assortment** are important predictors of store performance.
- **School and state holidays** lead to observable dips/spikes in sales.

---


