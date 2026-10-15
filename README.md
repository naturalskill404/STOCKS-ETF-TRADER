# 📈 Maria Grandoare Alpaca Trader (V28.0)

Maria Grandoare Alpaca Trader is a modern, open-source algorithmic trading and portfolio monitoring bot built in Python. Designed for both paper and live trading, it integrates seamlessly with the official Alpaca API (`alpaca-py`) and features a sleek, dark-themed user interface powered by **CustomTkinter**.

---

## 🚀 Key Features

* **Multi-Asset Support:** Built-in scanner covering over 200+ top stocks and ETFs (Tech, Semiconductors, Finance, Healthcare, Energy, Retail, and Leveraged ETFs).
* **Real-Time Technical Analysis:** Computes real-time RSI (Relative Strength Index) on minute-level bars.
* **Dual Operational Modes:**
  * **Calm Mode:** Scans the market, logs data, and tracks RSI/PNL without placing automatic orders.
  * **Aggressive Mode:** Automatically executes market buy orders when RSI drops below your target threshold and takes profit when goals are met.
* **Interactive CustomTkinter GUI:**
  * Live portfolio balance and cash tracking.
  * Sortable portfolio and scanner table (click headers to sort by PNL, price, RSI, etc.).
  * Quick filtering by symbol and double-click manual sell override for active positions.
* **Robust Network Resilience:** Features built-in automatic retry logic to gracefully handle sudden TCP disconnections (`ConnectionResetError`).

---

## 🛠️ Installation & Setup

1. **Clone the repository:**
   ```bash
   git clone [https://github.com/YOUR_USERNAME/your-repo-name.git](https://github.com/YOUR_USERNAME/your-repo-name.git)
   cd your-repo-name

   pip install customtkinter alpaca-py pandas

   python main.py
