---
author: ['Nicolas Kosinski', 'CARE-COLIN Thibaut', 'bl-ue', 'Patrice Denis', 'marchersimon']
date: 1633592259
title: "git checkout"
description: "git checkout, Extraire une branche ou des chemins vers l'arborescence de travail."
categories: "common"
---
> Plus d'informations : <https://git-scm.com/docs/git-checkout>.

- Créer une branche et basculer dessus :

```bash
git checkout -b nom_de_branche
```

- Créer une branche depuis une référence spécifique et basculer dessus (par exemple, branche locale/distante, tag, commit) :

```bash
git checkout -b nom_de_branche référence
```

- Basculer sur une branche locale existante :

```bash
git checkout nom_de_branche
```

- Basculer sur la branche précédente :

```bash
git checkout -
```

- Basculer sur une branche distante existante :

```bash
git checkout --track nom_distant/nom_de_branche
```

- Annule tout les changements dans le répertoire courant (voir `git reset` pour plus de commandes d'annulation) :

```bash
git checkout .
```

- Annule tout les changements dans le fichier spécifié :

```bash
git checkout filename
```

- Remplace un fichier par sa version d'une autre branche :

```bash
git checkout nom_de_branche -- filename
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

