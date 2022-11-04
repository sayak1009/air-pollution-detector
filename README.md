
# Air Pollution forecasting using LSTM Network

## Table of Content 
- [Overview](#overview) 
- [Motivation](#motivation)
- [Dataset](#dataset)
- [Installation of Dependency](#Installation-of-Dependency)
- [Results](#results)
- [Application](#application) 
- [Feedback](#feedback)


## Overview 
Here I forecasts the Air Pollution using RNN(LSTM) network

I have tried to build a model that forecasts the pollution of next hour based on the weathers condition and pollution over the last 24 hours.

## Motivation
- Air polution is a serious issue now a days . Lots of people died and affected for the air polution . If some how we predict the pollution advance , then we can reduce the effect .

##  Dataset 
https://archive.ics.uci.edu/ml/datasets/Beijing+PM2.5+Data#

## Installation Of Dependency
First install 'pip' 

```bash
 $ pip install numpy
 $ pip install pandas
 $ pip install matplotlib
 $ pip install seaborn.
 $ pip install -U scikit-learn ( Windows )
 $ pip install tensorflow
```


## Results

As my model is regression model so I have taken RMSE(Root Mean Square Error) for validation .

RMSE is calculated as :- 

![App Screenshot](https://github.com/bumba5341/Air_Pollution_Forecasting/blob/master/Image/RMSE.png)

 My RMSE value is : 23.33 
 
 As my data range (0-10000) , I think ,it is good .

 ## Graphical Results 
![App Screenshot](https://github.com/bumba5341/Air_Pollution_Forecasting/blob/master/Image/Result.png)

## Application

- If we forecast the pollution prior , we can easily alert the people who has some air pollution diseases like breathing problem , asthma,lung cancer etc for avoiding the places
- The traffic police also restrict the private vehicle and also influence the people to use public transport .

## Feedback

If you have any feedback, please reach out to me at souvikdey707@gmail.com
