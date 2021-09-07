# Week 11( Day 2)

## What is the difference between a primary key and a foreign key

A Primary key constraint on a column signifies that it is uniquely identifies for every roew in a table. Whereas Foreign Key is a column that creats a relationship between two tables.

A table can only contain singl Primary Key, whereas foreign key can have multiple foreign keys.

Primary key can't have duplicate values, whereas table containing foreign key can have multiple rows with th same value.

Foreign key values are validate against primary key for references. Any value that is not part of the primary key willn't be inserted into foreign table.a column of a primary key.

## What is an Alias?

An Alias in SQL statemnts are used as a temporary name for shorter representation 
used for tables, columns. 


## Demonstrate how you would query a join statement that would get all of a doctors patients from the following collections:

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

CREATE TABLE doctorspatients (
  id INT NOT NULL AUTO_INCREMENT,
  doctorId INT NOT NULL,
  patientId INT NOT NULL,

  FOREIGN KEY (doctorId)
    REFERENCES doctors(id),
  FOREIGN KEY (patientId)
    REFERENCES patients(id),
)

SQL Statement

select 
dp.*, d.*, p.* from doctorspatients dp
JOIN doctors d on d.id = dp.doctorId,
join patients p on p.id = dp.patientId
