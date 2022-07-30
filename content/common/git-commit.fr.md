---
author: ['Tan A', 'Nicolas Kosinski', 'Hugo Dupras', 'CARE-COLIN Thibaut', 'bl-ue', 'marchersimon']
date: 1633592259
title: "git commit"
description: "git commit, Enregistrer (`commit`) les fichiers dans le dépôt."
categories: "common"
---
> Plus d'informations : <https://git-scm.com/docs/git-commit>.

- Commit les fichiers en stage dans le dépôt avec un message :

```bash
git commit -m "message"
```

- Commit tous les fichiers modifiés avec un message :

```bash
git commit -am "message"
```

- Met à jour le dernier commit avec les modifications en stage :

```bash
git commit --amend
```

- Commit seulement les fichiers spécifiés (qui sont déjà en stage) :

```bash
git commit chemin/vers/mon/fichier1 chemin/vers/mon/fichier2
```
Liste des modifications apportées à cette documentation


Auteur | Description | Format de la date ISO 8601 | Lien vers GitHub
------|-----|-----|-----
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | Replace non-breaking space with regular space in French pages (#6842) | 2021-10-07T09:37:39 | [d63065b882e7](https://github.com/tldr-pages/tldr/commit/d63065b882e77c3d3361e76cfa7f28bf5415832e)
[Nicolas Kosinski](mailto:nicokosi@yahoo.com) | multiple pages: fix typos in French translation (#5841) | 2021-05-01T18:49:31 | [6467b39f66b4](https://github.com/tldr-pages/tldr/commit/6467b39f66b40110a64d13af20f1a7ab27380fa9)
[Tan A](mailto:40173707+Yutyo@users.noreply.github.com) | git-commit: quote message argument (#5477) | 2021-03-19T13:26:51 | [d526739418e8](https://github.com/tldr-pages/tldr/commit/d526739418e89eba9a32b3b6acfe406abb9bdb50)
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | multiple pages: fix French colon punctuation (#5152) | 2021-01-30T18:03:18 | [5f1ef5bee7db](https://github.com/tldr-pages/tldr/commit/5f1ef5bee7dba1b2749d25e4d0a7be22c89cf8b4)
[CARE-COLIN Thibaut](mailto:carecolin@gmail.com) | git*: add French translation (#4619) | 2020-11-10T12:17:06 | [8c8314f72568](https://github.com/tldr-pages/tldr/commit/8c8314f7256871ec042395d6eef6d77827cda04c)
[Hugo Dupras](mailto:jabesq@gmail.com) | Add French translation for git basic commands (#3483) * git-add: Add French translation Signed-off-by: Hugo D. (jabesq) [...] | 2019-12-09T19:14:31 | [8ec0c33e4413](https://github.com/tldr-pages/tldr/commit/8ec0c33e4413536b49901e1f626bd2fec5d73a51)

