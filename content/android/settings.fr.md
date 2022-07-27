---
author: ['Nicolas Hansse']
date: 1633372595
title: "settings, TLDR Pages"
description: "settings, Récupère les informations du système d'exploitation Android."
categories: "android"
---
> Plus d'informations : <https://adbinstaller.com/commands/adb-shell-settings-5b670d5ee7958178a2955536>.

- Affiche une liste des paramètres de l'espace de nom `global` :

```bash
settings list global
```

- Récupère la valeur d'un paramètre :

```bash
settings get global airplane_mode_on
```

- Assigne une valeur à un paramètre :

```bash
settings put system screen_brightness 42
```

- Supprime un paramètre :

```bash
settings delete secure screensaver_enabled
```
Liste des modifications apportées à cette documentation


Auteur | Description | Format de la date ISO 8601 | Lien vers GitHub
------|-----|-----|-----
[Nicolas Hansse](mailto:nico.hansse@gmail.com) | android/*: add French translation (#6716) | 2021-10-04T20:36:35 | [1a1fc29b50c3](https://github.com/tldr-pages/tldr/commit/1a1fc29b50c3a931756fb51d571ca61a43e70067)

