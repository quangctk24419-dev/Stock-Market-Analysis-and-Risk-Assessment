# 📈 Stock Market Dynamics & Correlation Analysis

## 📌 Project Overview
This project explores 5 years of historical S&P 500 data (600,000+ records) to decode the "heartbeat" of the stock market. Focusing on four giants—**Apple, Amazon, Netflix, and Coca-Cola**—the study visualizes the trade-off between aggressive growth and defensive stability.

## 🛠 Methodology & Features
- **Data Preprocessing:** Cleaned 600k+ rows of data, handled missing values, and synchronized time-series formats.
- **Financial Feature Engineering:** Calculated:
    - **Daily & Cumulative Returns:** To track wealth growth (e.g., Netflix's 11x growth).
    - **Moving Averages (MA20/MA50):** To identify "Golden Cross" trend signals.
    - **Maximum Drawdown (MDD):** To measure the "psychological pain" of investment during market crashes.
- **Risk & Correlation Analysis:**
    - **Heatmaps:** To uncover hidden links between sectors (e.g., the 0.67 correlation between Coca-Cola and PepsiCo).
    - **Distribution Plots (KDE):** To analyze the "fat-tail" risk of volatile tech stocks vs. the stability of consumer staples.
    - **Pairplots:** To visualize linear vs. non-linear relationships in a diversified portfolio.

## 📊 Key Findings
- **High Growth, High Pain:** Netflix showed the highest returns (11x) but suffered from sharp 30% drawdowns, testing investor discipline.
- **The Diversification Anchor:** Adding Coca-Cola (KO) to a tech-heavy portfolio significantly reduces overall systemic risk due to its low correlation with Big Tech.
- **Volume as a Signal:** High trading volume during price drops often signals "panic selling," a critical indicator for contrarian investors.

## 🚀 Technologies Used
- **Python:** The core engine for data processing.
- **Pandas:** Time-series analysis and rolling calculations.
- **Seaborn & Matplotlib:** Advanced financial visualizations and heatmaps.
- ## 📊 Dataset
The dataset contains over 600,000 records of stock prices (Open, High, Low, Close, Volume).
- **Direct Link:** [S&P 500 Stocks Dataset (Kaggle)](https://www.kaggle.com/datasets/rohitjain454/all-stocks-5yr)
- **Note:** Due to the file size (~30MB), the raw CSV file (`all_stocks_5yr.csv`) is not included in this repository. Please download it from Kaggle and place it in the project directory before running the notebook.

## 📂 How to use
- Open `Analysis.ipynb` to view the end-to-end workflow from data cleaning to strategic insights.
