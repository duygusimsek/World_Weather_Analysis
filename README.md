# World_Weather_Analysis

## Overview

### History of the Project

The purpose of the previous analysis was how to provide real-time suggestions for the PlanMyTrip app.’s clients’ preferences of hotels. For that goal, 1500 pairs of latitudes and longitudes had chosen randomly and identified 201 cities from the coordinates. Those cities’ weather data were retrieved based on clients’ weather preferences. 

Based on the data temperature, humidity, cloudiness, and wind speed were compared to latitude; and for these categories, a series of heatmaps were created. And finally, a heatmap with pop-up markers, which displays information about the city’s current max. temperature and a hotel in the city were generated. 

### Purpose of the Analysis

The previous analysis of weather data was increased to 2000 randomly selected pairs of latitudes and longitudes and identified 702 cities from the coordinates, and current weather description data was added to the dataset. For the clients of the PlanMyTrip app. input statements were provided for their weather preferences, which were used for identification of potential travel destinations and nearby hotels. 

Four cities had been chosen from the potential travel destination list and a travel itinerary was created. By using the Google Maps Directions API, a travel route between those four cities was generated and marked with information pop-up markers. 











## Resources
- Data Sources:

  * [WeatherPy_Database.csv](https://github.com/duygusimsek/World_Weather_Analysis/blob/main/Weather_Database/WeatherPy_Database.csv)
  * [WeatherPy_vacation.csv](https://github.com/duygusimsek/World_Weather_Analysis/blob/main/Vacation_Search/WeatherPy_vacation.csv)

-  Language:[Python 3.10.2](https://www.python.org/downloads)
-  Software: [Jupiter Notebook 6.3.0](https://jupyter.org/)
-  Libraries: Pandas and Numpy, Matplotlib, CitiPy, SciPy, Python Requests, APIs and JSON Traversals
