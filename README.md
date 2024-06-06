# Seoul-Bike-Sharing-Demand-Prediction

## Introduction
Bike sharing system is an innovative transportation strategy that provides individuals with bikes for their common use on a short-term basis for a price or for free. Over the last few decades, there has been a significant increase in the popularity of bike-sharing systems all over the world. This is because it is an environmentally sustainable, convenient and economical way of improving urban mobility. In addition to this, this system also helps to promote healthier habits among its users and reduce fuel consumption.

## Problem Statement
With the growing demand and user base for bike-sharing system, providing the city with a stable supply of rental bikes could eventually become a challenging task. The success of bike-sharing system relies in ensuring that the quality of facilities provided, meets the needs and expectations of the users. Therefore, it is important to ensure that rental bikes are available and accessible to the users at right time,as it reduces the waiting time. Forecasting the number of bikes required and identifying the key factors that influence the demand for rental bikes can greatly help in managing the bike-sharing system.

## Dataset Information
The dataset used in this project is the Seoul Bike Share program data. This dataset contains information about the total count of rented bikes at each hour, along with other features such as:

* Date: year-month-day
* Rented Bike count: Count of bikes rented at each hour
* Hour: Hour of the day
* Temperature: Temperature in Celsius
* Humidity: %
* Windspeed: m/s
* Visibility: 10m
* Dew point temperature: Celsius
* Solar radiation: MJ/m2
* Rainfall: mm
* Snowfall: cm
* Seasons: Winter, Spring, Summer, Autumn
* Holiday: Holiday/No holiday
* Functional Day: NoFunc(Non Functional Hours), Fun(Functional hours)

## Steps to Solve the Problem Statement
The following steps were taken to solve the problem statement:

1. Understanding the dataset, performing some basic data inspection to verify the number of columns, comprehending data distribution, and examining the statistics for each variable.
2. Feature engineering, new features were added, old features were removed, and the data was encoded into numerical form.
3. Bi-variate analysis is used to determine whether the independent and dependent variables have any linear relationships.
4. The data is finally scaled, and various techniques are tested.
5. To improve accuracy, we first explored some straightforward models like the linear regressor and decision tree before moving on to more complicated algorithms like tree ensemble.

## Algorithms Used
The following algorithms were used to solve the problem statement:

* Linear Regression
* Decision Tree
* Random Forest


## Conclusion
This study demonstrates how numerous factors have an impact on bike rentals. Due to our understanding that many Koreans hire bikes throughout the week, we assumed that most of their use is for commuting to work or school. The number of rentals varies depending on a number of factors, including the day of the week, the hour of the day, and the weather. Because there are more rentals in the spring and summer, weather conditions are particularly crucial. And as we predicted, when the weather is good, more customers plan to rent bikes.
