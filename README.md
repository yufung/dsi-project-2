# Project 2 - Ames Housing Data and Kaggle Challenge

## Problem Statement
This data science project aims to predict the price of houses in Ames, Iowa. We are given 80 variables on the quality and quantity of many physical attributes from individual residential properties in Ames, including their sale price, from property sales between 2006 and 2010.

## Executive Summary

### Contents:
- [1. Exploratory Data Analysis](./code/ames-housing.ipynb#1.-Exploratory-Data-Analysis)
- [2. Data Cleaning](./code/ames-housing.ipynb#2.-Data-Cleaning)
- [3. Exploratory Visualizations](./code/ames-housing.ipynb#3.-Exploratory-Visualizations)
- [4. Pre-processing](./code/ames-housing.ipynb#4.-Pre-processing)
- [5. Modeling](./code/ames-housing.ipynb#5.-Modeling)
- [6. Inferential Visualizations](./code/ames-housing.ipynb#6.-Inferential-Visualizations)
- [7. Business Recommendations](./code/ames-housing.ipynb#7.-Business-Recommendations)


## Business Recommendations

#### Which features appear to add the most value to a home?
- The size of a home, such as above ground living area, first floor and basement area. For instance, a 1 square foot increase in above ground living area will on average increase \$11000 in value to a home. 
- Overall quality rating of the material and finish of a house - a 1 unit increase in the quality rating will increase the value to a home by around \$9000.
- Kitchen quality - having a kitchen with an excellent quality rating will add \$6300 on average to the value of a home.

#### Which features hurt the value of a home the most?
- Being a 1-story planned unit development hurts the value of a home by \$2500 on average when compared to a 1-story house built after 1946.
- A house with average/typical quality of the material on the exterior reduces its value by around \$2300.
- For a house located in North Ames, its value is expected to be lower by \$2300 in comparison to a house located in Bloomington Heights.

#### What are things that homeowners could improve in their homes to increase the value?
- Build a fully-furnished kitchen to increase its quality.
- Regular exterior maintenance to improve the quality of the material and finish of a house.

#### What neighborhoods seem like they might be a good investment?
- Northridge Heights
- Stone Brook
- Northridge

#### Do you feel that this model will generalize to other cities?
- It depends on factors such as whether other cities have similar building types to Ames. I suspect the model will not work as well on cities with a high-density of high-rise apartments as many of the features in our current model are biased towards bungalows.
- Features related to Ames city, such as neighborhood, will also have to be removed.

#### How could you revise your model to make it more universal OR what date would you need from another city to make a comparable model?
- I can group related features to generalize the model even further, such as overall size of home, binary variables for facilities, or distance to points of interests such as schools, supermarkets, etc.