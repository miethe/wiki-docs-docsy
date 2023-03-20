+++
title = "ARO Full-scale, all services"
weight = 2
description = '''
'''
+++
## Source
BoxBoat - Internally Developed by Nick Miethe


## Original Customer
State of Washington


## Environment Overview
This cluster is based on ARO, Azure’s Managed OpenShift instance. It is based in a Private network and vNet Paired with public subnets for access. 

The primary cluster is based across 3 AZs, with an additional standby DR cluster in the assigned DR Region; additionally, the solution allows for N additional clusters, with the only current connection being with RHACS and RHACM.

Several Azure-native integrations are utilized in this solution to optimize performance and availability. Examples are Azure AD, managed SQL DB, Observability, Storage, etc.


## Use Cases

* Customer requires moderate availability and failure resistance, but can sustain short periods of downtime to save considerable cost.


* Customer doesn’t have the resources, or the desire, to manage their own underlying infrastructure. 


* Customer will be performing app development within the cluster.




## Included OCP Components
The below list doesn’t necessarily include standard Day 2 Ops.


* RHACS


* RHACM


    * Submariner


    * MCH


    * Admission Controller



    
* OpenShift GitOps


* OpenShift Pipelines


* ARO CSI


* OCP Registry


* OpenShift Service Mesh (Istio)


* MuleSoft


* OpenShift Monitoring


* OpenShift Logging


    * Elastic Operator


    * Loki Operator



    


## Diagram
122966435851ARO_API_Services11oHgXzFDlr4fdTrscqDmEIami--0m-jrOhttps://boxboat.atlassian.net/wikiARO_API_Services0GDrive7gcUSTIZ7YSJ5vT40chW 123731autohidden2075

*****

[[category.storage-team]] 
[[category.confluence]] 
