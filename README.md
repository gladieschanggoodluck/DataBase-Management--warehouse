# DataBase-Management--warehouse
Data normalization, T-SQL and UI
Normalization is a database design technique that reduces redundancy and eliminates undersirable characteristics like insertion, Update and Deletion Anomalies.
Normalization rules divides larger tables into smaller tables and links them using relationships. The pirpose of Normalization in SQL is to eliminate redundant(repetitive) data and ensure data is stored logically.

DataBase Normal Form
- 1NF (First Normal Form)
- 2NF (Sencond Nromal Form)
- 3NF (Third Normal Form)
- BCNF (Boyce-Codd Normal Form)
- 4NF (Forth Normal Form)
- 5NF (Fifth Normal Form)
- 6NF (Sixth Normal Form)

# 1NF (First Normal Form) Rules
- Each table cell should contain a single value
- Each record needs to be unique

# 2NF (Second Normal Form) Rules 
- Rule 1- Be in 1NF
- Rule 2- Single Column Primary Key
(From 1NF to 2NF is quite straightforward, you need to observed the duplicated rows, and use new primary key to partition table)

# 3NF (Third Normal Form) Rules
- Rule 1 - Be in 2NF
- Rule 2 - Has no transitive functional dependencies
