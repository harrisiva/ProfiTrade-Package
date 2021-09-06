# ProfiTrade-Package 0.0.3
A proprietary open-source fintech python package with a plethora of features for building equity and cryptocurrency trading algorithms.
## Features
### Data.Price
Crypto (Class): 
- Historical: This function takes the interval and outputsize as parameters, using the alpha vantage API, it returns a df with historical price data.
- Current: If toAppend (parameter) is set true, the function takes in a pandas dataframe and appends the current price data. Else, when toAppend is false, using the alpha vantage API, it returns a df with the current crypto exchange rate.

Stock (Class):
- historicalIntraday: This function takes the interval and outputsize as parameters, using the alpha vantage API, it returns a df with historical intraday price data.
- historicalIntradayExtended: This function takes the interval as parameters, using the alpha vantage API, it returns a df with extended historical intraday price data.
- historicalDaily: This function takes the outputsize as parameters, using the alpha vantage API, it returns a df with historical daily price data.
### Indicators.Technical
- SMA(func.):      Given a pandas dataframe, this function calculates and adds simple moving average.
- RSI(func.):      Given a pandas dataframe, this function calculates and adds relative strength index.
- EMA(func.):      Given a pandas dataframe, this function calculates and adds expotential moving average.
- MACD(func.):     Given a pandas dataframe, this function calculates and adds Moving Average Convergence Divergence.
- BOLBANDS(func.): Given a pandas dataframe, this function calculates and adds the Boll. Bands.

### Screen.Finviz
.Quantitative:
- MostVolatile
- MostActive
- TopGainers

.Technical:
- HorizontalSupportResistance
- SidewaysHighVolume
- SidewaysChannel

## Upcomming Features
- Multiple trade logging functions (xl, csv, email, pandas etc.)
- Catalyst (Using ML to differentiate between negative and positve news, social media sentiment etc.)
- Fundemental Analysis (Based on financial ratios, financial health and future cash flow models etc.)
- Economic Analysis (Using bond yields, interest rates, fed decisions)
- Financial Data (Cash flow and other financial statements)
- Technical Analysis
- Any many more comming soon for free!
