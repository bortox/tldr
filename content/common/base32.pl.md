---
author: ['Dario Vladović', 'Matthias Lübken', 'Lucas Gabriel Schneider', 'Michal', 'marchersimon']
date: 1617292466
title: "base32"
description: "base32, Enkoduj lub dekoduj plik lub standardowe wejście do/z Base32, na standardowe wyjście."
categories: "common"
---
> Więcej informacji: <https://www.gnu.org/software/coreutils/base32>.

- Enkoduj plik:

```bash
base32 nazwapliku
```

- Dekoduj plik:

```bash
base32 --decode nazwapliku
```

- Enkoduj z stdin:

```bash
jakiespolecenie | base32
```

- Dekoduj z stdin:

```bash
jakiespolecenie | base32 --decode
```
Wykaz zmian wprowadzonych do niniejszej dokumentacji


Autor | Opis. | Format daty ISO 8601 | Link do GitHub
------|-----|-----|-----
[Dario Vladović](mailto:d.vladimyr@gmail.com) | coreutils*: use short more info links (#5658) | 2021-04-01T17:54:26 | [4830093903f6](https://github.com/tldr-pages/tldr/commit/4830093903f66ccf3ebbc2ecf477286e45edac59)
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | base32: add link (#5571) | 2021-03-30T09:11:31 | [30331c3d152d](https://github.com/tldr-pages/tldr/commit/30331c3d152d78ba495f78b7759f04b7bcd46f9f)
[Matthias Lübken](mailto:matthias.luebken@gmail.com) | base32, base64: fix -D flag (#5234) | 2021-03-07T23:58:11 | [00e00396a42a](https://github.com/tldr-pages/tldr/commit/00e00396a42a8b5fcc189909a1aae3173e513f72)
[Lucas Gabriel Schneider](mailto:casdpa@gmail.com) | multiple pages: format technical tokens (#5119) Co-authored-by: bl-ue <54780737+bl-ue@users.noreply.github.com> Co-authored-by: [...] | 2021-01-31T18:05:18 | [a5fe31bc47ae](https://github.com/tldr-pages/tldr/commit/a5fe31bc47aece3efa5e66b52b3cf384f27d5d72)
[Michal](mailto:mich.biesiada@gmail.com) | update base32 updated | 2020-04-19T14:31:16 | [6b389acca1bb](https://github.com/tldr-pages/tldr/commit/6b389acca1bbe8b6ffcb433623b305773401fec8)
[Michal](mailto:mich.biesiada@gmail.com) | update base32 updated | 2020-04-19T14:31:16 | [557c588cd916](https://github.com/tldr-pages/tldr/commit/557c588cd916777426b02697c4f1367513bddfbe)
[Michal](mailto:mich.biesiada@gmail.com) | create base32.md initial | 2020-04-19T14:31:16 | [4e9414d61d97](https://github.com/tldr-pages/tldr/commit/4e9414d61d97c8a6aef4a769e157ce36cf748ec8)

