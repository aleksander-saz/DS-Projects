# Project 12 - Definition of the prices of the cars

Car sales company would like to develop an app for the attraction of new clients, in which clients could get the market price of the car based on it's parameters. For that purpose it's required to train a model for the prediction of the car price based on the data provided from company. It's required to train several model, compare it by quality, training time, prediction time and select the best model.

## The main tasks for the project are following:
1) to import and overview data, select features and target;

2) Train the models;.

3) Compare the models and select the optimal one based on the client's needs;

Important parameters of the model for client is:

- quality of prediction;
- prediction time;
- training time.

For the models scores comparison it's required to use RMSE metric.
The score of best model shall be 2500 or less.

Provided data includes one dataset - autos.csv.

## Datasets description: 

Data set has 354369 rows and 15 columns:

Features:
- DateCrawled                      
- VehicleType;      
- RegistrationYear  - year of car being registered;  
- Gearbox - type of gearbox;
- Power - number of power;
- Model;
- Kilometer - car's milage;         
- RegistrationMonth - month of car being registered;  
- FuelType;
- Brand - car brand;        
- NotRepaired - info with car being repaired or not;      
- DateCreated - date of creation of advertisement;     
- NumberOfPictures;
- PostalCode - postal code of car region;         
- LastSeen - last time user was in app; 

Target
- price.