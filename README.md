# ARIMA-for-stock-price-prediction

# Description:
ARIMA (AutoRegressive Integrated Moving Average) is a classic time series forecasting technique, ideal for stationary datasets. It combines:

* **AR**: dependency on past values

* **I**: differencing to remove trends

* **MA**: dependency on past forecast errors

We’ll use ARIMA to forecast future stock prices based on historical closing data.

# ✅ What It Does:
* Downloads real stock data using yfinance

* Fits an ARIMA model to historical closing prices

* Forecasts the next 30 business days

* Visualizes both historical data and the forecasted trend

