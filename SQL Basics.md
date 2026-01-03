Boot.dev SQL basics Course notes: 

A **relational database** is a collection of information that organizes data in predefined relationships where data is stored in one or more tables (or "relations") of columns and rows, making it easy to see and understand how different data structures relate to each other. Relationships are a logical connection between different tables, established on the basis of interaction among these tables.

Create, Read, Update and Delete (CRUD) operations are performed on relational databases. 

We will use **SQLite** for learning.
SQLite is great for embedded projects, web browsers, and toy projects. It's lightweight, but has limited functionality compared to the likes of PostgreSQL or MySQL - two of the more common production SQL technologies.

SQLite is a bit different is that it stores Boolean values as integers - the integers 0 and 1.   
0 = false  
1 = true  
Note: Like Python and JavaScript, SQLite has a loose type system.     

**NoSQL:**   
NoSQL databases tend to be fairly unique and are used for more niche purposes. Some of the main differences between SQL and NoSQL databases are:   
  NoSQL databases are usually non-relational, SQL databases are usually relational.   
  SQL databases usually have a defined schema, NoSQL databases usually have dynamic schema.   
  SQL databases are table-based, NoSQL databases have a variety of different storage methods, such as document, key-value, graph, wide-column, and more. 

Two great relational database are PostgreSQL and SQLite. Comparison between the two are documented in the link: https://db-engines.com/en/system/PostgreSQL%3BSQLite


