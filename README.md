# Background

Python script to visualize the weather of 500+ cities across the world of varying distance from the equator using CityPy, a simple Python library, and the OpenWeatherMap API.

The visualizations includce a series of scatter plots to showcase the following relationships:

Temperature (F) vs. Latitude Humidity (%) vs. Latitude Cloudiness (%) vs. Latitude Wind Speed (mph) vs. Latitude

The script accomplishes the following:

Randomly selects at least 500 unique (non-repeat) cities based on latitude and longitude.

Performs a weather check on each of the cities using a series of successive API calls.

Includes a print log of each city as it's being processed with the city number and city name.

Saves both a CSV of all data retrieved and png images for each scatter plot.

Observations 
Based on the data, we can conclude the following trends: 

# 1. Temperature increases as we approach the equator.  A strong correlation exists between latitude and max tempoerature.
     - As you approach the equator, temperatures get higher
     - As you move further away from the equator, temperatures get lower and plummet.

# 2. Cloudiness and humidity do not show a strong correlation to latitude. 

# 3. Wind Speed appears to slightly increase as we move away from the equator. The sampled data does not give us a definitive conclusion
