---
author: ['Lucas Gabriel Schneider', 'Bruno Bonnin', 'bl-ue', 'Patrice Denis', 'marchersimon']
date: 1633592259
title: "apt-get"
description: "apt-get, Utilitaire de gestion des paquets Debian et Ubuntu."
categories: "linux"
---
> Recherche des paquets en utilisant `apt-cache`.

> Plus d'informations : <https://manpages.debian.org/latest/apt/apt-get.8.html>.

- Mise à jour de la liste des paquets et des versions disponibles (il est recommandé de l'exécuter avant les autres commandes `apt-get`) :

```bash
apt-get update
```

- Installation d'un paquet, ou mise à jour avec la dernière version disponible :

```bash
apt-get install package
```

- Suppression d'un paquet :

```bash
apt-get remove package
```

- Suppression d'un paquet et de ses fichiers de configuration :

```bash
apt-get purge package
```

- Mise à jour de tous les paquets installés vers les dernières versions disponibles :

```bash
apt-get upgrade
```

- Nettoyage du dépôt local - supprime les fichiers de paquets (`.deb`) des téléchargements interrompus qui ne peuvent plus être téléchargés :

```bash
apt-get autoclean
```

- Suppression de tous les paquets qui ne sont plus nécessaires :

```bash
apt-get autoremove
```

- Mise à jour des paquets installés (comme la commande `upgrade`), mais avec suppression des paquets obsolètes et installation des paquets supplémentaires pour répondre aux nouvelles dépendances :

```bash
apt-get dist-upgrade
```
Liste des modifications apportées à cette documentation


Auteur | Description | Format de la date ISO 8601 | Lien vers GitHub
------|-----|-----|-----
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | Replace non-breaking space with regular space in French pages (#6842) | 2021-10-07T09:37:39 | [d63065b882e7](https://github.com/tldr-pages/tldr/commit/d63065b882e77c3d3361e76cfa7f28bf5415832e)
[Patrice Denis](mailto:patrice.denis@gmail.com) | apt-*: add more info links; apt-file: add regex search example (#5710) | 2021-04-17T15:26:03 | [ca8394dc52de](https://github.com/tldr-pages/tldr/commit/ca8394dc52def4e55971ce4049b20fa8839f464d)
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | *: trim multiple spaces, fix line endings | 2021-04-04T01:44:24 | [04dd546e2de7](https://github.com/tldr-pages/tldr/commit/04dd546e2de7f59f40a867acca6f46b0dc8ea9b4)
[Lucas Gabriel Schneider](mailto:casdpa@gmail.com) | multiple pages: format technical tokens (#5119) Co-authored-by: bl-ue <54780737+bl-ue@users.noreply.github.com> Co-authored-by: [...] | 2021-01-31T18:05:18 | [a5fe31bc47ae](https://github.com/tldr-pages/tldr/commit/a5fe31bc47aece3efa5e66b52b3cf384f27d5d72)
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | multiple pages: fix French colon punctuation (#5152) | 2021-01-30T18:03:18 | [5f1ef5bee7db](https://github.com/tldr-pages/tldr/commit/5f1ef5bee7dba1b2749d25e4d0a7be22c89cf8b4)
[Bruno Bonnin](mailto:bbonnin@gmail.com) | apt*: add French translation (#4441) | 2020-10-05T12:22:02 | [2f3bf0f7ec62](https://github.com/tldr-pages/tldr/commit/2f3bf0f7ec62df41ac98d17cddd78b19fde0884b)

