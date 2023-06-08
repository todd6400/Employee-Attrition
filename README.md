# Employee-Attrition
The purpose of this project was to create a regression model and tree model for a mock company to determine how likely an employee will stay with the company and what factors may be relevant 
on why or why not an employee may leave.
In conclusion, monthly income and how long the employees have been working for the company were relevant factors to determine if an employee stays or leaves in the company as they had a negative correlation with Attrition.
After a monthly income of around $3750, employees seems less likely to leave the company.  
After 10 years it seems very likely employees will not leave the company. 
The company should possibly increase the monthly income to $3750 for new employees they want to keep longer than 10 years.
The Decision Tree model was not very strong. It had 59.7% AUC, 29.2% Precision, 14% Recall, 18% F1-Score, 80.6% Accuracy. The Random Forest model was a bit stronger with 66.3% AUC, 62.5% Precsion, 7.8& Recall, 13% F1-Score, 83.6% Accuracy.The Regression model shows an Accuracy of 81%, Precision of 68%, Recall of 81% and F1 Score of 74% (weighted averages).
Source
https://www.kaggle.com/datasets/colearninglounge/employee-attrition?select=employee_attrition_train.csv
Explanation of CSV
AGE Numerical Value

ATTRITION Employee leaving the company (0=no, 1=yes)

BUSINESS TRAVEL (1=No Travel, 2=Travel Frequently, 3=Travel Rarely)

DAILY RATE Numerical Value - Salary Level

DEPARTMENT (1=HR, 2=R&D, 3=Sales)

DISTANCE FROM HOME Numerical Value - THE DISTANCE FROM WORK TO HOME

EDUCATION Numerical Value. (1 'Below College' 2 'College' 3 'Bachelor' 4 'Master' 5 'Doctor')

EDUCATION FIELD (1=HR, 2=LIFE SCIENCES, 3=MARKETING, 4=MEDICAL SCIENCES, 5=OTHERS, 6= TECHNICAL)

EMPLOYEE COUNT Numerical Value

EMPLOYEE NUMBER Numerical Value - EMPLOYEE ID

ENVIRONMENT SATISFACTION Numerical Value - SATISFACTION WITH THE ENVIRONMENT (1 'Low' 2 'Medium' 3 'High' 4 'Very High')

GENDER (1=FEMALE, 2=MALE)

HOURLY RATE Numerical Value - HOURLY SALARY

JOB INVOLVEMENT Numerical Value - JOB INVOLVEMENT (1 'Low' 2 'Medium' 3 'High' 4 'Very High')

JOB LEVEL Numerical Value - LEVEL OF JOB

JOB ROLE (1=HR REP, 2=HR, 3=LAB TECHNICIAN, 4=MANAGER, 5= MANAGING DIRECTOR, 6= RESEARCH DIRECTOR, 7= RESEARCH SCIENTIST, 8=SALES EXECUTIVE, 9= SALES REPRESENTATIVE)

JOB SATISFACTION Numerical Value - SATISFACTION WITH THE JOB (1 'Low' 2 'Medium' 3 'High' 4 'Very High')

MARITAL STATUS (1=DIVORCED, 2=MARRIED, 3=SINGLE)

MONTHLY INCOME Numerical Value - MONTHLY SALARY

MONTHLY RATE Numerical Value - MONTHLY RATE

NUMCOMPANIES WORKED Numerical Value - NO. OF COMPANIES WORKED AT

OVER 18 (1=YES, 2=NO)

OVERTIME (1=NO, 2=YES)

PERCENT SALARY HIKE Numerical Value - PERCENTAGE INCREASE IN SALARY

PERFORMANCE RATING Numerical Value - PERFORMANCE RATING

RELATIONS SATISFACTION Numerical Value - RELATIONS SATISFACTION

STANDARD HOURS Numerical Value - STANDARD HOURS

STOCK OPTIONS LEVEL Numerical Value - STOCK OPTIONS (Higher the number, the more stock option an employee has)

TOTAL WORKING YEARS Numerical Value - TOTAL YEARS WORKED

TRAINING TIMES LAST YEAR Numerical Value - HOURS SPENT TRAINING

WORK LIFE BALANCE Numerical Value - TIME SPENT BETWEEN WORK AND OUTSIDE

YEARS AT COMPANY Numerical Value - TOTAL NUMBER OF YEARS AT THE COMPANY

YEARS IN CURRENT ROLE Numerical Value -YEARS IN CURRENT ROLE

YEARS SINCE LAST PROMOTION Numerical Value - LAST PROMOTION

YEARS WITH CURRENT MANAGER Numerical Value - YEARS SPENT WITH CURRENT MANAGER
