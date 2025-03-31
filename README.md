# 📈 Future Sales Prediction – Machine Learning Project

This project predicts future sales using various regression models. The workflow includes data cleaning, exploratory data analysis, feature engineering, and model evaluation using multiple algorithms in Google Colab.

## 📁 Files

- `Future_Sales_Prediction.ipynb` – Complete notebook containing all steps from EDA to model training.
- `sales_dataset.csv` – Input dataset used for training.

## 🔍 Problem Statement

The goal is to predict the `Item_Outlet_Sales` for products across different store types using historical sales data and features like item type, MRP, outlet size, etc.

## 🧠 Techniques Used

- Data preprocessing (handling missing values, label encoding, one-hot encoding)
- Exploratory Data Analysis with Seaborn and Matplotlib
- Feature engineering (`Outlet_Years`, fat content simplification)
- Regression Models:
  - Linear Regression
  - Ridge & Lasso
  - Decision Tree
  - Random Forest
  - Support Vector Regressor (SVR)
  - XGBoost

## 📊 Evaluation

- Models evaluated using **Root Mean Squared Error (RMSE)** and **R² Score**
- Best performing models: **Ridge Regression** and **Linear Regression**

## ▶️ Run in Colab

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Aniket381/Future_Sales_Prediction/blob/main/Future_Sales_Prediction.ipynb)

## 🚀 Future Improvements

- Hyperparameter tuning for better performance
- Time-series modeling based on sales trends
- Deployment as a Streamlit web app

## 🔗 Project Link

[https://github.com/Aniket381/Future_Sales_Prediction](https://github.com/Aniket381/Future_Sales_Prediction)
