# python-api-challenge
Data Analytics Boot Camp - Module 6 Challenge - APIs - Jalaj Sharma

This challenge involves two Jupyter notebooks - WeatherPy.ipynb and VacationPy.ipynb.

The objective is to randomly select cities in the world and identify their weather patterns, using the OpenWeatherMap API, based on maximum temperature, humidity, cloudiness, and wind speed.

This allows for relationships to be investigated when comparing with the respective city's latitude. Furthermore, linear regression analysis can be conducted to quanitfy the data analysis.

WeatherPy.ipynb was used to perform the above tasks.



With the cities and their weather parameters known, a criteria for the next vacation can be developed to filter from these randomly selected cities.

My personal criteria is:

    1. Maximum temperature should not exceed 25 degrees Celsius AND should be greater than 20 degrees Celsius
    2. Not too windy with a wind speed of less than 3m/s
    3. Some cloudiness is accepted - should be 20% or less

With the above criteria, the preferred cities can be filtered.

This then allows for the GeoAPIfy API to be used for identifying the closest hotel within 10km of the city coordinates.

I can then have my pick based on my weather criteria.

VacationPy.ipynb was used to perform the above tasks.