---
author: ['Nicolas Kosinski', 'bl-ue', 'marchersimon', 'CARE-COLIN Thibaut']
date: 1633592259
title: "git send-email, TLDR Pages"
description: "git send-email, Envoyer une collection de correctifs par email."
categories: "common"
---
> Les correctifs peuvent être spécifiés sous forme de fichiers, de directions ou de liste de révisions.

> Plus d'informations : <https://git-scm.com/docs/git-send-email>.

- Envoyer le dernier commit de la branche courante :

```bash
git send-email -1
```

- envoyer un commit spécifique :

```bash
git send-email -1 commit
```

- envoyer de multiples commits de la branche courante (ici : 10) :

```bash
git send-email -10
```

- Envoyez un e-mail de présentation de la série de correctifs :

```bash
git send-email -number of commits --compose
```

- Consultez et modifiez l'e-mail de chaque patch que vous êtes sur le point d'envoyer :

```bash
git send-email -number of commits --annotate
```
Liste des modifications apportées à cette documentation


Auteur | Description | Format de la date ISO 8601 | Lien vers GitHub
------|-----|-----|-----
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | Replace non-breaking space with regular space in French pages (#6842) | 2021-10-07T09:37:39 | [d63065b882e7](https://github.com/tldr-pages/tldr/commit/d63065b882e77c3d3361e76cfa7f28bf5415832e)
[Nicolas Kosinski](mailto:nicokosi@yahoo.com) | multiple pages: fix typos in French translation (#5841) | 2021-05-01T18:49:31 | [6467b39f66b4](https://github.com/tldr-pages/tldr/commit/6467b39f66b40110a64d13af20f1a7ab27380fa9)
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | multiple pages: fix French colon punctuation (#5152) | 2021-01-30T18:03:18 | [5f1ef5bee7db](https://github.com/tldr-pages/tldr/commit/5f1ef5bee7dba1b2749d25e4d0a7be22c89cf8b4)
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | multiple pages: normalize "more information" labels (#5140) | 2021-01-15T18:24:49 | [c59f12aa9f55](https://github.com/tldr-pages/tldr/commit/c59f12aa9f55d85612ba22e4da86db293ff76977)
[CARE-COLIN Thibaut](mailto:carecolin@gmail.com) | git*: add French translation (#4619) | 2020-11-10T12:17:06 | [8c8314f72568](https://github.com/tldr-pages/tldr/commit/8c8314f7256871ec042395d6eef6d77827cda04c)

