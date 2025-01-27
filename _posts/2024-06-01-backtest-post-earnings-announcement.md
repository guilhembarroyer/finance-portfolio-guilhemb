---
layout: post
title: Earnings-&-Sentiment-Based Backtesting Tool
subtitle: Backtesting trading strategies using earnings releases, sentiment analysis, and news data
gh-repo: guilhembarroyer/backtest_post_earnings_annoucement
gh-badge: [star, fork, follow]
#cover-img: /assets/img/backtesting_cover.png
thumbnail-img: /assets/img/backtest_symbol.png
tags: [finance, trading, data-analysis, python]
comments: true
mathjax: false
author: Guilhem Barroyer
---

{: .box-success}
**Earnings-Based Backtesting Tool** is a Python project designed to simulate and evaluate trading strategies based on quarterly earnings releases, sentiment analysis, and financial data. This tool uses historical data and news sentiment to test strategies dynamically and identify the most effective parameters for optimized returns.

---

## **Repository**

Explore the full source code on GitHub:

[![GitHub Repository](https://img.shields.io/badge/GitHub-Earnings_Based_Backtesting-blue?style=flat-square&logo=github)](https://github.com/guilhembarroyer/backtest_post_earnings_annoucement)

---

## **Key Features**

### 1. **Dynamic Backtesting**
{: .box-note}
- Simulates trading strategies around quarterly earnings announcements.
- Leverages **news sentiment scores** to refine trading decisions.
- Tests trades based on user-defined parameters such as:
  - Take-Profit levels
  - Minimal sentiment scores
  - Days before and after earnings announcements.

### 2. **Data-Driven Insights**
{: .box-note}
- Uses historical stock prices and sentiment data for analysis.
- Automatically fills missing financial data via the Alpha Vantage API.
- Optimizes strategy parameters for better risk-adjusted returns.

### 3. **Performance Evaluation**
{: .box-note}
- Analyzes trade outcomes, including:
  - Total yield and cash returns.
  - The number of trades executed.
  - Win/loss ratio and average trade duration.
- Outputs results in a structured CSV format for easy reporting.

### 4. **Integration with News Sentiment**
{: .box-note}
- Incorporates **sentiment analysis** of financial news headlines.
- Links sentiment scores with earnings announcements to adjust trading strategies dynamically.

---

## **Project Structure**

### **Main Components**
- **`main.py`**: Coordinates the backtesting process, iterating through stock tickers, earnings periods, and strategies.
- **`backtest.py`**: Core module that handles the simulation of trades based on defined parameters.
- **`local_dataF.py`**: Manages historical stock data and news recovery, leveraging the Alpha Vantage API for missing data.
- **`outputF.py`**: Handles daily trading logic, including position management, stop-loss, and take-profit mechanisms.

---

## **Interactive Results**

{: .box-success}
- **Visualization**: Results can be exported for custom visualization and benchmarking.
- **Customizable**: Modify parameters to explore various strategies and refine trading models.

Example CSV Output:
![Exemples de résultats cs](assets/img/ex_results.png)
