# Project: Predicting-Final-Term-Marks-of-Students
 This project is not only about prediction of marks but also analysis done on a real-world student dataset and exploring characteristics that could potentially impact     students' grades as well as visualizations.
 
➢Introduction:

In this notebook, we will conduct exploratory data analysis using Pandas and Seaborn to find any relationships between student background and student performance in the final term. We will also explore any possible reasonings to our insights and finish up with any key insights that we find.

➢Motivation:

Education is the building block of society. Traditionally, instructors have relied on assessments and periodic tests to judge the students’ progress. This often resulted in late identification of struggling individuals. With the help of tools of Machine Learning we can identify patterns and instructors can make changes to help struggling learners. This project is based on the data gathered from 2 schools of Portugal. The data attributes include student grades, demographic, social and school related features. All these features are essential in understanding the performance of students in academics. Anova test is also used in the project for studying the affect of features on average marks scored by students and to help in feature selection. 

The features that we have worked upon will be benefical for parents/guardians to get an insight into the factors leading to the poor performance of their wards. 

➢Code and Resources used:

◉Python 3.7

◉Packages: Pandas, Numpy, Matplotlib, Seaborn, Sklearn

◉Data: Kaggle



➢EDA:

Affect of Mother's Education(numeric: 0 = none, 1= primary education (4th grade), 2= 5th to 9th grade, 3= secondary education or 4= higher education) 
on performance of student. 


![](https://github.com/SohitPanwar/Project-Predicting-Final-Term-Marks-of-Students/blob/main/Medu.png)


Male=1, Female=0


Affect of Daily alcohol consumption on rate of failure among students



![](https://github.com/SohitPanwar/Project-Predicting-Final-Term-Marks-of-Students/blob/main/Dalc.png)



Studytime ie number of hours spent for studying plays a vital role which is visible in this plot.


![](https://github.com/SohitPanwar/Project-Predicting-Final-Term-Marks-of-Students/blob/main/Studtytime.png)


➢Algorithms:

◉Linear regression

◉Lasso and Ridge regression

◉Random Forest regressor with GridseaarchCV and RandomSearchCV for hyperparamter optimization

◉KNN

◉XGBoostRegressor
