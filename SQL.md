# SQL ( Structured Query Language):
![](https://th.bing.com/th/id/R666f61f55cd1fb1c57e9877b15463555?rik=EdgotAmkIp7nYQ&riu=http%3a%2f%2fcontent.wisestep.com%2fwp-content%2fuploads%2f2014%2f10%2fsql.gif&ehk=AZmV5ibMAXbhbGOeKzAF2kUv4r9D%2fP%2bjIq%2fOfrhRSbs%3d&risl=&pid=ImgRaw)


-----

## It is a language designed to allow both technical and non-technical users query, manipulate, and transform data from a relational database.
## Before learning the SQL syntax, it's important to have a model for what a relational database actually is. A relational database represents a collection of related (two-dimensional) tables. Each of the tables are similar to an Excel spreadsheet, with a fixed number of named columns (the attributes or properties of the table) and any number of rows of data.
1. ### Select queries:
           SELECT column, another_column, …
           FROM mytable;

2. ### Queries with constrains:
            SELECT column, another_column, …
            FROM mytable
            WHERE condition
            AND/OR another_condition
            AND/OR …; 

3. ### Filtering and storing query result:
        Select query with limited rows

        SELECT column, another_column, …
        FROM mytable
        WHERE condition(s)
        ORDER BY column ASC/DESC
        LIMIT num_limit OFFSET num_offset;

