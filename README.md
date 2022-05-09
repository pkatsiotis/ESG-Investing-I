# ESG-Investing
Application and analysis of ESG screening approach for portfolio selection & optimization.
First a selection strategy is applied and then mean-variance optimization is performed.
S&P 500 Stocks are used, historical prices & ESG data are from yahoo finance.

A random sample of 50 stock is selected and 5 different selection strategies are implemented:
• No screening (all 50 stocks are considered for optimization)
• Environmental screening, using the environmental score the bottom 30% quantile are screened out from the investing universe
• Social screening, using the social score the bottom 30% quantile are screened out from the investing universe
• Governance screening, using the governance score the bottom 30% quantile are screened out from the investing universe
• ESG screening, using the total ESG score the bottom 30% quantile are screened out from the investing universe

For the 5 selection strategies mean-variance optimization is performed.
The efficient frontiers and maximum sharpe ratio portfolios for each strategy are computed and compared.
The performance of the maximum sharpe ratio portfolios for each strategy are compared in-sample (2016) and out-of-sample (2017).
