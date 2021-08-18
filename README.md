# World_Weather_Analysis

## Scope:
A travel technology company in internet related services specializing in the hotel and lodging industry has reached out for analysis. The goal is to collect and present data for customers via a search page, which can be filter based on their ideal hotel. Using Jupiter notebook and the citypi module we will get the cities of more than 500 random latitudes and longitudes to requests city weather data from open weather map API. The weather data from these cities will be added to a Panda's data frame and use the matplotlib module to create a series of scatter plots showing the relationship between the latitude and a variety of weather parameters for over 500 cities. After creating the scatter plots, we will use statistical calculations on the data using linear regression on the weather parameters in the Northern and Southern hemispheres. This data will be use to predict the best time of the year for people to plan their vacation. We will then export the clean weather data to choose the best cities for a vacation based on certain weather criteria. Finally, we will then map these cities using Jupiter, google maps and the Google places API. 

## Adjustment:
After creating the beta app described above the testers recommended a few changes to take the app to the next level. Specifically, they recommend adding the weather description to the [weather data](https://github.com/kwporras/World_Weather_Analysis/tree/main/Weather_Database) already retrieved. Then, we'll allow the beta testers to use input statements to filter the data for their weather preferences, which will be used to identify potential [travel destinations](https://github.com/kwporras/World_Weather_Analysis/tree/main/Vacation_Search) and nearby hotels. This will allow the beta tester to choose four cities to create a [travel itinerary](https://github.com/kwporras/World_Weather_Analysis/tree/main/Vacation_Itinerary) form the list of potential travel destinations. Lastly, we'll create a travel route between the four cities as well as a marker layer map using the Google Maps Directions API.

##### Resources
- Data Source: cities.csv, 
- Software: Python 3.7.10, Conda 4.10.3, Jupyter-notebook 6.3.0, 
- Module: citypi 0.0.5, matplotlib 3.3.4
- API's: [Open Weather Map](https://openweathermap.org/api), [Google Maps](https://cloud.google.com/maps-platform)


