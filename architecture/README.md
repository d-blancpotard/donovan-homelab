
# Architecture de l'infrastructure

## Présentation

Cette section décrit l'architecture générale de mon Homelab, les équipements utilisés et leur rôle dans l'infrastructure.

## Équipements physiques

| Équipement | Adresse de gestion | Fonction |
|---|---|---|
| PC1 - Proxmox | Adresse privée documentée séparément | Virtualisation |
| PC2 - Proxmox | Adresse privée documentée séparément | Virtualisation |
| Switch HP A5120-16G | Adresse privée documentée séparément | Commutation |
| Freebox | Passerelle du réseau | Accès Internet |

## Environnement de virtualisation

Les machines virtuelles sont réparties sur deux hyperviseurs Proxmox indépendants.

## Services hébergés

- Active Directory et DNS
- Serveur Debian
- Serveur Minecraft Fabric

## Schéma réseau

À compléter : 

## Évolutions prévues

- Documentation détaillée du plan d'adressage.
- Étude de la segmentation réseau.
- Mise en place d'une supervision.
- Amélioration de la sécurité.
