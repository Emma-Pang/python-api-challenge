# python-api-challenge

#### Python API homework ####

Created a Python script to visualize the weather of 500+ cities across the world of varying distance from the equator. 

To accomplish this, I used citypy (python library) and OpenWeatherMap API to do the following-

* Randomly select at least 500 unique (non-repeat) cities based on latitude and longitude.
* Perform a weather check on each of the cities using a series of successive API calls.
* Include a print log of each city as it's being processed with the city number and city name.

Utilizing matplotlib I built various scatter plots to showcase the following relationships - 

* Temperature (F) vs. Latitude
* Humidity (%) vs. Latitude
* Cloudiness (%) vs. Latitude
* Wind Speed (mph) vs. Latitude
