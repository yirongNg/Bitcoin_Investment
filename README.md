# Should your fund invest in Bitcoin?

## 🔗 Project Links
- [EDA on Jupyter Notebook](Bitcoin_Investment.ipynb)

## 📖 Background
You work as an analyst at an investment fund in New York. Your CFO wants to explore if it is a good idea to invest some of the fund's assets in Bitcoin. You have to prepare a report on this asset and how it compares to the stock market in general.

## 💾 The data
#### Bitcoin daily data in US dollars
- "date" - date from September 17, 2014 to November 17, 2021
- "open" - the price at the beginning of the trading day
- "high" - the highest price reached that day
- "low" - the lowest price reached that day
- "close" - the price at the closing of the trading day
- "volume" - how many Bitcoin were traded that day

#### S&P 500 daily data
- "date" - date from September 17, 2014 to November 17, 2021
- "open" - the index level at the beginning of the trading day
- "high" - the highest level reached that day
- "low" - the lowest level reached that day
- "close" - the level at the closing of the trading day
- "volume" - how many shares in the companies that make up the index were traded that day

#### inflation and gold as monthly data
- "date" - date from September, 2014 to November, 2021
- "gold_usd" - price in usd of gold for that month
- "cpi_us" - the inflation index for the US for that month (cpi = consumer price index)

_CPI data from the [U.S. Bureau of Labor Statistics](https://www.bls.gov/cpi/). Publicly available information_.

## 🔍 Results and Findings
1. Bitcoin dataset has more dates than S&P 500 dataset because bitcoin trading runs everyday 24/7 but S&P 500 trading only happens on business days (weekdays). Gold prices and CPI data are recorded on the 1st of every month. There are missing values in four dates of bitcoin dataset. All three asset classes (i.e. Bitcoin, S&P 500, Gold) are in a uptrend pattern. Monthly Consumer Price Index (CPI) is also on an uptrend pattern.
2. The average annual returns of Bitcoin, S&P 500, and Gold between Year 2014 and 2021 are 240.67%, 11.85%, and 1.17%, respectively. Bitcoin outperforms S&P 500 by 20 times and gold by 200 times!
3. The annualized volatility of Bitcoin is approximately 5 times higher than S&P 500. This means that Bitcoin is considered to be risky asset because it experience larger and faster price swings than S&P 500. Although Bitcoin has high percentage returns, it has significant negative returns on certain years such as 2014 (-31.27%) and 2018 (-73.48%) which are more than 10 times worst than the performance of S&P 500 and Gold. The inconsistent gains of Bitcoin and high volatility makes it impossible to hedge against inflation.
4. A hypothesis testing with a 10% significance level was conducted and the test result returned a p-value lower than the significance level. Hence, we reject the null hypothesis "Investing in Bitcoin cannot beat inflation". In order to create a low volatility fund, it is recommended to only include S&P 500 fund or perhaps no more than 5% of portfolio allocation to Bitcoin.
