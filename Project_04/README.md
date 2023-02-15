# Project 4  - Survey of the cinema distribution data

Based on the provided data from Ministry of Culture (open data from Ministry of Culture web site) it's required to analyze the market of the movies in the cinema theaters and determine the trends. Additionally it's required to analyze the movies with government support, and answer the question "Does the movies with government support are interesting to the viewers?"


The main tasks for the project are following:
1) Import and analyze the data;

2) Data preparation:
- fill the empty values;
- duplicates processing;
- analyze categorical columns;
- update the incorrect values of columns "types";
- analyze numeric columns;
- extract year when movies were issued;
- extract the name of leading director;
- extract leading movie genre;
- calculate the percentage of movies with government support;

3) Perform the exploratory analysis: 
- Analyze the quantity of issued movies per year, and it's dynamics;
- Calculate the percentage of movies with specified box office information;
- Analyze the changes of data by year;
- What year has the highest and lowest box office revenue index?;
- calculate average and median value of box office revenue per year;
- compare the revenues of movies with different types of age restriction;
- what type of age restriction movies has highest box office revenue?;
- does it changes every year?

4) Perform the analysis of movies with government support:
- analyze the amounts of governments support;
- analyze the ROI rates for movies with government support;
- analyze the ratings of such movies.

Initial data includes two data sets: mkrrf_movies and mkrf_shows.

Mkrf_movies dataset has 7486 rows and 15 columns:
- title — movie name;
- puNumber — box office id;
- show_start_date;
- type — movie type;
- film_studio;
- production_country;
- director;
- producer;
- age_restriction;
- refundable_support;
- nonrefundable_support;
- financing_source;
- budget;
- ratings — movie rating on kinopoisk;
- genres.

Mkrf_shows dataset has 3158 rows and 2 columns:
- puNumber — box office id;
- box_office — box office revenue.