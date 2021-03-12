# API Weather Analysis 

## Part I - Weather Analysis
 
In part I, a Python script was created to visualize the weather of 500+ unique cities across the world of varying distance from the equator. To accomplish this, a simple Python library and the OpenWeatherMap API were used to create a representative model of weather across world cities.

The first series of scatter plots showcases the following relationships:

- Temperature (F) vs. Latitude
- Humidity (%) vs. Latitude
- Cloudiness (%) vs. Latitude
- Wind Speed (mph) vs. Latitude

![Latitude%20vs.%20Temperature.png](https://github.com/kflores56/API-Weather-Analysis/blob/main/WeatherPy/Outputs/Latitude%20vs.%20Temperature.png)

The second series of includes a linear regression on each relationship and separates the plots into Northern Hemisphere and Southern Hemisphere:

- Northern Hemisphere - Temperature (F) vs. Latitude
- Southern Hemisphere - Temperature (F) vs. Latitude
- Northern Hemisphere - Humidity (%) vs. Latitude
- Southern Hemisphere - Humidity (%) vs. Latitude
- Northern Hemisphere - Cloudiness (%) vs. Latitude
- Southern Hemisphere - Cloudiness (%) vs. Latitude
- Northern Hemisphere - Wind Speed (mph) vs. Latitude
- Southern Hemisphere - Wind Speed (mph) vs. Latitude




## Part II - Vacation Destination Analysis

Part II starts by displaying humidity for every city from Part I.

The dataframe was then narrowed down to ideal weather conditions:

- Temperature between 21 - 24 degrees C (70 - 75 degrees F)
- Wind speed less than 10 mph.
- Zero cloudiness

Using Google Places API a hotel was located for each city  within 5000 meters. 

![Hotel_List.png](https://github.com/kflores56/API-Weather-Analysis/blob/main/VacationPy/Hotel_List.png)

The hotels were then ploted on top of the humity heatmap with each pin containing the Hotel Name, City, and Country.

![Hotel_Heatmap.png](https://github.com/kflores56/API-Weather-Analysis/blob/main/VacationPy/Hotel_Heatmap.png)
