# Stock Forecasting Model

This project implements a stock forecasting model using time series analysis techniques. The model is built using historical stock price data and aims to predict future stock prices.

## Steps Involved

1. **Data Visualization**: The stock prices are visualized over time to identify trends and patterns.
2. **Stationarity Check**: The Augmented Dickey-Fuller (ADF) test is used to check if the time series is stationary.
3. **Decomposition**: The time series is decomposed into trend, seasonality, and residual components.
4. **Handle Missing Values**: If there are missing values, they are handled appropriately (e.g., interpolation, forward fill).
5. **Transform the Data**: If necessary, transformations (e.g., differencing, logarithmic) are applied to stabilize variance and make the series stationary.
6. **Model Selection**: A suitable time series model (e.g., ARIMA) is chosen based on the characteristics of the data.
7. **Model Fitting**: The selected model is fitted to the data.
8. **Model Diagnostics**: The residuals of the model are checked to ensure they are white noise.
9. **Forecasting**: The fitted model is used to make forecasts for future stock prices.
10. **Model Evaluation**: The forecasts are compared with actual values (if available) using metrics like RMSE or MAE.
11. **Model Saving**: The trained model is saved for future use.

## Requirements

- Python 3.x
- pandas
- matplotlib
- statsmodels
- scikit-learn
- joblib

## Usage

To run the stock forecasting model, ensure you have the required libraries installed. You can install them using pip:

```bash

pip install pandas matplotlib statsmodels scikit-learn joblib
```

Then, run the script:

```bash

python stock_forecasting.py
```

This will execute the time series analysis and forecasting steps, and save the trained model as `stock_model.pkl`.

## Author

Abdirazak Mubarak

## Date

Aug 14, 2025
