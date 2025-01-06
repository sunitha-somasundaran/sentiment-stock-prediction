# Stock Market Prediction and Sentiment Analysis

## Project Overview
This project explores the integration of Long Short-Term Memory (LSTM) networks and sentiment analysis to predict stock market trends. By analyzing historical stock data alongside public sentiment extracted from Reddit, the study aims to enhance the accuracy and reliability of stock market predictions.

## Research Question
Can LSTM networks, combined with sentiment analysis, be utilized to enhance the accuracy and reliability of stock market predictions?

## Project Objectives
- **Develop an LSTM model** to predict stock prices based on historical data and sentiment analysis.
- **Compare predictions** made with and without sentiment data to understand the impact of public sentiment on stock market movements.
- **Integrate sentiment analysis findings** into the LSTM model to improve prediction accuracy.
- **Evaluate the integrated model's effectiveness** using back-testing and performance metrics.
- **Provide recommendations** for investors and stakeholders based on the predictive insights generated.

## Data
1. **DJIA.csv**: Stock data (2008-08-08 to 2015-07-01) - Dow Jones Industrial Average (DJIA) collected from Yahoo Finance.
2. **Reddit.csv**: Textual data (2008-06-08 to 2015-07-01) - Reddit posts and comments collected using Reddit’s official API.

## Final Code
- **Jupyter Notebook Version**: `final-code.ipynb`
- **Python Script Version**: `final-code.py`

The final code includes:
- Comparison of stock price prediction using LSTM:
  - **Using only the closing price** as input.
  - **Using both closing price and sentiment score** as input.

## Previous Versions
1. **first-version.ipynb**: Contains basic Exploratory Data Analysis (EDA).
2. **second-version.ipynb**: Stock price prediction without using sentiment scores.
3. **third-version.ipynb**: Prediction using only the sentiment score and closing price.

## Evaluation
The integrated model's effectiveness was assessed through:
- Performance metrics (e.g., MSA, RMSE).

## Recommendations
Based on the findings, actionable insights are provided for investors and stakeholders, highlighting the role of public sentiment in market movements and its potential in improving predictive models.

---
