---
author: ['Neluji']
date: 1634661236
title: "ssh-keyscan, TLDR Pages"
description: "ssh-keyscan, Récupère les clés SSH publiques de machines distantes."
categories: "common"
---
> Plus d'informations : <https://man.openbsd.org/ssh-keyscan>.

- Récupère toutes les clés d'une machine distante :

```bash
ssh-keyscan hote_distant
```

- Récupère toutes les clés d'une machine distante en écoutant sur un port particulier :

```bash
ssh-keyscan -p port hote_distant
```

- Récupère un type particulier de clés d'une machine distante :

```bash
ssh-keyscan -t rsa,dsa,ecdsa,ed25519 hote_distant
```

- Met à jour manuellement le fichier `known_hosts` des hôtes connus avec l'empreinte d'une :

```bash
ssh-keyscan -H hote_distant >> ~/.ssh/known_hosts
```
Liste des modifications apportées à cette documentation


Auteur | Description | Format de la date ISO 8601 | Lien vers GitHub
------|-----|-----|-----
[Neluji](mailto:38362829+Neluji@users.noreply.github.com) | ssh-*: add French translation (#6970) | 2021-10-19T18:33:56 | [7d92295ce701](https://github.com/tldr-pages/tldr/commit/7d92295ce7014b1167a9d6370e83891749412f83)

