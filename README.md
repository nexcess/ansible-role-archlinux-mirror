# Ansible Role: Arch Linux Mirror

Installs the Arch Linux mirroring role

## Requirements

None.

## Role Variables

See `defaults/main.yml`.

## Dependencies

nexcess.mirror

## Add to Requirements

    - src: https://github.com/nexcess/ansible-role-archlinux-mirror.git
      name: nexcess.archlinux-mirror

## Example Playbook

    - hosts: servers
      roles:
        - nexcess.archlinux-mirror

## License

MIT / BSD
