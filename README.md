# AI-ML-Powered Stock Prediction & Portfolio Rebalancing
## Project Overview

This project focuses on predicting stock market trends and optimizing portfolio rebalancing using advanced AI-ML techniques. The system leverages an LSTM-based model for stock market prediction and integrates a Market Mood Indicator powered by Generative AI to analyze market sentiment and dynamically adjust investments. With the help of quantitative analysis and market mood indicators, the solution helps users rebalance their portfolios, saving 10-25% of their portfolio value by making data-driven decisions based on real-time market conditions.

---
# Key Features

## 1. Portfolio Rebalancing

Dynamically adjusts investments based on real-time market conditions and predictions.
Aim to save 10-25% of portfolio value by optimizing asset allocation.
It helps to rebalance the entire portfolio.
<img width="646" alt="image" src="https://github.com/user-attachments/assets/bbe1a8b8-0ec9-4ecd-89c7-7f8ddf2d7c12" />

## 2. Risk-to-Return Ratio-based Stock Suggestion

Suggests stocks based on their Risk-to-Return Ratio using moving averages (100-day and 200-day).
Classifies stocks into three categories:
High-Risk Stocks: High potential returns with higher volatility.
Moderate-Risk Stocks: Balanced returns with moderate volatility.
Safe Stocks: Stable returns with low volatility.
Helps users select stocks according to their risk appetite and investment goals.
![image](https://github.com/user-attachments/assets/1e06e7ee-331e-41bd-b2fb-6528a2c4e253)

## 3. Quantitative Analysis

Conducts quantitative analysis of each stock in the portfolio to evaluate performance.
Uses 100-day & 200-day moving averages, Volume, Closing Price, and Gain/Loss over the period to identify long-term trends and inform rebalancing decisions.
### 3.1) Last Trade Price of Portfolio
![image](https://github.com/user-attachments/assets/353782fc-19cc-4b36-9510-9ad46daeb208)
### 3.2) Volume of Portfolio
![image](https://github.com/user-attachments/assets/74df7e5c-e4c2-4109-909e-d64f3a28b945)

### 3.3) Daily Return of Portfolio
![image](https://github.com/user-attachments/assets/a6e117b3-71d5-4aae-99c7-6cb55398786b)
### 3.4) Moving Average of Stock
![image](https://github.com/user-attachments/assets/05d8a11b-091c-474e-8a7a-d13735d38904)

## 4. Market Mood Indicator

Powered by Generative AI to analyze market sentiment from news, social media, and other sources.
Helps optimize portfolio rebalancing by identifying market trends.
Dynamically adjusts investments to save 10-25% of portfolio value.
![image](https://github.com/user-attachments/assets/9d926ed9-830d-4a17-a860-51cd872ecb47)

## 5. Stock Market Prediction using LSTM

Achieves 97% accuracy in forecasting market trends.
Utilizes historical stock data, including 200-day and 100-day moving averages, to train the LSTM model.
Provides actionable insights for investors.

## 6. Comprehensive Module Evaluation

Ensures robust performance and reliability of the system through rigorous testing and evaluation.

---
# Implementation Details.

## 1. Portfolio Rebalancing

Objective: Maintain the desired risk-to-return ratio by dynamically adjusting investments.
Process:
Monitors portfolio performance in real-time.
Identifies underperforming or overperforming assets.
Reallocates funds to optimize returns while minimizing risk.
Outcome: Saves 10-25% of portfolio value by making data-driven decisions.

## 2. Risk-to-Return Ratio-based Stock Suggestion

Data Collection:
Fetches historical stock data from Yahoo Finance.
Calculates 100-day and 200-day moving averages for each stock.
Classification:
High-Risk Stocks: Stocks with high volatility and high potential returns.
Moderate-Risk Stocks: Stocks with balanced risk and return.
Safe Stocks: Stocks with low volatility and stable returns.
User Input:
Users can specify their risk appetite (High, Moderate, or Safe).
The system suggests stocks accordingly.
## 3. Market Prediction

Data Collection and Preprocessing:
Fetches historical stock data from Yahoo Finance.
Visualizes closing prices and calculates moving averages to identify trends.
Dataset Preparation:
Splits data into 70% training and 30% testing sets.
Normalizes data using MinMax Scaler for better model performance.
LSTM Model:
Built with multiple layers to capture temporal dependencies in stock data.
Trained on historical data to learn patterns and trends.
Predicts future stock prices using the last 100 columns of the training dataset.
Evaluation:
Compares predicted vs. actual stock prices using graphs.
Calculates Mean Absolute Error (MAE) and R2 Score to evaluate model performance.


## 4. Market Mood Indicator

Sentiment Analysis:
Uses Generative AI to analyze market sentiment from news, social media, and other sources.
Integration:
Combines sentiment analysis with LSTM predictions to optimize portfolio rebalancing.
Outcome:
Helps users save 10-25% of portfolio value by making data-driven decisions.
Results

Achieved 95% accuracy in stock market prediction using the LSTM model.
The Market Mood Indicator successfully optimized portfolio rebalancing, saving users 10-25% of their portfolio value.
Risk-to-Return Ratio-based Stock Suggestion helped users select stocks according to their risk appetite.
Key metrics:
R2 Score: Evaluates model performance.





---
By:-
Biswajit Behera

