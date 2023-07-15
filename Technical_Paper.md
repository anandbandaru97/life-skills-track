# NoSQL (Not only SQL) 
Used to describe a category of databases that differ from relational databases (SQL databases) in terms of data model, storage, and query methods. NoSQL databases were developed to address specific requirements of modern applications, such as scalability, high performance, and flexibility in handling unstructured or semi-structured data.

## Key Characteristics:

**Data Model:** Uses various data models, such as key-value pairs, document-based, columnar, and graph-based models. Each model is suited for different types of data and use cases.

**Scalability:** Designed to scale horizontally across multiple servers or nodes. They can handle large amounts of data and high traffic loads by distributing the data and workload across the nodes.

**Schema-less:** Unlike relational databases, NoSQL databases typically do not enforce a fixed schema. They allow flexible schema designs and can handle evolving data structures without requiring schema modifications.

**High Performance:** NoSQL databases optimize for high-speed read and write operations. They often sacrifice some features offered by SQL databases, such as complex joins and transactions, to achieve higher performance.

## Types of NoSQL Databases:

**Key-Value Stores:** Simplest form of NoSQL databases. They store data as a collection of key-value pairs, where each value is associated with a unique key.
Ex - Redis, Amazon DynamoDB, and Riak.

**Document Databases:** It stores data in flexible, semi-structured documents, typically in formats like JSON or XML. Each document can have its own structure, and the data is typically organized in collections or buckets.
Ex - MongoDB, Couchbase, and Elasticsearch.

**Columnar Databases:** It stores data in columns rather than rows, which allows for efficient data compression and querying of specific columns. They are optimized for analytical workloads that involve aggregations and complex queries.
Ex - Apache Cassandra, HBase, and Vertica.

**Graph Databases:** Designed to represent and store data in the form of nodes, edges, and properties. They are well-suited for scenarios that involve complex relationships and interconnected data, such as social networks, recommendation engines, and fraud detection.
Ex - Neo4j, Amazon Neptune, and JanusGraph.

**Wide-Column Stores:** Also known as column-family databases, combine the features of columnar and key-value databases. They store data in column families, where each column family can have multiple columns. Wide-column stores provide high scalability and are often used for large-scale distributed systems.
Ex - Apache Cassandra.

These five types represent different data models and are designed to address specific use cases and requirements. The choice of the NoSQL database type depends on factors such as the nature of the data, scalability needs, query patterns, and performance requirements of the application.

Reference - [Refer Here](https://www.mongodb.com/nosql-explained)
