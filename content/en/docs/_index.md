+++
title = "BOP Wiki"
linkTitle = "BOP Wiki"
weight = 1
description = '''
**Welcome to BoxBoat’s OpenShift Practice! (BOP)** Here you can find resources related to BOP, including Onboarding, curated documentation, collateral, etc.
'''
+++

{{% pageinfo color="primary" %}}
This site is still a WIP; some links may be broken, and formatting will be messy.
{{% /pageinfo %}}

## What is OpenShift?
OpenShift is simply, at its core, Red Hat’s opinion on Kubernetes. OpenShift is based on the latest upstream Kubernetes version, with various enhancements on top. Usually, these enhancements eventually make their way into later k8s versions.In fact, many of the core Kubernetes features were forked from, or inspired by, OpenShift functionality; ie, Ingress.

OpenShift was first released in 2011 as a proprietary Linux container-based PaaS, but was quickly became open-source. OpenShift v3 was eventually released as a major refactor based upon Kubernetes, which had recently been released. OpenShift was moved to its current, and most powerful, form with v4, shifting to CRI-O, Podman, and Buildah, along with other major architectural changes. OpenShift is currently on  {{< param "ocp_version" >}}.



However, there’s more to OpenShift than a few new features, which leads into OpenShift Container Platform (OCP). OCP is more than a simple flavor of Kubernetes; it is an entire ecosystem for the development and deployment of applications. With traditional k8s deployments, each individual component must be chosen, integrated, and maintained in order to create a proper and fully-featured devops infrastructure. OCP, however, provides such native integrations out-of-the-box from Day 1, with included offerings such as OpenShift Pipelines (based on Tekton & ArgoCD), Logging, Security (Stackrox), Service Mesh (Istio-based), and many others.

One primary advantage with these integrations that differentiates OCP from other similar services, is where every single component is configurable, optional, and modifiable. That means you can use as much, or as little, of the RH-offered integrations as you like, and bring your own when desired.

For more info on common OpenShift terms and abbreviations, check out this [page]({{< ref "/terms-abbreviations-and-definitions" >}}).

{{% alert title="Deploying OCP" color="info" %}}
If you’d like to try OpenShift, check our page to determine which version will work for you!

[Trying OpenShift]({{< ref "/trying-openshift" >}})
{{% /alert %}}

{{% alert title="Where to Start?" color="secondary" %}}
If you’re new, start with the Initial Tasks!

[Initial To-Dos]({{< ref "/initial to-dos" >}})
{{% /alert %}}


## What is the Mission of BoxBoat’s OpenShift Practice?
BOP’s role is multi-faceted, like all Practice areas at BoxBoat. However, there are 3 core directives on which BOP focuses its efforts.

1. Enablement & Evangelization - Both Engineering and Sales. Both Internal and External
2. Ensuring Pre-sales & Delivery Excellence
3. Navigating GTM Strategy
## Slack Channels
BoxBoat
* [#eng-openshift](https://boxboat.slack.com/archives/C6A002Q0L)
* [#eng-openshift-onboarding](https://boxboat.slack.com/archives/C02SYSWDZEX) (for all things OpenShift learning, not just New Hires)
* [#sales-openshift](https://boxboat.slack.com/archives/C02CVV1Q8FN)
* [#partner-redhat](https://boxboat.slack.com/archives/C02CPP6LWKU) (largely deprecated, use #eng-openshift for most purposes)

IBM
* [#americas-ocp-elite](https://ibmconsultingamericas.slack.com/archives/C028M3G84AU)
