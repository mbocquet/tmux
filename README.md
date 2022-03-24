# tmux

Ansible role to install tmux.

## Requirements

None.

## Role Variables

See defaults/main.yml for details

## Dependencies

None.

## Install this role as submodule in a git repository

`git submodule add https://git.sekoya.org/mb/tmux.git roles/tmux`

## Example Playbook

    - hosts: servers
      roles:
         - tmux


    - hosts: servers
      roles:
         - { role: tmux, x: 42 }

## License

GPLv3

## Author Information

http://www.sekoya.org
