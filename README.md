# Trader Behavior Insights – Market Sentiment Analysis

## Project Overview

This project analyzes the relationship between **Bitcoin market sentiment (Fear vs Greed)** and **trader performance** using historical trading data from Hyperliquid.

The objective is to uncover patterns in trader behavior and identify insights that could support more informed trading strategies.

---

## Datasets Used

## Dataset

The datasets used in this project are too large to upload to GitHub.

You can download them from the following links:

Historical Trading Data:
https://drive.google.com/file/d/1IAfLZwu6rJzyWKgBToqwSmmVYU6VbjVs/view

Fear & Greed Index Dataset:
https://drive.google.com/file/d/1PgQC0tO8XN-wqkNyghWc_-mnrYv_nhSf/view

### 1. Bitcoin Market Sentiment Dataset
Contains the **Fear & Greed Index**, which reflects overall cryptocurrency market sentiment.

Columns include:
- timestamp
- value
- classification (Fear / Greed)
- date

### 2. Historical Trader Data (Hyperliquid)

This dataset contains real trading activity from traders.

Important columns include:
- Account
- Coin
- Execution Price
- Size USD
- Side (Buy / Sell)
- Closed PnL (Profit or Loss)
- Timestamp
- Date

---

## Project Workflow

### 1. Data Loading
Both datasets were loaded using **Pandas**.

### 2. Data Cleaning
- Converted timestamps to datetime format
- Extracted trading dates
- Standardized column names

### 3. Data Integration
The datasets were merged using the **Date** column to align trader activity with the corresponding market sentiment.

### 4. Exploratory Data Analysis

The following analyses were performed:

- Trader profit vs market sentiment
- Trade frequency during Fear vs Greed
- Profit by cryptocurrency
- Profit by trade direction (Buy vs Sell)
- Distribution of profit and loss

---

## Key Insights

1. Trader profitability varies depending on market sentiment conditions.
2. Trading activity tends to increase during **Greed** market sentiment periods.
3. Certain cryptocurrencies contribute more significantly to total trader profit.
4. Trade direction (Buy vs Sell) shows differences in overall profitability.
5. Profit and loss distribution indicates that most trades produce small outcomes while a few produce larger gains or losses.

---
## Summary

This analysis explored the relationship between Bitcoin market sentiment and real trader behavior on Hyperliquid across multiple dimensions: profitability, win rate, trade volume, coin selection, buy/sell direction, and sentiment transitions.

**Tools used:** Python · Pandas · NumPy · Matplotlib · Seaborn  
**Author:** THAISREE S

