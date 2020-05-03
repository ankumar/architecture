# Terminology:
* [**Architecture Decision Records (ADR's)**](https://engineering.walmart.com/adrs) 
* [**Conway's Law**](http://www.melconway.com/Home/Conways_Law.html) - How to Organize Organization for Optimal Development / "Shipping the Org Chart",  Pay the cost later in internal tools & stitching data together
* **Cloud Native** - Cloud native technologies empower organizations to build and run scalable applications in modern, dynamic environments such as public, private, and hybrid clouds. **Containers, service meshes, microservices, immutable infrastructure, and declarative APIs** exemplify this approach. These techniques enable loosely coupled systems that are resilient, manageable, and observable. Combined with robust automation, they allow engineers to make high-impact changes frequently and predictably with minimal toil.

* **Inner Source** - Global & Local dichotomy, Open source best practices within organization
* **Cell-Based Architecture** - System Availability & Minimize the **"blast radius"** of any failures
   * [**Cell-Based Architecture**](https://github.com/wso2/reference-architecture/blob/master/reference-architecture-cell-based.md)
   * [**Control vs Data plane**](http://www.cs.cmu.edu/~4D/papers/greenberg-ccr05.pdf)
   * [**Shopify Journey**](https://engineering.shopify.com/blogs/engineering/e-commerce-at-scale-inside-shopifys-tech-stack)
* **Application & Microservices** - https://martinfowler.com/articles/microservices.html
   * Ex: [Demo App - Hipster Shop](https://github.com/GoogleCloudPlatform/microservices-demo)
* **Stateless & Stateful services** - A definition [Twelve-Factor App -> Processes](https://12factor.net/processes)
   * Service checking availability of items is **stateless** - the data (state) is stored by another backend system.
   * Service like shopping cart is **stateful**, items are stored and retrieved.
* **Hybrid** - An Architecture where we use a public cloud provider in combination with private, own data center.
* [**Enterprise**](https://learning.oreilly.com/library/view/lean-enterprise/9781491946527/) - Single Metric, Measure **Time to Value** everywhere
   * **Governance**
     * [**Cloud**](https://aws.amazon.com/blogs/enterprise-strategy/governance-in-the-cloud-and-in-the-digital-age-part-one/)
   * **Business Continuity**
     * [**COVID19 Context**](https://azure.microsoft.com/en-us/blog/update-3-business-continuity-azure/)

