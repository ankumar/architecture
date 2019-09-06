## Well Architected

Architecture is about Systems Thinking including People, Process and Technology; synthesis of multiple perspectives, including social dynamics, domain-driven design, business models, and software architecture. It's not about code, and it's not a synonym for "software architecture".

Systems Thinking:
* [“If we have a system of improvement that’s directed at improving the parts taken separately, you can be absolutely sure that the performance of the whole will not be improved. The performance of a system depends on how the parts fit, not how they act taken separately.” -Dr. Russell Ackoff](https://www.youtube.com/watch?v=EbLh7rZ3rhU)
1. A system is a whole that is defined by its function(s) in one or more containing systems.
2. Every system contains at least two essential parts and these must satisfy three conditions.
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

* Frameworks
  * [The Twelve Factors](https://12factor.net/)
  * [AWS Well-Architected Framework](https://wa.aws.amazon.com/index.html)
* Visual
  * [Cloud Diagrams & Notes](https://www.awsgeek.com/)
* Tools
  * [The C4 model for visualising software architecture](https://c4model.com/)
  * [AWS Well-Architected Tool](https://aws.amazon.com/well-architected-tool/)
* Resources
  * [Technical Leadership Masterclass](https://www.slideshare.net/RufM/technical-leadership-decisions)
  * [Martin Fowler](https://martinfowler.com/)
  * [Resources for Software and Systems Architects](http://www.bredemeyer.com/)
  * [The Architect Elevator](https://architectelevator.com/)
  * [Azure Architecture Center](https://docs.microsoft.com/en-us/azure/architecture/)
* Anti-Architecture
  * A [big ball of mud](http://www.laputan.org/mud/) is a software system that lacks a perceivable architecture. Although undesirable from a software engineering point of view, such systems are common in practice due to business pressures, developer turnover and code entropy. They are a type of design anti-pattern.
 
## Microservices
Decomposing an Application into Services;designing Modularity & Interfaces

From https://microservices.io/
Microservices - also known as the microservice architecture - is an architectural style that structures an application as a collection of services that are
1. Highly maintainable & testable
2. Loosely coupled
3. Independently deployable
4. Organized around business capabilities
5. Owned by a small team

The microservice architecture enables the rapid, frequent and reliable delivery of large, complex applications. It also enables an organization to evolve its technology stack.

Related:
* [Historical Context & Shifts](https://slidr.io/kameshsampath/sail-smoothly-in-the-cloud-an-introduction-to-istio#1)
* [Modular Monoliths](https://www.youtube.com/watch?v=5OjqD-ow8GE)
* [Service Mesh](https://www.datawire.io/envoyproxy/service-mesh/)
* [Query Language for API](https://graphql.org/)

## Data Processing
Unified Model for Batch, Streaming & SQL 

* ["The Log”: Storage abstraction for ordered sequence of immutable data](https://engineering.linkedin.com/distributed-systems/log-what-every-software-engineer-should-know-about-real-time-datas-unifying)
* [Kafka](https://www.microsoft.com/en-us/research/wp-content/uploads/2017/09/Kafka.pdf)
* [BookKeeper](http://bookkeeper.apache.org/distributedlog/)
* [LogDevice](https://code.fb.com/core-data/logdevice-a-distributed-data-store-for-logs/)
* [Pravega](http://www.pravega.io/)

## Databases
Access Patterns, Entity Modeling, User interactions, Data Analysis, Analytics, Aggregations etc.

* [NoSQL, Relational, Document, Graph:A one size fits all database doesn't fit anyone](https://www.allthingsdistributed.com/2018/06/purpose-built-databases-in-aws.html)
* [NoSQL Historical Context](https://www.youtube.com/watch?v=qI_g07C_Q5I)
* [Cassandra](https://www.cs.cornell.edu/projects/ladis2009/papers/lakshman-ladis2009.pdf)
* [Amazon.com fits 90% of Retail workloads into DynamoDB](https://www.allthingsdistributed.com/2017/10/a-decade-of-dynamo.html)
  * [Advanced Design Patterns for Amazon DynamoDB](https://www.youtube.com/watch?v=jzeKPKpucS0)
  * [Amazon DynamoDB Deep Dive](https://www.youtube.com/watch?v=jzeKPKpucS0)
  * [Best Practices for DynamoDB](https://www.youtube.com/watch?v=HaEPXoXVf2k)
  * [Under the Hood](https://www.youtube.com/watch?v=yvBR71D0nAQ)
* [CosmosDB](https://azure.microsoft.com/en-us/blog/a-technical-overview-of-azure-cosmos-db/)
* [BigQuery](https://cloud.google.com/blog/products/gcp/inside-capacitor-bigquerys-next-generation-columnar-storage-format)
* [Presto](https://www.facebook.com/notes/facebook-engineering/presto-interacting-with-petabytes-of-data-at-facebook/10151786197628920/)
* [Snowflake](http://pages.cs.wisc.edu/~remzi/Classes/739/Spring2004/Papers/p215-dageville-snowflake.pdf)
* [Redshift](https://www.allthingsdistributed.com/2018/11/amazon-redshift-performance-optimization.html)
* [Athena](https://aws.amazon.com/athena/)

## Learning Systems
* [Robocars](https://diyrobocars.com/)

## Cloud
* [Kafka Cloud Native](https://www.confluent.io/blog/introducing-cloud-native-experience-for-apache-kafka-in-confluent-cloud)
* [Cassandra Cloud](https://constellation.datastax.com/)
* [Amazon Aurora cloud-native relational database](https://www.allthingsdistributed.com/2019/03/Amazon-Aurora-design-cloud-native-relational-database.html)
* [Socrates: The New SQL Server in the Cloud](https://www.microsoft.com/en-us/research/uploads/prod/2019/05/socrates.pdf)



