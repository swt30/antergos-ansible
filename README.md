# arch-ansible 

[Ansible](https://ansible.com) playbooks to set up my Antergos (Arch Linux) install.

## Pre-install

Install `ansible`: `sudo pacman -Syu ansible`

## Usage
Clone and

```sh
ansible-playbook playbook.yml
```

or just use ansible-pull:

```sh
ansible-pull -U git@github.com:swt30/antergos-ansible.git playbook.yml
```
