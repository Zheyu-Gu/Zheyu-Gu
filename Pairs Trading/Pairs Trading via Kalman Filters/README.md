# Pairs Trading of SPY and DIA

- **Goal:** Innovate the pairs trading by using Kalman Filters to update beta and generate trading signals, and compare this trading results with the one given by traditional rolling regression approach.
- **Project Breakdown:**
  - *First Section:* Read price files and prepare data for convenient computation later
  - *Second Section:* Apply Kalman Filter to update beta throughout the time
  - *Third Section:* Backtest trading strategy given by Kalman Filter beta update
  - *Fourth Section:* Apply rolling regression to update beta throughout the time 
  - *Fifth Section:* Backtest trading strategy given by rolling regression beta update
  - *Sixth Section:* Comparison between the two methodologies in regards of their performance and beta estimates
- **Strategy Performance:** Even though the pairs trading strategy given by Kalman Filter beta update cannot outperform the market, it still can do better than the strategy given by traditional approach. One possible reason that this strategy is not profitable is that too many people may have already exploited the advantages of using pairs trading on these two popular ETFs.
- **Data:** Daily prices of SPY and DIA ranging from 2007/01/03 to 2020/02/18
