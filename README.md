# Madrid-daily-weather-analysis
Daily weather conditions in Madrid from 1997-2015, including max/min/mean temperature, dew point, humidity, visibility, and wind speed, along with precipitation events, cloud cover and wind direction.

![](https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcSTpcTDmrMoa1PGbWYiEx3lTcjW1TOCTv6mlg&usqp=CAU)

**Data set Description**
The dataset has 6812 rows and 23 columns.

 0   CET                          6812 non-null   datetime64[ns]
 1   Max TemperatureC             6810 non-null   float64       
 2   Mean TemperatureC            6809 non-null   float64       
 3   Min TemperatureC             6810 non-null   float64       
 4   Dew PointC                   6810 non-null   float64       
 5   MeanDew PointC               6810 non-null   float64       
 6   Min DewpointC                6810 non-null   float64       
 7   Max Humidity                 6810 non-null   float64       
 8    Mean Humidity               6810 non-null   float64       
 9    Min Humidity                6810 non-null   float64       
 10   Max Sea Level PressurehPa   6812 non-null   int64         
 11   Mean Sea Level PressurehPa  6812 non-null   int64         
 12   Min Sea Level PressurehPa   6812 non-null   int64         
 13   Max VisibilityKm            5872 non-null   float64       
 14   Mean VisibilityKm           5872 non-null   float64       
 15   Min VisibilitykM            5872 non-null   float64       
 16   Max Wind SpeedKm/h          6812 non-null   int64         
 17   Mean Wind SpeedKm/h         6812 non-null   int64         
 18   Max Gust SpeedKm/h          3506 non-null   float64       
 19  Precipitationmm              6812 non-null   float64       
 20   CloudCover                  5440 non-null   float64       
 21   Events                      1798 non-null   object        
 22  WindDirDegrees               6812 non-null   int64     
 
 **Methodology**
 we used methodology like this:
 - Descriptive analysis of data
 - Data Preprocessing
 - Data Visualization
 - Task 
 1. During the time period in this sample, what % of days had some sort of precipitation event? What % were clear?
 2. Suppose you're planning a vacation to Madrid and hoping for the warmest temperature. Which month might you plan to travel?
 3. On which date in the sample did Madrid see the fastest wind gust? What was the weather like on that day?
 4. How does the average visibility (Km) compare for clear days vs. foggy days?
 
 [Notebook]()
 
 **Conclusion**
- The dataset contains weather information for 6812 rows and 23 columns, with temperature ranging from -10 to 41 degrees Celsius, and maximum wind speed and gust speed of 182 km/h and 103 km/h, respectively.
- In Madrid, precipitation-free days are much more common than days with precipitation, accounting for *96.4% *of all days on average.
- The warmest month in Madrid varies depending on whether you consider mean or maximum temperature. July has the highest mean temperature of 32 degrees Celsius, while August has the highest recorded maximum temperature of 41 degrees Celsius.
- On November 6th, 1997, Madrid experienced a rain event with a maximum gust speed of 103.0 km/hr. The mean temperature was 11 degrees Celsius, maximum wind speed was 58 km/hr, cloud cover was 5.0, and there was no recorded precipitation in terms of millimeters.
- The average visibility in clear days in Madrid is 24.64 km, which is significantly higher than the average visibility in foggy days, which is 8.15 km.
- Madrid experiences relatively few rainy days compared to the total number of days in a year, which can make precipitation events like the one on November 6th, 1997, relatively noteworthy.
