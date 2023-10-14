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

### Program To Create Table:
```
 CREATE TABLE employe(empid NUMBER,emoname VARCHAR(10),dept VARCHAR(10),salary NUMBER);
```
## Program To Create Procedure:
```
SQL>  create or replace procedure inserting_data is
  2  begin
  3  insert into employe values(1,'varsha','it',123000);
  4  insert into employe values(2,'kiki','cs',12330);
  5  insert into employe values(3,'dhivya','aids',12030);
  6  insert into employe values(4,'shama','it',1203);
  7  commit;
  8  end;
  9  /
```
## Program To Call The Procedure:
```
 execute inserting_data;
```
## Program To Display The Table:
```
select * from employe;
```

### Output:

![dbms 4 1](https://github.com/svarsha220/Ex-No-4-Creating-Procedures-using-PL-SQL/assets/127709117/5013222b-71f6-46b0-867a-d565a2a14d70)


### Result:
Hence procedure has been created using PL/SQL.

