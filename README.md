# Pewlett-Hackard-Analysis
PostgreSQL/pgAdmin Analysis of company Human Resource data

> ## Overview of the analysis: 
Analysis purpose is to determine the number of retiring employees per title, and identify employees who are eligible to participate in a mentorship program. 

## Results: 
•	There are 7 unique Retiring Titles which account for 133,776 total employees born between January 1, 1952 and December 31, 1955. 
•	When the data is filtered to provide the 7 unique Retiring Titles the retiring employee count drops from 133,776 to 72,458 for employees born between January 1, 1952 and December 31, 1955. This could skew the data as the top two titles “Engineer” and “Staff” dropped to third and fourth and reflect less retiring employees for Pewlett-Hackard to consider in their analysis.
  
•	The Top 4 Retiring Titles are:
o	25.83% are “Engineer” titles with 34,559 employees 
o	24.26% are “Staff” titles with 32,452 employees. 
o	21.99%are “Senior Engineer” titles with 29,415 employees
o	21.12%are “Senior Staff” titles with 28,256 employees

 
Out of 7 unique Retiring Titles these 4 titles account for 93.20% of the retiring employees and provide Pewlett-Hackard an opportunity to focus staffing in these title categories.
•	1,549 current employees, who were born between January 1, 1965 and December 31, 1965, are eligible to participate in the mentorship program. This will aid Pewlett-Hackard in training the younger employee demographic to learn and retain the skill set of senior employees who will retire in the future.

## Summary: 
### Provide high-level responses to the following questions, then provide two additional queries or tables that may provide more insight into the upcoming "silver tsunami."
o	How many roles will need to be filled as the "silver tsunami" begins to make an impact?
1.	133,776 total roles with need to be filed. An additional query to assess the total number of retiring employees by tile, without the unique title filter:
 
o	Are there enough qualified, retirement-ready employees in the departments to mentor the next generation of Pewlett-Hackard employees?
1.	No, there are 1,549 total employees born between January 1, 1965 and December 31, 1965 who are eligible to participate in the mentorship program. Pwelett-Hackard may consider investing in additional training resources to build the mentoring program into a robust training program to accommodate the 133,776 total roles eligible for retirement.
2.	93,756 potential employees could be eligible for the mentorship program is Pewlett-Hackard expanded the employee birth date range to employees born between January 1, 1960 and December 31, 1965
 ![image]( https://github.com/MStewart0218/Pewlett-Hackard-Analysis/blob/main/Potential_Mentorship_Emp.png?raw=true)


