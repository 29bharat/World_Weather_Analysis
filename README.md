# World_Weather_Analysis

## Part 1: 
Get the Weather Description and Amount of Precipitation for Each City

Steps taken:
The code from practice where 1500 random latitudes and longitudes were retrieved is taken and follwoing info was added:
Weather description - using the info from json 
Rain Inches(last 3 hrs) - using try-except method
Snow Inches(last 3 hrs) - usiing try-except method

A new dataframe was created and saved as WeatherPy_challenge.csv
No. of cities that recorded rain - 
No. of cities that recorded snow - 

## Part 2
Have Customers Narrow Their Travel Searches Based on Temperature and Precipitation

Steps taken:
We used the csv file from Part 1 above and filtered the data based on user prompts for max and min temp, rainfall(yes/no) and snow(yes/no) using the if-elif-else statement.
Hotel Name was added using the API call.
A new dataframe was craeted and saved as WeatherPy_vacation.csv
Cities with hotel info were plotted on a marker layer map along with pop up info.


## Part 3
Create a Travel Itinerary with a Corresponding Map

Steps Taken:
Direction API was enabled on GCP.
WeatherPy_vacation.csv from Part 2 dataset was the datasource for this exercise. Random 4 cities from a single country was chosen - I chose cities from Spain(ES)
Direction Layer Map from gmaps was created on these 4 cities for DRIVING.
Marker layer was added to show Hotel Name, City, Country and Current Weather with Max Temp. Thsi was saved as WeatherPy_travel_map_markers.png
