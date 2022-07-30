---
author: ['Lucas Gabriel Schneider', 'Dario Vladović', 'Matthias Lübken', 'marchersimon', 'Manuel Carabajo R']
date: 1617292466
title: "base64"
description: "base64, Codifica o decodifica un archivo o la entrada estandar hacia/desde Base64, a la salida estandar."
categories: "common"
---
> Más información: <https://www.gnu.org/software/coreutils/base64>.

- Codifica un archivo:

```bash
base64 nombre_de_archivo
```

- Decodifica un archivo:

```bash
base64 --decode nombre_de_archivo
```

- Codifica stdin:

```bash
comando | base64
```

- Decodifica stdin:

```bash
comando | base64 --decode
```
Lista de modificaciones realizadas en este archivo


Autor | Descripción | Formato de fecha ISO 8601 | Enlace a GitHub
------|-----|-----|-----
[Dario Vladović](mailto:d.vladimyr@gmail.com) | coreutils*: use short more info links (#5658) | 2021-04-01T17:54:26 | [4830093903f6](https://github.com/tldr-pages/tldr/commit/4830093903f66ccf3ebbc2ecf477286e45edac59)
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | base64: add link (#5572) | 2021-03-30T09:06:32 | [59583f4c3ef2](https://github.com/tldr-pages/tldr/commit/59583f4c3ef21258f554c49dc14001e27e3bd4e1)
[Matthias Lübken](mailto:matthias.luebken@gmail.com) | base32, base64: fix -D flag (#5234) | 2021-03-07T23:58:11 | [00e00396a42a](https://github.com/tldr-pages/tldr/commit/00e00396a42a8b5fcc189909a1aae3173e513f72)
[Lucas Gabriel Schneider](mailto:casdpa@gmail.com) | multiple pages: format technical tokens (#5119) Co-authored-by: bl-ue <54780737+bl-ue@users.noreply.github.com> Co-authored-by: [...] | 2021-01-31T18:05:18 | [a5fe31bc47ae](https://github.com/tldr-pages/tldr/commit/a5fe31bc47aece3efa5e66b52b3cf384f27d5d72)
[Manuel Carabajo R](mailto:30765477+mcarabajo@users.noreply.github.com) | base64: add Spanish translation (#4675) | 2020-10-13T14:01:40 | [6df5f5c829a0](https://github.com/tldr-pages/tldr/commit/6df5f5c829a0815b651ed54faf5233479d0f736e)

