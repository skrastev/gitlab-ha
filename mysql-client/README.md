[![Build Status](https://travis-ci.org/RealSalmon/ansible-mysql-client.svg?branch=master)](https://travis-ci.org/RealSalmon/ansible-mysql-client)

RealSalmon.mysql-client
=======================
Ansible role to install mysql client and development libraries

Requirements
------------
- Ubuntu 14.04
- Ansible 1.9

Role Variables
--------------
- mysql_client_install_client: true
- mysql_client_install_libraries: true

See defaults/main.yml for a description of role variables.

Dependencies
------------
None

Example Playbook
----------------
    ---
    - hosts: all
      roles:
        - RealSalmon.mysql-client

License
-------
BSD

Author Information
------------------
Ben Jones <ben@fogbutter.com>
