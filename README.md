# FAANG Stock Price Time Series Analysis

## Project Overview
This project analyzes the historical adjusted closing prices of FAANG stocks (Facebook/Meta, Amazon, Apple, Netflix, Google) from June 2012 to June 2020. Using statistical and machine learning techniques, we examine stock trends, seasonality, and interdependencies to build predictive models.

## Key Features
- **Data Preprocessing**: Log transformation and differencing to handle non-stationarity.
- **Univariate Modeling**: ARIMA and SARIMA models to capture stock-specific trends.
- **Multivariate Modeling**: Vector AutoRegression (VAR) to explore causal relationships between stocks.
- **Baseline Comparison**: Evaluating performance against a Random Walk model.

## Results
- The **Random Walk model** outperformed SARIMA and VAR models in forecasting accuracy.
- Granger causality tests revealed significant interdependencies among FAANG stocks.
- While SARIMA and VAR models captured complex relationships, they struggled against the high volatility of stock prices.

## Technologies Used
- Python (Pandas, NumPy, SciPy, Statsmodels, Matplotlib)
- Time Series Modeling (ARIMA, SARIMA, VAR)
- Financial Data Analysis
