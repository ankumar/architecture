# Architecture

Build on community learning from design & development to infrastructure & application modernization, leveraging open source, commodity utility technologies & investment made by the [Hyperscalers](https://leadingedgeforum.com/insights/constructing-cloud-native-business-capabilities-if-you-think-cloud-is-only-about-it-infrastructure-you-seriously-need-to-think-again/) in cloud-native applications and business capabilities.

## Steering Changes - CRAWL, WALK & RUN

![](https://github.com/ankumar/Architecture/blob/main/images/APIs.jpeg)
<p align="center"> <b> "APIs have replaced the central database in an enterprise's business operations." </b> </p>

Source: [Mary Poppendieck on Six Decades of Software Engineering](https://www.infoq.com/presentations/six-decades-software-engineering/)

## Technology Platform

**Application modernization** - developing & deploying containerized applications on Kubernetes & “Infrastructure as Code”. This provides ways of provisioning infrastructure resources in the cloud, and a technology stack for applications through code and automation. This is an enablement to standardize and automate software delivery process, as well as improve collaboration across several teams.

- **Process** - Design & Decisions
  * **Writing** Request for Comments (RFCs) & Architecture Decision Records (ADRs) 
    * -> TODO

(TODO: Link to blog posts on medium Sharing stories of **Platform** & Applications development & deployment)

## System

![Ackoff's Best](https://github.com/ankumar/Architecture/blob/main/images/Ackoff's%20Best.png)
[Ackoff's Best: His Classic Writings on Management](https://www.amazon.com/gp/product/0471316342/)
  * [Russell L Ackoff From Mechanistic to Systemic thinking](https://www.youtube.com/watch?v=yGN5DBpW93g)
  * [Idealized Design, Systems Thinking, and a Model for OutlierInnovation, by Dr. Russell Ackoff](https://www.youtube.com/watch?v=spm2HUxgI30)
  * [If Russ Ackoff had given a TED Talk...](https://www.youtube.com/watch?v=OqEeIG8aPPk)
  * [Systems Thinking Speech by Dr. Russell Ackoff](https://www.youtube.com/watch?v=EbLh7rZ3rhU)

## Engineering

* [What in the World Is World-Class Engineering?](https://jdcarlston.medium.com/what-in-the-world-is-world-class-engineering-part-2-4b384c74dc19)

* ["For understanding the specific proficiencies involved in creating a good Delivering to Optimizing agile team."](http://arlobelshee.github.io/AgileEngineeringFluency/?)
  * https://engineering.atspotify.com/about/
  * ["Staff Engineer"](https://staffeng.com/)
  * [Technical Leadership Masterclass](https://www.ruthmalan.com/Bredemeyer/Technical_Leadership_Masterclass_Overview.htm)
  * https://ti.to/bredemeyer/softwarearchitecturebundlespring2021/with/software-architecture-workshop-bundle-limited-early-enrollment 

> "Whatever "experience" you think you need probably doesn't matter as much as that person's ability to learn whatever comes next. Invest in smart folks. The rest works out"

  * https://acloudguru.com/blog/business/why-you-should-invest-in-undervalued-people 

* “DORA 4” metrics are highly correlated with **business performance**. 1. deployment frequency, 2. lead time for changes, 3. time to restore service, and 4. change failure rate.
![FOUR KEYS](https://github.com/GoogleCloudPlatform/fourkeys/blob/main/images/dora-chart.png)
![FOUR KEYS](https://cdn.thenewstack.io/media/2019/08/3ffd3515-screen-shot-2019-08-22-at-7.43.52-am.png)

### DevOps

* [DORA-Research](https://www.devops-research.com/research.html) | [DORA-4 Keys](https://github.com/GoogleCloudPlatform/fourkeys)
  
**1. Diagrams and Documentation**
* https://structurizr.org/ - unique feature ... the decoupling of model authoring and diagram rendering.

**2. GitLab - A Cloud Native Architecture:**

* Overview - https://docs.gitlab.com/ee/README.html
* Security - https://about.gitlab.com/blog/2020/06/24/soc2-compliance/
* CI Pipelines - https://docs.gitlab.com/ee/ci/pipelines/pipeline_efficiency.html
* Infrastructure - https://docs.gitlab.com/ee/user/project/clusters/
* [DORA metrics In GitLab](https://about.gitlab.com/releases/2021/01/22/gitlab-13-8-released/)
  * https://gitlab.com/groups/gitlab-org/-/epics/4358

**3. TODO, Microsoft - GitHub, Azure, and VS(Studio & Code):**
* Overview - https://github.com/features 
  * Enterprise - https://github.com/enterprise#github-one
* [Development metrics In GitHub](https://github.com/enterprise#github-one)
  * https://github.com/features/insights

### Security

* zero-trust security model
  * https://www.bleepingcomputer.com/news/security/nsa-microsoft-promote-a-zero-trust-approach-to-cybersecurity/
  * https://cloud.google.com/blog/products/identity-security/introducing-beyondcorp-enterprise

* "Shifting Left"
  * https://cloud.google.com/solutions/shifting-left-on-security
> Microsoft added queries to its open-source project CodeQL to search for the code used in the **SolarWindsHack** in your own code.
  * https://github.com/github/codeql/pull/5083

## Principles

Source: [Architecture Principles (draft)](https://ruthmalan.com/ByTopic/architecture/202102ArchitecturePrinciples.pdf)

Deliver working software frequently, from a couple of weeks to a couple of months, with a preference to the shorter timescale. 

Business people and developers must work together daily throughout the project. 

Build projects around motivated individuals. Give them the environment and support they need, and trust them to get the job done. 

The most efficient and effective method of conveying information to and within a development team is face-to-face conversation.

Working software is the primary measure of progress.

Agile processes promote sustainable development. The sponsors, developers, and users should be able to maintain a constant pace indefinitely.

Continuous attention to technical excellence and good design enhances agility.

Simplicity—the art of maximizing the amount of work not done—is essential.

The best architectures, requirements, and designs emerge from self-organizing teams.

At regular intervals, the team reflects on how to become more effective, then tunes and adjusts its behavior accordingly.

---

[Vijay Raghavendra](https://www.linkedin.com/in/vraghavendra/)

I had shared this a couple of folks previously. This is the framework we arrived at in my previous life after debating what characteristics were/were not important in the people on the team. Helped us with hiring and calibration during talent assessment, annual eval, etc. 

* **Get it Done**		
  * Prioritizes - Understand criticality of work and able to decide where and when to focus
  * Drives - Takes ownership. Ensures commitments are met
  * Runs fast and anticipates - Acts with a sense of urgency. Able to see around corners

* **Do it Right**
	
  * Adds Business Value - Understand business goals and ensures work adds right value
  * Delivers with Quality and Agility
	
* **Elevate**
		
  * Challenges and Influences
  * Builds Trust

* **Always Innovate**
		
  * Offers Vision - Articulates big picture 
  * Takes Risks

* **Lead**
		
  * Raises the bar
  * Develops talent in others
  * Innovates to accelerate

* **People Leadership**

  * Coaches and develops 
  * Attracts and Hires top talent

* **Inspires and Empowers**
	
  * Team Focused
  * Org Focused

## Open Source

* https://github.com/sponsors
* https://opencollective.com/
* https://twitter.com/ParisInBmore/status/1365472931757760512
* https://github.com/dirkriehle/coss-course
* https://monetize.substack.com/p/open-source-eras
* https://www.oss.fund/
* https://www.cognitect.com/blog/2020/12/15/sponsoring-open-source-developers

## API

[How to design a good API and why it matters](https://dl.acm.org/doi/10.1145/1176617.1176622)

https://cloud.google.com/blog/topics/developers-practitioners/database-cicd-database-spanner-liquibase

## Continuous Delivery

* [What is Continuous Delivery?](https://continuousdelivery.com/)

* https://stackoverflow.blog/2021/01/19/fulfilling-the-promise-of-ci-cd/

* [Semantic Versioning](https://semver.org/)
  * https://www.youtube.com/watch?v=rEgevIkqp2o
  * https://twitter.com/ahmetb/status/1362114431514071044
  * https://twitter.com/hynek/status/1366680550564634634

* Examples: microservices-demo
  * [Deployment](https://octopus.com/blog/ultimate-guide-to-k8s-microservice-deployments)
  * [Observability](https://github.com/lightstep/hipster-shop)

## Resilience

[Resilience engineering](https://github.com/lorin/resilience-engineering/blob/master/intro.md)

## Cloud

https://github.com/lynnlangit/learning-cloud

https://tanzu.vmware.com/developer/

### Azure

New eBook: Dapr for .NET Developers "Modern, distributed systems are in, and monolithic apps are out!" 
 
https://docs.microsoft.com/en-us/dotnet/architecture/dapr-for-net-developers/
1. State management 
2. Service invocation
3. Pub/sub
4. Bindings
5. Observability
6. Secrets
7. Dapr .NET SDK
 
* Sketchnote: https://cloud-skills.dev
* Article: https://aka.ms/visual-azure-acg
* Module: https://docs.microsoft.com/en-us/learn/modules/intro-to-azure-fundamentals/

## Containers

"Containers" - [has come to be a deeply overloaded term, and I see it causing confusion nearly every day](https://twitter.com/MarcJBrooker/status/1222217458028707841)

1. Easily build container images 
* [Jib](https://github.com/GoogleContainerTools/jib) / [Jib CLI](https://github.com/GoogleContainerTools/jib/tree/master/jib-cli)
2. .NET - https://devblogs.microsoft.com/dotnet/staying-safe-with-dotnet-containers/
3. [Open Repository for Container Tools](https://github.com/containers)
4. [Lifecycle of a container on Cloud Run](https://cloud.google.com/blog/topics/developers-practitioners/lifecycle-container-cloud-run)
5. [Dockerfile](https://docs.docker.com/engine/reference/builder/)
6. [containers-from-scratch](https://github.com/lizrice/containers-from-scratch/blob/master/main.go)  

## Pipelines

1. [Azure Pipelines](https://aka.ms/yaml):
  * Bedrock - https://github.com/gneisstech/bedrock/tree/bedrock-main/ci/pipelines/azure 
  * Service - https://github.com/gneisstech/http-https-echo/blob/master-bedrock/ci/pipelines/azure/bless_development_artifiacts.yml

2. [GitHub Pipelines](https://docs.github.com/en/actions/reference/workflow-syntax-for-github-actions)
  * Bedrock - https://github.com/gneisstech/bedrock/issues/2
  * Actions - https://docs.github.com/en/actions/learn-github-actions/migrating-from-azure-pipelines-to-github-actions

## Helm

Helm is the package manager for Kubernetes and helps users define, manage, install, upgrade, and rollback even the most complex Kubernetes application. Helm uses a package format called [Charts](https://helm.sh/docs/topics/charts/) to describe a set of Kubernetes resources. The Helm Chart contains the resources described in the following table.
| Resource | Description |
|----------|-------------|
| Chart.yaml | Information about the chart. |
| values.yaml | Default configuration for the chart. |
| templates | Templates that combine with values to generate the Kubernetes manifest files. |
| --set, --values | additional values provided at deployment time which override values.yaml settings |

Refer to the guide on [Using Helm](https://helm.sh/docs/intro/using_helm/) for an explanation of useful Helm concepts.

The repo for the helm charts may look something like this:

```
$ tree -a charts/

charts/
└── My App
    ├── .helmignore
    ├── Chart.yaml
    ├── charts
    ├── templates
    │   ├── NOTES.txt
    │   ├── _helpers.tpl
    │   ├── deployment.yaml
    │   ├── ingress.yaml
    │   ├── service.yaml
    │   ├── serviceaccount.yaml
    │   └── tests
    │       └── test-connection.yaml
    └── values.yaml
```

See [helm repo](https://helm.sh/docs/helm/helm_repo/) for command documentation.

Best Practices:
- Official docs - https://helm.sh/docs/chart_best_practices/ 
- Codefresh - https://codefresh.io/docs/docs/new-helm/helm-best-practices/
- JFrog - https://jfrog.com/blog/helm-charts-best-practices/
- Bitnami - https://docs.bitnami.com/tutorials/series/best-practices-helm/

### Create Chart
```
$ helm create
```

See helm [create](https://helm.sh/docs/helm/helm_create/) for command documentation.

### Install Chart
```
$ helm install 
```

See helm [install](https://helm.sh/docs/helm/helm_install/) for command documentation.

### Dependencies
```
$ helm dependency
```

See helm [dependency](https://helm.sh/docs/helm/helm_dependency/) for command documentation.

### Uninstall Chart
```
$ helm uninstall
```

This removes all the Kubernetes components associated with the chart and deletes the release.

See helm [uninstall](https://helm.sh/docs/helm/helm_uninstall/) for command documentation.

### Upgrading Chart
```
$ helm upgrade --install
```

See helm [upgrade](https://helm.sh/docs/helm/helm_upgrade/) for command documentation.

# Kubernetes Users Stories

- Zalando tech - https://github.com/zalando/public-presentations
- Tesla - 

# Kubernetes Failure Stories

- https://k8s.af/

# Kubernetes

[Kubernetes is from Greek, meaning helmsman or pilot](https://kubernetes.io/docs/concepts/overview/what-is-kubernetes/)

- [Docs](https://kubernetes.io/docs/home/)
- [Kubernetes the Hard Way](https://acloudguru.com/course/kubernetes-the-hard-way)
- [K8s In 30 mins](https://github.com/r0hi7/k8s-In-30Mins)
- [Visual Way](https://gumroad.com/aurelievache)
- [learnk8s](https://learnk8s.io)
  * https://learnk8s.io/troubleshooting-deployments 
- [Getting started](https://kubernetes.io/docs/setup/)

## Tools 
1. CLI

- https://kubernetes.io/docs/reference/kubectl/

2. Web/Desktop
- Dashboard - https://kubernetes.io/docs/tasks/access-application-cluster/web-ui-dashboard/
- Headlamp - https://github.com/kinvolk/headlamp

3. iOS
- Kuber - https://apps.apple.com/us/app/kuber-kubernetes-dashboard/id1461666739

--- 
- Google 

"ko is an open-source tool developed at Google that helps you build container images from Go programs and push them to container registries ... ko does its job without requiring you to write a Dockerfile or even install Docker itself on your machine."

  * [ko](https://cloud.google.com/blog/topics/developers-practitioners/ship-your-go-applications-faster-cloud-run-ko)
  * https://github.com/GoogleContainerTools
- Azure
  * [.NET] - https://www.dotnetcurry.com/aspnet-core/kubernetes-for-developers
  * [.NET] - https://dev.to/mcklmt/build-and-deploy-net-5-app-with-github-actions-1de
- VMware - http://vmware.github.io/ https://carvel.dev/
- Lens - https://k8slens.dev/
- Kubevious - https://nethminiromina.medium.com/introducing-kubernetes-new-friend-kubevious-2b393f639d67

[10 Awesome K8s tools](https://docs.google.com/presentation/d/13k-Lhc-tVgUohrtKqAYIikaQCTsmuzzjhOe_hpwgUgw/edit#slide=id.g91ee8ae7fb_0_123)
1. k9s - https://k9scli.io/
2. Kubectl aliases - https://github.com/ahmetb/kubectl-aliases
3. Stern - https://github.com/wercker/stern
4. Dive - https://github.com/wagoodman/dive
5. Kubens - https://github.com/ahmetb/kubectx/blob/master/kubens
6. Kube-PS1 - https://github.com/jonmosco/kube-ps1
7. Kubectx - https://github.com/ahmetb/kubectx 
8. KubeSpy - https://github.com/pulumi/kubespy
9. Kube-Shell - https://github.com/cloudnativelabs/kube-shell
10. Kubectl - https://github.com/kubernetes/kubectl

## Deep Dive
  * https://github.com/shubheksha/kubernetes-internals 
  * https://www.usenix.org/conference/lisa19/presentation/petazzoni-talk
  * https://speakerdeck.com/thockin/

## Articles
  * https://blog.heptio.com/core-kubernetes-jazz-improv-over-orchestration-a7903ea92ca
  * https://www.mgasch.com/2021/01/listwatch-prologue/
  * https://www.mgasch.com/2018/08/k8sevents/
  
  * Developer Experience:
    * [Maximizing Developer Effectiveness](https://martinfowler.com/articles/developer-effectiveness.html)

  * UML:
    * https://docs.gitlab.com/ee/administration/integration/plantuml.html
    * https://github.com/plantuml-stdlib/C4-PlantUML

  * ADRs:
    * [Original Article](https://cognitect.com/blog/2011/11/15/documenting-architecture-decisions)
    * [Templates](https://github.com/npryce/adr-tools)
    * https://github.com/endjin/dotnet-adr
      * https://github.com/endjin/dotnet-adr/tree/master/Solutions/Endjin.Adr.Templates
