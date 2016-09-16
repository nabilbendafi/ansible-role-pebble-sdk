pebble-sdk
==========

[![Build Status](https://travis-ci.org/nabilbendafi/ansible-role-pebble-sdk.png?branch=master)](https://travis-ci.org/nabilbendafi/ansible-role-pebble-sdk)

This role installs and configures the open-source [pebble-sdk](https://developer.pebble.com/sdk/) for Peeble apps development.

Installation
------------

```
$ ansible-galaxy install nabilbendafi.pebble-sdk
```

```
# pebble-sdk.yml
- hosts: localhost
  roles:
    - nabilbendafi.pebble-sdk
```

```
$ ansible-playbook pebble-sdk.yml
```

Dependencies
------------

None

License
-------

[MIT](LICENSE.txt)

Author Information
------------------

[Nabil Bendafi](https://github.com/nabilbendafi)
