---
author: ['Bruno Bonnin', 'Patrice Denis', 'bl-ue', 'marchersimon']
date: 1633592259
title: "apt-mark, TLDR Pages"
description: "apt-mark, Utilitaire permettant de modifier l'état des paquets installés."
categories: "linux"
---
> Plus d'informations : <https://manpages.debian.org/latest/apt/apt-mark.8.html>.

- Marquer un paquet comme étant automatiquement installé :

```bash
sudo apt-mark auto package_name
```

- Maintenir un paquet à sa version actuelle et empêcher les mises à jour :

```bash
sudo apt-mark hold package_name
```

- Permettre une nouvelle mise à jour d'un paquet :

```bash
sudo apt-mark unhold package_name
```

- Afficher les paquets installés manuellement :

```bash
apt-mark showmanual
```

- Afficher les paquets détenus qui ne sont pas mis à jour :

```bash
apt-mark showhold
```
Liste des modifications apportées à cette documentation


Auteur | Description | Format de la date ISO 8601 | Lien vers GitHub
------|-----|-----|-----
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | Replace non-breaking space with regular space in French pages (#6842) | 2021-10-07T09:37:39 | [d63065b882e7](https://github.com/tldr-pages/tldr/commit/d63065b882e77c3d3361e76cfa7f28bf5415832e)
[Patrice Denis](mailto:patrice.denis@gmail.com) | apt-*: add more info links; apt-file: add regex search example (#5710) | 2021-04-17T15:26:03 | [ca8394dc52de](https://github.com/tldr-pages/tldr/commit/ca8394dc52def4e55971ce4049b20fa8839f464d)
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | multiple pages: fix French colon punctuation (#5152) | 2021-01-30T18:03:18 | [5f1ef5bee7db](https://github.com/tldr-pages/tldr/commit/5f1ef5bee7dba1b2749d25e4d0a7be22c89cf8b4)
[Bruno Bonnin](mailto:bbonnin@gmail.com) | apt*: add French translation (#4441) | 2020-10-05T12:22:02 | [2f3bf0f7ec62](https://github.com/tldr-pages/tldr/commit/2f3bf0f7ec62df41ac98d17cddd78b19fde0884b)

