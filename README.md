[![No Maintenance Intended](http://unmaintained.tech/badge.svg)](http://unmaintained.tech/)

logstash
========

[![Build Status](https://travis-ci.org/kbrebanov/ansible-logstash.svg?branch=master)](https://travis-ci.org/kbrebanov/ansible-logstash)

Installs and configures Logstash

Requirements
------------

This role requires Ansible 1.9 or higher.

Role Variables
--------------

| Name             | Default | Description                    |
|:-----------------|:--------|:-------------------------------|
| logstash_version | 2.3.2   | Version of Logstash to install |

Dependencies
------------

- kbrebanov.java (OpenJDK 8)

Example Playbook
----------------

Install Logstash
```yaml
- hosts: all
  roles:
    - kbrebanov.logstash
```

License
-------

BSD

Author Information
------------------

Kevin Brebanov
