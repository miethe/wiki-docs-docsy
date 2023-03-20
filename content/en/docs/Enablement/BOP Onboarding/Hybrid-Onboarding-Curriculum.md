+++
title = "Hybrid Onboarding Curriculum"
weight = 4
description = '''
'''
+++
### Instructions

* Follow instructions in [[Initial To-Dos|Initial-To-Dos]]


    * Ie: Sign-up for [Partner Portal](https://partnercenter.redhat.com/)



    
* If relevant, follow tasks in Trello card. See an example Onboarding card below:



https://trello.com/c/hp6I0lXs


## General Notes

* Only take courses for OCP 4.x, not 3.x


* There are 2 types of courses within  _OPEN_ :  **Partner Training**  and  **Red Hat Enterprise Training**  (as Partners, we get complementary access to the latter Paid courses via the Partner Portal).


    * In this section, the former will be denoted at  **PT** , the latter as  **RHET** .


    * The primary courses will be the  **Red Hat Enterprise Training** 


    * These are denoted by 2 letters and 3 numbers in the course title. OCP-specific courses use  _DO_ , RHEL use  _RH_ , etc. EG:  _DO280_ .



    
* Once you enroll in your first  **PT**  course ( _if applicable_ ) which contains labs, you will shortly after receive an email with your login info to OpenTLC, the lab environment, from  _Red Hat OPEN Training Learning Cloud •_ [ _noreply@opentlc.com_ ](mailto:noreply@opentlc.com)


    * When beginning a  **PT**  course, it is recommended to first start the lab to initiate the provisioning process, then return to the content while waiting.



    
* The content from [ **Red Hat Developer** ](https://developers.redhat.com/topics) has been known to be buggy, especially the RHEL modules. If you run into issues, just skip it! These were added as complimentary rather than primary modules.


* For all general questions about Onboarding and OpenShift, please ask in [ _#eng-openshift-onboarding_ ](https://boxboat.slack.com/archives/C02SYSWDZEX). Someone else has probably had the same question or will in the future.


* When reading documentation from Red Hat, make sure you have chosen the latest release.



 **Section 1 - OpenShift Fundamentals** 
### Summary
Container and K8s fundamentals with an OpenShift focus, using Podman and OCP. This section utilizes DO180 and DO280 to focus on fundamentals with RHEL and Kubernetes/containerization, slowly progressing further into the OpenShift ecosystem as you proceed. Feel free to spend as much, or little, time on this section as you deem necessary.

:info:atlassian-info#FFEBE6Individuals with considerable prior experience with Containers and Kubernetes may find course  **DO180**  to be redundant. Consider briefly reviewing the topics for anything novel, and then move on to the next course.


### Red Hat OpenShift I: Containers & Kubernetes (DO180) 
Introduction to building and managing containers for deployment on a Kubernetes and OpenShift 4 cluster.

note This is the corresponding course for the RH exam, [ **EX180** ](https://www.redhat.com/en/services/training/ex180-red-hat-certified-specialist-containers-kubernetes-exam). If you are interesting in pursuing RH certifications, consider reviewing this course to sit for that initial exam. 

[[Exam Prep Resources|EX180]]

 This is the corresponding course for the RH exam, [ **EX180** ](https://www.redhat.com/en/services/training/ex180-red-hat-certified-specialist-containers-kubernetes-exam). If you are interesting in pursuing RH certifications, consider reviewing this course to sit for that initial exam. 

[Exam Prep Resources](/wiki/spaces/OSP/pages/2288353289/EX180)


### Red Hat OpenShift Administration II: Operating a Production Kubernetes Cluster (DO280)
Configure, manage, and troubleshoot OpenShift clusters and containerized applications.

This course teaches you how to configure, troubleshoot, and manage OpenShift Container Platform (OCP). This hands-on, lab-based course shows you how to verify the successful installation of a cluster, manage it on a day-to-day basis, and troubleshoot the deployment of containerized applications. 

Based on:


* RHEL 8.2


* OCP 4.6



noteThis is the corresponding course for the RH exam, [ **EX280** ](https://www.redhat.com/en/services/training/ex280-red-hat-certified-specialist-in-openshift-administration-exam) aka COA, the equivalent of CKA. This is currently the core OpenShift certification, so consider focusing on this course if it’s something you’re interested in pursuing.

This is the corresponding course for the RH exam, [ **EX280** ](https://www.redhat.com/en/services/training/ex280-red-hat-certified-specialist-in-openshift-administration-exam) aka COA, the equivalent of CKA. This is currently the core OpenShift certification, so consider focusing on this course if it’s something you’re interested in pursuing.

 **Section 2 - OpenShift Configuration and Deployment** 
### Summary
Administration of OpenShift clusters, deploying optimized applications, and advanced workshops. 

This is where the meat of Onboarding resides, and when the tasks begin to dive deeper into advanced topics. Based on your own prior experience and comfort in this space, consider spending the majority of your Onboarding time on the courses in this section. 

The 2nd half of this Section, Knowledge Gap-Filling, is purposefully open-ended to allow each person the opportunity to find and pursue their own interests within OpenShift. OCP is a massive ecosystem with Kubernetes and containers consisting of only a very small piece. The true interesting parts are in the integrations.


### Red Hat OpenShift Administration III: Scaling Kubernetes Deployments in the Enterprise (DO380)
Plan, implement, and manage OpenShift clusters at scale.

This course expands upon the skills required to plan, implement, and manage OpenShift clusters in the enterprise. You will learn how to support a growing number of stakeholders, applications, and users to achieve large-scale deployments. 

Based on:


* OCP 4.6




### Knowledge Gap-Filling section from OpenShift Full Onboarding Week 2: scenarios on IBM Cloud and RH Developer site. 
As mentioned in the Section Summary, the below Options are simply that, options. Feel free to work with your mentor to choose your own adventure here within the OCP ecosystem, whether it be self-directed, hands-on labs in OCP, or studying more advanced topics. 


* Provision a free OCP cluster on IBM Cloud following the instructions linked [here](https://developer.ibm.com/articles/deploy-a-game-server-on-red-hat-openshift/#step-2-provision-a-free-openshift-environment). If you have any trouble or need more time (the sandbox lasts 60min), request a  _SNO_  cluster from your mentor.


    * Deploy an online game server to OCP via [IBM Cloud](https://developer.ibm.com/articles/deploy-a-game-server-on-red-hat-openshift/).


    * Secure routes with TLS for OpenLiberty apps hosted on OCP via [IBM Cloud](https://developer.ibm.com/tutorials/secure-routes-with-passthrough-tls-for-web-applications-using-open-liberty-on-red-hat-openshift/). 



    
* Lab Scenarios from Full Onboarding Week 2 on SNO cluster. 


* Choose advanced OCP customization course from Training Portal:


    *  DO288, DO381, Service Mesh, Data Foundations, etc.



    




## Appendix

### Red Hat Enterprise Training Course List
Primary
* DO180 - Red Hat OpenShift I: Containers & Kubernetes


* DO280 - Red Hat OpenShift Administration II: Operating a Production Kubernetes Cluster


* DO380 - Red Hat OpenShift Administration III: Scaling Kubernetes Deployments in the Enterprise



Additional
* DO101 - Introduction to OpenShift Applications


* DO240 - Cloud-Native API Administration with Red Hat 3scale API Management


* DO288 - Red Hat OpenShift Development II: Containerizing Applications


    * Corresponding Certification exam, [EX288](https://www.redhat.com/en/services/training/ex288-red-hat-certified-specialist-openshift-application-development-exam)



    
* DO316 - Managing Virtual Machines with Red Hat OpenShift Virtualization


* DO322 - Red Hat OpenShift Installation Lab


* DO326 - Red Hat OpenShift Migration Lab


* DO328 - Building Resilient Microservices with Istio and Red Hat OpenShift Service Mesh


* DO370 - Enterprise Kubernetes Storage with Red Hat OpenShift Data Foundation


* DO374 - Developing Advanced Automation with Red Hat Ansible Automation Platform


* DO378 - Red Hat Cloud-Native Microservices Development with Quarkus




### Course Descriptions
25namehttps://drive.google.com/drive/u/0/folders/1G5S7Wuw7iO0BVKPdrFnFPL4lbZBYpYT6



*****

[[category.storage-team]] 
[[category.confluence]] 
