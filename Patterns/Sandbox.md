[CNCF](https://www.cncf.io/) Cloud Native Definition: Cloud native technologies empower organizations to build and run scalable applications in modern, dynamic environments such as public, private, and hybrid clouds. **Containers, service meshes, microservices, immutable infrastructure, and declarative APIs exemplify this approach.**

These techniques enable loosely coupled systems that are resilient, manageable, and observable. Combined with robust automation, they allow engineers to make high-impact changes frequently and predictably with minimal toil.

[Open Application Model (OAM)](https://github.com/oam-dev/spec) is a specification for building cloud native applications. OAM aims to enable the [separation of concerns](https://github.com/oam-dev/spec/blob/d16d5add/introduction.md) between application developers, application operators, and infrastructure operators.
  
**1. Control Plane:** [Crossplane](https://crossplane.io/) is an open source multicloud control plane that shares many of OAM's goals around enabling the separation of concerns when modelling cloud native applications.

[Crossplane](https://github.com/crossplane/crossplane) “introduces a powerful open source control plane to enterprise platforms, enabling companies to standardize on application and infrastructure management; automate operations; effectively implement their security, governance, and cost policies; and publish an internal API that integrates with their development workflows and tools.”

  * Implementation of the Open Application Model specification for Kubernetes https://github.com/crossplane/crossplane/blob/master/design/one-pager-oam-workflow.md
  
  * [Distributed Application Runtime](https://dapr.io/)
    * [Latest Presentation](https://github.com/dapr/docs/blob/master/presentations/Dapr%20Presentation%20Deck.pptx)

  * Extending [Backstage, Open Source from Spotify](https://backstage.io/):
    * Phase 1: Extensible frontend platform (Done ✅) 
    * Phase 2: [Manage your stuff](https://backstage.io/blog/2020/05/22/phase-2-service-catalog) (**current focus**)
    * Phase 3: Ecosystem (later) 


**2. Open Interfaces:** In the future the majority of managed infrastructure offerings MAY be backed by Open Interfaces, NOT necessarily Open Source Projects.

Compute:
DBaaS:


---

**Real World Apps:**

---

**Sample Demo Apps:**
 
