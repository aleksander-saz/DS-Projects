# Project 13 - Prediction of the star temperature

Astronomy company would like to define the temperature on the surface of the newly spotted stars. For that purpose it's required to predict the star temperature using maching learning and based on the previos data from the database of the stars.

## The main tasks for the project are following:
1) import and prepare data;
2) perform the exploratory analysis;
3) rescale the data, and split it on train and test samples;
4) build neural networks;
- decalre the function for training and prediction;
- plot the comparison chart of actual and predicted star temperature;
5) perfom the network tuning (using dropout, optimisers, qunatity of layers, activation functions);
6) Compare and select most suitable model for the star temperature prediction.

The score of best model shall be 4500 or less.

Background Information:
- Average Luminosity of Sun) =3.828,10 
- Average Radius of Sun)  =6.9551,10 

Provided data includes one dataset - data_stars.csv.

## Datasets description: 

Data set has 240 rows and 6 columns:

Features:
- relative luminosuty L/Lo  - star luminosity compare to Sun luminosity;
- relative radius R/Ro - star raius compare to radius of Sun;
- Absolute star magnitude Mv - physical value, describing the star shining;
- Star color (white, red, blue, yellow, yellow-orange , etc.). Star color determined during spectral analysis.
- Star type. Number, correspondant to type:
    - 0 brown dwarf;
    - 1 red dwarf;
    - 2 white dwarf;
    - 3 Main sequence star;    
    - 4 supergiant;    
    - 5 hypergiant;

Target
- Absolute temperature T(K) - temperature on the star's surface (Kelvin).