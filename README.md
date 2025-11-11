# Stock Take Dashboard

**Finance Through Data**

---

## Overview

Stock Take is a minimalist web-based dashboard for visualizing stock prices over time. It allows users to track individual stocks, overlay a second stock for comparison, and quickly view key metrics like **open, close, and volume**.  

The dashboard emphasizes clarity and clean design, using Chart.js for charting, and includes a subtle visual touch with **faded company logos in the chart background**.

---

## Features

- **Ticker Search with Suggestions** – Start typing a ticker symbol and get autocomplete suggestions from a pre-defined list.  
- **Multiple API Providers** – Supports Finnhub, Alpha Vantage, and Twelve Data with fallback logic if one fails.  
- **Stock Info Panel** – Displays latest **Open, Close, Volume** data.  
- **Interactive Chart** – Line chart with:
  - Smooth curves
  - Filled area under line
  - Overlay support for a second stock
  - Fade-in animations
  - Custom tooltip showing price and volume
- **Trend Arrow** – Minimalistic black arrow above the chart indicates short-term trend (up or down).  
- **Faded Logo Background** – Each stock shows a small, subtle logo behind the chart for branding.  
- **Date Ranges** – Quick buttons to switch between 1M, 3M, 6M, and 1Y views.  
- **Debug Console** – Optional toggle for live logging of API calls and chart updates.

---

## Technologies Used

- **HTML5 & CSS3**
- **JavaScript (ES6)**
- **Chart.js** – For dynamic chart rendering
- **Simple Icons** – For stock logos
- **Fetch API** – For pulling stock data from:
  - Finnhub
  - Alpha Vantage
  - Twelve Data

---

## How to Use

1. Open `index.html` in a modern web browser.
2. Type a stock ticker (e.g., `AAPL`) in the search box.
3. Optionally check **Overlay Second Ticker** to compare anoth
