# Recurrent Neural Network to Predict Stock Prices
Recurrent Neural Network to Predict Tesla Stock Prices (TensorFlow and Keras)

## Background
This study is based on a paper from Stanford University.

http://cs229.stanford.edu/proj2012/BernalFokPidaparthi-FinancialMarketTimeSeriesPredictionwithRecurrentNeural.pdf

## Data

https://finance.yahoo.com/quote/TSLA/history?p=TSLA

## Introduction

Recurrent Neural Networks are excellent to use along with time series analysis to predict stock prices. What is time series analysis? Time series analysis comprises methods for analyzing time series data in order to extract meaningful statistics and other characteristics of the data. Time series forecasting is the use of a model to predict future values based on previously observed values.
An example is this. Would today affect the stock prices of tomorrow? Would last week affect the stock prices of tomorrow? How about last month? Last year? Seasons or fiscal quarters? Decades? Although stock advisors may have different opinions, recurrent neural networks uses every single case and finds the best method to predict.

Problem: Client wants to know when to invest to get largest return in 2017.

Data: 5 years of Tesla stock prices. (2012-2017)

Solution: Use recurrent neural networks to predict Tesla stock prices in 2017 using data from 2012-2016.

## Steps
* Data Visualization
* Data Preprocessing
* Building the Recurrent Neural Network
* Making Predictions and Visualizing the Results
