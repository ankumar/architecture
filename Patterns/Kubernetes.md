1. Foundational Patterns, covers the core concepts of Kubernetes. These are the underlying principles and practices for building container-based cloud-native applications.
* Predictable Demands, explains why every container should declare its resource profile and stay confined to the indicated resource requirements.
* Declarative Deployment, shows the different application deployment strategies that can be performed in a declarative way.
* Health Probe, dictates that every container should implement specific APIs to help the platform observe and manage the application in the healthiest way possible.
* Managed Lifecycle, describes why a container should have a way to read the events coming from the platform and conform by reacting to those events.
* Automated Placement, introduces a pattern for distributing containers in a Kubernetes multinode cluster.
2. Behavioral Patterns, describes patterns that sit on top of the foundational patterns and add finer-grained concepts for managing various types of container and platform interactions.
* Batch Job, describes an isolated atomic unit of work run until completion.
* Periodic Job, allows the execution of a unit of work to be triggered by a temporal event.
* Daemon Service, allows running infrastructure-focused Pods on specific nodes, before application Pods are placed.
* Singleton Service, ensures only one instance of a service is active at a time and still highly available.
* Stateful Service, is all about how to create and manage distributed stateful applications with Kubernetes.
* Service Discovery, explains how clients can access and discover the instances providing application services.
* Self Awareness, describes mechanisms for introspection and metadata injection into applications.
3. Structural Patterns, contains patterns related to organizing containers within a Pod, which is the atom of the Kubernetes platform.
* Init Container, introduces a separate lifecycle for initialization-related tasks and the main application containers.
* Sidecar, describes how to extend and enhance the functionality of a pre-existing container without changing it.
* Adapter, takes an heterogeneous system and makes it conform to a consistent unified interface that can be consumed by the outside world.
* Ambassador, describes a proxy that decouples access to external services.
4. Configuration Patterns, gives insight into the various ways application configuration can be handled in Kubernetes. These are very granular patterns, including concrete recipes for connecting applications to their configuration.
* EnvVar Configuration, uses environment variables to store configuration data.
* Configuration Resource, uses Kubernetes resources like ConfigMaps or Secrets to store configuration information.
* Immutable Configuration, brings immutability to large configuration sets by putting it into containers linked to the application at runtime.
* Configuration Template, is useful when large configuration files need to be managed for various environments that differ only slightly.
5. Advanced Patterns, is a collection of advanced concepts, such as how the platform itself can be extended or how to build container images directly within the cluster.
* Controller, is essential to Kubernetes itself and this pattern shows how custom controllers can extend the platform.
* Operator, combines a Controller with custom and domain-specific resources to encapsulate operational knowledge in an automated form.
* Elastic Scale, describes how Kubernetes can handle dynamic loads by scaling in various dimensions.
* Image Builder, moves the aspect of building application images into the cluster itself.

A pattern might not always fit into one category alone. Depending on the context, the same pattern might fit into several categories. Every pattern chapter is self-contained, and you can read chapters in isolation and in any order.
