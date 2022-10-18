podman
=========

A ansible role that installs podman and podman-compose on a server. On ubuntu 22.04, it installs the default packages, before that it adds the kubic repository and installs it from there.

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
- name: Install podman and podman-compose
  hosts: servers
  roles:
      - drerik.container.podman
```

License
-------

Apache-2.0

Author Information
------------------

Erik Kaareng-Sunde <erik@eriksunde.com>
