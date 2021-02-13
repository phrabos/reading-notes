The keywords to use when using SQL are:
- SELECT - used for selecting columns
- FROM - name of table
- WHERE - set of conditions
- ORDER BY - column ASC/DESC
- LIMIT - how many rows of data OFFSET- how many to skip
Multiple Table Query Using Joins:
- JOIN - allows to combine row data across two separte tables
    - the ON keyword tells SQL what the common data point is in the two tables: ```ON movies.id = boxoffice.move_id```.
INNER vs OUTER :   outer joins remind me of something similar to a pivot table.
Having NULL values on a database will require special queries to handle the null values. Try to avoid null by using zero for numbers or empty strings for text. 
- https://www.essentialsql.com/get-ready-to-learn-sql-database-normalization-explained-in-simple-english/

Database Normalization: The process of  planning what data a table will have and what order to avoid duplicate data from other tables.
Three common forms of database normalization: 1st, 2nd, 3rd.
- First - the information is stored in a relational table with each column containing atomic values, no repeating groups of columns
Second - First Form, plus all the columns depend on the table's primary key (single purpose)
Third - columns are not transitively dependent on the primary key

- https://www.codeproject.com/Articles/33052/Visual-Representation-of-SQL-Joins
A join is an operation allowing the user to retrieve data from multiple tables. Self joins are will join a table with itself to include data from multiple columns into a single column.