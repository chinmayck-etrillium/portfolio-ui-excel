# 📊 Investment Tracker with Google Sheets

A simple and powerful **Investment Tracking Dashboard** built with Google Sheets, using **Google Finance** to fetch live data and visualize your investment portfolio with minimal effort.

---

## ✨ Features

- 🔄 **Live Stock Updates** via `GOOGLEFINANCE()`
- 📅 **Easy Transaction Entry** – Just input date, ticker, buy/sell, quantity, and price
- 📈 **Dynamic Dashboard** with real-time summaries
- 📊 **Breakdown Sheet** showing asset allocation and investment insights
- 📌 **Holdings Sheet** listing current positions and unrealized returns
- 🔍 **Stock Trend Viewer** – View 12-month trend chart of any selected stock

---

## 🧾 How It Works

1. **Enter transactions** in the `Transaction Detail` sheet:

   - Date
   - Ticker (e.g. `NSE:HDFCBANK`)
   - Buy/Sell
   - Quantity
   - Price

2. **Live prices** are fetched automatically using:

   ```excel
   =GOOGLEFINANCE(ticker, "price")

   ```

3. **Holdings** are calculated based on your latest positions.

4. **Dashboard shows**:

   - Current value
   - Total investment
   - Unrealized P&L
   - Performance trends

5. Breakdown visualizes:

   - Asset classes
   - Sectoral exposure (if mapped)
   - Weight by holding

6. Stock Quote Viewer:
   - Select a ticker from the dropdown
   - View a 12-month price trend chart

---

## 📸 Screenshots

**Add screenshots here once added to the repo**: - dashboard.png - transaction-details.png - holdings.png - breakdown.png

---

## 🔧 Requirements

- **A Google Account**
- **Google Sheets(Free)**

---

## 📥 Getting Started

1. [Click here] (https://docs.google.com/spreadsheets/d/1d5WRcExNcmhvfHwlu1YfPb19l5CZJMjF_VsZkLDhEwg/edit?usp=sharing) to make a copy of the template

2. Go to `File > Make` a copy to edit and use your own version

3. Begin by entering transactions in the `Transaction Detail sheet`, Example data there.

---

## 🙋‍♂️ Author

**Created by [Chinmay C K]**
📫 [chinmayck24@gmail.com]
🌐 [chinmayck] (www.linkedin.com/in/chinmayck/)

---

## 📌 Note

**Data is pulled using Google Finance and may have limitations on certain international tickers**

**This tracker is designed for personal finance tracking and is not a substitute for professional investment platforms**

---
