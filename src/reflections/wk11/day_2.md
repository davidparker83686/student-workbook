# Day 2 - MYSQL RELATIONSHIPS (MANY-TO-MANY)

Daily Journal
Read Dotnet WebAPI's > Relationships, and answer the following questions

## What is the difference between a primary key and a foreign key
```
Primary key is a chosen unique Property that can be used to Identify the table where a foreign key is how a child table looks at the parent table using the parents primary key as the childs foreign key
```

## What is an Alias?
```
A situation where the same memory location can be accessed using different names.
```

## Demonstrate how you would query a join statement that would get all of a doctors patients from the following collections:
```
string sql = @"
                SELECT
                d.*,
                p.*
                dp.id as doctorpatientId,
                dp.patientId as patientId,
                dp.doctorId as doctorId
                FROM
                doctors_patients dp
                JOIN doctors d ON d.id = dp.doctorId
                JOIN patients p ON p.id = dp.patientId
                WHERE
                dp.doctorId = @doctorId;
            ";
```

CREATE TABLE doctors (
  id INT NOT NULL AUTO_INCREMENT,
  -- CODE OMITTED
  PRIMARY KEY (id)
)

CREATE TABLE patients (
  id INT NOT NULL AUTO_INCREMENT,
  -- CODE OMITTED
  PRIMARY KEY (id)
)

CREATE TABLE doctors (
  id INT NOT NULL AUTO_INCREMENT,
  doctorId INT NOT NULL,
  patientId INT NOT NULL,

  FOREIGN KEY (doctorId)
    REFERENCES doctors(id),
  FOREIGN KEY (patientId)
    REFERENCES patients(id),


AFTERNOON-https://davidparker83686.github.io/job_and_contractors/