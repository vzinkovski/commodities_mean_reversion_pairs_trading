**Commodities Mean Reversion Pairs Trading Strategy**

Most trading strategies can be classified as either momentum or mean reversion strategies. Commodities are often fungible, which means they can be used as substitutes for each other given the right economics. For such fungible commodities pairs, this implies both a positive correlation, as well as cointegration. Cointegration simply means that the individual price series for the two commodities cannot deviate indefinitely and will tend to revert to some mean value. This project explores a mean reverting pairs trading strategy for a select portfolio of cointegrated agricultural commodities pairs and evaluates its performance against a benchmark S&P GSCI.

Additionally, the notebook is written in a way to encourage the reader to download a copy and experiment themselves across various date ranges, commodities pairs, benchmark indexes and hyperparameter combinations in order to compare the relative performance of different strategies. The only required edits are in the code cells directly following the section headers labeled USER INPUT. Please ensure that your environment matches the dependencies listed at the end of the notebook.

**Key themes covered:**
- Computing a mean reverting spread via the hedge ratio
- Testing for stationarity
- Bollinger Bands
- Defining trading rules and generating a signal
- Equity curves
- Constructing a basic portfolio of agricultural commodities pairs
- Computing portfolio vs. benchmark returns
- Performance metrics: Sharpe Ratio, Sortino Ratio, maximum drawdown
- Defining a custom walk-forward hyperparameter optimisation function
