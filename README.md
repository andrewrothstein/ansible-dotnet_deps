andrewrothstein.dotnet_deps
=========

![Build Status](https://github.com/andrewrothstein/ansible-dotnet_deps/actions/workflows/build.yml/badge.svg)

Installs OS pkg mgr dependencies for dotnet.

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
    - andrewrothstein.dotnet_deps
```

License
-------

MIT

Author Information
------------------

Andrew Rothstein <andrew.rothstein@gmail.com>
