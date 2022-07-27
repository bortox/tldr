---
author: ['qontinuum-dev']
date: 1636288524
title: "pacman --upgrade, TLDR Pages"
description: "pacman --upgrade, Mets à jour ou ajoute des paquets au système."
categories: "linux"
---
> Plus d'informations : <https://man.archlinux.org/man/pacman.8>.

- Affiche l'aide :

```bash
pacman --upgrade --help
```

- Installe un ou des paquets depuis le système de fichiers :

```bash
sudo pacman --upgrade chemin/vers/paquet1.pkg.tar.zst chemin/vers/paquet2.pkg.tar.zst
```

- Installe un paquet silencieusement :

```bash
sudo pacman --upgrade --noconfirm chemin/vers/paquet.pkg.tar.zst
```

- Ecris par dessus les fichiers en conflit pendant l'installation du paquet :

```bash
sudo pacman --upgrade --overwrite chemin/vers/fichier chemin/vers/paquet.pkg.tar.zst
```

- Installe un paquet sans vérifier les dépendances :

```bash
sudo pacman --upgrade --nodeps chemin/vers/paquet.pkg.tar.zst
```

- Affiche ce qui se passerait si la commande était exécutée mais sans agir :

```bash
pacman --query --print chemin/vers/paquet.pkg.tar.zst
```
Liste des modifications apportées à cette documentation


Auteur | Description | Format de la date ISO 8601 | Lien vers GitHub
------|-----|-----|-----
[qontinuum-dev](mailto:79641156+qontinuum-dev@users.noreply.github.com) | pacman-*: add French translation (#7054) | 2021-11-07T13:35:24 | [0926e0fb59d4](https://github.com/tldr-pages/tldr/commit/0926e0fb59d438c47d8b3fdbc645c95b6fa5e2f6)

