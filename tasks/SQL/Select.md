# Select statement
- Where to practice?

The w3school provides database with the existing prefilled tables, for example Customers, Orders,
Products etc.

You can easily use this resource with contain already populated tables. Be free to modify anything, after
refresh the state of tables will remain.
https://www.w3schools.com/sql/trysql.asp?filename=trysql_select_all

# Tasks
- Q1: Write an SQL query to fetch “CustomerName” from Customer table using the alias name as "Customers".
- Q2: Select the City and Country from Customer table.
- Q3: Select all colomns where Country is Germany.
- Q4: Select all columns where City is not Madrid.
- Q5: Select all columns where CustomerId is graeter than 15 but less than 25.
- Q6: Select CustomerName in upper case.
- Q7: Select unique countries (tables should return unique countries in the table).
- Q8: Select the length of unique countries (table should return the length of country name).
- Q9: Select all columns in distirct order, sorted by City. (table should return the same result but in distinct order by City).
- Q10: Select CustomerName column which name starts from 'A' (table should return only customers which name starts from 'A').

# Answers 
- A1:
- A2: SELECT City, Country FROM Customers;
- A3: SELECT * FROM Customers WHERE Country = 'Germany';
- A4: SELECT * FROM Customers WHERE NOT City  = 'Madrid';
- A5: SELECT * FROM Customers WHERE CustomerID BETWEEN 15 AND 25;
- A6: SELECT UPPER(CustomerName) AS UppercaseCustomerName FROM Customers;
- A7: SELECT DISTINCT Country FROM Customers;
- A8: SELECT LENGTH(DISTINCT Country) AS LengthOfCountry FROM Customers;
- A9: SELECT * FROM Customers ORDER BY City; 
- A10: SELECT CustomerName FROM Customers Where [CustomerName] like 'a%'
Hello world!