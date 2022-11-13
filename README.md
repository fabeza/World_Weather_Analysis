# World Weather Analysis

## Overview
In the [Weather_Database.ipynb](https://github.com/fabeza/World_Weather_Analysis/blob/525ffb8dc9d03409f6185d0995f5c55d30062313/Weather_Database/Weather_Database.ipynb) file, we generated a set of 2,000 random latitudes and longitudes, retrieve the nearest city, and perform an API call with OpenWeatherMap. In addition to the city weather data, we retrieved the current weather description for each city. Then, created a new DataFrame [WeatherPy_Database.csv](https://github.com/fabeza/World_Weather_Analysis/blob/525ffb8dc9d03409f6185d0995f5c55d30062313/Weather_Database/WeatherPy_Database.csv) containing the updated weather data. 

In [Vacation_Search.ipynb](https://github.com/fabeza/World_Weather_Analysis/blob/525ffb8dc9d03409f6185d0995f5c55d30062313/Vacation_Search/Vacation_Search.ipynb), we employed input statements to retrieve customer weather preferences. Next, we used those preferences to identify potential travel destinations and nearby hotels. Finally, we showed those destinations on a marker layer map with pop-up markers.

![WeatherPy_vacation_map.png](https://github.com/fabeza/World_Weather_Analysis/blob/525ffb8dc9d03409f6185d0995f5c55d30062313/Vacation_Search/WeatherPy_vacation_map.png)

Finally, in [Vacation_Itinerary.ipynb](https://github.com/fabeza/World_Weather_Analysis/blob/525ffb8dc9d03409f6185d0995f5c55d30062313/Vacation_Itinerary/Vacation_Itinerary.ipynb), we use the Google Directions API to create a travel itinerary that shows the route between four cities chosen from the customer’s possible travel destinations. Then, we created a marker layer map with a pop-up marker for each city on the itinerary.

Route Map
![WeatherPy_travel_map.png](https://github.com/fabeza/World_Weather_Analysis/blob/525ffb8dc9d03409f6185d0995f5c55d30062313/Vacation_Itinerary/WeatherPy_travel_map.png)

Itinerary pop-up markers
![WeatherPy_travel_map_markers.png](https://github.com/fabeza/World_Weather_Analysis/blob/525ffb8dc9d03409f6185d0995f5c55d30062313/Vacation_Itinerary/WeatherPy_travel_map_markers.png)

*Source: Bootcamp Spot Module 6 Challenge instructions*
