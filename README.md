# Forecasting-Stock-Price-Direction
### Objective: Forecast the daily price direction of Amazon.com, Inc. (AMZN) stock. Navigating the stock market's complexities and volatility can be challenging. To achieve profitability, it's not necessary to predict the exact price; instead, it's crucial to anticipate the price direction, whether it will rise or fall compared to the current price. If the prediction indicates an increase, it could be advantageous to purchase stocks; otherwise, selling may be the better option. 
### Data Description
I have used data for the period from 1997 up to year 2020 that I have split that into training (1997-2016), validation (2016-2018) and testing (2018-2020) periods. The data is available in the AMZN_train.csv, AMZN_val.csv and AMZN_test.csv files, respectively.

Each dataset has the same format with the following 7 columns:
```
Date - in format YYYY-MM-DD
Open - stock price upon opening of an exchange
High - the highest stock price on a given day
Low - the lowest stock price on a given day
Close - stock price at the end of a trading day
Adj Close - adjusted closing price that takes into account corporate actions
Volume - the amount of shares traded over the course of a trading day
```
