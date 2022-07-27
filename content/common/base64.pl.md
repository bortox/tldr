---
author: ['Michal', 'Dario Vladović', 'Matthias Lübken', 'Lucas Gabriel Schneider', 'marchersimon']
date: 1617292466
title: "base64, TLDR Pages"
description: "base64, Enkoduj lub dekoduj plik lub standardowe wejście do/z Base64, na standardowe wyjście."
categories: "common"
---
> Więcej informacji: <https://www.gnu.org/software/coreutils/base64>.

- Enkoduj plik:

```bash
base64 nazwapliku
```

- Dekoduj plik:

```bash
base64 --decode nazwapliku
```

- Enkoduj z stdin:

```bash
jakiespolecenie | base64
```

- Dekoduj z stdin:

```bash
jakiespolecenie | base64 --decode
```
Wykaz zmian wprowadzonych do niniejszej dokumentacji


Autor | Opis. | Format daty ISO 8601 | Link do GitHub
------|-----|-----|-----
[Dario Vladović](mailto:d.vladimyr@gmail.com) | coreutils*: use short more info links (#5658) | 2021-04-01T17:54:26 | [4830093903f6](https://github.com/tldr-pages/tldr/commit/4830093903f66ccf3ebbc2ecf477286e45edac59)
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | base64: add link (#5572) | 2021-03-30T09:06:32 | [59583f4c3ef2](https://github.com/tldr-pages/tldr/commit/59583f4c3ef21258f554c49dc14001e27e3bd4e1)
[Matthias Lübken](mailto:matthias.luebken@gmail.com) | base32, base64: fix -D flag (#5234) | 2021-03-07T23:58:11 | [00e00396a42a](https://github.com/tldr-pages/tldr/commit/00e00396a42a8b5fcc189909a1aae3173e513f72)
[Lucas Gabriel Schneider](mailto:casdpa@gmail.com) | multiple pages: format technical tokens (#5119) Co-authored-by: bl-ue <54780737+bl-ue@users.noreply.github.com> Co-authored-by: [...] | 2021-01-31T18:05:18 | [a5fe31bc47ae](https://github.com/tldr-pages/tldr/commit/a5fe31bc47aece3efa5e66b52b3cf384f27d5d72)
[Michal](mailto:mich.biesiada@gmail.com) | update base64 updated | 2020-04-19T14:31:16 | [bc080e87ec67](https://github.com/tldr-pages/tldr/commit/bc080e87ec67343d0fad3f99b0b9f022008325cd)
[Michal](mailto:mich.biesiada@gmail.com) | update base64 updated | 2020-04-19T14:31:16 | [1ba0d0c32b61](https://github.com/tldr-pages/tldr/commit/1ba0d0c32b61dc938190020a8432c1049abc13c8)
[Michal](mailto:mich.biesiada@gmail.com) | create base64.md initial | 2020-04-19T14:31:16 | [1f3c78c7155b](https://github.com/tldr-pages/tldr/commit/1f3c78c7155b5f3dba93e06c60136b9a7dafeffb)

