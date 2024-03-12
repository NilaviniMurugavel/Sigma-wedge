SIGMA INTERNSHIP CODING CHALLENGE

Overview
This repository hosts code for constructing a basic stock trading model leveraging Quantrocket.
The goal is to develop a strategy that optimizes portfolio performance by making informed decisions on specific days.
The model focuses on Apple Inc. (AAPL) stock using historical price data from 2023.

Getting Started
Start by setting up Quantrocket on your local environment or preferred cloud platform.
Clone this repository to your local machine to access the code.

Dependencies
 
Quantrocket
pandas
matplotlib
PyPortfolioOpt
statsmodels

 
Data Retrieval
The code retrieves daily closing price data for AAPL stock in 2023 from Quantrocket.

Data Preprocessing
The retrieved price data is organized into a pandas DataFrame with 'Date' as the index and 'FIBBG000B9XRY4' (closing price) as the sole column.

Data Visualization
Matplotlib is used to create visualizations of AAPL's closing prices for the year 2023, aiding in understanding price trends.

Calculations and Analysis
Daily percentage returns are calculated based on closing price changes.
Portfolio optimization techniques like Efficient Frontier and Discrete Allocation are applied to maximize portfolio value.
Forecasting via the ARIMA model predicts future price movements.
State classification categorizes states into Bull, Flat, or Bear based on returns.
Buy/sell signals are determined to optimize portfolio value by leveraging state transitions.

