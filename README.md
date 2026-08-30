# BTC Regression

This is a simple machine learning project created for practice and educational purposes.

The main goal of this project is to practice working with real-world time-series data and compare different regression models for predicting the next-day Bitcoin closing price.

## Models
- Linear Regression
- Ridge Regression
- Lasso Regression

## Features
Historical BTC-USD data is used along with several engineered features:
- Previous Close
- Daily Return
- 7-Day Moving Average
- 30-Day Moving Average
- 7-Day Volatility
- High-Low Range
- Open-Close Difference

## Evaluation
The models are evaluated using:
- MAE
- RMSE

The data is split chronologically to preserve the time-series structure.

## Note
This project was developed as a learning exercise to practice regression, feature engineering, time-series data handling, and model evaluation.

It is not intended for real-world Bitcoin price forecasting, trading, or financial advice.
