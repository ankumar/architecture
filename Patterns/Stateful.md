# Services, Hard Parts

1. Apps - **Getting Boundaries Right**
2. Distributed Data Management - **Data Consistency & Deleting Data, Ex: CCPA**
3. Purpose-built Databases - **SQL & NoSQL**

## Apps
[Microservice, Why?](https://chrisrichardson.net/post/microservices/2020/02/18/why-microservices-part-1.html)
  * [Microservice Architecture](https://microservices.io/patterns/microservices.html)
  
APIs - REST, GraphQL or gRPC or anything else 
  
Data Access patterns - Mapping between application & database structures. The two major categories are the [active record pattern](http://calpaterson.com/activerecord.html) and the data mapper pattern.

The Data model comprises of
1. Collection of Domain models like Customer, Order & Item 
2. Schema of the underlying database like Tables/Columns
  
## Distributed Data Management
Data Consistency
  * [Using Sagas](https://chrisrichardson.net/post/microservices/2019/07/09/developing-sagas-part-1.html)

Deleting Data - Cross cutting concerns, Data Catalog of Online microservices & Offline Warehouses;Data Discoverability, Access & Processing;Abstraction ... 
  * [Twitter Use-case](https://blog.twitter.com/engineering/en_us/topics/infrastructure/2020/deleting-data-distributed-throughout-your-microservices-architecture.html) 

## Streaming aaS 



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

https://github.com/ankumar/Architecture/blob/master/Patterns/Terminology.md
