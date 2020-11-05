# Student Performance

## Quick Intro

I have always wonder what factors determine whether a student performs good or not so good in their academic career, which is why I decided to find a dataset that could tackle my curiosity. 

## Problem statement

In this analysis, we use data from students (unknown where they were obtained) and their performance in their writing, reading and maths exams, and try to discover if some factors that are not controlled by the students affect their exams performance. Towards the end of the project, we try to use a regression model to try and predict the scores of students that meet certain conditions.
 
## Approach

Given the following information about the passengers:
- Gender: Male/Female (object)
- Race/ethnicity: Ethnicity group they belong to. Group A to E. (Object)
- Parental Level of Education: Describes parental's level of education. (Object)
- Lunch: If student pays full price for lunch or it's reduced (Object)
- Test Preparation Course: If student completed the test preparation course (Object)
- Reading Score (int64) 
- Writing Score (int64)
- Maths Score (int64)

As we won't have the scores before the students take the exams (obviously), those variables will be used for feature engineering and EDA, but will not be used as input for the regression algorithm. 

We try to predict our target variable (student's score on the exams) with a regression algorithm. We will split our data into train and test, so that we can see if our model performs accordingly with new data. 

The algorithms used to model and fit our data were: Ridge Regression, Lasso Regression, ElasticNet, Decision Tree Regressor, Random Forest Regressor and Gradient Boosting Regressor. To quantify our models I used the metrics of R2, MSE and MAE.  

## Quick Exploratory Data Analysis Summary
![](https://github.com/gonzalobrunoldis/Personal_Projects/tree/main/00.%20Predictive%20Modeling/Regression%20Models/Student%20Performance/Data/2020-11-05_15h42_22.jpg?raw=true)

## Result

The best performing algorithm was Random Forest with an R2 score of 0.5834.

The fact that we did not get a great R2 makes us think that maybe the features did not provide enough information to predict the target variable. Perhaps the variables that are not under the control of the students (such as ethnicity, or parental level of education) do not have as much influence as one would think.

It would be interesting to do an analysis with more variables controlled by the students, such as hours of study, GPA at primary and secondary school, travel time to school, etc.

Thank you for reading!

### Contact Me

| Contact Method |  |
| --- | --- |
| Professional Email | gonzalobrunoldis@gmail.com |
| LinkedIn | https://www.linkedin.com/in/gonzalobrunoldi/ |
