# World_Weather_Analysis
##Module6_API

For this Challege an application (app) was developed called PlanMyTrip.  This app allows the user to select a destination city to travel to based on weather conditions. Particularly a user defined API query from the OpenWeather website and data collection is acomplished with the imput of maximum and minimum temperature desired. 
see folder Weather_Database for weather data collection and database creation
!(path to weather folder) https://github.com/AnaMMoreira/World_Weather_Analysis/tree/main/Weather_Database

Further, in folder  Vacation_Search the code allows the user to imput the temperature desired and generate a database of locations meeting the criteria and a search for nearby hotels is performed using an API query on the google maps website.
a map of cities with information markers was generated and can be see as follows
!(potential destinations map)https://github.com/AnaMMoreira/World_Weather_Analysis/blob/main/Vacation_Search/WeatherPy_vacation_map.png

Lastly, the generation of a travel itinerary was performed by selection of 4 cities which met the max and  min temperatures.  The cities shown in the following example were selected within continental US for simplicity.  

see the selection map 
!(selection map)https://github.com/AnaMMoreira/World_Weather_Analysis/blob/main/Vacation_Itinerary/WeatherPy_pickCity_map.png

Using Google Maps Directions API, a map showing driving direction was also generated using start and end city selection and waypoints in between

!(driving dirrections)https://github.com/AnaMMoreira/World_Weather_Analysis/blob/main/Vacation_Itinerary/WeatherPy_travel_map.png

and lastly a map showing the selected cities with markers shoing hotel and weather conditions was also generated

!(marker map of travel itinerary)https://github.com/AnaMMoreira/World_Weather_Analysis/blob/main/Vacation_Itinerary/WeatherPy_travel_map_markers.png
