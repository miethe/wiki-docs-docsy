+++
title = "ICCA Journeys"
linkTitle = "ICCA Journeys"
weight = 2
description = '''
Information on the IBM Consulting Cloud Accelerator
'''
+++

## What is ICCA, and what are Journey’s!?
 **ICCA**  is the IBM Consulting Cloud Accelerator. In short, it is a collection of assets purpose built for “cloud transformation”. ICCA contains an ever-growing list of common solutions which might be performed for a customer by HCS, each termed a  **Journey** . The idea is that anything which can and often is reproduced within or across customers, should have an associated Journey to enable and potentially standardize future solutions.  Some examples are as follows:


* [Rehost Oracle DB to AWS EC2](https://pages.github.ibm.com/hcw/rehost-legacy-playbook/journeys/rehost_oracle_ec2/)


* [Rehost Windows based applications to OCP](https://pages.github.ibm.com/hcw/rehost-legacy-playbook/journeys/rehost_windows_apps_ocp/)


* [Refactor apps on EKS/AKS to OCP](https://pages.github.ibm.com/hcw/refactor-apps-playbook/journeys/migrate_eks_aks_to_ocp/)


* [Containerize .NET Framework to .NET Core](https://pages.github.ibm.com/hcw/replatform-microsoft-playbook/journeys/containerize_NET_framework_to_NET_core/)




## Important Links
[ICCA FAQ](https://pages.github.ibm.com/hcw/faq/questions/general/)

[ICCA W3 site](https://w3.ibm.com/w3publisher/ibm-consulting-cloud-accelerator/)

[ICCA Sandbox](https://assess-tool.ose.ibmsandbox.io/home) - (sandbox version of the actual web app, not for prod) Best way to examine individual Journey and experience how ICCA is used.

[Internal GitHub Pages on ICCA](https://pages.github.ibm.com/hcw/main/#overview) - (for some reason the main page links were recently broken. [Start from here](https://pages.github.ibm.com/hcw/rehost-legacy-playbook/journeys/) for now, or remove /main/ in the url.) Easiest way to review the Journeys and relevant materials quickly. 

[Content+](https://w3.ibm.com/services/contentplus/home.html) - Generally informative site for IBM-C


* [What is Content+?](https://w3.ibm.com/services/lighthouse/spaces/view/content-plus-guide/what-is-content)


* [Hybrid Cloud Journey’s - GTM Handbook](https://w3.ibm.com/services/contentplus/initiatives/hcs-handbook.html) (w/e this actually is, lots of informative docs and links)


* [HCS Offerings](https://w3.ibm.com/services/contentplus/search.html?category=Offerings)


* [Hybrid Cloud Journeys](https://w3.ibm.com/services/contentplus/initiatives/red-hat.html#hybrid_cloud_journeys) (OpenShift)


* [RH Page](https://w3.ibm.com/services/contentplus/initiatives/red-hat.html)


* Lots more!




## How do we use ICCA?
ICCA’s first use case is as a catalog of services in HCS. When a seller is discussing needs with a customer, they can pull up ICCA and review relevant Journey’s that the customer might be interested in. Of course this is limited to the Journey’s already created, but it is the lowest hanging fruit to finding a possible solution. When a Journey is targeted, it often contains GTM content to assist the AE in sealing the deal. This includes value add, datapoints, customer pain points the Journey could resolve, differentiators, even slide decks and other sales collateral.

After a deal is sold, the target Journey can be used for the Solutioning and Architecture. Each Journey generally includes a suite of tools to assist in scoping a deal. You follow the guides, utilize custom built calculators, etc to determine the scope of a project. The Journey will likely include reference architectures to provide a foundation for a solution, various architectural decisions to be made, common challenges and risks, etc.

After being solutioned comes delivery. Each Journey includes some degree of automation already developed to assist with the delivery process. Many in the Hybrid Cloud space utilize MTV (based on Konveyor), Move2Kube, etc. It is also common to find a mix of IBM-developed, community OSS, and vendor provided tooling related to the task at hand.

Finally, after solution deployment, the Journey will wrap up with Day 2 Ops. As expected, this section consists of a mix of automation and references related to common Day 2 Ops often performed with the relevant Journey. For example, if you just rehosted an application to OCP, you might setup storage, observability, security, etc. The Journey will provide varying degrees of resources around a subset of these tasks.

In addition to all of the above, each Journey generally includes some degree of additional references, such as past client implementations, documentation and demos, reference architecture and integrations, and other automation or relevant tooling. 





*****

[[category.storage-team]] 
[[category.confluence]] 
