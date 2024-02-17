[![Build Status](https://app.travis-ci.com/CSCfi/ansible-role-apache.svg?branch=master)](https://app.travis-ci.com/github/CSCfi/ansible-role-apache)

Ansible-Role: Apache
=========

An role which install Apache on RedHat/Debian servers.

Requirements
------------

None. Purpose of this role is to perform base installation for apache with default hardenings (eg: Mozilla observatory and SSLLabs).

Role Variables
--------------

See defaults/main.yml for the variables you can overwrite via role call as a parameter.

Dependencies
------------

None

Example Playbook
----------------

    - hosts: apache
      roles:
        - { role: CSCfi.apache }
