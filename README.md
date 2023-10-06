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
* What was the average age with regards to current employees? Ex-employees? Total employees?
* What is the attrition rate for this company?
* What is the average amount of absences for total employees? Current Employees? Ex-employees?
* What's the average salary for total employees? Current employees? Ex-employees?
* What was the marital status for the employees?
* What was the gender for the employees?
* What department were/are the employees working in?
* What was their race/ethinicity?
* How was their performance at work?
* What was their salary range?
* On average, how long were the Ex-Employees employed?
* What were the top 5 reasons for the Ex-Employees being terminated?

### Tools Used

**PostgreSQL** for Data Exploration, Cleaning, and Analysis

**Power BI** for Visualizations

### Skills/Concepts Demonstrated

The following **SQL** skills were used: Joins, Subqueries/CTEs, Windows Functions, Aggregate Functions, Unions, Creating Views, Cases, Adding Data, Updating Data, 
Cleaning/Transforming/Reformatting Data.

If interested here is the code: https://github.com/darianlee555/Portfolio-Projects/blob/main/SQL%20Motor%20Vehicle%20Crashes%20Code.sql

The following **Power BI** features were incorporated: DAX, Measures, Page Navigation/Buttons, Filters.

### Data Visualization/Dashboard

![Screenshot (27)](https://github.com/darianlee555/HR-Analytics-Project/assets/145151765/67a8c48a-8eeb-47a6-b321-f8cadcf06ac0)


### Features:
- "More Info" and "Previous Info" are navigational buttons that allow the user to navigate easily through the two pages of the dashboard.
- The filters "Borough" and "Year" allow users to filter through the data to see data associated with a certain year and/or borough.
- The "Key Insights" from analyzing the data are put on the left-hand side to make them more obvious to users.
- A zoomable map is included with locations of fatalities for each borough so that the info about those particular collisions can be investigated further. 

### Analysis
Here is the code used to obtain the following results: https://github.com/darianlee555/Portfolio-Projects/blob/main/SQL%20Motor%20Vehicle%20Crashes%20Code.sql
- Driver Inattention/Distracted Driving was the most likely reason for a crash.
- People aged 21 to 40 were most likely to get into car crashes.
- Brooklyn has the most injuries and fatalies of any borough.
- July has the most crashes of any month.
- Males are more likely to get into a crash then females.
- Back injuries were the most common injury in a crash.
- Crashes involving two vehicles (double vehicle crash) were the most common type of crash with 1,502,012 total collisions.
- Friday has the most accidents of any day.
- Most accidents occur in the afternoon.
- The number of total crashes is 2,016,265.
- The number of total injuries is 609,150.
- The number of total fatalities is 2,913.

### Recommendations
Based on the data, in order to prevent future vehicle collisions in NYC, I would encourage more advertisements about the dangers of distracted driving. I would have these ads target the demographic of males that are aged 21 to 40 as they tend to get into the most accidents. I would encourage more ads in Brooklyn specifically, as well as have more traffic directors or officers in Brooklyn since Brooklyn is the most dangerous borough with the most injuries and fatalies. I would also have more officers patrol traffic in all boroughs on Friday afternoons since that's the most likely timeframe that an accident will occur. Also, even though July is the month with the most crashes, it's clear that after April, there is a clear increase in the number of crashes as seen in the line chart graph. Therefore, I would focus more on increasing traffic safety measures from May onwards, as January through April have a somewhat low amount of crashes in comparison to other months. If all/any of these steps are taken, perhaps they will reduce the amount of future collisions NYC has. 

### More Screenshots showing Interactivity/Filters/Navigation
![](Media3.gif)
![](Media4.gif)
![Media5 (4)](https://github.com/darianlee555/Portfolio-Projects/assets/145151765/c724bed6-9265-4e71-9f03-65f8764e4f46)
