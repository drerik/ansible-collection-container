docker
=========

A ansible role that installs docker and docker-compose on a server

Requirements
------------

None

Role Variables
--------------

None

Dependencies
------------

None

Example Playbook
----------------

```yaml
- name: Install docker and docker-compose
  hosts: servers
  roles:
      - drerik.container.docker
```

License
-------

Apache-2.0

Author Information
------------------

Erik Kaareng-Sunde <erik@eriksunde.com>
