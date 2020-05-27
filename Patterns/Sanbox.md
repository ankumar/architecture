# "Sandbox" for sharing & collaborating

[Open Application Model (OAM)](https://github.com/oam-dev/spec) is a specification for building cloud native applications. OAM aims to enable the [separation of concerns](https://github.com/oam-dev/spec/blob/d16d5add/introduction.md) between application developers, application operators, and infrastructure operators. [Crossplane](https://crossplane.io/) is an open source multicloud control plane that shares many of OAM's goals around enabling the separation of concerns when modelling cloud native applications.
  
Control Plane:
  * [Backstage - Open Source from Spotify](https://labs.spotify.com/2020/04/21/how-we-use-backstage-at-spotify/)
     * Phase 1: Extensible frontend platform (Done ✅) 
     
     * Phase 2: Manage your stuff (**current focus**)
       * [Distributed Application Runtime](https://dapr.io/)
The core of building Platforms rests in versatile entity management. Entities represent the nouns or the "truths" of our world.

Quote from Platform Nuts & Bolts: Extendable Data Models

Entities, or what we refer to as “components” in Backstage, represent all software, including services, websites, libraries, data pipelines, and so forth. The focus of Phase 2 will be on adding an entity model in Backstage that makes it easy for engineers to create and manage the software components they own.
     
     * Phase 3: Ecosystem (later)
       * Upbound [Crossplane](https://github.com/crossplane/crossplane)
         * Implementation of the Open Application Model specification for Kubernetes https://github.com/crossplane/crossplane/blob/master/design/one-pager-oam-workflow.md
       
Sample Apps:  
  * https://github.com/GoogleCloudPlatform/microservices-demo
  * https://blog.yugabyte.com/cloud-native-meets-distributed-sql-bringing-microservices-kubernetes-istio-yugabytedb-together-with-hipster-shop-demo/
  * https://github.com/aws-samples/retail-demo-store
  * https://github.com/aws-samples/aws-serverless-ecommerce-platform
  
