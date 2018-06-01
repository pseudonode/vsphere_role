# vsphere role

This repo contains Ansible roles and playbooks to orchestrate end to end network and virtualization infrastructure.

This collection allows for the creation of Cisco ACI constructs as well as VMWARE vSphere constructs.

The repository consists of one role:
- vsphere

# VSPHERE Role Details

The vsphere role contains a /tasks playbook that allows for the creation of one or multiple VMs from a VM Template leveraging the vmware_guest module

VM data is defined inside of host_vars and VM hostnames are defined inside if the inventory file

The vSphere data model is defined inside of the host_vars folder of the project
