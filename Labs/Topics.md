# Architecture

**Breaking down silos and increasing agility, keep costs under control and the focus on delivering business value**

1. Dev + Ops - https://itrevolution.com/
2. Fin + Ops - https://www.finops.org/
3. Dev + Sec + Ops - ?

[Modeling](../Patterns/Modeling.md)

* https://github.com/michaelkeeling/saturn2019-architecture-island-workshop
* https://github.com/awslabs/aws-well-architected-labs
* https://github.com/binhnguyennus/awesome-scalability
* https://github.com/lorin/resilience-engineering
* https://github.com/wso2/reference-architecture
* https://ruthmalan.com/Journal/2019/201902OReillySAConPresentationPartI.htm

There isn't a concrete, well-defined algorithm for [decomposing](https://blog.acolyer.org/2016/09/05/on-the-criteria-to-be-used-in-decomposing-systems-into-modules/) [a system](https://queue.acm.org/detail.cfm?id=3395214) into [services](Modeling.md). As with much of software development, it's something of an art. If you decompose a system incorrectly, we have a distributed monolith, a system consisting of coupled services that must be deployed together. A distributed monolith has the drawbacks of both the monolithic and the Microservices architectures.

* [Domain-Driven](https://www.dddheuristics.com/)
* [DDD and Messaging Architectures](https://verraes.net/2019/05/ddd-msg-arch/)

# Languages & Frameworks

[A Day in Java Developer’s Life, with a taste of Kubernetes](https://github.com/aws-samples/kubernetes-for-java-developers/blob/master/readme.adoc)

[Java/Spring](https://www.infoq.com/news/2020/06/spring-boot-230-cloud/)
* [Azure](https://azure.microsoft.com/en-us/services/spring-cloud/)
* [GCP](https://cloud.spring.io/spring-cloud-gcp/reference/html/)
* https://derkoe.dev/blog/beating-c-with-java/

* https://github.com/aws-samples/aws-step-functions-long-lived-transactions
  * https://www.temporal.io/
  * https://cadenceworkflow.io/

# Distributed Systems

[Fallacies of Distributed Computing](https://en.wikipedia.org/wiki/Fallacies_of_distributed_computing)

* https://github.com/p0lyn0mial/awesome-distributed-systems

* https://github.com/aphyr/distsys-class

* https://www.the-paper-trail.org/

* https://www.slideshare.net/paulszulc/impossibility

1. [Serverless](../System/Serverless.md)
2. [Databases](../System/Databases.md)
3. [Kubernetes](../System/Kubernetes.md)

# Control Theory

https://gianarb.it/blog/control-theory-is-dope; https://fauna.com/blog/control-theory-for-fun-and-profit

# Cloud & Desktop IDE

https://www.gitpod.io/
* https://theia-ide.org/ - At long last, with Eclipse Theia we have an open source "platform to develop multi-language Cloud & Desktop IDEs with state-of-the-art web technologies". Theia is already used by Google Cloud, Eclipse Che and Gitpod.
* https://shell.azure.com/
  * https://github.com/features/codespaces
* https://ssh.cloud.google.com/
  * [GCP - Cloud Shell](https://cloud.google.com/blog/products/gcp/introducing-google-cloud-shels-new-code-editor)
* https://aws.amazon.com/cloud9/

# Open Source

[Backstage from Spotify](https://backstage.io/) is an open platform for building developer portals
* Phase 1: Extensible frontend platform (Done ✅) 
* Phase 2: [Manage your stuff](https://backstage.io/blog/2020/05/22/phase-2-service-catalog) (**current focus**)
* Phase 3: Ecosystem (later) 

https://relay.sh/
* https://relay.sh/blog/user-defined-webhooks-with-knative-and-ambassador/
* https://github.com/argoproj/gitops-engine
  * https://argoproj.github.io/argo-cd/  

https://opentelemetry.io/about/
* https://prometheus.io/
* https://promlabs.com/
* https://thanos.io/
* https://cortexmetrics.io/

https://linuxcontainers.org/
* https://opencontainers.org/
* https://github.com/containers
* https://getnelson.io/
* https://katacontainers.io/
* https://aws.amazon.com/blogs/aws/bottlerocket-open-source-os-for-container-hosting/

https://cd.foundation/
* https://tekton.dev/
  
* https://devcenter.heroku.com/articles/buildpacks
  * https://buildpacks.io/
    
* https://okteto.com/

* https://upbound.io/
  * https://github.com/rberrelleza/crossplane-community-day-2020

* [GoogleContainerTools](https://github.com/GoogleContainerTools)
  * https://skaffold.dev/
  * https://github.com/GoogleCloudPlatform/cloud-run-button#add-the-cloud-run-button-to-your-repos-readme
  
* https://relay.sh/workflows/

* [Unified/Multi-Model](http://www.mm-adt.org/)

# Tools

1. **Keras**
* https://keras.io/examples/vision/captcha_ocr/
* https://github.com/keras-team/keras-io/blob/master/call_for_contributions.md

2. **OpenAI**
* https://github.com/openai

3. **GCP**
* https://github.com/tensorflow/cloud
  * https://medium.com/google-cloud/video-object-tracking-as-a-service-18eb4227df34

4. **NVIDIA**
* https://developer.nvidia.com/isaac-sim

5. **MICROSOFT**
* https://microsoft.github.io/moab/


