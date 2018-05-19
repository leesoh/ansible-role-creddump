CredDump
=========

Ansible role to install CredDump.

Requirements
------------

None

Role Variables
--------------

creddump_git_location: '/opt'

Dependencies
------------

leesoh.git

Example Playbook
----------------

- hosts: servers
  roles:
      - leesoh.creddump

License
-------

BSD

Author Information
------------------

CredDump: https://github.com/Neohapsis/creddump7
