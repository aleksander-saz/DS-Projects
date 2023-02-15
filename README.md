# Data-Scientist-Projects
<hr />

<h1> Certificate:</h1>

https://github.com/aleksander-saz/DS-Projects/blob/main/Certificate/Certificate_ENG.pdf
____

This repository is mainly for projects I've completed during Yandex Practicum Data Scientist Courses.

Yandex Practicum Data Scientist programme prepared me for a career of a data analyst/scientist by helping learn to clean and organize data, uncover pattern and insights, prepare the data for the machine learning, train the models considering the business tasks, make the predictions and draw a meaningful conclusions. I am developing proficiency in Python and it's data analysis and machine learning libraries and SQL as I build a portfolio of projects.

`Tip:` For data science project I would recommend to install the following libraries: numpy, pandas, scipy, sklearn, matplotlib, seaborn, SQLAlchemy, tensorflow, python, keras.

<hr />

## Part 1 - Intro to Data Analysis

**Subject Covered:**

-  Python: main python tools, different data types -  lists, arrays, dictionaries, etc., loops,functions;
-  Main tools of pandas library;
-  Data analysis - starting from tasks definition to visualization of results and conclusion;
-  Data preparation: nulls processing, changing data types, duplicates processing, data categorization;
-  Exploratory Data Analysis: graphs and histogram plotting, join and merge of datasets, slice the data, definition and interpretation of data correlation, automatization of graph plotting.
-  Statistics, Pyplot, lemmatization, Jupyter Notebook.

### Project 1 - Survey of the users behavior in yandex music app

Based on the provided data of yandex music app it's required to carry out the analysis using pandas library and find the most popular genres in Saint-Petersburg and Moscow. 

