# Python_API_Challenge 

## "Part I: WeatherPy"
I'll be creating a Python script to visualize the weather of 500+ cities across the world of varying distance from the equator. To accomplish this, I'll be utilizing a simple Python library, the OpenWeatherMap API, to create a representative model of weather across world cities.

The first requirement is to create a series of scatter plots to showcase the following relationships:

1. Temperature (F) vs. Latitude
2. Humidity (%) vs. Latitude
3. Cloudiness (%) vs. Latitude
4. Wind Speed (mph) vs. Latitude

After each plot, I'll explain my code and the analysis.

The second requirement is to run linear regression on each relationship. This time, separate the plots into Northern Hemisphere (greater than or equal to 0 degrees latitude) and Southern Hemisphere (less than 0 degrees latitude):

1. Northern Hemisphere - Temperature (F) vs. Latitude
2. Southern Hemisphere - Temperature (F) vs. Latitude
3. Northern Hemisphere - Humidity (%) vs. Latitude
4. Southern Hemisphere - Humidity (%) vs. Latitude
5. Northern Hemisphere - Cloudiness (%) vs. Latitude
6. Southern Hemisphere - Cloudiness (%) vs. Latitude
7. Northern Hemisphere - Wind Speed (mph) vs. Latitude
8. Southern Hemisphere - Wind Speed (mph) vs. Latitude

After each pair of plots, I'll explain what the linear regression is modeling and include my analysis:

1. Randomly select at least 500 unique (non-repeat) cities based on latitude and longitude.
2. Perform a weather check on each of the cities using a series of successive API calls.
3. Include a print log of each city as it's being processed with the city number and city name.
4. Save a CSV of all retrieved data and a PNG image for each scatter plot.

## "Part II: VacationPy"
I'll be using jupyter-gmaps and the Google API to plan future vacations.

To do this, I'll be completing the following:
1. Create a heat map that displays the humidity for every city from Part I.
2. Narrow down the DataFrame to find your ideal weather condition.
3. Using Google Places API to find the first hotel for each city located within 5000 meters of your coordinates.
4. Plot the hotels on top of the humidity heatmap with each pin containing the Hotel Name, City, and Country.
