# Python-API-challenge

This project has 2 parts: WeatherPy and VacationPy. 

## Part 1: WeatherPy

In this part python script is created to visualize the weather over 500 cities with varying distance from equador. Here I used citipy Python library and OpenWeatherMap API.

   1. By using OpenWeatherMap API I retrieve weather data from cities list generated in starter code. The goal is to create plots to showcase the relationship between weather variables (temperature, humidity, cloudiness, wind speed) and latitude. Outputs of those findings can be found in output_data.
      
   2. Goal is to computee the linear regression for each relationship listed in first requirement for Northern Hemisphere and Southern Hemisphere. Also detailed analysis                      was done after each pair of plots, explaining what linear regression is modeling. Analysus can be found in Jupyter Notebook and all outputs are saved in output_data.


## Part2: VacationPy

In this part of project goal it to plan future vacation by using weather data skills. Here I used geoViews Python library and Geoapify API. Following map visualisations are created:


  1. Map that displays a point for every city in the city_data_df DataFrame. The size of the point should be the humidity in each city.

  2. Map that displays ideal weather conditions {(max.tem <27 & >21), wind speed <4.5, cloudiness zero} and for each city(that displays those ideal weather conditions) by using 
     Geoapify API located hotel in radius of 10,000m.
     


     
    
Very interesting project this was to work on. I greatly appreciate help from Learning Assistent. 
