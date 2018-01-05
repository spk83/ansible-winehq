spk83.winehq
============
[![Build Status](https://travis-ci.org/spk83/ansible-winehq.svg?branch=master)](https://travis-ci.org/spk83/ansible-winehq)

Installs Wine on Ubuntu and Debian systems

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
    - spk83.winehq
```

License
-------

MIT

Author Information
------------------

Vishal Shah <vishal.shah@nyu.edu>
