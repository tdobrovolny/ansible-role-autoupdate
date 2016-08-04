[![Build Status](https://travis-ci.org/tdobrovolny/ansible-role-autoupdate.svg?branch=master)](https://travis-ci.org/tdobrovolny/ansible-role-autoupdate)

autoupdate
==========

Running this role you update all installed packages on target node to the latest version available in repositories configured on this node.

Requirements
------------

 - ansible apt module
 - ansible dnf module
 - ansible yum module
 - ansible shell module
 - ansible command module
 - ansible debug module

Role Variables
--------------

This role does not use settable variables.

Dependencies
------------

This role does not depand on any role.

Example Playbook
----------------

    - hosts: servers
      roles:
         - { role: tdobrovolny.autoupdate }

License
-------

BSD

Author Information
------------------

Tomas Dobrovolny - sdobrtomas@gmail.com - https://github.com/tdobrovolny
