# TGIK playlist

The following list contains information about the individual TGIK episodes such as the YouTube url and the show notes.

The master playlist can be found at [TGIK playlist](https://www.youtube.com/playlist?list=PLvmPtYZtoXOENHJiAQc6HmV2jmuexKfrJ)

> Come hang out with Joe Beda as he does a bit of hands on exploration of Kubernetes and related topics.  Some of this will be Joe talking about the things he knows well.  Some of this will be Joe exploring something new with the audience.  Ask questions, comment and help decide where things go.

## TGI Kubernetes 024: Kubernetes Job objects

- Recording date: 2018-02-02
- Video: https://www.youtube.com/watch?v=-gLMTm85R3M
- Show notes:

  > This week we'll dig into the Kubernetes "Job" primitive. We'll look at how it works, how it compares to other controllers like Deployments and common usage patterns.

  - [KUAR excerpt link (unfortunately doesn't have Jobs chapter)](http://go.heptio.com/kubernetes-up-and-running)
  - [k8s.io docs on Jobs](https://kubernetes.io/docs/concepts/workloads/controllers/jobs-run-to-completion/)
  - [Issue around sidecars and jobs](https://github.com/kubernetes/kubernetes/issues/25908)
  - [kubectl run behavior based on flags](https://kubernetes.io/docs/reference/kubectl/conventions/#generators)
  - [KUAR org with kuard and examples](https://github.com/kubernetes-up-and-running)
  - [CoreOS joins RedHat](https://coreos.com/blog/coreos-agrees-to-join-red-hat)
  - [Container Linux lives](https://groups.google.com/forum/m/#!topic/coreos-user/GR4YlF2c1dM)
  - [CoreOS/Red Hat FAQ](https://www.redhat.com/en/blog/faq-red-hat-acquire-coreos)
  - [Brandon is a dad!](https://twitter.com/BrandonPhilips/status/958809760299565056)
  - [Brian shaves his beard!](https://twitter.com/brianredbeard/status/958455929694953473)
  - [Heptio Kubernetes Subscription. The Undistro](https://blog.heptio.com/introducing-heptio-kubernetes-subscription-5415052ef374)
  - [KubeCon EU Contributor Summit](https://github.com/kubernetes/community/tree/master/events/2018/05-contributor-summit)
  - [New k8s.io docs experience!](https://kubernetes.io/docs/home/?path=users&persona=app-developer&level=foundational)
  - [Rename Master in Kubernetes](https://github.com/kubernetes/website/issues/6525)

## TGI Kubernetes 023: Using private registries

- Recording date: 2018-01-26
- Video: https://www.youtube.com/watch?v=-JN8NSUnVgM
- Show notes:

  > This week we'll look at how to use private/custom registries with Kubernetes.  I'm going to try to cover major cloud providers and the Docker Hub.  We'll look at how registries interact with Kubernetes secrets and service accounts.

  - [Notes I was using during the video](https://gist.github.com/jbeda/71b85764187dcd3434ee921ff0baae3a)
  - [k8s.io docs on private registries](https://kubernetes.io/docs/tasks/configure-pod-container/pull-image-private-registry/)
  - [k8s.io docs on service accounts (and imagePullSecrets)](https://kubernetes.io/docs/tasks/configure-pod-container/configure-service-account/)
  - [ECR re-registerer](https://github.com/upmc-enterprises/registry-creds)
  - [Applatix joins Intuit](https://blog.argoproj.io/applatix-joins-intuit-7ab587270573)
  - [Nuclio hackathon](https://nuclio.devpost.com)
  - [Nuclio 0.2.4](https://github.com/nuclio/nuclio/releases/tag/0.2.4)
  - [99pi Scott McCloud episode](https://99percentinvisible.org/episode/speech-bubbles-understanding-comics-scott-mccloud/)
  - [Scott's k8s comic](https://cloud.google.com/kubernetes-engine/kubernetes-comic/)
  - [OpenCensus](https://opencensus.io)
  - [kubed-sh](https://github.com/mhausenblas/kubed-sh)
  - [Telepresence](https://github.com/datawire/telepresence)
  - [Heptio Labs wardroom](https://github.com/heptiolabs/wardroom)
  - [Node validation code for docker version](https://github.com/kubernetes/kubernetes/blob/master/test/e2e_node/system/docker_validator.go)

## TGI Kubernetes 022: Nuclio serverless system

- Recording date: 2018-01-19
- Video: https://www.youtube.com/watch?v=wmXHqQLdM2I
- Show notes:

  > This week we will look at Nuclio -- a serverless system that is aimed at real time and data driven applications.  How does this compare with some of the other serverless systems out there? What makes it for "real time and data driven apps"?  How does it work when I try to install on a k8s cluster that they don't have explicit instructions around?

  - [Nuclio serverless](https://nuclio.io)
  - [Nuclio github](https://github.com/nuclio/nuclio)
  - [@kelseyhightower tweet on nuclio](https://twitter.com/kelseyhightower/status/950867543773859840)
  - [Nuclio hackathon!](https://nuclio.devpost.com)
  - [Matt Klein's post on modern LBing](https://blog.envoyproxy.io/introduction-to-modern-network-load-balancing-and-proxying-a57f6ff80236)
  - [Maglev paper from Google](https://research.google.com/pubs/pub44824.html)
  - [Heptio community call on moving monolithic applications to k8s hosted by Kris Nova](https://blog.heptio.com/moving-monolithic-apps-e8f7483938db)
  - [Heptio help article on accessing private registries](http://docs.heptio.com/content/private-registries/pr-gcr.html)
  - [Old but good blog post on queueing theory with single threaded workers with Rap Genius (now genius.com) and heroku](https://genius.com/James-somers-herokus-ugly-secret-annotated)

## TGI Kubernetes 021: kube-deploy

- Recording date: 2018-01-12
- Video: https://www.youtube.com/watch?v=f_ANRYIXFgI
- Show notes:

  > This week we will look at kube-deploy. This is an early project that reexamines how to build and scale clusters using the "Cluster API". We'll talk about how this builds on top of kubeadm and look at an early version in action on GCP.

  - [Cluster API working group](https://github.com/kubernetes/community/tree/master/wg-cluster-api)
  - [kube-deploy repo](https://github.com/kubernetes/kube-deploy)
  - [kubicorn](https://github.com/kris-nova/kubicorn)
  - [Kubernetes API docs](https://kubernetes.io/docs/reference/generated/kubernetes-api/v1.9/)
  - [heptiolabs/ktx](https://github.com/heptiolabs/ktx)
  - [Nuclio serverless platform](https://github.com/nuclio/nuclio)

## TGI Kubernetes 020: Argo workflow system

- Recording date: 2018-01-05
- Video: https://www.youtube.com/watch?v=M_rxPPLG8pU
- Show notes:

  > This week we will take a look at the Argo project.  This is a Kubernetes native declarative workflow system driven by CRDs.

  - [Argo github](https://github.com/argoproj/argo)
  - [Meltdown/Spectre 1](https://meltdownattack.com)
  - [Meltdown/Spectre 2](https://googleprojectzero.blogspot.se)
  - [Brigade](https://github.com/azure/brigade)
  - [Matt's post on Brigade/YAML](http://technosophos.com/2018/01/04/why-brigade-doesn-t-do-yaml.html)
  - [Fission workflow](http://fission.io/workflows/)
  - [AWS StepFunctions](https://aws.amazon.com/step-functions/)
  - [kubeflow](https://github.com/google/kubeflow)

## TGIK Kubernetes 019: Prometheus as a noob

- Recording date: 2017-12-22
- Video: https://www.youtube.com/watch?v=pDb2psNcvKU
- Show notes:

  > This week we will be exploring monitoring with Prometheus. Joe hasn't used Prometheus before (but has used similar systems inside of Google).  We'll install it and try to get some simple metrics connected.  Let's see how far we can get in ~1.5 hours.

  - [Prometheus](https://prometheus.io)
  - [Prometheus Operator](https://github.com/coreos/prometheus-operator)
  - [kube-prometheus config](https://github.com/coreos/prometheus-operator/tree/master/contrib/kube-prometheus)
  - [jrnt30's patch to kuard adding metrics](https://github.com/kubernetes-up-and-running/kuard/pull/14)
  - [Example of scraping pods directly instead of via service](https://github.com/prometheus/prometheus/blob/70f3d1e9f95ad6611be2e76fad44f07b0a2579ca/documentation/examples/prometheus-kubernetes.yml#L248)
  - [Honeycomb for high cardinality observability](https://honeycomb.io)
  - [Scripts I used in the episode](https://gist.github.com/jbeda/50ce424c318a1862e5c619ea649f7c53)

## TGIK Kubernetes 018: kube-metacontroller

- Recording date: 2017-12-15
- Video: https://www.youtube.com/watch?v=xdCTC4scjDg
- Show notes:

    > This week we will be exploring the kube-metacontroller project from Anthony Yeh at Google.  This is a framework that makes it super easy to create controllers and is something that was highlighted in a KubeCon keynote. As this is the first episode after KubeCon I'll also share my impressions of what I saw there.

    - [kube-metacontroller](https://github.com/GoogleCloudPlatform/kube-metacontroller)
    - [Dick's Drive In](http://www.ddir.com)
    - [KSonnet](https://ksonnet.io)
    - [KSonnet quick screencast](https://www.youtube.com/watch?v=KgEoh9xCfXc)
    - [Heptio Ark + Microsoft Azure](https://techcrunch.com/2017/12/07/heptio-teams-up-with-microsoft-to-build-a-better-kubernetes-disaster-recovery-solution/)
    - [Helm security thoughts](https://engineering.bitnami.com/articles/helm-security.html)
    - [tgik-controller](https://github.com/jbeda/tgik-controller)

## TGIK Kubernetes 017: Resource limits and quota

- Recording date: 2017-11-17
- Video: https://www.youtube.com/watch?v=xtl2KV1JW9s
- Show notes:

    > This week we will be exploring resource limits (CPU, RAM, etc.) along with resource quotas. We'll explore how these work, how to set them and some best practices.  We also cover heapster and how it collects resource statistics.

    - [One year for Heptio!](https://blog.heptio.com/one-year-of-heptio-5a1dbd95b73b)
    - [Jamie's deep dive on how k8s works](https://github.com/jamiehannaford/what-happens-when-k8s)
    - [My working notes and some of the files I used](https://gist.github.com/jbeda/3c54ddd9c25eaafb399b143f65b9c07d)

## TGIK Kubernetes 016: Heptio Contour ingress controller

- Recording date: 2017-11-11
- Video: [https://www.youtube.com/watch?v=-Hvfl6zOLGE](https://www.youtube.com/watch?v=-Hvfl6zOLGE)
- Show notes:

    > This week we will be exploring a new project from Heptio: Contour! This is a new Kubernetes Ingress controller based on Envoy written by Dave Cheney.

    - [Contour](https://github.com/heptio/contour)
    - [Envoy](https://www.envoyproxy.io)
    - [Envoy v2 API](https://github.com/envoyproxy/data-plane-api)
    - [Kris and Justin's Cloud Native Infrastructure book](https://www.amazon.com/Cloud-Native-Infrastructure-Applications-Environment/dp/1491984309)
    - [Weaveworks Flux](https://github.com/weaveworks/flux)
    - [Zalando ALB controller](https://github.com/zalando-incubator/kube-ingress-aws-controller)
    - [Glowforge](https://glowforge.com)
    - [My paperjs program for the slinky](http://sketch.paperjs.org/#S/nZFhS8MwEIb/yhGQJUvRTGUbnX7yDwh+tH6I7bmWthfJ4kRG/7uXtnM6JoKBQO7ufS95LjtBtkWRiocaQ16KROSuiPHWemg/7m0o4RYI3yEepVplNGTPN8G7Gu9c4zwrJh6LCRczisYcKaDfG11FQV4bk/BWg4De2j69Yc2lMb3xhRvJihNmBRXcHDQcaq1glxHwivYt5sH97D9W47K0bjAFeTU3Fws1ldXZQiWHcoO0DmXKd0xhNqS7yBUPI5stCjky6PEyfngXX3liJn+M5JhrOfD8G0dW6jTQ18D0zOy5fsHS36H405892vq1N4v08an7BA==)

## TGIK Kubernetes 015: Exploring Brigade from Microsoft

- Recording date: 2017-11-04
- Video: [https://www.youtube.com/watch?v=hreCyC7XnOw](https://www.youtube.com/watch?v=hreCyC7XnOw)
- Show notes:

    > This week Joe will be looking at Brigade from Microsoft. This is a Serverless-ish workflow system that was recently announced.

    - [Brigade](https://open.microsoft.com/2017/10/23/announcing-brigade-event-driven-scripting-kubernetes/) and [Brigade on github](https://github.com/azure/brigade)
    - [Heptio Contour](https://github.com/heptio/contour)
    - [In flight work to add NLB to AWS cloud provider](https://github.com/kubernetes/kubernetes/issues/52173)
    - [SPIFFE/SPIRE demo give at SIG-Auth](https://www.youtube.com/watch?v=uDHNcZ0eGHI&list=PL69nYSiGNLP0VMOZ-V7-5AchXTHAQFzJw&index=1)
    - [Mutable Webhooks to Beta in 1.9](https://github.com/kubernetes/community/blob/master/contributors/design-proposals/api-machinery/admission-control-webhooks.md)
    - [Helm RBAC instructions](https://gist.github.com/mgoodness/bd887830cd5d483446cc4cd3cb7db09d)

## TGIK Kubernetes 014: Serverless with OpenFaaS

- Recording date: 2017-10-27
- Video: [https://www.youtube.com/watch?v=iMzf_oWsRi0](https://www.youtube.com/watch?v=iMzf_oWsRi0)
- Show notes:

    > This week Joe will be digging into the OpenFaaS serverless framework.  This is a continuation from the last two weeks when he looked at kubeless and fission.  We'll be starting from scratch and see how far we can get.  We will also compare and contrast approaches.

    - [Updated AWS Quickstart for Kubernetes for 1.8](https://github.com/aws-quickstart/quickstart-heptio)
    - [Heptio Sonobuoy 0.9.0](https://github.com/heptio/sonobuoy/releases/tag/v0.9.0)
    - [Heptio Ark 0.5.0](https://github.com/heptio/ark/releases)
    - [Brigade](https://open.microsoft.com/2017/10/23/announcing-brigade-event-driven-scripting-kubernetes/) and [Brigade on github](https://github.com/azure/brigade)
    - [New AKS](https://azure.microsoft.com/en-us/services/container-service/kubernetes/)
    - [Hacking and Hardening Kubernetes by Example](https://docs.google.com/presentation/d/1xeagoDn-6kQ6FPdfX9IlD5MjWalW2o8PeCt20DEfFpg/edit#slide=id.gcb9a0b074_1_0)
    - [OpenFaaS Guides](https://github.com/openfaas/faas/tree/master/guide)
    - [OpenFaaS Golang functions](https://blog.alexellis.io/serverless-golang-with-openfaas/)

## TGIK Kubernetes 013: Serverless with Fission

- Recording date: 2017-10-20
- Video: [https://www.youtube.com/watch?v=3XgBB4mATNM](https://www.youtube.com/watch?v=3XgBB4mATNM)
- Show notes:

    > This week Joe will be digging into the Fission serverless framework.  This is a continuation from last week when he looked at kubeless.  We'll be starting from scratch and see how far we can get.  We will also compare and contrast approaches.

    - [Grafeas announcement](https://cloudplatform.googleblog.com/2017/10/introducing-grafeas-open-source-api-.html)
    - [Grafeas site](https://grafeas.io)
    - [Kelsey's guide to installing Grafeas](https://github.com/kelseyhightower/grafeas-tutorial)
    - [Docker/Kubernetes announcement](https://blog.docker.com/2017/10/kubernetes-docker-platform-and-moby-project/)
    - [Moby and Kubernetes](https://blog.mobyproject.org/moby-and-kubernetes-bf888ab31e38)
    - [Fission](http://fission.io)
    - [Fission Workflows](https://github.com/fission/fission-workflows)
    - [kube-metacontroller](https://github.com/GoogleCloudPlatform/kube-metacontroller)

## TGIK Kubernetes 012: Exploring serverless with Kubeless

- Recording date: 2017-10-13
- Video: [https://www.youtube.com/watch?v=WotK415iOQM](https://www.youtube.com/watch?v=WotK415iOQM)
- Show notes:

    > In this episode Joe will be getting hands on with kubeless for the first time.  Kubeless is a popular serverless framework that runs on top of Kubernetes.

    - [Kubeless](http://kubeless.io) and [Kubeless on github](https://github.com/kubeless/kubeless)
    - [Kubernetes office hours](https://github.com/kubernetes/community/blob/master/community/office-hours.md)
    - [Kubernetes Up & Running](http://shop.oreilly.com/product/0636920043874.do)
    - [Heptio Labs](https://blog.heptio.com/announcing-heptio-labs-c39c268da67c)
    - [Becoming a Cloud Native Organization eBook](https://blog.heptio.com/becoming-cloud-native-a8b82be02d27)
    - [Heptio Solutions Engineer Job listing](https://jobs.lever.co/heptio/9b6c7578-b696-4468-859b-a39d58fa0eb8)
    - [kubevirt](https://github.com/kubevirt/kubevirt)
    - [Heptio Quickstart issue w/ storage classes](https://github.com/heptio/aws-quickstart/issues/80)

## TGIK Kubernetes 011: Upgrading to 1.8 with kubeadm

- Recording date: 2017-10-06
- Video: [https://www.youtube.com/watch?v=x9doB5eJWgQ](https://www.youtube.com/watch?v=x9doB5eJWgQ)
- Show notes:

    > This episode will involving taking a running 1.7.x cluster that was originally built with kubeadm and upgrading that to 1.8.  We'll also talk about the future of install tools and maybe have time to explore "kubeadm phases".

    - [Kubeadm upgrade guide to 1.8](https://kubernetes.io/docs/tasks/administer-cluster/kubeadm-upgrade-1-8/)
    - [1.8 change notes](https://github.com/kubernetes/kubernetes/blob/master/CHANGELOG.md#v180)
    - [My notes I was copy/pasteing from](https://gist.github.com/jbeda/9d14523377b53937cc531f78b9f0f021)
    - [Allegory of the Cave (wrt API versions)](https://en.wikipedia.org/wiki/Allegory_of_the_Cave)

## TGIK Kubernetes 010: Ingress with TLS

- Recording date: 2017-09-29
- Video: [https://www.youtube.com/watch?v=9uU2QMAiZrI](https://www.youtube.com/watch?v=9uU2QMAiZrI)
- Show notes:

    > This episode will explore installing nginx ingress on an AWS cluster. We'll also look at how to get TLS certificates automatically allocated by Let's Encrypt via kube-lego.

    - [Sonobuoy Scanner](https://scanner.heptio.com)
    - [Kubernetes 1.8 release notes](https://github.com/kubernetes/kubernetes/blob/master/CHANGELOG.md#v180)
    - [Ingress repo](https://github.com/kubernetes/ingress-nginx)
    - [kube-lego repo](https://github.com/jetstack/kube-lego)
    - [kube-lego RBAC rules](https://github.com/jetstack/kube-lego/issues/99#issuecomment-320342156)
    - [kuard example server](https://github.com/kubernetes-up-and-running/kuard)
    - [Ingress docs](https://kubernetes.io/docs/concepts/services-networking/ingress/)

## TGIK Kubernetes 009: Finishing the Controller

- Recording date: 2017-09-15
- Video: [https://www.youtube.com/watch?v=wqhKCiGsf1Y](https://www.youtube.com/watch?v=wqhKCiGsf1Y)
- Show notes:

    > In this episode, Joe will be continue to build the controller he started in [TGIK 007](https://www.youtube.com/watch?v=8Xo_ghCIOSY). Some great progress was made in [TGIK 008](https://www.youtube.com/watch?v=fWkK-zsFtlU) and we'll look to finish up in this episode.

    - [The github repo we were working on](https://github.com/jbeda/tgik-controller)

## TGIK Kubernetes 008: Continuing the Controller

- Recording date: 2017-09-08
- Video: [https://www.youtube.com/watch?v=fWkK-zsFtlU](https://www.youtube.com/watch?v=fWkK-zsFtlU)
- Show notes:

    > In this episode, Joe will be continue to build the controller he started in [TGIK 007](https://www.youtube.com/watch?v=8Xo_ghCIOSY).  After taking a 3 week break from TGIK, Joe is going to take a step back and take a simpler approach to building this. Come hear what he got wrong the first time and watch as he fixes it.

   - [Repo with the code](https://github.com/jbeda/tgik-controller)
   - [Julia's cool drawing](https://twitter.com/b0rk/status/872822361199972352)
   - [Pointer to new AWS NL](https://twitter.com/jbeda/status/905935335237881857)
   - [nginx Unit](https://www.nginx.com/products/nginx-unit/)

## TGIK Kubernetes 007: Building a Controller

- Recording date: 2017-08-11
- Video: [https://www.youtube.com/watch?v=8Xo_ghCIOSY](https://www.youtube.com/watch?v=8Xo_ghCIOSY)
- Show notes:

    > In this episode, Joe will be building a new controller using Go.  Learn how controllers work and a bit about how to build one.  Also watch Joe, most probably, looks stuff up on Stack Overflow.

    - [The repo where this project lives](https://github.com/jbeda/tgik-controller)
    - [The code that we started with](https://github.com/jbeda/tgik-controller/tree/13db5aaa9d9cc6745474b83316dc5faa9fff9c5f)
    - [The code that we ended with](https://github.com/jbeda/tgik-controller/tree/ac55060d60f51fc89240200050e88368d5f58848)

## TGIK Kubernetes 006: kubeadm

- Recording date: 2017-08-04
- Video: [https://www.youtube.com/watch?v=2Yyc2R8yDRo](https://www.youtube.com/watch?v=2Yyc2R8yDRo)
- Show notes:

    > In this episode Joe uses kubeadm to stand up a cluster using raw AWS instances.  He goes into some of the details of what is happening under the covers.  You can use this process to get Kubernetes set up on *any* set of linux machines.

    - Lachlan Evenson's videos
      - [Sonobuoy](https://twitter.com/LachlanEvenson/status/893563156324208641)
      - [Ark](https://twitter.com/LachlanEvenson/status/893509442750169088)
    - [Kubeadm docs](https://kubernetes.io/docs/setup/independent/create-cluster-kubeadm)
    - [Gist with commands I was copy/pasting](https://gist.github.com/jbeda/2317cbfdd6b75288254a79468ed30200)
    - [K8s Quickstart from Heptio repo (for reference)](https://github.com/heptio/aws-quickstart)
    - [AWS cloud provider notes (need to get these into official docs)](https://docs.google.com/document/d/17d4qinC_HnIwrK0GHnRlD1FKkTNdN__VO4TH9-EzbIY/edit#heading=h.2hif681swxfg)

## TGIK Kubernetes 005: Pod Params and Probes

- Recording date: 2017-07-28
- Video: [https://www.youtube.com/watch?v=xEdBSVaUtp4](https://www.youtube.com/watch?v=xEdBSVaUtp4)
- Show notes:

    > In this episode we cover the various parameters on the Pod object and how those interact to provide reliable service.  See Joe kill AWS instances out from under Kubernetes and have Kubernetes continue without missing a beat.  Learn how liveness and readiness probes work to make sure that services stay up and only serve traffic when they want to.  Watch Joe learn new things about Kubernetes that he didn't already know.

## TGIK Kubernetes 004: RBAC

- Recording date: 2017-07-21
- Video: [https://www.youtube.com/watch?v=slUMVwRXlRo](https://www.youtube.com/watch?v=slUMVwRXlRo)
- Show notes:

    > Here we talk about Authentication, Authorization and RBAC for Kubernetes.

    - [AWS Quick Start for Kubernetes by Heptio](https://aws.amazon.com/quickstart/architecture/heptio-kubernetes/)
    - [Jakub Scholz's guide to adding users with x509 certs](https://www.linkedin.com/pulse/adding-users-quick-start-kubernetes-aws-jakub-scholz)
    - [Kubernetes docs page on Authn](https://kubernetes.io/docs/admin/authentication/)
    - [Kubernetes docs page on Authz](https://kubernetes.io/docs/admin/authorization/)
    - [Heptio cheat page on RBAC](http://docs.heptio.com/content/tutorials/rbac.html)

## TGIK Kubernetes 003: Istio

- Recording date: 2017-07-14
- Video: [https://www.youtube.com/watch?v=WnDG-5cvEew](https://www.youtube.com/watch?v=WnDG-5cvEew)
- Show notes:

    > Not everything goes as planned, but with the help of the watchers we figure it out and get Istio up and running on Kubernetes.
    > A fix for the issue that we hit is outlined here: [https://github.com/istio/istio/pull/333](https://github.com/istio/istio/pull/333)
    > The link to Tim's presentation about Containers vs Pods: [https://twitter.com/thockin/status/885803327614840833](https://twitter.com/thockin/status/885803327614840833)

## TGIK Kubernetes 002: Networking and Services

- Recording date: 2017-07-07
- Video: [https://www.youtube.com/watch?v=PlnvxqKR28A](https://www.youtube.com/watch?v=PlnvxqKR28A)
- Show notes:

    > No show notes for episode 002

## TGIK Kubernetes 001: A Quick Tour

- Recording date: 2017-06-30
- Video: [https://www.youtube.com/watch?v=9YYeE-bMWv8](https://www.youtube.com/watch?v=9YYeE-bMWv8)
- Show notes:
    - [Quick Start for Kubernets by Heptio](https://aws.amazon.com/quickstart/architecture/heptio-kubernetes)
    - [Command line snippets](https://gist.github.com/jbeda/9a2097c726584560fa13f6c1ae13abfb)
    - [ksonnet](http://ksonnet.heptio.com)
    - [ksonnet on github](https://github.com/ksonnet)