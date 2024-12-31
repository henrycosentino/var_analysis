### Project Overview
  - The purpose of this project is to calculate the Value at Risk and analyze return distributions for a given portfolio.
### Steps Involved:
  - Read in historical stock data from yfinance.
  - Clean data frame and check data.
  - Create a comprehensive class that:
    - Calculates the portfolio’s value and daily returns
    - Tests for Normality (Shapiro Wilks) and Goodness of Fit (Chi-Square)
    - Plots a histogram of the data
    - Calculates parametric portfolio VaR
    - Calculates historic percentile VaR
  - Apply the methods inside the class to the stock data from yfinance and analyze the data and VaR
