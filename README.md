<font size="16">
 
# Modern Application Development
**"If we have a system of improvement that’s directed at improving the parts taken separately, you can be absolutely sure that the performance of the whole will not be improved. The performance of a system depends on how the parts fit, not how they act taken separately.” -Dr. Russell Ackoff.**

# Well-Architected
Architecture is about [Systems Thinking](https://www.youtube.com/watch?v=OqEeIG8aPPk) including People, Process and Technology; synthesis of multiple perspectives, including social dynamics, domain-driven design, business models, and software architecture. It's not about code, and it's not a synonym for "software architecture". 

**"[Software Patterns](https://github.com/ankumar/Architecture/blob/master/Patterns/Stuff.md) aren't prescriptive rules that say do this because it works. They say this has worked in many cases, Try it and see if it works for you."**

# Services
* Designing Modularity & Interfaces
* Decomposing an Application into Services & APIs

![](https://github.com/ankumar/Architecture/blob/master/images/Microservices1.jpg)

[Microservices](https://www.youtube.com/watch?v=wgdBVIX9ifA) - also known as the microservice architecture - is an architectural style that structures an application as a collection of services that are

1. Highly maintainable & testable
2. Loosely coupled
3. Independently deployable
4. Organized around business capabilities
5. Owned by a small team

There isn't a concrete, well-defined algorithm for decomposing a system into services. As with much of software development, it's something of an art. If you decompose a system incorrectly, we have a distributed monolith, a system consisting of coupled services that must be deployed together. A distributed monolith has the drawbacks of both the monolithic and the Microservices architectures.

![](https://images.ctfassets.net/ro61k101ee59/2bmS9TVlJc5einK9YLBY3V/992367961e649dd0343a3486616601fd/Image-1.png?w=1348&q=90)
<p align="center"> <a href="https://monzo.com/blog/we-built-network-isolation-for-1-500-services">FinTech, Monzo: 1,500+ services</a> </p>

# Data-Intensive
Data powers new innovations, improvements in customer experience, and efficiency. Small advantage in data and algorithms result in increased customers/business success which in turn results in more data. This virtuous cycle due to positive feedback loop amplifies a company's competitive advantage, making data one of the key ingredients in building companies that have Increasing Returns instead of commonly seen Decreasing Returns.

![AI powered Monopolies](https://miro.medium.com/max/1372/1*zOp70MCQ-uhaS7lUVAhATA.png)

While data is an important starting point, for data to be useful, it should be turned to Information.
Data - Raw, unorganized facts about something
Information - Data/Facts that is structured, organized, and presented with context
Knowledge - Understanding of Information with experience and intuition
For data to be useful, every company must be able to turn data into information, and eventually into knowledge. Knowledge empowers understanding and decisions.
What are the factors that is driving data today?
1. Accessibility to scalable infra and platform
2. Awareness of importance of data
3. Machine Learning on the rise
4. Modeling physical world in real-time
What is the problem with data today?

Problem #1 - Spending the time on wrong things
![](https://github.com/ankumar/Architecture/blob/master/images/data-intensive1.png)

Problem #2 - Data is not designed and collected systematically

Problem #3 - Companies have lots of data but not information

Problem #4 - Data and data assets are not discoverable

Problem #5 - Tools are not addressing complexity

Problem #6 - It is not tools and technology but people and processes

# Cloud Computing - Developer Productivity

|[Characteristics](https://nvlpubs.nist.gov/nistpubs/Legacy/SP/nistspecialpublication800-145.pdf)| |
|------------------------| ---------------------------------------------------------------------------------------------|
| **On-demand self-service** | A consumer can unilaterally provision computing capabilities, such as server time and network storage, as needed automatically without requiring human interaction |
|**Broad network access**|Capabilities are available over the network and accessed through standard mechanisms|
|**Resource pooling**|The provider’s computing resources are pooled to serve multiple consumers using a multi-tenant model, with different physical and virtual resources dynamically|
|**Rapid elasticity**|Capabilities can be elastically provisioned and released to scale rapidly outward and inward with demand|
|**Measured service**|Cloud systems automatically control and optimize resource use by leveraging a metering capability (typically per-per-use)|

[![Service Mesh](https://github.com/ankumar/Architecture/blob/master/images/Istio2.png)](https://www.youtube.com/watch?v=do-PrVi0ifk "Eric Brewer, VP Infrastructure & Google Fellow")
<p align="center">Google: 100,000+ services</p>

</font>

