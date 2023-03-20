+++
title = "ROSA"
linkTitle = "ROSA"
weight = 1
+++
## What is it?
[ **ROSA** ](https://aws.amazon.com/rosa/) - Red Hat OpenShift Service on AWS


## Who is the Vendor?
AWS


### Pricing
[AWS ROSA Pricing](https://aws.amazon.com/rosa/pricing/)

Service Fees

|  **Node Role**  |  **Hourly Rate**  |  **Billable Unit**  | 
|  --- |  --- |  --- | 
| Worker | $0.171 | 4 vCPUs | 
| Control Plane or  _Required_  Infra | $0 | N/A | 

Annual Rate

|  |  **On-demand**  |  **1-year contract**  |  **3-year contract**  | 
|  --- |  --- |  --- |  --- | 
| Worker Node fee per 4 vCPU/Year | $1500 | $1000 | $667 | 

AWS Infrastructure FeesFees for Worker, Infra, and Control Plane Nodes, storage, and network.


### Minimal Deployments


|  **Node Role**  |  **Single- or Multi-AZ**  |  **Min Quantity**  | 
|  --- |  --- |  --- | 
| Worker | Single | 3 | 
| Infra | Single | 3 | 
| Control | Single | 3 | 
| Worker | Multi | 2 | 
| Infra | Multi | 2 | 
| Control | Multi | 3 | 


## Technical Description

### Differences from base OCP
 


## Documentation
[RH ROSA Docs](https://docs.openshift.com/rosa/welcome/index.html)

[AWS ROSA FAQ](https://aws.amazon.com/rosa/faqs/)


### Requirements
[Documentation](https://docs.openshift.com/rosa/rosa_planning/rosa-limits-scalability.html)

ROSA has the following minimum HW requirements:



|  **Node Role**  |  **Min Nodes**  |  **Min Node Types**  |  **Min cores**  |  **Min RAM**  |  **Min Storage**  |  **User-accessible?**  | 
|  --- |  --- |  --- |  --- |  --- |  --- |  --- | 
| Master | 3 | m5.2xlarge |  vCPUs | GB | GB |  | 
| Worker | 2 |  |  vCPUs | GB | GB |  | 
| Infra | 3 | r5.xlarge |  vCPUs | GB | GB |  | 


### Install
Install Docs



*****

[[category.storage-team]] 
[[category.confluence]] 
