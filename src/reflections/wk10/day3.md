# Week 10( Day 3)

## In a SQL table, what is the difference between information in a row and information in a column?

Information in a row, represents a sequence of one or more column values and information in a column represents it's own value.

## Demonstrate the basic structure for creating a new table called characters with the values name, age, description as strings, and an int id.

Create table TABLENAME (
  id int not null,
  name VARCHAR(255),
  age VARCHAR(255),
  description VARCHAR(255)
)

## What is the difference between the following statements:

DELETE FROM table_name;
DROP TABLE table_name;

DELETE FROM table_name - removed all the rows, but updated the database log.
DROP TABLE table_name - removed the entire table from the database, with out logging.


Lab Url: https://github.com/shankerkarra/knightstale.git