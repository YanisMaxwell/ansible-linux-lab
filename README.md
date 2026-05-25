# ansible-linux-lab
# Ansible Linux Lab

Lab d'automatisation Linux avec l'outil Ansible.

## Architecture

- Contrôleur : Debian 13
- Machine cible : AlmaLinux 9
- Communication via SSH
- Automatisation avec Ansible

## Objectif

Apprendre les bases d'Ansible dans un environnement Linux réel :

- configuration d'un inventory
- création d'un playbook YAML
- installation automatique de paquets
- gestion de services Linux
- communication SSH entre machines

## Technologies utilisées

- Linux
- Debian
- AlmaLinux
- Ansible
- SSH
- YAML

## Commandes importantes

```bash
ansible -i inventory.ini alma -m ping

ansible-playbook -i inventory.ini setup.yml --ask-pass --ask-become-pass

ansible-playbook --syntax-check setup.yml
