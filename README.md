[![CI](https://github.com/data-tangles/ansible/actions/workflows/main.yml/badge.svg)](https://github.com/data-tangles/ansible/actions/workflows/main.yml)
[![HitCount](https://hits.dwyl.com/qman-being/ansible.svg?style=for-the-badge&show=unique)](http://hits.dwyl.com/qman-being/ansible)
[![ansible](https://img.shields.io/badge/Ansible-red?style=for-the-badge&logo=ansible)](https://www.ansible.com/)
[![renovate](https://img.shields.io/badge/renovate-enabled-brightgreen?style=for-the-badge&logo=renovatebot)](https://github.com/renovatebot/renovate)

# Ansible

This repo contains all my Ansible playbooks which I use regularly within my homelab environment. If you would like to clone this repo you would just need to create your own inventory and vars files. You would also need to edit the main playbook host to match your own environment.

```sh
📁 root
├─📁 .github
├─📁 playbooks
├─📁 roles
├─🗒️ CHANGELOG.md
├─🗒️ .gitattributes
├─🗒️ .gitignore
├─🗒️ LICENSE
├─🗒️ package.yaml
├─🗒️ README.md
└─🗒️ renovate.json
```

## Table of Contents

- [Getting Started](#getting-started)
  - [Install Ansible](#install-ansible)
  - [Clone Repository](#clone-repository)
  - [Examples](#examples)
  - [Additional Information](#additional-information)
- [Support](#support)
  - [Issues](#issues)
  - [Feature Requests](#feature-requests)
  - [Updates](#updates)

## Getting started 

### Install Ansible

You would need to start by [installing](https://docs.ansible.com/ansible/latest/installation_guide/intro_installation.html) Ansible onto a machine where you would like to run playbooks from. 

### Clone Repository

```
git clone https://github.com/data-tangles/ansible.git
```

### Examples

Below showcases an example playbook being run

```
ansible-playbook -i /path/to/inventory.ini -u ansible-user -k example_playbook.yml
```

### Additional Information

The [documentation](https://docs.ansible.com/) site for Ansible has everything you need to setup all components for Ansible so I encourage you to read through it and familiarize yourself with the key concepts.

## Support
This repository is provided as is and should be considered as a hobby project. With that being said, please see below on details for support.

### Issues

- Please submit a new [Issue](https://github.com/data-tangles/ansible/issues/new) if you encounter any bugs or issues.

### Feature Requests

- You are welcome to submit a feature request but no timeline or guarantee will be provided regarding implentation thereof.

### Updates

- The repository will be updated from time to time with fixes and new playbooks.
