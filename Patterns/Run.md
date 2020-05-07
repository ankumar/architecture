# The Stack
  
## Metrics
High Performance System - How you [Structure & Monitor Measurements](https://www.youtube.com/watch?v=lJ8ydIuPFeU) radically alters what numbers you'll see, and it's extremely counterintuitive if you don't think long & hard, A Sample:

Service that always responds in 100ms, except for 5 minutes of every hour where it stalls completely(TCP connection and HTTP request will be accepted, but the response will be provided at the end of the 5 minute stall). If a serial client (i.e. it sends a request, waits for it to finish, sends next) is monitoring latency, what 99th percentile does it measure?
**- About 300s**

Same service, but with a client sending requests every 1s whether the last one has completed or not. What 99th percentile latency does it see?
**- About 110ms**

Same service, serial client with a 1s request timeout. What 99th percentile latency does it measure?
**- About 1s**

  * https://web.dev/vitals/
  
## Framework  
  * [AWS, Amplify](https://aws.amazon.com/amplify/)
  * [GraphQL](https://landscape.graphql.org/)
  * Purpose-built Databases - "It wasn't that long ago when the DBAs owned THE shared database. Nowadays, in all kinds of companies, no one blinks an eyelid when every service has its own database. The most unexpected things can change so quickly."
    * IN-MEMORY, RELATIONAL, KEY VALUE, WIDE COLUMN, DOCUMENT, TIME-SERIES, LEDGER

## Kubernetes:
**Sidecar** - Cross-cutting concerns in a [**sidecar**](https://microservices.io/patterns/deployment/sidecar.html) process or container that runs alongside the service instance
  * [OAM (w/ Alibaba Team), Open Application Model](https://github.com/oam-dev/spec) specification   
  * [DAPR, Distributed Application Runtime](https://dapr.io/)
  * [KEDA, Kubernetes Event-driven Autoscaling](https://keda.sh)
  * [Distributed State Management for Serverless](https://cloudstate.io)
  * [Kubernetes native applications](https://operatorhub.io)
  * [Secure networking](https://www.projectcalico.org)
  * [API Shark, Service Catalog & Call Graph](https://www.cloudvector.com/api-shark/)
  * ...

**Planes - Management, Control & Data:**
* [GCP, Cloud Run](https://cloud.google.com/run/)   
* https://crossplane.io - is a universal control plane on which any platform can be built and configured through Kubernetes style APIs;is open source/open governance, supports multiple cloud/infra providers, support application self-servicing, enables a clean separation of concern, and more.

**Scheduler - Smart Schedulers on top of an orchestrator with tasks encapsulated & labelled:**
* [Green Scheduler](https://blog.google/inside-google/infrastructure/data-centers-work-harder-sun-shines-wind-blows/)

**Hybrid:**
* Azure [Stack](https://azure.microsoft.com/en-us/overview/azure-stack/) - Appliance, ...
* GCP [Anthos](https://inthecloud.withgoogle.com/content-anthos/dl-cd.html) - OSS components, Kubernetes, Istio, Knative, Cloud Run ...


    


