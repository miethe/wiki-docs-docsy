+++
title = "Networking"
weight = 1
description = '''
'''
+++

## Core Network

### SDN

### OVN

## LoadBalancer

### On-prem/Baremetal

[MetalLB](https://metallb.universe.tf/) Deployed via [MetalLB Operator](https://github.com/openshift/metallb-operator).

Decent [Video](https://www.youtube.com/watch?v=8RQBt9y2xY4&t=0s) helping to explain.

2 options for using MLB:
* L2 Config
    * Utilizes vIPs.
* BGP Config
    * More performant and better for Production
    * Requires a BGP-configured and -capable Router.

#### Deployment

* Deploy MLB Operator
* Deploy MLB CR via Operator into metallb-system project.
* Deploy IPAddressPool with target range.
* Deploy L2Advertisment CR matched to above Pool.
* Follow OCP specific tasks in [docs](https://metallb.universe.tf/installation/clouds/) to modify the Speaker and Controller as necessary.
* All current and future services of type: LoadBalancer should now receive an ingress IP from the above IP Pool.

## Cloud

