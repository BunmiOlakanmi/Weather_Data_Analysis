# Weather Data Analysis

The purpose of this project is to visualize the weather of 500+ cities across the world of varying distance from the equator.


![Equator](Images/equatorsign.png)

### Tools used in this Project
1.  Python libraries:
    - matplotlib.pyplot
    - requests
    - Pandas
    - numpy
    - time
    - json
    - scipy.stats
2.  OpenWeather API
3.  Jupyter Notebook

## WeatherPy

In this challenge, I created a Python script to visualize the weather of 500+ cities across the world of varying distance from the equator. To accomplish this, I utilized a [simple Python library](https://pypi.python.org/pypi/citipy), the [OpenWeatherMap API](https://openweathermap.org/api), and a little common sense to create a representative model of weather across world cities.

Firstly, I created a series of scatter plots to showcase the following relationships:

* Temperature (F) vs. Latitude
* Humidity (%) vs. Latitude
* Cloudiness (%) vs. Latitude
* Wind Speed (mph) vs. Latitude

After each plot, I added a sentence or two explaining what the code is and analyzing.

Secondly, I ran linear regression on each relationship, only this time separating them into Northern Hemisphere (greater than or equal to 0 degrees latitude) and Southern Hemisphere (less than 0 degrees latitude):

* Northern Hemisphere - Temperature (F) vs. Latitude
* Southern Hemisphere - Temperature (F) vs. Latitude
* Northern Hemisphere - Humidity (%) vs. Latitude
* Southern Hemisphere - Humidity (%) vs. Latitude
* Northern Hemisphere - Cloudiness (%) vs. Latitude
* Southern Hemisphere - Cloudiness (%) vs. Latitude
* Northern Hemisphere - Wind Speed (mph) vs. Latitude
* Southern Hemisphere - Wind Speed (mph) vs. Latitude

After each pair of plots,I explained what the linear regression is modeling such as any relationships I noticed and any other analysis.

The final notebook contains:

* Randomly selected, **at least** 500 unique, (non-repeat) cities based on latitude and longitude.
* A weather check on each of the cities using a series of successive API calls.
* A print log of each city as it's being processed with the city number and city name.
* Saved CSV of all retrieved data and PNG image for each scatter plot.
