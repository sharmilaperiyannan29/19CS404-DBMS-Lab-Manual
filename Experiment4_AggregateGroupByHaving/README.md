# Experiment 4: Aggregate Functions, Group By and Having Clause

## AIM
To study and implement aggregate functions, GROUP BY, and HAVING clause with suitable examples.

## THEORY

### Aggregate Functions
These perform calculations on a set of values and return a single value.

- **MIN()** – Smallest value  
- **MAX()** – Largest value  
- **COUNT()** – Number of rows  
- **SUM()** – Total of values  
- **AVG()** – Average of values

**Syntax:**
```sql
SELECT AGG_FUNC(column_name) FROM table_name WHERE condition;
```
### GROUP BY
Groups records with the same values in specified columns.
**Syntax:**
```sql
SELECT column_name, AGG_FUNC(column_name)
FROM table_name
GROUP BY column_name;
```
### HAVING
Filters the grouped records based on aggregate conditions.
**Syntax:**
```sql
SELECT column_name, AGG_FUNC(column_name)
FROM table_name
GROUP BY column_name
HAVING condition;
```

**Question 1**
<img width="922" height="507" alt="image" src="https://github.com/user-attachments/assets/a66b0234-992a-4454-adb4-d9af3f2fb905" />


**Output:**

<img width="1032" height="862" alt="image" src="https://github.com/user-attachments/assets/1d88dec3-5abc-45e8-acd3-37a365860bbe" />


**Question 2**
<img width="702" height="552" alt="image" src="https://github.com/user-attachments/assets/3c6d7b57-9900-43c7-ab36-0912e9d4c977" />

**Output:**

<img width="1020" height="836" alt="image" src="https://github.com/user-attachments/assets/2c6e2923-9a93-46f2-8321-961a513190ee" />


**Question 3**
<img width="937" height="586" alt="image" src="https://github.com/user-attachments/assets/48e8c648-13aa-4dc7-a376-f6a9af637840" />


**Output:**

<img width="587" height="847" alt="image" src="https://github.com/user-attachments/assets/f30c225c-1778-43bd-9788-b236ef54e55e" />


**Question 4**
<img width="771" height="432" alt="image" src="https://github.com/user-attachments/assets/738f57a9-9942-41ff-904e-8a6c32e9a963" />


**Output:**

<img width="571" height="787" alt="image" src="https://github.com/user-attachments/assets/46887599-216f-4223-ae1e-e07d1833085d" />


**Question 5**
<img width="1125" height="435" alt="image" src="https://github.com/user-attachments/assets/c63ad58c-435d-4daf-a418-48e8c64bab40" />



**Output:**

<img width="757" height="820" alt="image" src="https://github.com/user-attachments/assets/585caed3-82c3-40fa-afc9-fcc9f2455c9a" />


**Question 6**
<img width="717" height="467" alt="image" src="https://github.com/user-attachments/assets/ad26a16f-22da-4981-aec5-bc96b0f4ef45" />


**Output:**

<img width="710" height="832" alt="image" src="https://github.com/user-attachments/assets/c07ad308-2e06-4fd3-bf59-fddceeda03d6" />


**Question 7**
<img width="780" height="460" alt="image" src="https://github.com/user-attachments/assets/c4b3074f-a284-475a-94ff-6251ee81c05d" />


**Output:**

<img width="507" height="781" alt="image" src="https://github.com/user-attachments/assets/907a9390-312c-46f1-9c79-2e1c23325818" />


**Question 8**
<img width="1217" height="411" alt="image" src="https://github.com/user-attachments/assets/b0d22290-ce5b-4683-8833-ee892be603cc" />




**Output:**
<img width="781" height="822" alt="image" src="https://github.com/user-attachments/assets/ef7faae0-fb27-4160-95e3-6772d14bec6b" />


**Question 9**
<img width="1222" height="455" alt="image" src="https://github.com/user-attachments/assets/6b54eff7-48d2-4df6-8a0b-9b6b64ba3d4f" />


**Output:**

<img width="1017" height="837" alt="image" src="https://github.com/user-attachments/assets/46009897-f5d5-4951-82d5-ec91c73be080" />

**Question 10**

<img width="1225" height="550" alt="image" src="https://github.com/user-attachments/assets/ce52a265-d148-42bf-beb0-4af07667780c" />


**Output:**

<img width="480" height="822" alt="image" src="https://github.com/user-attachments/assets/1be9d914-3c93-42a5-a72c-c779f740859f" />



## RESULT
Thus, the SQL queries to implement aggregate functions, GROUP BY, and HAVING clause have been executed successfully.
