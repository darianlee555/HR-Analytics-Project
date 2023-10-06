# Human Resources Analysis and Dashboard

### Project Overview

![HR-career (3)](https://github.com/darianlee555/HR-Analytics-Project/assets/145151765/4c117f80-6f6e-40c4-839b-3d5da962449d)

This is an **SQL** and **Power BI** project analysing a **Human Resources Dataset** from a fictional company. The point of this project is to answer crucial questions using the HR data and provide deeper insights and recommendations into employee patterns and future hiring decisions at this fictional company. 

### Data Source

https://www.kaggle.com/datasets/rhuebner/human-resources-data-set/data

**Dataset Overview:**

The **Human Resources dataset** revolves around a fictitious company and the core data set contains info such as names, DOBs, age, gender, marital status, date of hire, reasons for termination, department, whether employees are active or terminated, position title, pay rate, manager name, and performance score.
More further info about the dataset can be found in the data source link above.

### Objectives

I wanted to answer the following questions using the data:

* How many employees are in the company's history (AKA total employees)?
* How many of those employees are currently still with the company (AKA current employees)?
* How many of those employees left the company (AKA ex-employees)?
* What was the average age with regards to total employees? current employees? Ex-employees? 
* What is the attrition rate for this company?
* What is the average amount of absences for total employees? Current Employees? Ex-employees?
* What's the average salary for total employees? Current employees? Ex-employees?
* What was the marital status for the total and current employees?
* What was the gender for the employees?
* What department has the most employees?
* What was their race/ethnicity?
* How was the performance of most of the employees?
* What is the most common salary range?
* On average, how long were the Ex-Employees employed?
* What were the biggest reasons for Ex-Employees leaving the company?

### Tools Used

**PostgreSQL** for Data Exploration, Cleaning, and Analysis

**Power BI** for Visualizations

### Skills/Concepts Demonstrated

The following **SQL** skills were used: Joins, Subqueries/CTEs, Windows Functions, Aggregate Functions, Unions, Creating Views, Cases, Adding Data, Updating Data, 
Cleaning/Transforming/Reformatting Data.

If interested, here is the code: https://github.com/darianlee555/HR-Analytics-Project/blob/main/HR%20data%20queries.sql

The following **Power BI** features were incorporated: DAX, Measures, Page Navigation/Buttons, Filters.

### Data Visualization/Dashboard

![Screenshot (31)](https://github.com/darianlee555/HR-Analytics-Project/assets/145151765/abd79e6d-9a61-49d5-a229-a1d4d497a2c5)
![dsk](https://github.com/darianlee555/HR-Analytics-Project/assets/145151765/8ad665df-7c34-4501-a50c-d58922e9d7d7)
![upload this](https://github.com/darianlee555/HR-Analytics-Project/assets/145151765/c563d9cb-a5cd-4783-9234-3fa916678b44)


### Features:
- On the bottom left are navigational buttons that allow the user to navigate easily through the three pages of the dashboard to see data for total employees, current employees, and ex-employees.
- The filters "By Manager", "Gender", "Department", "Recruitment Source", "By Performance", and "Marital Status" allow users to filter the data based on values in those categories.

### Analysis/Results/Insights
Here is the code used to get the following results: 
https://github.com/darianlee555/HR-Analytics-Project/blob/main/HR%20data%20queries.sql
* There are 311 Total Employees in the company's history
* 207 are current employees.
* 104 are ex-employees.
* For total employees, the average age is 41. For current employees, the average age is 44. For ex-employees, the average age is 37. 
* The attrition rate in this company is 33%.
* For total employees, the average amount of absences is 10. For current employees, the average amount of absences is also 10. For ex-employees, the average amount of absences is 11.
* For total employees, the average salary is 69k. For current employees, the average salary is 71k. For ex-employees, the average salary was 66k. 
* For total employees, 137 are single, 124 are married, 30 are divorced, 12 are separated, and 8 are widowed. For current employees, 101 are single, 77 are married, 14 are divorced, 11 are separated, and 4 are widowed.
* For total employees, 135 are male and 176 are female. For current employees, 91 are male and 116 are female. For ex-employees, 44 are male and 60 are female.
* For total employees, the department with the most employees is production with 209 employees. For current employees, the department with the most employees is production with 126 employees. For ex-employees, the department with the most employees is production with 83 employees.
* For total employees, the most common race/ethnicity is White with 187 employees. For current employees, the most common race/ethnicity is White with 124 current employees. For ex-employees, the most common race/ethinicity is White with 63 ex-employees.
* Most of the total employees fully met their work expectations with a count of 243. Most of the current employees fully met their work expectations with a count of 162. And most of the ex-employees fully met their work expectations with an count of 81.
* For total employees, the most common salary range is 60k to 69k with 101 employees. For current employees, the most common salary range is also 60k to 69k with 73 employees. And for ex-employees, the most common salary range is 50k-59k with 35 employees.
* The average time the ex-employees were employed is 1264 days (about 3 and a half years).
* The biggest reasons why employees leave this company is because they want another position somewhere else or it's because they're unhappy.

### Recommendations
Based on the data, in order to prevent future vehicle collisions in NYC, I would encourage more advertisements about the dangers of distracted driving. I would have these ads target the demographic of males that are aged 21 to 40 as they tend to get into the most accidents. I would encourage more ads in Brooklyn specifically, as well as have more traffic directors or officers in Brooklyn since Brooklyn is the most dangerous borough with the most injuries and fatalies. I would also have more officers patrol traffic in all boroughs on Friday afternoons since that's the most likely timeframe that an accident will occur. Also, even though July is the month with the most crashes, it's clear that after April, there is a clear increase in the number of crashes as seen in the line chart graph. Therefore, I would focus more on increasing traffic safety measures from May onwards, as January through April have a somewhat low amount of crashes in comparison to other months. If all/any of these steps are taken, perhaps they will reduce the amount of future collisions NYC has. 

### More Screenshots showing Interactivity/Filters/Navigation
![](gif1.gif)


