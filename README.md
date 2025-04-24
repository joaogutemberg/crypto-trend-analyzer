# Crypto Trend Analyzer

A Python-based tool to fetch, analyze, and visualize the 30-day price trend and returns for BTC (Bitcoin).  
Built with pandas, yfinance, and matplotlib, this project demonstrates data collection, processing, analysis, and charting—all in one self-contained notebook.

---

## 🚀 Project Features

- **Data Pull**: Retrieves daily OHLCV data for BTC-USD over the past 30 days via the Yahoo Finance API (`yfinance`).
- **Metric Calculations**: Computes daily returns and absolute price changes.
- **Trend Detection**: Calculates 7-day and 14-day simple moving averages (SMAs) and labels the current trend as “Uptrend” or “Downtrend.”
- **Visualizations**:  
  - Line chart of closing price  
  - Bar chart of daily returns  
- **Summary Output**: Prints a clear summary message, e.g.:  
 ```text
  BTC 30-day return: +7.23% | Current trend is: Uptrend.
