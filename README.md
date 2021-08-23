andrewrothstein.sentinel
=========
![Build Status](https://github.com/andrewrothstein/ansible-sentinel/actions/workflows/build.yml/badge.svg)

Installs [Sentinel](https://www.hashicorp.com/sentinel/).

Requirements
------------

See [meta/main.yml](meta/main.yml)

Role Variables
--------------

See [defaults/main.yml](defaults/main.yml)

Dependencies
------------

See [meta/main.yml](meta/main.yml)

Example Playbook
----------------

```yml
- hosts: servers
  roles:
    - andrewrothstein.sentinel
```

License
-------

MIT

Author Information
------------------

Andrew Rothstein <andrew.rothstein@gmail.com>
