# Bike-sharing-demand-prediction
Seoul-Bike-Sharing-Demand-Prediction
 # Problem Statement
 Currently Rental bikes are introduced in many urban cities for the enhancement of mobility comfort. It is important to make the rental bike 
 available and accessible to the public at the right time as it lessens the waiting time. Eventually, providing the city with a stable supply of rental bikes becomes a major concern. The crucial part is the prediction of bike count required at each hour for the stable supply of rental bikes.
 # Data Description:
The dataset contains weather information (Temperature, Humidity, Windspeed, Visibility, Dewpoint, Solar radiation, Snowfall, Rainfall), the number of bikes rented per hour and date information.
 # Attribute Information:
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

# Exploratory Data Analysis (EDA)
Univariate Analysis
Bivariate Analysis

# Identified Multicollinearity
VIF(Variance Inflation Factor)
Heat MAP.

# Data Outlier Handled.
IQR METHOD.

# Feature Engineering.
ONE HOT ENCOADING.

Pandas Get Dummies Method.

# Model Building
1.Linear Regression:- a. Lasso Regression b. Ridge Regression. c. Elastic net Regression
2.Decision tree
3.Random Forest Regressor
4.XG Boosting.

# Conclusion
The results clearly suggest that XG Boost Regressor is the best model for predicting bike sharing demand, as the performance measure (MAPE, RMSE) is lower and (R2, adjusted_R2) value is greater.
Temperature is regarded as the most important variable for the linear regression model.
We discovered through EDA that people ride bikes more frequently in the summer season and also when the winds are strong.
The months of May, June, and July can be considered to have a larger demand for rented bikes.
There is a considerable demand for the rented bikes during the peak office hours. Therefore base stations can be setup near office buildings.
In order to reduce public waiting times, the number of bikes should be raised during the summer. As a result, they can easily rent bikes whenever they need to or at any time.

# Problems faced during the project:
Transforming the target variable, which was previously nonlinear, into a normal distribution with square root transformation.
Handling the outliers.
We transformed several categorical data into numerical features to feed them into the model and in order to train them more easily.
Initially we got low R2 score and unsatified MAPE% with linear regression model, so we used some advanced tree-based models to improve our accuracy.
