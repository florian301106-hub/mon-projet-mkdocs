# Documentation

## Switch

- ajout du ssh
- ajout des vlan
- ajout du mode trunk

## Routeur

- reinitialisation du routeur 
- mode trunk
- config realisé

## Page protégée par mot de passe

Une page secrète a été mise en place pour isolé les configuration qui serait sensible. Cette protection est possible grace au plugin `mkdocs-encryptcontent-plugin`, installé via pip et déclaré dans le fichier `mkdocs.yml` :

​```yaml
plugins:
  - search
  - encryptcontent: {}
​```

Le mot de passe est défini directement dans l'en-tête (il faut créer un fichier en .md ) de la page à protéger :

![alt text](image-3.png)

## dans la nouvelle page
![alt text](image-4.png)
​

Lorsqu'un visiteur accède à cette page, le contenu n'est pas affiché directement : un formulaire lui demande de saisir le mot de passe avant de pouvoir le consulter.

Cette protection agit uniquement sur le site généré (HTML) : elle empêche un visiteur classique de voir le contenu sans le mot de passe, mais ne protège pas le code source du dépôt Git, où le mot de passe reste visible en clair pour toute personne ayant accès au dépôt.