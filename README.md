# World Weather Analysis
preferred travel criteria to find the ideal hotel

## Generating Weather Database
A set of 2,000 random latitudes and longitudes are generated and the nearest city is retrieved by performing an API call with OpenWeatherMap. The city weather data is gathered and the current weather description for each city is saved. 

## Vacation Search
Customer weather preferences are retrieved using the input method. Those preferences are used to identify potential travel destinations and nearby hotels. Those destinations is saved on a map and is shown below:

![World map and possible destinations](/Vacation_Search/WeatherPy_vacation_map.PNG)

## Vacation Iternity
Customers chose to go to South Africa for their trip. The Geoapify Routing API is used to create a travel itinerary that shows the route between four cities chosen from the customer’s possible travel destinations. Then, a map is created with a pop-up marker for each city on the itinerary as shown below:

![Customer Rout in South Africa](/Vacation_Itinerary/WeatherPy_travel_map.PNG)

FYI, ZA is an abbreviation of the Dutch name for the South African country: Zuid-Afrika.
