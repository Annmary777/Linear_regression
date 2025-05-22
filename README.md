# 🏡 Housing Price Prediction using Linear Regression

This project applies **Linear Regression** to predict housing prices based on several features such as location, age of the house, population, and income statistics. It is built using Python, scikit-learn, and statsmodels.

---

## 📁 Dataset

The dataset contains 17,000 rows and 9 columns, all numeric, with the target variable being `median_house_value`. The features include:
- `longitude`
- `latitude`
- `housing_median_age`
- `total_rooms`
- `total_bedrooms`
- `population`
- `households`
- `median_income`

---

## 🧠 Objective

Build a linear regression model to accurately predict house prices and evaluate it using R² score, coefficients, intercepts, and statistical summaries.

---

## 🛠️ Features

- Preprocess data (null check, train-test split)
- Train a `LinearRegression` model using scikit-learn
- Evaluate the model using:
  - R² Score
  - Coefficients & Intercept
  - Mean Squared Error (MSE)
  - OLS Statistical Summary using `statsmodels`
- Visual comparison of actual vs predicted prices

---

## 📦 Requirements

Install required libraries using:

```bash
pip install -r requirements.txt
