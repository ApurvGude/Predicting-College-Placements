# Predicting Placement Salaries of College Graduates

Every year in India around 2.9 million Engineering Students graduate. Out of these, less than 20% percent students recieve jobs in their core and even lesser get enough Salary to sustain their families.

So a model to determine what salary a graduate will get in his placements will be extremely useful to a student and would help him determine in which areas he/she should improve to obtain a good salary.

This prediction model will be made using the Aspiring Minds’ Employability Outcomes (AMEO) dataset. This dataset contains data from around 4500 students who gave AMCAT in 2015.

The dataset was obtained from http://research.aspiringminds.com/resources/#ameo

Aspiring Minds’ Employability Outcomes 2015 (AMEO 2015) is a unique dataset which contains engineering graduates’ employment outcomes (salaries, job titles and job locations) along with standardized assessment scores in three fundamental areas - cognitive skills, technical skills and personality.

Various factors such as college grades, candidate skills, proximity of the college to industrial hubs, the college specialization one has, market conditions for specific industries determine this Employability outcome.

We will also build a Model to predict the Starting Salary of an Engineering Graduate based on the test data given.

The site has their own model evaluation system at http://leaderboard.aspiringminds.com/  ,which we will use to evaluate our model


## Part 1 : EDA and Data Cleaning

![Image 1](https://github.com/ApurvGude/Predicting-College-Placements/blob/master/images/index.png)

In the first part ,we load the dataset and analyze each column to see which factors play a role in determining the salary of the candidate.

We would do this by analyzing the relation between each variable.

## Part 2 : Feature Engineering

This step involves removing some redundant features which we analyzed from the previous step and adding some other features to the final training set which affect the final Salary of the graduation candidate.

## Part 3 : Making the model

![Image 2](https://github.com/ApurvGude/Predicting-College-Placements/blob/master/images/index1.png)

Once the processed data is created we will fit the training data to different varieties of models to see which model provides the most accurate results.

## Part 4: Analyzing the results

Once the models are trained we will find out how accurate the different models predictions are and based on this we will make our final predictions  and test them on the above website's evaluation system.
