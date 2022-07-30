---
author: ['qontinuum-dev']
date: 1636288524
title: "pacman-key"
description: "pacman-key, Script enrobeur pour GnuPG utilisé pour gérer le trousseau de clés de pacman."
categories: "linux"
---
> Plus d'informations : <https://man.archlinux.org/man/pacman-key>.

- Initialise le trousseau de clés de pacman :

```bash
sudo pacman-key --init
```

- Ajoute les clés par défaut pour Arch Linux :

```bash
sudo pacman-key --populate archlinux
```

- Liste les clés publiques du trousseau de clés :

```bash
pacman-key --list-keys
```

- Ajoute les clés contenues dans le fichier spécifié :

```bash
sudo pacman-key --add chemin/vers/fichier
```

- Reçois une clé depuis un serveur de clés :

```bash
sudo pacman-key --recv-keys "uid|nom|email"
```

- Affiche l'empreinte d'une clé du trousseau de clés :

```bash
pacman-key --finger "uid|nom|email"
```

- Signe, localement, une clé du trousseau de clés :

```bash
sudo pacman-key --lsign-key "uid|nom|email"
```

- Supprime une clé :

```bash
sudo pacman-key --delete "uid|nom|email"
```
Liste des modifications apportées à cette documentation


Auteur | Description | Format de la date ISO 8601 | Lien vers GitHub
------|-----|-----|-----
[qontinuum-dev](mailto:79641156+qontinuum-dev@users.noreply.github.com) | pacman-*: add French translation (#7054) | 2021-11-07T13:35:24 | [0926e0fb59d4](https://github.com/tldr-pages/tldr/commit/0926e0fb59d438c47d8b3fdbc645c95b6fa5e2f6)

