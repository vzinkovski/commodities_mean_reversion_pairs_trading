**Commodities Mean Reversion Pairs Trading Strategy**

Most trading strategies can be classified as either momentum or mean reversion strategies. Commodities are often fungible, which means they can be used as substitutes for each other given the right economics. For such fungible commodities pairs, this implies both a positive correlation, as well as cointegration. Cointegration simply means that the individual price series for the two commodities cannot deviate indefinitely and will tend to revert to some mean value. This project explores a mean reverting pairs trading strategy for a select universe of cointegrated agricultural commodities pairs.

The notebook is written in a way to encourage the reader to download a copy and experiment themselves across various date ranges, commodities pairs and hyperparameter combinations in order to compare the relative performance of different strategies.

**Key themes covered:**
- Computing the spread via the hedge ratio
- Testing for stationarity
- Bollinger Bands
- Defining trading rules and generating a signal
- Equity curves
- Constructing a basic portfolio of commodities pairs
- Computing portfolio vs. benchmark returns
- Performance metrics: Sharpe Ratio, Sortino Ratio, maximum drawdown
- Defining a custom hyperparameter optimisation function
- 
