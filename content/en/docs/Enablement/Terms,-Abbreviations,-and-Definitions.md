+++
title = "Terms, Abbreviations, and Definitions"
linkTitle = "Terms, Abbreviations, and Definitions"
weight = 2
description = '''
Too many abbreviations? Check here!
'''
+++
noteOpenShift and OCP are often used interchangeably, both for their specific definitions as well as catch-all terms for the entire OpenShift ecosystem.

OpenShift and OCP are often used interchangeably, both for their specific definitions as well as catch-all terms for the entire OpenShift ecosystem.


## OpenShift Specific

* [ **OCP** ](https://access.redhat.com/documentation/en-us/openshift_container_platform/4.10/html/architecture/index) -  _OpenShift Container Platform_ 


    * The collection of components which form the OpenShift ecosystem. Below you will find an overview of this ecosystem with many examples.


    * OCP is the typical avenue for licensure of OpenShift.


    * Find the comparison between  _OKE_  and  _OCP_ [[here|OKE-vs-OCP]].



    

![Graph showing examples of components included in each OpenShift offering.](images/storage/OpenShift Ecosystem.png)
*  **OPP**  -  _OpenShift Platform Plus_ 


    * As shown above, OPP is all of OCP as well as  _RHACM_ ,  _RHACS_ ,  _Quay_ , and  _ODF_  (not shown)


    * These licenses are sold as an up-charge.



    
*  **BOP**  -  _BoxBoat’s OpenShift Practice_ 


    * BoxBoat’s Practices are similar to those in other Consulting firms, including IBM-C.


    * With the IBM Executive directive “OpenShift Everywhere”, there is a critical need for OCP resources within BoxBoat.


    * BoxBoat joined IBM-C with the premier expertise on a number of technologies, and we have the opportunity to add OCP to that list. This would exponentially increase our importance and potential earnings.



    
* [ **RHACM** ](https://access.redhat.com/documentation/en-us/red_hat_advanced_cluster_management_for_kubernetes/2.5/html/about/index) -  _Red Hat Advanced Cluster Management_ 


    * As shown above, allows for multi-cluster management including  _Ansible_  and pipelines ( _Tekton_ / _ArgoCD_ )


    * Deployed within OCP cluster, separate UI



    
* [ **Hybrid Cloud Console** ](https://console.redhat.com/)


    * AKA  _RH Console_  or  _OpenShift Cloud Console_ 


    * Management platform for many RH products, including OCP. See [summary](https://access.redhat.com/products/red-hat-hybrid-cloud-console) for more.


    * Contains  _OCP Cluster Manager_ - primary location for deploying initial OCP clusters, managing subscriptions, etc


    * Not to be confused with the OCP Console - a separate entity for each cluster - or [RHACM](#) - a customer-owned and deployed multi-cluster management platform.



    
    * Centralized dashboard of Insights, Utilization, etc of all environments.


    * Allows usage of Automation, creation of RHEL-based Images, etc.



    
* [ **RHACS** ](https://access.redhat.com/documentation/en-us/red_hat_advanced_cluster_security_for_kubernetes/3.70/html/architecture/index) -  _Red Hat Advanced Cluster Security_ grdfc n,b,.Previously known as  _Stackrox_  (now the OSS upstream instance)


    * Provides a full multi-cluster security suite with native integration.


    * Deployed within OCP cluster, separate UI



    
* [ **ODF** ](https://access.redhat.com/documentation/en-us/red_hat_openshift_data_foundation/4.10/html/red_hat_openshift_data_foundation_architecture/index) -  _OpenShift Data Foundations_ 


    * Previously OCS,  _OpenShift Container Storage_ 


    * Cluster based storage based on  _Ceph_ ,  _Nooba_ , and other technologies



    
* [ **OKD** ](https://www.okd.io/)


    * Upstream, community, OSS distribution of Kubernetes which OCP is built off of.


    * The  _CentOS_  _Stream_  to OCP’s RHEL (roughly)



    
* [ **OKE** ](https://docs.openshift.com/container-platform/4.10/welcome/oke_about.html) -  _OpenShift Kubernetes Engine_ 


    * The official base of OCP. 


    * The Fedora to OCP’s RHEL (roughly)


    * Find the comparison between  _OKE_  and  _OCP_ [[here|OKE-vs-OCP]].



    
* [ **OpenShift Local** ](https://access.redhat.com/documentation/en-us/red_hat_openshift_local/2.5/html/getting_started_guide/index)


    * Previously CRC -  _CodeReady Containers_ 


    * Minimal OpenShift cluster without license requirements, built to run on a developer’s personal machine.



    
* [ **OpenShift Dev Spaces** ](https://access.redhat.com/documentation/en-us/red_hat_openshift_dev_spaces/3.0/html/administration_guide/index)


    * Previously CRW -  _CodeReady Workspaces_ 


    * Cluster/Browser based IDE, built off of Eclipse CHE



    
*  **UPI** - [User-Provisioned Infrastructure](https://docs.openshift.com/container-platform/4.10/installing/index.html#installation-process_ocp-installation-overview)


    * Provision and manage cluster infrastructure


    * Either deploying to existing infrastructure, need highly-specific control, or environment doesn’t support IPI.


    * Must provide all infrastructure and resources.



    
*  **IPI**  - [Installer-Provisioned Infrastructure](https://docs.openshift.com/container-platform/4.10/installing/index.html#installation-process_ocp-installation-overview)


    * Install program performs infrastructure bootstrapping and provisioning.


    * Installer creates all networking, machines, OS, etc.



    


## Other Red Hat

*  **RHEL**  -  _Red Hat Enterprise Linux_ 


    * Red Hat’s supported distribution of Linux



    
*  **Fedora** 


*  **CentOS Stream** 


*  **Software Release Phases** 


    * TP - [Technical Preview](https://access.redhat.com/support/offerings/techpreview/)


    * TP features are provided with limited support scope



    
    * Dev Preview - Developer Preview


    * Contrary to TP, Dev Preview features affect the entire cluster. Any cluster utilizing Dev Preview is considered a Dev cluster with Dev support scope .



    
    * GA - General Availability


    * Available to the Public with full support scope.



    

    


## General Industry

*  **vCPUs**  - Similar to idea of Threads. generally 2 vCPUs per physical Core in a CPU.







*****

[[category.storage-team]] 
[[category.confluence]] 
