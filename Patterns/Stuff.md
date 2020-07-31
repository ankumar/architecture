# Design Heuristics
![](../images/Return-to-the-Edge-–-End-of-Cloud-Computing.008.jpeg)
["I'm going to take you out to the edge to show you what the future looks like"](https://a16z.com/2019/11/15/the-end-of-cloud-computing-2/)
-- Peter Levine, general partner at Andreessen Horowitz

In 1967, Melvin Conway coined a phrase at the end of his publication [‘How do committees invent?’](http://www.melconway.com/Home/pdf/committees.pdf) that was subsequently made popular by **Fred Brooks** in his book **The Mythical Man-Month**, where he dubbed it 'Conway’s Law', which states **"Organizations which design systems are constrained to produce designs which are copies of the communication structures of these organizations."**

<p align="center">
  <img src="../images/Conway's%20Law.jpeg"/>
</p>

**Although this is not a scientific law, it is a valid proposition for many environments. Many organizations have become adept at identifying what they need from software development projects, based on a keen understanding of their business goals. Even so, they’re often surprised to find out that the end results don’t achieve the transformative impact they were expecting. Their mistake? Overlooking the importance of Conway’s Law.** [We often see its effects in our workplace and in other companies that develop software](https://www.thoughtworks.com/insights/blog/applying-conways-law-improve-your-software-development).

* [Six Decades of Software Engineering By Mary Poppendieck](https://www.meetup.com/DevOps-Lisbon/events/271172214/) / https://www.youtube.com/watch?v=PzI07SBqaPA

* ![](../images/Six%20Decades%20of%20SoftwareEngineering.png)
<p align="center"> <b> No engineering process can replace the philosophy of responsibility. </b> </p> 

In the context of [Software Is Eating the World](https://a16z.com/2011/08/20/why-software-is-eating-the-world/) & [The Future of Software Engineering in the Cloud](https://www.youtube.com/watch?v=6K4ljFZWgW8), Businesses across Retail, Finance, Health, Education, Manufacturing & Goverment are “modernizing” infrastructure, application layer around Cloud Native stack, some retiring on-premises data centers. The architecture is being developed in a vendor neutral & open governance model driven by open source communities under [Cloud Native Computing Foundation](https://www.cncf.io/) & other [organizations](https://opensource.com/resources/organizations).

[Per Cloud Native Landscape](https://github.com/cncf/landscape), a definition ...

Cloud native technologies empower organizations to build and run scalable applications in modern, dynamic environments such as public, private, and hybrid clouds. ***Containers, service meshes, microservices, immutable infrastructure, and declarative APIs exemplify this approach.***

***These techniques enable loosely coupled systems that are resilient, manageable, and observable. Combined with robust automation, they allow engineers to make high-impact changes frequently and predictably with minimal toil.***

The Cloud Native Computing Foundation seeks to drive adoption of this paradigm by fostering and sustaining an ecosystem of open source, vendor-neutral projects. We democratize state-of-the-art patterns to make these innovations accessible for everyone.

##
![](../images/Cloud%20Native%20Architecture.png)
**Development + Security + Finance + Operations**
* Many Teams, each working on different areas of the Product
* Teams need to control their own development, deployment, and scale
* Without having to co-ordinate their changes with other teams
* Development process needs to be distributed and decoupled just like our software

Additional Considerations being mindful of **Flow**, breaking down dependencies & silos, keeping costs under control & the focus on delivering business value. 
Let's look at some interesting [System design principles](Design%20Patterns.md), Implementations of **Mobile, Web & Edge** [Applications](https://martinfowler.com/bliki/ApplicationBoundary.html), **Application Programming Interfaces (APIs)**, span from single to multiple request/response using **Workflows** & **Integrations**.

* [API Applications](../System/API.md)  
* [Workflows & Integrations](Workflows.md)

-> [Sandbox](../Labs/Sandbox.md) to evaluate [components](https://martinfowler.com/articles/microservices.html#ComponentizationViaServices) & compositions


