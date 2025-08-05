# 📈 Stock Price Prediction Using Machine Learning

**Predicting future stock closing prices** for Apple Inc. (AAPL) using historical market data and machine learning models — **Linear Regression** and **Random Forest Regressor**.

This project demonstrates how to fetch real financial data, preprocess it, train ML models, evaluate performance, and visualize predictions over time.
 
📊 Used in analysis for: **Time Series Forecasting**, **Algorithmic Trading**, and **Financial Modeling**

---

## 🧩 Project Overview

The goal of this project is to predict the next day’s closing price of Apple (AAPL) stock using key features such as:
- Opening price
- Daily high
- Daily low
- Trading volume

Two regression models are trained and compared:
1. **Linear Regression** – A simple baseline model.
2. **Random Forest Regressor** – A more complex ensemble model for non-linear patterns.

Models are evaluated using **Mean Squared Error (MSE)** and **R-squared (R²)** metrics, with visualizations showing actual vs. predicted prices.

---

## 🛠️ Technologies & Libraries Used

- **Python** – Core programming language
- **yfinance** – To download historical stock data from Yahoo Finance
- **Pandas & NumPy** – Data manipulation and analysis
- **Scikit-learn** – Machine learning models and evaluation
- **Matplotlib** – Data visualization
- **Jupyter Notebook / Python Script** – Implementation environment

---

## 📊 Dataset

- **Stock Ticker**: AAPL (Apple Inc.)
- **Date Range**: January 1, 2020 – January 1, 2023
- **Source**: [Yahoo Finance](https://finance.yahoo.com/)
- **Features Used**:
  - Open
  - High
  - Low
  - Volume
- **Target Variable**: Next day’s Close price (`next_Close`)

Data is split into:
- **80% Training**
- **20% Testing**
- No shuffling to preserve time series order.
```bash
git clone https://github.com/yourusername/stock-price-prediction.git
cd stock-price-prediction
