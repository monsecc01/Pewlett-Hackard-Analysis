# Pewlett-Hackard-Analysis
Analysis of employees at Pewlett Hackard using SQL.

## Resources
Data Source: Employe_Database_Challenge.sql

Software: PostgresSQL 11

## Overview of the analysis: Explain the purpose of this analysis.

The purpose of the Pewlett Hackard analysis is to provide the company a report with the following data:
1.  A table with a number of retiring employees in the company by title
2.  A table with employees eligible for the mentorship program

## Results

4 major points we can derive from the two analysis tables:
1.  The majority of the retirement-eligble employees are senior level employees (64%), meaning that valuable employees to the company could leave in the near future. 

![retiring_titles](https://user-images.githubusercontent.com/81447450/117581941-41910100-b0c5-11eb-8113-f35117d8f728.png)

2.  Since the majority of retirement-eligible employees have senior level positions, those senior level positions should be prioritized when the company looks to back-fill roles.
3.  There are nearly 60 times more employees eligible for retirement (90,398) than there are employees eligible for mentorship (1,549). 
4.  As a result the business may want to investigate mentor/retirement gap as there are many retirement-eligible employees. 

![mentorship_eligible_title_count](https://user-images.githubusercontent.com/81447450/117582267-d21c1100-b0c6-11eb-87ca-2b7a7dc637a9.png)


## Summary

### How many roles will need to be filled as the "silver tsunami" begins to make an impact?
Currently there are potentially 90,398 roles opening up as a result of retirement. However, to better understand the potential retirees we can further group the first table by age group. Assuming the retirement age is 65 and that all retirement eligble employees will retire upon reaching 65, we can group the employees by age year and forecast how many employees will retire each year. This will help with planning for recruitment and hiring. 

### Are there enough qualified, retirement-ready employees in the departments to mentor the next generation of Pewlett Hackard employees?
Based on our anlysis table 1 and 2, there are not enough qualified retirement-ready employees to be mentors. We have significanlty lower mentorship-eligible employees than retirement-ready employees. To help with this gap, we can use the above suggest table showing retiring employees by year. This will forecast how many positions will need to be back-filled by year and therefore how many employees need to mentor younger employees. To match these mentors with younger employees, we can create a querie at the begining of every year to show how many employees (along with last names and first names) are eligble to be mentored to potentially fill those roles. 