*Detailed description you can find in [readme of Project 1](https://github.com/aleksander-saz/DS-Projects/tree/main/Project_01)*

### Project 2  - Survey of the reliability of the bank clients

Based on the provided data from client (Credit department of the Bank) it's required to analyze the data using pandas library and summarize how does the marital status and quantity of child are influence on the payment of outstanding fees in the specified duration in credit contract.

*Detailed description you can find in [readme of Project 2](https://github.com/aleksander-saz/DS-Projects/tree/main/Project_02)*

### Project 3  - Survey of the advertisements on real estate sales

Based on the provided data from real estate company (archive of an apartment sales in Saint-Petersburg and nearest cities for the past few years) it's required to define parameters which has the highest effect on the market prices of apartments. The definition of these parameters will allow the client to develop the system of automatization of the price calculation and would tracks the anomalies and scammers activity.

*Detailed description you can find in [readme of Project 3](https://github.com/aleksander-saz/DS-Projects/tree/main/Project_03)*

### Project 4  - Survey of the cinema distribution data

Based on the provided data from Ministry of Culture (open data from Ministry of Culture web site) it's required to analyze the market of the movies in the cinema theaters and determine the trends. Additionally it's required to analyze the movies with government support, and answer the question "Does the movies with government support are interesting to the viewers?"

*Detailed description you can find in [readme of Project 4](https://github.com/aleksander-saz/DS-Projects/tree/main/Project_04)*

<hr />

## Part 2 - Statistics and intro to Machine Learning

**Subject Covered:**

- Statistics: selection of suitable metrics for data description, definition of histograms types required for evaluation of distinct and continuos values, making a conclusion based on the statistical data, probability theory, identification and calculation of standard an binominal distributions, building and testing of hypotheses;
-  Intro to machine learning: standard regression and classification models, algorithms of training, training of models and evaluation using sklearn library, studying and testing of models.
- Machine learning: classification metrics: precision, recall, F1, AUC-ROC, measure the classes weight, combat to imbalance: upsample, downsample, setting the thresholds, Regression: evaluate the the quality of models with R2 and MAE scores;
- Machine learning in business: to differ the offline and online metrics, calculation of confidence limits and metrics using bootstrap, to use cross-validation for model quality testing.


### Project 5 - Survey of the mobile operator plans

Company "Megaline" - Federal Mobile operator rolls out new mobile plans - "Smart" and "Ultra". Based on the provided data from mobile operator it's required to analyze two plans and client's behavior to understand what plan would bring higher income to the company. 

*Detailed description you can find in [readme of Project 5](https://github.com/aleksander-saz/DS-Projects/tree/main/Project_05)*

### Project 6  - Recommendation of the mobile phone plans for the mobile operator's company

After the completed analysis in Project 5 it's required to create a system that could predict the clients behavior and suggest to the client to switch on a new plans (such as "Smart" and "Ultra"). Using the provided data from project 5 it's required to train the classification model for selection of the optimal plan for clients.

*Detailed description you can find in [readme of Project 6](https://github.com/aleksander-saz/DS-Projects/tree/main/Project_06)*

### Project 7  - Forecast of the loss of clients in the Bank

The client - "Beta-Bank" requested to analyze the reason of the loss of the client, due to the monthly clients loss. The percentage of loss of clients is minor, but bank's marketing department calculated that to keep the clients is cheaper than to attract new clients. Based on the historical data it's required to create a model for prediction of the clients behavior (will client terminate the contract with the bank soon or not) 

*Detailed description you can find in [readme of Project 7](https://github.com/aleksander-saz/DS-Projects/tree/main/Project_07)*

### Project 8  - Selection of the optimal location of the drilling for the oil company

Oil company "GlavGovNeft" would like to drill new hole for oil production. Based on the provided information from company it's required to analyze the data and train the model for the prediction of estimated volume of oil in new boreholes and recommend the location of the hole to the oil company.

*Detailed description you can find in [readme of Project 8](https://github.com/aleksander-saz/DS-Projects/tree/main/Project_08)*

### Project 9  - Forecast of client loss for the hospitality company 

Hospitality company "As home" wants to increase the costumers flow. For that purpose company added an option to book the room without prepayment, however company has faced the losses of income in a case of booking cancellation. To solve this issue company wants to develop the System which will predict the booking cancellation. In case of possible cancellation of booking hospitality company client has to make a prepayment of 80% of cost of booking.

*Detailed description you can find in [readme of Project 9](https://github.com/aleksander-saz/DS-Projects/tree/main/Project_09)*

<hr />

## Part 3 - SQL, Linear Algebra, Calculus, Neural Networks

**Subject Covered:**

- SQL: writing of queries of different difficulty, slicing the data, writing frame queries, aggregate functions, joining and merge tables, etc; SQL-alchemy library, postgre sql;
- Spark:Mllib: using the system of storage and processing of big data, using Spark;
- Linear Algebra: operations with matrices and vectors, creating classes of machine learning, linear regression principle of operation.
- Calculus: to calculate the difficulty of algorithms, training the gradient boosting model, using the gradient boosting in business; 
- Neural Networks: difference of neural networks to standard ML models, building a nd training of neural networks using Pytorch, hyperparameter tuning of NN.

### Project 10 - Forecast of real estate price

Based on the provided data from real estate agency it's required using spark session to conduct an analysis, encode the data and train a regression models for the prediction of the median cost of real estate price. First model has to include only numeric features, second - numeric and categorical features.

*Detailed description you can find in [readme of Project 10](https://github.com/aleksander-saz/DS-Projects/tree/main/Project_10)*

### Project 11 - Personal data protection in insurance company

Insurance company would like to develop a method of protection of client's personal data. It's required to have an option to get the original information (unprotected personal data) after the completion of such protection. The quality of the model prediction shall be the same on the original and protected data. The protection of the personal data shall be done using the matrix operations.

*Detailed description you can find in [readme of Project 11](https://github.com/aleksander-saz/DS-Projects/tree/main/Project_11)*

### Project 12 - Definition of the prices of the cars

Car sales company would like to develop an app for the attraction of new clients, in which clients could get the market price of the car based on it's parameters. For that purpose it's required to train a model for the prediction of the car price based on the data provided from company. It's required to train several model, compare it by quality, training time, prediction time and select the best model.

*Detailed description you can find in [readme of Project 12](https://github.com/aleksander-saz/DS-Projects/tree/main/Project_12)*

### Project 13 - Prediction of the star temperature

Astronomy company would like to define the temperature on the surface of the newly spotted stars. For that purpose it's required to predict the star temperature using machine learning and based on the previous data from the database of the stars.

*Detailed description you can find in [readme of Project 13](https://github.com/aleksander-saz/DS-Projects/tree/main/Project_13)*

### Project 14 - Prediction of the accident possibility for car sharing company

Car sharing company would like to develop system for the evaluation of the risk of accident for the selected route. As risk company understands is possibility of accident with any damage to the vehicle. The system has to evaluate the risk level just after the booking of the car by client. Current task for the company is to understand is it possible to predict the possibility of accident based on the historical data of one of the regions where company operated.

*Detailed description you can find in [readme of Project 14](https://github.com/aleksander-saz/DS-Projects/tree/main/Project_14)*

<hr />

## Part 4 - Time Series, NLP, Computer Vision

**Subject Covered:**

- Time Series: analysis of time series, trends and seasonality, creating of time series features, training of models on time series datasets.
- NLP: Text processing, lemmatization, tokenization, vectorization, using TF-IDF, Word2Vec, Bert models, training of models on text;
- Computer Vision: Training of neural networks using Keras Library, Building the Sequential and convolution neural networks, building of neural networks using ResNet architecture.
 
### Project 15 - Prediction of the quantity of taxi orders in time

Taxi company wants to analyze what time is the highest and lowest drivers load for the optimization of the cost and increase of the drivers in a peak drivers load time. Based on the provided historical data from the company (taxi orders in airports) it's required to develop the system for prediction of the quantity of the orders in next hour.

*Detailed description you can find in [readme of Project 15](https://github.com/aleksander-saz/DS-Projects/tree/main/Project_15)*

### Project 16 - Automatization processing of the comments for the online store

Online store just to rolls out new service. With new service the clients can edit and add a description of the products in the store (same as in wiki services). Clients could suggest the edits of descriptions and comment the changes of other clients. Store would like to have a tool which can classify the comments on toxic and regular. It's required to train a model for the classification of future comments.

*Detailed description you can find in [readme of Project 16](https://github.com/aleksander-saz/DS-Projects/tree/main/Project_16)*

### Project 17 - Prediction of the clients age for the grocery store

Grocery store wants to use computer vision system for the clients photos processing for definition of their ages. It would help the store to analyze the purchases and suggest the relevant products for the exact clients age group, in addition it would check the cashier behavior during the sell of the age restricted products in accordance with compliance with law. For the realization of such tool it's required to train a model which predicts the approximate age of the client by the photo.

*Detailed description you can find in [readme of Project 17](https://github.com/aleksander-saz/DS-Projects/tree/main/Project_17)*

### Project 18 - Development of the model for search of image by text query

Photo hosting for the professional photographers wants to develop the service of the searching tool for the search of similar photos by text query. Users of hosting can upload the photos with full description such as place, date, camera model, etc and also can add a description to the photos of others users. Based on the provided data from hosting it's required to develop preliminary version of tool which could find the most suitable image by  text query.

*Detailed description you can find in [readme of Project 18](https://github.com/aleksander-saz/DS-Projects/tree/main/Project_18)*

<hr />

## Graduation project - Prediction of steel temperature on steel manufacturing

Steel manufacturing company requested to develop the system for the prediction of steel temperature for the optimization of electricity costs. Based on the provided data from company it's required to conduct an analysis and train a models for the prediction of the steel temperature.

*Detailed description you can find in [readme of Project 19](https://github.com/aleksander-saz/DS-Projects/tree/main/Project_19)*
