# podman-wsl

Automated install Podman on WSL. This Playbook is an updated version of the steps decribed in [this blog article](https://www.redhat.com/sysadmin/podman-windows-wsl2).

## Supported Distros

- Ubuntu
- Debian 10
- Arch Linux

## How to use

Make sure Ansible is installed.

```
# Debian/Ubuntu:
sudo apt update && sudo apt -y install python3-pip git && sudo pip3 install ansible
# Arch Linux:
pacman -S ansible git
```

Run the automation

```
sudo ansible-pull -U https://github.com/c-goes/podman-wsl
```