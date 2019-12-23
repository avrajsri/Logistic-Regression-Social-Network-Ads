# Logistic-Regression-Social-Network-Ads

Using Logistic Regression model to predict if a person is going to buy a new car or not based on the available data

## Problem

Suppose a company is going to launch a new campaign for their new brand of car and want to know which category of people are likely to buy their brand new car so they can have the ads that target those peoples. For this they contacted a social network advertising company which have the data from another similar successful campaign. Now, they want to make a model which helps achieve their goal.

## Dataset

The dataset contains 400 entries which contains the userId, gender, age, estimatedsalary and the purchased history. The matric of features taken into account are age and estimated salary which are going to predict if the user is going to buy new car or not(1=Yes, 0=No).

## Solution

First the pre-processing of data is done and then the prediction was done using logistic regression followed with visualization.

The confusion matrix below shows that our model predicts 89 correct and 11 wrong decisions which shows 89% accuracy.

![Confusion Matrix](https://user-images.githubusercontent.com/14214659/71309703-c8333880-2413-11ea-9e3a-b8baa47da327.png)

The data visualization of the training set and test set is given below. As logistic regression is linear model the data is being separated linearly. The green dots shows the people buying the car whereas red dots shows the people who don't buy the car.

![Logistic Regression (Training Set)](https://user-images.githubusercontent.com/14214659/71309694-a934a680-2413-11ea-81bf-a7d93fed2992.png)

![Logistic Regression (Test set)](https://user-images.githubusercontent.com/14214659/71309696-b81b5900-2413-11ea-85c4-14ce3dfacc64.png)
