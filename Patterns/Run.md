## Developers
  
Development Platforms:
* [GitHub - Codespaces](https://github.com/features/codespaces)
* [GCP - Cloud Shell](https://cloud.google.com/blog/products/gcp/introducing-google-cloud-shels-new-code-editor)
* [AWS - Cloud9](https://aws.amazon.com/cloud9/)
* [Kubernetes for Developers](https://okteto.com/)
  * https://github.com/rberrelleza/crossplane-community-day-2020

Visualize:
* Architecture & Code - [A Model "Above the Line, Below the Line"](https://queue.acm.org/detail.cfm?id=3380777)

## Infrastructure & Services
Cloud (& Edge) native technologies empower organizations to build and run scalable applications in modern, dynamic environments such as public, private, and hybrid clouds. **Containers, service meshes, microservices, immutable infrastructure, and declarative APIs exemplify this approach.**

These techniques enable loosely coupled systems that are resilient, manageable, and observable. Combined with robust automation, they allow engineers to make high-impact changes frequently and predictably with minimal toil.
-- [CNCF Cloud Native Definition](https://www.cncf.io/)

1. Separation of Compute & Storage
2. Network topology, Authentication, Cloud resource provisioning, Deployment, Logging and Monitoring, Traffic routing, Rate limiting, Staging and Production environments.

Programs are optimized for managing [cross-cutting concerns](https://dl.acm.org/doi/pdf/10.1145/3190508.3190526) in an intuitive and obvious manner, with feature requirements coded on one axis and common concerns on the other.

### 1. Security

* Data - Sensitive data, Personally identifiable information - PII, PCI or PHI 

* Services - 11 security patterns for microservice architectures - all in one handy guide! - https://developer.okta.com/blog/2020/03/23/microservice-security-patterns
    
### 2. Manage State

* [Stateful](https://github.com/ankumar/Architecture/blob/master/Patterns/Stateful.md)
  
## Metrics
**High Performance System** - How you [Structure & Monitor Measurements](https://www.youtube.com/watch?v=lJ8ydIuPFeU) radically alters what numbers you'll see, and it's extremely counterintuitive if you don't think long & hard.
 1. [User-centric meaningful availability](https://www.usenix.org/system/files/nsdi20spring_hauer_prepub.pdf)
 2. https://web.dev/vitals/
 
 ## Experimentation
 
 [My Sandbox](Sandbox.md)
 
  * [CosmosDB](https://docs.microsoft.com/en-us/azure/cosmos-db/) is not just Open Source C*/CQL compatibility. It's also potentially Change Data Capture (CDC) integrated w/ EventHub & Compute (Serverless) used for Data Lake
  * https://aws.amazon.com/blogs/database/introducing-the-aurora-storage-engine/
  * https://www.alibabacloud.com/blog/lindorm-alibaba-clouds-newest-cloud-native-multi-model-database_596269?spm=a2c65.11461433.0.0.46a75355aeZ2GL

