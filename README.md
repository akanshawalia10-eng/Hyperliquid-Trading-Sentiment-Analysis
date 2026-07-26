# 📈 Hyperliquid Trading Sentiment Analysis

![Python](https://img.shields.io/badge/Python-3.x-blue)
![Pandas](https://img.shields.io/badge/Pandas-Data%20Analysis-green)
![NumPy](https://img.shields.io/badge/NumPy-Numerical%20Computing-orange)
![Matplotlib](https://img.shields.io/badge/Matplotlib-Visualization-red)
![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-yellow)
![Status](https://img.shields.io/badge/Project-Completed-brightgreen)

---

## 📖 Project Overview

This project explores the relationship between **Bitcoin market sentiment** and **Hyperliquid trader performance** using the **Bitcoin Fear & Greed Index**. By combining historical trading data with market sentiment indicators, the analysis identifies patterns in trader profitability, trading activity, and cryptocurrency preferences.

The project demonstrates a complete **Exploratory Data Analysis (EDA)** workflow, including data preprocessing, merging datasets, visualization, and business insight generation using Python.

---

## 🎯 Project Objectives

- Analyze Hyperliquid trading performance.
- Study Bitcoin Fear & Greed Index trends.
- Compare trader profitability across different market sentiments.
- Identify the most actively traded cryptocurrencies.
- Explore Buy vs Sell trading behavior.
- Generate meaningful insights using data visualization.

---

## 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Jupyter Notebook
- CSV Dataset

---

## 📂 Dataset

The project uses two datasets:

### Hyperliquid Historical Trading Data
Contains:
- Trade Date
- Coin
- Trade Type
- Closed Profit & Loss (PnL)
- Trading Volume

### Bitcoin Fear & Greed Index
Contains:
- Date
- Fear & Greed Score
- Market Sentiment Classification

Both datasets were cleaned, merged, and analyzed to understand how market psychology influences trader performance.

---

### Average Closed PnL by Market Sentiment

![Average Closed PnL](images/Average%20Closed%20PnL%20by%20Market%20Sentiment.png)

---

### Buy vs Sell Trades

![Buy vs Sell Trades](images/Buy%20vs%20Sell%20Trades.png)

---

### Daily Trading Activity

![Daily Trading Activity](images/Daily%20Trading%20Activity.png)

---

### Distribution of Closed PnL

![Distribution of Closed PnL](images/Distribution%20of%20Closed%20PnL.png)

---

### Number of Trades by Market Sentiment

![Number of Trades](images/Number%20of%20Trades%20by%20Market%20Sentiment.png)

---

### Top 10 Coins by Average Closed PnL

![Top 10 Coins by Average Closed PnL](images/Top%2010%20Coins%20by%20Average%20Closed%20PnL.png)

---

### Top 10 Most Traded Coins

![Top 10 Most Traded Coins](images/Top%2010%20Most%20Traded%20Coins.png)

---

## 📈 Key Insights

- Extreme Greed market conditions generated the highest average Closed PnL.
- Trading activity increased during positive market sentiment.
- Buy and Sell trades remained nearly balanced throughout the analysis period.
- Bitcoin (BTC) emerged as the most frequently traded cryptocurrency.
- Some altcoins produced strong average profitability despite lower trading volumes.
- Market sentiment showed a noticeable influence on trading behavior and profitability.

---

## 💡 Skills Demonstrated

- Data Cleaning
- Exploratory Data Analysis (EDA)
- Data Visualization
- Financial Data Analysis
- Cryptocurrency Market Analysis
- Sentiment Analysis
- Statistical Analysis
- Python Programming
- Business Insight Generation

---

## 📂 Repository Structure

```
Hyperliquid-Trading-Sentiment-Analysis/
│
├── data/
│   ├── historical_data.csv
│   └── fear_greed_index.csv
│
├── images/
│   ├── Average Closed PnL by Market Sentiment.png
│   ├── Buy vs Sell Trades.png
│   ├── Daily Trading Activity.png
│   ├── Distribution of Closed PnL.png
│   ├── Number of Trades by Market Sentiment.png
│   ├── Top 10 Coins by Average Closed PnL.png
│   └── Top 10 Most Traded Coins.png
│
├── analysis.ipynb
├── Hyperliquid Trading Sentiment Analysis Report.pdf
└── README.md
```

---

## 🚀 How to Run

1. Clone this repository

```bash
git clone https://github.com/akanshawalia10-eng/Hyperliquid-Trading-Sentiment-Analysis.git
```

2. Navigate to the project directory

```bash
cd Hyperliquid-Trading-Sentiment-Analysis
```

3. Install the required libraries

```bash
pip install pandas numpy matplotlib
```

4. Open

```
analysis.ipynb
```

using Jupyter Notebook or VS Code.

5. Run all cells to reproduce the analysis and visualizations.

---

## 📊 Project Outcome

This project demonstrates how cryptocurrency trading data can be combined with market sentiment indicators to extract meaningful insights into trader behavior and profitability. It highlights practical applications of data analysis in financial markets using Python.

---

## 🚀 Future Enhancements

- Build an interactive Streamlit dashboard.
- Integrate real-time cryptocurrency APIs.
- Perform predictive sentiment analysis using Machine Learning.
- Develop automated trading signal generation.
- Add advanced financial performance metrics.

---

## 👩‍💻 Author

**Akansha Walia**

MCA Student | Data Analytics | Machine Learning | AI Enthusiast

GitHub: https://github.com/akanshawalia10-eng

---

⭐ If you found this project helpful, consider giving it a **Star** on GitHub!
