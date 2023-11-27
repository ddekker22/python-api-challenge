# python-api-challenge

## API's and JSON traversals

This code and analysis answers the question: "What is the weather like as we approach the equator?" It takes a few hundred randomly selected longitude and latitude coordinates and inputs them into the CityPy API to determine the closest city. It then uses the OpenWeatherMap API to determine the weather for each location, and finally the GeoApify API to determine the closest hotel in each city.

An analysis was done using regression lines and scatter plots to determine the relationship between distance from the equator and specific weather conditions, such as temperature, wind speed, cloudiness, and humidity. 

Hotels were limited to locations with the following parameters: 
* Max Temperature less than 29.5 degrees Celcius
* Humidity less than 75%
* Cloudiness less than 50%
* Wind Speed less than 5 m/s

