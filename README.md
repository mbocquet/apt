# apt-config

Configures APT.

## Requirements

None.

## Role Variables

None.

## Dependencies

None.

## Install this role as submodule in a git repository

`git submodule add https://github.com/mbocquet/apt-config.git roles/apt-config`

## Example Playbook

    - hosts: servers
      roles:
         - apt-config


    - hosts: servers
      roles:
         - { role: apt-config, x: 42 }

## License

GPLv3

## Author Information

http://www.sekoya.org
