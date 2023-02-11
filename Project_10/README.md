# Project 10 - Forecast of real estate price

Based on the provided data from real estate agency it's required using spark session to conduct an analysis, encode the data and train a regression models for the prediction of the median cost of realestate price. First model has to include only numeric features, second - numeric and categorical features.

## The main tasks for the project are following:
1) Iniate spark session and import the data;

2) Prepare the data, encode it (using One hot encoding), extract target and features, split it on train, valid samples.

3) Train the two models - using all features and only numeric features;

4) Compare the models score using RMSE, MAE and R2 scores. Test the  best model. 

Provided data includes one dataset - housing.csv.

## Datasets description: 

Data set has 20640 rows and 10 columns:

Features:
- longitude;
- latitude;
- housing_median_age - median age of residents living in residential area;
- total_rooms - total quantity of rooms in houses in residential area;
- total_bedrooms - total quantity of bedrooms in houses in residential area;
- population - quantity of residents living in residential area;
- households - quantity of houses in residential area;
- median_income - median income of residents living in residential area;
- ocean_proximity;

Target
- median_house_value - median cost of residence in residential area;