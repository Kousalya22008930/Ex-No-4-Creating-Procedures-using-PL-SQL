# Ex. No: 4 Creating Procedures using PL/SQL

### AIM: To create a procedure using PL/SQL.

### Steps:
1. Create employee table with following attributes (empid NUMBER, empname VARCHAR(10), dept VARCHAR(10),salary NUMBER);
2. Create a procedure named as insert_employee data.
3. Inside the procdure block, write the query for inserting the values into the employee table.
4. End the procedure.
5. Call the insert_employee data procedure to insert the values into the employee table.
6. Display the employee table

### Program:
```sql
create or replace procedure insert_employee_data AS
begin
insert into employee (empid,empname,dept,salary)
values (1,'john','HR',50000);
insert into employee (empid,empname,dept,salary)
values (2,'joe','IT',60000);
insert into employee (empid,empname,dept,salary)
values (3,'bob','Finance',55000);
commit;
end;
/

begin
insert_employee_data;
end;
/
```
### Output:
![image](https://github.com/Kousalya22008930/Ex-No-4-Creating-Procedures-using-PL-SQL/assets/119389108/142f2787-9a22-4e96-8b88-5d2678ec4470)


### Result:
Hence the procedure using pl/sql is created successfully.
