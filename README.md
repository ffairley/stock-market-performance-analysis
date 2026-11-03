# Stock Market Performance, Risk & Investment Analysis (2021–2025)

## Project Overview

This project uses Python to analyze the historical stock market performance of five major publicly traded companies: Apple, Microsoft, NVIDIA, JPMorgan Chase, and Amazon.

The analysis covers January 2021 through December 2025 and evaluates investment performance, daily returns, annualized arithmetic returns, and annualized volatility. Visualizations are used to compare stock price growth and the relationship between investment risk and return.

## Objectives

- Collect and analyze historical stock market data.
- Calculate daily stock returns.
- Compare annualized arithmetic returns across companies.
- Measure annualized volatility to evaluate investment risk.
- Visualize historical stock performance and risk-return relationships.
- Identify differences in historical performance among the selected companies.

## Companies Analyzed

| Company | Ticker |
|---|---|
| Apple | AAPL |
| Microsoft | MSFT |
| NVIDIA | NVDA |
| JPMorgan Chase | JPM |
| Amazon | AMZN |

## Tools & Technologies

- Python
- Google Colab
- Pandas
- NumPy
- Matplotlib
- Seaborn
- yfinance

## Methodology

Historical stock price data was collected using the Yahoo Finance API through the `yfinance` Python library.

The analysis included:

1. **Data Collection:** Retrieved adjusted historical closing prices from January 2021 through December 2025.
2. **Daily Returns:** Calculated percentage changes in stock prices to measure daily performance.
3. **Annualized Arithmetic Returns:** Estimated average annual returns by multiplying average daily returns by 252 trading days.
4. **Annualized Volatility:** Measured the variability of daily returns using standard deviation, annualized using the square root of 252.
5. **Data Visualization:** Created charts to compare normalized stock price performance, volatility, and risk versus return.

## Key Findings

- **NVIDIA** recorded the highest annualized arithmetic return at 66.95%, alongside the highest annualized volatility at 52.22%.
- **JPMorgan Chase** had the lowest annualized volatility at 24.27% and the second-highest annualized arithmetic return at 24.45%.
- **Amazon** recorded the lowest annualized arithmetic return at 13.60%, with the second-highest volatility at 35.11%.
- The results demonstrate that stronger historical returns were not necessarily associated with lower investment risk.

## Project Conclusion

This analysis demonstrates how Python can be used to collect, process, analyze, and visualize financial market data. Comparing annualized returns and volatility provides a clearer understanding of the historical relationship between investment performance and risk.

## Limitations

This project uses historical market data and does not account for transaction costs, taxes, or individual investor circumstances. Annualized arithmetic returns and volatility are based on historical daily returns and should not be interpreted as predictions of future performance. The analysis is limited to five selected companies and is intended for educational purposes, not as investment advice.

## How to Explore the Project

## Open in Google Colab

[Open the Stock Market Performance Analysis Notebook in Google Colab](https://colab.research.google.com/drive/1vw9cdDFd--flUMYQsogqBfqItJCdGiIk#scrollTo=EuscV4D5OdY2)



