# demo

This is a demo branch for deployment and setting up a coreDNS service running in docker on photonOS.

## Project

The project was to deploy, configure and run coreDNS in docker on photonOS
using Ansible.
The goal was/ is to get acustomed with Ansible.

The Ansible playbook,roles etc are stored in the branch ansible-play-photonOS-coreDNS
if this git Repository.
An extra bonus was to update the coreDNS data files via a git repository.

## Ansible controller

I used for deployment a centos/7 VM, provisioned via vagrant and an ansible playbook.
From this VM I provisioned a fresh photon OS 3.0 VM.

### preruiqsites

- a fresh deployed photonOS VM (via .OVA or .iso)
- authentication with the photonOS via pub/private keypair
- the photonOS needs to have internet access
