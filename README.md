# Human Resources Analysis and Dashboard

### Project Overview

![HR-career (3)](https://github.com/darianlee555/HR-Analytics-Project/assets/145151765/4c117f80-6f6e-40c4-839b-3d5da962449d)

This is an **SQL** and **Power BI** project analyzing a **Human Resources Dataset** from a fictional company. The point of this project is to answer crucial questions using the Human Resources data and provide deeper insights and recommendations into employee patterns and future hiring decisions at this fictional company. 

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
Here is the code used to get the following results/insights: 
https://github.com/darianlee555/HR-Analytics-Project/blob/main/HR%20data%20queries.sql

* **Total Employees**: The company's historical record includes a total of 311 employees.
* **Current Employees**: Presently, there are 207 employees actively working within the company.
* **Ex-Employees**: 104 individuals have previously worked for the company but are no longer employed.
* **Average Age**: For total employees, the average age is 41. Among current employees, the average age rises to 44, while ex-employees' average age is 37.
* **Attrition Rate**: The attrition rate within the company stands at 33%.
* **Absence Averages**: On average, both total and current employees have 10 absences, whereas ex-employees had an average of 11 absences.
* **Salary Averages**: The average salary for total employees is 69k. Among current employees, the average salary is slightly higher at 71k, while ex-employees had an average salary of 66k.
* **Marital Status**: Among total employees, marital status breakdown is as follows: 137 single, 124 married, 30 divorced, 12 separated, and 8 widowed. Current employees include 101 singles, 77 married, 14 divorced, 11 separated, and 4 widowed.
* **Gender Distribution**: Among total employees, there are 135 males and 176 females. Among current employees, 91 are male and 116 are female, while among ex-employees, there are 44 males and 60 females.
* **Department Breakdown**: The department with the highest employee count among total employees is production, with 209 employees. Among current employees, the production department also leads with 126 employees, and among ex-employees, the production department leads with 83 former members as well.
* **Race/Ethnicity**: For total employees, the most prevalent race/ethnicity is White, accounting for 187 employees. Among current employees, White is also the most common with 124 individuals, and among ex-employees, White is also the most common with 63 former employees.
* **Performance**: The majority of employees across categories (total, current, and ex-employees) fully met their work expectations, with counts of 243, 162, and 81, respectively.
* **Salary Ranges**: The most common salary range for total employees is $60,000 to $69,000, comprising 101 employees. Current employees mirror this trend, with 73 employees in the same salary range. Among ex-employees, the most common salary range is $50,000 to $59,000, with 35 individuals.
* **Average Tenure of Ex-Employees**: Ex-employees, on average, had an employment duration of 1,264 days, which is roughly equivalent to 3 and a half years.
* **Reasons for Departure**: The primary reasons cited for employee departures include a desire for another position elsewhere, unhappiness, and seeking higher compensation.

### Conclusions/Recommendations
Based on the data, I recommend that the company actively consider hiring more male employees since the current workforce appears slightly skewed towards females. The organization could also benefit from a more diverse workforce in terms of ethnicity. Since a significant portion of employees are of White ethnicity, proactive efforts to recruit individuals from minority backgrounds can help foster racial diversity. The average age of employees seems to be on the older side with age averages of 41, 44, and 37 for total, current, and ex-employees respectively. Thus, in order to promote age diversity and introduce fresh perspectives, the company may find value in hiring younger employees alongside experienced ones. The attrition rate in this company is 33% which is rather high so in order to lower the attrition rate, I  recommend that the company consider more competitive compensation packages, especially given that a desire for higher pay was one of the primary reasons for employee departures. I recommend that the company concentrate training and resources on the production department because it has the largest number of both current (126) and former employees (83), so targeted support can significantly enhance retention rates in this department. If any or all of these suggestions are implemented, the company may become more diverse and successful in the future, with lower attrition rates and a more balanced and dynamic workforce.

### More Screenshots showing Interactivity/Filters/Navigation
![](gif1.gif)
![](safa.gif)
![gif3](https://github.com/darianlee555/HR-Analytics-Project/assets/145151765/05bdf730-a135-4562-9d8a-5b4aec0680f2)

