# NoSQL Databases

### 1. What Are NoSQL Databases?
NoSQL databases are non-relational databases that do not store data in the traditional tabular format used by relational databases. Unlike relational databases, they do not require a fixed schema to define the structure of the data.
Instead, they store data using flexible data structures and formats such as JSON, XML, key-value pairs, and graphs.
NoSQL databases are mainly used to store and manage large volumes of structured, semi-structured, and unstructured data. They often use distributed systems to store and process data, ensuring high availability, scalability, and reliability.

### 2. Types of NoSQL Databases
There are four major types of NoSQL databases:
#### 1. Key-Value Store
* This type of database uses a dictionary-like structure to store data in key-value pairs.
* Each key must be unique and is used to retrieve its corresponding value.
* The value can be of any type, such as strings, numbers, objects, or even other data structures.
* It is commonly used for caching and fast data retrieval.
#### Examples:
* Amazon DynamoDB
* Redis

### 2. Document Store
* This type of database stores data in document formats such as JSON, XML, or BSON.
* It is designed to handle semi-structured data.
* Documents can contain simple values, complex objects, and nested objects.
* Each document has a unique ID that is used to retrieve the required data.
#### Examples:
* Amazon DocumentDB
* MongoDB

### 3. Wide-Column Store
* This type of database stores data in groups or families of related columns.
* It provides high scalability and flexibility when handling large volumes of data.
* It is commonly used in applications that require large-scale data storage, such as social media platforms and real-time analytics.
#### Examples:
* Apache Cassandra
* Google Cloud Bigtable

### 4. Graph Store
* This type of database stores data using nodes (vertices) and edges.
* Nodes represent entities, while edges represent relationships between those entities.
* Users can traverse the graph through connected nodes and edges to explore relationships between data.
* It is useful for applications that involve complex relationships.
#### Examples:
* Amazon Neptune
* Neo4j

## 3. Advantages of NoSQL Databases
#### 1. Flexible Schema
NoSQL databases support flexible data structures, allowing developers to store structured, semi-structured, and unstructured data (such as JSON or XML) without defining a rigid table structure beforehand.

#### 2. Horizontal Scalability
NoSQL databases can scale horizontally by adding more servers or nodes to a cluster instead of upgrading existing hardware. This makes them suitable for applications that handle large amounts of data.

#### 3. High Performance
NoSQL databases provide fast read and write operations for specific access patterns, such as key-value lookups, document retrieval, and column-family storage.

## 4. Disadvantages of NoSQL Databases
#### 1. Lack of Standardization
Unlike relational databases, NoSQL databases do not have a universal query language like SQL. Different database systems use their own APIs and query syntaxes.

#### 2. Limited Joins and Complex Queries
Performing relational joins across multiple datasets and executing complex queries can be difficult or less efficient compared to relational databases.

#### 3. Higher Operational Complexity
Managing and maintaining distributed NoSQL clusters can be challenging. It requires specialized administrative skills, proper configuration, monitoring, and application-level data management.

## 5. References
* https://docs.aws.amazon.com/whitepapers/latest/choosing-an-aws-nosql-database/types-of-nosql-databases.html    
* https://www.ibm.com/think/topics/nosql-databases
* https://www.youtube.com/watch?v=0buKQHokLK8