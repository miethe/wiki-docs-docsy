+++
title = "OpenShift Core Components"
weight = 1
summary = '''
Like most fully-featured Kubernetes deployments, OCP consists of various core components. These include things such as the CNI, CSI, container runtime, etc. These aren’t often directly modified or interacted with, but are still important to understand as Architects and Engineers.
'''
description = '''
Includes core Kubernetes things such as the CNI, CSI, container runtime, etc.
'''
+++
### Host OS

|  **Role**  |  **Component**  |  **Description**  | 
|  --- |  --- |  --- | 
| OS |  _RHCOS_  | Custom RHEL-image specifically built for OCP. | 
| Firstboot configuration |  _Ignition_  | initial boot and configures machines | 
| Container Runtime |  _CRI-O_  | Kubernetes native Docker replacement, optimized for OCP. | 
| Node Agent |  _Kubelet_  | launches and monitors containers | 

### Control Plane

### Operators
