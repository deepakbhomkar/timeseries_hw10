# timeseries_hw10
Homework 10 Time Series

# A Yen for the Future

#### Time-Series Forecasting

This notebook demonstrates the forecasting of yen prices using the time series forecasting model

The following steps were executed as part of this activity

1. Decomposition using a Hodrick-Prescott Filter (Decompose the Settle price into trend and noise).
2. Forecasting Returns using an ARMA Model.
3. Forecasting the Settle Price using an ARIMA Model.
4. Forecasting Volatility with GARCH.

## Results and Conclusions

The ARMA model has a p value > 0.05 and might not be a good fit model.


The GARCH model has a p value < 0.05 and seems to be a good fit model.

The GARCH model predicts an increase in volatility for the 5 day forecast. Hence I would not buy the yen now since it would be highly volatile and can go either way. The risk of the yen is expected to increase.
I feel confient the GARCH model can be used for trading as it highlights the volatility/risk for the future.
