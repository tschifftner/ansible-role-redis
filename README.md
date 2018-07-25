# Ansible Role: Redis

[![Build Status](https://travis-ci.org/tschifftner/ansible-role-redis.svg?branch=master)](https://travis-ci.org/tschifftner/ansible-role-redis)

Installs redis on Debian/Ubuntu linux servers.

## Requirements

None

## Role Variables

Available variables are listed below, along with default values (see `defaults/main.yml`):

```
redis_enable_persistence: true
redis_scheduled_rewriting: true
```


## Dependencies

None.

## Example Playbook

    - hosts: server
      roles:
        - { role: tschifftner.redis }

## Supported OS

 - Debian 9 (Stretch)
 - Debian 8 (Jessie)
 - Ubuntu 18.04 (Bionic Beaver)
 - Ubuntu 16.04 (Xenial Xerus)
 
## Required ansible version

Ansible 2.5+

## License

[MIT License](http://choosealicense.com/licenses/mit/)

## Author Information

 - [Tobias Schifftner](https://twitter.com/tschifftner), [ambimax® GmbH](https://www.ambimax.de)