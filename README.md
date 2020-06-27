# Employee-Msy-Leave-or-Not
This is case study of Hacker Earth challenge link: https://www.hackerearth.com/challenges/competitive/hackerearth-machine-learning-challenge-predict-employee-attrition-rate/problems/

Where I've to find Employee will leave or not by predicting **"Attrition_rate"** column. It's Regression challenge with one SQL question and I got 111.301 points out of 150 and my rank is 33th.

Approach = Multi LinearRegression this approch work for numeric values and Employee_ID is string type that's why I've saprate that column and once I got my prediction values I've combine my prediction with Employee_ID because prediction order is not changed.

Feature Engineering Variable = After find the correlation b/w all the variables, I'm not sure about VAR columns so I've used SelectKBest tool and select 8 feature according to ANOVA F_Value.

Model Evalution: For better accuracy I've Lasso Regression.

Tool = Jupyter Notebook
