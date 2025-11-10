# My Sql Learning Task
-- Question 1: Answer
SELECT * 
FROM employees
WHERE department = 'HR';

-- Question 2: Answer
SELECT * 
FROM employees
WHERE salary > 80000;

-- Question 3: Answer
SELECT *
FROM employees
WHERE hire_date > '2019-01-01';

-- Question 4: Answer
DELETE
FROM employees
WHERE department = 'Sales';
