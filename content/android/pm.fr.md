---
author: ['Nicolas Hansse']
date: 1633372595
title: "pm"
description: "pm, Afficher des informations sur les applications d'un appareil Android."
categories: "android"
---
> Plus d'informations : <https://developer.android.com/studio/command-line/adb#pm>.

- Affiche la liste des applications installées :

```bash
pm list packages
```

- Affiche une liste de toutes les applications système instalées :

```bash
pm list packages -s
```

- Affiche une liste de toutes les applications tierces :

```bash
pm list packages -3
```

- Affiche une liste des applications qui correspondent à des mots clés :

```bash
pm list packages mots_clés
```

- Affiche le chemin vers l'APK d'une application spécifique :

```bash
pm path application
```
Liste des modifications apportées à cette documentation


Auteur | Description | Format de la date ISO 8601 | Lien vers GitHub
------|-----|-----|-----
[Nicolas Hansse](mailto:nico.hansse@gmail.com) | android/*: add French translation (#6716) | 2021-10-04T20:36:35 | [1a1fc29b50c3](https://github.com/tldr-pages/tldr/commit/1a1fc29b50c3a931756fb51d571ca61a43e70067)

