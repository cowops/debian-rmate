Debian-Rmate
============

Edit files from an ssh session in TextMate 2

Requirements
------------

This role requires a debian compliant system such as ubuntu.

Role Variables
--------------

No variables

Dependencies
------------

None

Example Playbook
----------------

    - hosts: servers
      roles:
         - { role: loranger.debian-rmate }

Tasks
-----

  - Install [rmate](https://github.com/textmate/rmate) command

License
-------

BSD
