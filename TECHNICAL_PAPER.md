# Investigating NoSQL Databases for Improved Performance and Scalability

NoSQL databases are purpose-built for specific data models and store data in flexible schemas that scale easily for modern applications. NoSQL databases are widely recognized for their ease of development, functionality, and performance at scale. This page includes resources to help you better understand NoSQL databases and to get started.


## Scenario
In our current project, we are experiencing performance and scaling issues. After conducting an initial analysis, our team lead has suggested that we explore the use of NoSQL databases to address these challenges. This technical paper investigates five popular NoSQL databases, highlighting their features and use cases to determine their suitability for our project.



## NoSQL Databases

1. **MongoDB**
   - **Type**: Document Store
   - **Key Features**:
     - Schema flexibility with JSON-like documents.
     - High performance with efficient indexing.
     - Horizontal scaling through sharding.
   - **Use Cases**: Content management systems, real-time analytics, IoT applications, and mobile apps.

2. **Cassandra**
   - **Type**: Wide Column Store
   - **Key Features**:
     - High availability with no single point of failure.
     - Linear scalability and fault tolerance.
     - Optimized for high write throughput.
   - **Use Cases**: Time series data, sensor data, recommendation systems, and product catalogs.

3. **Redis**
   - **Type**: Key-Value Store
   - **Key Features**:
     - Extremely low latency and high throughput with in-memory data storage.
     - Supports various data structures such as strings, hashes, lists, sets, and sorted sets.
   - **Use Cases**: Caching, real-time analytics, session storage, leaderboards, and message brokering.

4. **Couchbase**
   - **Type**: Document Store
   - **Key Features**:
     - Memory-first architecture for high performance.
     - Easy and efficient scaling for large data volumes.
   - **Use Cases**: Mobile and web applications, real-time analytics, and customer 360 applications.

5. **Neo4j**
   - **Type**: Graph Database
   - **Key Features**:
     - Excels in handling complex and connected data with fast traversal of relationships.
     - Flexible schema supporting various types of relationships and properties.
   - **Use Cases**: Social networks, recommendation engines, fraud detection, and network/IT operations.

![Image shows how the database schema looks like](https://media.geeksforgeeks.org/wp-content/uploads/20220405112418/NoSQLDatabases.jpg)


## Types of databases — NoSQL

1. **Document-oriented databases**
   - A document-oriented database stores data in documents similar to JSON objects. Each document contains pairs of fields and values. The values can typically be a variety of types, including things like strings, numbers, booleans, arrays, or even other objects. A document database offers a flexible data model, much suited for semi-structured and typically unstructured data sets. They also support nested structures, making it easy to represent complex relationships or hierarchical data.

2. **Key-value databases**
   - A key-value store is a simpler type of database where each item contains keys and values. Each key is unique and associated with a single value. They are used for caching and session management and provide high performance in reads and writes because they tend to store things in memory. Examples are Amazon DynamoDB and Redis.

3. **Wide-column stores**
   - Wide-column stores store data in tables, rows, and dynamic columns. The data is stored in tables. However, unlike traditional SQL databases, wide-column stores are flexible, where different rows can have different sets of columns. These databases can employ column compression techniques to reduce the storage space and enhance performance. The wide rows and columns enable efficient retrieval of sparse and wide data. Some examples of wide-column stores are Apache Cassandra and HBase.

4. **Graph databases**
   - A graph database stores data in the form of nodes and edges. Nodes typically store information about people, places, and things (like nouns), while edges store information about the relationships between the nodes. They work well for highly connected data, where the relationships or patterns may not be very obvious initially. Examples of graph databases are Neo4J and Amazon Neptune.

## Conclusion
Each NoSQL database offers unique strengths and is suited to different types of applications and workloads. Based on our project’s specific requirements—such as data type, volume, read/write patterns, and need for scalability and high availability—we can select the most appropriate NoSQL database to improve our system’s performance and scalability.

## References
* [MongoDB Explained](https://www.mongodb.com/nosql-explained)
