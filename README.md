# EDA_project

# 📈 Titan Stock EDA Project

This project performs an Exploratory Data Analysis (EDA) of **Titan Company Limited (TITAN.NS)** stock data using Python. It utilizes various data visualization and analysis techniques to explore the stock's performance between 2020 and 2025.

---

## 📌 Project Objectives

- Analyze historical stock price trends of Titan Company
- Visualize daily returns and volatility
- Calculate and plot moving averages
- Understand correlations between stock features
- Gain insights into trading behavior over time

---

## 🧰 Tools & Libraries Used

- Python
- [yfinance](https://pypi.org/project/yfinance/)
- pandas
- numpy
- seaborn
- matplotlib

---

## 📅 Dataset

The dataset is downloaded directly from **Yahoo Finance** using the `yfinance` API for the time period:
Start Date: January 1, 2020
End Date: January 1, 2025
Ticker: TITAN.NS (Titan Company Limited - NSE)


---

## 📊 Key Analyses Performed

- **Closing Price Trends**  
  Line plot of Titan's closing prices over 5 years.

- **Daily Returns**  
  Computation and visualization of percentage daily returns and return distribution.

- **Moving Averages**  
  20-day and 50-day rolling averages plotted with closing price.

- **Volatility Analysis**  
  20-day rolling standard deviation used to analyze volatility.

- **Correlation Matrix**  
  Heatmap of correlations between Open, High, Low, Close, Volume, etc.

---

## 📷 Sample Visuals

> 📌 Add screenshots here if you're uploading to GitHub or using Colab.

---

## 💾 How to Run

1. Clone the repository or download the files.
2. Install dependencies:
3. Run the script:
```bash
python titan_eda.py


