1. Create Employee_master table with data using Employee
CREATE TABLE EMPLOYEE_MASTER
AS
SELECT * FROM EMPLOYEE;

2. Delete all record into Employee_master whose DeptNo is 10.
DELETE FROM EMPLOYEE_MASTER
WHERE DEPTNO = 10;

3. Update 10% in his salary of DEPTNO 20 into Employee_Master.
UPDATE EMPLOYEE_MASTER
SET SAL = SAL + (SAL * 0.10)
WHERE DEPTNO = 20;

4. Alter SAL with size 10,2 in Employee_Master.
ALTER TABLE EMPLOYEE_MASTER
MODIFY SAL DECIMAL(10,2);

5. Drop Employee_master Table
DROP TABLE EMPLOYEE_MASTER;
