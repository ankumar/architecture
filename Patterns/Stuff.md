# "Sandbox" for sharing & collaborating
**Online Hipster Shop** - Services, Stateless & Stateful
* "Stateless"
    * [Distributed Microservices / GCP](https://github.com/GoogleCloudPlatform/microservices-demo)
    * [Distributed SQL / YugabyteDB](https://blog.yugabyte.com/cloud-native-meets-distributed-sql-bringing-microservices-kubernetes-istio-yugabytedb-together-with-hipster-shop-demo/)
* "Stateful"
    * Business Flows (beyond a single request/reply)

**Learning Systems** - Business, Infrastructure engineers, data engineers, and data scientists to seamlessly collaborate. 
* [NVIDIA](https://www.youtube.com/watch?v=3mkRyBkS5zE) - [For use cases, Covariant](https://covariant.ai/solutions)

## 1. Software-Intensive:
**Services -** 
There isn't a concrete, well-defined algorithm for [decomposing](https://blog.acolyer.org/2016/09/05/on-the-criteria-to-be-used-in-decomposing-systems-into-modules/) [a system](https://queue.acm.org/detail.cfm?id=3395214) into [services](Modeling.md). As with much of software development, it's something of an art. If you decompose a system incorrectly, we have a distributed monolith, a system consisting of coupled services that must be deployed together. A distributed monolith has the drawbacks of both the monolithic and the Microservices architectures.

 * **Design Heuristics**
   * [Domain-Driven](https://www.dddheuristics.com/)
  
 * **API**
   * [Declarative/GraphQL](https://github.com/ankumar/Architecture/blob/master/Patterns/GraphQL.md)  
   * [REST/OpenAPI](https://github.com/OAI/OpenAPI-Specification/)
   * More Styles:
     * RPC-Style, Ex: [Slack's API](https://api.slack.com/web)
   * [Event-driven/Async](https://www.asyncapi.com/)
   * [Span Multiple Requests/Workflow](https://cadenceworkflow.io/)
   * [RPC & REST](https://cloud.google.com/blog/products/api-management/understanding-grpc-openapi-and-rest-and-when-to-use-them)
   
   * [Unified/Multi-Model](http://www.mm-adt.org/)
  
 * **Tools**
    * **Customized Workflows** 
      * [Developer Portal/Backstage - Spotify](https://labs.spotify.com/2020/04/21/how-we-use-backstage-at-spotify/)
      * [Deployment Model](Run.md)
    * **Remote backed by Cloud**
      * [GitHub - Codespaces](https://github.com/features/codespaces)
      * [GCP - Cloud Shell](https://cloud.google.com/blog/products/gcp/introducing-google-cloud-shels-new-code-editor)
      * [AWS - Cloud9](https://aws.amazon.com/cloud9/)
    
## 2. Data-Intensive:
Data powers new innovations, improvements in customer experience, and efficiency. Small advantage in data and algorithms result in increased customers/business success which in turn results in more data. This virtuous cycle due to positive feedback loop amplifies a company's competitive advantage, making data one of the key ingredients in building companies that have Increasing Returns instead of commonly seen Decreasing Returns.

![](https://miro.medium.com/max/1372/1*zOp70MCQ-uhaS7lUVAhATA.png)

<p> <a href="https://www.itsonlyamodel.com/">"All models are wrong, but some are useful."</a> </p>

### Advances in machine learning (ML) over the last decade have opened up a radically new approach to building software systems. Dubbed [“Software 2.0”](https://medium.com/@karpathy/software-2-0-a64152b37c35), this approach focuses on training models to learn from data instead of explicitly writing code for the required behavior. 
## > a. Data Validation
<p align="center"> <b> "In traditional software engineering, or Software 1.0, a program’s functionality is defined via code as dictated by a human. In the age of machine learning, we are increasingly observing Software 2.0 systems, where a program’s functionality is defined by the weights of neural networks as dictated by the data. You wouldn’t trust a piece of human-written code that hasn’t ever been debugged or tested, so why shouldn’t our data receive the same treatment now that it’s a first-class citizen in so many real-world systems?"

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
* [Determined: The Open Source Deep Learning Training Platform](https://determined.ai/developers/)

The goal of the platform is to enable Deep Learning Engineers to focus more of their time and energy on their ultimate goal — training high-quality models. They achieve this by tightly integrating all of the functionality DL Engineers need to train models at scale, including:
- High-performance distributed training that just works
- State-of-the-art hyperparameter search
- Experiment management with experiment tracking, log management, metrics visualization, reproducibility, and dependency management
- Flexibility - a fully open source system that supports both Tensorflow and PyTorch, and can run in the cloud or on-prem

* [Return to the Edge & the End of Cloud Computing](https://www.youtube.com/watch?v=4QTAtFaIiyc)


---


Glossary - https://github.com/ankumar/Architecture/blob/master/Patterns/Terminology.md
