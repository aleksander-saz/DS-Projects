

# Project 7  - Forecast of the loss of clients in the Bank

The client - "Beta-Bank" requested to analyze the reason of the loss of the client, due to the monthly clients loss. The precentage of loss of clients is minor, but bank's marketing department calculated that to keep the clients is cheaper than to attract new clients. Based on the historical data it's required to create a model for prediction of the clients behavior (will client terminate the contract with the bank soon or not) 

## The main tasks for the project are following:
1) Import the data;

2) Prepare the data, encode it, extract target and features, split it on train, valid and test samples.

3) Train the models. Analyze the classes imbalance. Apply the tool for combat to imbalance.

4) Test the model. The F1 score shall be higher than 0.59.

Provided data includes one dataset - Churn.csv.

## Datasets description: 

Data set has 10000 rows and 15 columns:

Features:
- RowNumber;
- CustomerId;
- Surname;
- CreditScore;
- Geography - client country;
- Gender;
- Age;
- Tenure - duration of being bank client in years;
- Balance - balance on the bank account;
- NumOfProducts - quantity of bank product used by client;
- HasCrCard - presence/absence of credit card;
- IsActiveMember - client activity;
- EstimatedSalary;

Target
- Exited - fact of contract termination with bank