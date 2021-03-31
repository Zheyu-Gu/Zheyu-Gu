# Time Series Analysis of Natural Gas Prices

- **Goal:** Apply ARMA and ARCH/GARCH models to predict natural gas' next daily return and volatility respectively, and draw conclusion of prediction power of each method
- **Project Breakdown:**
  - *First Part (Section 3):* Load and visualize data
  - *Second Part (Section 4-5):* Preliminary tests including stationarity test, ACF, PACF, and ARMA residual assumption test
  - *Third Part (Section 6-7):* ARMA model fitting, return prediction, and performance evaluation
  - *Fourth Part (Section 8):* Conduct volatility forecasting benchmark model, which is 15-day historical rolling window volatility forecasting
  - *Fifth Part (Section 9-12):* ARCH/GARCH model fitting of different orders, volaility prediction, and performance evaluation
- **Project Conclusion:** It is hardly feasible for ARMA to predict returns or prices of commodities due to lack of correlation with past values, but GARCH models can generally outperform 15-day historical rolling window volatility forecasting model with GARCH(1,1) being the best.
- **Data:** Natural gas daily prices ranging from 2007/10/11 to 2020/10/06
