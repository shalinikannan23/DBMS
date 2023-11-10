# EXP NO 2: DATA DEFINITION LANGUGE COMMANDS 
### DATE : 16/08/2023
## AIM:
To create a student database and execute DDL queries using SQL.


## THEORY
### DDL (Data Definition Language)

* DDL or Data Definition Language actually consists of the SQL commands that can be used to define the database schema.
* It simply deals with descriptions of the database schema and is used to create and modify the structure of database objects in the database.
* DDL is a set of SQL commands used to create, modify, and delete database structures but not data.
* These commands are normally not used by a general user, who should be accessing the database via an application.

 
### List of DDL commands: 
1. CREATE: This command is used to create the database or its objects (like table, index, function, views, store procedure, and triggers).
2. DROP: This command is used to delete objects from the database.
3. ALTER: This is used to alter the structure of the database.
4. TRUNCATE: This is used to remove all records from a table, including all spaces allocated for the records are removed.
5. RENAME: This is used to rename an object existing in the database.

## Query:
### 1) Create a database studentdb

### SQL QUERY:
```
create database studentdbb;
```

### OUTPUT:
![image](https://github.com/sabithapaulraj/DBMS/assets/118343379/58fc5109-3fe3-4b71-adfa-c8de97a3eb0c)
![image](https://github.com/sabithapaulraj/DBMS/assets/118343379/a4e4ad5f-3b5d-4d4c-b347-54957dca3420)

### 2) Create a table student  and insert any two rows with the following fieds RegisterNumber,Name,Age,Address,Phone number

### SQL QUERY: 
```
 create table student(RegisterNumber int,Name varchar(100),Age int,Address varchar(250),PhoneNumber int) ;
```

### OUTPUT:
![image](https://github.com/sabithapaulraj/DBMS/assets/118343379/2ed4d00e-5741-4f71-a0d2-0384650e6dae)


### 3) Alter the above student table by adding another attribute department

### SQL QUERY: 
```
 alter table student add dept varchar(20);
```

### OUTPUT:
![image](https://github.com/sabithapaulraj/DBMS/assets/118343379/0d709df7-9e80-4b2c-a358-dac94a29b6fa)


### 4) Rename the student table to mystudent

### SQL QUERY: 
```
rename table student to mystudent;
```

### OUTPUT:
![image](https://github.com/sabithapaulraj/DBMS/assets/118343379/331990e2-babb-47a7-8576-d71ef8928eb3)


### 5) Delete the mystudent rows using truncate keyword

### SQL QUERY: 
```
 truncate table mystudent;
```
### OUTPUT:
![image](https://github.com/sabithapaulraj/DBMS/assets/118343379/73984590-23c6-4463-bb92-bfd6325824df)

### 4) Drop the mystudent table
 
### SQL QUERY: 
```
 drop table mystudent;
```

### OUTPUT:
![image](https://github.com/sabithapaulraj/DBMS/assets/118343379/f798b751-c946-4215-83de-d22ebf9c9d73)

## Result:
         Thus the basic DDL commands in SQL are executed. 
