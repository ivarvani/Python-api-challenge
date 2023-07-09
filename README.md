# Python-api-challenge
# WeatherPy
Firstly used the WeatherPy to get the different Latitudes and Longitudes.
Then used the citipy module to get the neatrest city to the random data of latitudes and longitudes we got.
Then used the openweathermap Api to get the city_data using the Cities we had got before.
Then extracted the data we required from the json_city_data. 
Formed the city_data_df.
Convereted the date in the city_data_df from timestamp format to date(dd-mm-yyyy) format. (source-(geeksforgeeks.org)).
Plotted the scattter plots required.
Formed the function to create linear regression
Got the source of icluding annotate points in the function from (stack-overflow).
Plotted the required linear regression plots.
# VacationPy
Used the City_data_df form Weatherpy and plotted the hvplot for all the cities.
Narrowed-down the city_data_df to our ideal weather condition.
Copied the required columns to our new hotel_df.
Added a new empty column for "Hotel Name".
Used the geoapify places to get the nearest hotel.
Got the data for the hotel name and stored it in the hotel_df.
Plotted the hvplot for the hotel_df data.
