---
author: ['Neluji']
date: 1634661236
title: "ssh-copy-id, TLDR Pages"
description: "ssh-copy-id, Dépose une clé publique sur une machine distante, dans les clés autorisées `authorized_keys`."
categories: "common"
---
> Plus d'informations : <https://manned.org/ssh-copy-id>.

- Dépose toutes les clés publiques sur la machine distante :

```bash
ssh-copy-id nom_utilisateur@hote_distant
```

- Dépose une clé publique spécifique sur la machine distante :

```bash
ssh-copy-id -i chemin/vers/certificat nom_utilisateur@hote_distant
```

- Dépose une clé publique spécifique sur la machine distante en utilisant un port particulier :

```bash
ssh-copy-id -i chemin/vers/certificat -p port nom_utilisateur@hote_distant
```
Liste des modifications apportées à cette documentation


Auteur | Description | Format de la date ISO 8601 | Lien vers GitHub
------|-----|-----|-----
[Neluji](mailto:38362829+Neluji@users.noreply.github.com) | ssh-*: add French translation (#6970) | 2021-10-19T18:33:56 | [7d92295ce701](https://github.com/tldr-pages/tldr/commit/7d92295ce7014b1167a9d6370e83891749412f83)

