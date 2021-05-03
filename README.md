# Ansible development environment

Setting up your development environment with Ansible

## Requirements
- fresh installed Ubuntu (out of scope)
- ansible >= 2.10.5

### Install Ansible

[Ansible Documentation](https://docs.ansible.com/ansible/latest/installation_guide/intro_installation.html#installing-ansible-on-ubuntu)

```

$ sudo apt update
$ sudo apt install software-properties-common
$ sudo apt-add-repository --yes --update ppa:ansible/ansible
$ sudo apt install ansible

```

## Ansible-Playbook
`` $ ansible-playbook -K playbook.yml -i inventory/hosts.yml  ``

## Roles
- common ubuntu packages:
   - jq
   - vim
   - htop
   - curl
   - wget
   - cifs-utils
- OpenJDK 16
- Maven 3.8.1
- Docker
- Docker Compose
- Atom
- GIT
- TeamViewer
- ...
