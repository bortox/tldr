---
author: ['qontinuum-dev']
date: 1636288524
title: "pacman --query, TLDR Pages"
description: "pacman --query, Fais des requêtes dans la base de données des paquets installés."
categories: "linux"
---
> Plus d'informations : <https://man.archlinux.org/man/pacman.8>.

- Liste les paquets installés et leur version :

```bash
pacman --query
```

- Liste uniquement les paquets installés explicitement :

```bash
pacman --query --explicit
```

- Trouve le paquet propriétaire d'un fichier :

```bash
pacman --query --owns fichier
```

- Affiche des informations sur un paquet installé :

```bash
pacman --query --info paquet
```

- Liste les fichiers appartenant à un paquet :

```bash
pacman --query --list paquet
```

- Liste les paquets orphelins (installés en tant que dépendances mais requis par aucun paquet installé) :

```bash
pacman --query --unrequired --deps --quiet
```

- Liste les paquets installés ne se trouvant pas dans les dépôts :

```bash
pacman --query --foreign
```

- Liste les paquets périmés :

```bash
pacman --query --upgrades
```
Liste des modifications apportées à cette documentation


Auteur | Description | Format de la date ISO 8601 | Lien vers GitHub
------|-----|-----|-----
[qontinuum-dev](mailto:79641156+qontinuum-dev@users.noreply.github.com) | pacman-*: add French translation (#7054) | 2021-11-07T13:35:24 | [0926e0fb59d4](https://github.com/tldr-pages/tldr/commit/0926e0fb59d438c47d8b3fdbc645c95b6fa5e2f6)

