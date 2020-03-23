# Digital Platforms

![](https://github.com/ankumar/Architecture/blob/master/images/Werner.png)
> New ways of thinking about solving actual business problem, [Nocode - Write nothing; Deploy nowhere!](https://twitter.com/kelseyhightower/status/961026365146320896) / [Dark - Holistic approach](https://medium.com/darklang/the-design-of-dark-59f5d38e52d2) / [An Application Development, Execution Platform for the Rest of Us](https://twitter.com/conways_law/status/1238539198203822081)

## 1. Platform is a perspective, serving our customers
## 2. Value Chain - **APIs, Analytics, Artificial Intelligence, Machine Learning, ...** 
### > Data & Quality, Business models around data
### > Development & Operations, Model "As a Service"
### > Development, [Dealing with the Complexity](https://github.com/ankumar/Architecture/blob/master/Patterns/Stuff.md)

## 1. Services
- "APIs are forever, code is not..." - Mike Amundsen
 - Services, Stateless & Stateful
 - State, Purpose-built Databases
 
[![Service Mesh](https://github.com/ankumar/Architecture/blob/master/images/Istio2.png)](https://www.youtube.com/watch?v=do-PrVi0ifk "Eric Brewer, VP Infrastructure & Google Fellow")<p align="center">
 <b>Google: 100,000+ services - Connecting In & Across Regions </b></p>
 
![](https://images.ctfassets.net/ro61k101ee59/2bmS9TVlJc5einK9YLBY3V/992367961e649dd0343a3486616601fd/Image-1.png?w=1348&q=90)
<p align="center"> <a href="https://monzo.com/blog/we-built-network-isolation-for-1-500-services">A Modern Bank, Monzo: 1,600+ services - A visualisation of network of microservices w/ Strong DevOps & Observability</a> </p>
 
## > Devs to focus on Business logic, Hiding Distributed systems complexity
**There isn't a concrete, well-defined algorithm for [decomposing](https://blog.acolyer.org/2016/09/05/on-the-criteria-to-be-used-in-decomposing-systems-into-modules/) a system into services. As with much of software development, it's something of an art. If you decompose a system incorrectly, we have a distributed monolith, a system consisting of coupled services that must be deployed together. A distributed monolith has the drawbacks of both the monolithic and the Microservices architectures.** <br/>
* Preparing for a future Microservices journey using DDD & Wardley Maps
  - [Slides](https://www.slideshare.net/SusanneKaiser3/preparing-for-a-future-microservices-journey-using-ddd-wardley-maps)
  - [Video](https://www.youtube.com/watch?v=1cnLMuBABo0)

**Examples:**
* [GCP Cloud Run- Run stateless containers on a fully managed environment](https://cloud.google.com/run/)

## 2. Data
 - Data Catalog
 - Data Warehouse
 - Data Lake
### Data powers new innovations, improvements in customer experience, and efficiency. Small advantage in data and algorithms result in increased customers/business success which in turn results in more data. This virtuous cycle due to positive feedback loop amplifies a company's competitive advantage, making data one of the key ingredients in building companies that have Increasing Returns instead of commonly seen Decreasing Returns.

![](https://miro.medium.com/max/1372/1*zOp70MCQ-uhaS7lUVAhATA.png)

### Advances in machine learning (ML) over the last decade have opened up a radically new approach to building software systems. Dubbed [“Software 2.0”](https://medium.com/@karpathy/software-2-0-a64152b37c35), this approach focuses on training models to learn from data instead of explicitly writing code for the required behavior. 
## > 1. Data Validation 
## <p align="center"> <b> "In traditional software engineering, or Software 1.0, a program’s functionality is defined via code as dictated by a human. In the age of machine learning, we are increasingly observing Software 2.0 systems, where a program’s functionality is defined by the weights of neural networks as dictated by the data. You wouldn’t trust a piece of human-written code that hasn’t ever been debugged or tested, so why shouldn’t our data receive the same treatment now that it’s a first-class citizen in so many real-world systems?"
Data quality problem categories:
- Data creation
- Data labelling
- Data manipulation
- Data quality evaluation 
## > 2. Software Engineering Practices:
![](https://github.com/ankumar/Architecture/blob/master/images/Hidden%20Technical%20Debt%20in%20ML%20Systems.png)
### <p align="center"> [Hidden Technical Debt in Machine Learning Systems](https://papers.nips.cc/paper/5656-hidden-technical-debt-in-machine-learning-systems.pdf) </p>

## 3. Open Source
### - “if you want to go fast go alone, but if you want to go far, go together”. "Feels like it's time to really focus on accelerating the abundance of open source, collaborating to make the pie bigger for all. Abundance, not scarcity. I'm so, so happy to see Elastic doing well, and love this community where we can build together, even when we compete"
### - " "new model" is a big increase in end user corporations contributing to and producing their own open source projects. That's where the resources are coming from, and it's part of the success of Netflix, Capital One, Lyft, Airbnb that is spreading. ” <p align="right"><b>- Adrian Cockcroft, VP Cloud architecture strategy at Amazon Web Services</b></p>
### <p> <b>- Cloud would not have been possible without open source</b> </p>
### - Developers - Over 1.3 million first time contributors joined the open source community
### - How much has cloud hurt Elastic? "We haven't seen Open Distro really make any change or difference for us". Lots of good, incl AWS/others contributing to Elasticsearch/Lucene & seemingly no bad. Turns out cloud/open source are force multipliers. -  Shay Banon (CEO)
### - Community & Company Driven [Projects](https://www.linuxfoundation.org/projects/)
### - Open [Governance](https://github.com/cncf/toc/), Stewardship & [Principles](https://github.com/cncf/toc/blob/master/PRINCIPLES.md#toc-operating-principles)
[![It's not a race if we're all on the same team](https://github.com/ankumar/Architecture/blob/master/images/Kelsey%20Hightower.png)](https://www.youtube.com/watch?v=jiaLsxjBeOQ "Kelsey Hightower, Staff Developer Advocate, Google")
### <p align="center"> "Allergies - *it's not a race it's a marathon ... it's not a race if we're all on the same team*" </p>

## > InnerSource
### >> [GitHub Whitepaper](https://resources.github.com/whitepapers/introduction-to-innersource/)
### >> [Open source best practices within organization](https://github.com/InnerSourceCommons/InnerSourcePatterns)
### >> [Spotify Guilds – Cultivating Knowledge Sharing in Large-scale Agile Organizations](https://cacm.acm.org/magazines/2020/3/243029-spotify-guilds/abstract)

 “Guilds or Communities of practice (CoPs) are not a new phenomenon. Communities existed in the cave times, when people gathered around a fire to discuss strategies for cornering prey. Communities are cultivated for their potential to influence the knowledge culture and bring value on the individual level (e.g. forum for expanding skills and expertise, strong sense of professional identity), team/project level (e.g. arena for problem solving, quick answers to questions) and company level (e.g. coordination and standardization across units, knowledge-based alliances, increased retention of talent). In large-scale agile organizations, CoPs are recognized for alleviating the inter-team coordination.”

## 4. Cloud Computing
| **Characteristics** | **Developer Productivity** |
|------------------------| ---------------------------------------------------------------------------------------------|
| **On-demand self-service** | A consumer can unilaterally provision computing capabilities, such as server time and network storage, as needed automatically without requiring human interaction |
|**Broad network access**|Capabilities are available over the network and accessed through standard mechanisms|
|**Resource pooling**|The provider’s computing resources are pooled to serve multiple consumers using a multi-tenant model, with different physical and virtual resources dynamically|
|**Rapid elasticity**|Capabilities can be elastically provisioned and released to scale rapidly outward and inward with demand|
|**Measured service**|Cloud systems automatically control and optimize resource use by leveraging a metering capability (typically per-per-use)|

![](https://github.com/ankumar/Architecture/blob/master/images/CNCF.png)<p align="center"> </p>
[![Opensource's value and collaborating with cloud vendors](https://github.com/ankumar/Architecture/blob/master/images/databricks-opensource.png)](https://dbricks.co/ex200221a, "")
### <p align="right"><b>- Ali Ghodsi, Co-founder & CEO at data science, big data processing and machine learning company Databricks.</b></p>

## > [Service Model - SaaS](https://nvlpubs.nist.gov/nistpubs/Legacy/SP/nistspecialpublication800-145.pdf)
