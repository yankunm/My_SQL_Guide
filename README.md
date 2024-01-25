# Yankun"s SQL Guide

SQL stands for **Structured Query Language**. It is used to **communicate with databases**.

## Database Basics

Databases are analogous to Spreadsheets in Excel/Google Sheets, where the tabs are called **tables**, and in each tab there are data organized in **rows and columns**. Unlike spreadsheets, databases can handle larger amounts of data, have data integrity, automate, and be used for websites and applications.

There are numerous SQL-based databases, some common options include *PostgreSQL, MySQL, MariaSQL, SQLite, Oracle Databases or MS SQL Server Express*. You can also use SQL on systems like *Hive, Google's BigQuery, or Facebook's Presto* to work with distributed data.

## SQL Basics

* `SELECT` column `FROM` table - selects the specific columns from table (e.g. `*` means all)
* SELECT `DISTINCT(column)` FROM table - call distinct on columns to remove duplicates
* SELECT `COUNT(*)` FROM table - called on columns to count how many rows there are
* SELECT * FROM table `WHERE` conditions - returns columns that only satisfy the conditions (make sure to use single quotes around strings)
* ... `ORDER BY` column `ASC/DESC` - sorts the columns based ascending or descending
* ... `LIMIT` how_many - limit the number of rows returned for the query
* `(NOT)` `BETWEEN` a `AND` b - between (not between) two conditions inclusive

Note: BETWEEN can be used with dates, but it stops on the  0:00 mark not the 23:59  mark
* WHERE color `IN ('red', 'blue')` - check if a value is in a list of options
* WHERE name `LIKE '_Cher%` - perform pattern matching, where `_` represents a single character and `%` represents a sequence of characters (`ILIKE` is the case-insensitive version)




