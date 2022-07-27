---
author: ['qontinuum-dev']
date: 1636288524
title: "pacman --sync, TLDR Pages"
description: "pacman --sync, Synchronise les paquets."
categories: "linux"
---
> Plus d'informations : <https://man.archlinux.org/man/pacman.8>.

- Installe un nouveau paquet :

```bash
sudo pacman --sync paquet
```

- Synchronise et mettre à jour :

```bash
sudo pacman --sync --refresh --sysupgrade
```

- Synchronise, mets à jour et installe un paquet sans demander de confirmation :

```bash
sudo pacman --sync --refresh --sysupgrade --noconfirm paquet
```

- Recherche un paquet en utilisant un nom ou une expression régulière :

```bash
pacman --sync --search "motif"
```

- Affiche des informations sur un paquet :

```bash
pacman --sync --info paquet
```

- Ecris par dessus des fichiers pendant une mise à jour :

```bash
sudo pacman --sync --refresh --sysupgrade --overwrite path/to/file
```

- Synchronise et mets à jour les paquets, en ignorant un paquet (peut être utilisé plusieurs fois) :

```bash
sudo pacman --sync --refresh --sysupgrade --ignore paquet
```

- Supprime les fichiers concernant des paquets non installés et les dépôts supprimés du cache de pacman :

```bash
sudo pacman --sync --clean
```
Liste des modifications apportées à cette documentation


Auteur | Description | Format de la date ISO 8601 | Lien vers GitHub
------|-----|-----|-----
[qontinuum-dev](mailto:79641156+qontinuum-dev@users.noreply.github.com) | pacman-*: add French translation (#7054) | 2021-11-07T13:35:24 | [0926e0fb59d4](https://github.com/tldr-pages/tldr/commit/0926e0fb59d438c47d8b3fdbc645c95b6fa5e2f6)

