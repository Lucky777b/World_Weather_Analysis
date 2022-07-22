# World_Weather_Analysis

## Purpose

The purpose of this project was to be able to create a vacation map, where users could input a criteria of the maximum and minimum weather(in degrees) that they would prefer to have while on vacation, and this would help them to determine where they might want to plan their next vacation. The OpenWeatherMap API was used to retrieve the weather information, but it did not provide hotel names. By using a GoogleAPI, the user could see the hotel names associated with a location that matched their criteria, so it was necessary to use both API's.

## Overview 

For this project, I learned how to set up and make API calls using OpenWeatherMap and GoogleMaps. I learned how to create a random dataset of latitude and longitude coordinates, import a citipy module to find the nearest cities based on my lat/long points. Then, by using the lat/long points that were found to have an associated nearby city, I was able to create a dataframe to retrieve information about maximum temperature, percent humidity and cloudiness, wind speed, and weather description. Using that information, I created a new dataframe, and applied a user input statement for minimum and maximum weather criteria. Using that input criteria, a google map with markers would populate to show the user of places they could go vacation at that matched the user's criteria, as well as, providing information for the hotel names, city, country, and current weather (in degrees) and weather description.