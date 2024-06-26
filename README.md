# A Simple Stock Price App using Streamlit

##### This Dashboard shows Closing prices and the volume of Google stock (GOOGL).

##### I’ve been pretty interested in stock data lately; seeing if I can pick a carefully chosen selection of stocks capable of giving modest returns in the medium term. I wanted to share how even to get stock price data in the first place. It turns out that by using the very convenient Python library called yfinance, this task becomes easy.

##### Open up your Anaconda Prompt or other command prompt and type: pip install yfinance

#### The key arguments here are:
##### period: the frequency at which to gather the data; common options would include ‘1d’ (daily), ‘1mo’ (monthly), ‘1y’ (yearly)
##### start the date to start gathering the data. For example ‘2010–1–1’
##### end: the date to end gathering the data. For example ‘2020–1–25’


##### Your result should be a Pandas dataframe containing daily historical stock price data for Microsoft. 

#### Key fields include:
##### Open: the stock price at the beginning of that day/month/year
##### Close: the stock price at the end of that day/month/year
##### High: the highest price the stock achieved that day/month/year
##### Low: the lowest price the stock achieved that day/month/year
##### Volume: How many shares were traded that day/month/year
