# System:
**1. A system is a whole that is defined by its function(s) in one or more containing systems.** <br>
**2. Every system contains at least two essential parts and these must satisfy three conditions.**
  * Every essential part of a system can affect its behavior or properties.
  * The way an essential part affects the properties or behavior of the whole depends on the
   state or activity of at least one other part of the system.
  * Groups of essential parts, subsystems, also can affect the behavior and properties of the whole system and none has an independent effect on it.

Some important properties of a system derive from its definition.
  * When a system is taken apart it loses its essential properties.
  * No part of a system can carry out the function that defines the system.
  * When a system is taken apart its essential parts lose their ability to carry out the
   function they have in the whole.

Finally: When the performance of any essential part of a system, taken separately, is improved, the performance of the whole may not be.

# Leadership:
* [Technical Leadership Masterclass](https://ruthmalan.com/Journal/2019/20190629SlideDocTechnicalLeadershipDecisions.pdf)

# Enterprise Architecture:
* [Cell Based Architecture - Inspired by Biology](https://github.com/wso2/reference-architecture/blob/master/reference-architecture-cell-based.md)

# Patterns:
* [Microservices](https://microservices.io/patterns/index.html)
* [The Twelve Factors](https://12factor.net/)
* [Martin Fowler](https://martinfowler.com/)
* [Resources for Software and Systems Architects](http://www.bredemeyer.com/)
* [The Architect Elevator](https://architectelevator.com/)
* [Azure Architecture Center](https://docs.microsoft.com/en-us/azure/architecture/)
* [Amazon Builders Library](https://aws.amazon.com/builders-library/)
* [AWS Well-Architected Framework](https://wa.aws.amazon.com/index.en.html)
* [Historical Context & Shifts](https://slidr.io/kameshsampath/sail-smoothly-in-the-cloud-an-introduction-to-istio#1)
* [Modular Monoliths](https://www.youtube.com/watch?v=5OjqD-ow8GE)
* [Service Mesh](https://www.datawire.io/envoyproxy/service-mesh/)
* [Query Language for API](https://graphql.org/)
* [Fin Tech](https://github.com/ankumar/Architecture/blob/master/Patterns/Monzo.md)

# Data-Intensive:

## Data Processing
Unified Model for Batch, Streaming & SQL 

* ["The Log”: Storage abstraction for ordered sequence of immutable data](https://engineering.linkedin.com/distributed-systems/log-what-every-software-engineer-should-know-about-real-time-datas-unifying)
  * [Kafka](https://www.microsoft.com/en-us/research/wp-content/uploads/2017/09/Kafka.pdf)
  * [BookKeeper](http://bookkeeper.apache.org/distributedlog/)
  * [LogDevice](https://code.fb.com/core-data/logdevice-a-distributed-data-store-for-logs/)
  * [Pravega](http://www.pravega.io/)

## Databases
Access Patterns, Data Modeling, User interactions, Data Analysis, Analytics, Aggregations etc.

* [Relational,NoSQL,Document,Graph:A one size fits all database doesn't fit anyone](https://www.allthingsdistributed.com/2018/06/purpose-built-databases-in-aws.html)

* [NoSQL](https://www.youtube.com/watch?v=qI_g07C_Q5I)
  * [Cassandra](https://www.cs.cornell.edu/projects/ladis2009/papers/lakshman-ladis2009.pdf)
  * [CosmosDB](https://azure.microsoft.com/en-us/blog/a-technical-overview-of-azure-cosmos-db/)
  * [Amazon.com fits 90% of Retail workloads into DynamoDB](https://www.allthingsdistributed.com/2017/10/a-decade-of-dynamo.html)
    * [Advanced Design Patterns for Amazon DynamoDB](https://www.youtube.com/watch?v=jzeKPKpucS0)
    * [Amazon DynamoDB Deep Dive](https://www.youtube.com/watch?v=jzeKPKpucS0)
    * [Best Practices for DynamoDB](https://www.youtube.com/watch?v=HaEPXoXVf2k)
    * [Under the Hood](https://www.youtube.com/watch?v=yvBR71D0nAQ)

* [Data Warehouse](https://www.wiley.com/en-us/Building+the+Data+Warehouse%2C+4th+Edition-p-9780764599446)
  * [Presto processes hundreds of petabytes of data and quadrillions of rows per day at Facebook](https://www.facebook.com/notes/facebook-engineering/presto-interacting-with-petabytes-of-data-at-facebook/10151786197628920/)
    * https://prestosql.io/paper.html
  * [BigQuery](https://cloud.google.com/blog/products/gcp/inside-capacitor-bigquerys-next-generation-columnar-storage-format)
  * [Snowflake](http://pages.cs.wisc.edu/~remzi/Classes/739/Spring2004/Papers/p215-dageville-snowflake.pdf)
  * [Athena](https://aws.amazon.com/athena/)
  * [Redshift](https://www.allthingsdistributed.com/2018/11/amazon-redshift-performance-optimization.html)

## AI
* [Reinforcement Learning](https://diyrobocars.com/)

# Cloud Computing:
* [Open Application Model](https://oam.dev/)
* [Decouple developers from operations](https://www.youtube.com/watch?v=do-PrVi0ifk)
* [Cloud Run](https://cloud.google.com/run/)
* [Kafka Cloud Native](https://www.confluent.io/blog/introducing-cloud-native-experience-for-apache-kafka-in-confluent-cloud)
* [Cassandra Cloud](https://constellation.datastax.com/)
* [Amazon Aurora cloud-native relational database](https://www.allthingsdistributed.com/2019/03/Amazon-Aurora-design-cloud-native-relational-database.html)
* [Socrates: The New SQL Server in the Cloud](https://www.microsoft.com/en-us/research/uploads/prod/2019/05/socrates.pdf)

## Operational
* [If everyone is responsible for success, why not failure? Root cause analysis exists to find blame](https://www.verica.io/inhumanity-of-root-cause-analysis/)

# Anti-Architecture:
* A [big ball of mud](http://www.laputan.org/mud/) is a software system that lacks a perceivable architecture. Although undesirable from a software engineering point of view, such systems are common in practice due to business pressures, developer turnover and code entropy. They are a type of design anti-pattern.
