# EXP NO 1: DATA DEFINITION LANGUGE COMMANDS IN RDBMS

## DATE:

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
```
create table Studentsdetails(rollno numeric(12),name varchar(20),age numeric(2),address varchar(100),phoneno numeri
c(10));

```



### OUTPUT:
![Screenshot 2023-10-05 091907](https://github.com/dhivyapriyar/F2_DBMS/assets/119477552/27f7dac7-8f0b-4fb6-bfb0-cce7d8bef170)


### 2) Change the above student table by adding another attribute department

### SQL QUERY: 
```
alter table Studentsdetails add dept char(20);

```
### OUTPUT:
![Screenshot 2023-10-05 092043](https://github.com/dhivyapriyar/F2_DBMS/assets/119477552/8366f99d-c8cf-43d6-91be-3b1cc5b8f9ad)


### 3) Drop the student table


### SQL QUERY: 
 ```
drop table Studentsdetails;

```


### OUTPUT:

![Screenshot 2023-10-05 092728](https://github.com/dhivyapriyar/F2_DBMS/assets/119477552/b6fd287a-f80c-4b7e-9b5e-2624b6c90cd5)
### 4) Delete the student table using truncate keyword

### SQL QUERY: 

```
truncate table Studentsdetails;

```
### OUTPUT:
![Screenshot 2023-10-05 092551](https://github.com/dhivyapriyar/F2_DBMS/assets/119477552/e30e9d60-d6e8-4456-a8c9-39d50b6d6118)



### 5) Rename the student table to mystudent

### SQL QUERY: 

```
alter table Studentsdetails rename to my_student;

```

### OUTPUT:

![Screenshot 2023-10-05 092651](https://github.com/dhivyapriyar/F2_DBMS/assets/119477552/597d87cb-1af4-4bf6-87fc-c7e3a9b4327b)



### RESULT:

Thus the student database is created and DDL queries executed successfully.

