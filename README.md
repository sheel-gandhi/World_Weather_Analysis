# World_Weather_Analysis

An analysis on World Weather using Python APIs

## Purpose

* **Perform tasks using new Python libraries and modules.**
* **Pandas, gmaps, requests, numpy, random, matplotlib, timeit, scipy, citipy, datetime, time**
* **Retrieve and use data from an API "get" request to a server.**
* **Retrieve and store values from a JSON array.**
* **Use try and except blocks to resolve errors.**
* **Write Python functions.**
* **Create scatter plots using the Matplotlib library, and apply styles and features to a plot.**
* **Perform linear regression, and add regression lines to scatter plots.**
* **Create heatmaps, and add markers using the Google Maps API.**

## Project Overview

Purpose of the project is to launch an app which will help clients find their vacation destination within 2000 randomly generatted latitudes and longitudes. We will be making a list of cities with important weather elements like Humidity, Maximum Temperature, Wind Speed, Cloudiness and current weather description. Cliens will be able to filter out cities based on their preferred temperature, find hotels within those cities and make travel itinerary for their future travel plans.  

## Results

### Weather Data

An API was generated with OpenWeatherMap and a DataFrame was created to get the initial list of potential cities. Dataframe was later downloaded in csv file. Below is the list of cities in csv file. 

![weather_db](https://user-images.githubusercontent.com/108366412/217149559-de11b9bf-55cc-4121-b8fa-80b9b20e0bb9.png)

### Travel Map

After prompting the beta testers for their minimum and maximum temperature preferences, the data frame was cleaned for null hotel entries and empty rows. Markers and pins were created for the remainder of the hotels.

![WeatherPy_vacation_map](https://user-images.githubusercontent.com/108366412/217149892-532325a7-851e-4f66-8239-0df59e8589f9.png)

### Itinerary Map

The list was narrowed down to 4 cities in the same country and a travel map was created.

![WeatherPy_travel_map](https://user-images.githubusercontent.com/108366412/217150000-a03095cc-1b83-4aa9-81f4-28dffe7fd493.png)

Makers were added to the map of four cities.

![WeatherPy_travel_map_markers](https://user-images.githubusercontent.com/108366412/217150052-c2897cd6-d967-4bb3-86af-257b9661dc20.png)
