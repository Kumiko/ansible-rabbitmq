# Ansible RabbitMQ role

This Ansible role will install the RabbitMQ message queue server from the main
Ubuntu repository. The role is tested and designed for use on Ubuntu 16.04.

## Installation

```
cd roles

git clone https://github.com/Kumiko/ansible-rabbitmq.git rabbitmq
```

## Usage

Include the role in your playbook:

```
- hosts: your_rabbitmq_hosts
  roles:
    - name: rabbitmq
```
