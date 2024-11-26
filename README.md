# Prediction of demand for shared bikes

## Table of Contents
* [General Info](#general-information)
* [Problem solving](#problem-solving)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

## General Information
This assignment is a programming assignment wherein you have to build a multiple linear regression model for the prediction of demand for shared bikes

A US bike-sharing provider BoomBikes has recently suffered considerable dips in their revenues due to the ongoing Corona pandemic. The company is finding it very difficult to sustain in the current market scenario. So, it has decided to come up with a mindful business plan to be able to accelerate its revenue as soon as the ongoing lockdown comes to an end, and the economy restores to a healthy state.

They have contracted a consulting company to understand the factors on which the demand for these shared bikes depends. Specifically, they want to understand the factors affecting the demand for these shared bikes in the American market. The company wants to know:
- Which variables are significant in predicting the demand for shared bikes
- How well those variables describe the bike demands

Dataset to be used for analysis is [here](https://ml-course2-upgrad.s3.amazonaws.com/Linear+Regression+Assignment/Bike+Sharing+Assignment/day.csv) and data dictionary is [here](https://drive.google.com/file/d/1x4Vi_FF0DEmTN1Cf6BnPHUuQP9p0s0Pz/view?usp=sharing)

## Problem Solving
As I have to build multiple linear regression model for the prediction following steps are taken to build & test the model
- Reading, understanding and visualizing the data
- Preparing data for modelling (train-test split, scaling)
- Training the model
- Residual analysis
- Predictions and evaluation on the test set 

## Conclusions
- My Model to predict bike rental count is explained by following linear expression

cnt_pred = 0.5334 - 0.3034 X weathersit_LightRain - 0.2581 X season_spring + 0.0567 X workingday - 0.1031 X mnth_Jan + 0.2480 X yr + 0.0714 X mnth_Sep + 0.0650 X weekday_Mon - 0.0888 X weathersit_Mist - 0.0729 X season_winter - 0.1887 X windspeed - 0.0406 X season_summer
- Following 3 variables are found most significant, based on their magnitude
    - weathersit_LightRain
    - season_spring
    - yr

## Acknowledgements
- I sincerly thank to Upgrad team, IITB Professors and SMEs who guided me timely to complete this assignment

## Contact
Created by [Sudhir Wani](https://github.com/sudhirswani)
