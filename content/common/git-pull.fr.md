---
author: ['Hugo Dupras', 'bl-ue', 'marchersimon', 'CARE-COLIN Thibaut']
date: 1633592259
title: "git pull, TLDR Pages"
description: "git pull, Récupère une branche depuis le serveur distant et la fusionne dans la branche local."
categories: "common"
---
> Plus d'informations : <https://git-scm.com/docs/git-pull>.

- Télécharge les changements depuis le serveur distant par défaut et fusionne les :

```bash
git pull
```

- Télécharge les changements depuis le serveur distant par défaut et applique les changements locaux par dessus :

```bash
git pull --rebase
```

- Télécharge les changements depuis un serveur et une branche distante, puis fusionne les dans HEAD :

```bash
git pull nom_distant branche
```
Liste des modifications apportées à cette documentation


Auteur | Description | Format de la date ISO 8601 | Lien vers GitHub
------|-----|-----|-----
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | Replace non-breaking space with regular space in French pages (#6842) | 2021-10-07T09:37:39 | [d63065b882e7](https://github.com/tldr-pages/tldr/commit/d63065b882e77c3d3361e76cfa7f28bf5415832e)
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | multiple pages: fix French colon punctuation (#5152) | 2021-01-30T18:03:18 | [5f1ef5bee7db](https://github.com/tldr-pages/tldr/commit/5f1ef5bee7dba1b2749d25e4d0a7be22c89cf8b4)
[CARE-COLIN Thibaut](mailto:carecolin@gmail.com) | git*: add French translation (#4619) | 2020-11-10T12:17:06 | [8c8314f72568](https://github.com/tldr-pages/tldr/commit/8c8314f7256871ec042395d6eef6d77827cda04c)
[Hugo Dupras](mailto:jabesq@gmail.com) | Add French translation for git basic commands (#3483) * git-add: Add French translation Signed-off-by: Hugo D. (jabesq) [...] | 2019-12-09T19:14:31 | [8ec0c33e4413](https://github.com/tldr-pages/tldr/commit/8ec0c33e4413536b49901e1f626bd2fec5d73a51)

