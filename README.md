
# Donovan Homelab

Bienvenue sur mon projet Homelab !

Ce dépôt regroupe la documentation technique de mon infrastructure personnelle, mise en place dans le but d'approfondir mes compétences en administration systèmes, réseaux, virtualisation et cybersécurité.

## Objectifs du projet

- Concevoir et administrer une infrastructure informatique.
- Approfondir mes connaissances en systèmes Windows et Linux.
- Expérimenter les technologies de virtualisation.
- Mettre en place des services réseau.
- Étudier les mécanismes de sécurité informatique.
- Automatiser et documenter les opérations d'administration.

## Infrastructure

| Équipement | Technologie | Caractéristique | Utilisation |
|---|---|---|---|
| PC1 | Windows 11 | 16Go | PC perso qui me sert de pc d'administration |
| PC2 | Proxmox VE | 16Go 500Go SSD | Hyperviseur #1 - Hébergement des VMs pour l'AD, DNS, DHCP...|
| PC3 | Proxmox VE | 8Go 250Go SSD | Hyperviseur #2 - Disponible mais pour l'instant pas branché ni utilisé |
| Switch HP | | Constitue le coeur de réseau|

## Technologies utilisées

- **Virtualisation :** Proxmox VE
- **Systèmes :** Windows Server, Debian Linux
- **Annuaire :** Active Directory, DNS, GPO
- **Réseaux :** TCP/IP, Ethernet, VLAN
- **Services :** SSH
- **Automatisation :** Bash, PowerShell

## Documentation

La documentation sera organisée par domaine :

- [Architecture](architecture/README.md)
- [Proxmox](proxmox/README.md)
- [Windows Server](windows-server/README.md)
- [Linux](linux/README.md)
- [Réseaux](networking/README.md)
- [Cybersécurité](cybersecurity/README.md)
- [Automatisation](automation/README.md)
- [Services](services/README.md)

*Les sections seront complétées progressivement au fil de l'évolution du projet.*

## Évolution du projet

Ce Homelab est un environnement d'apprentissage évolutif. Chaque nouvelle installation, configuration ou expérimentation fait l'objet d'une documentation afin de conserver une trace des procédures et des compétences acquises.

---
*Projet personnel — Documentation et expérimentations réalisées en environnement de laboratoire.*
