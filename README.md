# Cryptocurrency-Market-Analysis-Dashboard

An interactive and data-driven analysis of the cryptocurrency market. This project utilizes historical price and volume data to visualize market trends, asset performance, and volatility using **Power BI** and **Data Analysis** techniques.

## 📌 Project Overview
The crypto market is characterized by high volatility and rapid shifts in market sentiment. This project processes a dataset of historical records (Price High, Low, Open, Close, Volume, and Market Cap) to provide a clear view of how major digital assets have evolved. The goal is to help stakeholders identify market cycles, top-performing assets, and liquidity trends.

## 🛠️ Tech Stack & Tools
* **Data Source:** Historical Cryptocurrency Market Data (Excel/CSV).
* **Data Visualization:** Power BI Desktop.
* **Analysis Focus:** Trend Analysis, Asset Comparison, and Market Liquidity.

## 🚀 Key Features & Workflow

### 1. Data Preparation
* **Cleaning:** Standardized date formats and handled large numerical values (Market Cap and Volume) for accurate scaling.
* **Categorization:** Grouped assets by Symbol (BTC, ETH, AAVE, XRP, etc.) to allow for side-by-side performance benchmarking.
* **Metric Calculation:** Created measures for daily price fluctuations and percentage changes to measure volatility.

### 2. Interactive Dashboard (Power BI)
The dashboard provides a 360-degree view of the crypto market through:
* **Market Capitalization Overview:** Visualizing the dominance of top-tier assets compared to the broader market.
* **Price Trend Analysis:** Line charts tracking "High" vs "Low" prices over time to identify support and resistance levels.
* **Volume vs. Market Cap:** A correlation analysis to see how trading volume impacts the total market value of specific coins.
* **Time-Series Filtering:** Ability to drill down into specific years, months, or even daily movements.

## 📊 Key Insights
* **Market Dominance:** Clear visualization of how assets like Bitcoin and Ethereum hold the majority of market value.
* **Volatility Spikes:** Identification of specific historical dates where trading volume surged, often correlating with major price corrections or rallies.
* **Liquidity Trends:** Analysis of "Volume" to determine which assets are the most liquid and actively traded.

## 💡 Business Value
* **Investment Decision Support:** Provides a historical context for price movements, helping users understand "All-Time Highs" and "Market Bottoms."
* **Risk Management:** By visualizing volatility, the dashboard helps users identify assets with higher price swings versus more stable market leaders.
* **Portfolio Diversification:** Identifies correlations between different tokens to help in building a balanced digital asset portfolio.

## ⚙️ How to Run

### 1. Prerequisites
* **Power BI Desktop** (Free to download)
* The provided dataset: `CryptoData.xlsx`

### 2. Visualization
1.  Clone this repository to your local machine.
2.  Open the `Cryptocurrency Dashboard.pbix` file.
3.  If the data does not load automatically, click on **'Transform Data'** -> **'Data Source Settings'** and point it to the `CryptoData.xlsx` file on your computer.
4.  Click **'Refresh'** to update the visuals.

---

## 📁 Repository Structure
```text
├── data/
│   └── CryptoData.xlsx                  # Historical market dataset
├── dashboard/
│   └── Cryptocurrency Dashboard.pbix    # Interactive Power BI file
└── images/
    └── dashboard_preview.png            # Screenshot of the final dashboard
