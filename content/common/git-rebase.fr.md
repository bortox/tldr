---
author: ['Nicolas Kosinski', 'bl-ue', 'marchersimon', 'CARE-COLIN Thibaut']
date: 1633592259
title: "git rebase, TLDR Pages"
description: "git rebase, Rejoue les commits d'une branche par dessus une autre."
categories: "common"
---
> Communément utilisé pour dupliquer les commits d'une branche dans une autre, en créant de nouveaux commits dans la branche de destination.

> Plus d'informations : <https://git-scm.com/docs/git-rebase>.

- Rejouer les commits de la branche courante sur la branche master :

```bash
git rebase master
```

- Rejouer les comits interactivement, ce qui permet aux commits d'être re-arrangés, exclus, combinés ou modifiés :

```bash
git rebase -i branche_de_base_ou_commit
```

- Continuer le re-jeu des commits après la résolution d'un conflit :

```bash
git rebase --continue
```

- Continuer le re-jeu des commits en sautant la résolution d'un conflit :

```bash
git rebase --skip
```

- Annule l'opération (ex : en cas de conflit) :

```bash
git rebase --abort
```

- Déplacez une partie de la branche actuelle sur une nouvelle base, fournissant l'ancienne base à partir de laquelle commencer :

```bash
git rebase --onto new_base old_base
```

- Rejoue les 5 derniers commits, ce qui permet aux commits d'être re-arrangés, exclus, combinés ou modifiés :

```bash
git rebase -i HEAD~5
```

- Résoudre automatiquement les conflits en précisant la version à conserver (`theirs` signifie la version des fichiers à privilégier) :

```bash
git rebase -X theirs master
```
Liste des modifications apportées à cette documentation


Auteur | Description | Format de la date ISO 8601 | Lien vers GitHub
------|-----|-----|-----
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | Replace non-breaking space with regular space in French pages (#6842) | 2021-10-07T09:37:39 | [d63065b882e7](https://github.com/tldr-pages/tldr/commit/d63065b882e77c3d3361e76cfa7f28bf5415832e)
[Nicolas Kosinski](mailto:nicokosi@yahoo.com) | multiple pages: fix typos in French translation (#5841) | 2021-05-01T18:49:31 | [6467b39f66b4](https://github.com/tldr-pages/tldr/commit/6467b39f66b40110a64d13af20f1a7ab27380fa9)
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | multiple pages: fix French colon punctuation (#5152) | 2021-01-30T18:03:18 | [5f1ef5bee7db](https://github.com/tldr-pages/tldr/commit/5f1ef5bee7dba1b2749d25e4d0a7be22c89cf8b4)
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | multiple pages: normalize "more information" labels (#5140) | 2021-01-15T18:24:49 | [c59f12aa9f55](https://github.com/tldr-pages/tldr/commit/c59f12aa9f55d85612ba22e4da86db293ff76977)
[CARE-COLIN Thibaut](mailto:carecolin@gmail.com) | git*: add French translation (#4619) | 2020-11-10T12:17:06 | [8c8314f72568](https://github.com/tldr-pages/tldr/commit/8c8314f7256871ec042395d6eef6d77827cda04c)

