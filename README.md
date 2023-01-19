# World Weather Analysis
preferred travel criteria to find the ideal hotel

## Generating Weather database
A set of 2,000 random latitudes and longitudes are generated and the nearest city is retrieved by performing an API call with OpenWeatherMap. The city weather data is gathered and the current weather description for each city is saved. 

## Vacation search
Customer weather preferences is retrieved using input method. Those preferences is used to identify potential travel destinations and nearby hotels. Those destenation is saved on a map and is shown below:

![World map and possible destinations](/Vacation_Search/WeatherPy_vacation_map.PNG)

## Vacation Iternity
Customers chose to go to south africa for their trip. The Geoapify Routing API is used to create a travel itinerary that shows the route between four cities chosen from the customer’s possible travel destinations. Then, a map is created with a pop-up marker for each city on the itinerary as shown below:

![Customer Rout in South Africa](/Vacation_Itinerary/WeatherPy_travel_map.PNG)

FYI, ZA is an abbreviation of the Dutch name for the south africa country: Zuid-Afrika.
