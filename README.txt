# SQL Proyect
## The purpose of this project is to practice basic SQL commands.
### Learning to create a DATABASE, TABLE and perform basic operations.

### SQL commands

CREATE DATABASE ej_sql;

USE ej_sql;

CREATE TABLE workers  (
  id INT PRIMARY KEY,
  name VARCHAR(50)
);

INSERT INTO workers (id, name)
VALUES (007, JUAN);

Select *FROM workers;

UPDATE workers (id, name)
SET name = Juan Alberto
WHERE id= 007;

DELETE FROM workers
WHERE id = 007;