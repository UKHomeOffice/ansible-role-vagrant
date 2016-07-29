## Install Go lang

This role installs [Vagrant](https://www.vagrantup.com/downloads.html) from a binary package.

[![Build Status](https://travis-ci.org/gtrafimenkov/ansible-role-vagrant.svg)](http://travis-ci.org/gtrafimenkov/ansible-role-vagrant)
[![Ansible Role](https://img.shields.io/badge/role-gtrafimenkov.vagrant-blue.svg?maxAge=2592000)](https://galaxy.ansible.com/gtrafimenkov/vagrant)

### Usage

By default the latest stable version is installed.

You can specify another version using variable `vagrant_version`.  For example:

```
---
- hosts:
    - testhost
  become: yes
  vars:
    vagrant_version: 1.8.3
  roles:
    - gtrafimenkov.vagrant
```

### Supported Version of Vagrant

- 1.8.5
- 1.8.3

### Supported Platforms

- Debian-based Linux distros

### To Do

- add configuration option for updating to newest version
- support rpm-based distros
- support i686 architecture

### License

MIT
