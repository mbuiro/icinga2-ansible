# icinga2-ansible
=======================

Installs Icinga2 on clients and adds host to master config.


Requirements
------------

Ansible v2.0+
Python
Icinga2

Role Variables
--------------

Use vars.yml as main configuration file

Dependencies
------------

None

Example Playbook
----------------

    - hosts:
        - icinga2
      roles:
        - icinga2-add-hot

License
-------

GPLv3

Author Information
------------------

Michael Ezebuiro
