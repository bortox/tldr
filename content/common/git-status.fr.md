---
author: ['Simon Landry', 'CARE-COLIN Thibaut', 'Nicolas Kosinski', 'bl-ue', 'marchersimon']
date: 1633592259
title: "git status, TLDR Pages"
description: "git status, Affiche les changements sur les fichiers dans la branche courante."
categories: "common"
---
> Affiche les fichiers édités, déplacés, renommés, ajoutés, supprimés par rapport à la référence de la branche courante.

> Plus d'informations : <https://git-scm.com/docs/git-status>.

- Affiche les fichiers modifiés qui n'ont pas encore été ajoutés pour le commit :

```bash
git status
```

- Affiche les fichiers modifiés (version courte) :

```bash
git status -s
```

- Affiche les fichiers modifiés, sans tenir des comptes des fichiers non-suivis :

```bash
git status --untracked-files=no
```

- Affiche les fichiers modifiés (version courte) avec les informations de branche :

```bash
git status -sb
```
Liste des modifications apportées à cette documentation


Auteur | Description | Format de la date ISO 8601 | Lien vers GitHub
------|-----|-----|-----
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | Replace non-breaking space with regular space in French pages (#6842) | 2021-10-07T09:37:39 | [d63065b882e7](https://github.com/tldr-pages/tldr/commit/d63065b882e77c3d3361e76cfa7f28bf5415832e)
[Nicolas Kosinski](mailto:nicokosi@yahoo.com) | multiple pages: fix typos in French translation (#5841) | 2021-05-01T18:49:31 | [6467b39f66b4](https://github.com/tldr-pages/tldr/commit/6467b39f66b40110a64d13af20f1a7ab27380fa9)
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | multiple pages: fix French colon punctuation (#5152) | 2021-01-30T18:03:18 | [5f1ef5bee7db](https://github.com/tldr-pages/tldr/commit/5f1ef5bee7dba1b2749d25e4d0a7be22c89cf8b4)
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | multiple pages: normalize "more information" labels (#5140) | 2021-01-15T18:24:49 | [c59f12aa9f55](https://github.com/tldr-pages/tldr/commit/c59f12aa9f55d85612ba22e4da86db293ff76977)
[CARE-COLIN Thibaut](mailto:carecolin@gmail.com) | git*: add French translation (#4619) | 2020-11-10T12:17:06 | [8c8314f72568](https://github.com/tldr-pages/tldr/commit/8c8314f7256871ec042395d6eef6d77827cda04c)
[Simon Landry](mailto:landry_simon@pm.me) | git-status: add French translation (#4622) | 2020-10-12T23:08:29 | [7cc20f8258b0](https://github.com/tldr-pages/tldr/commit/7cc20f8258b017443f7b447055d407d1d2554c6e)

