Ansible Role: Hello
=========

An Ansible Role that outputs message on RHEL/CentOS

Requirements
------------

none.

Role Variables
--------------

Available variables are listed below, along with default values (see defaults/main.yml):

msg: 'Hello World.'

Dependencies
------------

none.

Example Playbook
----------------

    - hosts: all
      roles:
         - mhimuro.hello

License
-------

MIT

Author Information
------------------

This role was created in 2021 by mhimuro
