# Standardize Tech Stack
## One Design Principle: Devs to focus on Business logic, Hiding Distributed systems complexity.

Programs are optimized for managing [cross-cutting concerns](https://dl.acm.org/doi/pdf/10.1145/3190508.3190526) in an intuitive and obvious manner, with feature requirements coded on one axis and common concerns on the other.

Separation of Compute & Storage; Network topology, Authentication, Cloud resource provisioning, Deployment, Logging and Monitoring, Traffic routing, Rate limiting, Staging and Production environments.
 
 Visualize Software, Architecture & Code - [Resilience, A Model "Above the Line, Below the Line"](https://queue.acm.org/detail.cfm?id=3380777)
  
## Metrics
**High Performance System** - How you [Structure & Monitor Measurements](https://www.youtube.com/watch?v=lJ8ydIuPFeU) radically alters what numbers you'll see, and it's extremely counterintuitive if you don't think long & hard.
 1. [User-centric meaningful availability](https://www.usenix.org/system/files/nsdi20spring_hauer_prepub.pdf)
 2. https://web.dev/vitals/

## Security

11 security patterns for microservice architectures - all in one handy guide! 
  * https://developer.okta.com/blog/2020/03/23/microservice-security-patterns

## Virtualization
* Firecracker offers the best of both worlds: the security of hardware-virtualization-based virtual machines and the resource efficiency and fast startup time of containers. Firecracker has been deployed in two publicly available serverless computer services within AWS (Lambda and Fargate), where it supports millions of production workloads, and trillions of requests each month.
  * Paper - https://www.amazon.science/publications/firecracker-lightweight-virtualization-for-serverless-applications
  * Open Source - https://github.com/firecracker-microvm/firecracker

## Kubernetes
The reason why Kubernetes is popular is that it doesn't force you down a single path of getting things done, and it supports more workload types: **crontab, batch jobs, stateless and stateful workloads**. -- [Kelsey Hightower](https://www.infoq.com/podcasts/kubernetes-event-driven-architecture/)

**Topology** - Edge & Cloud Computing

**Manage Planes, [Control & Data](http://brooker.co.za/blog/2019/03/17/control.html)**

* **Scheduler** - Smart Schedulers on top of an orchestrator with tasks encapsulated & labelled
  * [Green Scheduler](https://blog.google/inside-google/infrastructure/data-centers-work-harder-sun-shines-wind-blows/)

* **Service Mesh** - This design pattern combines [data planes & control planes](https://blog.envoyproxy.io/service-mesh-data-plane-vs-control-plane-2774e720f7fc)
  * [GCP, Cloud Run](https://cloud.google.com/run/)

* **Multi-cloud**
  * [Crossplane](https://crossplane.io) - open source universal control plane on which any platform can be built and configured through Kubernetes style APIs;is open source/open governance, supports multiple cloud/infra providers, support application self-servicing, enables a clean separation of concern, and more.
  * AWS [Outposts](https://aws.amazon.com/outposts/)
  * Azure [Stack](https://azure.microsoft.com/en-us/overview/azure-stack/) - Appliance, ...
  * GCP [Anthos](https://inthecloud.withgoogle.com/content-anthos/dl-cd.html) - OSS components, Kubernetes, Istio, Knative, Cloud Run ...

* **Sidecar** - Cross-cutting concerns in a [**sidecar**](https://microservices.io/patterns/deployment/sidecar.html) process or container that runs alongside the service instance
  * [OAM (w/ Alibaba Team), Open Application Model](https://github.com/oam-dev/spec) specification   
  * [DAPR, Distributed Application Runtime](https://dapr.io/)
  * [KEDA, Kubernetes Event-driven Autoscaling](https://keda.sh)
  * [Kubernetes native applications](https://operatorhub.io)
  * [Secure networking](https://www.projectcalico.org)
  * [API Shark, Service Catalog & Call Graph](https://www.cloudvector.com/api-shark/)
  * ...
    
## Manage State

* [Stateful](https://github.com/ankumar/Architecture/blob/master/Patterns/Stateful.md)
  
  
