# Bike-Sharing-Demand-Prediction---Capstone-Project

**Seoul-Bike-Sharing-Demand-Prediction**

**Problem Statement**

Currently Rental bikes are introduced in many urban cities for the enhancement of mobility comfort. It is important to make the rental bike available and accessible to the public at the right time as it lessens the waiting time. Eventually, providing the city with a stable supply of rental bikes becomes a major concern. The crucial part is the prediction of bike count required at each hour for the stable supply of rental bikes.

Data Description:
The dataset contains weather information (Temperature, Humidity, Windspeed, Visibility, Dewpoint, Solar radiation, Snowfall, Rainfall), the number of bikes rented per hour and date information.

We will do with following set of work

Workflow

Data Collection and Understanding

Data Wrangling & Feature Engineering

EDA

Preparation of data for model building

Model Selection and Evaluation

Conclusion

![image](https://user-images.githubusercontent.com/94465266/209511938-d5fc6338-dcde-4a1c-82ec-6b8ed2c03250.png)


Attribute Information:
• Date : year-month-day

• Rented Bike count - Count of bikes rented at each hour

• Hour - Hour of the day

• Temperature-Temperature in Celsius

• Humidity - %

• Windspeed - m/s

• Visibility - 10m

• Dew point temperature - Celsius

• Solar radiation - MJ/m2

• Rainfall - mm

• Snowfall - cm

• Seasons - Winter, Spring, Summer, Autumn

• Holiday - Holiday/No holiday

• Functional Day - NoFunc(Non Functional Hours), Fun(Functional hours)



**CONCLUSION:-**

Random forest Regressor and Gradient Boosting gridsearchcv gives the highest R2 score of 99% and 90% respectively for Train Set and 92% for Test set.

Feature Importance value for Random Forest and Gradient Boost are different.

• We can deploy this model.

![image](https://user-images.githubusercontent.com/94465266/209511858-62b5bc73-a882-4710-905b-c2e5ba426f2c.png)

