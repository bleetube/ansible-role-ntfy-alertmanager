# Ansible Role: ntfy-alertmanager

This Ansible Role installs [ntfy-alertmanager](https://git.xenrox.net/~xenrox/ntfy-alertmanager).

## Requirements

* [gantsign.golang](https://github.com/gantsign/ansible-role-golang)

## Role Variables

```yaml
ntfy_alertmanager_version: v0.2.0
```

## Example Playbook

```yaml
- hosts: all
  roles:
    - role: bleetube.ntfy-alertmanager
```
