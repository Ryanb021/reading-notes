# Read 11

## MongoDB and Mongoose

# 5 Differences between SQL and NoSQL databases

# SQL

- SQL databases are primarily called as Relational Databases (RDBMS).

- SQL databases are table based databases which means that SQL databases represent data in form of tables which consists of n number of rows of data.

- SQL databases have predefined schema.

- SQL databases are vertically scalable, SQL databases are scaled by increasing the horse-power of the hardware.

- SQL databases uses SQL ( structured query language ) for defining and manipulating the data, which is very powerful.

# NoSQL

- NoSQL database are primarily called as non-relational or distributed database.

- NoSQL databases are document based, key-value pairs, graph databases or wide-column stores which means NoSQL databases are the collection of key-value pair, documents, graph databases or wide-column stores which do not have standard schema definitions which it needs to adhered to.

- NoSQL databases have dynamic schema for unstructured data.

- NoSQL databases are horizontally scalable, NoSQL databases are scaled by increasing the databases servers in the pool of resources to reduce the load.

- NoSQL database, queries are focused on collection of documents. Sometimes it is also called as UnQL (Unstructured Query Language). The syntax of using UnQL varies from database to database.


## What kind of data is a good fit for an SQL database?

- Complex query intensive environment

## Give a real world example.

- Date and Time data types such as Date, Time, Datetime etc.
- 
## What kind of data is a good fit a NoSQL database?

- For example, you may have a Business document. Not all businesses have an email address for example. Businesses that don't have an email address won't have an 'email' key in their document. The document store takes care of storing the email when necessary and ignoring it when not available.

## Give a real world example.


## Which type of database is best for hierarchical data storage?

- NoSQL fits better for the hierarchical data storage as it follows the key-value pair way of storing data similar to JSON data. NoSQL database are highly preferred for large data set (i.e for big data).

## Which type of database is best for scalability?

- It depends. As in most typical situations, SQL databases are vertically scalable. You can manage increasing load by increasing the CPU, RAM, SSD, etc, on a single server. On the other hand, NoSQL databases are horizontally scalable. You can just add few more servers easily in your NoSQL database infrastructure to handle the large traffic.

## What does SQL stand for?

- Structured Query Language

## What is a relational database?

- A relational database is a type of database that stores and provides access to data points that are related to one another. Relational databases are based on the relational model, an intuitive, straightforward way of representing data in tables.

## What type of structure does a relational database work with?

- Relational databases are based on the relational model, an intuitive, straightforward way of representing data in tables. In a relational database, each row in the table is a record with a unique ID called the key.

## What is a ‘schema’?

- A schema is a list of logical structures of data. A database user owns the schema, which has the same name as the database manager.

## What is a NoSQL database?

- NoSQL, also referred to as “not only SQL”, “non-SQL”, is an approach to database design that enables the storage and querying of data outside the traditional structures found in relational databases.

## How does it work?

- As a non-relational database, it can process structured, semi-structured, and unstructured data. It uses a non-relational, document-oriented data model and a non-structured query language.

## What is inside of a MongoDB database?

- MongoDB stores data records as documents (specifically BSON documents) which are gathered together in collections. A database stores one or more collections of documents.

## Which is more flexible - SQL or MongoDB? and why.

- While MongoDB is more flexible and ensures high and diverse data availability, a SQL Database operates with the ACID (Atomicity, Consistency, Isolation, and Durability) properties and ensures greater reliability of transactions.

## What is the disadvantage of a NoSQL database?

-  They don't support ACID (atomicity, consistency, isolation, durability) transactions across multiple documents. With appropriate schema design, single-record atomicity is acceptable for lots of applications.
