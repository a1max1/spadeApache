# spadeApache
spadeApache
===========

An Ansible role that install apache and is tested through Travis
This is only built as a sample for glaxy/travis integration
next step docker integration

[![Build Status](https://travis-ci.org/a1max1/spadeApache.svg?branch=master)](https://travis-ci.org/a1max1/spadeApache)

Requirements
------------

running apt-get vs yum

Role Variables
--------------

located in defaults/main.yml

Example Playbook
----------------

example of how to use the role
  - hosts: servers
    roles:
      - { role: a1max1.spadeApache, x: 42 }

Author Information
------------------
Ace of Spade

