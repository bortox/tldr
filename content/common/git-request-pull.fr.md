---
author: ['CARE-COLIN Thibaut', 'bl-ue', 'marchersimon']
date: 1633592259
title: "git request-pull"
description: "git request-pull, Générer une requête demandant au projet en amont d'inclure les modifications dans son arborescence."
categories: "common"
---
> Plus d'informations : <https://git-scm.com/docs/git-request-pull>.

- Produire une requête résumant les changements entre la version v1.1 et le master :

```bash
git request-pull v1.1 https://example.com/project master
```

- Produire une requête résumant les changements entre la version v1.1 sur la branche master et la branche locale foo :

```bash
git request-pull v0.1 https://example.com/project master:foo
```
Liste des modifications apportées à cette documentation


Auteur | Description | Format de la date ISO 8601 | Lien vers GitHub
------|-----|-----|-----
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | Replace non-breaking space with regular space in French pages (#6842) | 2021-10-07T09:37:39 | [d63065b882e7](https://github.com/tldr-pages/tldr/commit/d63065b882e77c3d3361e76cfa7f28bf5415832e)
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | multiple pages: fix French colon punctuation (#5152) | 2021-01-30T18:03:18 | [5f1ef5bee7db](https://github.com/tldr-pages/tldr/commit/5f1ef5bee7dba1b2749d25e4d0a7be22c89cf8b4)
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | multiple pages: normalize "more information" labels (#5140) | 2021-01-15T18:24:49 | [c59f12aa9f55](https://github.com/tldr-pages/tldr/commit/c59f12aa9f55d85612ba22e4da86db293ff76977)
[CARE-COLIN Thibaut](mailto:carecolin@gmail.com) | git*: add French translation (#4619) | 2020-11-10T12:17:06 | [8c8314f72568](https://github.com/tldr-pages/tldr/commit/8c8314f7256871ec042395d6eef6d77827cda04c)

