# AI Stock Analysis

## Overview:
This project focuses on the stock analysis of four major companies: Nvidia, AMD, Meta, and C3.ai. The analysis involves detailed statistical assessments and risk evaluation to understand the trends and volatilities in their stock prices.

## Conclution: 
- These STD values show the volatility of each of these stocks. Based on these values it is clear that NVDA is very volatile
- The mean shows the average closing price of each stock (based on 252 trading days).
- The median of all the stocks shown above shows the central tendency of all the stocks and these values or prices will remain centered as a typical market price.
- The standard deviation above for each stock shows the variation of the stock prices from the mean stock price. From our data, NVDA has a high price fluctuation.
- The standard error of the stocks above indicates that NVDA the stock price of NVDA is quite unstable since it is a bit far from the mean
- The variance shown above shows how risky these stocks are. For a risk average individual, NVDA is not the best option since it shows evidence of unpredictability.
- Each of the stocks' returns resulted in a beta that is greater than 1. This signifies that the volatility of the prices exceeds that of the market. Small cap and technology stocks typically have higher betas than the market benchmark. Therefore, adding stocks to a portfolio will raise its risk, but it may also improve its expected return.
- Based on the finding of the drawdown graphs, META is is dropping a lot, which indicates it is risky to invest in. NVDA goes up and down a lot,which makes it very unpredictable. 
- AMD has some ups and downs as well but it is not as unpredictable as NVDA. However,  AI stock is more stable and no significant changes has occurred yet.
-  AMD, AI, META and NVDA have positive correlation moving in the same direction. The return percentage over the 1,3,5 and 10 years have been moving upward . Even though past performance does not guarantee future performance , we believe there is great growth potential for investors who are still interested in getting AI  investment theme since the market for AI has not reached it peak yet.

## Files Included:
### Resources:
#### 1. Spy_prices.csv: 
  - Contains the historical stock price data for SPY Index.
#### 2. StockDataConsolidated.csv: 
  - Contains the historical stock price data for Nvidia, AMD, Meta, and C3.ai going back to 2013
### stocks.ipynb: 
  - A Jupyter notebook that includes all the coding and visualization for the analysis.

## Features of the Jupyter Notebook:

### 1. Statistical Analysis: 
- Computation of basic statistics such as mean, variance, standard deviation,  and standard  error.
### 2. Comparative Analysis: 
- Computation of rolling average to understand trends.
### 3. Visualization: 
- Plots of stock prices over time for each company to visualize trends and patterns.
### 4. Risk Analysis:
#### - Stock Beta: 
  - Calculation of beta for each stock to assess the volatility of the stocks compared to the market.
#### - Drawdown: 
  - Analysis of drawdowns to measure the potential downside risk and the volatility of each stock.

## Objective:
The aim of this project is to provide a comprehensive analysis of the selected stocks, helping to identify investment risks and opportunities based on their price behaviors and statistical metrics.

## Usage:
To run the analysis, open the stocks.ipynb in a Jupyter environment, ensuring that all dependencies are installed as outlined in the notebook. Ensure to download the necessary CSV files.
