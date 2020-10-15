Vaisible Governor
=========

An Ansible role that installs Vaisible Governor service.

Requirements
------------

None.

Role Variables
--------------
```
aes_key: <some secure key> 
```

Dependencies
------------

geerlingguy.docker

Example Playbook
----------------

Install from the system package manager:
```
    - hosts: all
      roles:
         - role: vaisible.governor_ansible
```
License
-------

Apache-2.0

Author Information
------------------

This role was created by [Michael Abramovich](https://github.com/m-abramovich).
