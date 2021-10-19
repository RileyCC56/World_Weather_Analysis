# World Weather Analysis

The World Weather Analysis is a user-friendly input system that allows potential travelers to advise their preferred weather conditions. After the user provides their desired temperature travel conditions our data base will auto generate a map that provides the following cities as well as a surrounding radius of hotels within that city that meets the user’s criteria. For example, we have also created an itinerary that displays four different cities that the potential travelers can visually interact with to see all transit options.

# Tools:
Python, OpenWeatherMap API, Google Maps API, NumPy, Pandas, CitiPy, SciPy, Juptyer Notebook

# Steps needed to complete:

1. Generate a set of over 2,000 random latitudes and longitudes to retrieve the nearest cities to perform and API call on the OpenWeatherMap
2. From the API call gather the current weather description for each city
3. Create a DataFrame containing the updated weather data (Weather_Database Folder)
4. Use input statements to retrieve customer weather preferences, then use those preferences to identify travel destinations and nearby hotels. Then, show those destinations on a marker layer map with pop-up markers. (Vacation_Search Folder)
5. Using Google API Create an itinerary showing the distance between four cities for a customer’s possible travel itinerary. (Vacation_Itinerary Folder)


# Summary: 

The travel user friendly app will allow customers to search for desired travel destinations based on their temperature preferences.

As the customers have the option to filter the database based on their temperature preferences a heatmap will focus in and filter the cities that meet the criteria.

![WeatherPy_vacation_map](https://user-images.githubusercontent.com/81484054/137991376-6daaf114-d389-435f-aa82-07d4874555d1.png)

Additionally, the markers will display the following information of Hotel Name, City, Country, and real-time weather at the time of search.

![WeatherPy_Travel_map_markers](https://user-images.githubusercontent.com/81484054/137991384-f20777c1-38f4-4eb9-bdc9-f57163541b2a.png)


# Weather Database

In order to make the following come into tuition the following Open Weather Map API consists of over 720 different cities around the world that includes the following information:
 - Minimum and Maximum Temperature
 - Cloud coverage
 - Wind Speed
 - Humidity
 - Real-time Weather 

These filters make a user friendly app for our customers to specifically pinpoint their potential travel destination

# Weather Data Scatter Plots

To further conclude or analysis we have created a series of scatter plots for each weather parameter against the latitude for all cities. 

City Latitude vs. Maximum Temperature
 ![Fig1](https://user-images.githubusercontent.com/81484054/137995646-b07db4a8-e64b-4511-b577-6cb6d1ead63a.png)

City Latitude vs Humidity
![Fig2](https://user-images.githubusercontent.com/81484054/137995663-2ef3326f-70ad-40bb-8ab6-c76e2cf5c2c8.png)

City Latitude vs Cloudiness
![Fig3](https://user-images.githubusercontent.com/81484054/137995718-b15ab1e0-74c7-4df4-8d7b-423ebdda99f7.png)


City Latitude vs Wind Speed
![Fig4](https://user-images.githubusercontent.com/81484054/137995730-434b8e58-43df-4007-b263-01e9bee67de9.png)
