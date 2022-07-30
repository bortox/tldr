---
author: ['lucas schneider', 'Nicolas Kosinski', 'CARE-COLIN Thibaut', 'bl-ue', 'marchersimon']
date: 1633592259
title: "git branch"
description: "git branch, Commande Git principale pour travailler avec des branches."
categories: "common"
---
> Plus d'informations : <https://git-scm.com/docs/git-branch>.

- Liste les branches locale en préfixant la branche courante avec `*` :

```bash
git branch
```

- Liste toutes les branches (locale et distantes) :

```bash
git branch -a
```

- Affiche le nom de la branche courante :

```bash
git branch --show-current
```

- Crée une nouvelle branche depuis le commit courant :

```bash
git branch nom_de_branche
```

- Crée une nouvelle branche depuis un commit en particulier :

```bash
git branch nom_de_branche commit_hash
```

- Renommer une branche (ne pas se trouver sur la branche pour le faire) :

```bash
git branch -m ancien_nom_de_branche nouveau_nom_de_branche
```

- Supprimer un branche locale (ne pas se trouver sur la branche pour le faire) :

```bash
git branch -d nom_de_branche
```

- Supprimer une branche distante :

```bash
git push nom_distant --delete nom_de_branche_distante
```
Liste des modifications apportées à cette documentation


Auteur | Description | Format de la date ISO 8601 | Lien vers GitHub
------|-----|-----|-----
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | Replace non-breaking space with regular space in French pages (#6842) | 2021-10-07T09:37:39 | [d63065b882e7](https://github.com/tldr-pages/tldr/commit/d63065b882e77c3d3361e76cfa7f28bf5415832e)
[Nicolas Kosinski](mailto:nicokosi@yahoo.com) | multiple pages: fix typos in French translation (#5841) | 2021-05-01T18:49:31 | [6467b39f66b4](https://github.com/tldr-pages/tldr/commit/6467b39f66b40110a64d13af20f1a7ab27380fa9)
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | multiple pages: fix French colon punctuation (#5152) | 2021-01-30T18:03:18 | [5f1ef5bee7db](https://github.com/tldr-pages/tldr/commit/5f1ef5bee7dba1b2749d25e4d0a7be22c89cf8b4)
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | multiple pages: normalize "more information" labels (#5140) | 2021-01-15T18:24:49 | [c59f12aa9f55](https://github.com/tldr-pages/tldr/commit/c59f12aa9f55d85612ba22e4da86db293ff76977)
[lucas schneider](mailto:casdpa@gmail.com) | rename git to Git | 2021-01-08T14:09:54 | [eef3712fc3a6](https://github.com/tldr-pages/tldr/commit/eef3712fc3a6a3774384b2e4ed934583c8349d75)
[CARE-COLIN Thibaut](mailto:carecolin@gmail.com) | git*: add French translation (#4619) | 2020-11-10T12:17:06 | [8c8314f72568](https://github.com/tldr-pages/tldr/commit/8c8314f7256871ec042395d6eef6d77827cda04c)

