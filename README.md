ansible-role-noipduc
=========
[![Travis](https://img.shields.io/travis/louwandre90/ansible-role-noipduc.svg?style=flat-square)](https://travis-ci.org/louwandre90/ansible-role-noipduc.svg?branch=master)
[![Ansible Role](https://img.shields.io/badge/role-louwandre90.noipduc-blue.svg?style=flat-square)](https://galaxy.ansible.com/louwandre90/noipduc/)

This role installs the No-IP DUC Debian.

No configuration is done. 

Requirements
------------

None

Role Variables
--------------

The following defaults are set:

    username: jarvis

To pass different variables:

    ansible-playbook playbook.yml -e 'username=myuser'
    
Dependencies
------------

None 

Example Playbook
----------------

    - hosts: servers
      roles:
         - { role: louwandre90.noipduc }

License
-------

BSD

Author Information
------------------

This role was created in 2016 by Andre Louw.
