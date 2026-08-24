# Experiment 2: DDL Commands

## AIM
To study and implement DDL commands and different types of constraints.

## THEORY

### 1. CREATE
Used to create a new relation (table).

**Syntax:**
```sql
CREATE TABLE (
  field_1 data_type(size),
  field_2 data_type(size),
  ...
);
```
### 2. ALTER
Used to add, modify, drop, or rename fields in an existing relation.
(a) ADD
```sql
ALTER TABLE std ADD (Address CHAR(10));
```
(b) MODIFY
```sql
ALTER TABLE relation_name MODIFY (field_1 new_data_type(size));
```
(c) DROP
```sql
ALTER TABLE relation_name DROP COLUMN field_name;
```
(d) RENAME
```sql
ALTER TABLE relation_name RENAME COLUMN old_field_name TO new_field_name;
```
### 3. DROP TABLE
Used to permanently delete the structure and data of a table.
```sql
DROP TABLE relation_name;
```
### 4. RENAME
Used to rename an existing database object.
```sql
RENAME TABLE old_relation_name TO new_relation_name;
```
### CONSTRAINTS
Constraints are used to specify rules for the data in a table. If there is any violation between the constraint and the data action, the action is aborted by the constraint. It can be specified when the table is created (using CREATE TABLE) or after it is created (using ALTER TABLE).
### 1. NOT NULL
When a column is defined as NOT NULL, it becomes mandatory to enter a value in that column.
Syntax:
```sql
CREATE TABLE Table_Name (
  column_name data_type(size) NOT NULL
);
```
### 2. UNIQUE
Ensures that values in a column are unique.
Syntax:
```sql
CREATE TABLE Table_Name (
  column_name data_type(size) UNIQUE
);
```
### 3. CHECK
Specifies a condition that each row must satisfy.
Syntax:
```sql
CREATE TABLE Table_Name (
  column_name data_type(size) CHECK (logical_expression)
);
```
### 4. PRIMARY KEY
Used to uniquely identify each record in a table.
Properties:
Must contain unique values.
Cannot be null.
Should contain minimal fields.
Syntax:
```sql
CREATE TABLE Table_Name (
  column_name data_type(size) PRIMARY KEY
);
```
### 5. FOREIGN KEY
Used to reference the primary key of another table.
Syntax:
```sql
CREATE TABLE Table_Name (
  column_name data_type(size),
  FOREIGN KEY (column_name) REFERENCES other_table(column)
);
```
### 6. DEFAULT
Used to insert a default value into a column if no value is specified.

Syntax:
```sql
CREATE TABLE Table_Name (
  col_name1 data_type,
  col_name2 data_type,
  col_name3 data_type DEFAULT 'default_value'
);
```

**Question 1**
--
<img width="1262" height="492" alt="image" src="https://github.com/user-attachments/assets/75bfdd58-7511-492d-b433-507b9f0d3f90" />



**Output:**
<img width="1216" height="770" alt="image" src="https://github.com/user-attachments/assets/f730a2c4-6324-4ce3-95f3-86a9cac96023" />


**Question 2**
---
<img width="1250" height="337" alt="image" src="https://github.com/user-attachments/assets/7509d5b4-62c7-4664-a57c-995e7524b0f2" />


**Output:**
<img width="1252" height="811" alt="image" src="https://github.com/user-attachments/assets/b4f77dcc-783d-4a98-ba3f-4c740a405410" />


**Question 3**
---
<img width="972" height="308" alt="Screenshot 2026-08-21 112821" src="https://github.com/user-attachments/assets/883e3349-1e05-4325-8d09-3b51cff8a649" />


**Output:**

<img width="1260" height="837" alt="image" src="https://github.com/user-attachments/assets/917a728e-7e32-4639-b9bf-c474e93fce76" />


**Question 4**
---
<img width="795" height="322" alt="image" src="https://github.com/user-attachments/assets/cf3ac2e2-fdae-4995-87f8-5d1b3ef5de50" />


**Output:**
<img width="1216" height="762" alt="image" src="https://github.com/user-attachments/assets/931eba76-8276-440f-bf76-094c379a1be8" />


**Question 5**
---
<img width="887" height="462" alt="image" src="https://github.com/user-attachments/assets/d7c6eb3f-88c9-4062-b4cb-5426998a884f" />

**Output:**

<img width="1217" height="811" alt="image" src="https://github.com/user-attachments/assets/e9a01066-ac23-4eb9-9ab2-1d3f7897d471" />


**Question 6**
---
<img width="1247" height="401" alt="image" src="https://github.com/user-attachments/assets/388e5aa9-c9aa-4bbd-9112-008127fb1ce2" />


**Output:**

<img width="1241" height="835" alt="image" src="https://github.com/user-attachments/assets/697e054e-3533-4ea1-8706-10857a2567e8" />


**Question 7**
---
<img width="1256" height="245" alt="image" src="https://github.com/user-attachments/assets/0b82c25f-6c29-449c-8cba-80fcad6012ef" />


**Output:**

<img width="1246" height="790" alt="image" src="https://github.com/user-attachments/assets/f9e2a7bc-f332-4fc1-a499-95d18d9f8942" />


**Question 8**
---
<img width="1072" height="332" alt="image" src="https://github.com/user-attachments/assets/08a2bbb4-352d-46ff-8152-8454d4dcfbf7" />


**Output:**

<img width="1226" height="797" alt="image" src="https://github.com/user-attachments/assets/4abb57d0-79ad-4571-89a6-90cfee18f790" />


**Question 9**
---
<img width="1221" height="247" alt="image" src="https://github.com/user-attachments/assets/9239dfb9-d35f-4bda-9f2a-1ed3fcb36eb4" />


**Output:**

<img width="1196" height="755" alt="image" src="https://github.com/user-attachments/assets/a5b10baf-1490-4e5d-ae86-d3c10e98873f" />


**Question 10**
---
<img width="1186" height="402" alt="image" src="https://github.com/user-attachments/assets/f6fec510-7b52-4184-b16b-41c280ccf4a4" />


**Output:**
<img width="1237" height="802" alt="image" src="https://github.com/user-attachments/assets/c2d8027b-76b1-4f21-b293-1755e5201849" />

<img width="1497" height="91" alt="image" src="https://github.com/user-attachments/assets/b387fd12-e8ab-4fb0-ae91-4840d3971757" />



## RESULT
Thus, the SQL queries to implement different types of constraints and DDL commands have been executed successfully.
