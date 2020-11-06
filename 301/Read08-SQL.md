# ***Read 08***

![sql](https://cdn1.vectorstock.com/i/1000x1000/77/30/sql-database-icon-logo-design-ui-or-ux-app-vector-17507730.jpg)

# What is SQL ?


Today, Structured Query Language is the standard means of manipulating and querying data in relational databases, though with proprietary extensions among the products. The ease and ubiquity of SQL have even led the creators of many “NoSQL” or non-relational data stores, such as Hadoop, to adopt subsets of SQL or come up with their own SQL-like query languages.


![s](https://w7.pngwing.com/pngs/28/601/png-transparent-sql-logo-illustration-microsoft-azure-sql-database-microsoft-sql-server-database-blue-text-logo.png)

# Journey of SQL

If you wanted to list the students enrolled in CS 101. First you would find "CS 101" in the Courses set by name, set that as the owner or parent of the Enrollees set, find the first member (ffm) of the Enrollees set, which is a Student record, and list it. Then you would go into a loop: Find next member (fnm) and list it. When fnm failed, you would exit the loop.

That may seem like a lot of scut work for the database programmer, but it was very efficient at execution time. Experts like Michael Stonebraker of the University of California at Berkeley and Ingres pointed out that doing that sort of query in a CODASYL database such as IDMS took roughly half the CPU time and less than half the memory as the same query on a relational database using SQL.

![select](https://www.red-gate.com/wp-content/uploads/2018/03/word-image-83.png)

# SELECT

ay you wanted to list the students enrolled in CS 101. First you would find "CS 101" in the Courses set by name, set that as the owner or parent of the Enrollees set, find the first member (ffm) of the Enrollees set, which is a Student record, and list it. Then you would go into a loop: Find next member (fnm) and list it. When fnm failed, you would exit the loop.

That may seem like a lot of scut work for the database programmer, but it was very efficient at execution time. Experts like Michael Stonebraker of the University of California at Berkeley and Ingres pointed out that doing that sort of query in a CODASYL database such as IDMS took roughly half the CPU time and less than half the memory as the same query on a relational database using SQL.

#### SELECT
To retrieve data from a SQL database, we need to write SELECT statements, which are often colloquially refered to as queries. A query in itself is just a statement which declares what data we are looking for, where to find it in the database, and optionally, how to transform it before it is returned. It has a specific syntax though.

#### WHERE
In order to filter certain results from being returned, we need to use a WHERE clause in the query. The clause is applied to each row of data by checking specific column values to determine whether it should be included in the results or not.

#### DISTINCT
Even though the data in a database may be unique, the results of any particular query may not be – take our Movies table for example, many different movies can be released the same year. In such cases, SQL provides a convenient way to discard rows that have a duplicate column value by using the DISTINCT keyword.
#### INSERT 
When inserting data into a database, we need to use an INSERT statement, which declares which table to write into, the columns of data that we are filling, and one or more rows of data to insert. In general, each row of data you insert should contain values for every corresponding column in the table. You can insert multiple rows at a time by just listing them sequentially.

#### DELETE
When you need to delete data from a table in the database, you can use a DELETE statement, which describes the table to act on, and the rows of the table to delete through the WHERE clause.





### ***Thank you*** 😁😊