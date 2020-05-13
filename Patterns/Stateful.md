# Services, Hard Parts

1. Apps
2. Distributed Data Management
3. Purpose-built Databases

## Apps
1. Getting Boundaries Right
* [Patterns, Why?](https://en.wikipedia.org/wiki/Software_design_pattern)
    * https://www.oreilly.com/content/why-a-pattern-language-for-microservices/
 
  * [Microservice Architecture](https://microservices.io/patterns/microservices.html)
    * [Microservice, Why?](https://chrisrichardson.net/post/microservices/2020/02/18/why-microservices-part-1.html)
  * [Monolithic Architecture](https://microservices.io/patterns/monolithic.html)
* Access patterns - Mapping  between application & database structures. The two major categories are the [active record pattern](http://calpaterson.com/activerecord.html) and the data mapper (ORMs & [DTOs](https://martinfowler.com/eaaCatalog/dataTransferObject.html)) pattern. 

* APIs  
  * [Functions](https://flink.apache.org/stateful-functions.html)
  * [Serverless](https://cloudstate.io)
  
## Distributed Data Management
Data Consistency & Deleting Data, Ex: CCPA
* [Saga](https://microservices.io/patterns/data/saga.html)
  * [Using Sagas](https://chrisrichardson.net/post/microservices/2019/07/09/developing-sagas-part-1.html)
* [CQRS](https://microservices.io/patterns/data/cqrs.html)
* [API Composition](https://microservices.io/patterns/data/api-composition.html)
* [Delete Data](https://blog.twitter.com/engineering/en_us/topics/infrastructure/2020/deleting-data-distributed-throughout-your-microservices-architecture.html) 

## DBaaS 

"It wasn't that long ago when the DBAs owned THE shared database. Nowadays, in all kinds of companies, no one blinks an eyelid when every service has its own database. The most unexpected things can change so quickly."

**Landscape** - IN-MEMORY, RELATIONAL, KEY VALUE, WIDE COLUMN, DOCUMENT, TIME-SERIES, LEDGER

* [Cassandra / Cloud Native](https://www.datastax.com/blog/2020/05/why-astra-good-cassandra)
* [YugabyteDB Comparisons](https://docs.yugabyte.com/latest/comparisons/)
* Dynamo:
  * Single Table Design - https://www.alexdebrie.com/posts/dynamodb-single-table/
  * GraphQL/Multi Table - https://www.alexdebrie.com/posts/dynamodb-single-table/#graphql--single-table-design

