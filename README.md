# Predictive-Sales-Forecasting

## Project Overview

This project focuses on predicting sales using historical store sales data and Machine Learning techniques. The goal is to analyze sales patterns, identify key factors influencing sales, and build a predictive model that can estimate future sales with good accuracy.

---

## Objective

The objective of this project is to:

* Analyze historical sales data
* Identify trends and patterns in sales
* Understand the impact of promotions and holidays on sales
* Build a Machine Learning model for sales prediction
* Evaluate model performance using standard metrics

---

## Dataset

The dataset contains the following features:

| Feature | Description                   |
| ------- | ----------------------------- |
| date    | Date of sale                  |
| store   | Store identifier              |
| promo   | Promotion status              |
| holiday | Holiday indicator             |
| sales   | Total sales (Target Variable) |

---

## Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Scikit-learn
* Google Colab
* GitHub

---

## Project Workflow

### 1. Data Loading

* Imported dataset using Pandas
* Explored dataset structure

### 2. Data Cleaning

* Checked for missing values
* Verified data types
* Prepared data for analysis

### 3. Exploratory Data Analysis (EDA)

* Sales Trend Analysis
* Sales Distribution Analysis
* Promotion Impact Analysis
* Holiday Impact Analysis

### 4. Feature Engineering

Created additional features from the date column:

* Year
* Month
* Day
* Day of Week

### 5. Model Building

Implemented:

* Random Forest Regressor

### 6. Model Evaluation

Performance Metrics:

* Mean Absolute Error (MAE): **4.99**
* Root Mean Squared Error (RMSE): **6.37**

---

## Key Insights

* Promotional activities significantly influence sales.
* Sales patterns vary across stores and time periods.
* Date-related features improve prediction performance.
* The Random Forest model achieved strong predictive accuracy.

---

## Results

The trained model successfully predicted sales with low error values, demonstrating its effectiveness for sales forecasting tasks.

| Metric | Value |
| ------ | ----- |
| MAE    | 4.99  |
| RMSE   | 6.37  |

---

## Project Structure

```text
Predictive-Sales-Forecasting/
│
├── data/
│   └── store_sales.csv
│
├── notebook/
│   └── Sales_Forecasting.ipynb
│
├── images/
│   ├── sales_trend.png
│   ├── sales_distribution.png
│   ├── feature_importance.png
│
├── README.md
├── requirements.txt
└── report.pdf
```

---

## Future Improvements

* Implement advanced forecasting models such as XGBoost and LSTM.
* Deploy the model using Streamlit.
* Create an interactive Power BI dashboard.
* Perform hyperparameter tuning for improved accuracy.

---

## Author

**Harikrishnan K**

Data Analytics Internship Project

2026
