# python-api-challenge
Module 6 Challenge

Code generates random lattitude and longitude locations and then proceedes to find the closest city it can find via geoapi. Once we have the cities we pull the weather data for each city and save the data.
From this data, we look for corelation between lattitude several enviromental variables (temp, humidity, wind speed, and cloudiness). My sample data very much skewed to a single latitude around the 45th latitude.
From this data it does show any corelation between latitude the other variables.

The second file, vacationPy uses the data generated by WeatherPy to look for hotels in favorable conditions in the sample dataset generate. I admit I struggled with this one because I did not know we had an example of how to use hvplots in our class material, this one was assigned as out of class hours activity which i forgot about.
