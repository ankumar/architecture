# Standardized Tech Stack
**Design Principles: Devs to focus on Business logic, Hiding Distributed systems complexity.**

  * Programs are optimized for managing [cross-cutting concerns](https://dl.acm.org/doi/pdf/10.1145/3190508.3190526) in an intuitive and obvious manner, with feature requirements coded on one axis and common concerns on the other.
  * Separation of Compute & Storage; Network topology, Authentication, Cloud resource provisioning, Deployment, Logging and Monitoring, Traffic routing, Rate limiting, Staging and Production environments.
  * Visualize Software, Architecture & Code - [Resilience - Above the Line, Below the Line](https://queue.acm.org/detail.cfm?id=3380777)
  
## Metrics
**High Performance System** - How you [Structure & Monitor Measurements](https://www.youtube.com/watch?v=lJ8ydIuPFeU) radically alters what numbers you'll see, and it's extremely counterintuitive if you don't think long & hard, A Sample:

Service that always responds in 100ms, except for 5 minutes of every hour where it stalls completely(TCP connection and HTTP request will be accepted, but the response will be provided at the end of the 5 minute stall). If a serial client (i.e. it sends a request, waits for it to finish, sends next) is monitoring latency, what 99th percentile does it measure? 

**- About 300s**

Same service, but with a client sending requests every 1s whether the last one has completed or not. What 99th percentile latency does it see? 

**- About 110ms**

Same service, serial client with a 1s request timeout. What 99th percentile latency does it measure? 

**- About 1s**

 1. [User-centric meaningful availability](https://www.usenix.org/system/files/nsdi20spring_hauer_prepub.pdf)
 2. https://web.dev/vitals/
  
## Framework

### Data Modeling

</>

## Kubernetes:

**1.Manage - Planes, [Control & Data](http://brooker.co.za/blog/2019/03/17/control.html):**

* **Service Mesh** - This design pattern combines [data planes & control planes](https://blog.envoyproxy.io/service-mesh-data-plane-vs-control-plane-2774e720f7fc)
  * [GCP, Cloud Run](https://cloud.google.com/run/)
  * https://crossplane.io - is a universal control plane on which any platform can be built and configured through Kubernetes style APIs;is open source/open governance, supports multiple cloud/infra providers, support application self-servicing, enables a clean separation of concern, and more.

* **Sidecar** - Cross-cutting concerns in a [**sidecar**](https://microservices.io/patterns/deployment/sidecar.html) process or container that runs alongside the service instance
  * [OAM (w/ Alibaba Team), Open Application Model](https://github.com/oam-dev/spec) specification   
  * [DAPR, Distributed Application Runtime](https://dapr.io/)
  * [KEDA, Kubernetes Event-driven Autoscaling](https://keda.sh)
  * [Kubernetes native applications](https://operatorhub.io)
  * [Secure networking](https://www.projectcalico.org)
  * [API Shark, Service Catalog & Call Graph](https://www.cloudvector.com/api-shark/)
  * ...
  
**2.Manage - State**
  * [Stateful](https://github.com/ankumar/Architecture/blob/master/Patterns/Stateful.md)
  
**3.Manage - Scheduling (Smart Schedulers on top of an orchestrator with tasks encapsulated & labelled)**
* [Green Scheduler](https://blog.google/inside-google/infrastructure/data-centers-work-harder-sun-shines-wind-blows/)

**4.Manage - Hybrid:**
* Azure [Stack](https://azure.microsoft.com/en-us/overview/azure-stack/) - Appliance, ...
* GCP [Anthos](https://inthecloud.withgoogle.com/content-anthos/dl-cd.html) - OSS components, Kubernetes, Istio, Knative, Cloud Run ...
