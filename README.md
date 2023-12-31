# SQL-Parser-Implementation-for-Vengage-AI

## Goal
Implement backend code for the following problem statements

### Problem Statement 1
Write a method that reads phone book records from a CSV or JSON file. Each record consists of the following parameters Name, email, Phone 1, Phone 2.

### Problem Statement 2

Implement a SQL-like parser for phone book records in Problem 1 to implement CRUD 
operaNons and print SQL like output on console.

- 2.1 : SELECT * FROM phone_records; This statement reads the first 10 records and displays them  on the console.

- 2.2 SELECT * FROM phone_records WHERE name=’doe’; this statement filters the records and  displays the record(s) where ‘Doe’ is found

- 2.3 INSERT INTO phone_records(name, email,phone 1, phone 2)  VALUES(‘Test’,’test@test.xtyz’,’1234456’,’1233233’) This statement should create a new entry in the dataset and the same should be obtained  when execuNng secNon 2.2 (i.e. the previous example)

- 2.4 DELETE FROM phone_records WHERE name=’John’ This statement should delete the record from the dataset.

## Implementation instructions

### Languages and Tools required 

- Python 3.x
- Jupyter Notebook

### Libraries to import and install

- pandas
- csv
- faker
- prettytable (pip install PrettyTable)

### How to run

Click on Cell in navigation bar and select Run All option. You can see the implementation and results for all the given commands.

Separate SQL-like parsing functions have been written for each of the given commands to avoid confusion and increase clarity.

### Information about csv file

The csv file which is present here is just a sample to show that the format of the data is rightly generated according to the initial requirements of the task. In the implementation, synthetic generation of data has been done , due to which the data changes each time. Not to be confused with the sample data in this csv file. 


  
