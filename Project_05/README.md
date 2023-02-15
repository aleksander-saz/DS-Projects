# Project 5 - Survey of the mobile operator plans

Company "Megaline" - Federal Mobile operator rolls out new mobile plans - "Smart" and "Ultra". Based on the provided data from mobile operator it's required to analyze two plans and client's behavior to understand what plan would bring higher income to the company. 


## The main tasks for the project are following:
1) Import and analyze the data;

2) Prepare the data for the further usage:
- update data types;
- Calculate: quantity of minutes, messages, used Mb of internet, company's income per client;

3) Analyze the data:
- Describe the clients behavior on different mobile plans;
- Analyze the quantity of used minutes, messages and Mb of internet;
- Calculate average values, dispersion and standard deviation;
- plot the histograms;
- describe the type of distribution.

4) Test the Hypotheses:
- Average incomes per user on plans ultra and smart are different.
- The average income from clients in Moscow and other regions is different.


Provided data includes 5 datasets:
- calls - information on minutes usage by clients;
- internet - information on mobile internet traffic usage usage by clients;
- messages - information on messages usage by clients;
- tariffs - data on the mobile plans in company;
- users - data on the clients.

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


## Datasets description: 

1) calls dataset has 202607 rows and 4 columns: user id, call date, call id, duration;

2) tarrifs dataset - 2 rows (two plans - ultra and smart) and 8 columns:
- messages_included ;
- mb_per_month_included ;
- minutes_included ;
- rub_monthly_fee (monthly payment);
- rub_per_gb (in case of exceeding monthly package); 
- rub_per_message (in case of exceeding monthly package);
- rub_per_minute (in case of exceeding monthly package);
- tariff_name;

3) internet dataset has 149396 rows and 4 columns - session id, mb_used,session_date, user_id;

4) users dataset has 500 rows and following columns:
- client age;
- churn_date;
- client city;
- first_name;
- last_name;
- reg_date;
- tariff (plans);

5) messages dataset has 123036 rows and 3 columns with information on message id, user id and message date.
