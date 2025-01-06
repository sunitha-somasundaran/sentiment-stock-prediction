Project Title: Stock Market Prediction and Sentimental Analysis

Research question: Can LSTM networks, combined with sentiment analysis, be utilized to enhance the accuracy and reliability of stock market predictions?

Project Objectives:
• Develop an LSTM model that predicts stock prices based on historical data and sentiment analysis.
• Compare the prediction made with and without the sentiment data to understand the impact public
sentiment has on stock market movement.
• Integrate the findings from sentiment analysis into the LSTM model to improve prediction accuracy.
• Evaluate the effectiveness of the integrated model through back-testing and performance metrics.
• Provide recommendations for investors and stakeholders based on the predictive insights generated.

Data:

DJIA.csv - Stock data (from 2008-08-08 to 2015-07-01): Dow Jones Industrial Average (DJIA) collected from Yahoo Finance

Reddit.csv - Textual data (from 2008-06-08 to 2015-07-01): Collected using Reddit’s API. Reddit provides an official API that allows developers to access posts, comments, and other data in real-time.

Final code:

Jupyter notebook version - final-code.ipynb
python version - final-code.py


Previous versions that were submitted to supervisor via email:

first-version.ipynb  -  contains basic EDA
second-version.ipynb - contains stock prediction without using sentiment score
third version.ipynb  -  contains prediction using only the sentiment score and closing price.


The final code contains the comparision of stock price prediction using LSTM when using only the closing price as input and also by using both closing price and sentiment score as input.

