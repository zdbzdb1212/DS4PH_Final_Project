# DS4PH_Final_Project
Final project for Data Science for PH and BME

https://zdbzdb1212.shinyapps.io/Predictive_Growth_Crypto/


## General Description

Our team decided to create a tool that would aid in predicting the values of various cryptocurrencies through a number of methods. Alexander was in charge of collecting the data, manipulating it into a usable time series format, and applying the Facebook prophet model to forecast currencies in the near future. Zach then took that same time series data and applied a basic ARIMA random walk method to create a range of values in which the currencies could be reasonably expected to remain between. Upon outside research as to cyclical and stationary time series, Zach then chose to perform and ACF and PACF on each time series to determine if any of the currencies had any interesting properties that could make prediction less accurate. Finally, Talal trained, validated, and implemented a random forest classifier that takes in current data and predicts the closing value of bitcoin the following day to aid in prediction and decisions regarding the management of bitcoin in an extremely volatile market.


