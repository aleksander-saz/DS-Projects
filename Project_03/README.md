# Project 3  - Survey of the advertisements on real estate sales

Based on the provided data from real estate company (archive of an apartment sales in Saint-Petersburg and nearest cities for the past few years) it's required to define parameters which has the highest influence on the market prices of apartments. The definition of these parameters will allow the client to develop the system of automatization of the price calculation and would tracks the anomalies and scammers activity.

For each realty it's available two types of data - recorded by user and automaticly obtained based on the map data. (such as distance to airport, citycenter, etc.)

The main tasks for the project are following:
1) Import and anylize the data;
2) Prepare the data for the further usage;
3) Calculate: 
- price per square meter; 
- day, month, year of publishing; 
- apartment floor type;
- coefficient of correlation of living area to total area;
- coefficient of correlation of kitchen area to total area;
4) Perform the explorational analysis and plot histograms for paramters: total area, price, quantity of rooms, ceiling height;
5) Calculate the average and median value of selling period; 
6) Find the cities with biggest quantity of advertisements;
7) Find what distance is considered as citycenter.
8) To conduct the analysis and find the parameters with higher effect on the price of realty in city center, in city overall and compare the results;


Data set has 23699 rows and  19 following columns: 
- total_images (quantity of images in ad);
- last_price (price on the time of closing of the ad);
- total_area;
- first_day_exposition (day of publishing)
- rooms (quantity of bedrooms)
- ceiling_height;
- floors_total (qty of floor in building);
- living_area;
- floor;
- is_apartment (bool type apartments / not);
- studio (bool type studio / not);
- open_plan (bool type yes / not);
- kitchen_area;
- balcony   (quantity of balconies)
- locality_name (name of the city)
- airports_nearest (distance to airport)
- cityCenters_nearest (distance to citycenter)
- parks_around3000 (quantity of the parks in 3 area of 3 km)
- parks_nearest (name on nearest park)
- ponds_around3000  (quantity of the ponds in 3 area of 3 km)
- ponds_nearest (name of the nearest pond)
- days_exposition (duration of the exposition of the advertisement) 