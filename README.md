# python-api-challenge
---
## This repository will illustrate the use of Python requests, APIs, and JSON traversals.
---
## Part 1: WeatherPy
* Section 1

    Using OpenWeatherMap API to gather data for generating scatter plots with the following variables:

    Latitude vs. Temperature

    Latitude vs. Humidity

    Latitude vs. Cloudiness

    Latitude vs. Wind Speed


* Section 2

    Creation of scatter plots with their computed linear regression and analysis. 

    Scatter plots created:

    Northern Hemisphere: Temperature vs. Latitude

    Southern Hemisphere: Temperature vs. Latitude

    Northern Hemisphere: Humidity vs. Latitude

    Southern Hemisphere: Humidity vs. Latitude

    Northern Hemisphere: Cloudiness vs. Latitude

    Southern Hemisphere: Cloudiness vs. Latitude

    Northern Hemisphere: Wind Speed vs. Latitude

    Southern Hemisphere: Wind Speed vs. Latitude

---
## Part 2: VacationPy

Using geoViews Python library, and the Geoapify API to create a map displaying data.

* Step 1

    Creating a map that displays cities in data, with a size of point determined by the humidity in that city.
* Step 2

    Filtering data by the desired parameter.
* Step 3

    Creating a copy of DataFrame with the desired variable using Pandas copy function.

* Step 4

    Using the Geoapify API  to find hotel locations within 10000 meters of coordinates in copy Dataframe.
* Step 5 

    Creating a map with copy DataFrame.
Adding the hotel and country information to the hover message for each data point on the map.
