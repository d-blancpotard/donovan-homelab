
# Architecture de l'infrastructure

## Présentation

Cette section décrit l'architecture générale de mon Homelab, les équipements utilisés et leur rôle dans l'infrastructure.

## Équipements physiques

| Équipement | Caractéristiques | Fonction | 
|---|---|---|
| PC1 - Windows | X | Pc perso qui me sert de pc pour accéder à mes serveurs |
| pve1 - Proxmox | 16Go 500Go | Hyperviseur qui héberge mes VMs |
| Switch HP A5120-16G | 16 Ports | Commutation |
| Freebox | Passerelle du réseau | Accès Internet |

## Environnement de virtualisation

Les machines virtuelles sont sur l'hyperviseur Proxmox.

## Services hébergés

- Active Directory et DNS (SRV-AD01)
- Serveur Debian (SRV-DEBIAN01)


## Schéma réseau
PC 1 : 192.168.0.24
pve1 : 192.168.0.20
SRV-AD01 : 192.168.0.30
SRV-DEBIAN01 : 192.168.0.33


## Évolutions prévues

- Documentation détaillée du plan d'adressage.
- Étude de la segmentation réseau.
- Mise en place d'une supervision.
- Amélioration de la sécurité.
