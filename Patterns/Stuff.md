# The list here is not meant to be comprehensive, hopefully macro environments ...

# Software Engineering:

* [Margaret Hamilton](https://www.youtube.com/watch?v=ZbVOF0Uk5lU)
* [Software Art Thou: Glenn Vanderburg - Real Software Engineering](https://www.youtube.com/watch?time_continue=177&v=RhdlBHHimeM)
* [Building projects despite (and because of) existing complex systems](https://queue.acm.org/detail.cfm?id=3390746)
* [How Did Software Get So Reliable Without Proof? ](https://www.gwern.net/docs/math/1996-hoare.pdf)

# Developer Experience:
**"Application developers are successful when their work IS noticed. Platform developers are successful when their work is NOT noticed."** <br>
Good perspective! When done well, Platforms drive: <br>
1. Speed for Devs  &  Stability/Scalability/Security for Ops.<br>
2. Combining for a Win-Win! <br>
![Developers Developers Developers ...](https://github.com/ankumar/Architecture/blob/master/images/Github.png)<p align="center"> <p align="center"><b> 40 million Developers </b> </p>
### Developers - Over 1.3 million first time contributors joined the open source community
* [2019 Octoverse report](https://octoverse.github.com/)
-- After the United States, open source use picked up speed in China, India, and Germany this year. Developers in China forked and cloned 48% more projects than last year
* [2018 Octoverse report](https://octoverse.github.com/2018/)
-- collaborating more than ever before, with 1.1 billion contributions—and counting, transcending borders and barriers of all varieties to create something unquantifiable: a community of leaders, dreamers, dissenters, tinkerers, and doers building the way forward.
## "I maintain @github Actions is a shining beacon of developer experience done right." - @QuinnyPig
   * [Workflow (new feature)](https://github.com/features/actions)
     * [Compute: GCE, GKE, CLOUD RUN](https://github.com/GoogleCloudPlatform/github-actions)
   * [Desktop](https://desktop.github.com/)
   * [Mobile](https://github.com/mobile)  
* [Cloud Run](https://cloud.google.com/run/)
* [OSS Visual Studio Code](https://github.com/microsoft/vscode)
  * [Facebook moving from lots of internally developed tools](https://developers.facebook.com/blog/post/2019/11/19/facebook-microsoft-partnering-remote-development/) 
* [Wicked Problem](https://leadingedgeforum.com/research/are-platform-organizations-a-wicked-problem/)
  * [Liberating platform organizations](https://leadingedgeforum.com/research/liberating-platform-organizations/)

# Open Source:
* Cloud would not have been possible without open source
* “if you want to go fast go alone, but if you want to go far, go together”. "Feels like it's time to really focus on accelerating the abundance of open source, collaborating to make the pie bigger for all. Abundance, not scarcity. I'm so, so happy to see Elastic doing well, and love this community where we can build together, even when we compete"
* " "new model" is a big increase in end user corporations contributing to and producing their own open source projects. That's where the resources are coming from, and it's part of the success of Netflix, Capital One, Lyft, Airbnb that is spreading.” <p align="right"><b>- Adrian Cockcroft, VP Cloud architecture strategy at Amazon Web Services</b></p>
* Over 1.3 million first time contributors joined the open source community
* Community & Company Driven [Projects](https://www.linuxfoundation.org/projects/)
* Open [Governance](https://github.com/cncf/toc/), Stewardship & [Principles](https://github.com/cncf/toc/blob/master/PRINCIPLES.md#toc-operating-principles)
* How much has cloud hurt Elastic? "We haven't seen Open Distro really make any change or difference for us". Lots of good, incl AWS/others contributing to Elasticsearch/Lucene & seemingly no bad. Turns out cloud/open source are force multipliers. -  Shay Banon (CEO)

[![It's not a race if we're all on the same team](https://github.com/ankumar/Architecture/blob/master/images/Kelsey%20Hightower.png)](https://www.youtube.com/watch?v=jiaLsxjBeOQ "Kelsey Hightower, Staff Developer Advocate, Google")
<p align="center"> "*it's not a race it's a marathon ... it's not a race if we're all on the same team*" </p>

* InnerSource - Open source best practices within organization
  * [GitHub Whitepaper](https://resources.github.com/whitepapers/introduction-to-innersource/)
  * [Open source best practices within organization](https://github.com/InnerSourceCommons/InnerSourcePatterns)
  * [Spotify Guilds – Cultivating Knowledge Sharing in Large-scale Agile Organizations](https://cacm.acm.org/magazines/2020/3/243029-spotify-guilds/abstract)   “Guilds or Communities of practice (CoPs) are not a new phenomenon. Communities existed in the cave times, when people gathered around a fire to discuss strategies for cornering prey. Communities are cultivated for their potential to influence the knowledge culture and bring value on the individual level (e.g. forum for expanding skills and expertise, strong sense of professional identity), team/project level (e.g. arena for problem solving, quick answers to questions) and company level (e.g. coordination and standardization across units, knowledge-based alliances, increased retention of talent). In large-scale agile organizations, CoPs are recognized for alleviating the inter-team coordination.”

# Services:
Designing Modularity & Interfaces, Decomposing an Application into Services & APIs:

Historical Context: [Martin Fowler](https://twitter.com/martinfowler) & [James Lewis](https://twitter.com/boicy) In 2014 described the emerging microservices architectural style, identified 9 common characteristics ( size wasn't on the list, size is one of the least useful ). 
There are many useful heuristics for defining the boundaries of a service
* A Service is responsible for a specific business capability
* Explicit boundaries, both technically & functionally
* 'micro-services', 'milli-services', 'nano-services', 'macro-services' or 'well-sized services' - No-prefix services, call it just Service, 'size' is not important, boundaries are the problem
* Size is not a heuristics because it is not measurable
* Recommend a Service per team, since that's what's needed for Team Autonomy, unless there is a darn good reason for a team to have more

![](https://github.com/ankumar/Architecture/blob/master/images/Microservices1.jpg)
[Microservices](https://www.youtube.com/watch?v=wgdBVIX9ifA) - also known as the [microservice architecture](https://microservices.io/index.html) is an architectural style that structures an application as a collection of services that are

**1. Highly maintainable & testable** <br>
**2. Loosely coupled** <br>
**3. Independently deployable** <br>
**4. Organized around business capabilities** <br>
**5. Owned by a small team**<br>

* [On the criteria to be used in decomposing systems into modules](https://dl.acm.org/doi/10.1145/361598.361623)
* [Assembling Software from Independent Systems](https://scs-architecture.org/)
* [The Twelve Factors](https://12factor.net/)
* [Martin Fowler](https://martinfowler.com/)
* [Untangling Microservices, or Balancing Complexity in Distributed Systems](https://vladikk.com/2020/04/09/untangling-microservices/)
* [Historical Context & Shifts](https://slidr.io/kameshsampath/sail-smoothly-in-the-cloud-an-introduction-to-istio#1)
* [Modular Monoliths](https://www.youtube.com/watch?v=5OjqD-ow8GE)
* [Service Mesh](https://www.datawire.io/envoyproxy/service-mesh/)
* [Query Language for API](https://graphql.org/)
* [Fin Tech](https://github.com/ankumar/Architecture/blob/master/Patterns/Monzo.md)
* [Serverless Patterns](https://docs.google.com/document/d/1I6jaJyrsSTrrXEtrwSqH6aSuKRkyYhJU7LaYedVmvck/)
* [Domain-Driven Design](https://www.dddheuristics.com/)
* [Distributed Application Runtime- An event-driven, portable runtime for building microservices on cloud and edge](https://dapr.io/)
* [Open Application Model- A team-centric *standard* for building cloud native apps](https://oam.dev/)
  
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

![https://www.datacouncil.ai/](https://github.com/ankumar/Architecture/blob/master/images/Data%20Council.png)
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
  
# Cloud Computing:
## In the future the majority of managed infrastructure offerings will be backed by open interfaces, but not necessarily open source projects.

* [SCREAMING IN THE CLOUD](https://www.lastweekinaws.com/podcast/screaming-in-the-cloud/)
  * On the future of @Kubernetesio “We'll enter another phase where you'll build a platform on top of Kubernetes, but it won't be worth mentioning that Kubernetes is underneath. People will be more interested in the thing above.” 
* https://www.youtube.com/watch?v=ZVRI214nnto
* [A Brief History](https://docs.google.com/presentation/d/1BoxFeENJcINgHbKfygXpXROchiRO2LBT-pzdaOFr4Zg/edit#slide=id.g39c264972c_182_1000)
* [Standards](https://docs.google.com/presentation/d/1wc9nJSyfjrUO2KpVgXt5KnSHVlWvXpho6eINkin5U5g/edit#slide=id.g12bfb019f3_2_34)
* [Open Application Model](https://oam.dev/)
* [Decouple developers from operations](https://www.youtube.com/watch?v=do-PrVi0ifk)
* [Kafka Cloud Native](https://www.confluent.io/blog/introducing-cloud-native-experience-for-apache-kafka-in-confluent-cloud)
* [Cassandra Cloud](https://constellation.datastax.com/)
* [Amazon Aurora cloud-native relational database](https://www.allthingsdistributed.com/2019/03/Amazon-Aurora-design-cloud-native-relational-database.html)
* [Socrates: The New SQL Server in the Cloud](https://www.microsoft.com/en-us/research/uploads/prod/2019/05/socrates.pdf)
* [Azure Architecture Center](https://docs.microsoft.com/en-us/azure/architecture/)
* The Amazon Effect
   * [Open Source at AWS](https://aws.amazon.com/opensource)
   * [Commercial Open Source Software](https://coss.media/oss-will-eat-cloud-computing/)
   * [Fork and Commoditize](https://thenewstack.io/fork-and-commoditize-gitlab-ceo-critiques-the-new-open-source-approach-by-amazon-web-services/)
   * [AWS Well-Architected Labs](https://wellarchitectedlabs.com)
   * [Amazon Builders Library](https://aws.amazon.com/builders-library/)
   * [AWS Well-Architected Framework](https://wa.aws.amazon.com/index.en.html)
 
# Ops:
[![](https://github.com/ankumar/Architecture/blob/master/images/Above%20The%20Line.png)](https://www.youtube.com/embed/8bxj-FLEi10 "")
<p align="center"><b>Above & Below The Line - "A Model, Broad, proactive learning keeps pace with change, continually recharging the sources of adaptive capacity that lead to resilient performance.”</b></p>

SLI/SLO/SLA:
* [Observability](https://www.honeycomb.io/)

Learning From Incident Analysis:
* [Beyond the "Fix-it" Treadmill](https://queue.acm.org/detail.cfm?id=3380780)
* [RCA - If everyone is responsible for success, why not failure? Root cause analysis exists to find blame](https://www.verica.io/inhumanity-of-root-cause-analysis/)
* [Incidents](https://www.adaptivecapacitylabs.com/blog/)
* [Human Performance in Software](https://queue.acm.org/detail.cfm?id=3380776)
* [Study of complex systems](https://www.complexityexplorer.org/)

Chaos Engineering:
* </>

# Design & Architecture:
[![Systems thinking for a better world](https://github.com/ankumar/Architecture/blob/master/images/Systems%20thinking%20for%20a%20better%20world.png)](https://www.youtube.com/watch?v=d53-nyFzoVI "Rebecca Mills")
## 1. SYSTEMS THINKING - Large Scale Macro Environment, Technology/Processes/People
## 2. FUTURE - Opportunities & Patterns, NOT discrete Issues or Events
## 3. ENGAGE OTHERS TO DO THE SAME - Collective highly targeted unit, Shared View
  
## Architecture is about **Systems Thinking** including People, Process and Technology; synthesis of multiple perspectives, including social dynamics, domain-driven design, business models, and software architecture. It's not about code, and it's not a synonym for "software architecture"
![http://www.melconway.com/Home/Conways_Law.html](https://github.com/ankumar/Architecture/blob/master/images/Conways%20Law.png)

[![Systems Thinking](https://github.com/ankumar/Architecture/blob/master/images/Russell%20Ackoff.png)](https://www.youtube.com/watch?v=OqEeIG8aPPk "Dr. Russell Ackoff")
## <p align="center"><b>"If we have a system of improvement that’s directed at improving the parts taken separately, you can be absolutely sure that the performance of the whole will not be improved. The performance of a system depends on how the parts fit, not how they act taken separately.” <b>- Dr. Russell Ackoff.</b></p>
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

## Enterprise:
![](https://github.com/ankumar/Architecture/blob/master/images/wardley.jpeg)

"Anything is possible for a company when its culture is about listening, learning, and harnessing individual passions and talents to the company’s mission." - Satya Nadella

"One of the biggest tragedies in modern organisation design is the separation of tech and business. A big part of the role of technical leader and architect is to break down these barriers" - Martin Fowler, O’Reilly Software Arhitecture Conference

"Changing technology is (comparatively) easy compared to changing culture" / "Culture needs to change as our tech approaches change, but we’ve got to be patient, empathetic and realistic "
## 1. **Legacy:** "it makes actual money"
## 2. **Architecture:** Greenfield & Brownfield, Systems and Data
## 3. **Cloud:** **Cost Effective Scheduling, Data Gravity**

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

* **Design**
   * [The elephant in the architecture](https://www.oreilly.com/radar/the-elephant-in-the-architecture/)
   “One of the biggest tragedies, I feel, in much of the software world, is how we divorce ourselves, and organizations create barriers between the business side, and the technical side, and it's important for an architect, as a technical leader, to go out, and try and break down those barriers …”
   * [The Science of Digital Platforms](https://leadingedgeforum.com/media/1752/3-digital-platforms_b-murray.pdf)
   * [Business value as an architectural attribute](https://martinfowler.com/articles/value-architectural-attribute.html)
   * [Organizational Culture](https://cloud.google.com/solutions/devops/devops-culture-westrum-organizational-culture)
   * [Taking a Lean Thinking perspective](https://doi.org/10.4233/uuid:9a984128-64f2-41f2-83ee-441787362d46)
   * [Resources for Software and Systems Architects](http://www.bredemeyer.com/)
   * [The Architect Elevator](https://architectelevator.com/)
   
* **Cell Based Architecture**
  * [How AWS Minimizes the Blast Radius of Failures - Cell based architecture starts at 21:07](https://www.youtube.com/watch?v=swQbA4zub20)
  * [WSO2 - Enterprise Reference](https://github.com/wso2/reference-architecture/blob/master/reference-architecture-cell-based.md)
  * [Highscalability - Circa 2012](http://highscalability.com/blog/2012/5/9/cell-architectures.html)
* **DevOps**
  * [State of DevOps 2019](https://services.google.com/fh/files/misc/state-of-devops-2019.pdf)
  * [DevOps Transformation](https://github.com/ankumar/Architecture/blob/master/Patterns/The%20Unicorn%20Project.md)

## Sometimes architects wonder how they get attention up in the "penthouse". This is it - leadership is starved for meaningful, neutral advice. As an architect neutrality is the most important asset. It provides tremendous value to leadership, they usually don't get unbiased information from anybody else, everybody else has an agenda (usually money) - @ghohpe #OReillySACon #OReillySAConQuotes

## "Best way to get another peer architect is to train one" - Sonya Natanzon
* [Technical Leadership Masterclass](https://ruthmalan.com/Journal/2019/20190629SlideDocTechnicalLeadershipDecisions.pdf)

* [Prof. Richard Rumelt | Good Strategy/Bad Strategy](https://www.youtube.com/watch?v=UZrTl16hZdk)
* [Simon Wardley | Create situational awareness in business...](https://medium.com/wardleymaps/on-being-lost-2ef5f05eb1ec)

![](https://github.com/ankumar/Architecture/blob/master/images/Kotter%208%20Steps.jpeg) ![](https://github.com/ankumar/Architecture/blob/master/images/Kotter%208%20Steps2.jpeg)

# Anti-patterns:
* A [big ball of mud](http://www.laputan.org/mud/) is a software system that lacks a perceivable architecture. Although undesirable from a software engineering point of view, such systems are common in practice due to business pressures, developer turnover and code entropy. They are a type of design anti-pattern.

# Terminology:
* Cloud Native - Cloud native technologies empower organizations to build and run scalable applications in modern, dynamic environments such as public, private, and hybrid clouds. Containers, service meshes, microservices, immutable infrastructure, and declarative APIs exemplify this approach. These techniques enable loosely coupled systems that are resilient, manageable, and observable. Combined with robust automation, they allow engineers to make high-impact changes frequently and predictably with minimal toil.
* Inner Source - Global & Local dichotomy, Open source best practices within organization
* Cell-Based Architecture - System Availability & Minimize the "blast radius" of any failures
   * [Cell-Based Architecture](https://github.com/wso2/reference-architecture/blob/master/reference-architecture-cell-based.md)
   * [Shopify Journey](https://engineering.shopify.com/blogs/engineering/e-commerce-at-scale-inside-shopifys-tech-stack)
* [Control vs Data plane](http://www.cs.cmu.edu/~4D/papers/greenberg-ccr05.pdf) - </>
* [Lean Enterprise](https://learning.oreilly.com/library/view/lean-enterprise/9781491946527/) - Single Metric, Measure Time to Value everywhere
* [Conway's Law](http://www.melconway.com/Home/Conways_Law.html) - How to Organize Organization for Optimal Development / "Shipping the Org Chart",  Pay the cost later in internal tools & stitching data together

# Academic:
## Stanford - Matei Zaharia
 * [Value of Data and AI](https://canvas.stanford.edu/courses/114221)
 * [Principles of Data-Intensive Systems](http://web.stanford.edu/class/cs245/)
