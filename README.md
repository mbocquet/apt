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

## Before running

This role can configure dpkg options (see templates/dpkg.j2.example).

Copy this file in your templates search path as dpkg.j2 and tweak it to your
needs before running this role.

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
