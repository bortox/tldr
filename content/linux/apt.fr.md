---
author: ['Reinhart Previano Koentjoro', 'Patrice Denis', 'Bruno Bonnin', 'bl-ue', 'marchersimon']
date: 1641608133
title: "apt, TLDR Pages"
description: "apt, Utilitaire de gestion des paquets pour les distributions basées sur Debian."
categories: "linux"
---
> Remplacement recommandé pour `apt-get` lorsqu'il est utilisé de manière interactive dans les versions 16.04 et ultérieures d'Ubuntu.

> Plus d'informations : <https://manpages.debian.org/latest/apt/apt.8.html>.

- Mettre à jour la liste des paquets et des versions disponibles (il est recommandé de l'exécuter avant les autres commandes `apt`) :

```bash
sudo apt update
```

- Recherche d'un paquet donné :

```bash
apt search package
```

- Afficher les informations pour un paquet :

```bash
apt show package
```

- Installer un paquet, ou le mettre à jour avec la dernière version disponible :

```bash
sudo apt install package
```

- Supprimer un paquet (utiliser `purge` à la place supprime également ses fichiers de configuration) :

```bash
sudo apt remove package
```

- Mettre à jour tous les paquets installés vers les dernières versions disponibles :

```bash
sudo apt upgrade
```

- Lister tous les paquets :

```bash
apt list
```

- Lister les paquets installés :

```bash
apt list --installed
```
Liste des modifications apportées à cette documentation


Auteur | Description | Format de la date ISO 8601 | Lien vers GitHub
------|-----|-----|-----
[Reinhart Previano Koentjoro](mailto:reinhart_previano@yahoo.com) | apt: add backticks to apt-get (#7620) | 2022-01-08T03:15:33 | [e97d77689ab9](https://github.com/tldr-pages/tldr/commit/e97d77689ab99cfb2860768a9a50a0a65a4e03bd)
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | Replace non-breaking space with regular space in French pages (#6842) | 2021-10-07T09:37:39 | [d63065b882e7](https://github.com/tldr-pages/tldr/commit/d63065b882e77c3d3361e76cfa7f28bf5415832e)
[Patrice Denis](mailto:patrice.denis@gmail.com) | apt-*: add more info links; apt-file: add regex search example (#5710) | 2021-04-17T15:26:03 | [ca8394dc52de](https://github.com/tldr-pages/tldr/commit/ca8394dc52def4e55971ce4049b20fa8839f464d)
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | multiple pages: fix French colon punctuation (#5152) | 2021-01-30T18:03:18 | [5f1ef5bee7db](https://github.com/tldr-pages/tldr/commit/5f1ef5bee7dba1b2749d25e4d0a7be22c89cf8b4)
[Bruno Bonnin](mailto:bbonnin@gmail.com) | apt*: add French translation (#4441) | 2020-10-05T12:22:02 | [2f3bf0f7ec62](https://github.com/tldr-pages/tldr/commit/2f3bf0f7ec62df41ac98d17cddd78b19fde0884b)

