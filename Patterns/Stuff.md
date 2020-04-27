# The list here is not meant to be comprehensive, hopefully macro environments ...

# Software Engineering:

* [Margaret Hamilton - Apollo project (1969)](https://www.youtube.com/watch?v=ZbVOF0Uk5lU)
* [Software Art Thou: Glenn Vanderburg - Real Software Engineering](https://www.youtube.com/watch?time_continue=177&v=RhdlBHHimeM)
* [Building projects despite (and because of) existing complex systems](https://queue.acm.org/detail.cfm?id=3390746)
* [How Did Software Get So Reliable Without Proof? ](https://www.gwern.net/docs/math/1996-hoare.pdf)

# Developer Experience:
> [](https://github.com/ankumar/Architecture/blob/master/Patterns/Developer%20Experience.md)

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
