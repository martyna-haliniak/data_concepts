#Joins

**What is a JOIN?**  
A JOIN combines rows from two or more tables based on a related column 
(often a foreing key).

**JOIN Types**
Below are the four main types of JOINs, each with a different way of 
combining data from two tables.

1. INNER JOIN  
Returns only the rows that have matching values in both tables.

<pre> ```sql SELECT * FROM Customers AS c INNER JOIN Orders AS o
 ON c.CustomerID = o.CustomerID; ``` </pre>

  - Matches only where CustomerID exists in both Customers and Orders.


