# WeatherPy
In this activity, a Python script is created to visualize the weather of 500+ cities across the world of varying distance from the equator. To accomplish this, 
- a simple Python library called citipy is used to sample cities
- the OpenWeatherMap API.

The objective is to build a series of scatter plots to showcase the following relationships:
- Temperature (F) vs. Latitude
- Humidity (%) vs. Latitude
- Cloudiness (%) vs. Latitude
- Wind Speed (mph) vs. Latitude

Steps include:
- Randomly select at least 500 unique (non-repeat) cities based on latitude and longitude.
- Perform a weather check on each of the cities using a series of successive API calls.
- create a print log of each city as it's being processed with the city number and city name.
- Save both a CSV of all data retrieved and png images for each scatter plot.
