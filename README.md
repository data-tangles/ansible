[![ansible](https://img.shields.io/badge/Ansible-red?style=for-the-badge&logo=ansible)](https://www.ansible.com/)

[![HitCount](https://hits.dwyl.com/qman-being/ansible.svg?style=for-the-badge&show=unique)](http://hits.dwyl.com/qman-being/ansible)

[![Build Status](https://dev.azure.com/qman-being/dreddrealm/_apis/build/status/qman-being.ansible?branchName=master)](https://dev.azure.com/qman-being/dreddrealm/_build/latest?definitionId=11&branchName=master)

# Ansible

This repo contains all my Ansible playbooks which I use regularly within my homelab environment. If you would like to clone this repo you would just need to create your own inventory and vars files. You would also need to edit the main playbook host to match your own environment.

## Getting started 

You would need to start by [installing](https://docs.ansible.com/ansible/latest/installation_guide/intro_installation.html) Ansible onto a machine where you would like to run playbooks from. 

In my case, I have Ansible installed on a dedicated node which also acts as an Azure DevOps agent so that I can run all my playbooks via CI/CD pipelines.

The [documentation](https://docs.ansible.com/) site has everything you need to setup all components for Ansible so I encourage you to read through it and familiarize yourself with the key concepts.
