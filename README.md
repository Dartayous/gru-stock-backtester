<p align="center">
  <img src="assets/GRU_STOCK_BACKTESTER_Banner.png" alt="GRU Stock Backtester - AI + Finance" width="100%">
</p>

<h1 align="center">🤖 GRU Stock Backtester</h1>
<p align="center">AI-Powered Time Series Forecasting Meets Financial Strategy</p>

<p align="center">
  <img src="https://img.shields.io/badge/Python-3.11-blue" />
  <img src="https://img.shields.io/badge/AI-Enabled-lightgrey" />
  <img src="https://img.shields.io/badge/Backtesting-Financial%20Markets-brightgreen" />
</p>

## 🚀 Project Overview

`gru-stock-backtester` is an AI-powered backtesting framework that leverages GRU-based deep learning for time series forecasting in financial markets. Built to bridge predictive analytics and trading strategy evaluation, it enables developers and data scientists to simulate, refine, and validate investment logic using historical stock data. Designed with modular components and scalable architecture, this project demonstrates expertise in Python, machine learning model integration, and quantitative strategy design. Ideal for showcasing applied knowledge in AI engineering, financial modeling, and decision-support systems.

## 🧰 Key Features

- 📈 GRU-powered predictive modeling for stock price movements
- 🧪 Historical data simulation with flexible strategy injection
- 📊 Visual performance tracking of trades vs. predictions
- 📂 Modular architecture for easy strategy swap-ins


## 🔧 Getting Started

1. Clone the repository  
   `git clone https://github.com/your-username/gru-stock-backtester.git`
2. Install dependencies  
   `pip install -r requirements.txt`
3. Run the demo notebook  
   `jupyter notebook notebooks/gru_backtest_demo.ipynb`


## 🚀 Features
Multivariate GRU neural network trained on:

RSI, MACD, Volume Shift

Close price sequences

Simulated sentiment scoring from:

News, earnings, and social media

Hybrid trading logic using:

MACD crossovers

Sentiment thresholds

Model predictions

Performance metrics:

CAGR (Compound Annual Growth Rate)

Sharpe Ratio

Final Portfolio Value


## 📈 Tested Assets
Apple (AAPL)

Amazon (AMZN)

Tesla (TSLA)

Microsoft (MSFT)


## 🧪 Evaluation Snapshot
{
  'AAPL': {'CAGR': '-0.17%', 'Final Value': 9745.86, 'Sharpe': -0.15},
  'AMZN': {'CAGR': '-0.27%', 'Final Value': 9606.56, 'Sharpe': -0.25},
  'MSFT': {'CAGR': '-0.78%', 'Final Value': 8891.12, 'Sharpe': -0.46},
  'TSLA': {'CAGR': '0.94%',  'Final Value': 11446.97, 'Sharpe': 0.33}
}



## 🛠️ Requirements
See requirements.txt. Core dependencies include:
numpy
pandas
matplotlib
yfinance
ta
tensorflow
scikit-learn


## 📁 File Structure
stock_backtester.ipynb — full pipeline from GRU training to backtest

requirements.txt — dependency list

README.md — this file


## 🧠 Future Plans
Integrate trained GRU instead of rolling predictions

Add true sentiment data via APIs (e.g. news or Twitter)

Deploy as an API with Flask or FastAPI

Add front-end dashboard (Plotly/Dash)

Added custom banner to README
