# 📈 Stocks Optimization

This is the complete portfolio optimization project built using Python. The goal is to simulate multiple portfolio allocations of selected Indian stocks and identify the one with the best **risk-adjusted return** using the **Sharpe Ratio**.

---

## 🔍 Overview

* **Type of analysis**: Monte Carlo Simulation for Portfolio Optimization
* **Risk metric used**: Portfolio Volatility (Standard Deviation)
* **Performance metric**: Sharpe Ratio (Assuming Risk-Free Rate = 0)
* **Data source**: `yfinance` API
* **Stocks analyzed**: A selected group of top Indian stocks (HDFC.NS,RELIANCE.NS, TCS.NS,INFY.NS)

---

## 🚀 Features

* Fetches historical stock data using `yfinance`
* Calculates daily and annualized returns
* Computes the annualized covariance matrix of returns
* Simulates 10,000+ random portfolios with varying weight combinations
* Calculates:

  * Expected return
  * Volatility
  * Sharpe Ratio for each portfolio
* Plots the **Efficient Frontier** with Sharpe Ratio as color gradient
* Highlights the **optimal portfolio** with the maximum Sharpe Ratio

---

## 📊 Visualizations

* Plotting Moving Average Prices of Stocks over the past 1 year (07/2024-07/2025)
* Daily return distribution for stock prices

- Frontier Plot of 10,000 portfolios showing:

  * X-axis: Portfolio Volatility
  * Y-axis: Expected Return
  * Color: Sharpe Ratio

---

## 🛠️ Technologies Used

* Python
* NumPy
* Pandas
* Matplotlib
* *yfinance*
