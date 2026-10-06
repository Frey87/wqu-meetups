# WQU Meet-up: Financial Assets

**Date:** 30 September 2026  
**Format:** Online  
**Language:** Ukrainian  
**Community:** WQU Ukraine Community  

## About the Meet-up

This meet-up explored financial assets from both conceptual and
quantitative perspectives, combining financial theory with a practical
Python demonstration in Google Colab.

The session covered traditional financial instruments, digital assets,
portfolio risk, and selected institutional approaches to financial
risk management.

## Topics

- Financial and real assets
- Stocks and bonds
- ETFs
- Gold and financial exposure to real assets
- Bitcoin and digital assets
- Liquidity and market risk
- Return and volatility
- Sharpe Ratio
- Correlation and diversification
- Drawdown
- Rolling correlation
- EWMA volatility
- Value at Risk (VaR)
- Expected Shortfall (ES)
- Stress testing
- U.S. Treasury yields
- 10Y–2Y yield spread
- CPI inflation
- Macro-financial relationships
- IFRS 9 and SPPI
- Cryptoassets and IAS 32
- Tokenisation and DLT

## Google Colab / Python

The practical part uses four market exposures:

| Ticker | Description |
|---|---|
| SPY | ETF tracking the S&P 500 |
| TLT | Long-term U.S. Treasury bond ETF |
| GLD | Gold ETF |
| BTC-USD | Bitcoin |

The notebook demonstrates a progression from basic market-data analysis
to institutional risk metrics:

**Market data → Normalization → Returns → Volatility → Sharpe Ratio → 
Correlation → Drawdown → Dynamic Risk → VaR / ES → Stress Testing → 
Macroeconomic Factors**

- [Presentation (PDF)](./WQU_Financial_Assets_Presentation.pdf)
- [Google Colab / Jupyter Notebook](./WQU_Financial_Assets.ipynb)

The notebook can be opened directly in Jupyter Notebook or Google Colab.

## Data Sources and Python Libraries

The practical demonstration uses:

- `yfinance` — market data
- FRED — macroeconomic data
- `pandas`
- `NumPy`
- `Matplotlib`
- `pandas-datareader`

## Key Takeaway

> Same quantitative tools can be applied to different market-priced
> assets, but this does not mean that those assets have the same
> economic nature.

Quantitative results should therefore be interpreted together with the
economic characteristics of the asset, the data used, model assumptions,
and the relevant market environment.

## Disclaimer

The materials and calculations presented in this repository are provided
for educational purposes only and do not constitute investment,
financial, or trading advice.
