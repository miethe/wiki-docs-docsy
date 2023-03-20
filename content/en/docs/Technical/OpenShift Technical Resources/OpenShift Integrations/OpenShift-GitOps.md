+++
title = "OpenShift GitOps"
weight = 3
categories = ["Technical", "Integrations"]
description = '''
'''
+++
## Core Upstream Technology
[ArgoCD](https://argo-cd.readthedocs.io/en/stable/)


### Additional GitHub links
[OCP GitOps Operator](https://github.com/redhat-developer/gitops-operator)


## Documentation

### OCP GitOps vs ArgoCD


| Features | GitOps Operator | Argo CD Community Operator | 
|  --- |  --- |  --- | 
| Default Cluster Argo CD instance | ✅ | ❌ | 
| Cluster Argo CD instances in namespaces defined by envrionment variable ARGOCD_CLUSTER_CONFIG_NAMESPACES | openshift-gitops | ❌ | 
| Cluster Configuration RBAC/Policy Rules | All APIGroups,Resources,get,list,watch Verbs appended with admin ClusterRoles. Additional APIGroups: operator.openshift.io,user.openshift.io, config.openshift.io, console.openshift.io, machine.openshift.io, machineconfig.openshift.io, compliance.openshift.io, rbac.authorization.k8s.io, storage.k8s.io, etc. | All APIGroups,Resources,Verbs | 
| Integrated with OpenShift Console Environments page for visualizing GitOps environments and applications | ✅ | ❌ | 
| Air-gapped environments | OCP | ❌ | 
| Installed tools | helm 3, kustomize | helm 2 and 3, kustomize, ksonnet | 
| Single Sign-on | RHSSO, Dex | Keycloak, Dex | 
| Redis Server | Redis 5, Secure connection is not yet supported | Redis 6 | 
| ArgoCDExport | ❌ | ✅ | 
| Installation Modes | All Namepaces | Single, All Namespaces | 
| Support for Kubernetes | ❌ | ✅ | 
| Maintained by | Red Hat | Community | 


### Access Documentation
OpenShift [GitOps Docs](https://docs.openshift.com/container-platform/4.11/cicd/gitops/gitops-release-notes.html)


### Technical Deep Dive
https://drive.google.com/file/d/1DKCFQrSIfAwJQd7ISW5-WVxbAi9XioVs/view?usp=drivesdk300true
### Others

* https://drive.google.com/file/d/1ENRBn_eS92Y3wk4ISmyq8C3CBA3Ujwcj/view?usp=drivesdk


* [Nubenetes](https://nubenetes.com/argo/)


* [GitOps Happy Hour](https://www.youtube.com/watch?v=o03m-1FHhDI&list=PLaR6Rq6Z4IqfGCkI28cUMbNhPhsnj4nq3&index=11&t=10s)


* [Pipelines and GitOps GA](https://cloud.redhat.com/blog/openshift-pipelines-and-openshift-gitops-are-now-generally-available?extIdCarryOver=true&intcmp=7013a000002D1gVAAS&sc_cid=701f2000001OH7EAAW)


* [GitOps and RHACM](https://cloud.redhat.com/blog/understanding-gitops-with-red-hat-advanced-cluster-management?extIdCarryOver=true&sc_cid=701f2000001Css5AAC&intcmp=7013a000002D1gVAAS)




## Relevant Courses

### Partner Portal

* [Config Mgmt at Scale with GitOps](https://training-lms.redhat.com/sso/saml/auth/rhopen?RelayState=deeplinkoffering%3D45035061) (video)




### Community

* [Develop with GitOps](https://developers.redhat.com/courses/gitops)


* [Getting Started with ArgoCD and OpenShift GitOps Operator](https://developers.redhat.com/courses/gitops/getting-started-argocd-and-openshift-gitops-operator)




## Notes




*****

[[category.storage-team]] 
[[category.confluence]] 
