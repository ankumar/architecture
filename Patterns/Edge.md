# distributed systems architecture for Highly Autonomous Systems

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

