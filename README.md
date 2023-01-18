# Module 6 Challenge


## WeatherPy Results


In this deliverable, a Python script was used to visualise the weather of over 500 cities of varying distances from the equator.

The code generated random geographic coordinates and the nearest city to each latitude and longitude combination.

### Requirement 1: Create Plots to Showcase the Relationship Between Weather Variables and Latitude

Latitude vs. Temperature

![Latitude vs. Temperature](/output_data/Fig1.png)

Latitude vs. Humidity

![Latitude vs. Humidity](/output_data/Fig2.png)

Latitude vs. Cloudiness

![Latitude vs. Cloudiness](/output_data/Fig3.png)

Latitude vs. Wind Speed

![Latitude vs. Wind Speed](/output_data/Fig4.png)


### Requirement 2: Compute Linear Regression for Each Relationship

Northern Hemisphere: Temperature (C) vs. Latitude

![Northern Hemisphere: Temperature (C) vs. Latitude](/output_data/NH_Temp_Lat_LR.png)
The r-value is: 0.7302916346197993

Southern Hemisphere: Temperature (C) vs. Latitude

![Southern Hemisphere: Temperature (C) vs. Latitude](/output_data/SH_Temp_Lat_LR.png)
The r-value is: 0.11543384334841626

Northern Hemisphere: Humidity (%) vs. Latitude

![Northern Hemisphere: Humidity (%) vs. Latitude](/output_data/NH_Humidity_Lat_LR.png)
The r-value is: 0.16327497478004085

Southern Hemisphere: Humidity (%) vs. Latitude

![Southern Hemisphere: Humidity (%) vs. Latitude](/output_data/SH_Humidity_Lat_LR.png)
The r-value is: 0.08152682042894913

Northern Hemisphere: Cloudiness (%) vs. Latitude

![Northern Hemisphere: Cloudiness (%) vs. Latitude](/output_data/NH_Cloudiness_Lat_LR.png)
The r-value is: 0.09694943787266845

Southern Hemisphere: Cloudiness (%) vs. Latitude

![Southern Hemisphere: Cloudiness (%) vs. Latitude](/output_data/SH_Cloudiness_Lat_LR.png)
The r-value is: 0.15138512985420405

Northern Hemisphere: Wind Speed (m/s) vs. Latitude

![Northern Hemisphere: Wind Speed (m/s) vs. Latitude](/output_data/NH_WindSpeed_Lat_LR.png)
The r-value is: 0.03879504577913238

Southern Hemisphere: Wind Speed (m/s) vs. Latitude

![Southern Hemisphere: Wind Speed (m/s) vs. Latitude](/output_data/SH_WindSpeed_Lat_LR.png)
The r-value is: 0.1182136466749865


#### Results and analysis

There is a strong correlation between Temperature and Latitude in the Northern Hemisphere. On the other hand, the correlation in the Southern Hemisphere is very weak. For the particular dataset under study, there are more samples in the Northern Hemisphere than in the Southern Hemisphere (371 vs. 190, respectively).

For the sample obtained, the average Latitude in the Northern Hemisphere was 38.91, whereas the average latitude in the Southern Hemisphere was -20.43. This means that a more significant part of the sample in the Southern Hemisphere was in the tropical region. (The tropics are defined in latitude by the Tropic of Cancer in the Northern Hemisphere at 23.43629° N and the Tropic of Capricorn in the Southern Hemisphere at 23.43629° S). This can be visualised in the first VacationPY plot below.

There is none to very weak correlation between the Humidity and Latitude in both the Northern and Southern Hemispheres (Both values are under 0.3)

There is none to very weak correlation between the Cloudiness and Latitude in both the Northern and Southern Hemispheres (Both values are under 0.3)

There is none to very weak correlation for the Wind Speed and Latitude in both the Northern and Southern Hemispheres (Both values are under 0.3)


## VacationPy Results


Map that displays a point for every city based on the coorindates from WeatherPy

![Cities previous dataset](/output_data/Coordinates_Map.png)

To narrow down the ideal weather conditions for a vacation, the following conditions were imposed on the citites and hotels were found were applicable within 10K of the coordinates

Maximum Temperature = 30 degC
Minimum Temperature = 15 deg C
Maximum Wind Speed  = 2 m/s
Maximum Cloudiness = 30 %

Map with hotel locations as per above requirements is below. The requires information for each hotel can be obsevered in the Jupyter Notebook for the submission

![Hotel Locations](/output_data/Location_Hotels_Conditions.png)


## Submission

1. Submitted and available in GitHub under https://github.com/lcardsvr/python-api-challenge

2. Written report is included in the Readme.md file 

3. WeatherPy submission is available under https://github.com/lcardsvr/python-api-challenge/blob/main/WeatherPy.ipynb

4. Vacation submission is available under https://github.com/lcardsvr/python-api-challenge/blob/main/VacationPy.ipynb



