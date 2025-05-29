# Rossmann Store Sales Forecasting

This project is based on the [Rossmann Store Sales](https://www.kaggle.com/competitions/rossmann-store-sales) Kaggle competition. The goal is to forecast daily sales for a large retail chain using time series analysis and machine learning techniques.

## 📌 Project Tasks

### 1.  Perform Data Analysis
- Time series decomposition (trend, seasonality, residuals)
- Autocorrelation and partial autocorrelation (ACF/PACF)
- Stationarity testing (ADF test)
- Rolling statistics and smoothing techniques

### 2.  Apply Simple Forecasting Models
Evaluated using the same metric as the competition (Root Mean Squared Percentage Error - RMSPE):
- Naive Forecast
- Moving Average
- Weighted Moving Average

### 3.  Apply ETS Models (Error-Trend-Seasonal)
- Simple Exponential Smoothing (SES)
- Holt’s Linear Trend Method
- Holt-Winters’ Seasonal Method

### 4.  Apply ARIMA Model
- Stationarity tests (ADF)
- Parameter selection using ACF/PACF plots
- Fitting ARIMA/SARIMA models
- Forecasting and model evaluation

### 5.  Apply Prophet Model
- Forecasting using Facebook's Prophet
- Handling seasonality and holiday effects
- Visualizing forecast components
- Model evaluation on validation set

### 6.  Apply Machine Learning Models
- Train-test split and model training
- Applied models:
  - Random Forest Regressor
  - XGBoost Regressor
  - CatBoost Regressor
- Model evaluation using RMSPE


