## 1. APIs: 
**Design Principles:**
Devs to focus on Business logic, Hiding Distributed systems complexity.
 * [Application Model](https://github.com/oam-dev/spec)
 * Unified API
   * [Declarative/GraphQL](https://reactjs.org/blog/2015/05/01/graphql-introduction.html)  
   * [REST/OpenAPI](https://github.com/OAI/OpenAPI-Specification/)
   * [Event-driven/Asynchronous](https://www.asyncapi.com/)
   * More Styles:
     * RPC-Style, Ex: [Slack's API](https://api.slack.com/web)
 * Services
 
 **There isn't a concrete, well-defined algorithm for [decomposing](https://blog.acolyer.org/2016/09/05/on-the-criteria-to-be-used-in-decomposing-systems-into-modules/) [a system](https://queue.acm.org/detail.cfm?id=3395214) into services. As with much of software development, it's something of an art. If you decompose a system incorrectly, we have a distributed monolith, a system consisting of coupled services that must be deployed together. A distributed monolith has the drawbacks of both the monolithic and the Microservices architectures.** <br/>
   * Stateless - Product Catalog, UGC, ... 
   * Stateful - User Shopping Cart, ...
   * State Management:
     * Data Modeling
     * Purpose-built Databases
 * Developer Experience
   * [Backstage - Spotify Developer Portal](https://labs.spotify.com/2020/04/21/how-we-use-backstage-at-spotify/) 
---     
* **Preparing for a future Microservices journey using DDD & Wardley Maps**
  - [Slides](https://www.slideshare.net/SusanneKaiser3/preparing-for-a-future-microservices-journey-using-ddd-wardley-maps)
  - [Video](https://www.youtube.com/watch?v=1cnLMuBABo0)
 * **Decisions:**
     * [AWS, Amplify](https://aws.amazon.com/amplify/)
     * [GraphQL](https://landscape.graphql.org/) 
     * [Deployment Model](https://github.com/ankumar/Architecture/blob/master/Patterns/Run.md)
     * Databases
       * IN-MEMORY, RELATIONAL, KEY VALUE, DOCUMENT, TIME-SERIES, LEDGER

## 2. Data-Intensive:
### Data powers new innovations, improvements in customer experience, and efficiency. Small advantage in data and algorithms result in increased customers/business success which in turn results in more data. This virtuous cycle due to positive feedback loop amplifies a company's competitive advantage, making data one of the key ingredients in building companies that have Increasing Returns instead of commonly seen Decreasing Returns.

![](https://miro.medium.com/max/1372/1*zOp70MCQ-uhaS7lUVAhATA.png)
<p align="center"> <a href="https://www.itsonlyamodel.com/">"All models are wrong, but some are useful."</a> </p>

### Advances in machine learning (ML) over the last decade have opened up a radically new approach to building software systems. Dubbed [“Software 2.0”](https://medium.com/@karpathy/software-2-0-a64152b37c35), this approach focuses on training models to learn from data instead of explicitly writing code for the required behavior. 
## > a. Data Validation 
## <p align="center"> <b> "In traditional software engineering, or Software 1.0, a program’s functionality is defined via code as dictated by a human. In the age of machine learning, we are increasingly observing Software 2.0 systems, where a program’s functionality is defined by the weights of neural networks as dictated by the data. You wouldn’t trust a piece of human-written code that hasn’t ever been debugged or tested, so why shouldn’t our data receive the same treatment now that it’s a first-class citizen in so many real-world systems?"
Data Quality problem categories:
- Data creation
- Data labelling
- Data manipulation
- Data quality evaluation 

**Examples:**
* [AI for Full-Self Driving](https://www.youtube.com/watch?v=hx7BXih7zx8)

## > b. Software Engineering Practices
![](https://github.com/ankumar/Architecture/blob/master/images/Hidden%20Technical%20Debt%20in%20ML%20Systems.png)
### <p align="center"> [Hidden Technical Debt in Machine Learning Systems](https://papers.nips.cc/paper/5656-hidden-technical-debt-in-machine-learning-systems.pdf) </p>
   
**Examples:**
* [Deep Learning Training Platform](https://determined.ai/developers/)
 
