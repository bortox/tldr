---
author: ['qontinuum-dev']
date: 1636288524
title: "pacman-mirrors, TLDR Pages"
description: "pacman-mirrors, Génère une liste de miroirs pour pacman sur Manjaro Linux."
categories: "linux"
---
> Tout appel à pacman-mirrors demande de synchroniser les bases de données et de mettre à jour le système en exécutant `sudo pacman -Syyu` en suivant.

> Plus d'informations : <https://wiki.manjaro.org/index.php?title=Pacman-mirrors>.

- Génère une liste de miroirs avec les réglages par défaut :

```bash
sudo pacman-mirrors --fasttrack
```

- Obtiens le statut des miroirs actuels :

```bash
pacman-mirrors --status
```

- Affiche la branche courante :

```bash
pacman-mirrors --get-branch
```

- Utilise une branche différente :

```bash
sudo pacman-mirrors --api --set-branch stable|unstable|testing
```

- Génère une liste de miroirs se trouvant dans le pays associé à l'adresse IP :

```bash
sudo pacman-mirrors --geoip
```
Liste des modifications apportées à cette documentation


Auteur | Description | Format de la date ISO 8601 | Lien vers GitHub
------|-----|-----|-----
[qontinuum-dev](mailto:79641156+qontinuum-dev@users.noreply.github.com) | pacman-*: add French translation (#7054) | 2021-11-07T13:35:24 | [0926e0fb59d4](https://github.com/tldr-pages/tldr/commit/0926e0fb59d438c47d8b3fdbc645c95b6fa5e2f6)

