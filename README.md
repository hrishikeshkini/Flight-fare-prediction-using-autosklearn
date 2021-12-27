# Flight fare prediction using auto-sklearn
In this project we will be predicting the Fare of a flight a person has to give on inputting the data using the normal Machine Learning techniques then we will see how we can do the same thing with the help of using Auto SK Learn which is a Auto ML Library.

## Table of Content
  * [Problem Statement](#problem-statement)
  * [Approach](#approach)
  * [Technologies Used](#technologies-used)
  * [Installation](#installation)
  * [Bugs & Logs](#bugs--logs)
  * [Contributors](#contributors)

![Screenshot](download.png)


## Problem Statement
We have often heared travellers saying Flight TIckets are often very unpredictable and are very hard to guess. If one might see a price today and checks the same flight price tommorow it's a whole different story by then.
Let us create a Machine Learning Model which will help us in predicting the prices of a flight on inputting some of the attributes. Here we will be provided with prices of flight tickets for various airlines between the months of March and June of 2019 and between various cities.

![Auto Sklearn](https://miro.medium.com/max/1200/1*_wOrre885WuxLetqRXduBw.jpeg)

auto-sklearn frees a machine learning user from algorithm selection and hyperparameter tuning. It leverages recent advantages in Bayesian optimization, meta-learning and ensemble construction.

## Approach
Data Exploration : I started exploring dataset using pandas,numpy,matplotlib and seaborn.

Data visualization : Ploted graphs to get insights about dependend and independed variables.

Feature Engineering : Removed missing values and created new features as per insights.

Model Building & Testing : Tried many machine learning algorithms and checked the base accuracy to find the best fit.

Model Building using Auto SKLearn(Auto ML)

## Technologies Used
 
   1. Python 
   2. Sklearn
   3. RandomizedSearchCV
   4. Random Forest
   5. Auto Sklearn
   6. Pandas, Numpy 

## Dataset
[Download here](https://github.com/hrishikeshkini/Flight-fare-prediction-using-autosklearn/blob/main/flight%20data.csv)

## Installation
Click here to install [python](https://www.python.org/downloads/). To install the required packages and libraries, run this pip command in the project directory after cloning the repository:
```bash
git clone https://github.com/hrishikeshkini/Flight-fare-prediction-using-autosklearn.git
pip install -r requirements.txt
```
If pip is not already installed, Follow this [link](https://pip.pypa.io/en/stable/installation/)

## Bugs & Logs

1. If you find a bug, kindly open an issue and it will be addressed as early as possible. [Open](https://github.com/hrishikeshkini/Flight-fare-prediction-using-autosklearn/issues)
2. Under localhost, logging is performed for all the actions and its stored onto logs.txt file
3. When the app is deployed on heroku, logs can be viewed on  heroku dashboard or CLI.

## Contributors
  [Hrishikesh Kini](https://github.com/hrishikeshkini)
