# Software Engineering:

* [Margaret Hamilton - Apollo project (1969)](https://www.youtube.com/watch?v=ZbVOF0Uk5lU)
* [Software Art Thou: Glenn Vanderburg - Real Software Engineering](https://www.youtube.com/watch?time_continue=177&v=RhdlBHHimeM)
* [Building projects despite (and because of) existing complex systems](https://queue.acm.org/detail.cfm?id=3390746)
* [How Did Software Get So Reliable Without Proof? ](https://www.gwern.net/docs/math/1996-hoare.pdf)

# Design & Architecture:

## Developer Experience:
</>

[>_](https://github.com/ankumar/Architecture/blob/master/Patterns/Developer%20Experience.md)

## Services:
- "APIs are forever, code is not..." - Mike Amundsen
    * [GraphQL](https://reactjs.org/blog/2015/05/01/graphql-introduction.html)
    * REST, gRPC, ...
    * [OpenAPI](https://www.openapis.org/)
    * [AsyncAPI](https://www.asyncapi.com/)
    * RPC-Style, Ex: [Slack's API](https://api.slack.com/web)
    
- Services: 
    * Stateless - Product Catalog, UGC, ...
    * Stateful - User Shopping Cart, Inventory, ...
- State, Purpose-built Databases: IN-MEMORY, RELATIONAL, KEY VALUE, DOCUMENT, TIME-SERIES, LEDGER

[>_](https://github.com/ankumar/Architecture/blob/master/Patterns/Services.md)

## Data-Intensive:
</>

[>_](https://github.com/ankumar/Architecture/blob/master/Patterns/Data-Intensive.md)
  
## Cloud Computing:
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


[>_](https://github.com/ankumar/Architecture/blob/master/Patterns/Cloud%20Computing.md)
 
## Open Source:
</>

[>_](https://github.com/ankumar/Architecture/blob/master/Patterns/Open%20Source.md)

## Ops:
</>

[>_](https://github.com/ankumar/Architecture/blob/master/Patterns/Ops.md)

# Systems Thinking:
</>

[>_](https://github.com/ankumar/Architecture/blob/master/Patterns/%20Systems%20Thinking.md)


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
## Stanford
 * [Value of Data and AI](https://canvas.stanford.edu/courses/114221)
 * [Principles of Data-Intensive Systems](http://web.stanford.edu/class/cs245/) 
 * [Knowledge Graphs](https://web.stanford.edu/class/cs520/)
