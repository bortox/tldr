---
author: ['Dario Vladović', 'Ivor Benderavage', 'Matthias Lübken', 'Lucas Gabriel Schneider', 'Ivor', 'bl-ue', 'Patrice Denis', 'marchersimon']
date: 1633592259
title: "base32"
description: "base32, Encode ou décode un fichier ou l'entrée standard vers ou depuis la base 32, et retourne le résultat à la sortie standard."
categories: "common"
---
> Plus d'informations : <https://www.gnu.org/software/coreutils/base32>.

- Encode un fichier :

```bash
base32 fichier
```

- Décode un fichier :

```bash
base32 --decode fichier
```

- Encode depuis stdin :

```bash
commande | base32
```

- Décode depuis stdin :

```bash
commande | base32 --decode
```
Liste des modifications apportées à cette documentation


Auteur | Description | Format de la date ISO 8601 | Lien vers GitHub
------|-----|-----|-----
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | Replace non-breaking space with regular space in French pages (#6842) | 2021-10-07T09:37:39 | [d63065b882e7](https://github.com/tldr-pages/tldr/commit/d63065b882e77c3d3361e76cfa7f28bf5415832e)
[Patrice Denis](mailto:patricedenis@users.noreply.github.com) | multiple pages: fix typos in French translation (#5909) | 2021-06-23T02:34:03 | [a413b9555bc9](https://github.com/tldr-pages/tldr/commit/a413b9555bc9f326904814ecf6dc4f1ba1dc1267)
[Dario Vladović](mailto:d.vladimyr@gmail.com) | coreutils*: use short more info links (#5658) | 2021-04-01T17:54:26 | [4830093903f6](https://github.com/tldr-pages/tldr/commit/4830093903f66ccf3ebbc2ecf477286e45edac59)
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | base32: add link (#5571) | 2021-03-30T09:11:31 | [30331c3d152d](https://github.com/tldr-pages/tldr/commit/30331c3d152d78ba495f78b7759f04b7bcd46f9f)
[Matthias Lübken](mailto:matthias.luebken@gmail.com) | base32, base64: fix -D flag (#5234) | 2021-03-07T23:58:11 | [00e00396a42a](https://github.com/tldr-pages/tldr/commit/00e00396a42a8b5fcc189909a1aae3173e513f72)
[Lucas Gabriel Schneider](mailto:casdpa@gmail.com) | multiple pages: format technical tokens (#5119) Co-authored-by: bl-ue <54780737+bl-ue@users.noreply.github.com> Co-authored-by: [...] | 2021-01-31T18:05:18 | [a5fe31bc47ae](https://github.com/tldr-pages/tldr/commit/a5fe31bc47aece3efa5e66b52b3cf384f27d5d72)
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | multiple pages: fix French colon punctuation (#5152) | 2021-01-30T18:03:18 | [5f1ef5bee7db](https://github.com/tldr-pages/tldr/commit/5f1ef5bee7dba1b2749d25e4d0a7be22c89cf8b4)
[Ivor Benderavage](mailto:ivor.benderavage@gmail.com) | base32: French translation formatting | 2020-12-30T14:23:22 | [645207b69571](https://github.com/tldr-pages/tldr/commit/645207b695714ad5abfe2502c1be3e9fb6ea9e43)
[Ivor](mailto:ivor.benderavage@gmail.com) | base32: add French translation | 2020-12-30T14:23:22 | [9ceab1cb0cc8](https://github.com/tldr-pages/tldr/commit/9ceab1cb0cc8cb3eca39c6147aa79651cd89ed5c)

