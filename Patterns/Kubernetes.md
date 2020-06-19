# Design Patterns

* Design Documents
  * https://github.com/kubernetes/enhancements/tree/master/keps
  * https://github.com/kubernetes/community/tree/master/contributors/design-proposals
* API - https://kubernetes.io/docs/reference/generated/kubernetes-api/v1.18/
  * Resource model - https://kubernetes.io/docs/reference/using-api/api-overview/ / https://kubernetes.io/docs/reference/using-api/api-concepts/
  * Object model - https://kubernetes.io/docs/concepts/overview/working-with-objects/kubernetes-objects/
  * Message model - [gRPC](https://grpc.io/docs/what-is-grpc/core-concepts/)
  * Data model - [etcd](https://etcd.io/) Key / Value
* [10 must-know patterns](https://developers.redhat.com/blog/2020/05/11/top-10-must-know-kubernetes-design-patterns/2901820597/) 

---

The reason why Kubernetes is popular is that it doesn't force you down a single path of getting things done, and it supports more workload types: **crontab, batch jobs, stateless and stateful workloads**. -- [Kelsey Hightower](https://www.infoq.com/podcasts/kubernetes-event-driven-architecture/)

**Managem, [Planes - Control & Data](http://brooker.co.za/blog/2019/03/17/control.html)**

* **Multi-cloud**
  * [Crossplane](https://crossplane.io) - open source universal control plane on which any platform can be built and configured through Kubernetes style APIs;is open source/open governance, supports multiple cloud/infra providers, support application self-servicing, enables a clean separation of concern, and more.
  
  * [Crossplane](https://github.com/crossplane/crossplane) “introduces a powerful open source control plane to enterprise platforms, enabling companies to standardize on application and infrastructure management; automate operations; effectively implement their security, governance, and cost policies; and publish an internal API that integrates with their development workflows and tools.”

  * AWS [Outposts](https://aws.amazon.com/outposts/)
  * Azure [Stack](https://azure.microsoft.com/en-us/overview/azure-stack/) - Appliance, ...
  * GCP [Anthos](https://inthecloud.withgoogle.com/content-anthos/dl-cd.html) - OSS components, Kubernetes, Istio, Knative, Cloud Run ...

* **Sidecar** - Cross-cutting concerns in a [**sidecar**](https://microservices.io/patterns/deployment/sidecar.html) process or container that runs alongside the service instance. [Operators and Sidecars Are the New Model for Software Delivery](https://thenewstack.io/operators-and-sidecars-are-the-new-model-for-software-delivery/)
  
  * [DAPR, Distributed Application Runtime](https://dapr.io/)
Azure is launching Dapr a Open Source portable runtime for building applications in cloud and edge, Dapr is a a collection of really useful side-cars to make your distributed app development easier!
  * [KEDA, Kubernetes Event-driven Autoscaling](https://keda.sh)
  * [Kubernetes native applications](https://operatorhub.io)
  * [Secure networking](https://www.projectcalico.org)
  * [API Shark, Service Catalog & Call Graph](https://www.cloudvector.com/api-shark/)
  * ...
  
* **Service Mesh** - This design pattern combines [data planes & control planes](https://blog.envoyproxy.io/service-mesh-data-plane-vs-control-plane-2774e720f7fc)
  * [GCP, Cloud Run](https://cloud.google.com/run/)
  
* **Scheduler** - Smart Schedulers on top of an orchestrator with tasks encapsulated & labelled
  * [Green Scheduler](https://blog.google/inside-google/infrastructure/data-centers-work-harder-sun-shines-wind-blows/)
