# homework-unit10

## Time Series:
In this notebook, you will load historical Dollar-Yen exchange rate futures data and apply time series analysis and modeling to determine whether there is any predictable behavior.


> **Based on your time series analysis, would you buy the yen now?**

Answer 1: Based on the ARMA and ARIMA modelling, now is not the time to buy the Yen

> **Is the risk of the yen expected to increase or decrease?**

Answer 2: the risk of the Yen is expected to increase based on the GARCH model

> **Based on the model evaluation, would you feel confident in using these models for trading?**

Answer 3: No I would not be confident using these models for trading as the P value is very high (not close to 0) and the GARCH prediction is going to increase.





## Linear Regression Forecast
In this notebook, you will build a Scikit-Learn linear regression model to predict Yen futures ("settle") returns with lagged Yen futures returns and categorical calendar seasonal effects (e.g., day-of-week or week-of-year seasonal effects).

> **Does this model perform better or worse on out-of-sample data compared to in-sample data?**

Comparing the two RMSE's, the RMSE from the in sample sample is 0.415, whereas it is 0.596 from the rolling-out-of-sample model. The fact that the two are not close to each other in value though does suggest that our model is unstable. The In Sample data performs better than the out of sample.



