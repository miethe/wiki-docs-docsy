+++
title = "ARO - Standard - LZ Accelerator"
weight = 1
description = '''
'''
+++
## Source
Microsoft - Landing Zone Accelerator

[MSFT article](https://techcommunity.microsoft.com/t5/azure-developer-community-blog/announcing-landing-zone-accelerator-for-azure-red-hat-openshift/ba-p/3614057?utm_source=pocket_mylist)

[GitHub](https://github.com/Azure/aro-Landing-Zone-Accelerator)


## Environment Overview
This solution assumes a Platform Foundation w/ Azure already exists, or will be deployed using included automation. The environment is designed to be simple and secure, including typical resources a customer is likely to require. Of course, the solution favors Azure-native integrations over OCP/Red Hat.

Please see [Microsoft’s documentation](https://docs.microsoft.com/en-us/azure/cloud-adoption-framework/scenarios/app-platform/azure-red-hat-openshift/landing-zone-accelerator) for more information on the Platform Resources.


## Use Cases
This cluster provides a baseline ARO cluster from which most environments can be built. Microsoft’s  Landing Zone Accelerators are focused on MSFT offerings, naturally, and so automation is focused there. However, the resulting ARO cluster is just as functional for all other OCP-based workloads.


* Foundation for customized ARO clusters


* Standard, no-frills environment for simple workloads


* PoC for OCP, K8s, or Containerization, or even general Azure with various common potential integrations.




## Included OCP Components
This solution is a standard OCP deployment. 


## Automation
[GitHub - Secure Baseline Landing Zone Accelerator](https://github.com/Azure/ARO-Landing-Zone-Accelerator/tree/main/Scenarios/Secure-Baseline/Azure-CLI)


## Diagram
![](images/storage/image-20220912-214129.png)



*****

[[category.storage-team]] 
[[category.confluence]] 
