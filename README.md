# 🏠 California Housing Price Prediction 📊

A simple machine learning project to predict median house values in California 

# 📌 Project Overview

This project performs:
- **Data Cleaning & Preprocessing**
- **Exploratory Data Analysis (EDA)**
- **Feature Engineering**
- **Linear Regression Model Building**
- **Model Evaluation using MAE, MSE, and R²**
- **Visualization of Predictions and Coefficients**

## 📊 Dataset Description

- **Source:** California Housing Dataset [https://www.kaggle.com/datasets/camnugent/california-housing-prices]
- **Attributes:**
  - `longitude`
  -  `latitude`
  - `total_rooms`
  -  `total_bedrooms`
  - `population`
  -  `households`
  - `median_income`
  - `ocean_proximity` (categorical)
  - `median_house_value` (target variable)

# 📈 Workflow Summary

1. **Load Data**
2. **Clean Data**
   - Drop missing values
3. **Exploratory Data Analysis (EDA)**
   - Check distributions, correlations, and outliers
4. **Train-Test Split**
   - 80% training, 20% testing
5. **Preprocessing**
   - Log transformations for skewed numerical features
   - One-hot encoding for categorical variables
   - Feature engineering (`bedroom_ratio`, `household_rooms`)
   - Align train and test data
6. **Model Training**
   - Linear Regression
7. **Model Evaluation**
   - R² Score
   - Mean Absolute Error (MAE)
   - Mean Squared Error (MSE)
8. **Results Visualization**
   - Actual vs Predicted scatter plot
   - Coefficient importance plot
     
# 📊 Model Evaluation Metrics

- **Mean Absolute Error (MAE):** measures average absolute difference between actual and predicted values.
- **Mean Squared Error (MSE):** penalizes larger errors more than MAE.
- **R² Score:** indicates model performance (closer to 1 is better).




