# rabbitmq

[![Build Status](https://travis-ci.com/iroquoisorg/ansible-role-rabbitmq.svg?branch=master)](https://travis-ci.com/iroquoisorg/ansible-role-memcached)

Ansible role for rabbitmq

This role was prepared and tested for Ubuntu 16.04.

# Installation

`$ ansible-galaxy install iroquoisorg.rabbitmq`

# Default settings

```

rabbitmq_plugins: []
rabbitmq_admin: { name: 'admin', password: 'admin' }
rabbitmq_users: []

```
