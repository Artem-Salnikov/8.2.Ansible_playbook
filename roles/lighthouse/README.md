Ansible Role: LightHouse
=========

Данная роль разворачивает [LightHouse](https://github.com/VKCOM/lighthouse).

Эта роль будет работать на:
* Red Hat
* Debian
* Ubuntu

Example Playbook
----------------

- name: Install LightHouse
  hosts: lighthouse
  roles:
    - ansible-role-lighthouse
