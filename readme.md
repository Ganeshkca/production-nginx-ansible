# Production Nginx Deployment

## Project Overview
Automated Nginx deplyment using Ansible

## Technologies
- Kali Linux
- Ubuntu
- Ansible
- Nginx
- YAML
- Jinja2
- Git


## Features
- Automated Nginx installation
- Dynamic website deployment
- Reusable Ansible role
- Nginx security headers
- Configuration validation
- Automated HTTP health checks
- Idempotent execution

## Deployment

```bash
ansible-playbook -i inventory/hosts.ini site.yml -k -K --ask-vault-pass
```

### Verification
``` bash
curl -I http://192.168.56.104
```