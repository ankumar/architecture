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
---
**Preparing for a future Microservices journey using DDD & Wardley Maps**
[**- Slides**](https://www.slideshare.net/SusanneKaiser3/preparing-for-a-future-microservices-journey-using-ddd-wardley-maps)
[**- Video**](https://www.youtube.com/watch?v=1cnLMuBABo0)
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
* [Microsoft Coyote](https://microsoft.github.io/coyote/)
