Ansible Role: Vector
=========

Данная роль разворачивает [Vector](https://vector.dev/).

Эта роль будет работать на:
* Red Hat
* Debian
* Ubuntu

Role Variables
--------------
Вы можете изменить версию Vector:
vector_version: "0.18.0"

Example Playbook
----------------

- name: Install vector
  hosts: vector
  roles:
    - ansible-role-vector
