+++
title = "Trying OpenShift"
weight = 1
slug = "trying-openshift"
description = '''
What is the best way to try OpenShift?
'''
+++
## Summary
There are many ways to try OpenShift, likely with a best option for every need and use case. I recommend that everyone familiarize themselves with the various technologies mentioned below, such as the difference between OKE/OKD/OCP. These definitions can be found at [Terms, Abbreviations, and Definitions]({{< ref "../Terms,-Abbreviations,-and-Definitions.md" >}}). Also, for more information on each individual offering of OpenShift, check the below page tree:

[[OpenShift Offerings|OpenShift-Offerings]]

[[OpenShift Offerings|OpenShift-Offerings]]1


## Which Option Should I Use?
:info:atlassian-info#FFBDADGoing forward, (outside of personal OCP Local/NFRs usage) most OpenShift cluster needs should go through [TechZone](http://techzone.ibm.com), the IBM internal platform hosted on IBM Cloud. This provides a variety of hosted resources, including OCP (ROKS, IPI/UPI on VMware, etc), free to employees.

See below for instructions on TechZone. If you have requirements which fall outside of the TZ parameters, please utilize the below chart, or reach out to Nick for other options.

Remember, while usually full OCP/SNO has a license cost in addition to the resource cost, everyone gets a 60 day free trial per every cluster; plus, as Partners/IBMers we also may use NFRs as necessary for free licenses.

The below table provides our recommendations specific to BoxBoat/IBM, and only with regards to the best option for Enablement, Demos, PoCs, simple R&D, etc. These do not apply to Production or for customer recommendations.



|  **Deployment**  |  **Full OCP Features**  |  **Why Use?**  |  **BYO Dedicated Resources? Cloud or on-prem**  | 
|  --- |  --- |  --- |  --- | 
|  **Recommended**  | 
| [[ **OpenShift Local** |OpenShift-Local]] **(prev CRC)**  | No; see the linked page for more info. |  _Only for enablement, R&D, and simple demos._ This is an excellent way to try OCP on your own device, such as a laptop, while still getting a majority of the target functionality.  | No | 
| [[ **SNO** |SNO]] **(Single Node OpenShift)**  | Yes; except for those requiring multi-nodes, including HA, auto-scaling, and node types. | SNO is the ideal way to trial OCP in most situations. It is (nearly) fully-featured and very stable. Consider this route for extended enablement and R&D sessions | Yes; minimal resources | 
| [[ **MicroShift** |MicroShift]] |  |  | No/Yes | 
| [[ **IBM Open Labs** |IBM-Open-Labs]] | Yes, to a point; while there is a time limit like the RH Dev Sandbox, the IBM lab actually provides admin access to the cluster. Thus you have nearly full control of everything outside of modifying the machines. | Great way for a brief trial of OpenShift. Limited to only 60 minutes of active use per session, it’s not the best option for extended trials or learning through cluster configuration. However, it does allow deploying workloads through any standard method, including Operators. | No; 2 free Nodes each with 4 vCPUs, 16GB RAM, and 125GB storage. | 
|  **Specific Use Cases**  | 
|  **Full OCP**  | Yes | Obviously, this is the absolute best way to try every feature of OCP. However, due to resource requirements and deployment complexity, this should only be used if one’s needs exceed the Recommended offerings. | Yes | 
|  **RH Dev Sandbox**  | No; while the Sandbox is easy and based on a live, full OCP cluster, the allowed capabilities are severely limited in scope. |  | No | 
|  **Generally Not Recommended**  | 
|  **Minishift**  | No | While this was replaced by OpenShift Local for 4.x, Minishift is still the best option for testing 3.x. | No | 
|  **OKD**  | No | OKD is an excellent option for those in the community. However, at BoxBoat/IBM, OKD should really only be used if one is specifically interested in OKD vs OCP, simply because we have NFRs for OCP. | Yes | 




## IBM Tech Zone 
IBM [TechZone](https://techzone.ibm.com/decisionpoints) is a platform which provides demos, environments, and other content to IBM employees. These platforms are hosted on IBM Cloud and other environments. 


### OpenShift
There are several OCP offerings available for our usage, with 2 primary resources:


* [Custom ROKS](https://techzone.ibm.com/resource/custom-roks-vmware-requests) - IBM Cloud-managed OCP (like ARO or ROSA)


* [OCP Gymnasium](https://techzone.ibm.com/resource/ocp-gymnasium) - OCP on VMWare on IBM Cloud



ROKS - Most should choose thisThere are 4 options to deploy:


*  **Managed OpenShift cluster (ROKS) in IBM Cloud (“classic”) with NFS support** - Primary option


* Managed OpenShift cluster (ROKS) in IBM Cloud (VPC/"Gen2") with OCS support


* Self-Managed OpenShift cluster (VMware in IBM Cloud) with ODF support


    * UPI or IPI provisioned



    

This provides the most straightforward option to obtain an OCP cluster, with minimal pre-requisite work or ongoing admin tasks, being a managed offering.

Notably, this option does allow for [[ODF|OpenShift-Data-Foundation]] testing, and also provides access to a fully self-managed option.

OCP GymnasiumOCP Gym provides an isolated VMware environment with vSphere access via Bastion. It allows provides pre-configured OCP Installers and Pak for RHEL, as well as pfSense. The general Architecture is below.

![](images/storage/image-20230103-185731.png)OCP Gym requires more prior work to deploy an OpenShift cluster, however it allows for full control of the entire process and platform. Therefore, this is the ideal solution for deeper dives into OpenShift and the install/configuration process.








### Duration/Purposes
There are 5 uses cases for TZ resources, each with its own Reservation Durations, as seen in the below image:

![](images/storage/reservation policy.png)The 1st 2 Purposes are for individual usage, with the last 3 for customer usage (requires ISC). Each type defaults to a 3 day reservation and allows up to 2w of usage before de-provisioning. All also allow providing an ISC for an extension of up to 3 months.


### Provisioning
Provisioning through TechZone is fairly straightforward, especially with the ROKS method. After following the steps on the page, you should receive an email with a specific IBM Cloud account. This will link to your existing IBM Cloud account if you have one, but the billing is not associated.



*****

[[category.storage-team]] 
[[category.confluence]] 
