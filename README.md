![Build Status](https://img.shields.io/gitlab/pipeline-status/mireiawenrose/ansible-roles/openresolv?branch=master&style=plastic) [![Ansible Galaxy](https://img.shields.io/badge/Ansible%20Galaxy-mireiawen.openresolv-blueviolet?style=plastic)](https://galaxy.ansible.com/mireiawen/openresolv)

# openresolv

## Requirements
None.

## Role Variables
 Configuration key             | Description                                  | Default value
-------------------------------|----------------------------------------------|----------------------
`openresolv_package`           | The package name to use                      | `openresolv`
`openresolv_package_state`     | The desired package state                    | `present`
`openresolv_static_resolvconf` | Disable automatic changes to the resolv.conf | true

## Dependencies
None.

## Example Playbook
```yaml
- hosts: "servers"
  roles:
  - role: "mireiawen.openresolv"
```

## License
MIT, see `LICENSE`
