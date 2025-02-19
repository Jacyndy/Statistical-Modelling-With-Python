# Final-Project-Statistical-Modelling-with-Python

## Project/Goals
The goal of this project is to analyze the relationship between number of available bikes and POI characteristics

## Process
* For this project I used some APIs to gsther the data for analysis. The variables of interest: POIs, number of bikes and POI characteristics(distance and number of restaurants and parks in an area).
* I also performed some data  exploration using some visualizations. 
* With the result from the EDA (cleaning and handling outliers), I built a model to analyse the relationship between number of bikes and POI charateristics
* The data used for the analysis is stored in a database using SQLite.

## Results
For this analysis I employed the CityBikes API, Foursquare and Yelp API.
* The foursquare API gives me a more complete data. The yelp data provides less data coverage. Foursquare covers more than businesses eg train staions and daycares while is mostly business.
* Though the yelp API provides information on customer reviews, for the scope of this project I will be focusing of fsq_id (number of POIs in a location) and distance to build the model.

## Challenges 
The IDE VS code used for the analysis was not calling my API keys stored as environment varaible. This implies that environment used for any programming requires to be properly set up before starting any programming.

## Future Goals
It will be important to understand how time of the day can affect the number of available bikes in an area.