# Ansible Role: Redis

[![Build Status](https://travis-ci.org/tschifftner/ansible-role-redis.svg)](https://travis-ci.org/tschifftner/ansible-role-redis)

Installs redis on Debian/Ubuntu linux servers.

## Requirements

ansible 1.7+

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

Ansible          | Debian Jessie    | Ubuntu 14.04    | Ubuntu 12.04
:--------------: | :--------------: | :-------------: | :-------------: 
1.7              | Yes              | Yes             | Yes
1.8              | Yes              | Yes             | Yes
1.9              | Yes              | Yes             | Yes
2.0.1*           | Yes              | Yes             | Yes

*) 2.0.0.0, 2.0.0.1, 2.0.0.2 are not supported!


## License

MIT / BSD

## Author Information

 - Tobias Schifftner, @tschifftner