# msca-31009-machine-learning-project

# Wine Recommendation System
This project is a part of the Machine Learning and Predictive Class at the University of Chicago's Master in Science in Analytics Program.  


## Project Intro/Objective
The purpose of this project is to create a recommendation system using data on wine. The goal is to be able to suggest users similar wines based on some of the wines they like. 


### Methods Used
* Machine Learning
* Data Visualization
* Recommendation Systems


### Technologies
* Python
* Excel

## Dataset
The dataset, with more information can be found on kaggle, linked [here](https://www.kaggle.com/datasets/zynicide/wine-reviews) 

The dataset includes information for about 130k different wines and their ratings. The data has been sourced from [Wine Enthusiast](https://www.winemag.com/?s=&drink_type=wine)

There are multiple datasets as part of this project (all can be found in the /Data folder):
The only one being used as part of this project is the <i>winemag-data-130k-v2.csv</i> contains 10 columns and 130k rows of wine reviews. 


## Methodology

For this analysis we used 3 different recommendation systems:
- Content Based Recommendation using NLP on descriptions of the wine
- Non-negative Matrix Factorization using Surprise package in python 
- Hybrid CB+CF Method using LightFM

## Contributing Members

|Name     |  GitHub Handle   | 
|---------|-----------------|
|[Priyank Shroff](https://github.com/[shroffp05])| @shroffp05        |
|[Michelle Tang](https://github.com/[michelle-h-tang])| @michelle-h-tang        |
|[Veda Kilaru](https://github.com/[kilaru1]) |     @kilaru1   |
