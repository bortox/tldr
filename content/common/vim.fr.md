---
author: ['Nicolas Kosinski', 'CARE-COLIN Thibaut', 'marchersimon', 'bl-ue', 'Patrice Denis', 'lincc']
date: 1633592259
title: "vim"
description: "vim, Vim (Vi IMproved), un éditeur de texte en ligne de commandes, fournit plusieurs modes pour différentes manipulations de texte."
categories: "common"
---
> Pressez `i` pour passer en mode édition. `<Esc>` revient au mode normal, qui ne permet pas l insertion de code.

> Plus d'informations : <https://www.vim.org>.

- Ouvrir un fichier :

```bash
vim chemin/vers/fichier
```

- Ouvrir un fichier à une ligne spécifiée :

```bash
vim +numero_ligne chemin/vers/fichier
```

- consulter le manuel utilisateur :

```bash
:help<Entrée>
```

- Sauvegarder et fermer :

```bash
:wq<Entrée>
```

- Annuler la dernière opération :

```bash
u
```

- Rechercher un motif dans un fichier (appuyez `n`/`N` pour aller à la prochaine / précédente occurrence) :

```bash
/motif_recherché<Entrée>
```

- Effectuer une substitution par expression régulière dans tout le fichier :

```bash
:%s/motif/remplacement/g<Entrée>
```

- Afficher les numéros de ligne :

```bash
:set nu<Entrée>
```
Liste des modifications apportées à cette documentation


Auteur | Description | Format de la date ISO 8601 | Lien vers GitHub
------|-----|-----|-----
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | Replace non-breaking space with regular space in French pages (#6842) | 2021-10-07T09:37:39 | [d63065b882e7](https://github.com/tldr-pages/tldr/commit/d63065b882e77c3d3361e76cfa7f28bf5415832e)
[lincc](mailto:46962923+blueskyson@users.noreply.github.com) | vim: refresh (#6375) | 2021-08-17T20:11:25 | [4ba58f514ad8](https://github.com/tldr-pages/tldr/commit/4ba58f514ad8d22c477708ccc673453bf583a0cb)
[Patrice Denis](mailto:patricedenis@users.noreply.github.com) | multiple pages: fix typos in French translation (#5909) | 2021-06-23T02:34:03 | [a413b9555bc9](https://github.com/tldr-pages/tldr/commit/a413b9555bc9f326904814ecf6dc4f1ba1dc1267)
[Nicolas Kosinski](mailto:nicokosi@yahoo.com) | multiple pages: fix typos in French translation (#5841) | 2021-05-01T18:49:31 | [6467b39f66b4](https://github.com/tldr-pages/tldr/commit/6467b39f66b40110a64d13af20f1a7ab27380fa9)
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | multiple pages: fix French colon punctuation (#5152) | 2021-01-30T18:03:18 | [5f1ef5bee7db](https://github.com/tldr-pages/tldr/commit/5f1ef5bee7dba1b2749d25e4d0a7be22c89cf8b4)
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | multiple pages: normalize "more information" labels (#5140) | 2021-01-15T18:24:49 | [c59f12aa9f55](https://github.com/tldr-pages/tldr/commit/c59f12aa9f55d85612ba22e4da86db293ff76977)
[CARE-COLIN Thibaut](mailto:carecolin@gmail.com) | vim: add line numbers example (#4608) | 2020-10-31T21:42:18 | [591c38427555](https://github.com/tldr-pages/tldr/commit/591c38427555e8ff0ee9e05f0a2b04fc3ca47d3f)

