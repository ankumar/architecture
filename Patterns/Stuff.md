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

**Finally: When the performance of any essential part of a system, taken separately, is improved, the performance of the whole may not be.**

# Enterprise Architecture:
**"Application developers are successful when their work IS noticed. Platform developers are successful when their work is NOT noticed."**<br>
Good perspective! When done well, Platforms drive: <br>
1. Speed for Devs  &  Stability/Scalability/Security for Ops.<br>
2. Combining for a Win-Win! <br>

![http://www.melconway.com/Home/Conways_Law.html](https://github.com/ankumar/Architecture/blob/master/images/Conways%20Law.png)
* [Inspired by Biology - Cell Based Architecture](https://github.com/wso2/reference-architecture/blob/master/reference-architecture-cell-based.md)
* [DevOps Transformation](https://github.com/ankumar/Architecture/blob/master/Patterns/The%20Unicorn%20Project.md)

# Leadership:
* [Technical Leadership Masterclass](https://ruthmalan.com/Journal/2019/20190629SlideDocTechnicalLeadershipDecisions.pdf)

# Developer Experience:
![Developers Developers Developers ...](https://github.com/ankumar/Architecture/blob/master/images/Github.png)<p align="center"> <b>Github - 40 million Developers</b> </p>
   * [GitHub Actions](https://github.com/features/actions)
     * [Compute: GCE, GKE, CLOUD RUN](https://github.com/GoogleCloudPlatform/github-actions)
   * [Cloud Run](https://cloud.google.com/run/)

# Patterns:
* [Microservices](https://microservices.io/patterns/index.html)
* [Assembling Software from Independent Systems](https://scs-architecture.org/)
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
Data is an important starting point, for data to be useful, it should be turned to Information.
Data - Raw, unorganized facts about something
Information - Data/Facts that is structured, organized, and presented with context
Knowledge - Understanding of Information with experience and intuition
For data to be useful, every company must be able to turn data into information, and eventually into knowledge. Knowledge empowers understanding and decisions.
What are the factors that is driving data today?
1. Accessibility to scalable infra and platform
2. Awareness of importance of data
3. Machine Learning on the rise
4. Modeling physical world in real-time
What is the problem with data today?

**Problem #1 - Spending the time on wrong things**
![](https://github.com/ankumar/Architecture/blob/master/images/data-intensive1.png)

**Problem #2 - Data is not designed and collected systematically**

**Problem #3 - Companies have lots of data but not information**

**Problem #4 - Data and data assets are not discoverable**

**Problem #5 - Tools are not addressing complexity**

**Problem #6 - It is not tools and technology but people and processes**

## Science
* Data quality
  * [Data Validation for ML](https://mlsys.org/Conferences/2019/doc/2019/167.pdf)
* Architecture
  * [Reinforcement Learning](https://diyrobocars.com/)
* Publications
  * [On the Measure of Intelligence](https://arxiv.org/abs/1911.01547)
  * [Amazon](https://www.amazon.science/publications)
  * [A 10-year Prediction for Enterprise-Grade ML](http://cidrdb.org/cidr2020/papers/p8-agrawal-cidr20.pdf)
 
  
## Data Processing
**Unified Model for Batch, Streaming & SQL?**

* [The Evolution of Massive-Scale Data Processing](https://goo.gl/VlVAEp)
* [One SQL to Rule Them All](https://arxiv.org/pdf/1905.12133.pdf)
* ["The Log”: Storage abstraction for ordered sequence of immutable data](https://engineering.linkedin.com/distributed-systems/log-what-every-software-engineer-should-know-about-real-time-datas-unifying)
  * [BookKeeper](http://bookkeeper.apache.org/distributedlog/)
  * [LogDevice](https://code.fb.com/core-data/logdevice-a-distributed-data-store-for-logs/)
  * [Pravega](http://www.pravega.io/)
* [Kafka](https://www.microsoft.com/en-us/research/wp-content/uploads/2017/09/Kafka.pdf)
  * API Compatible
    * [Event Hubs](https://azure.microsoft.com/en-us/services/event-hubs/)
    * [Redpanda](https://vectorized.io/)

## Databases
**Access Patterns, Data Modeling, User interactions, Data Analysis, Analytics, Aggregations etc.**

* [DB's Ranking](https://db-engines.com/en/ranking)
* [Relational,NoSQL,Document,Graph:A one size fits all database doesn't fit anyone](https://www.allthingsdistributed.com/2018/06/purpose-built-databases-in-aws.html)

* [NoSQL](https://www.youtube.com/watch?v=qI_g07C_Q5I)
  * Dynamo
    * [Amazon.com fits 90% of Retail workloads into DynamoDB](https://www.allthingsdistributed.com/2017/10/a-decade-of-dynamo.html)
    * [Relational DB to single table](https://www.trek10.com/blog/dynamodb-single-table-relational-modeling/) 
    * Talks worth watching & still learn something new every time...
      * [Deep Dive](https://www.youtube.com/watch?v=6yqfmXiZTlM)
      * [Match Your Workload to the Right Database](https://www.youtube.com/watch?v=hwnNbLXN4vA)
      * [Under the Hood](https://www.youtube.com/watch?v=yvBR71D0nAQ)
      * [Advanced Design Patterns - 2018](https://www.youtube.com/watch?v=HaEPXoXVf2k)
      * [Advanced Design Patterns - 2017](https://www.youtube.com/watch?v=jzeKPKpucS0)
  
  * [Cassandra](https://www.cs.cornell.edu/projects/ladis2009/papers/lakshman-ladis2009.pdf)
    * API Compatible
      * [Syclla](https://www.scylladb.com/)
  * [CosmosDB](https://azure.microsoft.com/en-us/blog/a-technical-overview-of-azure-cosmos-db/)
* [Data Warehouse](https://www.wiley.com/en-us/Building+the+Data+Warehouse%2C+4th+Edition-p-9780764599446)
  * [Presto processes hundreds of petabytes of data and quadrillions of rows per day at Facebook](https://www.facebook.com/notes/facebook-engineering/presto-interacting-with-petabytes-of-data-at-facebook/10151786197628920/)
    * https://prestosql.io/paper.html
  * [BigQuery](https://cloud.google.com/blog/products/gcp/inside-capacitor-bigquerys-next-generation-columnar-storage-format)
  * [Snowflake](http://pages.cs.wisc.edu/~remzi/Classes/739/Spring2004/Papers/p215-dageville-snowflake.pdf)
  * [Athena](https://aws.amazon.com/athena/)
  * [Redshift](https://www.allthingsdistributed.com/2018/11/amazon-redshift-performance-optimization.html)

# Distributed computing:

[![Service Mesh](https://github.com/ankumar/Architecture/blob/master/images/Istio2.png)](https://www.youtube.com/watch?v=do-PrVi0ifk "Eric Brewer, VP Infrastructure & Google Fellow")<p align="center">
 <b>Connecting in & across data centers  - Google: 100,000+ services</b></p>

# Cloud Computing:

![](https://github.com/ankumar/Architecture/blob/master/images/Werner.png)

* [A Brief History](https://docs.google.com/presentation/d/1BoxFeENJcINgHbKfygXpXROchiRO2LBT-pzdaOFr4Zg/edit#slide=id.g39c264972c_182_1000)
* [Standards](https://docs.google.com/presentation/d/1wc9nJSyfjrUO2KpVgXt5KnSHVlWvXpho6eINkin5U5g/edit#slide=id.g12bfb019f3_2_34)
* [Open Application Model](https://oam.dev/)
* [Decouple developers from operations](https://www.youtube.com/watch?v=do-PrVi0ifk)
* [Kafka Cloud Native](https://www.confluent.io/blog/introducing-cloud-native-experience-for-apache-kafka-in-confluent-cloud)
* [Cassandra Cloud](https://constellation.datastax.com/)
* [Amazon Aurora cloud-native relational database](https://www.allthingsdistributed.com/2019/03/Amazon-Aurora-design-cloud-native-relational-database.html)
* [Socrates: The New SQL Server in the Cloud](https://www.microsoft.com/en-us/research/uploads/prod/2019/05/socrates.pdf)
 
# Operational:
[![](https://github.com/ankumar/Architecture/blob/master/images/Above%20The%20Line.png)](https://www.youtube.com/embed/8bxj-FLEi10 "")
<p align="center"><b>Above & Below The Line - "A Model, Broad, proactive learning keeps pace with change, continually recharging the sources of adaptive capacity that lead to resilient performance.”</b></p>

* [Observability](https://www.honeycomb.io/)
* [RCA - If everyone is responsible for success, why not failure? Root cause analysis exists to find blame](https://www.verica.io/inhumanity-of-root-cause-analysis/)
* [Incidents](https://www.adaptivecapacitylabs.com/blog/)
* [Human Performance in Software](https://queue.acm.org/detail.cfm?id=3380776)

# Anti-Architecture:
* A [big ball of mud](http://www.laputan.org/mud/) is a software system that lacks a perceivable architecture. Although undesirable from a software engineering point of view, such systems are common in practice due to business pressures, developer turnover and code entropy. They are a type of design anti-pattern.
