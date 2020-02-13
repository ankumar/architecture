# Modernization
## "If we have a system of improvement that’s directed at improving the parts taken separately, you can be absolutely sure that the performance of the whole will not be improved. The performance of a system depends on how the parts fit, not how they act taken separately.” -Dr. Russell Ackoff

## Architecture is about [Systems Thinking](https://www.youtube.com/watch?v=OqEeIG8aPPk) including People, Process and Technology; synthesis of multiple perspectives, including social dynamics, domain-driven design, business models, and software architecture. It's not about code, and it's not a synonym for "software architecture".
 
# Services
Decomposing an Application into Services; designing Modularity & Interfaces

A popular pattern https://microservices.io/ enables rapid, frequent and reliable delivery of large, complex applications. It also enables an organization to evolve its technology stack.

[Microservices](https://www.youtube.com/watch?v=wgdBVIX9ifA) - also known as the microservice architecture - is an architectural style that structures an application as a collection of services that are
1. Highly maintainable & testable
2. Loosely coupled
3. Independently deployable
4. Organized around business capabilities
5. Owned by a small team

Related:
* [Historical Context & Shifts](https://slidr.io/kameshsampath/sail-smoothly-in-the-cloud-an-introduction-to-istio#1)
* [Modular Monoliths](https://www.youtube.com/watch?v=5OjqD-ow8GE)
* [Service Mesh](https://www.datawire.io/envoyproxy/service-mesh/)
* [Query Language for API](https://graphql.org/)

# Data
## Learning Systems
* [Reinforcement Learning](https://diyrobocars.com/)

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

# [Cloud Computing](https://nvlpubs.nist.gov/nistpubs/Legacy/SP/nistspecialpublication800-145.pdf) - Make Developers more productive

| | |
|------------------------| ---------------------------------------------------------------------------------------------|
| On-demand self-service | A consumer can unilaterally provision computing capabilities, such as server time and network storage, as needed automatically without requiring human interaction |
|Broad network access|Capabilities are available over the network and accessed through standard mechanisms|
|Resource pooling|The provider’s computing resources are pooled to serve multiple consumers using a multi-tenant model, with different physical and virtual resources dynamically|
|Rapid elasticity|Capabilities can be elastically provisioned and released to scale rapidly outward and inward with demand|
|Measured service|Cloud systems automatically control and optimize resource use by leveraging a metering capability (typically per-per-use)|


## Cloud Native Services

* [Cloud Run](https://cloud.google.com/run/)
* [Kafka Cloud Native](https://www.confluent.io/blog/introducing-cloud-native-experience-for-apache-kafka-in-confluent-cloud)
* [Cassandra Cloud](https://constellation.datastax.com/)
* [Amazon Aurora cloud-native relational database](https://www.allthingsdistributed.com/2019/03/Amazon-Aurora-design-cloud-native-relational-database.html)
* [Socrates: The New SQL Server in the Cloud](https://www.microsoft.com/en-us/research/uploads/prod/2019/05/socrates.pdf)



