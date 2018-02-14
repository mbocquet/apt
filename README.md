# apt

Ansible role to configure APT.

## Requirements

None.

## Role Variables

None.

## Dependencies

None.

## Install this role as submodule in a git repository

`git submodule add https://github.com/mbocquet/apt.git roles/apt`

## Example Playbook

    - hosts: servers
      roles:
         - apt


    - hosts: servers
      roles:
         - { role: apt, x: 42 }

## License

GPLv3

## Author Information

http://www.sekoya.org
