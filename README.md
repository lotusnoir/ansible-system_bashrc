# ansible-system_bashrc

## Description

[![Galaxy Role](https://img.shields.io/badge/galaxy-system_bashrc-purple?style=flat)](https://galaxy.ansible.com/lotusnoir/system_bashrc)
[![Version](https://img.shields.io/github/release/lotusnoir/ansible-system_bashrc.svg)](https://github.com/lotusnoir/ansible-system_bashrc/releases/latest)
![GitHub repo size](https://img.shields.io/github/repo-size/lotusnoir/ansible-system_bashrc?color=orange&style=flat)
[![downloads](https://img.shields.io/ansible/role/d/56111)](https://galaxy.ansible.com/lotusnoir/system_bashrc)
![Ansible Quality Score](https://img.shields.io/ansible/quality/56111)
[![License](https://img.shields.io/badge/license-Apache--2.0-brightgreen?style=flat)](https://opensource.org/licenses/Apache-2.0)


Deploy custom bashrc using ansible.

## Requirements

none

## Role variables

| Name           | Default Value | Description                        |
| -------------- | ------------- | -----------------------------------|

## Examples

        ---
        - hosts: system_bashrc
          become: yes
          become_method: sudo
          gather_facts: yes
          roles:
            - role: ansible-system_bashrc
          environment:
            http_proxy: "{{ http_proxy }}"
            https_proxy: "{{ https_proxy }}"
            no_proxy: "{{ no_proxy }}

## License

This project is licensed under Apache License. See [LICENSE](/LICENSE) for more details.

