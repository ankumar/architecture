<font size="16">
 
# Application Development Architecture

## Systems Thinking: 
[![Systems Thinking](https://github.com/ankumar/Architecture/blob/master/images/Russell%20Ackoff.png)](https://www.youtube.com/watch?v=OqEeIG8aPPk "Dr. Russell Ackoff")
## <p align="center"><b>"If we have a system of improvement that’s directed at improving the parts taken separately, you can be absolutely sure that the performance of the whole will not be improved. The performance of a system depends on how the parts fit, not how they act taken separately.” <b>- Dr. Russell Ackoff.</b></p>
  
![](https://github.com/ankumar/Architecture/blob/master/images/wardley.jpeg)

"Anything is possible for a company when its culture is about listening, learning, and harnessing individual passions and talents to the company’s mission." - Satya Nadella

"One of the biggest tragedies in modern organisation design is the separation of tech and business. A big part of the role of technical leader and architect is to break down these barriers" - Martin Fowler, O’Reilly Software Arhitecture Conference

"Changing technology is (comparatively) easy compared to changing culture" / "Culture needs to change as our tech approaches change, but we’ve got to be patient, empathetic and realistic "
## 1. **Legacy:** "it makes actual money"
## 2. **Architecture:** Greenfield & Brownfield, Systems and Data
## 3. **Cloud:** **Containers & Cost Effective Scheduling, Data Gravity**

## Enterprise Architecture:
![](https://github.com/ankumar/Architecture/blob/master/images/Big-O.gif)
<p> <b> Context Specific - Know Thy Complexities! </b> </p>

#### <p align="center"> <b> "enterprises buy everything. If you're big enough and you have a big enough IT budget, most enterprises have a POC of everything that's for sale, period. There's some team in some pocket, maybe they came through via acquisition. Maybe they live in a different state. Maybe it's just a new project that came out. And what you tend to see, at least from my experiences, if I walk into a typical enterprise, they may tell me something like, "Hey, we have a POC, a Pivotal Cloud Foundry, OpenShift, and we want some of that new thing that we just saw from you guys. How do we get a POC going?" </b> </p> [- Kelsey Hightower, principal developer advocate at Google](https://www.lastweekinaws.com/podcast/screaming-in-the-cloud/the-staying-power-of-kubernetes-with-kelsey-hightower/)
## **1. Technology needs to be embedded in the Business not external to it or merely aligned with it**
         - Work backwards from Customer/Business outcomes
         - Build closed loop systems to optimize for continual Improvements & Learning
         - Technology Commoditization
## **2. Focus on core value vs plumbing:**
         - Business mapped into technologies that underpin the delivery of that core value 
         - Seeing Custom & Commodity technologies in the value chain
         - Custom to Commodity & Viceversa to increase the value delivery for lower cost

## Software Architecture:
### > Delivery & Operations, Model "As a Service"
### > Hiding Distributed systems complexity, Devs to focus on Business logic
### > Value of Data & Quality, Business models around data
### > Open source best practices, Inner Sourcing

### 1. Apps 
 - Services, Stateless & Stateful
 - Purpose-built Databases
### 2. Data 
 - Data Warehouse
 - Data Lake
 
### > [>> Leading Change ...](https://github.com/ankumar/Architecture/blob/master/Patterns/Stuff.md)
---
## 1. Services
![](https://github.com/ankumar/Architecture/blob/master/images/Microservices1.jpg)
[Microservices](https://www.youtube.com/watch?v=wgdBVIX9ifA) - also known as the [microservice architecture](https://microservices.io/index.html) is an architectural style that structures an application as a collection of services that are

**1. Highly maintainable & testable** <br>
**2. Loosely coupled** <br>
**3. Independently deployable** <br>
**4. Organized around business capabilities** <br>
**5. Owned by a small team**<br>
![](https://images.ctfassets.net/ro61k101ee59/2bmS9TVlJc5einK9YLBY3V/992367961e649dd0343a3486616601fd/Image-1.png?w=1348&q=90)
<p align="center"> <a href="https://monzo.com/blog/we-built-network-isolation-for-1-500-services">A Modern Bank, Monzo: 1,500+ services</a> </p>

## <p align="center"> "APIs are forever, code is not..." - Mike Amundsen </p>

[![Service Mesh](https://github.com/ankumar/Architecture/blob/master/images/Istio2.png)](https://www.youtube.com/watch?v=do-PrVi0ifk "Eric Brewer, VP Infrastructure & Google Fellow")<p align="center">
 <b>Connecting In & Across Data centers  - Google: 100,000+ services</b></p>
## > Devs to focus on Business logic, Hiding Distributed systems complexity, Examples:
**There isn't a concrete, well-defined algorithm for decomposing a system into services. As with much of software development, it's something of an art. If you decompose a system incorrectly, we have a distributed monolith, a system consisting of coupled services that must be deployed together. A distributed monolith has the drawbacks of both the monolithic and the Microservices architectures.**
* [GCP Cloud Run- Run stateless containers on a fully managed environment](https://cloud.google.com/run/)
* [Distributed Application Runtime- An event-driven, portable runtime for building microservices on cloud and edge](https://dapr.io/)
* [Open Application Model- A team-centric *standard* for building cloud native apps](https://oam.dev/)

## 2. Data

### Data powers new innovations, improvements in customer experience, and efficiency. Small advantage in data and algorithms result in increased customers/business success which in turn results in more data. This virtuous cycle due to positive feedback loop amplifies a company's competitive advantage, making data one of the key ingredients in building companies that have Increasing Returns instead of commonly seen Decreasing Returns.

![](https://miro.medium.com/max/1372/1*zOp70MCQ-uhaS7lUVAhATA.png)

### Advances in machine learning (ML) over the last decade have opened up a radically new approach to building software systems. Dubbed [“Software 2.0”](https://medium.com/@karpathy/software-2-0-a64152b37c35), this approach focuses on training models to learn from data instead of explicitly writing code for the required behavior. 
![https://www.datacouncil.ai/](https://github.com/ankumar/Architecture/blob/master/images/Data%20Council.png)
<p align="center"> <a href="https://www.datacouncil.ai/"> <b> Data Council </b> </p>

https://github.com/ankumar/Architecture/blob/master/images/Hidden%20Technical%20Debt%20in%20ML%20Systems.png

## <p align="center"> <b> "In traditional software engineering, or Software 1.0, a program’s functionality is defined via code as dictated by a human. In the age of machine learning, we are increasingly observing Software 2.0 systems, where a program’s functionality is defined by the weights of neural networks as dictated by the data. You wouldn’t trust a piece of human-written code that hasn’t ever been debugged or tested, so why shouldn’t our data receive the same treatment now that it’s a first-class citizen in so many real-world systems?"

## > 1. Data Validation 
Data quality problem categories:
- Data creation
- Data labelling
- Data manipulation
- Data quality evaluation 
## > 2. Software Engineering Practices, Examples:
* [ML development is harder than traditional software development;Production ML is Even Harder](https://www.slideshare.net/matei/scaling-up-machine-learning-development)
* [Organize, Manage, and Deploy your company’s ML model portfolio](https://algorithmia.com/enterprise)
* [GitHub Source Code Management for Algorithms](https://algorithmia.com/blog/introducing-github-source-code-management-for-algorithmia)
</b> </p>

## 3. Open Source
### - “if you want to go fast go alone, but if you want to go far, go together”. "Feels like it's time to really focus on accelerating the abundance of open source, collaborating to make the pie bigger for all. Abundance, not scarcity. I'm so, so happy to see Elastic doing well, and love this community where we can build together, even when we compete"
### - " "new model" is a big increase in end user corporations contributing to and producing their own open source projects. That's where the resources are coming from, and it's part of the success of Netflix, Capital One, Lyft, Airbnb that is spreading. ” <p align="right"><b>- Adrian Cockcroft, VP Cloud architecture strategy at Amazon Web Services</b></p>
### <p> <b>- Cloud would not have been possible without open source</b> </p>
### - Developers - Over 1.3 million first time contributors joined the open source community
* [2019 Octoverse report](https://octoverse.github.com/)
-- After the United States, open source use picked up speed in China, India, and Germany this year. Developers in China forked and cloned 48% more projects than last year
* [2018 Octoverse report](https://octoverse.github.com/2018/)
-- collaborating more than ever before, with 1.1 billion contributions—and counting, transcending borders and barriers of all varieties to create something unquantifiable: a community of leaders, dreamers, dissenters, tinkerers, and doers building the way forward.
### - How much has cloud hurt Elastic? "We haven't seen Open Distro really make any change or difference for us". Lots of good, incl AWS/others contributing to Elasticsearch/Lucene & seemingly no bad. Turns out cloud/open source are force multipliers. -  Shay Banon (CEO)
### - Community & Company Driven [Projects](https://www.linuxfoundation.org/projects/)
### - Open [Governance](https://github.com/cncf/toc/), Stewardship & [Principles](https://github.com/cncf/toc/blob/master/PRINCIPLES.md#toc-operating-principles)
[![It's not a race if we're all on the same team](https://github.com/ankumar/Architecture/blob/master/images/Kelsey%20Hightower.png)](https://www.youtube.com/watch?v=jiaLsxjBeOQ "Kelsey Hightower, Staff Developer Advocate, Google")
### <p align="center"> "*Allergies* - This is one of the best keynotes I've ever seen. it's not a race it's a marathon   ........... it's not a race if we're all on the same team" </p>

## > Inner Sourcing
### >> [Open source best practices within organization](https://github.com/InnerSourceCommons/InnerSourcePatterns)
### >> [Spotify Guilds – Cultivating Knowledge Sharing in Large-scale Agile Organizations](https://cacm.acm.org/magazines/2020/3/243029-spotify-guilds/abstract)

 “Guilds or Communities of practice (CoPs) are not a new phenomenon. Communities existed in the cave times, when people gathered around a fire to discuss strategies for cornering prey. Communities are cultivated for their potential to influence the knowledge culture and bring value on the individual level (e.g. forum for expanding skills and expertise, strong sense of professional identity), team/project level (e.g. arena for problem solving, quick answers to questions) and company level (e.g. coordination and standardization across units, knowledge-based alliances, increased retention of talent). In large-scale agile organizations, CoPs are recognized for alleviating the inter-team coordination.”

## 4. Cloud Computing
### - On the future of @Kubernetesio “We'll enter another phase where you'll build a platform on top of Kubernetes, but it won't be worth mentioning that Kubernetes is underneath. People will be more interested in the thing above.”
|Characteristics|Developer Productivity|
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
</font>
