SQL Aggregates, Subselect and Join Practice

# Sample Database

<https://raw.githubusercontent.com/bwood-crc/420-N32-HR-DB/refs/heads/main/hr_database_mysql.sql>

# Aggregate Functions and Group (14 Questions)

1. List the number of jobs available in the employees table.
2. Get the total salaries payable to employees.
3. Get the minimum salary from employees table.
4. Get the maximum salary of an employee working as a Programmer.
5. Get the average salary and number of employees working the department 90.
6. Get the highest, lowest, sum, and average salary of all employees.
7. Get the number of employees with the same job.
8. Get the difference between the highest and lowest salaries.
9. Find the manager ID and the salary of the lowest-paid employee for that manager.
10. Get the department ID and the total salary payable in each department.
11. Get the average salary for each job ID excluding programmer.
12. Get the total salary, maximum, minimum, average salary of employees (job ID wise), for department ID 90 only.
13. Get the job ID and maximum salary of the employees where maximum salary is greater than or equal to $4000.
14. Get the average salary for all departments employing more than 10 employees.

# Subqueries (21 Questions)

1. Find the name (first_name, last_name) and the salary of the employees who have a higher salary than the employee whose last_name='Bull'.
2. Find the name (first_name, last_name) of all employees who works in the IT department.
3. Find the name (first_name, last_name) of the employees who have a manager and worked in a USA based department.
4. Find the name (first_name, last_name) of the employees who are managers.
5. Find the name (first_name, last_name), and salary of the employees whose salary is greater than the average salary.
6. Find the name (first_name, last_name), and salary of the employees whose salary is equal to the minimum salary for their job grade.
7. Find the name (first_name, last_name), and salary of the employees who earns more than the average salary and works in any of the IT departments.
8. Find the name (first_name, last_name), and salary of the employees who earns more than the earning of Mr. Bell.
9. Find the name (first_name, last_name), and salary of the employees who earn the same salary as the minimum salary for all departments.
10. Find the name (first_name, last_name), and salary of the employees whose salary is greater than the average salary of each department.
11. Find the name (first_name, last_name) and salary of the employees who earn a salary that is higher than the salary of all the Shipping Clerk (JOB_ID = 'SH_CLERK'). Sort the results of the salary of the lowest to highest.
12. Find the name (first_name, last_name) of the employees who are not supervisors.
13. Display the employee ID, first name, last name, and department names of all employees.
14. Display the employee ID, first name, last name, salary of all employees whose salary is above average for their departments.
15. Fetch even numbered records from employees table.
16. Find the 5th maximum salary in the employees table.
17. Find the 4th minimum salary in the employees table.
18. Select last 10 records from a table.
19. List the department ID and name of all the departments where no employee is working.
20. Get 3 maximum salaries.
21. Get 3 minimum salaries.

# Joins (13 Questions)

1. Find the addresses (location_id, street_address, city, state_province, country_name) of all the departments. Hint : Use NATURAL JOIN.
2. Find the name (first_name, last name), department ID and name of all the employees.
3. Find the name (first_name, last_name), job, department ID and name of the employees who works in London.
4. Find the employee id, name (last_name) along with their manager_id and name (last_name).
5. Find the name (first_name, last_name) and hire date of the employees who was hired after 'Jones'.
6. Get the department name and number of employees in the department.
7. Find the employee ID, job title, number of days between ending date and starting date for all jobs in department 90.
8. Display the department ID and name and first name of manager.
9. Display the department name, manager name, and city.
10. Display the job title and average salary of employees.
11. Display job title, employee name, and the difference between salary of the employee and minimum salary for the job.
12. Display the job history that were done by any employee who is currently drawing more than 10000 of salary.
13. Display department name, name (first_name, last_name), hire date, salary of the manager for all managers whose experience is more than 15 years.
