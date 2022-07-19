# Linear regression bike sharing assignment 
> This assignment is a programming assignment wherein you have to build a multiple linear regression model for the prediction of demand for shared bikes. You will need to submit a Jupyter notebook for the same. 

## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

## General Information 
- What is the background of your project?
> A bike-sharing system is a service in which bikes are made available for shared use to individuals on a short term basis for a price or free. Many bike share systems allow people to borrow a bike from a "dock" which is usually computer-controlled wherein the user enters the payment information, and the system unlocks it. This bike can then be returned to another dock belonging to the same system. 
- What is the business probem that your project is trying to solve?
> A US bike-sharing provider BoomBikes has recently suffered considerable dips in their revenues due to the ongoing Corona pandemic. The company is finding it very difficult to sustain in the current market scenario. So, it has decided to come up with a mindful business plan to be able to accelerate its revenue as soon as the ongoing lockdown comes to an end, and the economy restores to a healthy state.
The company wants to know:
> 1. Which variables are significant in predicting the demand for shared bikes.
> 2. How well those variables describe the bike demands

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Conclusions
### Final interpretation of results
#### Analysing the above model, the comapany should focus on the following features:
1. Spring is the season the company is fallinf short and should focus on expanding during this    season
2. During September company can expect to have maximum bookings and should be focused in campaigns
3. We can expect to have great uptake in users once situation is normal.
4. Weather conditions will play a huge factor in number of booking, with least in rainy or snowy 
#### The variables to predict the demand of shared bikes
1. Year (2019)
2. Temprature 
3. Humidity
4. Season (Spring,winter) 
5. Day (Sunday)
6. Weather (Clear, Rainy)
7. Months (Jan,Jul,Sep,Dec)
8. Holiday

## Technologies Used
- numpy as np
- pandas as pd
- matplotlib.pyplot as plt
- seaborn as sns
- from sklearn.model_selection import train_test_split
- import statsmodels.api as sm
- sklearn.linear_model import LinearRegression
- statsmodels.stats.outliers_influence import variance_inflation_factor
- sklearn.preprocessing import StandardScaler

## Contact
Created by [@asmarzia07] - feel free to contact me!


<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->
