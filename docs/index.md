# 🏢 Projet SportLudique 2026-2027

Bienvenue sur notre documentation du projet **SportLudique**.

## 📍 Sites

Notre infrastructure comporte plusieurs sites :

 *## Étapes
## Sites


 Bourges
 Chartres
 Blois
 Tours
 Orléans

## 🌐 Plan d'adressage

| Site | Réseau | Masque |
|---|---|---|
| Bourges | `172.28.192.0/19` | `255.255.224.0` |
| Chartres | `172.28.160.0/19` | `255.255.224.0` |

## 🔌 VLAN

Nous allons mettre en place plusieurs VLAN :

 VLAN 10 → Administration
 VLAN 20 → Utilisateurs
 VLAN 30 → Serveurs
 VLAN 40 → Wi-Fi

## 💻 Exemple de configuration

```text
Adresse IP : 172.28.192.10
Masque     : 255.255.224.0
Passerelle : 172.28.192.1
