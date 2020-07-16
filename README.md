In the CSV you will find AAPL's historic Open - Close returns. Working in a Jupyter notebook, build a model to predict the returns

Set your window in as 3000 days and use the rest as your out sample

Your Y_hat is tomorrows return using todays data as X's

Decide which X's you would like to use (just use the historic price data provided for AAPL, no need to download other securities streams, such as NASDAQ or GOOG - there wont be too much lead lag correlation in Daily models between those names anyway). Explain why you chose the X's you did.

Decide on any regression methodology of your choice (i.e. lasso, NN, MARS regression, HMM etc.)

Show output as the following statistics:
PnL plot (using $10,000 investment on day 1 compounded throughout the 4626 days of the returns series))
Monthly return matrix (this is just monthly PnL(columns) by year (rows))
Daily return
Annualised Sharpe
Max drawdown
Performance vs. a buy – and – hold strategy