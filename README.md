# Forecasting-of-Sales-Transactions
This was a data challenge from a company that consisted of time series forecasting.



## Task : 
For the first 10 products, please conduct the exploratory analysis and compute the forecast for the next 7 weeks.

### Dataset
https://archive.ics.uci.edu/ml/datasets/Sales_Transactions_Dataset_Weekly.

**Summary :**

- Explored the time series dataset and prepared it for different models
- Compared the models using the mean absolute error metric
- Obtained a forecast for the next 7 weeks for the first 10 products


### Conclusion
I compared a number of techniques that can be used to forecast the time series. The fbprophet gave the best performance based on the mean absolute error.

The reason I used the default values instead of the normalized values is because it wouldn't make sense to use normalized values if we are doing a separate forecast for each product. However, it would be interesting to see the differences.

Moreover, most of these models can be improved further but I didn't want to spend too much time on that and rather wanted to show different implementations for solving the problem.

Furthermore, RNN and LSTMs can be used to solve the problem as well however it would be more appropriate to use if there was a larger amount of data.
