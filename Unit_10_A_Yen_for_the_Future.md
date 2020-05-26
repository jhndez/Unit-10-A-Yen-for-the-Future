* Using Time Series analysis to uncover investing tips for the relationships between the Yen and the USD. 

The settle price never went above 10,000 nor lower than 8000 with high volatility for most of 2016. It seems the price has leveled out since 2016.  

** Forecasting Settled returns using the ARMA model, see notebook.

What does the p-value mean in this ARMA model and is the model a good fit?

No this ARMA model is not a good fit, the p values are entirely too high. 

** Forcasting using the ARIMA model

The ARIMA model is significantly better than the previous model, with p values much closer to 0.05 (and one decidedly under (lag day 5, 0.028 ). 

In the near term the yen will bottom out on day 3 of the prediction (9222.0), and rocket upwards on the 4th day (9225 +). 

** Forecasting with GARCH

Garch has the best p-values of the previous models. The next 5 days as predicted by the model will increasingly become more volatile, presenting the buying opportunity identified with the ARIMA model. 

** Time Series Conclusions 

In the time period my previous models have analyzed, and considering my personal risk profile. I would purchase the YEN. I like to take on risk, and currently the Japanese economy is also better prepared post-COVID than others in my opinion, the YEN could be very strong in the future compared to the past. The Garch model predicted much more risk involved. 

However the models I used (ARMA and ARIMA) had poor p value performance, so much more due diligence must be performed in this case. I would not be confident in using these models for this particular trade. 

* Using Linear Regression analysis to uncover investing tips for the relationships between the Yen and the USD.

**Rolling Out-of-Sample Root Mean Squared Error (RMSE): 0.40333088574733467

The analysis is below 0.5 which is generally good. 