# Ansible role for Netdata

This is a simple role that will install Netdata on Debian/Ubuntu from the [packgecloud APT repo](https://packagecloud.io/netdata/netdata).

## Installation

Add this to your `requirements.yml`:

```yml
- src: https://github.com/angristan/ansible-netdata
```

## Sample playbook

```yaml
---

- hosts: myhost
  roles:
    - name: netdata
      tags: netdata
```
