1. Display the total number of employee working in the company.
SELECT COUNT(*) AS TOTAL_EMPLOYEES
FROM EMPLOYEE;

2. Display the total salary being paid to all employees.
SELECT SUM(SAL) AS TOTAL_SALARY
FROM EMPLOYEE;

3. Display the maximum salary from employee table.
SELECT MAX(SAL) AS MAX_SALARY
FROM EMPLOYEE;

4. Display the minimum salary from employee table.
SELECT MIN(SAL) AS MIN_SALARY
FROM EMPLOYEE;

5. Display the average salary from employee table
SELECT AVG(SAL) AS AVERAGE_SALARY
FROM EMPLOYEE;

6. Display the maximum salary being paid to clerk.
SELECT MAX(SAL) AS MAX_CLERK_SALARY
FROM EMPLOYEE
WHERE JOB = 'CLERK';

7. Display the maximum salary being paid in dept no 20.
SELECT MAX(SAL) AS MAX_SALARY_DEPT20
FROM EMPLOYEE
WHERE DEPTNO = 20;

8. Display the minimum salary paid to any salesman.
SELECT MIN(SAL) AS MIN_SALESMAN_SALARY
FROM EMPLOYEE
WHERE JOB = 'SALESMAN';

9. Display the average salary drawn by managers.
SELECT AVG(SAL) AS AVG_MANAGER_SALARY
FROM EMPLOYEE
WHERE JOB = 'MANAGER';


10. Display the total salary drawn by analyst working in dept no 40.
SELECT SUM(SAL) AS TOTAL_ANALYST_SALARY
FROM EMPLOYEE
WHERE JOB = 'ANALYST'
AND DEPTNO = 40;
