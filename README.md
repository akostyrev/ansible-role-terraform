# terraform

[![Build Status](https://travis-ci.org/kostyrev/ansible-role-terraform.svg?branch=master)](https://travis-ci.org/kostyrev/ansible-role-terraform)

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

```yaml
---
- hosts: localhost
  connection: local
  roles:
    - kostyrev.terraform

```

Install From Github
-------------------

```
git clone https://github.com/kostyrev/ansible-role-terraform.git kostyrev.terraform
cd kostyrev.terraform && make install
```

License
-------

BSD

Author Information
------------------

Aleksandr Kostyrev
