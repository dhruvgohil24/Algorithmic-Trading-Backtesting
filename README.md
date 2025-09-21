# Trading Strategy and Backtesting – HDFC Bank & NSE Stocks

This project focuses on **algorithmic trading strategy development and backtesting**, using real stock data from NSE, including **HDFC Bank** and other major stocks like Infosys, Tata Motors, Wipro, and Asian Paints. 

The goal is to test and evaluate trading strategies with proper performance metrics and visualizations to understand their effectiveness in real market scenarios.

---

## 📌 Project Overview
The notebook demonstrates the **complete trading strategy workflow**:
1. **Data Collection** – Download historical OHLCV (Open, High, Low, Close, Volume) data using `yfinance`.
2. **Strategy Development** – Generate buy/sell signals based on rules and conditions.
3. **Backtesting Engine** – Simulate trades over historical data.
4. **Performance Analysis** – Calculate essential metrics like Sharpe Ratio, Sortino Ratio, and drawdowns.
5. **Visualization** – Plot equity curves, drawdowns, and portfolio growth using interactive Plotly charts.

This helps in identifying whether a strategy is profitable and robust before deploying it in a live trading environment.

---

## 🎯 Features
- Automated historical stock data download.
- Custom **backtesting class** for trade simulation.
- Support for **long and short positions**.
- Detailed performance metrics:
  - Sharpe Ratio
  - Sortino Ratio
  - Maximum Drawdown
  - Win/Loss ratios
  - Portfolio growth
- Interactive equity and drawdown visualizations.

---

## 🛠 Tech Stack
- **Python**
- **Libraries Used:**
  - `numpy` – Numerical calculations
  - `pandas` – Data manipulation
  - `plotly` – Interactive visualizations
  - `yfinance` – Stock data from Yahoo Finance

---

## 🚀 Getting Started

### 1. Clone the Repository
### 2. Install Required Packages
pip install numpy pandas plotly yfinance
### 3. Open the Notebook
Open Dhruv_Trading_Strategy_and_Backtesting_HDFCB.ipynb and run the cells step-by-step.

## Strategy Workflow

1. Stock Data Download

Automatically fetch OHLCV data for multiple tickers.
Saves CSV files locally for later use.

2. Signal Generation

Define custom rules for when to enter or exit trades.
Example: Moving average crossovers or price thresholds.

3. Backtesting Simulation

Apply signals to historical data.
Track portfolio value, trade history, and fees.

4. Performance Evaluation

Compare strategy performance to Buy-and-Hold benchmark.
Assess risk using advanced metrics like drawdowns and ratios.

5. Visualization

Interactive equity curves.
Drawdown plots to highlight risk exposure.

## 👤 Author
Dhruv Gohil
git clone https://github.com/your-username/TradingStrategy-Backtesting.git
cd TradingStrategy-Backtesting
