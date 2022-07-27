---
author: ['Patrice Denis', 'CARE-COLIN Thibaut', 'Nicolas Kosinski', 'bl-ue', 'marchersimon']
date: 1633592259
title: "git diff, TLDR Pages"
description: "git diff, Afficher les changements sur les fichiers suivis."
categories: "common"
---
> Plus d'informations : <https://git-scm.com/docs/git-diff>.

- Afficher les changements sur les fichiers suivis :

```bash
git diff
```

- Afficher tous les changements sur les fichiers par rapport à la tête de branche :

```bash
git diff HEAD
```

- Afficher tous les changements sur les fichiers ajoutés mais pas encore commités :

```bash
git diff --staged
```

- Afficher les changements de tous les commits à partir d'une date / heure donnée (expression de dates, ex : "1 week 2 days" pour 1 semaine et 2 jours ou une date ISO) :

```bash
git diff 'HEAD@{3 months|weeks|days|hours|seconds ago}'
```

- Afficher seulement les noms des fichiers modifiés depuis un commit donné :

```bash
git diff --name-only commit
```

- Afficher un résumé des créations de fichiers, renommages ou changements de droits depuis un commit :

```bash
git diff --summary commit
```

- Comparer un fichier entre deux branches ou commits :

```bash
git diff branche_1..branche_2 [--] chemin/vers/fichier
```

- Comparer plusieurs fichiers de la branche courante avec une autre branche :

```bash
git diff branche:chemin/vers/fichier2 chemin/vers/fichier
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

