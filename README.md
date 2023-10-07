# Human Resources Analysis and Dashboard

### Project Overview

![HR-career (3)](https://github.com/darianlee555/HR-Analytics-Project/assets/145151765/4c117f80-6f6e-40c4-839b-3d5da962449d)

This is an **SQL** and **Power BI** project analyzing a **Human Resources Dataset** from a fictional company. The point of this project is to answer crucial questions using the HR data and provide deeper insights and recommendations into employee patterns and future hiring decisions at this fictional company. 

### Data Source

**Human Resources Dataset**: https://www.kaggle.com/datasets/rhuebner/human-resources-data-set/data

**Dataset Overview:**

The **Human Resources Dataset** revolves around a fictitious company and the core data set contains info such as names, DOBs, age, gender, marital status, date of hire, reasons for termination, department, whether employees are active or terminated, position title, pay rate, manager name, and performance score.

For further information about the dataset, please refer to the data source link above.

### Objectives

I aim to answer the following questions using the datasets:

1. How many employees are in the company's history (AKA total employees)?
2. How many of those employees are currently still with the company (AKA current employees)?
3. How many of those employees left the company (AKA ex-employees)?
4. What was the average age with regards to total employees? current employees? Ex-employees?
5. What is the attrition rate for this company?
6. What is the average amount of absences for total employees? Current Employees? Ex-employees?
7. What's the average salary for total employees? Current employees? Ex-employees?
8. What was the marital status for the total and current employees?
9. What was the gender for the employees?
10. What department has the most employees?
11. What was the race/ethnicity of the employees?
12. How was the performance of the employees?
13. What is the most common salary range?
14. On average, how long were the Ex-Employees employed?
15. What were the biggest reasons for Ex-Employees leaving the company?

### Tools Used

**PostgreSQL** for Data Exploration, Cleaning, and Analysis

**Power BI** for Visualizations

### Skills/Concepts Demonstrated

The following **SQL** skills were used: Aggregate Functions, Cases, Adding Data, Updating Data, Cleaning/Transforming/Reformatting Data.

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
* There are 311 Total Employees in the company's history.
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
* The biggest reasons why employees leave this company is because they want another position somewhere else or it's because they're unhappy or it's because they want more money.

### Conclusions/Recommendations
Based on the data, I would recommend that this particular company hire more males as the male to female ratio of their employees is slightly skewed towards females so hiring more males will bring about a more even gender ratio. I recommend the company also hire more employees that are minorities since most of their employees are white in order to bring about more racial diversity. The average age of employees in this company seem to be on the older side with age averages of 41, 44, and 37 for total, current, and ex-employees respectively. Perhaps this company should try hiring younger employees to decrease their age averages and improve their age diversity. The attrition rate in this company is 33% which is rather high so in order to lower the attrition rate, I recommend their employees get paid more if they want more since them wanting more money was one of the biggest reasons for them leaving. The average salary of these ex-employees was 66k which is noticably smaller then the 71k salary that current employees make on average and their salary ranges were more lower then current employees as well, further supporting that lack of pay is causing employees to leave. I recommend the company focus more of their training resources on the production department because it has the most current employees out of any department (126) and also the most ex-employees of any department (83) so more support towards the production department should increase the retention rate for employees in that department. And it doesn't seem like a lack of work ethic is a issue among since a majority of employees (for total, current, ex) all fully met performance expectations in their jobs and the average time ex-employees were employed for this company was about 3 and a half years which is quite a while and the average amount of absences for total, current, and ex-employees are about the same. The most common marital status of the current employees is that they're single so perphaps part of the reason why they're still with the company is because they don't have as much family responsiblities affecting them compared to others who are married.  

### More Screenshots showing Interactivity/Filters/Navigation
![](gif1.gif)
![](safa.gif)
![gif3](https://github.com/darianlee555/HR-Analytics-Project/assets/145151765/05bdf730-a135-4562-9d8a-5b4aec0680f2)

