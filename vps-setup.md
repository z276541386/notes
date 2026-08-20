# VPS Setup Guide

## Initial Setup
```bash
apt update && apt upgrade -y
apt install curl wget git vim ufw -y
```

## Security
```bash
ufw enable
ufw allow 22/tcp
ufw allow 80/tcp
ufw allow 443/tcp
```

## Common Tools
- fail2ban
- htop
- netdata
- nginx
