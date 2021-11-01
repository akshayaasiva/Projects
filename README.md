The goal of this project is to analyse and interpret business needs and requirements of a data visualization application with various functions. It creates a program which helps to compare the Relative Strength Index(RSI) values of different stocks over a customised period of time. 

This project aims to understand the rising needs of clients to compare the performances through the Relative Strength Index (RSI) of different stocks.

There is a need to build a charting software application that addresses the needs of the investment clients as shown.

The investment clients are given the following options:
1. Decide on the number of stocks between 1 to 10 stocks that they want to review
2. Select the required stocks based on their ticker value accordingly. For simplicity, 10 stocks are chosen here which they can choose from accordingly: "FB", "AAPL", "AMZN", "IBM", "GOOGL", "MSFT", "F", "O", "QCOM", "TSLA".
3. The software uses an API provider, which can be customised to retrieve the daily “Close” price for each equity.
4. The software then computes the RSI of the selected stocks with the following options: 
5. The client can decide the between two methods: Exponential Weighted Moving Average(EWMA) & Smooth Moving Average(SMA.)
6. The client can set the Moving Window range value
7. The client can customize the duration for plotting of the starting and finishing date, where they can choose a time period between 1st Jan 2010 to 31st Dec 2017.
8. The software then plots the charts based on the information provided by the client.

Prerequisites:
Jupyter Notebook, 
Python
