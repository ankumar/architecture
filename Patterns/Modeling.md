# Design
"Good design means then when I make a change, it’s as if the entire program was crafted in anticipation of it. I can solve a task with just a few choice function calls that slot in perfectly, leaving not the slightest ripple on the placid surface of the code."  -- [Game Programming Patterns](https://gameprogrammingpatterns.com/contents.html)

The definition of design itself is quite interesting: 
- That kind of intellectual activity which creates a whole from its diverse parts may be called the design of a system.

Thinking about design, we more naturally think about it the other way around: how to decompose the whole into a set of parts that will work together to accomplish the system goals. Of course, parts do have to fit together to produce the intended whole again.
Two bits of knowledge are needed at the beginning of the design process:
* An (initial) understanding of the system boundaries (and any boundaries on the design and development process too)—what's in scope and what's out of scope.
* A preliminary notion of how the system will be organized. Without this, you can't begin to break down the design work. [1]

# Blueprints

* A Model - ["Above the Line, Below the Line"](https://queue.acm.org/detail.cfm?id=3380777)
  * [C4 Model](https://c4model.com/)
  * [The “4+1” View Model of Software Architecture](https://www.cs.ubc.ca/~gregor/teaching/papers/4+1view-architecture.pdf)

# Boundaries - Balancing Coupling in Distributed Systems

Services should be organized around Business concepts, a.k.a. Business capabilities or DDD subdomains/bounded contexts. Their names and responsibilities should reflect the Business [2][4][5]

* Stateless - Product Catalog, UGC, ... 
* Stateful - User Shopping Cart, ...

## API  - "APIs are forever, code is not..." - [Mike Amundsen](http://amundsen.com/blog/) ; API Governance [3]
## Data Modeling
* NoSQL - Designing denormalized data models is way harder than RDBMS, it's also a completely different mental model. The shift is hard ...
* Relational -  Common Patterns [6]

---

1. https://queue.acm.org/detail.cfm?id=3395214
2. https://vladikk.com/2020/04/09/untangling-microservices/
3. [The challenge is how to mix decision elements within a team or set of teams to optimize effectiveness without slowing down production](https://blogs.mulesoft.com/dev/management-dev/improve-api-governance-with-distributed-decision-making/)
4. https://speakerdeck.com/vladikk/balancing-coupling-in-distributed-systems
5. https://microservices.io/patterns/decomposition/decompose-by-business-capability.html
     * https://microservices.io/patterns/decomposition/decompose-by-subdomain.html
6. [Things More Developers Knew About Databases](https://medium.com/@rakyll/things-i-wished-more-developers-knew-about-databases-2d0178464f78)
     * [NoSQL](https://www.dynamodbguide.com/what-is-dynamo-db)
     * [Relational: MySQL - FB, UBER, Quora, ...](https://www.quora.com/q/quoraengineering/MySQL-sharding-at-Quora)
       * Sharding (Vertical / Horizontal)
       * No JOINS policy in code
       * API based queries on Database
       * Discouraged use of SQL in code
       * Metadata (hosts, shards etc) Like in Zookeeper 
