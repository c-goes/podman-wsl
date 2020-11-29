# podman-wsl

Automated install Podman on WSL

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