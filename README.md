# bikes_london

**Tasks**
- Load the data, check the number of observations and columns, and check for gaps. Make sure the data types were read correctly. If necessary, cast the variables to the required types.
- Plot the number of trips by date and time.
- Transform the data and count the number of trips per day. Visualize the result.
- Use the daily aggregated data and calculate a moving average with a window of 3. As an answer, enter the number of rentals obtained for 2015-07-09, rounding up to the nearest whole number.
- Calculate the difference between the observed values and the values calculated using the moving average. Next, find the standard deviation.
- Determine the boundaries of the 99% confidence interval, add this information to the dataframe.
- Examine the abnormally high values ​​and indicate the day when the number of rentals was the highest. Find the cause of this anomaly.
- Examine the abnormally low values, find the day with the fewest rentals. Find the cause of this anomaly.

**Data Description**
- timestamp - date and time (accurate to the hour)
- cnt – number of bike rentals in this hour
- t1 – temperature, in С
- t2 - "feels like" temperature, in C
- hum - humidity (%)
- wind_speed - wind speed, km/h
-weather_code - weather conditions:
1 - clear (SKC)
2 - Mostly clear/scattered clouds occur (SCT)
3 - cloudy / significant clouds (BKN)
4 - overcast (OVC)
7 - light rain Rain / light Rain shower / Light rain
10 - rain with a thunderstorm
26 - snowfall
94 - ice fog (yes, it happens!)
- isholiday - whether the day is a holiday (1 - holiday, 0 - no)
- isweekend - whether the day is a weekend (1 - weekend, 0 - no)
- season - meteorological season (0 - spring, 1 - summer, 2 - autumn, 3 - winter)
