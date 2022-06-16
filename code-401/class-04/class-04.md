# Readings: Data Modeling

## Reading
[nosql vs sql](https://www.thegeekstuff.com/2014/01/sql-vs-nosql-db/?utm_source=tuicool)

1. What type of database is the best fit for the complex query intensive environment?

    ```
    SQL
    ```

2. What type of database is the best fit for hierarchical data storage?

    ```
    NoSQL
    ```

3. Describe the differences in scalability between a SQl and NoSQL database as though you were speaking to a non-technical friend.

    ```
    For scalability: In most typical situations, SQL databases are vertically scalable. You can manage increasing load by increasing the CPU, RAM, SSD, etc, on a single server. On the other hand, NoSQL databases are horizontally scalable. You can just add few more servers easily in your NoSQL database infrastructure to handle the large traffic.
    ```

[sql modeling techniques](https://www.essentialsql.com/get-ready-to-learn-sql-7-simplified-data-modeling/)

1. Among data tables, what is a one-to-many relationship and how do we “relate” them?

    ```
    A one-to-many relationship is a key from one table links to many keys in another table.

    1..*
    ```

2. Prior to designing your relational database, it might be useful to ___ a ___ of the database tables and their relationships.

    ```
    create a diagram
    ```

3. Explain the difference between a primary and foreign key.

    ```
    primary keys uniquely identify each row in a table.

    foreign keys match primary keys in another table.
    ```

## Videos
[sql vs nosql](https://www.youtube.com/watch?v=ZS_kXvOeQ5Y)

1. How do we treat keywords and parameters differently in SQL syntax?

    ```
    single quotes
    ```

2. Define normalization within the context of schemas and data.

    ```
    normalization is modeling data in such a way that no table can have redundant data elements
    ```

3. Explain the difference between one-to-one, one-to-many, and many-to-many relationships to a non-technical recruiter.

    ```
    one-to-one relationship: one record from one table matches one record from another, uniqeuly

    one-to-many: one record from one table matches many records in another

    many-to-many: many records from one table matches many records from another
    ```

## Bookmark and Review
[sequelize api](https://sequelize.org/master/)
