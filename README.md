# Ansible development environment

Setting up your development environment with Ansible

## Requirements
- fresh installed Ubuntu
- ansible >= 2.10.5

## Install
`` $ ansible-playbook -K playbook.yml -i inventory/hosts.yml  ``

## Roles
- common ubuntu packages:
   - jq
   - vim
   - htop
   - curl
   - wget
   - cifs-utils
- Atom
- GIT
- TeamViewer
- ...
