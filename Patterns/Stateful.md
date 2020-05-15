# “Stateful” ... 

An ontology of “stateful” systems ... 
* All systems are stateful. They only differ in the time it takes to restore state, when it was lost.
* All stateless systems are stateless in no more than 4 ways.
* All stateful systems are stateful in ... 21 possible ways?
  * With examples from Kafka (sticky partitioning), Cassandra (hinted handoffs).
* [A Paper - Locality, Statefulness, and Causality in Distributed Information Systems](https://arxiv.org/pdf/1909.09357.pdf)

![](https://github.com/ankumar/Architecture/blob/master/images/stateful.jpeg)

## Application Data
In a microservice architecture each service’s database is private to that service in order to ensure loose coupling. As a result, it’s challenging to implement transactions and queries that span services. The solution is to implement distributed transactions using the [Saga pattern and queries using the CQRS pattern](https://microservices.io/articles/applying.html).

**1. Data modeling** - typically needs to happen on (at least) two levels:

* On the **database** level
* On the **application** level (i.e., in your programming language)

The way how the application models are represented on both levels might differ due to a few reasons:

* Databases and programming languages use different data types
* Relations are represented differently in a database than in a programming language
* Databases typically have more powerful data modeling capabilities, like indexes, cascading deletes, or a variety of additional constraints (e.g. unique, not null, ...)
* Databases and programming languages have different technical constraints
    
**2. Data Access patterns** - Mapping between application & database structures. The two major categories are the [active record pattern](http://calpaterson.com/activerecord.html) and the data mapper pattern. The Data model comprises of

1. Collection of application domain models like Customer, Order, Item, ...
2. Schema of the underlying database like in 
* Relational databases (like PostgreSQL), they are stored in tables.
* Document databases (like MongoDB), they are stored in collections.
* Big Table databases (like Cassandra), Keyspace is an object that holds together all column families (or tables) of a design.

## Distributed Data Management 

An example for Booking Travel ... 

**Begin transaction**
    
    Start book hotel request
    
    End book hotel request
    
    Start book flight request
    
    End book flight request
    
    Start book car rental request
    
    End book car rental request
**End transaction**

**1. Kafka** - </>

**2. Data Consistency**
  * [Using Sagas](https://chrisrichardson.net/post/microservices/2019/07/09/developing-sagas-part-1.html)
  * Implementations:
    * https://eventuate.io/docs/manual/eventuate-tram/latest/getting-started-eventuate-tram-sagas.html
    * https://github.com/berndruecker/trip-booking-saga-java
    * https://github.com/eclipse/microprofile-lra

**3. Deleting Data** - (Ex: CCPA) Cross cutting concerns, Data Catalog of Online microservices & Offline Warehouses;Data Discoverability, Access & Processing;Abstraction ... 
  * [Twitter Use-case](https://blog.twitter.com/engineering/en_us/topics/infrastructure/2020/deleting-data-distributed-throughout-your-microservices-architecture.html) 

## DBaaS - Purpose-built Databases

**SQL & NoSQL** - IN-MEMORY, RELATIONAL, KEY VALUE, WIDE COLUMN, DOCUMENT, TIME-SERIES, LEDGER

**"It wasn't that long ago when the DBAs owned THE shared database. Nowadays, in all kinds of companies, no one blinks an eyelid when every service has its own database. The most unexpected things can change so quickly."**

* [CosmosDB](https://docs.microsoft.com/en-us/azure/cosmos-db/consistency-levels)
* [Big Table](https://www.cs.rutgers.edu/~pxk/417/notes/content/bigtable.html): "Containers" like keyspace is the top-level database object that controls the replication for the object it contains at each datacenter in the cluster. Keyspaces contain tables, materialized views and user-defined types, functions and aggregates. Typically, a cluster has one keyspace per application. Since replication is controlled on a per-keyspace basis, store data with different replication requirements (at the same datacenter) in different keyspaces. Keyspaces are not a significant map layer within the data model.
  1. [Cassandra](https://www.datastax.com/blog/2020/05/why-astra-good-cassandra)
  2. [ScyllaDB](https://www.scylladb.com/2020/05/07/introducing-scylla-open-source-4-0/)
  3. [DynamoDB](https://aws.amazon.com/dynamodb/)
    * Single Table Design - https://www.alexdebrie.com/posts/dynamodb-single-table/
    * GraphQL/Multi Table - https://www.alexdebrie.com/posts/dynamodb-single-table/#graphql--single-table-design  
  
* Spanner:
  * [CockroachDB](https://www.cockroachlabs.com/docs/stable/architecture/overview.html)
  * [YugabyteDB](https://docs.yugabyte.com/latest/comparisons/)
   
