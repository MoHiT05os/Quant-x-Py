# 📈 Moving Average Crossover Trading Bot (Python)

A simple yet powerful backtesting script that simulates a **moving average crossover** strategy on historical market data. Built using Python and Google Colab — perfect for beginners or anyone looking to learn the basics of strategy development and quantitative finance.

---

## ⚙️ Features

- Pulls real historical data (e.g., Bitcoin) using `yfinance`
- Implements a customizable **Moving Average Crossover** strategy
- Backtests performance and visualizes equity curve
- Shows total return and win rate
- Clean and modular code (easy to upgrade later)

---

## 🧠 Strategy Logic

The bot compares two moving averages:
- **Fast MA** (e.g., 10-day)
- **Slow MA** (e.g., 30-day)

**Signal Rules:**
- 📈 Buy when Fast MA crosses above Slow MA
- 📉 Sell when Fast MA crosses below Slow MA

---

## 📊 Example Output


![image](https://github.com/user-attachments/assets/06c23a6e-493b-457b-87e6-fb9cb8e44fee)


---

## 🔧 How to Use

1. Open the Colab Notebook: [👉 Click here](https://colab.research.google.com/)
2. Paste or upload the code.
3. Run all cells step-by-step.
4. Customize `fast` and `slow` MA values in the `generate_signals()` function.

---

## 📦 Requirements

Install these libraries (already included in Colab):

```bash
pip install yfinance pandas matplotlib

