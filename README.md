# Stock Market Fibonacci Calculator

## Overview  
This project is a Python-based technical analysis tool that fetches live market data, calculates Fibonacci retracement and extension levels using swing high/low logic, and visualizes the results on a candlestick chart with volume bars.  

It demonstrates the application of data collection, preprocessing, and analytical visualization in financial data analysis using Python.

---

## Features  
- Fetches live OHLC (Open, High, Low, Close) data using `yfinance`.  
- Calculates Fibonacci retracement and extension levels based on recent swing high/low.  
- Displays candlestick charts with color-coded Fibonacci zones and volume bars.  
- Provides a summary of key metrics including current price, swing range, and nearest Fibonacci level.  
- Supports user-defined period, interval, and lookback window.  
- Automatically appends `.NS` to Indian stock tickers.  
- Exports charts (`.png`) and raw data (`.csv`) for later analysis.  

---

## Concepts Demonstrated  
- Data ingestion and transformation with **pandas**.  
- Technical feature engineering for swing-based Fibonacci analysis.  
- Visualization using **mplfinance** for financial charting.  
- Automated reporting and data export.  
- Application of financial analytics logic in Python.  

---

## Tech Stack  

| Category | Tools / Libraries |
|-----------|-------------------|
| Programming | Python 3 |
| Data | pandas, yfinance, numpy |
| Visualization | mplfinance, matplotlib |
| Utilities | datetime, os |

---

## Installation

```bash
# Clone the repository
git clone https://github.com/<your-username>/fibonacci-market-analyzer.git
cd fibonacci-market-analyzer

# (Optional) Create a virtual environment
python -m venv venv
source venv/bin/activate        # On Windows: venv\Scripts\activate

# Install dependencies
pip install -r requirements.txt
