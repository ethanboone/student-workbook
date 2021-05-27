# Day 2 

## Daily Journal
Read Dotnet WebAPI's > Relationships, and answer the following questions
1. What is the difference between a primary key and a foreign key
The primary key is the unique identifier and the foreign key references other data on a different table.
2. What is an Alias?
alias is a variable defined in a mysql statement and we use it to store a new table in temporary memory with JOIN.
3. Demonstrate how you would query a join statement that would get all of a doctors patients from the following collections:

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

        CREATE TABLE doctors_patients (
        id INT NOT NULL AUTO_INCREMENT,
        doctorId INT NOT NULL,
        patientId INT NOT NULL,

        FOREIGN KEY (doctorId)
            REFERENCES doctors(id),
        FOREIGN KEY (patientId)
            REFERENCES patients(id),
        )

SELECT
    d.*,
    p.*
FROM 
doctors_patients dp
JOIN doctors d ON d.id = dp.doctorId
JOIN patients p ON p.id = dp.patientId
WHERE 
dp.doctorId = @doctorId;