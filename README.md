# wilmardo.nginx-lightspeed

[![Build Status](https://travis-ci.org/wilmardo/ansible-role-domoticz.svg?branch=master)](https://travis-ci.org/wilmardo/ansible-role-nginx-lightspeed)
[![Galaxy](https://img.shields.io/badge/galaxy-wilmardo.nginx-lightspeed-blue.svg)](https://galaxy.ansible.com/wilmardo/nginx-lightspeed/)

Role to install Nginx from source with brotli and pagespeed

## Requirements

None.

## Role Variables

### Default usage

As default nginx-lightspeed is installed and running.
If you want to adapt this to your needs look at the [Advanced usage](#advanced-usage) section.

### Advanced usage

For more advanced usage the following variables are available:
```yaml
# see defaults/main.yml
```

## Dependencies

None

## Example Playbook

Install nginx-lightspeed with the default settings
```yaml
- hosts: all
  roles:
     - role: wilmardo.nginx-lightspeed
```

## License

BSD-3-Clause-Clear

## Author Information

This role was created in 2018 by [Wilmar den Ouden](https://wilmardenouden.nl).
