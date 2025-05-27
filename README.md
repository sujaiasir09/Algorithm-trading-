# 📈 Algorithmic Trading Strategy with XGBoost

This project demonstrates an end-to-end **machine learning-based algorithmic trading strategy** using historical stock data. The model is trained to predict whether the next day's closing price will go up (Buy) or down (Sell) based on technical indicators.

---

## 🚀 Project Overview

- **Stock Used:** Apple Inc. (`AAPL`)
- **Date Range:** 2015-01-01 to 2023-12-31
- **Model:** XGBoost Classifier
- **Objective:** Predict buy/sell signals and compare strategy return with market return.

---

## 🧠 Features Used

- `Open`, `High`, `Low`, `Close`, `Volume`
- Moving Averages: `MA5`, `MA10`, `MA20`
- `Volatility`: 5-day rolling standard deviation
- `Return`: Daily % change

---

## 📦 Libraries Used

```bash
pip install yfinance xgboost pandas numpy matplotlib seaborn scikit-learn
