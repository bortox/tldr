---
author: ['qontinuum-dev']
date: 1636288524
title: "pacman --deptest, TLDR Pages"
description: "pacman --deptest, Vérifie la satisfaction des dépendances et renvoie celles qui ne le sont pas."
categories: "linux"
---
> Plus d'informations : <https://man.archlinux.org/man/pacman.8>.

- Affiche les noms des paquets qui ne sont pas installés dans la liste :

```bash
pacman --deptest paquet1 paquet2
```

- Vérifie que le paquet installé a une version supérieure ou égale :

```bash
pacman --deptest "bash>=5"
```

- Vérifie qu'une version ultérieure du paquet est installée :

```bash
pacman --deptest "bash>5"
```

- Affiche l'aide :

```bash
pacman --deptest --help
```
Liste des modifications apportées à cette documentation


Auteur | Description | Format de la date ISO 8601 | Lien vers GitHub
------|-----|-----|-----
[qontinuum-dev](mailto:79641156+qontinuum-dev@users.noreply.github.com) | pacman-*: add French translation (#7054) | 2021-11-07T13:35:24 | [0926e0fb59d4](https://github.com/tldr-pages/tldr/commit/0926e0fb59d438c47d8b3fdbc645c95b6fa5e2f6)

