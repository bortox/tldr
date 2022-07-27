---
author: ['Nicolas Hansse', 'Patrice Denis', 'William Belle', 'Dario Vladović', 'Matthias Lübken', 'Lucas Gabriel Schneider', 'bl-ue', 'marchersimon', 'julien']
date: 1633592259
title: "base64, TLDR Pages"
description: "base64, Encoder ou décoder un fichier ou l'entrée standard en utilisant le codage Base64 à destination de la sortie standard."
categories: "common"
---
> Plus d'informations : <https://www.gnu.org/software/coreutils/base64>.

- Encode un fichier :

```bash
base64 fichier
```

- Décode un fichier :

```bash
base64 --decode fichier
```

- Encode depuis stdin :

```bash
une_commande | base64
```

- Décode depuis stdin :

```bash
une_commande | base64 --decode
```
Liste des modifications apportées à cette documentation


Auteur | Description | Format de la date ISO 8601 | Lien vers GitHub
------|-----|-----|-----
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | Replace non-breaking space with regular space in French pages (#6842) | 2021-10-07T09:37:39 | [d63065b882e7](https://github.com/tldr-pages/tldr/commit/d63065b882e77c3d3361e76cfa7f28bf5415832e)
[Nicolas Hansse](mailto:nico.hansse@gmail.com) | base64: fix French translation (#6706) | 2021-10-03T14:59:14 | [19fcd3892806](https://github.com/tldr-pages/tldr/commit/19fcd3892806adfe13b59108527f27a64f8d1a4b)
[Patrice Denis](mailto:patricedenis@users.noreply.github.com) | multiple pages: fix typos in French translation (#5909) | 2021-06-23T02:34:03 | [a413b9555bc9](https://github.com/tldr-pages/tldr/commit/a413b9555bc9f326904814ecf6dc4f1ba1dc1267)
[Dario Vladović](mailto:d.vladimyr@gmail.com) | coreutils*: use short more info links (#5658) | 2021-04-01T17:54:26 | [4830093903f6](https://github.com/tldr-pages/tldr/commit/4830093903f66ccf3ebbc2ecf477286e45edac59)
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | base64: add link (#5572) | 2021-03-30T09:06:32 | [59583f4c3ef2](https://github.com/tldr-pages/tldr/commit/59583f4c3ef21258f554c49dc14001e27e3bd4e1)
[Matthias Lübken](mailto:matthias.luebken@gmail.com) | base32, base64: fix -D flag (#5234) | 2021-03-07T23:58:11 | [00e00396a42a](https://github.com/tldr-pages/tldr/commit/00e00396a42a8b5fcc189909a1aae3173e513f72)
[Lucas Gabriel Schneider](mailto:casdpa@gmail.com) | multiple pages: format technical tokens (#5119) Co-authored-by: bl-ue <54780737+bl-ue@users.noreply.github.com> Co-authored-by: [...] | 2021-01-31T18:05:18 | [a5fe31bc47ae](https://github.com/tldr-pages/tldr/commit/a5fe31bc47aece3efa5e66b52b3cf384f27d5d72)
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | multiple pages: fix French colon punctuation (#5152) | 2021-01-30T18:03:18 | [5f1ef5bee7db](https://github.com/tldr-pages/tldr/commit/5f1ef5bee7dba1b2749d25e4d0a7be22c89cf8b4)
[William Belle](mailto:william.belle@gmail.com) | base64: fix missing French translation (#3968) | 2020-04-10T13:59:10 | [357ba26eda5e](https://github.com/tldr-pages/tldr/commit/357ba26eda5e35aec3c522cc96d0fc7a19f5ba53)
[julien](mailto:git@julienc.io) | base64: add French translation | 2019-10-27T17:33:39 | [ab4cf0c8bef9](https://github.com/tldr-pages/tldr/commit/ab4cf0c8bef9d352c12cbc5a170eb067d319f47e)

