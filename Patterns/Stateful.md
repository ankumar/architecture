# Services, Hard Parts

1. Apps - **Getting Boundaries Right**
2. Distributed Data Management - **Data Consistency & Deleting Data, Ex: CCPA**
3. Purpose-built Databases - **SQL & NoSQL**

## Apps
* [Patterns, Why?](https://en.wikipedia.org/wiki/Software_design_pattern)
  * [Microservice, Why?](https://chrisrichardson.net/post/microservices/2020/02/18/why-microservices-part-1.html)
    * [Pattern for Microservices](https://www.oreilly.com/content/why-a-pattern-language-for-microservices/)
    * [Microservice Architecture](https://microservices.io/patterns/microservices.html)
  
* APIs - REST, GraphQL or gRPC or anything else 
  * [DTOs](https://martinfowler.com/eaaCatalog/dataTransferObject.html)

* Data Access patterns - Mapping between application & database structures. The two major categories are the [active record pattern](http://calpaterson.com/activerecord.html) and the data mapper pattern.
  
## Distributed Data Management
* [Using Sagas](https://chrisrichardson.net/post/microservices/2019/07/09/developing-sagas-part-1.html)
* CorssCommon Abstraction, Data catalog Online microservices & Offline Warehouses, Data discoverability, Access, Processing, 
  * [Delete Data](https://blog.twitter.com/engineering/en_us/topics/infrastructure/2020/deleting-data-distributed-throughout-your-microservices-architecture.html) 

## DBaaS 

"It wasn't that long ago when the DBAs owned THE shared database. Nowadays, in all kinds of companies, no one blinks an eyelid when every service has its own database. The most unexpected things can change so quickly."

**Landscape** - IN-MEMORY, RELATIONAL, KEY VALUE, WIDE COLUMN, DOCUMENT, TIME-SERIES, LEDGER

* [Cassandra / Cloud Native](https://www.datastax.com/blog/2020/05/why-astra-good-cassandra)
* [YugabyteDB Comparisons](https://docs.yugabyte.com/latest/comparisons/)
* Dynamo:
  * Single Table Design - https://www.alexdebrie.com/posts/dynamodb-single-table/
  * GraphQL/Multi Table - https://www.alexdebrie.com/posts/dynamodb-single-table/#graphql--single-table-design

---
## Glossary 

* **Data mapper**: A [data mapper](https://www.martinfowler.com/eaaCatalog/dataMapper.html) is a design pattern or piece of software that maps programming data structures to those stored in a database. Data mappers attempt to synchronize changes between the two sources while keeping them independent of each other. The mapper itself is responsible for maintaining a working translation, freeing developers to iterate the application data structures without concern for the database representation.
* **Functions**: A [Functions](https://flink.apache.org/stateful-functions.html) ...
* **Injection attack**: An injection attack is an attack in which a malicious user attempts to execute unwanted database operations using specially crafted input in user-facing application fields. Often, this is used to retrieve data that should not be accessible or to delete or mangle information in the database.
* **ORM**: ORMs, or object-relational mappers, are abstraction layers that translate between the data representations used in relational databases and the representation in memory used with object-oriented programming. The ORM provides an object-oriented interface to data within the database, attempting to reduce the amount of code and use familiar archetypes to speed up development.
* **Object-relational impedance mismatch**: Object-relational impedance mismatch refers to the difficulty of translating between an object-oriented application and a relational database. Since the data structures vary significantly, it can be difficult to faithfully and performantly mutate and transcribe the programmatic data structures to the format used by the storage backend.
* **Persistence framework**: A persistence framework is a middeware abstraction layer developed to bridge the gap between program data and databases. Persistence frameworks may also be ORMs if the abstraction they employ maps objects to relational entities.
* **Query builder**: A [query builder](https://softwareengineering.stackexchange.com/questions/138115/what-are-the-advantages-to-using-sql-query-builders) is an abstraction layer that helps developers access and control databases by providing a controlled interface which adds usability, safety, or flexibility features. Typically, query builders are relatively light-weight, focus on easing data access and data representation, and do not attempt to translate the data into a specific programming paradigm.
* **Serverless**: A [serverless](https://cloudstate.io) application is one that provides maximum business value over its application lifecycle and one that costs nothing to run when not used, excluding data storage costs.
* **SQL**: [SQL](https://en.wikipedia.org/wiki/SQL), or structured query language, is a domain-specific language developed for managing relational database management systems. It can be used to query, define, and manipulate data within a database as well as their organizational structures. SQL is ubiquitous among relational databases.
