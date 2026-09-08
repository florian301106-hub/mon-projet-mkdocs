# Projet SportLudique 2026-2027

Bienvenue sur notre documentation.

## Présentation

Ce projet consiste à mettre en place et administrer l'infrastructure réseau de l'entreprise **SportLudique**.

## Sites

Nous travaillons notamment sur les sites suivants :

- Bourges
- Chartres
- Blois
- Tours
- Orléans

## Infrastructure réseau

### Bourges

- Réseau : `172.28.192.0/19`
- Masque : `255.255.224.0`

### Chartres

- Réseau : `172.28.160.0/19`
- Masque : `255.255.224.0`

## VLAN

| VLAN | Nom | Utilisation |
|---|---|---|
| 10 | ADMIN | Administration |
| 20 | USERS | Utilisateurs |
| 30 | SERVEURS | Serveurs |
| 40 | WIFI | Wi-Fi |

## Exemple d'adressage

```text
IP : 172.28.192.10
Masque : 255.255.224.0
Passerelle : 172.28.192.1
DNS : 172.28.192.1
