# ML App to Forecast the Stock Market

## Introduction:

This project aims to develop a system that examines and tries to forecast the stock market. Stock markets are an interesting entity where the price movement or behaviour at certain times can be attributed to events that occur around the world, which in turns influences the buyers and sellers. Other example that influences the market can be the year-end tax loss sales. This is when traders sell their losses at the end of the year due to the nature of tax laws, leading to a downward price movement. However, when this event/phenomenon has been broadcast, traders then attempts to get ahead of the curve by buying these stocks in late December and selling them to expecting buyers in January. Becasue of this, the effect on the market will then be diluted. Overall it can be said that the price movement are largely influenced by the buyers and sellers themselves and their mentality behind each move. The system will attempt to build and test a trading strategy. 

## Dataset:

Data will be from the S&P 500 avaible from the last few years. The pandas package also allows for stock price data to be obtained, from Yahoo! or Google.

## Breakdown of this Project:

- Exploring the types of market analysis
- Stock Market Research
- Develop a trading System


# 1 Exploring the types of market analysis:

There are many financial instruments such as stocks, bonds, ETFs, FOREX and swaps, however, for this project, it will be limited to stocks and the stock market.

Stock: 
- Is a fractional share of ownership in a public listed company. The stock price is the price for every share.

There are also two types of investors, where the first is the fundamental analyst and the second is the technical anayst.

Fundamental analyst:
- These analyst investigates the company's financials looking for information that indicates if the market is undervaluing the shares. The factors innvestigated are revenue, earnings and cash flow, or types of ratios. Valuation of these comapanies are ususally compared to another.

Technical Analyst:
- Have a different approach where the analyst believes that the share prices reflects publicaly available infromation. They investigate historical prices (price rise, fall or stagnate) and its movements through time, where it may reveal clues regarding investor psychology.

# 2 Stock Market Research:

There are three forms mentioned in the efficient market hypothesis and these are called a weak form, a semi-strong form and a strong form. 

- The Weak Form: is where the market is considered efficient enough that the past information of prices cannot be used to predict future prices. This means that the information is reflected in stocks quickly making technical analysis ineffective and where in somoe scenarios, only fundamental analysis would be effective.

- The Semi-strong Form: is where the prices can be seen to immediately reflect relevant new public information circulating. This means that both the technical analysis and fundamental analysis would be ineffective.

- The Strong Form: is where the stock prices does reflect all public and private infromation. 

Overall, the market can be considered to be largely efficient in terms of its operations, However, often the money making opportunities occur when or during distinct intervals of market inefficiency. Such events can sometimes be detected by momentum strategies.

## 2.1 Momentum Strategies:

Momentum strategies can be summed up as stocks are ranked from the highest down to the lowest according to its return over a prior period. It has been suggested that people then to underreact to news during the short tem and proceed to overreact to news in the long term. This translate to investors failing to increase the prices sufficiently when the stocks are reacting to exceptionally good news and that it takes time for the investors to come around. This tendency can be called the anchoring effect.

## Dataset:

The dataset for this project was obtained directly from Yahoo! Using the pandas data reader package, as there are codes within the package to directly extract the data.

## Sanpshot:
Below shows a sneak peak of the price data of the S&P 500.

![Plot of Price Data](https://github.com/ylee9107/ML_App_ForecastStockMarket/blob/master/Images/Plot%20of%20Price%20Data.png)

## Required Libraries:

1. Pandas
2. Numpy
3. Pandas Datareader
4. Datetime
5. Matplotlib
6. mpl_finance
7. Potly
8. Sklearn
9. Scipy
10. Fastdtw

## Summary:

The intension of this project was to further develop my understanding in dealing with time-series data. Previously, I had undertaken a university Capstone data science project specifically looking into the FOREX market. 

For this project, it covers approaches that uses machine learning in a trading strategy. This project does not cover other important aspects of trading (for example, portfolio construction, risk mitigation, management of money etc.) whereas it ventures into creating trade signals and some trade patterns. There are many more aspects of this project that can be developed in time, and as ideas comes from further research, I will continue to update this project. 


