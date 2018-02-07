# Ansible Role: Git

[![Build Status](https://github.com/faktiva/ansible-role-faktiva-vim-config.git?branch=master)](https://travis-ci.org/faktiva/ansible-role-faktiva-vim-config)

Installs [faktiva/vim-config](https://github.com/faktiva/vim-config.git), a set of pre-configured VIM plugins that makes devs, devops and sysadmins life happier.

## Requirements

None.

## Role Variables

Available variables are listed below, along with default values (see `defaults/main.yml`):

    users:
      - root
      - foobar

## Dependencies

None.

## Example Playbook

    - hosts: servers
      roles:
        - { role: faktiva.faktiva-vim-config }

## License

MIT

## Author Information

This role was created in 2018 by [Emiliano Gabrielli](https://github.com/drAlberT).
