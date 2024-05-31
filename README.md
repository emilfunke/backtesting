# Option Trading Strategy Analysis and Backtesting

## Data Acquisition
Use the bloomberg.ipynb to prepare the semi manual download of historical option data from Bloomberg for the DAX.
Download DAX data using yfinance to get the data from Yahoo Finance. This data is stored in a pandas dataframe to compue strike prices.
Using the underlying dataframe, compute strike prices in the range of -3000 and +2000 points from the price 60 days off the strike date. 
Create the =BDH() function in excel to download the option data from Bloomberg.