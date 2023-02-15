# Project 14 - Prediction of the accident possibility for car sharing company

Car sharing company would like to develop system for the evaluation of the risk of accident for the selected route. As risk company understands is possibility of accident with any damage to the vehicle. The system has to evaluate the risk level just after the booking of the car by client. Current task for the company is to understand is it possible to predict the possibility of accident based on the historical data of one of the regions where company operated.

## The main tasks for the project are following:
1) connect to database and load the data;
2) overview the data;
3) perform the statistical analysis:
- analyze the statistic of accidents per month;
- prepare the list of tasks for work team (6 pcs);
- solve two of them (the tasks answer has to include query, graph and conclusion);
4) Train the models of evaluation of drivers risk (risk to be the causer of accident):
- select features which has affect on the accident;
- perform the statistical analysis of such features;
- if necessary apply rescaling and encoding;
5) Select the best model and test it;
6) Perform the analysis of importance of features that has impact on accident probability;
7) Propose the tools for reduction of driver's risk to be in accident.

Provided data includes three datasets - collisions, parties and vehicles .

## Datasets description: 

Data set collisions has 1400000 rows and 20 columns:
- case_id - table key (unique value);
- county_city_location - index of region;         
- county_location - region name;              
- distance - distance to closest city;                  
- direction - south/west/north/east;               
- intersection  -  category was it accident on crossroad or not;              
- weather_1  - type of weather : clear, cloudy, etc;                  
- location_type  - type of the road;                
- collision_damage  - type of vehicle damage: scratch, fatal, etc;
- party_count  - quantity of parties;        
- primary_collision_factor - reason of accident;
- pcf_violation_category - type of violation if applicable;
- type_of_collision;
- motor_vehicle_involved_with;
- road_surface - road surface condition: dry, wet, etc;
- road_condition_1 - type of road surface it self;
- lighting  - type of lighting in accident time;
- control_device; 
- collision_date;  
- collision_time;

Data set parties has 2752408 rows and 9 columns:
- id - table key (unique value);                   
- case_id;             
- party_number;          
- party_type - car/road sign, road bumper, etc;           
- at_fault  - 0/1  shows who's fault of accident (if 1 - the party is causer of accident)
- insurance_premium - absence/presence of premium insurance;
- party_sobriety  - type of sobriety of party
- party_drug_physical  - drug test of party
- cellphone_in_use - was party using the phone or not;

Data set vehicles has 1021234 rows and 6 columns:
- id - table key (unique value);                
- case_id              
- party_number;          
- vehicle_type ;        
- vehicle_transmission ; 
- vehicle_age; 