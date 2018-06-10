# Stock Market Analysis

### Main

[Stock_Market](https://github.com/sychi77/StockMarketAnalysis/blob/master/Stock_Market.ipynb "Stock Market Analysis Jupyter Notebook") Jupyter notebook contains the main code.

[Stock_Market_Analysis_Presentation](https://github.com/sychi77/StockMarketAnalysis/blob/master/Stock_Market_Analysis_Presentation.pdf "Stock Market Analysis  PowerPoint Slides") contains the PowerPoint slides presentation.

### Summary

Inspired by Burton Malkiel's quote from *A Random Walk Down Wall Street* where he says, "A blindfolded monkey throwing darts at a newspaper's financial pages could select a portfolio that would do just as well as one carefully selected by experts."

I decided to investigate the credibility of how a portfolio of 20 random stocks will perform against the S&P500. I explore a 5+ years window from January 2013 to June 2018. This report includes a thorough time series analysis and uses ARIMA models to predict and forecast the pair of time series.

### Data

The data for the S&P500 and the 20 random stocks was collected from the [Alpha Vantage API](https://www.alphavantage.co/ "Alpha Vantage"). Data is condensed to dates after 2013 for this report. Also this limited the randomization of stocks to those that existed and have records within this time frame. Understandably this introduces a survivorship bias to the random portfolio and should be noted when exploring the report. 

Please refer to [Data_Wrangling](https://github.com/sychi77/StockMarketAnalysis/blob/master/Data_Wrangling.ipynb "Data Wrangling Jupyter Notebook") for more details.
