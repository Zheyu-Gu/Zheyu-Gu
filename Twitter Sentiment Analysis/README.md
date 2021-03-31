# Twitter Sentiment Analysis on Publicly Traded Equity Securities (A, AFL, BA, CB, CCL, CDW, CERN, CI, COST, CTAS, CTVA, HD)

- **Goal:** Explore how Tweets mentioning selected stocks can affect their prices (5-minute), volumes (5-minute), and volatilities (daily)
- **Project Breakdown:**
  - *First Section:* Connect to Tweepy API using private Twitter Developer's accounts, tokenize each Tweet, clean tokens, and load 5-minute level price data
  - *Second Section:* Calculate each Tweet's polarity score by fully utilizing VADER Sentiment API, and draw Tweets' sentiment distribution for each stock
  - *Third Section:* Connect Tweet data with market data and find out impacts of Tweets' sentiments on each stock's excess return on 5-minute level basis, volume on 5-minute level basis, and volatility on daily basis
- **Project Conclusion:** Two-way relationship exists between Tweets' sentiments and 5-minute level excess returns; the volumes of stocks with relatively lower volumes are more sensitive to positive or negative Tweets; the volatilities of stocks with continuously high volatilities are more sensitive to Tweets' sentiments; but some limitations still need to be addressed in order to deploy a better and more accurate analysis.
- **Data:** Tweets from Tweepy API and selected stocks' 5-minute level prices ranging from 2020/12/01 9:30 to 2020/12/11 15:55
