# 🏠 House Price Prediction using Linear Regression

This repository contains a complete solution for predicting house prices using **simple and multiple linear regression** models. The dataset is taken from the [Housing Price Prediction Dataset on Kaggle](https://www.kaggle.com/datasets/harishkumardatalab/housing-price-prediction).

## 📌 Objectives
✅ Implement simple & multiple linear regression  
✅ Preprocess dataset: handle categorical and numerical features  
✅ Evaluate using MAE, MSE, RMSE, and R²  
✅ Plot regression line for simple regression  
✅ Interpret model coefficients

---

## 🔢 Dataset

The dataset contains features like:
- **Numeric:** area, bedrooms, bathrooms, stories, parking, etc.
- **Categorical:** mainroad, guestroom, basement, airconditioning, furnishing status, etc.
- **Target:** price (house price)

---

## 🛠️ Steps Implemented

1. **Import & Preprocess Data**
   - Loaded CSV using Pandas.
   - Handled missing values.
   - Converted categorical features to numeric using one-hot encoding.
2. **Train-Test Split**
   - Split data into training and testing sets with 80/20 ratio.
3. **Modeling**
   - **Simple Linear Regression**: Used `area` alone to predict `price`.
   - **Multiple Linear Regression**: Used all features to predict `price`.
4. **Evaluation**
   - Metrics used: MAE, MSE, RMSE, R².
   - Observed significant improvement in multiple regression over simple regression.
5. **Plot**
   - Plotted regression line for simple linear regression.
6. **Coefficient Interpretation**
   - Printed intercept and coefficients for both models to interpret feature impact.

---

## 📊 Results

### 🔹 Simple Linear Regression (Area → Price)
- **R²**: 0.27 → Model explains ~27% variance.
- **MAE**: ₹1.47 million
- **MSE**: 3.68×10¹²
- **RMSE**: ₹1.92 million

### 🔹 Multiple Linear Regression (All Features → Price)
- **R²**: 0.65 → Model explains ~65% variance.
- **MAE**: ₹0.97 million
- **MSE**: 1.75×10¹²
- **RMSE**: ₹1.32 million

---

## 🧠 Key Learnings
- Importance of data preprocessing (especially encoding categorical features).
- Simple linear regression can provide insights, but multiple features improve predictive performance.
- Metrics like R² and RMSE help compare model performance effectively.

---

## 📚 Requirements

- Python 3.x
- Libraries: pandas, numpy, matplotlib, seaborn, scikit-learn

---
