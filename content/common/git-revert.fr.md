---
author: ['CARE-COLIN Thibaut', 'Nicolas Kosinski', 'Andrew McIntosh', 'bl-ue', 'marchersimon']
date: 1633592259
title: "git revert, TLDR Pages"
description: "git revert, Créer un nouveau commit qui efface les changements du précédent."
categories: "common"
---
> Plus d'informations : <https://git-scm.com/docs/git-revert>.

- Crée un commit qui annule les changements du dernier commit :

```bash
git revert HEAD
```

- Crée un commit qui annule les changements des 5 dernier commit :

```bash
git revert HEAD~4
```

- Crée un commit qui annule les changements de plusieurs commit :

```bash
git revert master~5..master~2
```

- Ne pas créer de nouveau commit, remplacer uniquement dans l'arbre courant :

```bash
git revert -n 0c01a9..9a1743
```
Liste des modifications apportées à cette documentation


Auteur | Description | Format de la date ISO 8601 | Lien vers GitHub
------|-----|-----|-----
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | Replace non-breaking space with regular space in French pages (#6842) | 2021-10-07T09:37:39 | [d63065b882e7](https://github.com/tldr-pages/tldr/commit/d63065b882e77c3d3361e76cfa7f28bf5415832e)
[Andrew McIntosh](mailto:amcintosh@users.noreply.github.com) | git-revert: use HEAD in example (#6649) | 2021-10-01T20:47:08 | [55ec5b50d3f5](https://github.com/tldr-pages/tldr/commit/55ec5b50d3f56667aab8fbf89e61a8aa899fbbba)
[Nicolas Kosinski](mailto:nicokosi@yahoo.com) | multiple pages: fix typos in French translation (#5841) | 2021-05-01T18:49:31 | [6467b39f66b4](https://github.com/tldr-pages/tldr/commit/6467b39f66b40110a64d13af20f1a7ab27380fa9)
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | multiple pages: fix French colon punctuation (#5152) | 2021-01-30T18:03:18 | [5f1ef5bee7db](https://github.com/tldr-pages/tldr/commit/5f1ef5bee7dba1b2749d25e4d0a7be22c89cf8b4)
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | multiple pages: normalize "more information" labels (#5140) | 2021-01-15T18:24:49 | [c59f12aa9f55](https://github.com/tldr-pages/tldr/commit/c59f12aa9f55d85612ba22e4da86db293ff76977)
[CARE-COLIN Thibaut](mailto:carecolin@gmail.com) | git*: add French translation (#4619) | 2020-11-10T12:17:06 | [8c8314f72568](https://github.com/tldr-pages/tldr/commit/8c8314f7256871ec042395d6eef6d77827cda04c)

