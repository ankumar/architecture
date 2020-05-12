**Hard Parts**
1. **Boundaries Right**
2. **Distributed State Management**

**Use Cases:**
1. **Data Consisteny**
2. **Deleting Data, Ex: CCPA**

SandBox, Hipster Shop:
* [GCP](https://github.com/GoogleCloudPlatform/microservices-demo)
* [YugabyteDB](https://blog.yugabyte.com/cloud-native-meets-distributed-sql-bringing-microservices-kubernetes-istio-yugabytedb-together-with-hipster-shop-demo/)

----

1. Patterns: [Why?](https://www.oreilly.com/content/why-a-pattern-language-for-microservices/)
* [Microservice Architecture](https://microservices.io/patterns/microservices.html)
  * [Microservice, Why?](https://chrisrichardson.net/post/microservices/2020/02/18/why-microservices-part-1.html)
* [Monolithic Architecture](https://microservices.io/patterns/monolithic.html)
* [Distributed Data]()
  * [Saga](https://microservices.io/patterns/data/saga.html)
    * [Using Sagas](https://chrisrichardson.net/post/microservices/2019/07/09/developing-sagas-part-1.html)
  * [CQRS](https://microservices.io/patterns/data/cqrs.html)
  * [API Composition](https://microservices.io/patterns/data/api-composition.html)
  * [Delete](https://blog.twitter.com/engineering/en_us/topics/infrastructure/2020/deleting-data-distributed-throughout-your-microservices-architecture.html) 
* Dynamo:
  * Single Table Design - https://www.alexdebrie.com/posts/dynamodb-single-table/
  * GraphQL/Multi Table - https://www.alexdebrie.com/posts/dynamodb-single-table/#graphql--single-table-design
* [Functions](https://flink.apache.org/stateful-functions.html)
* [Serverless](https://cloudstate.io)



2. DBaaS: **Purpose-built Databases** - "It wasn't that long ago when the DBAs owned THE shared database. Nowadays, in all kinds of companies, no one blinks an eyelid when every service has its own database. The most unexpected things can change so quickly."

**Landscape** - IN-MEMORY, RELATIONAL, KEY VALUE, WIDE COLUMN, DOCUMENT, TIME-SERIES, LEDGER

* [Cassandra / Cloud Native](https://www.datastax.com/blog/2020/05/why-astra-good-cassandra)
* [YugabyteDB Comparisons](https://docs.yugabyte.com/latest/comparisons/)

