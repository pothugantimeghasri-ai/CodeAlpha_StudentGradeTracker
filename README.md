# Stock Trading Platform

A lightweight, console-based Java application that simulates a real-time stock trading environment. Users can view available market stocks, buy and sell shares, and track their portfolio balance in Indian Rupees (₹).

---

## 🚀 Features

- **Real-Time Market View**: Monitor current prices of major listed stocks (e.g., TCS, INFY, RELIANCE).
- **Buy Stocks**: Purchase shares with instant verification of balance sufficiency.
- **Sell Stocks**: Liquidate shares from your portfolio at current market rates.
- **Portfolio Tracking**: View owned shares, quantities, and remaining cash balance.
- **Console Interface**: Interactive command-line menu.

---

## 🛠️ Tech Stack & Requirements

- **Language**: Java (JDK 8 or higher)
- **APIs**: Standard Java Libraries (`java.util.Scanner`, `java.util.HashMap`, `java.util.Map`)

---

## 📁 File Structure

- [StockTradingPlatform.java](file:///c:/Users/megha/OneDrive/Desktop/task2/StockTradingPlatform.java): Main source file containing:
  - `Stock`: Model class for stock details (name and price).
  - `User`: Model class handling the portfolio, cash balance, and buy/sell actions.
  - `StockTradingPlatform`: Controller class running the interactive CLI loop.

---

## 🎮 How to Run

1. **Compile the source code**:
   ```bash
   javac StockTradingPlatform.java
   ```

2. **Execute the platform**:
   ```bash
   java StockTradingPlatform
   ```

---

## 📊 Market Stock Reference

| Stock Symbol | Name | Initial Price |
| :--- | :--- | :--- |
| **TCS** | Tata Consultancy Services | ₹3,500.00 |
| **INFY** | Infosys | ₹1,500.00 |
| **RELIANCE** | Reliance Industries | ₹2,800.00 |

*Note: Initial user balance is set to **₹100,000.00**.*
