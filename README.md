# Sales-Forecating Project 

 In this Jupyter notebook, I used time series forecasting to forecast champagne sales of a company named 'Perrin Freres'. 
 I divided the data into train and test Dataframes and built a SARIMAX model to forecast sales for the next two years. 
 
 ARIMA ( AUTO REGRESSIVE INTEGRATED MOVING AVERAGE)

I took the values of all the years except 1972 as the train data and the values in the year 1972(9 months) as the test data

Monthly sales are given in millions for 12 years. I took the sales values of the last year as the test data, and the data before that as the test data. I built a SARIMA model for this data.
The procedure I used is:-

Imported the dataset to a pandas Data Frame.
Built a training and testing set.
Checked if the data was stationarity.
I made the Data Stationary using Differencing.
Built a SARIMA model.
Then I validated the data with test data.
