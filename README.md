# Pewlett-Hackard-Analysis

## Overview
At Pewlett-Hackard, there is a large population of employees that are nearing their retirement. To better prepare for personnel changes, a Retirement Titles table that holds all the titles of current employees who were born between January 1, 1952 and December 31, 1955 was created using SQL. 
Additionally, employees that would be eligible to participate in a mentorship program were identifed.

## Resources
- Data: 
    - **Department list:** *departments.csv*
    - **Employees by Department:** *dept_emp.csv*
    - **Mangers:** *dept_manager.csv*
    - **Employees List:** *employees.csv*
    - **Salaries:** *salaries.csv*
    - **Titles:** *titles.csv*

- Software: PostgreSQL 14, pgAdmin, Python 3.8.8, Visual Studio Code 1.60.2 


## Results
### Employees nearing Retirement: 
<img width="216" alt="Screen Shot 2021-11-14 at 5 54 21 PM" src="https://user-images.githubusercontent.com/91163155/141704235-e0c04101-f512-4844-b6d7-cb20630cc77e.png"> <img width="200" alt="Screen Shot 2021-11-14 at 5 57 36 PM" src="https://user-images.githubusercontent.com/91163155/141704214-c5933b14-152a-462a-8aa1-cdf35aab788d.png">

Preview of retirement_titles.csv in Data folder. 
- List of number of employees nearing retirement by department. 
- Total count of employees nearing retirement at Pewlett-Hackard is 72,458.
- The vast majoirty of retiring employees are in senior positions.

### Employees Eligible to Participate in Mentorship:
<img width="650" alt="Screen Shot 2021-11-14 at 5 55 29 PM" src="https://user-images.githubusercontent.com/91163155/141704204-156de9cc-ea04-4942-824d-75b7e567eff6.png"><img width="210" alt="Screen Shot 2021-11-14 at 5 56 47 PM" src="https://user-images.githubusercontent.com/91163155/141704245-cb9c3798-9c9e-408c-a4ef-a5871cd342f3.png">

Preview of mentorship_eligibility.csv in Data folder. 
- List of employees & their titles that could participate in the mentorship program. 
- Total count of eligible employees at Pewlett-Hackard is 1,549.
- There are not many employees that would quailfy for mentorship positions, perhaps it would be wise to broaden the eligibility scope beyond age. 

## Summary
Pewlett-Hackard currently has 3000,024 total employees, with 72,458 of those employees are quickly reaching retirement ages. Losing nearly a quarter of employees, majoity of which are in senior positions, in the next few years will pose a serious hazard to ther wellbeing of the company if new employees are not hired quickly enough. Additionally, there is a need for these senior employees to participate in mentorship such that new hires will be adaquately prepared to take on senior role in the company. 

Additionally, a table of employees by most recent hire date and mentee_elegibility tables could be used to match mentor and mentee pairs. 

<img width="637" alt="Screen Shot 2021-11-14 at 6 29 47 PM" src="https://user-images.githubusercontent.com/91163155/141705346-1327d575-5f58-4d75-ace0-680e4d2ebfa6.png">
<img width="645" alt="Screen Shot 2021-11-14 at 6 32 59 PM" src="https://user-images.githubusercontent.com/91163155/141705463-74ae55a2-4155-463e-a5c8-b1f4f933a4f5.png">

These two additional tables are somwhat useless, as the youngest employee at Pewlett-Hackard was born in 1965 and the most recent hire was in 2000. 

