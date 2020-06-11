# Cloud Computing:
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

 * [CosmosDB](https://docs.microsoft.com/en-us/azure/cosmos-db/) is not just Open Source C*/CQL compatibility. It's also potentially Change Data Capture (CDC) integrated w/ EventHub & Compute (Serverless) used for Data Lake
  * https://aws.amazon.com/blogs/database/introducing-the-aurora-storage-engine/
  * https://www.alibabacloud.com/blog/lindorm-alibaba-clouds-newest-cloud-native-multi-model-database_596269?spm=a2c65.11461433.0.0.46a75355aeZ2GL

  
## Metrics
**High Performance System** - How you [Structure & Monitor Measurements](https://www.youtube.com/watch?v=lJ8ydIuPFeU) radically alters what numbers you'll see, and it's extremely counterintuitive if you don't think long & hard.
 1. [User-centric meaningful availability](https://www.usenix.org/system/files/nsdi20spring_hauer_prepub.pdf)
 2. https://web.dev/vitals/
 
 
## In the future the majority of managed infrastructure offerings will be backed by open interfaces, but not necessarily open source projects.

* [SCREAMING IN THE CLOUD](https://www.lastweekinaws.com/podcast/screaming-in-the-cloud/)
  * On the future of @Kubernetesio “We'll enter another phase where you'll build a platform on top of Kubernetes, but it won't be worth mentioning that Kubernetes is underneath. People will be more interested in the thing above.” 
* https://www.youtube.com/watch?v=ZVRI214nnto
* [A Brief History](https://docs.google.com/presentation/d/1BoxFeENJcINgHbKfygXpXROchiRO2LBT-pzdaOFr4Zg/edit#slide=id.g39c264972c_182_1000)
* [Standards](https://docs.google.com/presentation/d/1wc9nJSyfjrUO2KpVgXt5KnSHVlWvXpho6eINkin5U5g/edit#slide=id.g12bfb019f3_2_34)
* [Open Application Model](https://oam.dev/)
* [Decouple developers from operations](https://www.youtube.com/watch?v=do-PrVi0ifk)
* [Kafka Cloud Native](https://www.confluent.io/blog/introducing-cloud-native-experience-for-apache-kafka-in-confluent-cloud)
* [Cassandra Cloud](https://constellation.datastax.com/)
* [Amazon Aurora cloud-native relational database](https://www.allthingsdistributed.com/2019/03/Amazon-Aurora-design-cloud-native-relational-database.html)
* [Socrates: The New SQL Server in the Cloud](https://www.microsoft.com/en-us/research/uploads/prod/2019/05/socrates.pdf)
* [Azure Architecture Center](https://docs.microsoft.com/en-us/azure/architecture/)
* The Amazon Effect
   * [Open Source at AWS](https://aws.amazon.com/opensource)
   * [Commercial Open Source Software](https://coss.media/oss-will-eat-cloud-computing/)
   * [Fork and Commoditize](https://thenewstack.io/fork-and-commoditize-gitlab-ceo-critiques-the-new-open-source-approach-by-amazon-web-services/)
   * [AWS Well-Architected Labs](https://wellarchitectedlabs.com)
   * [Amazon Builders Library](https://aws.amazon.com/builders-library/)
   * [AWS Well-Architected Framework](https://wa.aws.amazon.com/index.en.html)
