---
author: ['Dario Vladović', 'David Bariod', 'Marco Bonelli', 'xBLACKICEx', 'julien', 'bl-ue', "Kevin O'Neal", 'marchersimon']
date: 1633928232
title: "wc"
description: "wc, Compte les lignes, les mots ou les octets."
categories: "common"
---
> Plus d'informations : <https://www.gnu.org/software/coreutils/wc>.

- Compte les lignes d'un fichier :

```bash
wc -l file
```

- Compte les mots d'un fichier :

```bash
wc -w file
```

- Compte les caractères (octets) d'un fichier :

```bash
wc -c file
```

- Compte les caractères d'un fichier (en prenant en compte l'ensemble des caractères multi-octets) :

```bash
wc -m file
```

- Utilisez l'entrée standard pour compter les lignes, les mots et les caractères (octets) dans cet ordre :

```bash
find . | wc
```
Liste des modifications apportées à cette documentation


Auteur | Description | Format de la date ISO 8601 | Lien vers GitHub
------|-----|-----|-----
[xBLACKICEx](mailto:xBLACKICEx@outlook.com) | wc: update pages.fr (translate) (#6951) | 2021-10-11T06:57:12 | [33c48b812cdd](https://github.com/tldr-pages/tldr/commit/33c48b812cdd861868c419ab30adb28e5d7fb5d1)
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | Replace non-breaking space with regular space in French pages (#6842) | 2021-10-07T09:37:39 | [d63065b882e7](https://github.com/tldr-pages/tldr/commit/d63065b882e77c3d3361e76cfa7f28bf5415832e)
[Dario Vladović](mailto:d.vladimyr@gmail.com) | coreutils*: use short more info links (#5658) | 2021-04-01T17:54:26 | [4830093903f6](https://github.com/tldr-pages/tldr/commit/4830093903f66ccf3ebbc2ecf477286e45edac59)
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | wc: add more information link (#5600) | 2021-03-30T15:48:08 | [4420ed005ff8](https://github.com/tldr-pages/tldr/commit/4420ed005ff8735eaf1b8932618d0c5ff2caec0e)
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | multiple pages: fix French colon punctuation (#5152) | 2021-01-30T18:03:18 | [5f1ef5bee7db](https://github.com/tldr-pages/tldr/commit/5f1ef5bee7dba1b2749d25e4d0a7be22c89cf8b4)
[Kevin O'Neal](mailto:oneal.kevin@gmail.com) | wc: order count types (#3565) | 2019-11-14T17:58:45 | [5db10fff8851](https://github.com/tldr-pages/tldr/commit/5db10fff88518f6f3b612fc85b0c669b064c9378)
[Marco Bonelli](mailto:mebeim@users.noreply.github.com) | wc (fr): remove additional trailing whitespace (#3493) | 2019-10-29T15:10:06 | [24d67a423953](https://github.com/tldr-pages/tldr/commit/24d67a4239533be28b2b7ee0177caac2b167f78a)
[julien](mailto:git@julienc.io) | wc: fix French punctuation and typos | 2019-10-26T17:59:51 | [b7074381625b](https://github.com/tldr-pages/tldr/commit/b7074381625bdf97a3ff627ccdd6811488107878)
[David Bariod](mailto:davidriod@googlemail.com) | wc: add French translation (#3156) | 2019-07-03T18:45:37 | [78157e5cfe39](https://github.com/tldr-pages/tldr/commit/78157e5cfe395a1439958448b5b009ce2a4a5d5a)

