---
author: ['bl-ue', 'marchersimon', 'CARE-COLIN Thibaut']
date: 1633592259
title: "git shortlog, TLDR Pages"
description: "git shortlog, Récapitule la sortie de `git log`."
categories: "common"
---
> Plus d'informations : <https://git-scm.com/docs/git-shortlog>.

- Afficher un résumé de tous les commits effectués, regroupés par ordre alphabétique par nom d'auteur :

```bash
git shortlog
```

- Afficher un résumé de tous les commits effectués, regroupés par le nombre de commits effectués :

```bash
git shortlog -n
```

- Afficher un résumé de tous les commits effectués, regroupés par le nom et l'email de l'utilisateur :

```bash
git shortlog -c
```

- fficher un résumé des 5 derniers commits effectués :

```bash
git shortlog HEAD~5..HEAD
```

- Afficher tout les utilisateurs, emails et le nombre de commits dans la branche :

```bash
git shortlog -sne
```

- Afficher tout les utilisateurs, emails et le nombre de commits dans toutes les branches :

```bash
git shortlog -sne --all
```
Liste des modifications apportées à cette documentation


Auteur | Description | Format de la date ISO 8601 | Lien vers GitHub
------|-----|-----|-----
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | Replace non-breaking space with regular space in French pages (#6842) | 2021-10-07T09:37:39 | [d63065b882e7](https://github.com/tldr-pages/tldr/commit/d63065b882e77c3d3361e76cfa7f28bf5415832e)
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | multiple pages: fix French colon punctuation (#5152) | 2021-01-30T18:03:18 | [5f1ef5bee7db](https://github.com/tldr-pages/tldr/commit/5f1ef5bee7dba1b2749d25e4d0a7be22c89cf8b4)
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | multiple pages: normalize "more information" labels (#5140) | 2021-01-15T18:24:49 | [c59f12aa9f55](https://github.com/tldr-pages/tldr/commit/c59f12aa9f55d85612ba22e4da86db293ff76977)
[CARE-COLIN Thibaut](mailto:carecolin@gmail.com) | git*: add French translation (#4619) | 2020-11-10T12:17:06 | [8c8314f72568](https://github.com/tldr-pages/tldr/commit/8c8314f7256871ec042395d6eef6d77827cda04c)

