# Asset Allocation, Technical Analysis Of Microsoft, Tesla, Coca-Cola And Royal Bank Of Canada Stock

#INTRODUCTION
According to investment theories, Investors are assumed to be risk averse and take a rational approach to investments. One of the theories put forward to explain investment behavior is the Prospect Theory.
Prospect theory assumes that losses and gains are valued differently, and thus individuals make decisions based on perceived gains instead of perceived losses [1]. In general, if presented options between a risk-free investment and another that offers fluctuating returns and a possibility of loss, an individual will opt for the investment where they won’t lose anything (risk free investment).
For investors seeking to invest for the long term, and aiming to attain growth in their portfolios, stocks are promoted by various investment advisors as the channels that will offer growth overtime. In order to narrow down on the best portfolio to hold, there is some ground work that has to be done, in terms of asset allocation and technical analysis. 
Asset allocation is an investment strategy that aims to balance risk and reward by apportioning a portfolio's assets according to an individual's goals, risk tolerance, and investment horizon [2]. We might not be completely certain of the success of the investment venture; however, we can minimize how much we lose. Key considerations in asset allocation: investment horizon, risk, return. 
In technical analysis of stocks, a technical indicator is a mathematical calculation based on historic price, volume, or (in the case of futures contracts) open interest information that aims to forecast financial market direction [2]. Technical indicators are a fundamental part of technical analysis and are typically plotted as a chart pattern to try to predict the market trend [2].
The ultimate goal of this project is to construct an optimal portfolio that is diversified. Diversification loosely translated is “don’t put all eggs in one basket”. Diversification can be achieved in various ways, for example; spreading investments across industries / sectors, asset classes, market capitalization, risk profiles, and maturity lengths. 
DATA SETS
The sectors of interest were identified as technology, manufacturing, beverages – nonalcoholic and banks – diversified. From the identified sectors, we collected the stock prices of Microsoft Corporation (MSFT), Tesla, Inc. (TSLA), The Coca-Cola Company (KO), and Royal Bank of Canada (RY) from 2012 to 2022. 
Data are available from https://finance.yahoo.com/quote and price quotes are products are made available for use. Each data set is a time series, structured data and formatted in .csv file. Each stock dataset includes daily opening price, closing price, highest price, lowest price and volume from 2012 to 2022. 
We are interested in the price change and volume change of each stock over the eleven-year period. The dataset of each stock contains about 2770 days of price data and we use four csv files to store the data of these four stocks
METHODOLOGY
In order to achieve the set goal of the project, each project collaborator set out to answer the guiding questions below:
⦁	What is the behavior of stock over time?
This will be a timeseries analysis of the stock focusing on the price movements, the moving average of the stock prices and the trade volumes of the stock. 

⦁	What is the average return of the stock?
This is aimed at unearthing the return profile of the chosen stocks over the period. The annualized return of each of the stock over the define time period will be visualized.

⦁	What is the risk-return nature of the stock?
Standard deviation is used a measure of risk of the stock. The risk-return relationship will give an indication of the volatility of each stock.

⦁	How does the stock return compare with the market index such as S&P 500, NASDAQ Composite and the Guaranteed Investment Certificate? The Guaranteed Investment Certificate (GIC) is are secured investments with very little risk, and guarantee an investor to get back the amount invested on maturity. GICs are safe investments, however the rate offered at the onset of the contract is static and could be eroded by inflation.

⦁	What is the optimal portfolio?
A consolidation of the respective stock information is expected to yield an optimal portfolio. An optimal portfolio is one designed with a perfect balance of risk and return [4]. A simulation of the various weights of the portfolio will help us unearth the optimal portfolio and this will be the mark of success for the project.
To explore the data sets, the data cleaning was handled in Python. We will have to cater for data on weekends and stock market holidays, which are days when the stock markets are closed. The cleaned data sets were loaded to SQL database. With the help of the SQL queries, the statistics for guiding questions one to four and part of question five were generated. The output tables of the queries were visualized in Python using Matplotlib and plotly. 
