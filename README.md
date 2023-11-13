# python-api-challenge
## Overview

This project aims to analyze weather data from various cities using the OpenWeatherMap API and visualize the 
relationships between weather parameters and latitude. Additionally, it helps users find hotels based on their preferred weather conditions using the Geoapify API.

## Part 1: WeatherPy

In this part, I perform the following tasks:

1. **Data Retrieval**: Use the OpenWeatherMap API to retrieve weather data for a list of cities generated in the code.

2. **Scatter Plots**: Create scatter plots to visualize the relationships between latitude and the following weather parameters:
   - Temperature
   - Humidity
   - Cloudiness
   - Wind Speed

3. **Linear Regression Analysis**: Perform linear regression analysis for each of the relationships mentioned above. This includes both Northern and Southern Hemisphere analysis.

## Part 2: VacationPy

In this part, we create a map and find hotels based on specific weather conditions:

1. **Map Generation**:  Generate a map that displays a point for every city in the `city_data_df` DataFrame.

2. **Narrow Down Weather Conditions**: Narrow down the list of cities in the `city_data_df` DataFrame to find cities that match user-specified ideal weather conditions.

3. **Find Hotels**: Use the Geoapify API to find the first hotel located within 10,000 meters of user-specified coordinates for each city in the `hotel_df` DataFrame.

4. **Add Hotel Information to Map**: Add  the hotel name and country as additional information in the hover message for each city on the map.
