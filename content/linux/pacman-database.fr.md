---
author: ['qontinuum-dev']
date: 1636288524
title: "pacman --database, TLDR Pages"
description: "pacman --database, Interagis avec les bases de données des paquets Arch Linux."
categories: "linux"
---
> Modifie des attributs des paquets installés.

> Plus d'informations : <https://man.archlinux.org/man/pacman.8>.

- Affiche l'aide :

```bash
pacman --database --help
```

- Marque un paquet comme étant installé en tant que dépendance :

```bash
sudo pacman --database --asdeps paquet
```

- Marque un paquet comme étant explicitement installé :

```bash
sudo pacman --database --asexplicit paquet
```

- Vérifie les dépendances de tous les paquets installés :

```bash
pacman --database --check
```

- Vérifie que toutes les dépendances des paquets installés sont disponibles dans les dépôts :

```bash
pacman --database --check --check
```

- N'affiche que les messages d'erreur :

```bash
pacman --database --check --quiet
```
Liste des modifications apportées à cette documentation


Auteur | Description | Format de la date ISO 8601 | Lien vers GitHub
------|-----|-----|-----
[qontinuum-dev](mailto:79641156+qontinuum-dev@users.noreply.github.com) | pacman-*: add French translation (#7054) | 2021-11-07T13:35:24 | [0926e0fb59d4](https://github.com/tldr-pages/tldr/commit/0926e0fb59d438c47d8b3fdbc645c95b6fa5e2f6)

