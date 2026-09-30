

A dynamic **Crypto Trading Dashboard** designed to monitor real-time cryptocurrency market data, manage automated trading bots, and track portfolio performance. Built on **React**, this application provides an interactive user interface for viewing live order book trades, analyzing performance trends via dynamic charts, and configuring trading strategy parameters via API services.

---

## 📌 Table of Contents

* [Features](https://www.google.com/search?q=%23-features)
* [Prerequisites](https://www.google.com/search?q=%23-prerequisites)
* [Interactive Project Tree](https://www.google.com/search?q=%23-interactive-project-tree)
* [Getting Started](https://www.google.com/search?q=%23-getting-started)
* [Application Architecture & Services](https://www.google.com/search?q=%23-application-architecture--services)
* [Available Scripts](https://www.google.com/search?q=%23-available-scripts)
* [Interactive Execution Tracker](https://www.google.com/search?q=%23-interactive-execution-tracker)

---

## ✨ Features

* 📊 **Market Data Visualizer:** Monitor real-time crypto prices and ticker updates.
* 🤖 **Bot Control Panel:** Configure, start, stop, and inspect trading bots via custom parameters (`BotCard`, `BotForm`).
* 📈 **Performance Analytics:** View trade returns and historical metrics using interactive charts (`PerformanceChart`).
* 📜 **Trade Logs & Order History:** Review past transactions and current active orders (`TradesList`).
* 🔌 **Modular API Service Layer:** Streamlined HTTP communication abstraction via `services/api.js`.

---

## ⚡ Prerequisites

| Tool | Version / Requirement | Link |
| --- | --- | --- |
| **Node.js** | `v16.x` or higher | [Download](https://www.google.com/search?q=https://nodejs.org/) |
| **npm** | `v8.x` or higher (comes with Node) | [Documentation](https://www.google.com/search?q=https://docs.npmjs.com/) |
| **Browser** | Modern Web Browser (Chrome, Firefox, Edge) | N/A |

---

## 📂 Interactive Project Tree

```text
Crypto-Trading-Dashboard-main/
├── public/
│   ├── favicon.ico
│   ├── index.html
│   ├── logo192.png
│   ├── logo512.png
│   ├── manifest.json
│   └── robots.txt
├── src/
│   ├── components/
│   │   ├── BotCard.js             # Trading bot status card component
│   │   ├── BotForm.js             # Form to configure new or existing bots
│   │   ├── MarketData.js          # Live cryptocurrency market price feeds
│   │   ├── Navbar.js              # Application header and navigation bar
│   │   ├── PerformanceChart.js    # Graphical analytics for trading metrics
│   │   └── TradesList.js          # Execution logs and trade history list
│   ├── services/
│   │   └── api.js                 # API abstraction for crypto data and backend services
│   ├── App.css
│   ├── App.js                     # Main layout & component router
│   ├── App.test.js
│   ├── index.css
│   ├── index.js                   # Application entry point
│   ├── logo.svg
│   ├── reportWebVitals.js
│   └── setupTests.js
├── .gitignore
├── package.json
└── package-lock.json

```

---

## 🚀 Getting Started

```bash
cd Crypto-Trading-Dashboard-main

```

```bash
npm install

```

```bash
npm start

```

> [!NOTE]
> Open [http://localhost:3000](http://localhost:3000) to view the dashboard in your browser.

---

## 🛠 Application Architecture & Services

The application follows a clean component-driven React architecture:

* **State & Service Layer (`src/services/api.js`):** Handles network requests to trading APIs or backend microservices.
* **UI Components (`src/components/`):** Modular units handling specific dashboard responsibilities:
* `BotCard.js` / `BotForm.js`: Interface for managing active trading bot lifecycle and strategies.
* `MarketData.js`: Ticker display for tracked crypto pairs.
* `PerformanceChart.js`: Data visualization rendering return rates over time.
* `TradesList.js`: Historical ledger showing buy/sell executions.



---

## 📜 Available Scripts

In the project directory, you can run:

### `npm start`

Runs the app in development mode at [http://localhost:3000](http://localhost:3000).

### `npm test`

Launches the test runner in interactive watch mode via `App.test.js`.

### `npm run build`

Builds the app for production to the `build` folder, optimizing the bundle for best performance.

---

## ✅ Interactive Execution Tracker

Track your setup and testing progress:

* [ ] **Step 1:** Verify Node.js and npm installations (`node -v`, `npm -v`).
* [ ] **Step 2:** Install dependencies using `npm install`.
* [ ] **Step 3:** Configure endpoint base URLs in `src/services/api.js` (if connecting to a live backend).
* [ ] **Step 4:** Run local development server (`npm start`).
* [ ] **Step 5:** Execute unit tests (`npm test`).
* [ ] **Step 6:** Generate production build bundle (`npm run build`).
