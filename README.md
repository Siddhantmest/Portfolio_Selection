# Portfolio Selection Strategies

In this project we are trying to compare various computational investment strategies implemented for 2 different timeframes to get a better understanding about them. We are trading only 20 stocks. There are 12 holding periods and each holding period lasts 2 months (2 years in total). As a result, you can re-balance your portfolio at most 12 times. Each transaction has a cost composed of a variable portion only. The variable fee is due to the difference between the selling and bidding price of a stock, and is 0.5% of the traded volume.

The trading strategies implemented are - 
* `Buy and hold`: it is the simplest strategy where you hold initial portfolio for the entire investment horizon of 2 years.
* `Equally weighted`: asset weights are selected as w_i = 1/n, where n is the number of assets.
* `Minimum variance`: compute minimum variance portfolio for each period and re-balance accordingly.
* `Maximum Sharpe ratio`: compute a portfolio that maximizes Sharpe ratio for each period and re-balance accordingly.
* `Equal risk contributions`: compute a portfolio that has equal risk contributions to standard deviation for each period and re-balance accordingly.
* `Leveraged equal risk contributions`: take long 200% position in equal risk contributions portfolio and short risk-free asset for each period and re-balance accordingly.
* `Robust mean-variance optimization`: compute a robust mean-variance portfolio for each period and re-balance accordingly.