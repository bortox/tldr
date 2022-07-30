---
author: ['Nicolas Hansse']
date: 1633372595
title: "logcat"
description: "logcat, Exporte une log depuis les messages système."
categories: "android"
---
> Plus d'informations : <https://developer.android.com/studio/command-line/logcat>.

- Affiche la journalisation système :

```bash
logcat
```

- Écris la journalisation système dans un fichier :

```bash
logcat -f chemin/vers/fichier
```

- Affiche les lignes qui correspondent à une expression régulière :

```bash
logcat --regex expression_régulière
```
Liste des modifications apportées à cette documentation


Auteur | Description | Format de la date ISO 8601 | Lien vers GitHub
------|-----|-----|-----
[Nicolas Hansse](mailto:nico.hansse@gmail.com) | android/*: add French translation (#6716) | 2021-10-04T20:36:35 | [1a1fc29b50c3](https://github.com/tldr-pages/tldr/commit/1a1fc29b50c3a931756fb51d571ca61a43e70067)

