# Weather-Analysis
This is an analysis of weather of 500+ cities of varying distance from the equator. Analysis of the data is included at the beginning of the Jupyter Notebook. The following analysis was conducted:
 - Ranomly selected 1500 unique cities based on latitude and longitude
 - Using successive API calls the weather was checked for each of these cities (resulting in fewer than 1500 results)
 - Each call was printed out to identify when a call was unsuccessful
 - Convert raw data to dataframe
 - All of this data was then saved to a .csv file
 - Created a scatter plot of Temperature (F) vs. Latitude and saved to .png
 - Created a scatter plot of Humidity (%) vs. Latitude and saved to .png
 - Created a scatter plot of Cloudiness (%) vs. Latitude and saved to .png
 - Created a scatter plot of Wind Speed (mph) vs. Latitude and saved to .png


API key not included. Will run if API key is supplied from OpenWeatherMap.
