# Services, Hard Parts

1. Apps - **Getting Boundaries Right**
2. Distributed Data Management - **Data Consistency & Deleting Data, Ex: CCPA**
3. Purpose-built Databases - **SQL & NoSQL**

## Apps
  * [Microservice, Why?](https://chrisrichardson.net/post/microservices/2020/02/18/why-microservices-part-1.html)
    * [Microservice Architecture](https://microservices.io/patterns/microservices.html)
  
APIs - REST, GraphQL or gRPC or anything else 
  * [DTOs](https://martinfowler.com/eaaCatalog/dataTransferObject.html)

Data Access patterns - Mapping between application & database structures. The two major categories are the [active record pattern](http://calpaterson.com/activerecord.html) and the data mapper pattern.

The Data model comprises of
1. Collection of Domain models like Customer, Order & Item 
2. Schema of the underlying database like Tables/Columns
  
## Distributed Data Management
Data Consistency
  * [Using Sagas](https://chrisrichardson.net/post/microservices/2019/07/09/developing-sagas-part-1.html)

Deleting Data - Cross cutting concerns, Data Catalog of Online microservices & Offline Warehouses;Data Discoverability, Access & Processing;Abstraction ... 
  * [Twitter Use-case](https://blog.twitter.com/engineering/en_us/topics/infrastructure/2020/deleting-data-distributed-throughout-your-microservices-architecture.html) 

## DBaaS 

"It wasn't that long ago when the DBAs owned THE shared database. Nowadays, in all kinds of companies, no one blinks an eyelid when every service has its own database. The most unexpected things can change so quickly."

top-level database object

A keyspace is the top-level database object that controls the replication for the object it contains at each datacenter in the cluster. Keyspaces contain tables, materialized views and user-defined types, functions and aggregates. Typically, a cluster has one keyspace per application. Since replication is controlled on a per-keyspace basis, store data with different replication requirements (at the same datacenter) in different keyspaces. Keyspaces are not a significant map layer within the data model.

**Landscape** - IN-MEMORY, RELATIONAL, KEY VALUE, WIDE COLUMN, DOCUMENT, TIME-SERIES, LEDGER

* Big Table:
  * [Cassandra](https://www.datastax.com/blog/2020/05/why-astra-good-cassandra)
  * [ScyllaDB](https://www.scylladb.com/2020/05/07/introducing-scylla-open-source-4-0/)
  * Dynamo:
    * Single Table Design - https://www.alexdebrie.com/posts/dynamodb-single-table/
    * GraphQL/Multi Table - https://www.alexdebrie.com/posts/dynamodb-single-table/#graphql--single-table-design
* Spanner:
  * [YugabyteDB](https://docs.yugabyte.com/latest/comparisons/)
   
---
## Glossary 

* **Data mapper**: A [data mapper](https://www.martinfowler.com/eaaCatalog/dataMapper.html) is a design pattern or piece of software that maps programming data structures to those stored in a database. Data mappers attempt to synchronize changes between the two sources while keeping them independent of each other. The mapper itself is responsible for maintaining a working translation, freeing developers to iterate the application data structures without concern for the database representation.
* **Functions**: A [Functions](https://flink.apache.org/stateful-functions.html) ...
* **Injection attack**: An injection attack is an attack in which a malicious user attempts to execute unwanted database operations using specially crafted input in user-facing application fields. Often, this is used to retrieve data that should not be accessible or to delete or mangle information in the database.
* **ORM**: ORMs, or object-relational mappers, are abstraction layers that translate between the data representations used in relational databases and the representation in memory used with object-oriented programming. The ORM provides an object-oriented interface to data within the database, attempting to reduce the amount of code and use familiar archetypes to speed up development.
* **Object-relational impedance mismatch**: Object-relational impedance mismatch refers to the difficulty of translating between an object-oriented application and a relational database. Since the data structures vary significantly, it can be difficult to faithfully and performantly mutate and transcribe the programmatic data structures to the format used by the storage backend.
* **Patterns**: Design patterns are formalized [best practices](https://en.wikipedia.org/wiki/Software_design_pattern) that the programmer can use to solve common problems when designing an application or system;[Microservices](https://www.oreilly.com/content/why-a-pattern-language-for-microservices/)
* **Persistence framework**: A persistence framework is a middeware abstraction layer developed to bridge the gap between program data and databases. Persistence frameworks may also be ORMs if the abstraction they employ maps objects to relational entities.
* **Query builder**: A [query builder](https://softwareengineering.stackexchange.com/questions/138115/what-are-the-advantages-to-using-sql-query-builders) is an abstraction layer that helps developers access and control databases by providing a controlled interface which adds usability, safety, or flexibility features. Typically, query builders are relatively light-weight, focus on easing data access and data representation, and do not attempt to translate the data into a specific programming paradigm.
* **Serverless**: A [serverless](https://cloudstate.io) application is one that provides maximum business value over its application lifecycle and one that costs nothing to run when not used, excluding data storage costs.
* **SQL**: [SQL](https://en.wikipedia.org/wiki/SQL), or structured query language, is a domain-specific language developed for managing relational database management systems. It can be used to query, define, and manipulate data within a database as well as their organizational structures. SQL is ubiquitous among relational databases.
