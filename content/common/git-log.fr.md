---
author: ['lucas schneider', 'Muhammad Falak R Wani', 'Nicolas Kosinski', 'CARE-COLIN Thibaut', 'bl-ue', 'marchersimon']
date: 1635631367
title: "git log"
description: "git log, Afficher un historique de commits."
categories: "common"
---
> Plus d'informations : <https://git-scm.com/docs/git-log>.

- Afficher la séquence de commits à partir de l'actuel, dans l'ordre chronologique inverse du dépôt Git dans le répertoire de travail actuel :

```bash
git log
```

- Afficher l'historique de fichiers ou répertoires en particulier :

```bash
git log -p chemin/vers/fichier_ou_repertoire
```

- Afficher la liste des fichiers modifiés pour chaque commit :

```bash
git log --stat
```

- Afficher un graphique des commits dans la branche actuelle en utilisant uniquement la première ligne de chaque message de commit :

```bash
git log --oneline --graph
```

- Afficher un graphique de tout les commits, tags et branches dans le dépôt entier :

```bash
git log --oneline --decorate --all --graph
```

- Afficher uniquement les commits dont le message contient la chaine (non sensible à la casse) :

```bash
git log -i --grep chaine_recherché
```

- Afficher les N derniers commits d'un utilisateur :

```bash
git log -n number --author=author
```

- Afficher les commits entre deux dates (yyyy-mm-dd):

```bash
git log --before="2017-01-29" --after="2017-01-17"
```
Liste des modifications apportées à cette documentation


Auteur | Description | Format de la date ISO 8601 | Lien vers GitHub
------|-----|-----|-----
[Muhammad Falak R Wani](mailto:falakreyaz@gmail.com) | git-log: clarify date format with example (#7150) | 2021-10-31T00:02:47 | [11f811cc994d](https://github.com/tldr-pages/tldr/commit/11f811cc994ddea4ff4dd07d254b0da120d2dc18)
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | Replace non-breaking space with regular space in French pages (#6842) | 2021-10-07T09:37:39 | [d63065b882e7](https://github.com/tldr-pages/tldr/commit/d63065b882e77c3d3361e76cfa7f28bf5415832e)
[Nicolas Kosinski](mailto:nicokosi@yahoo.com) | multiple pages: fix typos in French translation (#5841) | 2021-05-01T18:49:31 | [6467b39f66b4](https://github.com/tldr-pages/tldr/commit/6467b39f66b40110a64d13af20f1a7ab27380fa9)
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | multiple pages: fix French colon punctuation (#5152) | 2021-01-30T18:03:18 | [5f1ef5bee7db](https://github.com/tldr-pages/tldr/commit/5f1ef5bee7dba1b2749d25e4d0a7be22c89cf8b4)
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | multiple pages: normalize "more information" labels (#5140) | 2021-01-15T18:24:49 | [c59f12aa9f55](https://github.com/tldr-pages/tldr/commit/c59f12aa9f55d85612ba22e4da86db293ff76977)
[lucas schneider](mailto:casdpa@gmail.com) | rename git to Git | 2021-01-08T14:09:54 | [eef3712fc3a6](https://github.com/tldr-pages/tldr/commit/eef3712fc3a6a3774384b2e4ed934583c8349d75)
[CARE-COLIN Thibaut](mailto:carecolin@gmail.com) | git*: add French translation (#4619) | 2020-11-10T12:17:06 | [8c8314f72568](https://github.com/tldr-pages/tldr/commit/8c8314f7256871ec042395d6eef6d77827cda04c)

