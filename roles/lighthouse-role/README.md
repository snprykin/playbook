# Lighthouse Role

Ansible role for installing Lighthouse — a ClickHouse web interface.

## Requirements

- Ubuntu 20.04/22.04
- Ansible 2.9+

## Role Variables

| Variable | Description | Default |
|----------|-------------|---------|
| `lighthouse_nginx_port` | Web port | `80` |
| `lighthouse_install_dir` | Install path | `/opt/lighthouse` |

## Example

```yaml
- hosts: webservers
  roles:
    - lighthouse-role
