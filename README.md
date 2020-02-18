<font size="16">
 
# Modern Application Development

# Architecture
Architecture is about Systems Thinking including People, Process and Technology; synthesis of multiple perspectives, including social dynamics, domain-driven design, business models, and software architecture. It's not about code, and it's not a synonym for "software architecture". 

[![Systems Thinking](https://github.com/ankumar/Architecture/blob/master/images/Russell%20Ackoff.png)](https://www.youtube.com/watch?v=OqEeIG8aPPk "Dr. Russell Ackoff")
<p align="center"><b>Systems Thinking: "If we have a system of improvement that’s directed at improving the parts taken separately, you can be absolutely sure that the performance of the whole will not be improved. The performance of a system depends on how the parts fit, not how they act taken separately.”</b></p>
<p align="right"><b>-Dr. Russell Ackoff.</b></p>

![](https://github.com/ankumar/Architecture/blob/master/images/wardley.jpeg)
* **Enabling Business to Focus on core value vs plumbing:**
  1. **Work backwards from Customer/Business outcomes**
  2. **Build closed loop systems to optimize for continual Improvements & Learning**
  3. **Technology Commoditization**
* **Technology needs to be embedded in the Business not external to it or merely aligned with it**  

# Services
* Designing Modularity & Interfaces
* Decomposing an Application into Services & APIs

![](https://github.com/ankumar/Architecture/blob/master/images/Microservices1.jpg)

[Microservices](https://www.youtube.com/watch?v=wgdBVIX9ifA) - also known as the microservice architecture - is an architectural style that structures an application as a collection of services that are

**1. Highly maintainable & testable**

**2. Loosely coupled**

**3. Independently deployable**

**4. Organized around business capabilities**

**5. Owned by a small team**
![](https://images.ctfassets.net/ro61k101ee59/2bmS9TVlJc5einK9YLBY3V/992367961e649dd0343a3486616601fd/Image-1.png?w=1348&q=90)
<p align="center"> <a href="https://monzo.com/blog/we-built-network-isolation-for-1-500-services">FinTech, Monzo: 1,500+ services</a> </p>

**There isn't a concrete, well-defined algorithm for decomposing a system into services. As with much of software development, it's something of an art. If you decompose a system incorrectly, we have a distributed monolith, a system consisting of coupled services that must be deployed together. A distributed monolith has the drawbacks of both the monolithic and the Microservices architectures.**

# Software 2.0
Data powers new innovations, improvements in customer experience, and efficiency. Small advantage in data and algorithms result in increased customers/business success which in turn results in more data. This virtuous cycle due to positive feedback loop amplifies a company's competitive advantage, making data one of the key ingredients in building companies that have Increasing Returns instead of commonly seen Decreasing Returns.

![AI powered Monopolies](https://miro.medium.com/max/1372/1*zOp70MCQ-uhaS7lUVAhATA.png)

Advances in machine learning (ML) over the last decade have opened up a radically new approach to building software systems. Dubbed [“Software 2.0”](https://medium.com/@karpathy/software-2-0-a64152b37c35), this approach focuses on training models to learn from data instead of explicitly writing code for the required behavior. 

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

**Problem #1 - Spending the time on wrong things**
![](https://github.com/ankumar/Architecture/blob/master/images/data-intensive1.png)

**Problem #2 - Data is not designed and collected systematically**

**Problem #3 - Companies have lots of data but not information**

**Problem #4 - Data and data assets are not discoverable**

**Problem #5 - Tools are not addressing complexity**

**Problem #6 - It is not tools and technology but people and processes**

<p align="center"> <b> "In traditional software engineering, or Software 1.0, a program’s functionality is defined via code as dictated by a human. In the age of machine learning, we are increasingly observing Software 2.0 systems, where a program’s functionality is defined by the weights of neural networks as dictated by the data. You wouldn’t trust a piece of human-written code that hasn’t ever been debugged or tested, so why shouldn’t our data receive the same treatment now that it’s a first-class citizen in so many real-world systems?" </b> </p>

# Cloud Computing

|[Characteristics](https://nvlpubs.nist.gov/nistpubs/Legacy/SP/nistspecialpublication800-145.pdf)|Developer Productivity|
|------------------------| ---------------------------------------------------------------------------------------------|
| **On-demand self-service** | A consumer can unilaterally provision computing capabilities, such as server time and network storage, as needed automatically without requiring human interaction |
|**Broad network access**|Capabilities are available over the network and accessed through standard mechanisms|
|**Resource pooling**|The provider’s computing resources are pooled to serve multiple consumers using a multi-tenant model, with different physical and virtual resources dynamically|
|**Rapid elasticity**|Capabilities can be elastically provisioned and released to scale rapidly outward and inward with demand|
|**Measured service**|Cloud systems automatically control and optimize resource use by leveraging a metering capability (typically per-per-use)|

# Open Source
* Open [Governance](https://github.com/cncf/toc/), Stewardship & [Principles](https://github.com/cncf/toc/blob/master/PRINCIPLES.md#toc-operating-principles)
![](https://github.com/ankumar/Architecture/blob/master/images/CNCF.png)
<p align="center"><b>Cloud would not have been possible without open source</b></p>

* Community & Company Driven [Projects](https://www.linuxfoundation.org/projects/)

[![It's not a race if we're all on the same team](https://github.com/ankumar/Architecture/blob/master/images/Kelsey%20Hightower.png)](https://www.youtube.com/watch?v=jiaLsxjBeOQ "Kelsey Hightower, Staff Developer Advocate, Google")
<p align="center"><b>Community - "It's not a race if we're all on the same team"</b></p>

* <span style="color: red;"><b>"[Patterns](https://github.com/ankumar/Architecture/blob/master/Patterns/Stuff.md) aren't prescriptive rules that say do this because it works. They say this has worked in many cases, Try it and see if it works for you."</b>
</span>

<p align="center"><b>"I think the "new model" is a big increase in end user corporations contributing to and producing their own open source projects. That's where the resources are coming from, and it's part of the success of Netflix, Capital One, Lyft, Airbnb that is spreading.”</b></p>
<p align="right"><b>-Adrian Cockcroft</b></p>

</font>

