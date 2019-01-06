Ansible Role - HashiCorp Packer - CentOS
========================================

[![Build Status](https://travis-ci.org/bt5e/ansible-role-hashicorp-packer.svg?branch=master)](https://travis-ci.org/bt5e/ansible-role-hashicorp-packer)

HashiCorp Packer install based on: https://www.packer.io/intro/getting-started/install.html

Binary is installed as `packer.io` to avoid name conflict with existing `packer` binary.

Requirements
------------

None.

Role Variables
--------------

None.

Dependencies
------------

None.

Example Playbook
----------------

    - hosts: servers
      roles:
         - bt5e.hashicorp-packer

License
-------

MIT

Author Information
------------------

Ben Tse
