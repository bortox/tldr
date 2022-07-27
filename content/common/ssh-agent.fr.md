---
author: ['Neluji']
date: 1634661236
title: "ssh-agent, TLDR Pages"
description: "ssh-agent, Lance un agent SSH."
categories: "common"
---
> Un agent SSH permet de stocker des clés SSH déchiffrées, jusqu'à ce qu'elle soient retirées ou que l'agent soit arrêté.

> Voir également `ssh-add`, qui permet d'ajouter et de gérer les clés enregistrées par l'agent SSH.

> Plus d'informations : <https://man.openbsd.org/ssh-agent>.

- Démarre un agent SSH pour le shell actuel :

```bash
eval $(ssh-agent)
```

- Arrête l'agent actuellement en fonctionnement :

```bash
ssh-agent -k
```
Liste des modifications apportées à cette documentation


Auteur | Description | Format de la date ISO 8601 | Lien vers GitHub
------|-----|-----|-----
[Neluji](mailto:38362829+Neluji@users.noreply.github.com) | ssh-*: add French translation (#6970) | 2021-10-19T18:33:56 | [7d92295ce701](https://github.com/tldr-pages/tldr/commit/7d92295ce7014b1167a9d6370e83891749412f83)

