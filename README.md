# Ansible Role: keepalived

[![Lint](https://github.com/dcjulian29/ansible-role-keepalived/actions/workflows/lint.yml/badge.svg)](https://github.com/dcjulian29/ansible-role-keepalived/actions/workflows/lint.yml) [![GitHub Issues](https://img.shields.io/github/issues-raw/dcjulian29/ansible-role-keepalived.svg)](https://github.com/dcjulian29/ansible-role-keepalived/issues)

This an Ansible role to install and configure Keepalived.

## Requirements

- Active Internet Connection.

## Installation

To use, use `requirements.yml` with the following git source:

```yaml
---
roles:
- name: dcjulian29.keepalived
  src: https://github.com/dcjulian29/ansible-role-keepalived.git
  version: main
  ```

Then download it with `ansible-galaxy`:

```shell
ansible-galaxy install -r requirements.yml
```

## Dependencies

- None
