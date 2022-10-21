# World_Weather_Analysis

## Purpose
The purpose of this assignment is to construct a list of cities, and then present those cities to a hypothetical person's vacation choice.
The cities data was acquired through the generation of random numbers zipped into a list to provide latitude and longitude. Using the citipy module
city names were then established. 

These cities were then fed into an OpenWeather API in order to retrieve attributes necessary for organizing them.
The hypothetical vaction's minimum and maximum temperature was then selected, and then a Google Maps API request was used to generate a map
of the cities which lay between the temperature range, as well as selecting a nearby hotel.

Markers were added to the map to make it interactive.
