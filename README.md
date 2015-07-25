logstash
========

Installs and configures Logstash

Requirements
------------

This role requires Ansible 1.4 or higher.

Role Variables
--------------

| Name             | Default | Description                    |
|------------------|---------|--------------------------------|
| logstash_version | 1.5.3   | Version of Logstash to install |

Dependencies
------------

None

Example Playbook
----------------

Install Logstash
```
- hosts: all
  roles:
    - { role: kbrebanov.logstash }
```

Install Logstash specifying version
```
- hosts: all
  roles:
    - { role: kbrebanov.logstash, logstash_version: 1.4.4 }
```

License
-------

BSD

Author Information
------------------

Kevin Brebanov
