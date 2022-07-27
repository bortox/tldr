---
author: ['Nicolas Hansse']
date: 1633372595
title: "am, TLDR Pages"
description: "am, Manager d'activité Android."
categories: "android"
---
> Plus d'informations : <https://developer.android.com/studio/command-line/adb#am>.

- Commence une activité spécifique :

```bash
am start -n com.android.settings/.Settings
```

- Commence une activité et insère de la donnée :

```bash
am start -a android.intent.action.VIEW -d tel:123
```

- Commence une activité qui correspond à une action et une catégorie spécifique :

```bash
am start -a android.intent.action.MAIN -c android.intent.category.HOME
```

- Convertis une intention en URI :

```bash
am to-uri -a android.intent.action.VIEW -d tel:123
```
Liste des modifications apportées à cette documentation


Auteur | Description | Format de la date ISO 8601 | Lien vers GitHub
------|-----|-----|-----
[Nicolas Hansse](mailto:nico.hansse@gmail.com) | android/*: add French translation (#6716) | 2021-10-04T20:36:35 | [1a1fc29b50c3](https://github.com/tldr-pages/tldr/commit/1a1fc29b50c3a931756fb51d571ca61a43e70067)

