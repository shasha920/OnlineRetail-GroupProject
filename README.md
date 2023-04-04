# OnlineRetail-GroupProject<br>


*GBA 5140 Statistics Essentials for Business Analytics<br>*

*Turo Project Description<br>*

*team member: Ramon Gomez, Harry Ho, Noor Latif, Daniel Nguyen, Hua Yang<br>*

*Purpose<br>*

This project for like DBA to build a database to keep track of their inventory system. Inputs: Online Retail SpreadSheet named “Online Retail.xlsx” (top 200 rows)
The specific tasks:
1) Review the existing spreadsheet, and their sample data and make any assumptions you need about the company;
2) Design a data model(ERD, logical data model) using Erwin Modeler after reviewing the existing spreadsheet. Add any attributes(including data range) that you think could be useful. Identify primary keys, foreign keys, and relationships;
3) Perform a functional dependency analysis. Make sure all the tables are at least in 3NF. Make changes to the ERD if necessary;
4) Create a database using SSMS. Use SQL statements to create tables, insert rows, and create constraints;
5) The required constraints are:
a.	the date of Invoice must be after ‘2010-Jan-01’
b.	the customer id must be a five-digit number
c.	the default value of quantity is 0
d.	quantity is between 0 and 200
e.	use ON DELETE CASCADE and ON UPDATE CASCADE for the foreign key of the weak entity
6) Add a column into table Product to indicate the inventory status(If the column has not been created in previous steps). Create a trigger named quantity_update that checks the quantity of each product
Trigger timing and event: After Updating rows in the product table
Trigger action: If the quantity is below 5, then change the inventory status to “Need attention”
7) Run two queries:
a.	Find all the customers(ids) who purchased “CREAM CUPID HEARTS COAT HANGER” and “SAVE THE PLANET MUG”
b.	Find out which customer spent most money.<br>

*Briefly<br>*

*1.	Use Excel explore data.<br>*

*2.	Use Lucid and Erwin build ERD AND 3NF.<br>*

*3.	Use Excel filter data, remove duplicate row, slice data.*

*4.	Use SQL Server build database, use SQL create table, constraint, insert into data.<br>*

*5.	Test dataset<br>*

*6.	Check constraints.<br>*

