pebble-sdk
==========

[![Build Status](https://travis-ci.org/nabilbendafi/ansible-role-peeble-sdk.png?branch=master)](https://travis-ci.org/nabilbendafi/ansible-role-peeble-sdk)

This role installs and configures the open-source [peeble-sdk](https://developer.pebble.com/sdk/) for Peeble apps development.

Installation
------------

```
$ ansible-galaxy install nabilbendafi.peeble-sdk
```

```
# peeble-sdk.yml
- hosts: localhost
  roles:
    - nabilbendafi.peeble-sdk
```

```
$ ansible-playbook peeble-sdk.yml
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
