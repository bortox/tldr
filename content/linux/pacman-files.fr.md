---
author: ['qontinuum-dev']
date: 1636288524
title: "pacman --files"
description: "pacman --files, Interagis avec les bases de données de fichiers."
categories: "linux"
---
> Voir aussi `pkgfile`.

> Plus d'informations : <https://man.archlinux.org/man/pacman.8>.

- Affiche l'aide :

```bash
pacman --files --help
```

- Mets à jour les bases de données des fichiers :

```bash
sudo pacman --files --refresh
```

- Trouve les paquets contenant un fichier spécifique :

```bash
pacman --files fichier
```

- Trouve les paquets contenant un fichier spécifique en utilisant une expression régulière :

```bash
pacman --files --regex 'expression_reguliere'
```

- Liste uniquement les noms de paquets :

```bash
pacman --files --quiet fichier
```

- Liste les fichiers contenus dans un paquet :

```bash
pacman --files --list paquet
```
Liste des modifications apportées à cette documentation


Auteur | Description | Format de la date ISO 8601 | Lien vers GitHub
------|-----|-----|-----
[qontinuum-dev](mailto:79641156+qontinuum-dev@users.noreply.github.com) | pacman-*: add French translation (#7054) | 2021-11-07T13:35:24 | [0926e0fb59d4](https://github.com/tldr-pages/tldr/commit/0926e0fb59d438c47d8b3fdbc645c95b6fa5e2f6)

