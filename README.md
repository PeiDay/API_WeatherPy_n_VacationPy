# Python API - What's the Weather Like?

![heatmap.png]()

## Background

### Use Python requests, APIs, and JSON traversals to per form the following:

* The script was coded using Jupyter notebook. 

* Two directory were created within this repository: **WeatherPy** and **VacationPy**.

* The OpenWeatherMap API and Google Places API were used.

* **WeatherPy** folder contains:

    * 'WeatherPy.ipynb' script.
    * An **image** folder that stores PNG files of 4 scatter plots created and linear regression plots created by `weatherpy` script.
    * 'weatherpy_cities.csv' is the cities outsput from the `weatherpy` script.

* **VacationPy**folder contains:

    * 'VacationPy.ipynb' script.
    * An **image** folder that stores a heatmap and a marker heatmap that were created by `weatherpy` script.


## Part I - WeatherPy:    
Create a Python script to visualize the weather of 500+ cities across the world of varying distance from the equator. Create a series of scatter plots to showcase the following relationships:

    * Temperature (F) vs. Latitude
    * Humidity (%) vs. Latitude
    * Cloudiness (%) vs. Latitude
    * Wind Speed (mph) vs. Latitude
    * Northern Hemisphere - Temperature (F) vs. Latitude
    * Southern Hemisphere - Temperature (F) vs. Latitude
    * Northern Hemisphere - Humidity (%) vs. Latitude
    * Southern Hemisphere - Humidity (%) vs. Latitude
    * Northern Hemisphere - Cloudiness (%) vs. Latitude
    * Southern Hemisphere - Cloudiness (%) vs. Latitude
    * Northern Hemisphere - Wind Speed (mph) vs. Latitude
    * Southern Hemisphere - Wind Speed (mph) vs. Latitude

## Part II - VacationPy:
Use Jupyter gmaps and the Google Places API to plan future vacations based on weather data.

    * Use the result of WeatherPy, setting criterias for finding ideal travel cities for this season. Present with a heatmap.
    * Find and mark the hotels on the heapmap, see below.

![hotelmarker.png]()

