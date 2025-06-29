# -TimeSeries-Analysis-of-Ethereum-ETH-USDT-using-ARIMA
This project focuses on forecasting Ethereum's (ETH) closing prices using time series modeling techniques. The core objective is to build a statistical model that can predict future price movements and evaluate its performance based on historical data.
 Project Overview
Dataset: Historical Ethereum daily closing prices from 2021 to mid-2025

Model Used: ARIMA(0,1,1) with log transformation

Training Period: Jan 2021 to Mar 2024

Testing Period: Mar 2024 to Jun 2025

Evaluation Metrics: RMSE, MAPE

🛠 Key Components
Data Preprocessing: Log transformation and differencing to ensure stationarity

Model Training: ARIMA model fitted on the last 1500 days of data

Forecasting: Out-of-sample prediction for over 12 months

Visualization: Comparison of forecasted prices vs actual test data

Error Analysis:

RMSE ≈ 897

MAPE ≈ 27.3%

Observations: The ARIMA model produced a flat forecast, failing to capture high volatility in Ethereum prices.

📉 Limitations
Model underfit the test data due to lack of reactivity to market fluctuations

ARIMA may not be suitable for highly volatile assets like cryptocurrencies

✅ Future Improvements
Integrate SARIMA, GARCH, or LSTM models for improved performance

Incorporate external features like volume, market sentiment, or macro indicators

Use rolling forecasts to simulate real-world prediction scenarios

📊 Visualization

Ethereum Forecast vs Actual using ARIMA(0,1,1) — flat forecast despite volatile actual trend (can be used further and fixed by SARIMA model) 
