Sales forecasting with PyTorch LSTM on Time Series

Objective :
Using LSTM to forecast 6 months of sales. It serve as an alternative to SARIMA/ARIMA forecasting which requires knowledge of the techniques. LSTM simply learns the sequence of the sales data and predict base on past trend. Unlike seqeunce of machinary time to failure which has higher predictability, sales is influenced by human behavior which can be erratic, thus the accuracy of prediction is less dependable.

This model outcome was compared against SARIMA forecast. With some finetuning of the model bias, LSTM prediction was similar and mirrors the trend of SARIMA very closely. The results can still be a good reference guide for companies to optmise their business operation in preparation for near future sales. Lastly, minimal tweaking of the model is necessary after the model is properly set up.
