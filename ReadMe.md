# Decision Analystic class mini project 2
## Objective Question:
### Finding relationships betwen Baltimore City employee salary and department and time being hired.
## Data Question:
### Linear Regression of employee salary vs department and time being hired
## Findings:
### To some extent, the annul salary is droping as hiring time becomes longer.This means if an employee has been working in the government for longer they will get paid lessand less,which could potentials result in a loss inhuman resoueces.
### Annual Salary did not show significat linear relationship with employe's department.
### The two regressions are not statistically significant.Like the r^2 for simple and multiple regressions are 0.089 and 0.12 respectively.
The p values for coefficients are small and f value is also small, which shows that the regression coefficients are well estimated but the linear relationship between salary and days hired and  department are poor.
## Steps:
- Download the data
- Get A days_hired metric by using Date_hired-A_certain_Date and convert it into days.
- Get department id using "Middle" function
- Run Simple Regression :Salary vs.days_hired
- Run Multiple Regression: Salary vs. days_hired and department_id
## Possible Improvements:
- department id is not a good metric for linear regression because it's in random order.One ways is re-idex depart_id by mean_salary. The other is using soft regression.
