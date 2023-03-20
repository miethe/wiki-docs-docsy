+++
title = "OpenShift Pipelines"
weight = 6
categories = ["Technical", "Integrations"]
description = '''
'''
+++
## What is it?
OpenShift Pipelines

OpenShift Pipelines provides a native CI/CD platform for creating pipelines for the entire SDLC. Based upon Tekton, Pipelines utilizes CRDs, such as Tasks, to break up components of pipelines into reusable and shareable k8s-native blocks. Together with [[OpenShift GitOps|OpenShift-GitOps]], Pipelines provides a fully featured CI/CD option for OCP-based environments. Also, with the integration of [Tekton Chains](https://docs.openshift.com/container-platform/4.11/cicd/pipelines/using-tekton-chains-for-openshift-pipelines-supply-chain-security.html)/Cosign, Pipelines is capable of native supply chain security with image verification and provenance. Other native integrations include RHACS for additional security (including CVE scanning, admission controllers, policy enforcement, etc), OCI/Quay, Pipelines as Code w/ GitLab/GitHub/etc, GitOps, Logging, etc.


## Red Hat’s Description
Red Hat OpenShift Pipelines is a cloud-native, continuous integration and continuous delivery (CI/CD) solution based on Kubernetes resources. It uses Tekton building blocks to automate deployments across multiple platforms by abstracting away the underlying implementation details. Tekton introduces a number of standard custom resource definitions (CRDs) for defining CI/CD pipelines that are portable across Kubernetes distributions.


## Core Upstream Technology
[Tekton](https://tekton.dev/)


### Additional GitHub links

* [OpenShift Pipelines Project Page](https://github.com/openshift-pipelines)


* [RH Pipelines Catalog](https://github.com/redhat-developer-demos/pipelines-catalog)




### Pipelines Demos

* [OpenShift Pipelines Workshop](https://github.com/redhat-developer-demos/openshift-pipelines-workshop) ([doc](https://redhat-developer-demos.github.io/openshift-pipelines-workshop/))


* [Istio and Knative Pipelines Demos](https://github.com/redhat-developer-demos/tutorials-pipelines)


* [Pipelines Tutorial](https://github.com/openshift/pipelines-tutorial)




## Documentation

### Product Documentation
[OpenShift Pipelines](https://docs.openshift.com/container-platform/4.11/cicd/pipelines/op-release-notes.html)


### Technical Deep Dive

### Others

## Pipelines as Code

* [Pipelines as Code](https://pipelinesascode.com/)


* [Pipelines as Code flow](https://github.com/openshift-pipelines/pipelines-as-code)


* [PaC Announcement](https://cloud.redhat.com/blog/create-developer-joy-with-new-pipelines-as-code-feature-on-openshift#:~:text=What%20is%20this%20new%20feature,in%20terms%20of%20release%20updates.)


* [PaC Docs](https://pipelinesascode.com/docs/guide/)


    * [GitLab](https://pipelinesascode.com/docs/install/gitlab/)


    * [GitHub](https://pipelinesascode.com/docs/install/github_apps/)



    
* [Example PaC release pipeline](https://blog.chmouel.com/2021/07/01/how-to-make-a-release-pipeline-with-pipelines-as-code/)


* [PaC Demo - RH](https://youtu.be/3HdRVCqPdg8?t=1810)




## Relevant Courses

### Partner Portal

### Community

## Articles
[Introducing OpenShift Pipelines](https://cloud.redhat.com/blog/introducing-openshift-pipelines)


## Notes


*****

[[category.storage-team]] 
[[category.confluence]] 
