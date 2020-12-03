# DataBase-Management--warehouse
Data normalization, T-SQL and UI
Normalization is a database design technique that reduces redundancy and eliminates undersirable characteristics like insertion, Update and Deletion Anomalies.
Normalization rules divides larger tables into smaller tables and links them using relationships. The pirpose of Normalization in SQL is to eliminate redundant(repetitive) data and ensure data is stored logically.

# Anomalies in DBMS
- Insertion
- Update
- Deletion

# Functional Dependencies
- Let X and Y be sets of attributes in R. Y is functionally dependent on X in R iff for each x ∈ RX there is precisely one y ∈ RY

# Full Functional Dependencies
- Let X and Y be sets of attributes in R. Y is fully functional dependent on X in R iff Y is funcional dependent on X and Y is not functional dependent on any proper subset of X
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
(From 2NF to 3NF, it will be very straightfoward cut the table using transitive function. When you find the relationship X-> Y, you can use X to split table. X is the super key of the table)

# BCNF (Boyce-Codd Normal Form)
- Even when a database is in 3rd Normal Form, still there would be anomalies resulted if it has more than one Cndidate Key
Sometimes is BCNF is als referred as 3.5 Normal Form
