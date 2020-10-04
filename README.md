# Air Quality Index

An air quality index (AQI) is used by government agencies to communicate to the public how polluted the air currently
is or how polluted it is forecast to become. Public health risks increase as the AQI rises. Different countries have
their own air quality indices, corresponding to different national air quality standards.
Some of these are the Air Quality Health Index (Canada), the Air Pollution Index (Malaysia),
and the Pollutant Standards Index (Singapore).


## A One Health Approach NASA Space Apps Challenge

In this approach a task was to use earth science and health science to study the effect of 
air pollution. 

Our approach was to go with city level data and indian cities database. 

### Dataset

The datasets we used were: https://github.com/Gaurav-30/Boomerz/blob/main/city_day.csv
			   https://github.com/Gaurav-30/Boomerz/blob/main/Indian%20Cities%20Database.csv 


### Data cleaning

Firstly we cleaned the city level data, in  the cleaning we merged the benzene, toluene and xylene
columns into a single column because they had lots of missing data.

We also combined PM2.5 and PM10 columns into a single column to get overall PM values.

There was to be a lot of missing values in the dataset. Additionally, the Date
column is also not in the Date-Time format. So, we added that.

AQI Levels for 2015: 148 US AQI 
           for 2016: 155 US AQI  
	   FOR 2017: 156 US AQI
	   for 2018: 160 US AQI
	   for 2019: 152 US AQI

AQI Level after lockdown (2020): 80 US AQI

<img src = "aqi buc_after.jpeg"> 

Therefore there is a significant improvement in air quality after lockdown.

### Contents of data

Our data consists of these cities:'Ahmedabad', 'Chennai', 'Bengaluru', 'Lucknow', 'Mumbai', 'Delhi',
       				  'Hyderabad', 'Patna', 'Gurugram', 'Visakhapatnam', 'Amritsar',
      				  'Jorapokhar', 'Jaipur', 'Thiruvananthapuram', 'Amaravati',
      				  'Brajrajnagar', 'Talcher', 'Kolkata', 'Guwahati', 'Coimbatore',
         			  'Shillong', 'Chandigarh', 'Bhopal', 'Kochi', 'Ernakulam', 'Aizawl'

The features of the datasets include concentration of different pollutants such as NO2, SO2,
PM2.5, PM10, ozone, etc.

We have plotted the data for year wise and month wise regarding each
pollutant and particulate matter and all the data is in PPM.

We have created separate datasets for different pollutants and particulate
matter and sorted them in ascending order.

Further we have calculated AQI of major cities and have plotted bar graph of
each cities regarding data of changing AQI from 2019 to 2020 for not cluttering
the plot.


This is our Air Quality Index Website.

https://gaurav-30.github.io/Boomerz/

Open this link, for the visualization.

**Note:** We have used github page to publish our result as GitHub notebook doesn't support plotly graphs.

