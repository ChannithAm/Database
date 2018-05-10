# Database
Database, MySQL, SQL, ... (note)


A **database** is a collection of `information` that is organized so that it can be easily `accessed`, `managed`, and `updated`.

- Data is organized into rows, columns and tables, and it is indexed to make it easier to find relevent information.
- Data get updated, expanded and deleted as new information is added.
- Databases process workloads to create and update themselves, querying the data they contain and running applications against it.
- Computer databases typically contain aggregations of data records or files, such as sales transactions, product catalogs and inventories, and customer profiles.
- Typically, a database manager provides users with the ability to control `read/write` access, specify report generation and analyze usage.

# Evolution of database
Databases have evolved since their inception in the 1960s, beginning with `hierachical` and `network databases`, through the 1980s with `object-oriented database`, and today with `SQL` and `NoSQL` databases and `cloud databases`.

* In one view, databases can be classified according to content type:
    * Bibiliographic
    * Full text
    * Numeric
    * and Images

* In computing, databases are sometimes classified according to their organizational approach. There are many different kinds of databases, ranging from the most relevent approach, the relational, to a distributed database, cloud database or NoSQL database.

# Relatinal database
- A **relational database**, invented by E.F. Codd at IBM in 1970, is a tabular database in which data is defined so that it can be reorganized and accessed in a number of different ways.
- Relational databases are made up of a set of tables with data that fits into q predefined category. Each table has at least one data category in a column, and each row has a certain data instance for the categories which are defined in the columns.
- The `Structured Query Language` (SQL) is the standard user and application program interface for a relational database. Relational databases are easy to extend, and a new data category can be added after the original database creation without requiring that modify all the existing applications.

# Distributed database
- A **distributed database** is a database in which portions of the database are stored in multiple physical locations, and in which processing is dispersed or replicated among differnt points in a network.
- Distributed databases can be homogeneous or heterogeneous. All the physical locations in a homogeneous `distributed database system` have the same underlying hardware and run the same operation systems and database applications. The hareware, operating system or database applications in a heterogeneous distributed database may be different at each of the locations.

# Cloud database
- A **clud database** is a database that has been optimized or built for a virtualized environment, either in a hybrid cloud, public cloud or private cloud.
- Cloud database provide benifits such as the ability to pay for storage capacity and bandwith on a per-use basis, and the provide scalability on demand, along with high availability.
- A cloud database also gives enterprises the opportunity to support business applications in a software-as-a-service deployment.

# NoSQL database
- NoSQL database aer useful for large sets of distributed data.
- NoSQL database are effective for big data performance issue that relational databases aren't built to solve. They are most effective when an organization must analyze large chunks of unstructured data or data that's stored across multiple virtual servers in the cloud.

# Object-oriented database
- Items created using `object-oriented programming language` are often stored in relational databases, but object-oriented databases are well-suited for those items.
- An object-oriented database is organized around objects rather than actions, and data rather than logic. For example, a multimedia record in a relational database can be a defined data object, as opposed to an alphanumeric value.

# Graph database
- A **graph-oriented databse**, or graph database, is a type NoSQL database that useds graph theory to stor, map and query relationships. Graph databases are basically collections of nodes and edges, where each node represents and entity, and each edge represents a connection between nodes.
- Graph databases are growing in popularity for analyzing interconnections. For example, companies might use a graph database to `mine data` about customers from social media.

# Accessing the database: DBMS and RDBMS
- A database management system (DBMS) is a type of software that allows you to define, manipulate, retrieve and manage data stored withing a database.
- A relational database management system (RDBMS) is a type of database management software that was developed in the 1970s, based on the relational model, and is still the most popular way to manage a database.
- Microsoft SQL Server, Orace Database, IBM DB2 and MySQL are the top RDBMS products available for enterprise users. DBMS technologies began in the 1960s to support hierachical databases, and they conclude IBM's Information Management System and CA's Integrated Database Management System.

```
This article credit to: https://searchsqlserver.techtarget.com/definition/database
```