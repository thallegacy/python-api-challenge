# Python API Challenge - WeatherPy



## Method

#### Initial Work

- Dependencies and Setup
- Import API key
- Incorporated citipy to determine city based on latitude and longitude
- Output File
- Set the range of latitudes and longitudes

#### Generate Cities List

* List for holding lat_lngs and cities
* Create a set of random lat and lng combinations
* Identify nearest city for each lat, lng combination using a loop
* Add unique cities to a our cities list
* Print the city count to confirm sufficient count

#### Perform API Calls

* Create initial empty lists for values
* Create the base url for API call
* Create counters for processing log
* Create a for loop that will allow you to go through each or the randomly generated cities
* Query url for the API call
* Set data to collect from the API call
* If/Else statement to create the processing log
  * Print processing log
* Set an exception if the city is not found by the API call
  * Print processing log error
* Display the data collected in a DataFrame
* Output the data to a csv
* Use describe to generate descriptive statistics

#### Cities humidity < 100%

- Locate cities with humidity over 100 (if applicable)
- Get the indices of cities that have humidity over 100%
- New DataFrame with humidity under 100

#### Plot Data

- Do the following
  - Plot the data (scatter)
  - Format the graph
  - Save the graph
  - Display the graph
- For all the following graphs
  - Temperature (F) vs. Latitude
  - Humidity (%) vs. Latitude
  - Cloudiness (%) vs. Latitude
  - Wind Speed (mph) vs. Latitude

#### Plot Linear Regression Data

- Create Northern & Southern Hemisphere dataframes
- Do the following:
  - Set plot variables x and y
  - linear regression model
  - Plot the graph with slope intercept
  - Set the formatting of the graph
  - Set the r-value
  - Save the graph
  - Display the information
- For all of the following graphs:
  - Northern Hemisphere - Temperature (F) vs. Latitude
  - Southern Hemisphere - Temperature (F) vs. Latitude
  - Northern Hemisphere - Humidity (%) vs. Latitude
  - Southern Hemisphere - Humidity (%) vs. Latitude
  - Northern Hemisphere - Cloudiness (%) vs. Latitude
  - Southern Hemisphere - Cloudiness (%) vs. Latitude
  - Northern Hemisphere - Wind Speed (mph) vs. Latitude
  - Southern Hemisphere - Wind Speed (mph) vs. Latitude
