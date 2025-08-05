# Algo Trading Project – RSI & SMA Strategy

This project is part of my internship assignment where I designed and implemented an **Algorithmic Trading Strategy** using **Python**. The strategy is based on a combination of **Relative Strength Index (RSI)** and **Simple Moving Average (SMA)** indicators.

## 📌 Objective

To analyze stock price trends using technical indicators and automate buy/sell signal generation for selected stocks. This project demonstrates a rule-based trading system with backtesting and Google Sheets integration.

---

## 📈 Strategy Overview

- **Indicators Used**:
  - **RSI** (14-day): To identify overbought and oversold conditions
  - **SMA** (50-day): To track trend direction
- **Buy Signal**: RSI < 30 and price > SMA
- **Sell Signal**: RSI > 70 and price < SMA

---

## 🧪 Stocks Analyzed

- RELIANCE.NS  
- TCS.NS  
- HDFCBANK.NS  

These were downloaded using `yfinance` and processed using `pandas`.

---

## 🧠 Features

- Data download using Yahoo Finance API
- RSI & SMA calculation using pandas
- Signal generation logic
- Strategy backtesting
- Trade log creation
- Google Sheets integration using `gspread`
- Cleaned output CSVs for:
  - Signals
  - Buy/Sell logs
  - Backtested data

---

## 📂 Files Included

- `algo_trading.ipynb`: Main notebook
- CSVs: Intermediate and final outputs
- `credentials.json`: Google Sheets authentication (do not share this publicly)
- `SMA-Based Trading Strategy using Python.ipynb`: Optional demo strategy

---

## 🔗 Google Sheets

Trade logs were successfully pushed to Google Sheets using the `gspread` and `oauth2client` libraries.  
Each stock has its own sheet with a clean tabular format.

---

## 🛠️ Technologies Used

- Python 3.12  
- Pandas, NumPy, Matplotlib  
- yfinance, gspread  
- Jupyter Notebook  
- Git & GitHub  

---

## 📌 Repository Link

[👉 Click here to view the full project on GitHub](https://github.com/abishek-r754/Algo_Trading_Project)

---

## 🙋‍♂️ About Me

**Abishek R**  
Aspiring Data Analyst | Python Developer  
[GitHub](https://github.com/abishek-r754) | [LinkedIn](https://www.linkedin.com/in/abishek-r-84b42636b)

---

> ⚠️ Note: This project is for educational purposes only. It is not intended for live trading or investment advice.
