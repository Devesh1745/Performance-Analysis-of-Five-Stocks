# Performance-Analysis-of-Five-Stocks
Stock analysis involves comparing a company's current financial statement to its financial statements in previous years to give an investor a sense of whether the company is growing, stable, or deteriorating


<img src="6240060.jpg" width=1000>

## Collecting market data from Yahoo! Finance's API
<img src="Image/f650839d-8d70-4b36-9d8c-8a8dc16817cb.png" alt="logo" width="300" height="200"/>


# Overview
Collecting historical stock price data of various companies from trusted sources such as Yahoo Finance.

This project focuses on performing a detailed analysis of five Indian stocks — Titagarh, TCS, Motherson, CDSL, and HDFC — using historical market data from January 2022 to March 2025. Leveraging Python libraries like yfinance, pandas, numpy, matplotlib, and seaborn, the notebook extracts and analyzes daily stock prices, returns, volumes, and other performance metrics. The goal is to uncover patterns in stock behavior across different weekdays and months, assess risk versus return tradeoffs, and identify inter-stock correlations.

The analysis is designed to support data-driven investment decisions by highlighting periods of strong performance, volatility, and optimal portfolio diversification opportunities. Through visualizations and metrics, this project translates raw data into actionable financial insights.


# Insights
🧪 Stock Behavior :
Titagarh shows the highest expected daily return but also carries the highest risk (volatility).
HDFC and Motherson appear to be more stable but offer lower returns ideal for conservative investors.

📅 Weekday Performance :
Friday yields the highest average returns overall, particularly for Titagarh.
Monday tends to be more volatile and underperforming a potential "risk day" for investing.

📆 Monthly Seasonality :
Strongest returns were observed in June, April, and November.
February shows significant negative returns potentially a good time to avoid new entries.

📈 Volume vs. Return Trends :
High trading volumes don’t always translate to high returns.
Motherson and HDFC had consistently high volumes, indicating strong liquidity.

🔁 Correlation Analysis :
TCS and Motherson are highly correlated 0.89, meaning they tend to move together.
HDFC is less correlated with others good for portfolio diversification.






# Recommendations
1. Aggressive investors may consider Titagarh for its high returns, especially when timed around favorable months June, April.
2. Risk-averse investors could favor HDFC or Motherson for stability and liquidity.
3. Avoid high exposure during February and cautiously approach Mondays due to observed underperformance.
4. For portfolio balancing, include less correlated stocks like HDFC to minimize total risk.
5. Monitor correlated pairs (like TCS & Motherson) for paired trades or risk management.
