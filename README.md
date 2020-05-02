# Platform & Applications

## Platform is a perspective, Serving our customers;Tools, APIs, Analytics, Artificial Intelligence, Machine Learning, ... 
> "Platform” with a standardized interface allowing decentralized development.

> Programs built with it are “continually valid and observable from the very beginning of its construction”.
### > [Pattern - Tools, People front and center](https://twitter.com/conways_law/status/1238539198203822081)
[1. Spotify Developer Portal](https://labs.spotify.com/2020/04/21/how-we-use-backstage-at-spotify/)

[2. Holistic approach - Dark](https://medium.com/darklang/the-design-of-dark-59f5d38e52d2)

[3. Write nothing; Deploy nowhere! - Low code/no code](https://twitter.com/kelseyhightower/status/961026365146320896)

### > [Pattern - Technology & Business w/ Amazon CTO Werner Vogels](https://queue.acm.org/detail.cfm?id=1142065)
**A Customer centric Journey Growing Business starting from eCommerce -> Cloud -> AI -> Health -> Open Source ...**

![](https://github.com/ankumar/Architecture/blob/master/images/Werner.png)
Hi Werner, I was wondering... what advice would you offer to somebody who'd like to be a CTO someday? Especially for the younger folks, what should one know or how should one prepare themselves for their future? Appreciate you taking the time to read this.

in one tweet? 1) if you want to be a VP of Engineering focus on teams and people and how to make them succesfull 2) wanna be a CTO? Simplify.  Focus on the business, what is the simplest, most robust Tech/Ops that makes the business succeed.

### > [Patterns](https://github.com/ankumar/Architecture/blob/master/Patterns/Stuff.md)

## 1. Modeling Services
[![Service Mesh](https://github.com/ankumar/Architecture/blob/master/images/Istio2.png)](https://www.youtube.com/watch?v=do-PrVi0ifk "Eric Brewer, VP Infrastructure & Google Fellow")<p align="center">
 <b>Google: 100,000+ services - Networking In & Across Regions </b></p>
 
![](https://images.ctfassets.net/ro61k101ee59/2bmS9TVlJc5einK9YLBY3V/992367961e649dd0343a3486616601fd/Image-1.png?w=1348&q=90)
<p align="center"> <a href="https://monzo.com/blog/we-built-network-isolation-for-1-500-services">A Modern App, Monzo Bank: 1,600+ services - A visualisation of network of microservices w/ Strong DevOps & Observability</a> </p>
 
## > 1. Devs to focus on Business logic, Hiding Distributed systems complexity
**There isn't a concrete, well-defined algorithm for [decomposing](https://blog.acolyer.org/2016/09/05/on-the-criteria-to-be-used-in-decomposing-systems-into-modules/) a system into services. As with much of software development, it's something of an art. If you decompose a system incorrectly, we have a distributed monolith, a system consisting of coupled services that must be deployed together. A distributed monolith has the drawbacks of both the monolithic and the Microservices architectures.** <br/>

* Preparing for a future Microservices journey using DDD & Wardley Maps
  - [Slides](https://www.slideshare.net/SusanneKaiser3/preparing-for-a-future-microservices-journey-using-ddd-wardley-maps)
  - [Video](https://www.youtube.com/watch?v=1cnLMuBABo0)

**Examples:**
* [GCP Cloud Run- Run stateless containers on a fully managed environment](https://cloud.google.com/run/)

## 2. Modeling Business 
### Data powers new innovations, improvements in customer experience, and efficiency. Small advantage in data and algorithms result in increased customers/business success which in turn results in more data. This virtuous cycle due to positive feedback loop amplifies a company's competitive advantage, making data one of the key ingredients in building companies that have Increasing Returns instead of commonly seen Decreasing Returns.

![](https://miro.medium.com/max/1372/1*zOp70MCQ-uhaS7lUVAhATA.png)
<p align="center"> <a href="https://www.itsonlyamodel.com/">"All models are wrong, but some are useful."</a> </p>

### Advances in machine learning (ML) over the last decade have opened up a radically new approach to building software systems. Dubbed [“Software 2.0”](https://medium.com/@karpathy/software-2-0-a64152b37c35), this approach focuses on training models to learn from data instead of explicitly writing code for the required behavior. 
## > 1. Data Validation 
## <p align="center"> <b> "In traditional software engineering, or Software 1.0, a program’s functionality is defined via code as dictated by a human. In the age of machine learning, we are increasingly observing Software 2.0 systems, where a program’s functionality is defined by the weights of neural networks as dictated by the data. You wouldn’t trust a piece of human-written code that hasn’t ever been debugged or tested, so why shouldn’t our data receive the same treatment now that it’s a first-class citizen in so many real-world systems?"
Data Quality problem categories:
- Data creation
- Data labelling
- Data manipulation
- Data quality evaluation 

**Examples:**
* [AI for Full-Self Driving](https://www.youtube.com/watch?v=hx7BXih7zx8)

## > 2. Software Engineering Practices:
![](https://github.com/ankumar/Architecture/blob/master/images/Hidden%20Technical%20Debt%20in%20ML%20Systems.png)
### <p align="center"> [Hidden Technical Debt in Machine Learning Systems](https://papers.nips.cc/paper/5656-hidden-technical-debt-in-machine-learning-systems.pdf) </p>
