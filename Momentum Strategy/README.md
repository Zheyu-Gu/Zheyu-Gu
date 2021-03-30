# Use Beta Hedged Momentum Strategy to Avoid Momentum Crashes

- **Goal:** Typical long/short momentum strategies are subject to momentum crashes, which lead to significant portolio losses when market scenarios change or even reverse greatly. Therefore, a rolling beta hedged momentum strategy is tested for better performance.
- **Project Breakdown:**
  - *First Section:* Description of momentum crashes and summary of the reference paper
  - *Second Section:* Comparison between DJTMNMO (long/short momentum strategy index) and MOM (ETF tracking the former index)
  - *Third Section:* Replication of DJTMNMO by using MTUM (long only momentum strategy ETF) and SPY (S&P500 ETF)
  - *Fourth Section:* Our proposed market neutral momentum quantitative strategy
- **Strategy Performance:** Comparing to the benchmark DJTMNMO, our strategy has 8% higher annualized return, 56% lower annualized volatility, and 94% higher Sharpe Ratio.
- **Reference Paper:** Momenum Crashes by Kent Daniel and Tobias J. Moskowitz
