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

The objective is to build a series of scatter plots to showcase the following relationships:

* Temperature (F) vs. Latitude
* Humidity (%) vs. Latitude
* Cloudiness (%) vs. Latitude
* Wind Speed (mph) vs. Latitude

It is expected that the final Jupyter notebook must:

* Randomly select at least 500 unique (non-repeat) cities based on latitude and longitude.
* Perform a weather check on each of the cities using a series of successive API calls.
* Include a print log of each city as it's being processed with the city number and city name.
* Save both a CSV of all data retrieved and png images for each scatter plot.

The notebook also contains the linear regression analyses performed on both Northern Hemisphere (greater than or equal to 0 degrees latitude) and Southern Hemisphere (less than 0 degrees latitude):

After each plot, I added a sentence or two explaining what the code is and analyzing:

* Northern Hemisphere - Temperature (F) vs. Latitude
* Southern Hemisphere - Temperature (F) vs. Latitude
* Northern Hemisphere - Humidity (%) vs. Latitude
* Southern Hemisphere - Humidity (%) vs. Latitude
* Northern Hemisphere - Cloudiness (%) vs. Latitude
* Southern Hemisphere - Cloudiness (%) vs. Latitude
* Northern Hemisphere - Wind Speed (mph) vs. Latitude
* Southern Hemisphere - Wind Speed (mph) vs. Latitude


