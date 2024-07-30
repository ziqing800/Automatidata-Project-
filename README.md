# Automatidata-Project-

## Overview 
The goal of this project is to create a multiple linear regresion model to predict high rder gratuity. We utilized yellow taxi trips taken in New York city in the year 2017. The multiple regression model is able to describe 86.8% of variance in fare amount. 

## Business Understanding 
The salary earned by New York Taxi Drivers are significantly lower than the median rent value. It is thus important to understand factors that could encourage more tips for drivers so that they can have a higher income and a better standard of living

## Data Understanding 
The NYC Taxi and Limousine Commission data came from NYC.gov. The data consisted of approximately 408k unique trips and 18 features. The features included information on trip duration and destination, vendor used, toll information, and payment type. The bar chart below shows the breakdown of how many generous tippers (>20%) versus non-generous tippers that exist in the data set. 
![image](https://github.com/user-attachments/assets/74cd9a65-2b9d-4cbb-b8cd-36442b11326f)

## Modeling and Evaluation 
Mean_duration and mean_distance are both highly correlated with the target variable of fare_amount as seen in the heat map below. Hence, the model would incoporate these two variables and predict fare amount as a predictor variable. 
<img width="458" alt="image" src="https://github.com/user-attachments/assets/06059745-3dd6-4f65-a765-51fde0431939">

The model is able to describe 86.8% of variance in the fare amount and the final model indicates that mean distance is the variable that is most crucial in predicting fare amount. For every 3.5 miles of distance travelled, the fare increased by a mean of $7.13

## Conclusion 
This model can help taxi drivers to better understand how they can improve their income through tipping. Adding more information of a rider's tipping behaviour would also help in addressing the problem. 
