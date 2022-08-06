# World_Weather_Analysis
## Overview
The purpose of the project is to analyze weather data across cities worldwide and recommend ideal hotels based on PlanMyTrip's clients weather preferences. The analysis have been done by creating Pandas DataFrame with 500 or more of the world's unique cities and their weather data in real time. This process was done by collecting, analyzing, and visualizing the data.

Software : Python, Jupyter Notebook

## Analysis
The analysis was done by 
* Generating more than 1,500 random latitudes and longitudes using Numpy Module.
* Listing the nearest city to the latitudes and longitudes using CityPy  Module.
* Requesting the current weather data from each unique city in the list using OpenWeatherMap API.
* Parse the JSON data from the API request and collecting City, country, and date,Latitude and longitude,Maximum temperature,Humidity,Cloudiness and Wind speed.
The exploratory analysis has been done by plotting scatter plots and series of heatmaps using GoogleMaps API.

## Results
Based on the data collected from JSON file, heatmaps and travel maps with pop up markers were created which can display information about the city, current maximum temperature, and a hotel in the city based on a customer's travel preferences. Hotels were found from the cities coordinates using Google's Maps and Places API, and Search Nearby feature.
<img width="732" alt="WeatherPy_vacation_map" src="https://user-images.githubusercontent.com/108298416/183264083-1ed14870-d756-413b-9332-7601a73abb39.PNG">

<img width="716" alt="WeatherPy_travel_map" src="https://user-images.githubusercontent.com/108298416/183264167-8918aa2d-15ca-44d9-960f-7870ebe3f551.PNG">

<img width="717" alt="WeatherPy_travel_map_markers" src="https://user-images.githubusercontent.com/108298416/183264170-ca1b0bbf-d8c7-4743-8a66-e851e6744918.PNG">

