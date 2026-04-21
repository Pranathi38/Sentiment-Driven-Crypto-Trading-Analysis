# Sentiment-Driven-Crypto-Trading-Analysis

# Overview
This project analyzes how Bitcoin market sentiment (Fear/Greed) affects trader performance using historical trading data. It uncovers behavioral patterns and provides insights to support smarter, sentiment-aware trading decisions.

# Data
Sentiment Data: Fear, Neutral, Greed classifications
Trading Data: price, size, side, PnL, timestamp, etc.

# Objective
Find patterns between market sentiment & trading performance
Predict whether a trade will be profitable

# Method
Data cleaning & merging on date
Feature engineering (profit, trade size, time, sentiment)
EDA (profit, win rate, trade size vs sentiment)
Model: Random Forest Classifier

# Results
Accuracy: ~80%
Greed markets → higher profits
Neutral markets → lowest performance
Sentiment impacts trading behavior and outcomes

# Conclusion
Market sentiment is a useful signal for improving trading strategies and predicting profitability.

📂 Project Structure
├── trades.csv
├── sentiment.csv
├── model.ipynb
├── README.md
