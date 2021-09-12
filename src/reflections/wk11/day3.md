# Week 11( Day 3)

## What is SQL injection?

SQL injection is an attack, where malicious code can be sent as a user input which is passed on as parameter for execution.

SQL injection is an attack in which malicious code is inserted into strings that are later passed to an instance of SQL Server for parsing and execution. Any procedure that constructs SQL statements should be reviewed for injection vulnerabilities because SQL Server will execute all syntactically valid queries that it receives. Even parameterized data can be manipulated by a skilled and determined attacker.

## What are 3 methods SQL injection can be done by?

User input forms
Modify cookies or tokens
Attacking Operating system

## How can we detect and sanitize SQL injection attacks?

Use SQL Prepared statements with parameterized queries, instead of direct user-supplied input.

Control account privileges.

Remove default stored procedures, which are shipped along with databases and use stored procedures instead of direct SQL Statements.