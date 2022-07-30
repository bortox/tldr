---
author: ['Neluji']
date: 1634661236
title: "ssh-add"
description: "ssh-add, Gère les clés SSH enregistrées dans l'agent SSH `ssh-agent`."
categories: "common"
---
> S'assurer que `ssh-agent` est en fonctionnement pour enregistrer des clés.

> Plus d'informations : <https://man.openbsd.org/ssh-add>.

- Ajoute les clés présentes dans `~/.ssh` (clés par défaut) à l'agent SSH :

```bash
ssh-add
```

- Ajoute une clé spécifique à l'agent SSH :

```bash
ssh-add chemin/vers/clé_privée
```

- Liste les empreintes des clés actuellement enregistrées :

```bash
ssh-add -l
```

- Supprime une clé de l'agent SSH :

```bash
ssh-add -d chemin/vers/clé_privée
```

- Supprime toutes les clés enregistrées de l'agent SSH :

```bash
ssh-add -D
```

- Ajoute une clé spécifique à l'agent SSH et au trousseau de clés :

```bash
ssh-add -K chemin/vers/clé_privée
```
Liste des modifications apportées à cette documentation


Auteur | Description | Format de la date ISO 8601 | Lien vers GitHub
------|-----|-----|-----
[Neluji](mailto:38362829+Neluji@users.noreply.github.com) | ssh-*: add French translation (#6970) | 2021-10-19T18:33:56 | [7d92295ce701](https://github.com/tldr-pages/tldr/commit/7d92295ce7014b1167a9d6370e83891749412f83)

