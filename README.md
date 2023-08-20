# Cryptocurrency Price Prediction

This project was developed during a 36 hour hackathon.
Developed a web application using python (Flask framework) that predicts the day’s closing price of 5 leading cryptocurrencies. 
Historical price data from past 5+ years (Opening, closing and average prices of each day) are used to build an ML model (Ensemble model to improve accuracy). 
A sentimental analysis on current news regarding the given currency is performed to generate a sentiment score. Historical data + Sentiment score factor into the prediction of closing price for the currency.

Historical data is extracted from Yahoo Finance using YFinance API in Python
Sentimental Analysis for the selected cryptocurrencies on news concerning the last 7 days is done using TextBlob library in Python.

Ensemble Model takes into account the historical data and results of the sentimental analysis.

This project was developed by team Mavericks - C B Ananya, Ayshwarya B, Sathvika V S

