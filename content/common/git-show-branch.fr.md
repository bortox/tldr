---
author: ['Nicolas Kosinski', 'bl-ue', 'marchersimon', 'CARE-COLIN Thibaut']
date: 1633592259
title: "git show-branch, TLDR Pages"
description: "git show-branch, Affiche les branches et leurs commits."
categories: "common"
---
> Plus d'informations : <https://git-scm.com/docs/git-show-branch>.

- Affiche un résumé du dernier commit dans la branche :

```bash
git show-branch nom_de_branche|ref|commit
```

- Comparer des commits avec plusieurs commits ou branches :

```bash
git show-branch nom_de_branche|ref|commit
```

- Comparer toutes les branches distantes :

```bash
git show-branch --remotes
```

- Comparer la branche locale avec la branche distante :

```bash
git show-branch --all
```

- Lister les derniers commits sur toutes les branches :

```bash
git show-branch --all --list
```

- Comparer une branche spécifique à la branche courante :

```bash
git show-branch --current commit|branch_name|ref
```

- Afficher le nom du commit au lieu du nom relatif :

```bash
git show-branch --sha1-name --current current|branch_name|ref
```

- Continuez l'affichage d'un certain nombre de commits au-delà de l'ancêtre commun :

```bash
git show-branch --more 5 commit|branch_name|ref commit|branch_name|ref ...
```
Liste des modifications apportées à cette documentation


Auteur | Description | Format de la date ISO 8601 | Lien vers GitHub
------|-----|-----|-----
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | Replace non-breaking space with regular space in French pages (#6842) | 2021-10-07T09:37:39 | [d63065b882e7](https://github.com/tldr-pages/tldr/commit/d63065b882e77c3d3361e76cfa7f28bf5415832e)
[Nicolas Kosinski](mailto:nicokosi@yahoo.com) | multiple pages: fix typos in French translation (#5841) | 2021-05-01T18:49:31 | [6467b39f66b4](https://github.com/tldr-pages/tldr/commit/6467b39f66b40110a64d13af20f1a7ab27380fa9)
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | multiple pages: fix French colon punctuation (#5152) | 2021-01-30T18:03:18 | [5f1ef5bee7db](https://github.com/tldr-pages/tldr/commit/5f1ef5bee7dba1b2749d25e4d0a7be22c89cf8b4)
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | multiple pages: normalize "more information" labels (#5140) | 2021-01-15T18:24:49 | [c59f12aa9f55](https://github.com/tldr-pages/tldr/commit/c59f12aa9f55d85612ba22e4da86db293ff76977)
[CARE-COLIN Thibaut](mailto:carecolin@gmail.com) | git*: add French translation (#4619) | 2020-11-10T12:17:06 | [8c8314f72568](https://github.com/tldr-pages/tldr/commit/8c8314f7256871ec042395d6eef6d77827cda04c)

