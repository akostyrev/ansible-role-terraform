# terraform

[![Build Status](https://travis-ci.org/kostyrevaa/ansible-role-terraform.svg?branch=master)](https://travis-ci.org/kostyrevaa/ansible-role-terraform)

Installs Terraform

Requirements
------------

None

Role Variables
--------------

See [defaults/main.yml](defaults/main.yml) for a list and description of
variables used in this role.

Example Playbook
----------------

TODO: Add example playbook(s).

```yaml
---
- hosts: localhost
  connection: local
  vars:
    terraform_verion: 0.7.13
  roles:
    - kostyrevaa.terraform

```

License
-------

BSD

Author Information
------------------

Aleksandr Kostyrev
