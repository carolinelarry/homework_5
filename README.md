## Part 1: OpenWeatheMap API

Using the OpenWeatherMap API, I first created a series of scatter plots to showcase the following relationships:

- Temperature (F) vs. Latitude
- Humidity (%) vs. Latitude
- Cloudiness (%) vs. Latitude
- Wind Speed (mph) vs. Latitude

Then I ran linear regression on each relationship. This time, I separated the plots into Northern Hemisphere (greater than or equal to 0 degrees latitude) and Southern Hemisphere (less than 0 degrees latitude):

- Northern Hemisphere - Temperature (F) vs. Latitude
- Southern Hemisphere - Temperature (F) vs. Latitude
- Northern Hemisphere - Humidity (%) vs. Latitude
- Southern Hemisphere - Humidity (%) vs. Latitude
- Northern Hemisphere - Cloudiness (%) vs. Latitude
- Southern Hemisphere - Cloudiness (%) vs. Latitude
- Northern Hemisphere - Wind Speed (mph) vs. Latitude
- Southern Hemisphere - Wind Speed (mph) vs. Latitude

## Part 2: Google Places API

- In this part we created a heat map that displayed the humidity for every city from Part 1.

- I then narrowed down the DataFrame to find your ideal weather condition. I dropped all rows that didn't contain all three conditions I desired. You want to be sure the weather is ideal.

- Using Google Places API, I found the first hotel for each city located within 5000 meters of your coordinates

- I then plotted the hotels on top of the humidity heatmap with each pin containing the Hotel Name, City, and Country

<img width="862" alt="Screen Shot 2021-08-30 at 2 34 40 PM" src="https://user-images.githubusercontent.com/79863465/131394869-f6260c4b-a842-4969-9d07-23956e035a7f.png">
