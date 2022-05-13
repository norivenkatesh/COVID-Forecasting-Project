# COVID-Forecasting-Project

COVID-19 pandemic has hit the world hard, especially in the United States where there has been no signs of an
end to it. Given the drastic impact of the pandemic on people's lives & economy, early detection of localized
COVID-19 outbreak is of paramount importance for governments to exercise strict control measures such as
lock-downs or other restrictions to minimize the impact on people and economy. So, long term forecasts for new
daily COVID-19 cases are crucial to assess the situation and adopt appropriate measures to curb the virus's
spread. In this paper, we have developed forecasts for daily new Covid cases for a 21-day horizon for the state
most impacted by COVID-19 i.e. California in USA. In addition, we have developed a highly accurate short term
7-day horizon forecast using daily mobility aggregated at state level and the CDC transmission level as additional
regressors. The daily data is fed into multiple models such as ARIMA, GARCH & deep learning models based
on LSTM and an ensemble of these models is used to generate the predictions of new COVID-19 cases. For
21-day forecast, we achieved a RMSE as low as 1589 corresponding to 41% MAPE in test data and a RMSE of
5038 (169% MAPE) in the validation data using the ensemble model. For 7-day forecast, we achieved forecasts
with RMSE of just 730 (17.66% MAPE) in validation data and RMSE of 1037 (35.66% MAPE) in test data. The
model's robust performance indicates its efficacy in forecasting new COVID-19 cases and could be could be a
great tool for efficiently managing the Covid-19 pandemic.