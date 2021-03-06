
[![](https://img.shields.io/github/repo-size/laster13/patxav.svg?style=flat)](https://github.com/laster13/patxav)

--- 

pour plus de détail avant et après installation --> direction le [wiki](https://github.com/laster13/patxav/wiki)

# Introduction

### Pour se lancer dans l’installation, il faut au préalable avoir suivi les étapes suivantes:

- Avoir une machine (serveur ou NAS) (5000 score passmark minimum)
- Obtenir un nom de domaine
- Utiliser un compte Gsuite illimité avec création de dossier partagés disponible 
- Connexion en root via ssh/ (pas user puis root) [Activer root tuto simple pour debian](https://cloriou.fr/2016/12/05/debian-autoriser-acces-root-via-ssh/)
- une fois toutes ces étapes validées vous pouvez suivre les Prérequis.

***

# Pré-requis

Je vous recommande de suivre les étapes dans l'ordre suivant :

- [Transfert de gestion DNS Cloudflare](https://github.com/laster13/patxav/wiki/Transfert-de-gestion-DNS-Cloudflare)
- [Création des projets Google](https://github.com/laster13/patxav/wiki/Création-des-projets-Google)

***

# Installation en root

1. Mise à jour des paquets :
```
apt update && apt upgrade -y
```

2. Installation de Git :
```
apt install git -y
```

3. Clonage du script : 

```
git clone https://github.com/laster13/patxav.git /opt/seedbox-compose
```

4. Pour rentrer là ou le script est installé :

```
cd /opt/seedbox-compose 
```

5. Lancer le script : 

```
./seedbox.sh
```
Ce script est proposé à des fins d'expérimentation uniquement, le téléchargement d’oeuvre copyrightées est illégal.
Merci de vous conformer à la législation en vigueur en fonction de vos pays respectifs en faisant vos tests sur des fichiers libres de droits
