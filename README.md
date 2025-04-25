## Time Series Analysis of Climate Change

**This projected contributed to my thesis**

This research aims to:
1. Quantify climate variable trends across the four regions in India
2. Analyse and compare regional variations in climate change impacts
3. Identify statistically significant changes and potential links to extreme climate events over the years
The results and conclusions of this paper will contribute to understanding how climate change manifests differently across various, differently diverse regions in India and thereby provide information for adaptation strategies and policy decisions to mitigate the potential risks posed by climate change.

**Analysis goal:**
This project aims to analyse the average temperature variable in the 4 different cities - Delhi, Bangalore, Bhubaneswar and Mumbai and make conclusions about the living conditions in these regions with respect to the extreme climate events. 
The analysis employees cleaning processes, exploratory data analysis, data visualizations, regression analysis, and the usage of time series analysis model - ARIMA for forecasting and future predictions of the temperature in each of the cities, thereby providing recommendations based on climate change. 

**Data Acquisiton:**
The dataset used in this research paper is secondary - “Weather data Indian cities (1990 to 2022)” from Kaggle datasets. 
This dataset contains historical weather data for few Indian cities from the years 1990 to 2022. The original dataset contains a few climate variables – temperature (minimum, average and maximum) in °C and precipitation in millimeters (mm) recorded daily. This paper aims to use daily average temperature data from January to December, focusing on historical data from 2010 to 2020 to analyse the region and for predictions and forecasting. 

**Understanding the data:**
The original file mainly contains climate datasets for 8 cities, namely – Delhi, Bangalore, Chennai, Lucknow, Rajasthan, Mumbai, Bhubaneswar, Rourkela from 1990 to 2022 
Each city specific dataset originally has 5 columns – 
date – daily dates 
avg temp – average temperature per day
min temp – minimum temperature per day
max temp – maximum temperature per day
precip – amount of precipitation recorded per day
Of these 8 cities, we have shortlisted 4 cities based on their geographical location – North: Delhi, South: Bangalore, East: Bhubaneswar and West: Mumbai and we focus our analysis on a data range of 10 years, 2010 to 2020 for the Average temperature variable.
To simplify each dataset and further understand the basic feature of each of them, we use Microsoft Excel. 

**Data Cleaning:**
The data has been cleaned by: removing duplicated, removing irrelevant data, converting data types for uniformity in results, normalisation of data and handling missing values.

**EDA:**
We explore the data using visualisations by importing libraries - matplotlib and Seaborn. 
- Line plot: The line plot is used to display change over time as a series of data points connected by a straight line along two axes. It helps to determine the relationship between two sets of values, one being dependent on the other (amended from Salm M, 2022). Here, it helps visualise and understand the trends of average temperature over time.
- Heatmap: Heatmaps refer to a display that uses colour to represent quantitative data. They encode multivariate data – several variables that measure different aspects of some set of entities (Few S, 2006). In this paper, the heatmap combines year, month and average temperature.

**Regression analysis**

- Simple Linear regression: To start from a lower level of analysis, the data is first modelled using simple linear regression
- Time Series regression: Seasonal decomposition, Stationarity, fitting the ARIMA model

**Conclusion (according to the cities):**
Delhi:
Delhi exhibits quite extreme climatic conditions. From the visual representations, we see that there is extreme heat in Summer and predictions reveal higher temperatures in the typically colder months – December and January which usually are 14°C, now go up to 19.2°C. 
Since the RMSE value is a significant portion of the average temperature mean, the ARIMA model is a moderately good fit, hence, the predictions have a good basis may be an underestimation due to the variability.

Bangalore:
The average temperature of Bangalore is distributed quite well over the different seasons, there is seasonality in the region. 
The temperatures are mostly moderate from the analysis of the historical data from 2010 to 2020. The highest temperature recorded over the 10 years was 27.9°C and it has not increased thereafter in the area of study. 
On retraining the model, the forecast values align with the historical values. This reiterates that the low RMSE value of 0.9 suggests a good accuracy for temperature prediction as well as a model of good fit.

Bhubaneswar:
Owing to the sub-tropical climate of the region, we see that the temperatures are moderately high from 2010 through 2020. 
The monthly analysis also depicts very high temperatures in the Summer months – April, May, June. As compared to the other region, summer seems to be longer in the Eastern region. 
The temperature in Winter are mild and does not get too cold which is due to the climatic condition as well as climate change
 However, the higher, snow covered region in the region, might have different conclusions 
From the model predictions, we see the increase in temperature from December through January, going up to 24.6°C. This prediction is subject to gaps as the model is moderately accurate, basing most of its prediction on the general pattern of the historical data.

Mumbai:
Western India has warmer temperature as compared to the rest of the country owing to the Coasts. This can be seen from the visuals. Most of the years from 2014 to 2020 have higher temperatures of up to 29°C. 
Through the years majority of the months also have higher temperatures, reaching over 30°C.
The cooler months have temperatures as low as 23°C which in comparison to the other regions is rather high for Winter months. 
On prediction of future temperature, we see that the model is a moderately good fit with a low RMSE value.
There is a slight decreasing trend in the future predictions, which could imply that if the necessary steps to control climate change are taken, the region can have stable weather according to its climatic condition
Among the cities, Delhi exhibits the highest temperature through historical data, temperatures as high as 36.2°C and Bhubaneswar has longer periods of hot and humid climate. The future predictions for Mumbai seem to be stabilizing, with the right efforts. 

From this, we can conclude that Bangalore is a good city to live in, with moderate high and low temperatures as well as seasonality which helps with predicting and being prepared for the right temperature. Hence, from the analysis of these cities, South is a comparatively good region for living based on temperature changes.
Delhi and Bhubaneswar have extremely high temperatures in Summer and also remain quite warm all year round. This could potentially lead to extreme climate conditions in these regions.
Mumbai has higher temperature than Bangalore which is in the South and is a landlocked city. This could imply that the rise in sea levels and expansion due to the heat in the West contributes to higher temperature in the region.

**Recommendations:**
1. Climate change is a constant concern that requires continuous future analysis with the data points being updated constantly
2. Analysis to identify gaps in the scientific knowledge and prioritise the change in patterns as areas for further research to improve the understanding of climate change is important
3. Cities like Delhi and Bhubaneswar which have extreme high temperatures can switch to renewable energy resources in order to reduce greenhouse gas emission which can contribute to reducing the temperature and hence decrease the likelihood of extreme climate events
4. Policies must be drawn with Government for the increase in urbanization affecting the temperature in all the regions including those where the predicted temperature is more or less stable as of now. This can be a threat in the future and therefore should be addressed before it gets serious
5. Policies for the development of carbon pricing mechanisms like carbon tax to reduce the emissions and use in factories should be drawn up

