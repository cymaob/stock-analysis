# Stock Analysis Notebook

This repository contains a Jupyter notebook that analyzes the performance of Tesla and Volkswagen stocks, comparing their daily returns, cumulative returns, volatility, and beta relative to the S&P 500 index.

## Overview

The notebook begins by importing necessary libraries such as pandas, yfinance, and plotly for data manipulation, financial data retrieval, and data visualization respectively. It then specifies the ticker symbols for Tesla and Volkswagen, along with the desired date range for the analysis.

The notebook then downloads the historical market data for these stocks and the S&P 500 index using the yfinance library. It calculates the daily return for each stock, which is the percentage change in the adjusted closing price from one day to the next.

The notebook then proceeds to calculate the cumulative return for each stock, which is the total return from the beginning of the period to the current date. This is followed by the calculation of the volatility for each stock, which is a measure of the dispersion of the stock's returns.

Finally, the notebook calculates the beta for each stock relative to the S&P 500 index. Beta is a measure of a stock's risk in relation to the market. The notebook then compares the betas of Tesla and Volkswagen to determine which stock is more volatile.

Throughout the notebook, various plotly figures are used to visually represent the data and findings. The notebook provides a comprehensive analysis of the performance of Tesla and Volkswagen stocks, offering insights into their daily returns, cumulative returns, volatility, and beta.

## Usage

To run this notebook, clone the repository and open the Jupyter notebook file in a Jupyter environment. Make sure you have the necessary libraries installed. If not, you can install them using pip or simply use google's colab workspace:

```bash
bash pip install pandas yfinance plotly
```


Then, simply run the cells in the notebook to perform the analysis.
