
# Project 6  - Recommendation of the mobile phone plans for the mobile operator's company

After the completed analysis in Project 5 it's required to create a system that could predict the clients behavior and suggest to the client to switch on a new plans (such as "Smart" and "Ultra"). Using the provided data from project 5 it's required to train the classification model for selection of the optimal plan for clients.


## The main tasks for the project are following:
1) Import the data;

2) Extract the target and features and split the dataset on train, valid and test samples.

3) Train the models

4) Perform the hyperparameters tuning

5) Test the models

6) Test the efficacy of the models 

Provided data includes one dataset - users_behavior.

## Datasets description: 

users_behavior dataset has 3214 rows and 5 following columns: 
- calls - information on quantity of calls made by clients;
- minutes - information on minutes usage by clients;
- mb_used - information on mobile internet traffic usage by clients;
- messages - information on messages usage by clients;
- is_ultra - category of mobile plan (0 - "smart", 1 - "ultra")

## Mobile plans description:
1) Ultra:
 - monthly payment 1950 rubles;
 - 3000 minutes included;
 - 1000 messages included;
 - 30 gb of internet included;
 - cost of 1 additional minute (in case of exceeding monthly package) -  1 ruble;
 - cost of 1 additional message (in case of exceeding monthly package) -  1 ruble;
 - cost of 1 additional GB (in case of exceeding monthly package) -  150 rubles;

2) Smart:
 - monthly payment 550 rubles;
 - 500 minutes included;
 - 50 messages included;
 - 15 gb of internet included;
 - cost of 1 additional minute (in case of exceeding monthly package) -  3 ruble;
 - cost of 1 additional message (in case of exceeding monthly package) -  3 ruble;
 - cost of 1 additional GB (in case of exceeding monthly package) -  200 rubles;