---
author: ['Jennifer', 'Dario Vladović', 'Matthias Lübken', 'Lucas Gabriel Schneider', 'marchersimon']
date: 1617292466
title: "base64, TLDR Pages"
description: "base64, Codeer of decodeer bestand of standaardinvoer van/naar Base64 naar standaarduitvoer."
categories: "common"
---
> Meer informatie: <https://www.gnu.org/software/coreutils/base64>.

- Codeer een bestand:

```bash
base64 bestandsnaam
```

- Decodeer een bestand:

```bash
base64 --decode bestandsnaam
```

- Codeer stdin:

```bash
eencommando | base64
```

- Decodeer stdin:

```bash
eencommando | base64 --decode
```
Lijst van wijzigingen die in deze documentatie zijn aangebracht


Auteur | Beschrijving | ISO 8601 datum formaat | Link naar GitHub
------|-----|-----|-----
[Dario Vladović](mailto:d.vladimyr@gmail.com) | coreutils*: use short more info links (#5658) | 2021-04-01T17:54:26 | [4830093903f6](https://github.com/tldr-pages/tldr/commit/4830093903f66ccf3ebbc2ecf477286e45edac59)
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | base64: add link (#5572) | 2021-03-30T09:06:32 | [59583f4c3ef2](https://github.com/tldr-pages/tldr/commit/59583f4c3ef21258f554c49dc14001e27e3bd4e1)
[Matthias Lübken](mailto:matthias.luebken@gmail.com) | base32, base64: fix -D flag (#5234) | 2021-03-07T23:58:11 | [00e00396a42a](https://github.com/tldr-pages/tldr/commit/00e00396a42a8b5fcc189909a1aae3173e513f72)
[Lucas Gabriel Schneider](mailto:casdpa@gmail.com) | multiple pages: format technical tokens (#5119) Co-authored-by: bl-ue <54780737+bl-ue@users.noreply.github.com> Co-authored-by: [...] | 2021-01-31T18:05:18 | [a5fe31bc47ae](https://github.com/tldr-pages/tldr/commit/a5fe31bc47aece3efa5e66b52b3cf384f27d5d72)
[Jennifer](mailto:42771751+JenniX3@users.noreply.github.com) | base64: add Dutch translation (#4610) | 2020-10-13T00:09:40 | [0a679a6b151e](https://github.com/tldr-pages/tldr/commit/0a679a6b151e6d2de5581693d81e4a7a9580ed6e)

