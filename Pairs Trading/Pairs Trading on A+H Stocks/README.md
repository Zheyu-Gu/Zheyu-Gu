# Pairs Trading Strategies on Dual-listed Equities in Mainland China and Hong Kong Markets

- **Goal:** Test the effectiveness of applying pairs trading strategies on 10 dual-listed stocks in Mainland China and Hong Kong markets. Strategies were built based on three different methodologies, which were Engle-Granger approach (traditional cointegration method), Kalman Filter, and Law of One Price.
- **Project Breakdown:**
  - *First Section:* Read each individual equity's own historical price data and merge it with FX and indices' data to create raw dataset used for strategy implementation
  - *Second Section:* Calculate the p-value of Engle-Granger cointegration test for each A+H stock pair
  - *Third Section:* Define drawdown and strategy functions
  - *Fourth Section:* Optimize parameters used in trading strategies and find the optimal parameter combination for each strategy (Engle-Granger, Kalman Filter, and Law of One Price) on each equity under different scenarios (with and without short-selling restriction in A shares)
  - *Fifth Section:* Test each strategy's performance on out-of-sample data with corresponding optimal parameter combination
  - *Sixth Section:* Visualizations of best strategy, worst strategy, and A/H Premium
- **Project Conclusions:** 
  - In an ideal world where short-selling is permitted in A shares, pairs trading between A and H shares of same companies have high probability beating benchmarks
  - Short-selling restriction in A shares limits strategies’ capabilities of beating benchmarks, but the winning probability is still not less than 50%
  - The choice of companies used for A/H pairs trading is important, and the pairs trading strategy is not generally profitable for every A+H stocks
  - There is no significant preference between Engle-Granger and Kalman Filter strategies because Kalman Filter’s advantages cannot be exploited under this context
  - Law of One Price fails to describe A shares’ premiums over H shares, so the strategy associated to it fails to make good profit
- **Data:** 10 chosen A+H companies were the ones with the highest market capitalization in each sector. The data frequency was daily, and for each company I limited its data time range to be the overlapping trading days of its A shares, H shares, CNYHKD, CSI300 Index, and Hang Seng Index. 
