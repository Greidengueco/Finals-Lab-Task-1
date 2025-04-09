# Finals-Lab-Task-1
- This portfolio focuses on learning MySQL basics through a company database. It covers tasks like writing SQL queries, creating tables, and making an ER diagram. It also includes SQL copies of the database and table structures.

## Step by Step Process
1. **Employees Table**:  
- `employee_id`: Unique integer, auto-increment, primary key.  
- `employee_name`: VARCHAR (255 characters), not null.  
- `manager_id`: Integer, foreign key referencing `employee_id` from the same table.  

2. **Departments Table**:  
- `department_id`: Unique integer, auto-increment, primary key.  
- `department_name`: VARCHAR (255 characters), not null.  

3. **Employee_Departments Table**:  
- `employee_id`: Integer, foreign key referencing `employee_id` in employees.  
- `department_id`: Integer, foreign key referencing `department_id` in departments.  
- Composite primary key on `employee_id` and `department_id`.  

4. **Employee_Projects Table**:  
- `employee_id`: Integer, foreign key referencing `employee_id` in employees.  
- `project_name`: VARCHAR (255 characters), not null.  

5. **Managers Table**:  
- `manager_id`: Unique integer, auto-increment, primary key.  
- `employee_id`: Integer, foreign key referencing `employee_id` in employees.

# Screenshots:
## Query Statements
### 1. Employee Table
- ![Image](https://github.com/user-attachments/assets/b498133d-3217-4e49-a99e-034cd2fd0cc0)
### 2. Department Table
- ![Image](https://github.com/user-attachments/assets/df99dbf8-66cb-40d1-ac64-6dd44b23d96d)
### 3. Employee Departments Table
- ![Image](https://github.com/user-attachments/assets/a38b7700-6b85-4289-99e2-079a2066b877)
### 4. Employee Project Table
- ![Image](https://github.com/user-attachments/assets/f616c818-4c2a-45d8-a29c-858e707fe2ef)
### 5. Managers Table
- ![Image](https://github.com/user-attachments/assets/6d758544-6e6d-43af-9ea1-2a0c032e5fe5)
## Table Structure
### 1. Employee Table
- ![Image](https://github.com/user-attachments/assets/f21a67d7-9648-4df4-a877-7c68b2818fb3)
### 2. Department Table
- ![Image](https://github.com/user-attachments/assets/728ad6b6-c8ea-4402-9d22-b0f9395ab5ec)
### 3. Employee Departments Table
- ![Image](https://github.com/user-attachments/assets/ff338aef-87e6-46e0-a162-8a4fb2fe8036)
### 4. Employee Project Table
- ![Image](https://github.com/user-attachments/assets/ab998455-5991-47ad-ab1d-1abcf043980c)
### 5. Managers Table
- ![Image](https://github.com/user-attachments/assets/d77b6125-ce98-4be6-abbc-7d2856af59ab)
  
# ER Diagram
- ![Image](https://github.com/user-attachments/assets/e1e23f05-fe09-4344-b96f-3e0eb3a3b5d6)
