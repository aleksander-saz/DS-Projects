
# Project 8  - Selection of the optimal location of the drilling for the oil company

Oil company "GlavGovNeft" would like to drill new hole for oil production. Based on the provided information from company it's required to analyze the data and train the model for the prediction of estimated volume of oil in new boreholes and recommend the location of the hole to the oil company.


## The main tasks for the project are following:
1) Import the data;

2) Train the models and make the predictions:
- Split the data on train and valid samples (75/25)
- train the models and predict the valid target;
- Display the predicted quantity of product and RMSE;
- Analyze the obtained results;

3) Prepare to revenue calculation:
- to determine the key values
- find the minimum required quantity to achieve the breakeven point;

4) Declare function for calculation of revenue on selected boreholes:
- Select the boreholes with predicted maximum quantity of product:
- Calculate the sum of quantity of product in these boreholes;
- Calculate the revenue for the obtained quantity of product;

5) Calculate the risk and profit for every region:
- use bootstrap with 1000 samples, for calculation of revenue;
- Calculate the average revenue, 95% quantiles and risk of losses;
- recommend the Region for investment for the construction of boreholes.

## Additional conditions:
- during the boreholes exploration only 500 boreholes could be selected in region;
- using ML algorithms only 200 boreholes could be selected for furthe development;
- total budget is 10 billion rubles;
- price per one barrel is 450 rubles, income per one unit of product is 450 k rubles;
- only regioons with risk less than 2.5% could be selected;
- between the regions with risks less than 2.5% the region with highest profit to be selected.
- data is artifical - contract details and boreholes location is confidential information.


Provided data includes three datasets - geo_data_0,geo_data_1,geo_data_2;

## Datasets description: 

Data sets has 10000 rows and 5 columns:

Features:
- id - unqie borehole identifier;
- f0 - borehole feature;
- f1 - borehole feature;
- f2 - borehole feature;

Target
- product  - quantity of oil products (barrels)