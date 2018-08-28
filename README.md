Predicting Daily Close Stock Prices


The aim of this investigate using machine learning in trading equities, specifically to predict stock close prices for a 7-day period.

Description of Dataset
The primary dataset used is daily stock data for stocks on the National Stock Exchange(NSE). The date range for stock data varies depending on when the stock went public. The furthest date was in the year 1998. The most recent date in the dataset was 15 June 2018. The data was taken from Quandl's free access database.

All the data is in one comma-separated value file (CSV), with each row being one datapoint. There are over 14 million datapoints in the dataset.

Each row has 8 columns. That means we have 8 features for each stock on every trading day since the year when the stock was tradable (from 1998 onwards).

The Dataset is like this,

Date : YYYY-MM-DD 

Open : given to 2 decimal places. Price of stock when the market opened on that day in Rupees.

High : 2 d.p. Maximum price of the stock during the trading day in Rupees.

Low : 2 d.p. Minimum price of the stock during the trading day in in Rupees.

Last : 2 d.p. Price just before closing on any given day in Rupees.

Close : 2 d.p. Price of stock when the market closed on that day in Rupees.

Volume : 1 d.p. The number of shares of that stock traded on that day.

Turnover (Lacs) : Total equity trading on that day in Rupees.

Here, i have used a simpler linear regression model to predict, i have also tested other models. Now i am going for adding a feature of 
news sentimental analysis related to RELIANCE to predict the affect on next day's stock price.
