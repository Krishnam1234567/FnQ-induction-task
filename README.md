# RSI Strategy Backtesting using `Backtesting.py`, `TA-Lib`, and `yfinance`

This Python script performs backtesting and parameter optimization for a simple RSI-based trading strategy using historical market data.

## 📈 Strategy Overview

The strategy:
- Buys when the RSI drops below a lower bound (oversold).
- Sells when RSI rises above an upper bound (overbought).

You can optimize:
- `bound_up`: RSI overbought threshold
- `bound_down`: RSI oversold threshold
- `window`: RSI calculation window

## 🛠️ Requirements

Ensure you have the following Python packages installed:

```bash
pip install backtesting yfinance ta-lib pandas
