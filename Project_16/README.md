# Project 16 - Automatization processing of the comments for the online store

Online store just to rolls out new service. With new service the clients can edit and add a description of the products in the store (same as in wiki services). Clients could suggest the edits of descriptions and comment the changes of other clients. Store would like to have a tool which can classify the comments on toxic and regular. It's required to train a model for the classification of future comments.

Main tasks are:

- Import and overview the data.
- perform text lemmatization and vectorization;
- train the models;
- select best model;
- Test the model and draw a conclusion.

Provided data includes one dataset - `toxic_comments.csv`.

## Datasets description: 

Data set has 159292 rows and 2 columns:

- text -  contains text;
- toxic  -  target.
