+++
title = "Deploying OpenShift"
weight = 1
description = '''
'''
+++

One of the niceties of OCP is in the ease of deployment; at least, that’s the case for normal environments. Disconnected deployments are another matter! Generally, you have 3 ways to deploy OpenShift:

UPI

IPI

AI - Assisted Installer

The AI method is currently limited in available environments, focusing on On-Prem. However, when it is available, it is the easiest and most powerful deployment method. Otherwise, IPI is the best option if you don’t require to BYO resources.

Automation
Assuming you can’t use the AI method, you’ll want to bring automation to simplify the deployment process. IPI with the openshift_installer handles the majority of this for you, with it only needing a simple config file, any customizations, and access to the target environment. UPI, OTOH, is more difficult by definition.

UPI
The provisioning of necessary resources is entirely up to the user. Therefore, you need automation. IBM offers a handful of Terraform configs for deploying OCP to various environments.

[IBM Automation](https://w3.ibm.com/w3publisher/customersuccess/get-connected/red-hat-openshift-community/install-infra)