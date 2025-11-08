# EMA Backtest

**vectorized backtesting framework** for a **EMA20/50 crossover strategy** applied to multiple tech stocks using 5 years of stock data.
This project calculates key performance metrics (CAGR, Sharpe ratio, Max Drawdown, Win Rate) and visualise the results.

---

## Strategy 

- **Buy Signal**: EMA20 > EMA50  
- **Sell Signal**: EMA20 < EMA50  
- **Portfolio**: Equal-weight across tickers (AMZN, MSFT, META, GOOG)


### Requirements

To run the backtest, the following Python libraries must be installed:

pip install pandas numpy matplotlib yfinance


## Results KPI Table

| Ticker | CAGR | Max Drawdown | Sharpe Ratio | Win Rate | Profit Factor |
|--------|------|--------------|--------------|----------|---------------|
| AMZN   | 10.04% | -56.15% | 36.27% | 30.77% | 1.60 |
| MSFT   | 19.77% | -37.15% | 71.46% | 33.33% | 1.30 |
| META   | 18.16% | -76.74% | 53.53% | 57.14% | 7.10 |
| GOOG   | 26.59% | -44.60% | 82.52% | 36.36% | 2.40 |


## Portfolio Equity Curve of EMA20/50 Strategy
<img width="1015" height="483" alt="image" src="https://github.com/user-attachments/assets/3b0567fc-3a4e-46ce-a734-06550c05d0e3" />

<img width="942" height="452" alt="image" src="https://github.com/user-attachments/assets/f52ad50b-3578-4366-9810-81af7484f413" />
<img width="942" height="452" alt="image" src="https://github.com/user-attachments/assets/1cf25d64-6d98-461a-af38-75770c3bf3ec" />


