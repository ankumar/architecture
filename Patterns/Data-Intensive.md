# Data-Intensive: 
Data powers new innovations, improvements in customer experience, and efficiency. Small advantage in data and algorithms result in increased customers/business success which in turn results in more data. This virtuous cycle due to positive feedback loop amplifies a company's competitive advantage, making data one of the key ingredients in building companies that have Increasing Returns instead of commonly seen Decreasing Returns.

<p align="center"> <img src="https://miro.medium.com/max/1372/1*zOp70MCQ-uhaS7lUVAhATA.png"> </p>
<p align="center"> <a href="https://www.itsonlyamodel.com/">"All models are wrong, but some are useful."</a> </p>

### Advances in machine learning (ML) over the last decade have opened up a radically new approach to building software systems. Termed [“Software 2.0”](https://medium.com/@karpathy/software-2-0-a64152b37c35), this approach focuses on training models to learn from data instead of explicitly writing code for the required behavior.
## > a. Data Validation
<p align="center"> <b> "In traditional software engineering, or Software 1.0, a program’s functionality is defined via code as dictated by a human. In the age of machine learning, we are increasingly observing Software 2.0 systems, where a program’s functionality is defined by the weights of neural networks as dictated by the data. You wouldn’t trust a piece of human-written code that hasn’t ever been debugged or tested, so why shouldn’t our data receive the same treatment now that it’s a first-class citizen in so many real-world systems?"

Data Quality problem categories:
- Data creation
- Data labelling
- Data manipulation
- Data quality evaluation 

**Examples:**
* [AI for Full-Self Driving - Data for STOP sign detection](https://www.youtube.com/watch?v=hx7BXih7zx8)

## > b. Software Engineering Practices
![](../images/Hidden%20Technical%20Debt%20in%20ML%20Systems.png)
### <p align="center"> [Hidden Technical Debt in Machine Learning Systems](https://papers.nips.cc/paper/5656-hidden-technical-debt-in-machine-learning-systems.pdf) </p>
   

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

![https://www.datacouncil.ai/](../images/Data%20Council.png)
<p align="center"> <a href="https://www.datacouncil.ai/"> <b> Data Council </b> </p>
 
## Data Science
* Data quality
  * [Data Validation for ML](https://mlsys.org/Conferences/2019/doc/2019/167.pdf)
* Architecture
  * [Reinforcement Learning](https://diyrobocars.com/)
  * [AI-powered Monopolies and the New World Order](https://towardsdatascience.com/ai-powered-monopolies-and-the-new-world-order-1c56cfc76e7d)
  * [ML development is harder than traditional software development;Production ML is Even Harder](https://www.slideshare.net/matei/scaling-up-machine-learning-development)
  * [Organize, Manage, and Deploy your company’s ML model portfolio](https://algorithmia.com/enterprise)
  * [GitHub Source Code Management for Algorithms](https://algorithmia.com/blog/introducing-github-source-code-management-for-algorithmia)
  * [Data catalog & Visualization](https://datarow.com/)
  
* Publications
  * [On the Measure of Intelligence](https://arxiv.org/abs/1911.01547)
  * [Amazon](https://www.amazon.science/publications)
  * [A 10-year Prediction for Enterprise-Grade ML](http://cidrdb.org/cidr2020/papers/p8-agrawal-cidr20.pdf)
  * [The High Interest Credit Card of Technical Debt - ML systems are particularly susceptible to new and interesting forms of tech debt](https://storage.googleapis.com/pub-tools-public-publication-data/pdf/43146.pdf)
   
## Data Processing
**Unified Model for Batch, Streaming & SQL?**

* [The Evolution of Massive-Scale Data Processing](https://goo.gl/VlVAEp)
* [One SQL to Rule Them All](https://arxiv.org/pdf/1905.12133.pdf)
* ["The Log”: Storage abstraction for ordered sequence of immutable data](https://engineering.linkedin.com/distributed-systems/log-what-every-software-engineer-should-know-about-real-time-datas-unifying)
  * [BookKeeper](http://bookkeeper.apache.org/distributedlog/)
  * [LogDevice](https://code.fb.com/core-data/logdevice-a-distributed-data-store-for-logs/)
  * [Pravega](http://www.pravega.io/)
  * [Scalog](https://www.usenix.org/conference/nsdi20/presentation/ding)
* [Kafka](https://www.microsoft.com/en-us/research/wp-content/uploads/2017/09/Kafka.pdf)
  * API Compatible:
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
    * [Single Table Design](https://www.alexdebrie.com/posts/dynamodb-single-table/)
    * Talks worth watching & still learn something new every time...
      * [Deep Dive](https://www.youtube.com/watch?v=6yqfmXiZTlM)
      * [Match Your Workload to the Right Database](https://www.youtube.com/watch?v=hwnNbLXN4vA)
      * [Under the Hood - Watch this & learn how DynamoDB works!](https://www.youtube.com/watch?v=yvBR71D0nAQ)
      * [Advanced Design Patterns - 2018](https://www.youtube.com/watch?v=HaEPXoXVf2k)
      * [Advanced Design Patterns - 2017](https://www.youtube.com/watch?v=jzeKPKpucS0)
  
  * [Cassandra](https://www.cs.cornell.edu/projects/ladis2009/papers/lakshman-ladis2009.pdf)
    * API Compatible
      * [Syclla](https://www.scylladb.com/)
  * [CosmosDB](https://azure.microsoft.com/en-us/blog/a-technical-overview-of-azure-cosmos-db/)
* [Data Warehouse](https://www.wiley.com/en-us/Building+the+Data+Warehouse%2C+4th+Edition-p-9780764599446)
  * [BigQuery](https://cloud.google.com/blog/products/gcp/inside-capacitor-bigquerys-next-generation-columnar-storage-format)
  * [Snowflake](http://pages.cs.wisc.edu/~remzi/Classes/739/Spring2004/Papers/p215-dageville-snowflake.pdf)
    * https://www.infoq.com/presentations/snowflake-architecture/
  * [Athena](https://aws.amazon.com/athena/)
  * [Redshift](https://www.allthingsdistributed.com/2018/11/amazon-redshift-performance-optimization.html)
  * [Presto processes hundreds of petabytes of data and quadrillions of rows per day at Facebook](https://www.facebook.com/notes/facebook-engineering/presto-interacting-with-petabytes-of-data-at-facebook/10151786197628920/)
    * https://prestosql.io/paper.html
