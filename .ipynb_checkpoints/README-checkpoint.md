# Time_Series_Analysis_Project
A sample of python + pandas analysis of time series and forecasting through linear regressive modeling

# Conclusions from the Time Series Analysis

Based on your time series analysis, would you buy the yen now?

Is the risk of the yen expected to increase or decrease?

Based on the model evaluation, would you feel confident in using these models for trading?

## Responses
---
In order to determine if we should buy the yen now, first we must select the best model to assist in that decision.   In my analysis, I ran an ARMA and an ARIMA model to predict future value of the yen.  When I ran the models, I got the following Akaike Information Criterion(AIC) and Bayesian Information Criterion(BIC) results:
  <br>
> **ARMA:** ***AIC:*** 15798.142 ***BIC:*** 15832.00  <br>
> **ARIMA:** ***AIC:*** 83905.238 ***BIC:*** 83960.635 <br>
  
  
Based on these results,  I selected the ARMA model for my forecastand assessment as it had the lower scores.  According to the ARMA model, there is significant near term risk for the value of the yen to drop.  I would not invest at the current moment  due to that risk.  The GRACH model also demonstrates increasing  volatility over the next 5 periods as well which increase the risk profile of an investment at this time.  

---

# Conclusions from the Regression Analysis

## Response
---

RSME below 0.5 is considered an acceptable measure for a model to bew able to accuretely predict outcomes.  Our's models RSME is 0.5963 which is greater than the 0.5 threshold suggesting our model will poorly predict the future value of the yen.  

