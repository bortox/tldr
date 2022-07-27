---
author: ['qontinuum-dev']
date: 1636288524
title: "pacman --remove, TLDR Pages"
description: "pacman --remove, Supprimes des paquets."
categories: "linux"
---
> Plus d'informations : <https://man.archlinux.org/man/pacman.8>.

- Affiche l'aide :

```bash
pacman --remove --help
```

- Supprime un paquet et ses dépendances :

```bash
sudo pacman --remove --recursive paquet
```

- Supprime un paquet, ses dépendances et ses fichiers de configuration :

```bash
sudo pacman --remove --recursive --nosave paquet
```

- Supprime un paquet silencieusement :

```bash
sudo pacman --remove --noconfirm paquet
```

- Supprime les paquets orphelins (installés en tant que dépendance mais requis par aucun paquet installé) :

```bash
sudo pacman --remove --recursive --nosave $(pacman --query --unrequired --deps --quiet)
```

- Supprime un paquet et les paquets qui en dépendent :

```bash
sudo pacman --remove --cascade paquet
```

- Affiche les paquets qui seraient affectés par la commande sans agir :

```bash
pacman --remove --print paquet
```
Liste des modifications apportées à cette documentation


Auteur | Description | Format de la date ISO 8601 | Lien vers GitHub
------|-----|-----|-----
[qontinuum-dev](mailto:79641156+qontinuum-dev@users.noreply.github.com) | pacman-*: add French translation (#7054) | 2021-11-07T13:35:24 | [0926e0fb59d4](https://github.com/tldr-pages/tldr/commit/0926e0fb59d438c47d8b3fdbc645c95b6fa5e2f6)

