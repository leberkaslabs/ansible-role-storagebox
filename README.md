# Ansible Role: Storagebox

[![Ansible Molecule](https://github.com/leberkaslabs/ansible-role-storagebox/actions/workflows/molecule.yml/badge.svg)](https://github.com/leberkaslabs/ansible-role-storagebox/actions/workflows/molecule.yml)

Mount Hetzner storage box on linux systems.

## Prerequisites

- Ensure you have Ansible installed (e.g. `pip3 install ansible`)
- **Development**: Install the pip packages listed in [requirements.txt](requirements.txt)

## Role Variables

The default values for the variables are set in [defaults/main.yml](defaults/main.yml)

```yaml
- hosts: all
  roles:
    - role: dudecalledbro.storagebox
```

## License

Copyright © 2025 Niclas Spreng

Licensed under the [MIT license](LICENSE).
