# terraform

[![Build Status](https://travis-ci.org/akostyrev/ansible-role-terraform.svg?branch=master)](https://travis-ci.org/akostyrev/ansible-role-terraform)

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
    - akostyrev.terraform

```

Install From Github
-------------------

```
git clone https://github.com/akostyrev/ansible-role-terraform.git akostyrev.terraform
cd akostyrev.vagrant && make install
```

License
-------

BSD

Author Information
------------------

Aleksandr Kostyrev
