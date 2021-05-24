# Day 4 - CONNECTING TO A MYSQL DATABASE

Daily Journal
Read Dotnet WebAPI's > Welcome to SQL, and answer the following questions
## In a SQL table, what is the difference between information in a row and information in a column?
```
Rows will have all the differnt Properties for that object(ex: id,name,email,picture) while columns will have all the same properties for all the differnt objects in the table(ex: id,id,id,id). 
```
## Demonstrate the basic structure for creating a new table called characters with the values name, age, description as strings, and an int id.
```
CREATE TABLE basicStructure (
   id VARCHAR(255) NOT NULL,
   name VARCHAR(255) NOT NULL,
   age INT NOT NULL,
   description VARCHAR(255) NOT NULL,
   PRIMARY KEY (id)
);
```
## What is the difference between the following statements:
```
DELETE FROM table_name;
DROP TABLE table_name;
```