# Bitcoin Price Prediction Using Simple Moving Average and Naive Methods
# Introduction
The rise of cryptocurrencies has led to an increasing interest in predicting the prices of these digital assets. Bitcoin, the first and most popular cryptocurrency, has experienced significant price fluctuations over the years. In this project, we aim to predict the future price of Bitcoin using naive method and  simple moving average forecasting methods with different window sizes. The objective of this project is to compare the performance of these methods and analyze their results.
# Data
Data is available in github repo.
# Naive Method
This is the very basic method just to explain process.
# Simple Average Forecast
Simple average forecast is a basic forecasting method used to identify trends in data. It involves taking the average of the historical data and using it to predict future values. Simple average forecast can be useful for identifying the general direction of a trend in data. It is often used as a baseline or starting point for more sophisticated forecasting methods. However, it may not be suitable for data with a lot of variability or seasonality, as it does not take into account any patterns or cycles in the data.

In our project we are using Simple Average Forecast  to see the trends in data and forecasting.
We implemented several simple moving average forecasting methods with different window sizes to predict the future prices of Bitcoin. The methods used are:

3-month moving average
06-month moving average
12-month moving average

We trained these models on the historical data and used them to make predictions about future Bitcoin prices.

# Results
We evaluated the performance of the simple moving average methods and the naive method using  mean absolute percentage error, (MAPE) and root mean squared error (RMSE). The MSE and RMSE for each method are shown below:

