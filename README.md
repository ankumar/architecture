# Platform & Applications

![](https://github.com/ankumar/Architecture/blob/master/images/Werner.png)
> New patterns of Builders front and center - [1. An Application Development, Execution Platform for the Rest of Us - Mel Conway](https://twitter.com/conways_law/status/1238539198203822081) / [2. Holistic approach - Dark](https://medium.com/darklang/the-design-of-dark-59f5d38e52d2) / [3. Write nothing; Deploy nowhere! - Nocode](https://twitter.com/kelseyhightower/status/961026365146320896) / 

## 1. Measurements
### > Time To Value
## 2. Platform is a perspective, Serving our customers
### > "Platform” with a standardized interface allowing decentralized development.
### > Programs built with it are “continually valid and observable from the very beginning of its construction”.
## 3. Value Chain - **APIs, Analytics, Artificial Intelligence, Machine Learning, ...** 
### > DevOps & Ops - Modeling Services
### > Data & Quality - Modeling Business
### 4. Learning
### > [Pattern - Technology & Business w/ Amazon CTO Werner Vogels](https://queue.acm.org/detail.cfm?id=1142065)
### > [Patterns](https://github.com/ankumar/Architecture/blob/master/Patterns/Stuff.md)

## 1. Modeling Services
[![Service Mesh](https://github.com/ankumar/Architecture/blob/master/images/Istio2.png)](https://www.youtube.com/watch?v=do-PrVi0ifk "Eric Brewer, VP Infrastructure & Google Fellow")<p align="center">
 <b>Google: 100,000+ services - Networking In & Across Regions </b></p>
 
![](https://images.ctfassets.net/ro61k101ee59/2bmS9TVlJc5einK9YLBY3V/992367961e649dd0343a3486616601fd/Image-1.png?w=1348&q=90)
<p align="center"> <a href="https://monzo.com/blog/we-built-network-isolation-for-1-500-services">A Modern App, Monzo Bank: 1,600+ services - A visualisation of network of microservices w/ Strong DevOps & Observability</a> </p>
 
## > Devs to focus on Business logic, Hiding Distributed systems complexity
**There isn't a concrete, well-defined algorithm for [decomposing](https://blog.acolyer.org/2016/09/05/on-the-criteria-to-be-used-in-decomposing-systems-into-modules/) a system into services. As with much of software development, it's something of an art. If you decompose a system incorrectly, we have a distributed monolith, a system consisting of coupled services that must be deployed together. A distributed monolith has the drawbacks of both the monolithic and the Microservices architectures.** <br/>
- "APIs are forever, code is not..." - Mike Amundsen
- Services, Stateless & Stateful
- State, Purpose-built Databases
    * IN-MEMORY - Memcached, Redis, ...
    * RELATIONAL - Oracle, SQL Server, PostgresSQL, MySQL, MariaDB, ...
    * KEY VALUE - Cassandra, CosmosDB, ...
    * WIDE COLUMN - Cassandra
    * DOCUMENT - MongoDB, CosmosDB, ...
    * TIME-SERIES
    * LEDGER
* Preparing for a future Microservices journey using DDD & Wardley Maps
  - [Slides](https://www.slideshare.net/SusanneKaiser3/preparing-for-a-future-microservices-journey-using-ddd-wardley-maps)
  - [Video](https://www.youtube.com/watch?v=1cnLMuBABo0)

**Examples:**
* [GCP Cloud Run- Run stateless containers on a fully managed environment](https://cloud.google.com/run/)

## 2. Modeling Business
 - Data Catalog
 - Data Warehouse
 - Data Lake
### Data powers new innovations, improvements in customer experience, and efficiency. Small advantage in data and algorithms result in increased customers/business success which in turn results in more data. This virtuous cycle due to positive feedback loop amplifies a company's competitive advantage, making data one of the key ingredients in building companies that have Increasing Returns instead of commonly seen Decreasing Returns.

![](https://miro.medium.com/max/1372/1*zOp70MCQ-uhaS7lUVAhATA.png)

### Advances in machine learning (ML) over the last decade have opened up a radically new approach to building software systems. Dubbed [“Software 2.0”](https://medium.com/@karpathy/software-2-0-a64152b37c35), this approach focuses on training models to learn from data instead of explicitly writing code for the required behavior. 
## > 1. Data Validation 
## <p align="center"> <b> "In traditional software engineering, or Software 1.0, a program’s functionality is defined via code as dictated by a human. In the age of machine learning, we are increasingly observing Software 2.0 systems, where a program’s functionality is defined by the weights of neural networks as dictated by the data. You wouldn’t trust a piece of human-written code that hasn’t ever been debugged or tested, so why shouldn’t our data receive the same treatment now that it’s a first-class citizen in so many real-world systems?"
Data Quality problem categories:
- Data creation
- Data labelling
- Data manipulation
- Data quality evaluation 
## > 2. Software Engineering Practices:
![](https://github.com/ankumar/Architecture/blob/master/images/Hidden%20Technical%20Debt%20in%20ML%20Systems.png)
### <p align="center"> [Hidden Technical Debt in Machine Learning Systems](https://papers.nips.cc/paper/5656-hidden-technical-debt-in-machine-learning-systems.pdf) </p>

## 3. Cloud Computing
| **Characteristics** | **Developer Productivity** |
|------------------------| ---------------------------------------------------------------------------------------------|
| **On-demand self-service** | A consumer can unilaterally provision computing capabilities, such as server time and network storage, as needed automatically without requiring human interaction |
|**Broad network access**|Capabilities are available over the network and accessed through standard mechanisms|
|**Resource pooling**|The provider’s computing resources are pooled to serve multiple consumers using a multi-tenant model, with different physical and virtual resources dynamically|
|**Rapid elasticity**|Capabilities can be elastically provisioned and released to scale rapidly outward and inward with demand|
|**Measured service**|Cloud systems automatically control and optimize resource use by leveraging a metering capability (typically per-per-use)|
## [NIST - standards & guidelines](https://nvlpubs.nist.gov/nistpubs/Legacy/SP/nistspecialpublication800-145.pdf)
![](https://github.com/ankumar/Architecture/blob/master/images/CNCF.png)<p align="center"> </p>
[![Opensource's value and collaborating with cloud vendors](https://github.com/ankumar/Architecture/blob/master/images/databricks-opensource.png)](https://dbricks.co/ex200221a, "")
### <p align="right"><b>- Ali Ghodsi, Co-founder & CEO at data science, big data processing and machine learning company Databricks.</b></p>
