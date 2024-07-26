# Ansible Role: system_update

 [![Sponsor](https://img.shields.io/badge/Sponsor-Click%20Here-ff69b4)](https://github.com/sponsors/simeononsecurity) 

This Ansible role combines the functionality of two separate roles, namely [`linux_update`](https://github.com/simeononsecurity/ansible_linux_update) and [`windows_update`](https://github.com/simeononsecurity/ansible_windows_update), into a single role called `system_update`. The `system_update` role can be used to automate the patching of both Linux and Windows systems using Ansible.

Please make sure you have met the following requirements before using this role:
- Linux hosts and or Windows hosts
- Ansible 2.10 or later

## Requirements

- Linux hosts and or Windows hosts
- Ansible 2.10 or later

## Role Variables

None

## Dependencies

None

## Usage


### Installation
```bash
ansible-galaxy install simeononsecurity.system_update
```

To use this role, include it in your playbook as shown in the example below:

```yaml
- name: Apply system updates
  hosts: all
  become: yes

  roles:
    - system_update
```

## License: 
MIT

## Author Information:
This role was created by SimeonOnSecurity.
For more information, visit [SimeonOnSecurity.com](https://SimeonOnSecurity.com).

## [Learn more about Ansible Best Practice](https://simeononsecurity.com/articles/secure-coding-standards-for-ansible/)
