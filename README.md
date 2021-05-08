# stock-price-prediction 

OBJECTIVE:

Analysis of financial time series: Consider a time series stock values of various companies for a given duration and to find an appropriate model for the stock prediction. Compare at least with three different models. Elaborate on difficulties and alternative approaches.

METHODOLOGY:

For this project I have select three different models for prediction of stock prices.

1) EXPONENTIAL SMOOTHING: Exponential smoothing forecasting methods are similar in that a prediction is a weighted sum of past observations, but the model explicitly uses an exponentially decreasing weight for past observations. It requires parameter as follows:

                  i) Smoothing factor or Smoothing coefficient alpha (a): A value close to 1 indicates fast learning
                  (that is, only the most recent values influence the forecasts), whereas a value close to 0 indicates
                  slow learning (past observations have a large influence on forecasts).

                 ii) Smoothing factor beta (b): An additional smoothing factor is added to control the decay of the 
                 influence of the change in trend.

                iii) Seasonal component gamma (𝜸): controls the influence on the seasonal component.

2) AUTOREGRESSIVE INTEGRATED MOVING AVERAGE (ARIMA): A standard notation is used of ARIMA(p,d,q) where the parameters are substituted with integer values to quickly indicate the specific ARIMA model being used. The parameters of the ARIMA model are defined as follows:

                  a) p: The number of lag observations included in the model, also called the lag order.

                  b) d: The number of times that the raw observations are differenced, also called the degree
                  of differencing.

                  c) q: The size of the moving average window, also called the order of moving average

3) LONG SHORT TERM MEMORY (LSTM): LSTMs can be used to model univariate time series forecasting problems. This model will learn a function that maps a sequence of past observations as input to an output observation. We can divide the sequence into multiple input/output patterns called samples, where three time steps are used as input and one time step is used as output for the one-step prediction that is being learned.
