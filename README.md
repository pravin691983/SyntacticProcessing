# Bike Sharing

> To build a multiple linear regression model for the prediction of demand for shared bikes.

<p>
<img src ="https://play-lh.googleusercontent.com/56LEcA4KXoBhdqSn3jHzcSubIjgqF1_mHikBExgrGRcRML2oFHZLifYfBz4kiGsHDh8" alt='Figure 1'>
<center> <b>Figure 1. BookBikes</b> </center> 
 </br>  
</p>

## Table of Contents

- [Overview Business Understanding](#overview-business-understanding)
- [Problem Statement Business Objectives](#problem-statement-business-objectives)
- [Data in depth](#data-in-depth)
- [Approach](#approach)
- [Technologies Used](#technologies-used)
- [Conclusions](#conclusions)

<!-- You can include any other section that is pertinent to your problem -->

## Overview Business Understanding

You are required to model the demand for shared bikes with the available independent variables. It will be used by the management to understand how exactly the demands vary with different features. They can accordingly manipulate the business strategy to meet the demand levels and meet the customer's expectations. Further, the model will be a good way for management to understand the demand dynamics of a new market.

## Problem Statement Business Objectives

A bike-sharing system is a service in which bikes are made available for shared use to individuals on a short term basis for a price or free. Many bike share systems allow people to borrow a bike from a "dock" which is usually computer-controlled wherein the user enters the payment information, and the system unlocks it. This bike can then be returned to another dock belonging to the same system.

A US bike-sharing provider BoomBikes has recently suffered considerable dips in their revenues due to the ongoing Corona pandemic. The company is finding it very difficult to sustain in the current market scenario. So, it has decided to come up with a mindful business plan to be able to accelerate its revenue as soon as the ongoing lockdown comes to an end, and the economy restores to a healthy state.

In such an attempt, BoomBikes aspires to understand the demand for shared bikes among the people after this ongoing quarantine situation ends across the nation due to Covid-19. They have planned this to prepare themselves to cater to the people's needs once the situation gets better all around and stand out from other service providers and make huge profits.

They have contracted a consulting company to understand the factors on which the demand for these shared bikes depends. Specifically, they want to understand the factors affecting the demand for these shared bikes in the American market. The company wants to know:

- Which variables are significant in predicting the demand for shared bikes.
- How well those variables describe the bike demands
  Based on various meteorological surveys and people's styles, the service provider firm has gathered a large dataset on daily bike demands across the American market based on some factors.

### Want to

- Understand the driving factors (or driver variables) behind BIKE SHARING, i.e. the variables which are strong indicators of atmost profit.
- To build a multiple linear regression model for the prediction of demand for shared bikes.

## Data in depth

- We are going to analyze datasets,
- The datasets contains details information related of the bike sharing such as year, month, temp, wind speed etc.
- The dataset comprises of 730 observations of 16 columns. Below is a table showing names of the few columns.

## Approach

#### Understanding the Dataset

- To gain insights from data we must look into each aspect of it very carefully. We will start with observing few rows and columns of data both from the starting and from the end.

#### Preprocessing

- We will deal with erroneous, missing and outliers values of columns.
- Correlation between different columns
- See how preprocessing have transformed our dataset.
- Derive new data from existing data to get more insite

#### Exploratory Data Analysis on Loan Dataset

- Try to find out answers of some set of questions

#### Build Model after Dataset split

- Build model & validate results after split dataset in train & test repsectiviey using multiple linear regression model

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Conclusions

Based on our analysis and as per our final Model, the top 3 predictor variables that influences the bike booking are:

- Temperature (temp) - A coefficient value of ‘0.5309’ indicated that a unit increase in temp variable increases the bike hire numbers by 0.5309 units.
- Weather Situation 3 (weathersit_3) - A coefficient value of ‘-0.2993’ indicated that, w.r.t Weathersit1, a unit increase in Weathersit3 variable decreases the bike hire numbers by 0.2993 units.
- Year (yr) - A coefficient value of ‘0.2294’ indicated that a unit increase in yr variable increases the bike hire numbers by 0.2294 units.

Also the next best features that can also be considered are:

- season_4: - A coefficient value of ‘0.1412’ indicated that w.r.t season_1, a unit increase in season_4 variable increases the bike hire numbers by 0.1412 units.
- windspeed: - A coefficient value of ‘-0.1169’ indicated that, a unit increase in windspeed variable decreases the bike hire numbers by 0.1169 units.

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Technologies Used

- Python
- Numpy
- Panda
- Matplotlib
- Seaborn
- Jupyter Notebook

<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->

## Contact

Created by [@pravin691983] - feel free to contact me!

<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->
