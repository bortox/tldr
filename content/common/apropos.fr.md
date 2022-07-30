---
author: ['bl-ue', 'François Magimel', 'marchersimon']
date: 1633592259
title: "apropos"
description: "apropos, Recherche dans les pages de manuel, par exemple pour trouver une nouvelle commande."
categories: "common"
---
> Plus d'informations : <https://manned.org/apropos>.

- Recherche par mot clé :

```bash
apropos expression_reguliere
```

- Recherche sans limiter la sortie à la largeur du terminal :

```bash
apropos -l expression_reguliere
```

- Recherche les pages qui contiennent toutes les expressions données (fonction ET) :

```bash
apropos expression_reguliere_1 -a expression_reguliere_2 -a expression_reguliere_3
```
Liste des modifications apportées à cette documentation


Auteur | Description | Format de la date ISO 8601 | Lien vers GitHub
------|-----|-----|-----
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | Replace non-breaking space with regular space in French pages (#6842) | 2021-10-07T09:37:39 | [d63065b882e7](https://github.com/tldr-pages/tldr/commit/d63065b882e77c3d3361e76cfa7f28bf5415832e)
[marchersimon](mailto:marchersimon@zohomail.eu) | replace `man.archlinux.org` with `manned.org` | 2021-04-18T16:33:27 | [9abb079afb69](https://github.com/tldr-pages/tldr/commit/9abb079afb6972f3de61a30e1b3fb849ad4b68d9)
[marchersimon](mailto:marchersimon@zohomail.eu) | apropos: add link | 2021-04-18T16:33:27 | [be27e77a15b5](https://github.com/tldr-pages/tldr/commit/be27e77a15b529484e2896262d2bc563a3585f21)
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | multiple pages: ensure exactly one colon at the end of example descriptions (#5214) | 2021-02-03T17:22:44 | [d28035c980bd](https://github.com/tldr-pages/tldr/commit/d28035c980bde01b9168e76442fe564dc82ae5b7)
[François Magimel](mailto:magimel.francois@gmail.com) | apropos: add French translation (#4442) | 2020-10-05T16:51:13 | [c716cbd6c5da](https://github.com/tldr-pages/tldr/commit/c716cbd6c5dadf96506637b1d1a689f0a6d1fa84)

