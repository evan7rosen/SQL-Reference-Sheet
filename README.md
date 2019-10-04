# SQL-Reference-Sheet

## How to create a database

The CREATE DATABASE statement is used to create a new SQL database.

`CREATE DATABASE databasename;`

## How to create a table

The CREATE TABLE statement is used to create a new table in a database.

```
CREATE TABLE table_name (
    column1 datatype,
    column2 datatype,
    column3 datatype,
   ....
);
```

The column parameters specify the names of the columns of the table.

The datatype parameter specifies the type of data the column can hold (e.g. varchar, integer, date, etc.).

## How to get everything from a single table

`SELECT * FROM TableName;`

## How to get one thing from a single table with a "where" clause

```
SELECT * FROM Customers
WHERE CustomerID=1;
```

## How to add something to a table

```
INSERT INTO table_name (column1, column2, column3, ...)
VALUES (value1, value2, value3, ...);
```

## How to edit something inside of a table

```
UPDATE table_name
SET column1 = value1, column2 = value2, ...
WHERE condition;
```

## How to remove something from a table

```
DELETE FROM table_name WHERE condition;
```
