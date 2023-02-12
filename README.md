# Bike-sharing-demand-prediction-regression-project

![image](https://user-images.githubusercontent.com/115976515/218310315-07079d2f-67fd-45ca-b5a9-92e02ec9a5d3.png)

## Project Summary -
Bike sharing provides both locals and tourists an easy, low-cost, efficient means of transportation around cities. Users are able to pick up bicycles around the city from multiple bike stations.Bike sharing is striving to become a valid, reliable, and easy form of public transportation. The low cost of bike sharing is also appealing to locals and tourists alike. Data used include Seoul Bike and Capital Bikeshare program data. Data have weather data associated with it for each hour.we have first started with the step knowing your data which includes loading dataset, null/missing value count etc then the next step was to know the variables , after this cleaning the data or data wrangling was done. After this we have done EDA for the project.After we have done hypothesis testing followed by Data preprocessing and then MAchine learning model implementation .For the dataset, we are using linear regression model were train with optimize hyperparameters using a repeated cross validation approach and testing set is used for evaluation. Multiple evaluation indices such as R2 , Root Mean Square error are use to measure the prediction performance of the regression models. The performance of the model is vary with the time interval used in transforming data.

## Problem Statement
Currently Rental bikes are introduced in many urban cities for the enhancement of mobility comfort. It is important to make the rental bike available and accessible to the public at the right time as it lessens the waiting time. Eventually, providing the city with a stable supply of rental bikes becomes a major concern. The crucial part is the prediction of bike count required at each hour for the stable supply of rental bikes.

## Data Description
The dataset contains weather information (Temperature, Humidity, Windspeed, Visibility, Dewpoint, Solar radiation, Snowfall, Rainfall), the number of bikes rented per hour and date information. Attribute Information:

Date : year-month-day

Rented Bike count - Count of bikes rented at each hour

Hour - Hour of he day

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

## Steps for Model Building
1 Reading and Understanding Data

2 Visualising the 

3 Data Preparation

4 Splitting the Data into Training and Testing Sets

5 Feature Scaling on the train data

6 Building the Model

7 Residual Analysis of the train data

8 Making predictions using final model

9 Model Evaluation

## Data Insights 
People prefer rented bikes when temperature is high and humidity is low.
During holidays the demand for rented bikes is less compared to when there are no holidays.
People like to take rented bikes when rainfall and snowfall are low.
The demand is high in the morning and even higher in the evening which shows employees mostly prefer rented bikes before and after their working hours.
The demand is high in the month of June followed by July and May whereas the demand is lowest in the month of December, January and February.

## Conclusion
During the time of our analysis, we initially did EDA on all the features of our datset. We first analysed our dependent variable, 'Rented Bike Count' and also transformed it. Next we analysed categorical variable and dropped the variable who had majority of one class, we also analysed numerical variable, found out the correlation, distribution and their relationship with the dependent variable. We also removed some numerical features who had mostly 0 values , label encoding and hot encoding the categorical variables.

Next we implemented 7 machine learning algorithms Linear Regression,Lasso,Ridge,Elasticnet,Decision Tree, Random Forest and Gradient Boosting. We did hyperparameter tuning to improve our model performance.






