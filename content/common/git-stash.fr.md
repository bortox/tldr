---
author: ['Simon Landry', 'Patrice Denis', 'CARE-COLIN Thibaut', 'Nicolas Kosinski', 'bl-ue', 'marchersimon']
date: 1633592259
title: "git stash, TLDR Pages"
description: "git stash, Stocker les modifications Git locales dans une zone temporaire."
categories: "common"
---
> Plus d'informations : <https://git-scm.com/docs/git-stash>.

- Stocker les changements courants, sauf les fichiers non-suivis :

```bash
git stash [push -m nom_de_stash_optionel]
```

- Stocker les changements courants, incluant les fichiers non-suivis :

```bash
git stash -u
```

- Stocker les parties d'un fichier interactivement :

```bash
git stash -p
```

- Lister tous les stashs (affiche leurs noms, les branches relatives et messages) :

```bash
git stash list
```

- Applique un stash (par défaut, le dernier, nommé stash@{0}) :

```bash
git stash apply nom_de_stash_ou_de_commit_optionel
```

- Applique un stash (par défaut le dernier, stash@{0}), et le supprimer de la liste des stashs s'il n'y a pas de conflit :

```bash
git stash pop nom_de_stash_optionel
```

- Supprime un stash (par défaut le dernier, stash@{0}) :

```bash
git stash drop nom_de_stash_optionel
```

- Supprime tous les stashs :

```bash
git stash clear
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
[Simon Landry](mailto:landry_simon@pm.me) | git-stash: add French translation (#4623) | 2020-10-13T13:11:01 | [06f9747675f6](https://github.com/tldr-pages/tldr/commit/06f9747675f6b178e9589aaf9a812be30bcffa3a)

