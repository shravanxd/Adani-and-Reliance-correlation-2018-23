# correlation_adani_reliance_2018-23

The next step is to calculate the moving average of the stock prices over a given window size (10 in this case). 
The moving average is calculated using the 'rolling' function in Pandas and stored in a new column 'moving_average' in the DataFrame.

The next step is to predict future values of the stock price using the moving average. 
This is done by taking the average of the last 'window' number of moving average values. This average value is considered to be the future value of the stock price.

Finally, the code plots the stock prices ('Adj Close') and the moving average values ('Moving Average') along with the predicted future values ('Future Values') on a single plot using Matplotlib. 
The plot is displayed using the 'show' function.
