# World_Weather_Analysis
This project is meant to help Jack use APIs to collect, analyze, and visualize data on weather in 500+ cities. This will help his clients figure out when and where to take their desired vacations.

## Deliverable 1: Retrieve Weather Data
In this section, 2000 random latitude an dlongitude coordinates are created. APIs are used to find nearby cities (if any) and collect weather data. This information was input into a dataframe and converted into a csv.
*Results are found in the Weather_Database Folder.*

## Deliverable 2: Create a Customer Travel Destinations Map
For this section, we use the dataframe created in deliverable 1, along with customer input on what they would like the maximum & minimum temperatures to be on their vacation, to filter through the cities. Then, hotels are found in the preferred cities and added to the dataframe. From there, a map appears with pop ups that are clickable which show information about cities & hotels. 
*Results are found in the Vacation_Search Folder.*

## Deliverable 3: Create a Travel Itinerary Map
Here we use updated dataframe from deliverable 2 and the Google Directions API. Four cities from the dataframe are chosen (in the same country) and a map is created showing a route between the cities. When we specify that we are driving, a marker layer map with a pop-up marker for each city on the itinerary is created.
*Results are found in the Vacation_Itinerary Folder.*
