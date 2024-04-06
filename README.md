# crypto_analysis
Cryptocurrencies analysis project based on BTC,ETH,XRP,LTC --- using SARIMAX model
Cryptocurrencies have become increasingly popular as a unique investment option and a disruptive digital asset class. Their volatile price behavior poses both opportunities and challenges for traders and investors. To make informed decisions and develop effective trading strategies, analyzing historical price data is crucial. In this notebook, we'll perform exploratory data analysis (EDA) on a dataset containing cryptocurrency price information. Our objective is to visualize price trends, identify patterns, and explore relationships between different variables. The dataset includes columns such as 'Crypto', 'Date', 'Open', 'High', 'Low', 'Close', and additional features like 'Year', 'Month', 'Day', 'DayOfWeek', 'Quarter', and 'Season'.


What is Sarimax?
The Seasonal Autoregressive Integrated Moving Average with Exogenous Regressors (SARIMAX) model is a powerful time series forecasting technique that extends the traditional ARIMA model to account for seasonality and external factors. It’s a versatile model that can accommodate both autoregressive (AR) and moving average (MA) components, integrate differencing to make the data stationary, and incorporate external variables or regressors. SARIMAX is particularly valuable when dealing with time-dependent data that exhibits recurring patterns over specific time intervals.

Components of SARIMAX
Seasonal Component (S): Captures the periodic patterns in the data, such as weekly, monthly, or yearly cycles.
Autoregressive Component (AR): Represents the relationship between the current value and previous values in the time series.
Integrated Component (I): Involves differencing to make the time series stationary by removing trends and seasonality.
Moving Average Component (MA): Accounts for the dependency of the current value on past error terms, used to calculate trend.
Exogenous Regressors (X): Allows the inclusion of external variables that may affect the time series.
