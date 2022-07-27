---
author: ['Patrice Denis', 'CARE-COLIN Thibaut', 'lucas schneider', 'Nicolas Kosinski', 'bl-ue', 'marchersimon']
date: 1633592259
title: "git flow, TLDR Pages"
description: "git flow, Une collection d'extensions Git pour procurer des opérations supplémentaires sur les dépôts."
categories: "common"
---
> Plus d'informations : <https://github.com/nvie/gitflow>.

- Initialiser dans un registre Git existant :

```bash
git flow init
```

- Commencer le travail sur une fonctionnalité basé sur la branche `develop` :

```bash
git flow feature start feature
```

- Terminer le travail sur une branche de fonctionnalité, la fusionner dans la branche `develop` puis la supprimer :

```bash
git flow feature finish feature
```

- Publier une fonctionnalité sur le serveur distant :

```bash
git flow feature publish feature
```

- Récupérer une fonctionnalité publiée par un autre utilisateur :

```bash
git flow feature pull origin feature
```
Liste des modifications apportées à cette documentation


Auteur | Description | Format de la date ISO 8601 | Lien vers GitHub
------|-----|-----|-----
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | Replace non-breaking space with regular space in French pages (#6842) | 2021-10-07T09:37:39 | [d63065b882e7](https://github.com/tldr-pages/tldr/commit/d63065b882e77c3d3361e76cfa7f28bf5415832e)
[Patrice Denis](mailto:patricedenis@users.noreply.github.com) | multiple pages: fix typos in French translation (#5909) | 2021-06-23T02:34:03 | [a413b9555bc9](https://github.com/tldr-pages/tldr/commit/a413b9555bc9f326904814ecf6dc4f1ba1dc1267)
[Nicolas Kosinski](mailto:nicokosi@yahoo.com) | multiple pages: fix typos in French translation (#5841) | 2021-05-01T18:49:31 | [6467b39f66b4](https://github.com/tldr-pages/tldr/commit/6467b39f66b40110a64d13af20f1a7ab27380fa9)
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | French pages: fix (valid) tldr-lint errors (#5365) | 2021-03-07T16:42:12 | [6443e6a7254d](https://github.com/tldr-pages/tldr/commit/6443e6a7254dd0d9c350be2db0ee9ad7cab2d032)
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | multiple pages: fix French colon punctuation (#5152) | 2021-01-30T18:03:18 | [5f1ef5bee7db](https://github.com/tldr-pages/tldr/commit/5f1ef5bee7dba1b2749d25e4d0a7be22c89cf8b4)
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | multiple pages: normalize "more information" labels (#5140) | 2021-01-15T18:24:49 | [c59f12aa9f55](https://github.com/tldr-pages/tldr/commit/c59f12aa9f55d85612ba22e4da86db293ff76977)
[lucas schneider](mailto:casdpa@gmail.com) | rename git to Git | 2021-01-08T14:09:54 | [eef3712fc3a6](https://github.com/tldr-pages/tldr/commit/eef3712fc3a6a3774384b2e4ed934583c8349d75)
[CARE-COLIN Thibaut](mailto:carecolin@gmail.com) | git*: add French translation (#4619) | 2020-11-10T12:17:06 | [8c8314f72568](https://github.com/tldr-pages/tldr/commit/8c8314f7256871ec042395d6eef6d77827cda04c)

