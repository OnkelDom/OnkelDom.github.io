## My Lab

On this is the documentation of my server and homelab setup writen with own ansible roles.

Since RedHat stops support for CentOS, i switcht complete to ubuntu and doesn't support them.

I run the most applications as docker container with an systemd unit as service. It's for me easyer to handle all this applikations and have a ckean system.

## Ansible Roles

| Role | Description | Includes |
|------|-------------|----------|
| [wsl2-setup](https://gist.github.com/OnkelDom/1e7039c3ff6c5aa0578d1a84fdbb26bb) | client setup | windows 10, wsl2, ubuntu, windows terminal |
| [ansible-role-basic](https://github.com/OnkelDom/ansible-role-basic) | server setup | packages, motd, hosts, bashrc, users, sysctl, systemd-timesyncd, systemd-resolvd |
| [ansible-role-netplan](https://github.com/OnkelDom/ansible-role-netplan) |  |  |
| [ansible-role-ufw](https://github.com/OnkelDom/ansible-role-ufw) |  |  |
| [ansible-role-fail2ban](https://github.com/OnkelDom/ansible-role-fail2ban) |  |  |
| [ansible-role-docker](https://github.com/OnkelDom/ansible-role-docker) |  |  |
| [ansible-role-rclone](https://github.com/OnkelDom/ansible-role-rclone) |  |  |
| [ansible-role-node-exporter](https://github.com/OnkelDom/ansible-role-node-exporter) |  |  |
| [ansible-role-promtail](https://github.com/OnkelDom/ansible-role-promtail) |  |  |
| [ansible-role-docker-prometheus](https://github.com/OnkelDom/) |  |  |
| [ansible-role-docker-alertmanager](https://github.com/OnkelDom/) |  |  |
| [ansible-role-docker-grafana](https://github.com/OnkelDom/) |  |  |
| [ansible-role-docker-loki](https://github.com/OnkelDom/) |  |  |
| [ansible-role-docker-victrotiametrics](https://github.com/OnkelDom/) |  |  |
| [ansible-role-docker-blackbox-exporter](https://github.com/OnkelDom/) |  |  |
| [ansible-role-docker-traefik](https://github.com/OnkelDom/) |  |  |
| [ansible-role-docker-smtp-to-telegram](https://github.com/OnkelDom/) |  |  |
| [ansible-role-docker-watchtower](https://github.com/OnkelDom/) |  |  |
| [ansible-role-docker-poste.io](https://github.com/OnkelDom/) |  |  |
| [ansible-role-docker-bitwarden](https://github.com/OnkelDom/) |  |  |
| [ansible-role-docker-unifi](https://github.com/OnkelDom/) |  |  |
| [ansible-role-docker-unifi-exporter](https://github.com/OnkelDom/) |  |  |
| [ansible-role-docker-adguard](https://github.com/OnkelDom/) |  |  |
| [ansible-role-docker-adguard-exporter](https://github.com/OnkelDom/) |  |  |