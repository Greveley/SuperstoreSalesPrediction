# SuperstoreSalesPrediction

Using conventional (ARIMA) and deep learning (Univariate LSTMs) to forecast superstore sales into the future. Dataset can be found here: https://www.kaggle.com/rohitsahoo/sales-forecasting

For the deep learning I have utilised a simple LSTM and a stacked LSTM to attempt to predict 7 days in advance using the previous 14 days. I'm also only using univariate LSTMs at the minute but would like to expand the model to be multivariate and compare to the univariate approach. 

## Prediction examples
To generate pseudo-probabilities from the LSTM I trained and predicted using the model N times and utilised the fact I was using Dropout in my network to regularise and produced different predictions each time. 

Here is an example of the predictions on the test set. 

![](https://github.com/Greveley/SuperstoreSalesPrediction/blob/main/plots/result.png)

