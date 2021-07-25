# World_Weather_Analysis

### 
The objective of this project was to collect and analyze weather data across cities worldwide using API requests to OpenWeather. The data was then used to recommend ideal hotels based on clients' weather preferences using Google Places and Directions APIs. A series of maps were created from the data including heat maps of location versus weather condition, and itinerary maps with hotel data depending on the client's input for ideal minimum and maximum temperature when planning a trip. 

WeatherPy.ipynb contains plots such as the one below that show the relation between City Latitude vs Max Temp. 

![Fig1](https://user-images.githubusercontent.com/85901073/126914632-611aa9ed-9df3-4b6e-8e3a-49a5baf92817.png)

It also contains plots that show linear regression such as the one below that plots linear regression on the northern hemisphere for maximum temperatre, where R-values can be analyzed. 

<img width="471" alt="Screen Shot 2021-07-25 at 5 57 14 PM" src="https://user-images.githubusercontent.com/85901073/126914709-56c7db6e-7edc-4712-a631-26dc439f5a2b.png">

After collecting weather data for approximately 1,500 different cities in Weather_Database.ipynb, the data was used to find hotels and a possible vacation itinerary. 

<img width="977" alt="WeatherPy_vacation_map" src="https://user-images.githubusercontent.com/85901073/126914802-87071c15-692b-4703-94d2-7ea634ca887a.png">
<img width="1004" alt="WeatherPy_travel_map_markers" src="https://user-images.githubusercontent.com/85901073/126914807-22b762f1-f534-485b-9d14-c618cbe21911.png">
