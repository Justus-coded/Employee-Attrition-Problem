# Employee-Attrition-Problem
A detailed analysis on Employee Attrition and Predictive Analysis using Machine Learning Algorithms. 

## Description

The data is for company X which is trying to control attrition. There are two sets of data: “Existing employees” and “Employees who have left”. 
Following attributes are available for every employee.

Satisfaction Level, Last evaluation, Number of projects, Average monthly hours, Time spent at the company, Whether they have had a work accident, Whether they have had a promotion in the last 5 years
Departments (column sales),
Salary,
Whether the employee has left.

## ANALYSIS

1. Exploratory Data Analysis and Data Visualization
2. Data Modelling and Data Preprocessing
3. Predictive Analysis

### [Exploratory Data Analysis](https://github.com/Justus-coded/Employee-Attrition-Problem/blob/master/Employee%20Attrition%20Problem/Exploratory%20Data%20Analysis%20and%20Data%20Visualization.ipynb)
  The analysis was done using Python Libraries (MatPlot Library and Seaborn). Data Visualization was also done using Tableau. Check the Dashboard folder for data visualization images gotten using Tableau ([here](https://github.com/Justus-coded/Employee-Attrition-Problem/tree/master/Employee%20Attrition%20Problem/Employee%20Attrition%20DashBoards)).
 
 From the Analysis done we concluded that Low satisfaction level is a key factor in employee attrition. More details are in the [Powerpoint](https://github.com/Justus-coded/Employee-Attrition-Problem/blob/master/Employee%20Attrition%20Problem/Employee%20Attrition%20Analysis.pptx) slides.
 
### Data Modelling and Data Preprocessing
  Here we checked for missing values in the dataset. Also, create  a new column showing weather an employee left or not. We then merge the two Data Frames together. Check jupyter notebook [here](https://github.com/Justus-coded/Employee-Attrition-Problem/blob/master/Employee%20Attrition%20Problem/Data%20Modelling%20and%20Predictive%20Analysis.ipynb) for more details.

  
### Predictive Analysis 

   Using predictive analysis techniques, we predicted based on the data, whether an employee would leave the company or not. Using CatBoost Classifier, we achieved 99.47% accuracy. Check jupyter notebook [here](https://github.com/Justus-coded/Employee-Attrition-Problem/blob/master/Employee%20Attrition%20Problem/Data%20Modelling%20and%20Predictive%20Analysis.ipynb) for more details.


