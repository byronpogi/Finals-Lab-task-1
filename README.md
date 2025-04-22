# Finals-Lab-task-1
Final Task 1: MySQL Portfolio – Company Database

This portfolio covers the basics of MySQL by creating a company database. It includes writing SQL queries, setting up tables, and showing how the tables are related through schemas or ER diagrams. I’ve also included the SQL code used to build the database structure.

## Task 1: Employees Table employee_id: INT, auto-increment, primary key

employee_name: VARCHAR(255), not null

manager_id: INT, foreign key referencing employee_id in the same table

## Task 2: Departments Table department_id: INT, auto-increment, primary key

department_name: VARCHAR(255), not null

## Task 3: Employee_Departments Table employee_id: INT, foreign key from employees

department_id: INT, foreign key from departments

Composite primary key on both columns

## Task 4: Employee_Projects Table employee_id: INT, foreign key from employees

project_name: VARCHAR(255), not null

## Task 5: Managers Table manager_id: INT, auto-increment, primary key

employee_id: INT, foreign key from employees

#Screenshots

![Image](https://github.com/user-attachments/assets/50639112-6ed1-4f8b-b14b-d1982d7f0f43)
![Image](https://github.com/user-attachments/assets/69fb4caf-91d3-4c27-b42d-db6c34c30ba1)
![Image](https://github.com/user-attachments/assets/3000e6ee-1729-4700-b680-bd29866bfd47)
![Image](https://github.com/user-attachments/assets/c3fb83f5-347a-4cff-8b67-989b8c37850b)
![Image](https://github.com/user-attachments/assets/a120e5c4-5585-4b84-aa12-1954536a9cc1)
![image](https://github.com/user-attachments/assets/f14a4937-a3d6-4d9f-9f03-d167a9b4a885)
![Image](https://github.com/user-attachments/assets/0abda4b9-f4bd-4bf7-9e6b-f59b74b82cc9)
![Image](https://github.com/user-attachments/assets/06cbf78b-dac6-4d9e-973e-f0345ecd5259)
