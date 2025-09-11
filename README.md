# Retail Sales Forecasting

## Overview
The **Retail Sales Forecasting** project applies machine learning and time series regression techniques to predict future sales in the retail domain.  
Accurate sales forecasts are crucial for **inventory management, marketing strategies, demand planning, and revenue optimization**.  

The project explores **Exploratory Data Analysis (EDA)**, **time series feature engineering**, **model building**, and **evaluation** to generate reliable sales forecasts.  

---

## Project Structure
- **Regression_Time_Series.ipynb**  
  - Data loading and cleaning  
  - Exploratory Data Analysis (EDA)  
  - Time series decomposition (trend, seasonality, residuals)  
  - Feature engineering (lag variables, rolling statistics, date features)  
  - Regression modeling for forecasting  
  - Model evaluation and diagnostics  
  - Visualization of actual vs predicted sales  

---

## Results
- Identified key **seasonality and trend components** in retail sales.  
- Built regression-based forecasting models.  
- Evaluated performance using:  
  - **MAE (Mean Absolute Error)**  
  - **RMSE (Root Mean Squared Error)**  
  - **R² Score**  
- Generated visualizations comparing forecasted and actual sales.  

---

## Installation & Requirements
Install the required dependencies before running the notebook:

```bash
pip install numpy pandas matplotlib seaborn scikit-learn statsmodels jupyter
