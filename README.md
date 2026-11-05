# AGRIPRICE-INTELLIGENCE-SYSTEM
AI/ML-Based Agricultural Commodity Price Forecasting and Buffer Stock Decision Support System
# AgriPrice Insight – Decision Support System & Price Forecasting

**AI/ML-Driven Agricultural Commodity Price Forecasting and Buffer Stock Decision Support System with Regional Market Intelligence.**

---

## 🚀 How to Run Locally

### Prerequisites
- Node.js
- npm
- Visual Studio Code

### Method 1: Using Windows Batch Script

1. Extract the downloaded ZIP file.
2. Open the project folder.
3. Double-click `start-windows.bat`.
4. Wait for the dependencies to install and the server to start.
5. Open your browser and visit:

   `http://localhost:3000`

### Method 2: Using VS Code Terminal

1. Open Visual Studio Code.
2. Select **File → Open Folder** and choose the extracted project folder.
3. Open the terminal using **Terminal → New Terminal**.
4. Install the required dependencies:

   ```bash
   npm install --legacy-peer-deps
   ```

5. Start the development server:

   ```bash
   npm run dev
   ```

6. Open `http://localhost:3000` in your browser.

---

## 📦 Project Architecture and Key Features

- **Multi-Horizon Price Forecasting:** Predicts agricultural commodity prices for 7-day, 30-day, and 90-day periods.
- **Buffer Stock Recommendation:** Provides stock recommendations using the framework `Qcandidate = min(Ggap, Aavail, Ccap)`.
- **All Markets Live Board:** Displays mandi prices, arrivals, price trends, and retail unit conversions across Tamil Nadu markets.
- **Bilingual Interface:** Supports English and Tamil language translations.
- **GIS Mandi Map:** Provides interactive geographical visualization of regional agricultural markets using Leaflet.

---

## 🛠️ Technologies Used

- Frontend: React, TypeScript
- Backend: As implemented in the project
- Machine Learning: Seasonal Naive, SARIMA, XGBoost
- Visualization: Leaflet
- Package Management: npm

---

## 🎯 Project Objective

To develop an intelligent agricultural decision support system that forecasts commodity prices, provides buffer stock recommendations, and offers regional market insights to support informed agricultural planning and price stabilization.

---

## 👩‍💻 Project

**Project Name:** AgriPrice Insight

**Category:** Artificial Intelligence and Machine Learning

**Purpose:** Agricultural Commodity Price Forecasting and Buffer Stock Decision Support.
