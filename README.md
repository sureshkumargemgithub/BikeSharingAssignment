# Project Name
> Bike Sharing Assignment


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Assumptions](#assumptions)

<!-- You can include any other section that is pertinent to your problem -->

## General Information
Essentially, the company wants —

Build a model that finds the demand for shared bikes with the available independent variables. It will be used by the management to understand how exactly the demands vary with different features. They can accordingly manipulate the business strategy to meet the demand levels and meet the customer's expectations. Further, the model will be a good way for management to understand the demand dynamics of a new market.

 - To identify the variables affecting bike demand, e.g. area, number of rooms, bathrooms, etc.

 - To create a linear model that quantitatively relates bike demand with variables such as number of rooms, area, number of bathrooms, etc.

 - To know the accuracy of the model, i.e. how well these variables can predict bike demand.

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Technologies Used
- Python library - version 3
- Jupyter Notebook - Anaconda 3
- Git and GitHub for creating the repo to share it publicly

<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->

## Conclusions
- Majority of the categorical variables only became driving variables for the model and bike demand. Here is the list of variables which participated in the final model. 

['workingday','windspeed', 'summer', 'winter', 'fall', 'yr', 'sat', 'may', 'oct', 'mist_cloudy', 'mar',  'sep',  'light_rain']  

Here except windspeed all other columns are categorical varaiables only. We can infer that based on season and weather conditions are majorly effecting bike demand. 
- if we consider positive correlation, windspeed has got good correlation. But not to an extent like humidity.  But humidity is negatively highly correlated. 
- confirmed the assumption of normal distribution of the model by distplot of the error terms
- There is very high negative coefficient (-2771.65) with light rain and its obvious to guess there would not any person who will be interested in bike when it is raining. The next one is positive coefficient with the fall season (2673.16) which is very much convinient for bike riders. So, there is big demand in this season. The next one is positive coefficient with the year (2161.79), which indicates that the second year of the collected information has made more business in terms of bike demand. The next one is summer season (2058.92) has got better business compared other remaining seasons and than other driving variables.

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Assumptions
- In linear regression, we have few assumpions. I have confirmed the assumption of normal distribution of the model by distplot of the error terms
- There should be a linear and additive relationship between dependent (response) variable and independent (predictor) variable(s). A linear relationship suggests that a change in response Y due to one unit change in X is constant, regardless of the value of X. An additive relationship suggests that the effect of X on Y is independent of other variables. 

- There should be no correlation between the residual (error) terms. Absence of this phenomenon is known as Autocorrelation. 

- The independent variables should not be correlated. Absence of this phenomenon is known as multicollinearity. This can be verified with VIF 

- The error terms must have constant variance. This phenomenon is known as homoscedasticity. The presence of non-constant variance is referred to heteroscedasticity. 

- The error terms must be normally distributed. This can be verified with the graph 
- This project was based on [this tutorial](https://www.upgrad.com).


## Contact
Created by [@sureshkumargemgithub] - feel free to contact me!


<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->
