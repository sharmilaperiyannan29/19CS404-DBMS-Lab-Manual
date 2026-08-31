# Experiment 5: Subqueries and Views

## AIM
To study and implement subqueries and views.

## THEORY

### Subqueries
A subquery is a query inside another SQL query and is embedded in:
- WHERE clause
- HAVING clause
- FROM clause

**Types:**
- **Single-row subquery**:
  Sub queries can also return more than one value. Such results should be made use along with the operators in and any.
- **Multiple-row subquery**:
  Here more than one subquery is used. These multiple sub queries are combined by means of ‘and’ & ‘or’ keywords.
- **Correlated subquery**:
  A subquery is evaluated once for the entire parent statement whereas a correlated Sub query is evaluated once per row processed by the parent statement.

**Example:**
```sql
SELECT * FROM employees
WHERE salary > (SELECT AVG(salary) FROM employees);
```
### Views
A view is a virtual table based on the result of an SQL SELECT query.
**Create View:**
```sql
CREATE VIEW view_name AS
SELECT column1, column2 FROM table_name WHERE condition;
```
**Drop View:**
```sql
DROP VIEW view_name;
```

**Question 1**
<img width="1240" height="612" alt="image" src="https://github.com/user-attachments/assets/80976cea-c2d1-412d-a735-c920ddb8d2f0" />



**Output:**

<img width="1095" height="866" alt="image" src="https://github.com/user-attachments/assets/28840c71-a9b6-4c18-8ea6-6bc600ec4bfb" />


**Question 2**
<img width="1111" height="707" alt="image" src="https://github.com/user-attachments/assets/f7200bf5-583c-4c3d-9383-8c6bf16a4511" />

**Output:**
<img width="1282" height="837" alt="image" src="https://github.com/user-attachments/assets/8c35c48c-591a-4b17-82f6-33239673ec84" />



**Question 3**
<img width="1042" height="552" alt="image" src="https://github.com/user-attachments/assets/d9b7d762-aea3-45f6-b99b-5de6490004ef" />



**Output:**

<img width="1267" height="627" alt="image" src="https://github.com/user-attachments/assets/46340deb-76c4-4562-9e8d-10cab437b374" />


**Question 4**
<img width="1272" height="571" alt="image" src="https://github.com/user-attachments/assets/76e83183-1667-4e7c-910f-1a136bbcbed1" />



**Output:**
<img width="1210" height="827" alt="image" src="https://github.com/user-attachments/assets/36f60a58-4bcb-488d-851f-adab01fa9445" />


**Question 5**
<img width="1320" height="522" alt="image" src="https://github.com/user-attachments/assets/56940dd9-b474-49d8-b002-76f8e0281202" />
`

**Output:**

<img width="1207" height="805" alt="image" src="https://github.com/user-attachments/assets/e32ba52d-dad2-4200-be8c-0ac41889316c" />


**Question 6**
<img width="1192" height="417" alt="image" src="https://github.com/user-attachments/assets/928fe2f9-29f7-49e6-a19c-902869397ece" />



**Output:**

<img width="962" height="767" alt="image" src="https://github.com/user-attachments/assets/20002846-bc33-40ca-a664-58f1fd2c56c1" />


**Question 7**
<img width="1037" height="522" alt="image" src="https://github.com/user-attachments/assets/432b3432-9a57-457b-8b73-b2a90b246279" />

**Output:**
<img width="557" height="771" alt="image" src="https://github.com/user-attachments/assets/e26c2d64-fff2-4dab-a6ef-8e222e3c9763" />


**Question 8**
<img width="925" height="452" alt="image" src="https://github.com/user-attachments/assets/553322c3-f5f2-433f-a856-2aaf5c733fe7" />


**Output:**

<img width="862" height="822" alt="image" src="https://github.com/user-attachments/assets/d04c302e-ecb0-4c3c-b68c-a5650295144a" />


**Question 9**
<img width="1057" height="505" alt="image" src="https://github.com/user-attachments/assets/df6640c0-e559-4e16-af37-c424063f9d41" />


**Output:**

<img width="846" height="782" alt="image" src="https://github.com/user-attachments/assets/9876b190-e73c-41d1-b16f-59191034ae8f" />

**Question 10**
<img width="1286" height="712" alt="image" src="https://github.com/user-attachments/assets/5ba21429-f325-448b-b816-9924c3409423" />


**Output:**

<img width="1115" height="800" alt="image" src="https://github.com/user-attachments/assets/fa72c3de-b34b-4edc-97a9-02b60e67ab21" />



## RESULT
Thus, the SQL queries to implement subqueries and views have been executed successfully.
