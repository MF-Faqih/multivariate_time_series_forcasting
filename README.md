# multivariate_time_series_forcasting

In this projet, I'm trying to do forecasting on multivariate time series data, the data is about electricity consumption that recorded for one year. Machine Learning model I'm using inthis analysis are:
- Logistic regression
- K-nearest neighbbour
- ARIMA
- SARIMA with exogen variable
- Prophet

Among all 5 models, prophet has the best performance based on RMSE number. Some of the reason I can explain why prophet is better are:
- Prophet give more flexibility, we can tuning more parameters compared to other model
- ARIMA sarima work best on data with linear trend, but my data has quadratic trend
- Exogen variable have significant impact to the target variable, since only one predictor have linear relationship with the target, any other model will face endogenaity (lack of important variable) while prophet only use this variable to lower the error term.

Here, I'm also explaining step by step from model assumption to how to choose model parameters manually to get better undestanding of the model.
