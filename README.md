# Analysing-HR-Analytics-in-Power-BI  
Analysing Human Resources data for a fictitious company called Atlas Labs.

## Table of Contents

[Project Overview](#Project-Overview)  
[Data Sources](#Data-Sources)  
[Data Transformation](#Data-Transformation)  
[Findings](#Findings)  
[Recommendations](#Recommendations)  

### Project Overview

This project focuses on carrying out exploratory data analysis of HR data of Atlas Labs. This analysis will help organization to determine actions to be taken for retaining more employees.

### Data Sources

There are 4 dimension tables [Dim_SatisfiedLevel.csv](https://github.com/riteshgogade/Analysing-HR-Analytics-in-Power-BI/blob/main/Dim_EducationLevel.csv), [Dim_PerformanceRating.csv](https://github.com/riteshgogade/Analysing-HR-Analytics-in-Power-BI/blob/main/Dim_PerformanceRating.csv), [Dim_RatingLevel.csv](https://github.com/riteshgogade/Analysing-HR-Analytics-in-Power-BI/blob/main/Dim_RatingLevel.csv), [Dim_SatisfiedLevel.csv](https://github.com/riteshgogade/Analysing-HR-Analytics-in-Power-BI/blob/main/Dim_SatisfiedLevel.csv) and a fact table [Fact_Employee.csv](https://github.com/riteshgogade/Analysing-HR-Analytics-in-Power-BI/blob/main/Fact_Employee.csv). A extra date-time table was created using DAX function.

### Data Transformation

1. All columns in the tables were correctly formatted as text, numbers and dates were expected.
2. Connected all the 6 tables in snowflake schema with 6 active relationships and 4 inactive relationships.
3. Created a table for measures for calculating employee count, review dates and different satisfaction levels of employees.
4. Calculated measures of total employees, active and inactive employees and attrition rate.
5. Created measure for calculating employees hiring trend as per date for analysing employees who are still active.
6. Analysed department wise active employees.
7. Categorised employees in age groups. Analyse employee count wrt age, gender and marital status. Analysed average salary of employees with ethnicity.
8. Analysed employee satisfaction and rating levels wrt year.
9. Analysed attrition rate for each department and job role, business travel, overtime and tenure.

### Findings

1. Largest share of employees belong to age group 20-29.
2. White ethnic group is the highest paid.
3. Employee feeling less satisfied end up in getting low perfromance rating.
4. Sales Representative and HR recruiter have highest attrition of 39 % and 37 % respectively.
5. Employees with frequent travelling and overtime tend to leave the company.
6. Employees in first 2 years tenure tend to have higher attrition.

### Recommendations

