# Boom Bike Linear Regression Analysis

####  Team :
- Somesh Saraf

## Table of Contents
* [Problem statement](#general-information)
* [Analysis approach](#general-information)
* [Conclusion](#general-information)
* [Technologies Used](#technologies-used)


## Problem statement
- A bike-sharing system is a service in which bikes are made available for shared use to individuals on a short term basis for a price or free.
  Many bike share systems allow people to borrow a bike from a "dock" which is usually computer-controlled wherein the user enters the payment
  information, and the system unlocks it. This bike can then be returned to another dock belonging to the same system.


A US bike-sharing provider BoomBikes has recently suffered considerable dips in their revenues due to the ongoing Corona pandemic.
The company is finding it very difficult to sustain in the current market scenario.
So, it has decided to come up with a mindful business plan to be able to accelerate its revenue as soon as the ongoing lockdown
comes to an end, and the economy restores to a healthy state. 


In such an attempt, BoomBikes aspires to understand the demand for shared bikes among the people after this ongoing quarantine
situation ends across the nation due to Covid-19. They have planned this to prepare themselves to cater to the people's needs
once the situation gets better all around and stand out from other service providers and make huge profits.


They have contracted a consulting company to understand the factors on which the demand for these shared bikes depends.
Specifically, they want to understand the factors affecting the demand for these shared bikes in the American market. 
The company wants to know:

- Which variables are significant in predicting the demand for shared bikes.
- How well those variables describe the bike demands

Based on various meteorological surveys and people's styles, the service provider firm has gathered a large dataset on
daily bike demands across the American market based on some factors. 

## Analysis approach
- Data Understanding
- Check for Linear Regression and Colinearity
- Data clean up
- EDA
  - Univariate analysis
  - Segmented Univariate/Bivariate analysis.
- Data prepation for model building
  - Create dummy variable for categorical variables
  - Split into train and split
  - Rescaling the feature variables
- Data modelling and Evaluation
  - Recursive Feature Elimination (RFE)
- Residual Analysis of the train data
- Making Predictions Using the Final Model
- Calculate R-squared to check if it matches the model R-squared.


## Conclusion
Considering major contributors:
- Temperature(coef:0.4322) is major contributor to bike rentals. 
  A one unit increase in temperature the rentals increase by 0.4322 units.
  So increase in temperature will cause increase in bike rental.
- Year(coef:0.2352) also has significance where 2019 contributed more towards sale.
- Decrease in rain(coef:-0.2882) will cause increase in sale.
- Decrease in wind speed(-0.1501) will cause increase in sale.

## Technologies Used
- Python (3.8.5)
- numpy (1.19.2)
- Pandas library (1.1.3)
- Mathplotlib library (3.3.2)
- Seaborn library (0.11.0)


