---
author: ['bl-ue', 'CARE-COLIN Thibaut', 'Hugo Dupras', 'William Belle', 'marchersimon']
date: 1633592259
title: "git push, TLDR Pages"
description: "git push, Pousse les commits vers un dépôt distant."
categories: "common"
---
> Plus d'informations : <https://git-scm.com/docs/git-push>.

- Envoie les changements locaux dans la branche courante vers sa contrepartie distante :

```bash
git push
```

- Envoie les changements locaux d'une branche spécifique vers sa contrepartie distante :

```bash
git push nom_distant local_branch
```

- Publie la branche courante vers un dépôt distant, crée le nom de la branche distante :

```bash
git push nom_distant -u branche_distante
```

- Envoi les changements locaux sur toutes les branches locales vers leur contrepartie sur le dépôt distant :

```bash
git push --all nom_distant
```

- Supprime une branche dans un dépôt distant :

```bash
git push nom_distant --delete branche_distante
```

- Supprime les branches distantes qui n'ont pas de contrepartie locale :

```bash
git push --prune nom_distant
```

- Publie les tags qui ne sont pas sur le dépôt distant :

```bash
git push --tags
```
Liste des modifications apportées à cette documentation


Auteur | Description | Format de la date ISO 8601 | Lien vers GitHub
------|-----|-----|-----
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | Replace non-breaking space with regular space in French pages (#6842) | 2021-10-07T09:37:39 | [d63065b882e7](https://github.com/tldr-pages/tldr/commit/d63065b882e77c3d3361e76cfa7f28bf5415832e)
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | multiple pages: fix French colon punctuation (#5152) | 2021-01-30T18:03:18 | [5f1ef5bee7db](https://github.com/tldr-pages/tldr/commit/5f1ef5bee7dba1b2749d25e4d0a7be22c89cf8b4)
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | multiple pages: normalize "more information" labels (#5140) | 2021-01-15T18:24:49 | [c59f12aa9f55](https://github.com/tldr-pages/tldr/commit/c59f12aa9f55d85612ba22e4da86db293ff76977)
[CARE-COLIN Thibaut](mailto:carecolin@gmail.com) | git*: add French translation (#4619) | 2020-11-10T12:17:06 | [8c8314f72568](https://github.com/tldr-pages/tldr/commit/8c8314f7256871ec042395d6eef6d77827cda04c)
[William Belle](mailto:william.belle@gmail.com) | git-push: fix typo (#4112) | 2020-06-18T22:39:16 | [afa6de831f32](https://github.com/tldr-pages/tldr/commit/afa6de831f32bcab5974f6c5617b9bcf02d81f38)
[Hugo Dupras](mailto:jabesq@gmail.com) | Add French translation for git basic commands (#3483) * git-add: Add French translation Signed-off-by: Hugo D. (jabesq) [...] | 2019-12-09T19:14:31 | [8ec0c33e4413](https://github.com/tldr-pages/tldr/commit/8ec0c33e4413536b49901e1f626bd2fec5d73a51)

