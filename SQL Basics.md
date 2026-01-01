Boot.dev SQL basics Course notes: 

A **relational database** is a collection of information that organizes data in predefined relationships where data is stored in one or more tables (or "relations") of columns and rows, making it easy to see and understand how different data structures relate to each other. Relationships are a logical connection between different tables, established on the basis of interaction among these tables.

Create, Read, Update and Delete (CRUD) operations are performed on relational databases. 

We will use **SQLite** for learning.
SQLite is great for embedded projects, web browsers, and toy projects. It's lightweight, but has limited functionality compared to the likes of PostgreSQL or MySQL - two of the more common production SQL technologies.

SQLite is a bit different is that it stores Boolean values as integers - the integers 0 and 1.
0 = false
1 = true
