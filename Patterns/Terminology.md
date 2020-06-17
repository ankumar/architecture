# Glossary:

* **APIs** - REST, GraphQL or gRPC or anything else 

* **Application & Microservices** - https://martinfowler.com/articles/microservices.html
  * [Microservice, Why?](https://chrisrichardson.net/post/microservices/2020/02/18/why-microservices-part-1.html)
    * [Microservice Architecture](https://microservices.io/patterns/microservices.html)
  * Ex: [Demo App - Hipster Shop](https://github.com/GoogleCloudPlatform/microservices-demo)
![](https://github.com/ankumar/Architecture/blob/master/images/microservices.png)
Monoliths vs Microservices, both architectural patterns are valid, and for complex organizations, a mix of both is inevitable.

* [**Architecture Decision Records (ADR's)**](https://engineering.walmart.com/adrs) 
  * [Architecture Decision Records at Spotify](https://www.infoq.com/news/2020/04/architecture-decision-records/)
  * [TOMASP at Shopify](https://engineering.shopify.com/blogs/engineering/make-great-decisions-quickly-with-tomasp)

Irreversible: “Some decisions are **consequential** and **irreversible** or nearly irreversible [..] these decisions must be made methodically, carefully, slowly, with **great deliberation and consultation**”

Reversible: "But **most decisions** aren’t like that – they are **changeable, reversible** – they’re two-way doors. If you’ve made a suboptimal [reversible] decision, you don’t have to live with the consequences for that long. You can reopen the door and go back through."
   
* **Blast Radius** - Murphy's Law, "If anything can go wrong, it will." Failure is not binary, degree of impact
![](https://github.com/ankumar/Architecture/blob/master/images/Blast%20Radius.png)

* **CAP Theorem** - 

* **Cell-Based Architecture** - System Availability & Minimize the **"blast radius"** of any failures
  * [**How AWS Minimizes the Blast Radius of Failures - Cell based architecture starts at 21:07**](https://www.youtube.com/watch?v=swQbA4zub20)
  * [**WSO2 - Enterprise Reference**](https://github.com/wso2/reference-architecture/blob/master/reference-architecture-cell-based.md)
  * [**Control vs Data plane**](http://www.cs.cmu.edu/~4D/papers/greenberg-ccr05.pdf)
  * [**Shopify Journey**](https://engineering.shopify.com/blogs/engineering/e-commerce-at-scale-inside-shopifys-tech-stack)

* **Cloud Native** - Cloud native technologies empower organizations to build and run scalable applications in modern, dynamic environments such as public, private, and hybrid clouds. **Containers, service meshes, microservices, immutable infrastructure, and declarative APIs** exemplify this approach. These techniques enable loosely coupled systems that are resilient, manageable, and observable. Combined with robust automation, they allow engineers to make high-impact changes frequently and predictably with minimal toil.

* **Control & Data Planes** - 
![](https://github.com/ankumar/Architecture/blob/master/images/Control%20and%20Data%20planes.png)
  * [Control Planes vs Data Planes](https://brooker.co.za/blog/2019/03/17/control.html)
   
* [**Conway's Law**](http://www.melconway.com/Home/Conways_Law.html) - How to Organize Organization for Optimal Development / "Shipping the Org Chart",  Pay the cost later in internal tools & stitching data together
  * Inverse Conway Maneuver - **"organizations should evolve their team and organizational structure to achieve the desired architecture"**
    * https://www.thoughtworks.com/radar/techniques/inverse-conway-maneuver
  * **“One of the biggest tragedies, I feel, in much of the software world, is how we divorce ourselves, and organizations create barriers between the business side, and the technical side, and it's important for an architect, as a technical leader, to go out, and try and break down those barriers …”** – [By Martin Fowler, The elephant in the Architecture](https://www.oreilly.com/radar/the-elephant-in-the-architecture/) 

* **Data mapper** - A [data mapper](https://www.martinfowler.com/eaaCatalog/dataMapper.html) is a design pattern or piece of software that maps programming data structures to those stored in a database. Data mappers attempt to synchronize changes between the two sources while keeping them independent of each other. The mapper itself is responsible for maintaining a working translation, freeing developers to iterate the application data structures without concern for the database representation.

* **Data Transfer Object** - DTOs, A Pattern https://martinfowler.com/eaaCatalog/dataTransferObject.html

* **Design Patterns**
The concept of design patterns dates back to the 1970s and from the field of architecture. Christopher Alexander, an architect and system theorist, and his team published the groundbreaking [A Pattern Language](https://en.wikipedia.org/wiki/A_Pattern_Language) (Oxford University Press) in 1977, which describes architectural patterns for creating towns, buildings, and other construction projects. Sometime later this idea was adopted by the newly formed software industry. The most famous book in this area is [Design Patterns—Elements of Reusable Object-Oriented Software](https://en.wikipedia.org/wiki/Design_Patterns) by Erich Gamma, Richard Helm, Ralph Johnson, and John Vlissides—the Gang of Four (Addison-Wesley). When we talk about the famous Singleton, Factories, or Delegation patterns, it’s because of this defining work. Many other great pattern books have been written since then for various fields with different levels of granularity, like [Enterprise Integration Patterns](https://www.enterpriseintegrationpatterns.com/) by Gregor Hohpe and Bobby Woolf (Addison-Wesley) or [Patterns of Enterprise Application Architecture](https://www.martinfowler.com/books/eaa.html) by Martin Fowler (Addison-Wesley).

In short, a pattern describes a repeatable solution to a problem.[1] It is different from a recipe because instead of giving step-by-step instructions to solving a problem, a pattern provides a blueprint for solving a whole class of similar problems. For example, the Alexandrian pattern “Beer Hall” describes how public drinking halls should be constructed where “strangers and friends are drinking companions” and not “anchors of the lonely.” All halls built after this pattern look different, but share common characteristics such as open alcoves for groups of four to eight and a place where a hundred people can meet with beverages, music, and other activities.

However, a pattern does more than provide a solution. It is also about forming a language. The unique pattern names form a dense, noun-centric language in which each pattern carries a unique name. When this language is established, these names automatically evoke similar mental representations when people speak about these patterns. For example, when we talk about a table, anyone speaking English assumes we are talking about a piece of wood with four legs and a top on which you can put things. The same thing happens in software engineering when we talk about a “factory.” In an object-oriented programming language context, we immediately associate with a “factory” an object that produces other objects. Because we immediately know the solution behind the pattern, we can move on to tackle yet unsolved problems.

There are also other characteristics of a pattern language. Patterns are interconnected and can overlap so that together, they cover most of the problem space. Also, as already laid out in the original A Pattern Language, patterns do not have the same level of granularity and scope. More general patterns cover an extensive problem space and provide rough guidance on how to solve the problem. Granular patterns have a very concrete solution proposal but are not as widely applicable. This book contains all sort of patterns, and many patterns reference other patterns or may even include other patterns as part of the solution.

Another feature of patterns is that they follow a rigid format. However, each author defines a different format, and unfortunately there is no common standard for the way patterns should be laid out. Martin Fowler gives an excellent overview of the formats used for pattern languages in [Writing Software Patterns](https://www.martinfowler.com/articles/writingPatterns.html).

1. Christopher Alexander and his team defined the original meaning in the context of architecture as follows: “Each pattern describes a problem which occurs over and over again in our environment, and then describes the core of the solution to that problem, in such a way that you can use this solution a million times over, without ever doing it the same way twice,” (A Pattern Language, Christopher Alexander et al., 1977, p. x).

* [**Enterprise**](https://learning.oreilly.com/library/view/lean-enterprise/9781491946527/) - Single Metric, Measure **Time to Value** everywhere
  * **Governance**
    * [**Cloud**](https://aws.amazon.com/blogs/enterprise-strategy/governance-in-the-cloud-and-in-the-digital-age-part-one/)
  * **Business Continuity**
    * [**COVID19 Context**](https://azure.microsoft.com/en-us/blog/update-3-business-continuity-azure/)
     
* **Functions** - Functions are the general purpose element in serverless computing today, and lead the way to a simplified
and general purpose programming model for the cloud, packaged as FaaS (Function as a Service) offerings. Different cloud platforms have different names for their FaaS offerings—AWS Lambda for Amazon Web Services(AWS), Google Cloud Functions for Google Cloud Platform, IBM Cloud Functions for IBM Cloud, and Azure Functions for Microsoft Azure. They all have similar features, and we refer to them as cloud functions or FaaS offerings interchangeably.

   * [Stateful Functions](https://flink.apache.org/stateful-functions.html) 
   * [JAMstack Functions](https://jamstackfns.com/about) - The A in JAMstack, directory of Serverless functions.

* **Hybrid** - An Architecture where we use a public cloud provider in combination with private, own data center.

* **Injection attack** - An injection attack is an attack in which a malicious user attempts to execute unwanted database operations using specially crafted input in user-facing application fields. Often, this is used to retrieve data that should not be accessible or to delete or mangle information in the database.

* **Inner Source** - Global & Local dichotomy, Open source best practices within organization

* **Jamstack** - https://jamstack.org/

* **ORM** - ORMs, or object-relational mappers, are abstraction layers that translate between the data representations used in relational databases and the representation in memory used with object-oriented programming. The ORM provides an object-oriented interface to data within the database, attempting to reduce the amount of code and use familiar archetypes to speed up development.

* **Object-relational impedance mismatch** - Object-relational impedance mismatch refers to the difficulty of translating between an object-oriented application and a relational database. Since the data structures vary significantly, it can be difficult to faithfully and performantly mutate and transcribe the programmatic data structures to the format used by the storage backend.

* **Patterns** - Design patterns are formalized [best practices](https://en.wikipedia.org/wiki/Software_design_pattern) that the programmer can use to solve common problems when designing an application or system;[Microservices patterns](https://www.oreilly.com/content/why-a-pattern-language-for-microservices/)

* **Persistence framework** - A persistence framework is a middeware abstraction layer developed to bridge the gap between program data and databases. Persistence frameworks may also be ORMs if the abstraction they employ maps objects to relational entities.

* **Query builder** - A [query builder](https://softwareengineering.stackexchange.com/questions/138115/what-are-the-advantages-to-using-sql-query-builders) is an abstraction layer that helps developers access and control databases by providing a controlled interface which adds usability, safety, or flexibility features. Typically, query builders are relatively light-weight, focus on easing data access and data representation, and do not attempt to translate the data into a specific programming paradigm.

* **Serverless** - Serverless Computing provides an interface that greatly simplifies cloud programming, and represents an evolution that closely parallels past advances in programmer productivity, such as the transition from assembly language to high-level programming languages. Although it is arguably an oxymoron—you are still using servers to compute—the name caught on because it suggests that the cloud user simply writes the code and delegates the considerable server system administration tasks required by conventional cloud computing to the cloud provider.  The three fundamental differences between Serverless and conventional Cloud Computing are:

1. Decoupling of computation and storage; they scale separately and are priced independently.
2. The abstraction of executing a piece of code instead of allocating resources on which to execute that code.
3. Paying for the code execution instead of paying for resources you have allocated to executing the code.

   * [Cloud Programming Simplified: A Berkeley View on Serverless Computing](https://www2.eecs.berkeley.edu/Pubs/TechRpts/2019/EECS-2019-3.html)
   * [Two missing links in Serverless Computing: Stateful Computation and Placement Control](https://medium.com/riselab/two-missing-links-in-serverless-computing-stateful-computation-and-placement-control-964c3236d18)
   * A [serverless](https://cloudstate.io) application is one that provides maximum business value over its application lifecycle and one that costs nothing to run when not used, excluding data storage costs.

* **SQL** - [SQL](https://en.wikipedia.org/wiki/SQL), or structured query language, is a domain-specific language developed for managing relational database management systems. It can be used to query, define, and manipulate data within a database as well as their organizational structures. SQL is ubiquitous among relational databases.

* **Stateless & Stateful services** - A definition [Twelve-Factor App -> Processes](https://12factor.net/processes)
  * Service checking availability of items is **stateless** - the data (state) is stored by another backend system.
  * Service like shopping cart is **stateful**, items are stored and retrieved.
  
* [The Reactive Manifesto Glossary](https://www.reactivemanifesto.org/glossary)
