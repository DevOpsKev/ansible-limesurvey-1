Limesurvey
=========

Installs the Open Source on-line survey application Limesurvey

based on https://github.com/ICTO/ansible-limesurvey 

ATTENTION: early beta status!

Requirements
------------

Package names are based on the Debian distribution.

Role Variables
--------------

Default **admin** password is **password** (sha256). 

Dependencies
------------

debops framework

Example Playbook
----------------

```
- name: Limesurvey
  hosts: all
  sudo: yes

  roles:
    - limesurvey
```
