# distributed systems architecture for Highly Autonomous Systems

As a strategy formulation, we are trying to change a **situation A** into a better **situation B**. This process might end in the real world, but it starts in our imaginations, in the virtual world. This is a straw man proposal of such a virtual world to aid in decision making for design, develop, and deploy model of **Business Applications** backed by an **IoT Cloud Platform**. The imaginations will be refined over time after feedback, deeper understanding of real world.

![](https://info.container-solutions.com/hs-fs/hubfs/The%20strategist.png)

https://github.com/lf-edge

* https://www.infoq.com/presentations/linux-eve/ 
* https://www.lfedge.org/wp-content/uploads/2020/07/LF-Edge-web-july2020.pdf

https://iot.eclipse.org/

* DSL - https://vorto.eclipse.org/
* IoT GW - https://www.eclipse.org/hono/
* Microservices framework - https://iofog.org/
* Microservices - https://www.eclipse.org/ditto/
  * Policies - persistence of Policies
  * Things - persistence of Things and Features
  * Thing-Search - tracking changes to Things, Features, Policies and updating an optimized search index + executes queries on this search index
  * Gateway - provides HTTP and WebSocket API
  * Connectivity - connects to AMQP 1.0 (e.g. Eclipse Hono) and AMQP 0.9.1 endpoints and consumes messages in Ditto Protocol from it, optionally converts other formats to Ditto Protocol
  * Concierge - orchestrates the backing persistence services (including authorization)

