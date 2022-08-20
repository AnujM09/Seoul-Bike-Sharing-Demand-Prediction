# Seoul-Bike-Sharing-Demand-Prediction

# Problem Description:
Currently Rental bikes are introduced in many urban cities for the enhancement of mobility comfort. It is important to make the rental bike available and accessible to the public at the right time as it lessens the waiting time. Eventually, providing the city with a stable supply of rental bikes becomes a major concern. The crucial part is the prediction of bike count required at each hour for the stable supply of rental bikes.

# Data Description

Date : year-month-day

Rented Bike count - Count of bikes rented at each hour

Hour - Hour of the day

Temperature-Temperature in Celsius

Humidity - %

Windspeed - m/s

Visibility - 10m

Dew point temperature - Celsius

Solar radiation - MJ/m2

Rainfall - mm

Snowfall - cm

Seasons - Winter, Spring, Summer, Autumn

Holiday - Holiday/No holiday

Functional Day - NoFunc(Non Functional Hours), Fun(Functional hours)

# Steps to solve the problem statement:

* Understanding the dataset, performing some basic data inspection to verify the number of columns, comprehending data distribution, and examining the statistics for each variable. Performing a missing value check, To deal with outliers, visualise the distributions and boxplots for each variable. tidying up the info.

* By feature engineering, new features were added, old features were removed, and the data was encoded into numerical form. Tried using certain adjustments to make the dependant variable regularly distributed.

* Bi-variate analysis is used to determine whether the independent and dependent variables have any linear relationships. Using correlation analysis, you can see how severe the multicollinearity.

* The data is finally scaled, and various techniques are tested. To improve accuracy, we first explored some straightforward models like the linear regressor and decision tree before moving on to more complicated algorithms like tree ensemble.

* The linear regressor model did not perform well since there was little linear relationship between the independent and dependent variables. As a result, we switched to tree-based techniques, and performance significantly improved. Utilizing boosting and ensemble techniques as well as fine-tuning the hyperparameters, we continued to enhance the model's performance. The Random Forest Regressor model displayed the best performance.

* To avoid underfitting or overfitting, we observed various evaluation metrics together with the optimal collection of hyperparameters for the tested models. We also had a general understanding of the significance of each feature for each model.

# Summary

This study demonstrates how numerous factors have an impact on bike rentals. Due to our understanding that many Koreans hire bikes throughout the week, we assumed that most of their use is for commuting to work or school. The number of rentals varies depending on a number of factors, including the day of the week, the hour of the day, and the weather. Because there are more rentals in the spring and summer, weather conditions are particularly crucial. And as we predicted, when the weather is good, more customers plan to rent bikes.
