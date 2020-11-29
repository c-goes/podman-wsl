# podman-wsl

Automated install Podman on WSL

## Supported Distros

- Ubuntu
- Debian 10


## How to use

Make sure Ansible is installed.

```
sudo apt update && sudo apt -y install python3-pip git && sudo pip3 install ansible
```

Run the automation

```
sudo ansible-pull -U https://github.com/c-goes/podman-wsl
```