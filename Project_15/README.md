# Project 15 Prediction of the quantity of taxi orders in time

Taxi company wants to analyze what time is the highest and lowest drivers load for the optimization of the cost and increase of the drivers in a peak drivers load time. Based on the provided historical data from the company (taxi orders in airports) it's required to develpo the system for prediction of the quantity of the orders in next hour.

Main tasks are:

1) Load the data and perform resampling to 1 hour.
2) Perform the data Analysis.
3) Train the models with different hypreparameters. The test samplpe shall be equal to 10% of all data.
4) Test the best model and draw a conclusion.
5) RMSE score on the best model shall not exceed 48.

Provided data includes one dataset - taxi.csv.

## Datasets description: 

Data set has  26496 rows and 2 columns:

- num_orders - quantity of orders
- datetime - date and time of ride (with step  = 10 min)
