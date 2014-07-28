# Droplet Ansible Playbooks

The Ansible Playbooks for setting up my DigitalOcean Droplet.

It will init the Droplet with common configurations and then install certain services.

## Usage

```
$ ansible-playbook -i hosts droplet.yml
```

## Test

```
$ vagrant up
$ ansible-playbook -i hosts.vagrant droplet.yml
```

## Ansible Practice

### Roles

__common__: common configurations used on the server. (eg: locale, timezone, users)

__vpn__: VPN tunnel established via OpenVPN.

__rc__: resource configurations for interactive operating. (eg: bashrc, vimrc)
