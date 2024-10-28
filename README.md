# Assignment: Grouping and Summarizing Data with SQL
Instructions: Use the provided sample database tables (patients, providers, visits, ed_visits, admissions, discharges) to answer the following questions. Write SQL queries to perform grouping and summarizing tasks using aggregate functions and the GROUP BY clause.

## Learning Objectives
- Understand how to use aggregate functions (COUNT, SUM, AVG, MIN, MAX) in SQL for analysis
- Learn how to group data using the ```GROUP BY``` clause to summarize information
- Apply the ```HAVING``` clause to filter grouped data based on specific conditions
- Generate financial reports by combining grouping and aggregate functions in SQL queries.

## What you’ll need:
- Access to a computer with internet access
- A code editor (e.g., Visual Studio Code)

## Submission
- Clone the project on your local computer
- Create a file named answers.sql
- Run the queries on MySQL workbench and once they are successfull copy and paste on the answers.sql file on VS code
- Make sure you clearly comment your answers. Example:
```sql
-- question 1.1
SELECT * FROM table_one;

-- question 1.2
SELECT * RFOM table_two;
```
- Once you finish the assignment, push the code to github

<br/><br/>
## Part 1: Basic Aggregate Functions
**1.1).** Write a query to find the total number of patient admissions in the admissions table.<br/>
**1.2).** Write a query to calculate the average length of stay (difference between discharge date and admission date) for all patients.

<br/>

## Part 2: Grouping Data
**2.1).** Write a query to group admissions by primary_diagnosis and calculate the total number of admissions for each diagnosis.<br/>
**2.2).** Write a query to group admissions by service and calculate the average length of stay for each service (e.g., Cardiology, Neurology).<br/>
**2.3).** Write a query to group discharges by discharge_disposition and count the number of discharges in each category (e.g., Home, Expired, Transfer).

<br/>

## Part 3: Combining Aggregates and Filtering
**3.1).** Write a query to group admissions by service and show the services where the total number of admissions is greater than 5.<br/>
**3.2).** Write a query to find the average length of stay for patients admitted with a primary diagnosis of "Stroke" in the admissions table.

<br/>

## Part 4: Advanced Grouping and Summarizing
**4.1).** Write a query to group emergency department visits (ed_visits) by acuity and calculate the total number of visits for each acuity level.<br/>
**4.2).** Write a query to group admissions by primary_diagnosis and service, showing the total number of admissions for each combination.

<br/>

## Part 5: Practical Financial Analysis
**5.1).** Write a query to group admissions by month (using the admission_date) and calculate the total number of admissions per month.<br/>
**5.2** Write a query to find the maximum length of stay for each primary_diagnosis in the admissions table.

<br/>

## Bonus Challenge (optional)
Write a query to group admissions by service and calculate both the total and average length of stay for each service, ordered by the highest average length of stay.

<br/><br/>
# NOTE: Do not fork the repository
