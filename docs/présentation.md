# Documentation SportLudique

Bienvenue sur la documentation du projet **SportLudique de Bourges de Bonheur et Florian 2026-2027**.

## Présentation

Cette documentation présente la mise en place et la configuration de notre infrastructure réseau.

## Sites

Le site concerné est :

* Bourges


---

# Infrastructure

## IPAM

### Plan d'adressage VLAN

| VLAN | Nom            | Réseau            |
| ---- | -------------- | ----------------- |
| 110  | Management     | `10.110.0.0/16`   |
| 210  | *DMZ* | `172.28.210.0/24` |
| 211  | Serveur           | `172.28.211.0/24` |
| 212  | Clients        | `172.28.212.0/24` |

### Configuration réalisée

Les VLAN ci-dessus ont été configurés sur le switch, conformément au plan d'adressage IPAM.

Cette étape a été réalisée après l'activation de l'accès SSH sur les équipements, permettant leur administration à distance.

Nos pages de documentation ont également été configurées et liées aux dépôts GitHub de chacun.



## VLAN

Les VLAN permettent de séparer logiquement les différents réseaux.

| VLAN | Nom        | Utilisation        |
| ---- | ---------- | ------------------ |
| 110  | Management | Administration     |
| 210  | À préciser | À préciser         |
| 211  | DMZ        | Zone démilitarisée |
| 212  | Clients    | Postes clients     |



## Routage






## Équipements réseau :

### Switch

Le switch permet de connecter les différents équipements et de gérer les VLAN.





# Sites

## Bourges

### Réseau

Le réseau attribué au site de Bourges est :

`172.28.192.0/19` jusqu'a 

### Infrastructure

Le site comprend notamment :

* Des switches
* Un routeur
* Des postes clients
* Des équipements administrables en SSH

---

## Chartres

### Réseau

Le réseau attribué au site de Chartres est :

`172.28.160.0/19`

### Infrastructure

Le site comprend notamment :

* Des switches
* Un routeur
* Des postes clients
* Des équipements administrables en SSH

---

# Tests réseau

## Objectif

Les tests permettent de vérifier le bon fonctionnement de l'infrastructure après sa configuration.

## Tests de connectivité

```text
ping <adresse_IP>
```

```text
traceroute <adresse_IP>
```

## Vérifications

* Connectivité entre les machines
* Communication avec la passerelle
* Communication entre les VLAN
* Accès SSH aux équipements
* Communication entre les sites

## Résultats

Les résultats des tests seront ajoutés après leur réalisation.

---

# Avancement

| Tâche                        | État     |
| ---------------------------- | -------- |
| Création du repository       | Terminé  |
| Création de la documentation | Terminé  |
| Accès SSH                    | Terminé  |
| Configuration des VLAN       | Terminé  |
| Plan d'adressage IP          | En cours |
| Configuration du routage     | En cours |
| Tests réseau                 | À faire  |
