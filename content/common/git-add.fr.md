---
author: ['William Belle', 'Nicolas Kosinski', 'Hugo Dupras', 'CARE-COLIN Thibaut', 'bl-ue', 'marchersimon']
date: 1633592259
title: "git add"
description: "git add, Ajoute les fichiers modifiés à l'index."
categories: "common"
---
> Plus d'informations : <https://git-scm.com/docs/git-add>.

- Ajouter un fichier à l'index :

```bash
git add chemin/vers/fichier
```

- Ajouter tous les fichiers (suivis et non-suivis) :

```bash
git add -A
```

- Ajoute les modifications des fichiers déjà suivis :

```bash
git add -u
```

- Ajoute aussi les fichiers ignorés :

```bash
git add -f
```

- Ajoute des parties de fichiers interactivement :

```bash
git add -p
```

- Ajoute interactivement les parties d'un fichier spécifié :

```bash
git add -p chemin/vers/fichier
```

- Ajouter un fichier interactivement :

```bash
git add -i
```
Liste des modifications apportées à cette documentation


Auteur | Description | Format de la date ISO 8601 | Lien vers GitHub
------|-----|-----|-----
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | Replace non-breaking space with regular space in French pages (#6842) | 2021-10-07T09:37:39 | [d63065b882e7](https://github.com/tldr-pages/tldr/commit/d63065b882e77c3d3361e76cfa7f28bf5415832e)
[Nicolas Kosinski](mailto:nicokosi@yahoo.com) | multiple pages: fix typos in French translation (#5841) | 2021-05-01T18:49:31 | [6467b39f66b4](https://github.com/tldr-pages/tldr/commit/6467b39f66b40110a64d13af20f1a7ab27380fa9)
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | French pages: fix (valid) tldr-lint errors (#5365) | 2021-03-07T16:42:12 | [6443e6a7254d](https://github.com/tldr-pages/tldr/commit/6443e6a7254dd0d9c350be2db0ee9ad7cab2d032)
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | multiple pages: fix French colon punctuation (#5152) | 2021-01-30T18:03:18 | [5f1ef5bee7db](https://github.com/tldr-pages/tldr/commit/5f1ef5bee7dba1b2749d25e4d0a7be22c89cf8b4)
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | multiple pages, MAINTAINERS: remove trailing whitespace at line ends (#5151) * multiple pages: remove trailing whitespace at the end [...] | 2021-01-16T16:33:31 | [96145696557f](https://github.com/tldr-pages/tldr/commit/96145696557f2ee2d55577cd8a617d5a1885d200)
[CARE-COLIN Thibaut](mailto:carecolin@gmail.com) | git*: add French translation (#4619) | 2020-11-10T12:17:06 | [8c8314f72568](https://github.com/tldr-pages/tldr/commit/8c8314f7256871ec042395d6eef6d77827cda04c)
[William Belle](mailto:william.belle@gmail.com) | git-add: fix typos (fr; #4249) | 2020-08-10T01:17:27 | [3af7acb6238d](https://github.com/tldr-pages/tldr/commit/3af7acb6238d2e4b06fe4adcdf45d7a6b329f038)
[Hugo Dupras](mailto:jabesq@gmail.com) | Add French translation for git basic commands (#3483) * git-add: Add French translation Signed-off-by: Hugo D. (jabesq) [...] | 2019-12-09T19:14:31 | [8ec0c33e4413](https://github.com/tldr-pages/tldr/commit/8ec0c33e4413536b49901e1f626bd2fec5d73a51)

