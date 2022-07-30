---
author: ['Nicolas Hansse']
date: 1658041505
title: "amass track"
description: "amass track, Traque les différences entre les énumérations d'un même domaine."
categories: "common"
---
> Plus d'informations : <https://github.com/OWASP/Amass/blob/master/doc/user_guide.md#the-track-subcommand>.

- Affiche la différence entre les deux dernières énumérations d'un domaine donné :

```bash
amass track -dir chemin/vers/la_base_de_données -d nom_de_domaine -last 2
```

- Affiche la différence entre un certain moment dans le temps et la dernière énumération :

```bash
amass track -dir chemin/vers/la_base_de_données -d nom_de_domaine -since 01/02 15:04:05 2006 MST
```
Liste des modifications apportées à cette documentation


Auteur | Description | Format de la date ISO 8601 | Lien vers GitHub
------|-----|-----|-----
[Nicolas Hansse](mailto:nico.hansse@gmail.com) | amass-intel, amass-track, amass-viz: add French translation (#8210) | 2022-07-17T09:05:05 | [3ce8ac7de035](https://github.com/tldr-pages/tldr/commit/3ce8ac7de035f7f1be6e9285df49bbe28b35ad56)

