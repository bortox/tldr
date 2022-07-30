---
author: ['Nicolas Kosinski', 'CARE-COLIN Thibaut', 'bl-ue', 'Patrice Denis', 'marchersimon']
date: 1633592259
title: "git stage"
description: "git stage, Ajouter le contenu du fichier à la zone de préparation."
categories: "common"
---
> Synonyme de `git add`.

> Plus d'informations : <https://git-scm.com/docs/git-stage>.

- Ajouter un fichier à l'index :

```bash
git stage chemin/vers/fichier
```

- Ajoute tous les fichiers à l'index (suivis et non-suivis) :

```bash
git stage -A
```

- Ajout uniquement des fichiers déjà suivis :

```bash
git stage -u
```

- Ajout également des fichiers ignorés :

```bash
git stage -f
```

- Ajout des fichiers par parties, interactivement :

```bash
git stage -p
```

- Ajout d'un fichier par parties, interactivement :

```bash
git stage -p chemin/vers/fichier
```

- Ajout d'un fichier, interactivement :

```bash
git stage -i
```
Liste des modifications apportées à cette documentation


Auteur | Description | Format de la date ISO 8601 | Lien vers GitHub
------|-----|-----|-----
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | Replace non-breaking space with regular space in French pages (#6842) | 2021-10-07T09:37:39 | [d63065b882e7](https://github.com/tldr-pages/tldr/commit/d63065b882e77c3d3361e76cfa7f28bf5415832e)
[Patrice Denis](mailto:patricedenis@users.noreply.github.com) | multiple pages: fix typos in French translation (#5909) | 2021-06-23T02:34:03 | [a413b9555bc9](https://github.com/tldr-pages/tldr/commit/a413b9555bc9f326904814ecf6dc4f1ba1dc1267)
[Nicolas Kosinski](mailto:nicokosi@yahoo.com) | multiple pages: fix typos in French translation (#5841) | 2021-05-01T18:49:31 | [6467b39f66b4](https://github.com/tldr-pages/tldr/commit/6467b39f66b40110a64d13af20f1a7ab27380fa9)
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | multiple pages: fix French colon punctuation (#5152) | 2021-01-30T18:03:18 | [5f1ef5bee7db](https://github.com/tldr-pages/tldr/commit/5f1ef5bee7dba1b2749d25e4d0a7be22c89cf8b4)
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | multiple pages: normalize "more information" labels (#5140) | 2021-01-15T18:24:49 | [c59f12aa9f55](https://github.com/tldr-pages/tldr/commit/c59f12aa9f55d85612ba22e4da86db293ff76977)
[CARE-COLIN Thibaut](mailto:carecolin@gmail.com) | git*: add French translation (#4619) | 2020-11-10T12:17:06 | [8c8314f72568](https://github.com/tldr-pages/tldr/commit/8c8314f7256871ec042395d6eef6d77827cda04c)

