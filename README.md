# 📊 Sales Forecasting with Linear Regression

## 📝 Overview

This project uses Linear Regression to forecast future sales based on historical shampoo sales data. It demonstrates how simple machine learning models can uncover sales trends and provide business insights using time-series data.

---

## 📌 Problem Statement

Businesses often struggle to estimate future sales based on past performance. This project aims to address that challenge by building a regression model that predicts upcoming sales using historical monthly sales data.

---

## 🎯 Objectives

- Load and preprocess real-world time-series sales data.
- Apply Linear Regression to build a forecasting model.
- Predict future sales values.
- Visualize both actual and predicted sales.
- Forecast sales for the next 6 months.

---

## 📁 Dataset

- **Source**: [Shampoo Sales Dataset](https://raw.githubusercontent.com/jbrownlee/Datasets/master/shampoo.csv) by Jason Brownlee
- **Features**:
  - `Month`: Time period (e.g., 1-01, 1-02, ...)
  - `Sales`: Number of units sold

---

##📈 Output
-Graph: Actual vs Predicted Sales

-Table: Actual vs Predicted values

-Metric: RMSE (Root Mean Squared Error)

-Forecast: Sales prediction for the next 6 months

-Graph: Future Forecasted Sales

##🔮 Sample Forecast Output
-Month	Forecasted Sales
-2004-01	500.21
-2004-02	513.32
-2004-03	526.42

##📚 Learnings
-How to handle time-series data for regression

-Importance of avoiding data shuffling in time-series problems

-How to evaluate regression models using RMSE

-How to use linear models for simple business forecasting tasks
