# Bike Sharing Linear Regression Modelling Assignment 
Project Brief

Bike sharing company BoomBikes would like to use past data of the demand of the bike to create a model that will help to understand the pattern in consumer demand and create a model that will predict the future demands by using the features that affect the demand most


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)

<!-- You can include any other section that is pertinent to your problem -->
## General Information
Business Understanding
A bike-sharing system is a service in which bikes are made available for shared use to individuals on a short term basis for a price or free. Many bike share systems allow people to borrow a bike from a "dock" which is usually computer-controlled wherein the user enters the payment information, and the system unlocks it. This bike can then be returned to another dock belonging to the same system.

A US bike-sharing provider BoomBikes has recently suffered considerable dips in their revenues due to the ongoing Corona pandemic. The company is finding it very difficult to sustain in the current market scenario. So, it has decided to come up with a mindful business plan to be able to accelerate its revenue as soon as the ongoing lockdown comes to an end, and the economy restores to a healthy state. 

In such an attempt, BoomBikes aspires to understand the demand for shared bikes among the people after this ongoing quarantine situation ends across the nation due to Covid-19. They have planned this to prepare themselves to cater to the people's needs once the situation gets better all around and stand out from other service providers and make huge profits.

They have contracted a consulting company to understand the factors on which the demand for these shared bikes depends. Specifically, they want to understand the factors affecting the demand for these shared bikes in the American market. The company wants to know:

Which variables are significant in predicting the demand for shared bikes.
How well those variables describe the bike demands
Based on various meteorological surveys and people's styles, the service provider firm has gathered a large dataset on daily bike demands across the American market based on some factors. 

### Dataset
Data used for the case study contains the information about past demand of the bikes along with more information that may explain that demand.

In this case study, you will use EDA to understand how consumer influence the demand of the bikes and use linear regression to identify the variables that affetct the demand to predict future demands.
### Business Objectives
It is required to understand the factors affecting the demand of the shared bike and create a model that will help in predicting the demand for shared bikes with the available independent variables. 
It will be used by the business to understand how exactly the demands vary with different features. 
Based on finding of the model business strategy can be formulised to meet the demand levels based on the variation on business scenarios.
Further, the model will be a good way for management to understand the demand dynamics of a new market. 

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Conclusions
- Year on Year demand has increased
- Demand is higher when weather situation is (weathersit) is clear
- Demand seems to be increasing till July, no clear ternd for Aug and Sep (When checked for both years) and decreases from oct to dec
- Monday seems to be the day with highest demand, overall not much can be said about the relation of week days with demand
- Demand increases during holiday
- In terms of season, fall has seen highest demand
- cnt=0.0602 + 0.2344 X yr + 0.0555 X workingday + 0.4796 X temp - 0.1500 X windspeed - 0.0554 X season_spring + 0.0626 X season_summer + 0.0958 X season_winter + 0.0873 X mnth_Sep + 0.0667 X weekday_Mon + 0.0804 X weathersit_clear - 0.2089 X weathersit_light
- Demand of bikes can be explained by yr,workingday,temp,windspeed,season_spring,season_summer,season_winter,mnth_Sep,weekday_Mon ,weathersit_clear,weathersit_light

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->


## Technologies Used
- library - Numpy
- library - Pandas
- library - Matplotlib
- library - Seaborn
- library - sklearn

<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->

## Contact
Created by @varjit - feel free to contact me!


<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->
