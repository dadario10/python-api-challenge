# python-api-challenge
### Project Description
 - This assignment uses API's to find any connections between Latitude and Longitude and weather around the world. There are plot charts and linear regression lines to show any relationships that can be found. It also looks into specific criteria for an ideal vacation destination. Maps are generated to show these locations and hotel names are given in order to plan the perfect vacation destination.
### Summary of Contents
 - Part 1: WeatherPy
     - Using the OpenWeatherMap API to retrieve weather data from the cities list generated in the started code
     - Scatter plot to showcase the relationship between Latitude vs. Temperature
     - Scatter plot to showcase the relationship between Latitude vs. Humidity
     - Scatter plot to showcase the relationship between Latitude vs. Cloudiness
     - Scatter plot to showcase the relationship between Latitude vs. Wind Speed
     - Linear regression scatter plot for Northern Hemisphere: Temperature (C) vs. Latitude
     - Linear regression scatter plot for Southern Hemisphere: Temperature (C) vs. Latitude
     - Linear regression scatter plot for Northern Hemisphere: Humidity (%) vs. Latitude
     - Linear regression scatter plot for Southern Hemisphere: Humidity (%) vs. Latitude
     - Linear regression scatter plot for Northern Hemisphere: Cloudiness (%) vs. Latitude 
     - Linear regression scatter plot for Southern Hemisphere: Cloudiness (%) vs. Latitude
     - Linear regression scatter plot for Northern Hemisphere: Wind Speed (m/s) vs. Latitude
     - Linear regression scatter plot for Southern Hemisphere: Wind Speed (m/s) vs. Latitude 
 - Part 2: VacationPy
     - A map that displays a point for every city in the city_data_df DataFrame
     - Narrowed down the city_data_df DataFrame to find my ideal weather conditions
     - Used the Geoapify API to find the first hotel located within 10,000 metres of my narrowed DataFrame
     - Added the hotel names and the countries as additional information in the hover message for each city on the map
### Getting Started
 - This project uses "http://api.openweathermap.org/data/2.5/weather?units=Metric&APPID=" and "https://api.geoapify.com/v2/places" to pull API data in order to generate the plot graphs and maps. API keys are needed to run this file
### Acknowledgements
 - "http://api.openweathermap.org/data/2.5/weather?units=Metric&APPID="
 - "https://api.geoapify.com/v2/places"
