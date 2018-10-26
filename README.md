# Bash script to automate optimized EasyEngine v3 setup (beta)

* * *

## Server Stack

- Nginx 1.15.x/1.14 with [nginx-ee](https://virtubox.github.io/nginx-ee/)
- PHP-FPM 7.0/7.1/7.2
- MariaDB 10.1/10.2/10.3
- REDIS 4.0
- Fail2ban
- UFW Firewall
- ClamAV Antivirus
- Netdata
- Proftpd
- Acme.sh with [ee-acme-sh](https://virtubox.github.io/ee-acme-sh/)

* * *

**Documentation available here : [Ubuntu-Nginx-Web-Server](https://virtubox.github.io/ubuntu-nginx-web-server/)**

### Features

- Automated MariaDB server or client installation (10.1/10.2/10.3)
- Linux server tweaks
- [EasyEngine](https://github.com/EasyEngine/easyengine) v3.8.1 automated installation
- php7.1-fpm and/or php7.2-fpm installation & configuration
- Latest Nginx release compilation with [nginx-ee](https://virtubox.github.io/nginx-ee/)
- UFW configuration with custom SSH port
- Fail2ban Installation & Configuration
- [Netdata](https://github.com/firehol/netdata/) and [EasyEngine-Dashboard](https://virtubox.github.io/easyengine-dashboard/) installation
- Proftpd installation & configuration

### Compatibility

- Ubuntu 16.04 LTS
- Ubuntu 18.04 LTS

### Requirements

- login as root
- ssh connection with ssh keys
- VPS or dedicated server with at least 2GB RAM (Hetzner, OVH, DigitalOcean, Linode, Vultr, Scaleway are good choices)

### Usage

```bash
wget -O ee-nginx-setup.sh https://raw.githubusercontent.com/VirtuBox/ee-nginx-setup/master/ee-nginx-setup.sh
chmod +x ee-nginx-setup.sh
./ee-nginx-setup.sh
```

Published & maintained by [VirtuBox](https://virtubox.net)
