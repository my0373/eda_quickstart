# EDA Quickstart
This doc is designed to help you set up Red Hat Event Driven Automation using the Red Hat Developer subscription.

This is not for production use! The developer license doesn't support it, the deployment sizing and approach I'm using is not idea. This is for testing only :) 

## Create a Red Hat Developer subscription

Firstly, create your Red Hat Developer subscription here.

https://developers.redhat.com/register

## Download the RHEL 9 Base ISO for installation
You can use RHEL 8, or one of the cloud distributions of RHEL. Personally, I like RHEL 9. :) 

https://developers.redhat.com/products/rhel/download#getredhatenterpriselinux7163

## Create the VM
The sizing I will use for the VM is a 4xvCPU with 16GB RAM. I'll be using the [Proxmox](https://www.proxmox.com/en/) hypervisor.

## Containerised all in one installation of AAP v2.5
In days gone by, to install EDA, you probably had 3 VM's. 

* The Controller VM
* The Hub VM
* The EDA VM
* Perhaps some execution nodes (I'll update this with the new terminoligy when I gete a chance)

We now have the luxury of all of these components being containerised and deployable, with a simple Postges DB for testing purposes.

The document I'll be following is here. 

https://docs.redhat.com/en/documentation/red_hat_ansible_automation_platform/2.5/html-single/containerized_installation/index

More to come!