# Python-API_World-Weather

A Python script is created to visualize the weather of 500+ cities across the world of varying latitudes. 
Data obtained from the OpenWeatherMap API, and data were current of the API request date. 

Correlations between latitude and max temperature, humidity, cloudiness, and wind speed were analyzed. 
Cities were selected by randomly generating pairs of latitude and longitude coordinates, and the CitiPy Python Library was incorporated to locate the nearest city to the coordinate. Cities were unique, repeated cities were dropped. Weather check was performed on each city using a series of successive API calls. 
