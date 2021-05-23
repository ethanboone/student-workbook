# Day 3

## Daily Journal 
Read Dotnet WebAPI's > Welcome to SQL, and answer the following questions
1. In a SQL table, what is the difference between information in a row and information in a column?
A row contains an entire data "object" or model, a column would just be a single value.
2. Demonstrate the basic structure for creating a new table called characters with the values name, age, description as strings, and an int id.
NEW TABLE example (
    name VARCHAR(255) NOT NULL,
    age INT NOT NULL,
    description VARCHAR(255) NOT NULL,
    id INT NOT NULL AUTO_INCREMENT
);
3. What is the difference between the following statements:
DELETE FROM table_name;
DROP TABLE table_name;

Delete from table just deletes a row, drop table deletes the entire table of data.