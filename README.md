Redis Installer
=========

Builds redis from source and installs it.

Requirements
------------

Debian 10

Role Variables
--------------

`redis_version` -- desired version of redis to install.


Example Playbook
----------------
```
- name: Server installation according to roles
  hosts: all
  remote_user: root
  roles:
    - role: redis_installer
      vars:
        redis_version: 6.0.10
```

License
-------

BSD
