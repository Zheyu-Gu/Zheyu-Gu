# Comparison of Two Bollinger Band Reversal Strategies on Foreign Exchange Tradings

- **Goal:** Bollinger Band reversal strategies are mainly used in assets with mean-reversion attribute, like foreign exchanges and commodities. This project tries to compare the trading performances of Bollinger Band reversal strategies with and without trend indicators on various foreign exchanges including EURUSD, GBPUSD, USDCHF, and USDJPY. 
- **Project Breakdown:**
  - *Section (1):* Read all foreign exchange data, remove samples with no trading volume (typically during weekends), and convert time column to datetime object
  - *Section (2):* Define two trading strategies' functions, one for the strategy without trend indicators and another for the strategy with trend indicators
  - *Section (3):* Backtest both trading strategies on each foreign exchange by inputting with all combinations of parameters in the training/validation dataset, and choose the parameters giving us the highest Sharpe Ratios to be the optimized parameters which will be used for out-of-sample testing later
  - *Section (4):* Backtest both trading strategies on each foreign exchange by providing them with the optimized parameters in testing dataset; calculate performance metrics and plot informational graphs
- **Project Conclusion:** By comparing performance metrics between these two trading strategies and analytically examine generated plots, we can notice some improvements of incorporating trend filters into the basic Bollinger Band reversal strategy, but trading parameters and lengths of validation and testing datasets need to be carefully chosen to come up with significant results.
- **Data:** Hourly trading data of EURUSD, GBPUSD, USDCHF, and USDJPY ranging from 2010/11/01 to 2011/01/31
