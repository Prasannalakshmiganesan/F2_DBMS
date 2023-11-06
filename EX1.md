# EXP NO 1: DATA DEFINITION LANGUGE COMMANDS IN RDBMS

## Date:

## AIM:
To create a student database and execute DDL queries using SQL.


## DDL (Data Definition Language)
<div align="justify">
DDL or Data Definition Language actually consists of the SQL commands that can be used to define the database schema. It simply deals with descriptions of the database schema and is used to create and modify the structure of database objects in the database. DDL is a set of SQL commands used to create, modify, and delete database structures but not data. These commands are normally not used by a general user, who should be accessing the database via an application.
</div>
 
## List of DDL commands: 
<div align="justify">
CREATE: This command is used to create the database or its objects (like table, index, function, views, store procedure, and triggers).
DROP: This command is used to delete objects from the database.
ALTER: This is used to alter the structure of the database.
TRUNCATE: This is used to remove all records from a table, including all spaces allocated for the records are removed.
RENAME: This is used to rename an object existing in the database.
</div>

## Query:
### 1) Create a table student with the following fieds rollno,name,age,address,phoneno.

### SQL QUERY: 
 create table student(rollno int, name varchar(20), age int, address varchar(100), phoneno varchar(10));

### OUTPUT:
![image](https://github.com/Prasannalakshmiganesan/F2_DBMS/assets/118610231/d4aa3c36-5743-47de-9de2-224d56eb89cd)

### 2) Change the above student table by adding another attribute department

### SQL QUERY: 
alter table student add dept varchar(10);

### OUTPUT:
![image](https://github.com/Prasannalakshmiganesan/F2_DBMS/assets/118610231/ee8bc4e5-fec4-40a5-9e06-0425fa150ecd)


### 3) Drop the student table
 
### SQL QUERY: 
drop table student;

### OUTPUT:
![image](https://github.com/Prasannalakshmiganesan/F2_DBMS/assets/118610231/3ce36d4e-d455-4bf7-b6fd-5153a7cd2465)


### 4) Delete the student table using truncate keyword

### SQL QUERY: 
truncate table student;

### OUTPUT:
![image](https://github.com/Prasannalakshmiganesan/F2_DBMS/assets/118610231/e1ec3d24-63ed-4c60-a715-1bd0ab54a09e)


### 5) Rename the student table to mystudent

### SQL QUERY: 
alter table student rename to mystudent;

### OUTPUT:
![image](https://github.com/Prasannalakshmiganesan/F2_DBMS/assets/118610231/53ea4f2d-ba7e-489b-8c95-96f689efa45a)

## RESULT:
A student database is created and DDL queries using SQL is executed successfully.
