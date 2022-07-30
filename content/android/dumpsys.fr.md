---
author: ['Nicolas Hansse']
date: 1633372595
title: "dumpsys"
description: "dumpsys, Fourni des informations sur les services du système Android."
categories: "android"
---
> Cette commande peut être utilisé uniquement depuis `adb shell`.

> Plus d'informations : <https://developer.android.com/studio/command-line/dumpsys>.

- Récupère un diagnostic pour chaque service système :

```bash
dumpsys
```

- Récupère un diagnostic pour un service système spécifique :

```bash
dumpsys service
```

- Liste tous les services dont `dumpsys` peut donner les informations :

```bash
dumpsys -l
```

- Liste les arguments spécifiques d'un service :

```bash
dumpsys service -h
```

- Exclus un service spécifique d'un diagnostic :

```bash
dumpsys --skip service
```

- Spécifie un temps limite en secondes (10s par défault) :

```bash
dumpsys -t seconds
```
Liste des modifications apportées à cette documentation


Auteur | Description | Format de la date ISO 8601 | Lien vers GitHub
------|-----|-----|-----
[Nicolas Hansse](mailto:nico.hansse@gmail.com) | android/*: add French translation (#6716) | 2021-10-04T20:36:35 | [1a1fc29b50c3](https://github.com/tldr-pages/tldr/commit/1a1fc29b50c3a931756fb51d571ca61a43e70067)

