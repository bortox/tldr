---
author: ['Waldir Pimenta', 'Marco Bonelli', 'Dario Vladović', 'Hayden Schiff', 'Matthias Lübken', 'Lucas Gabriel Schneider', 'marchersimon']
date: 1617292466
title: "base32, TLDR Pages"
description: "base32, Encode or decode file or standard input to/from Base32, to standard output."
categories: "common"
---
> More information: <https://www.gnu.org/software/coreutils/base32>.

- Encode a file:

```bash
base32 filename
```

- Decode a file:

```bash
base32 --decode filename
```

- Encode from stdin:

```bash
somecommand | base32
```

- Decode from stdin:

```bash
somecommand | base32 --decode
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Dario Vladović](mailto:d.vladimyr@gmail.com) | coreutils*: use short more info links (#5658) | 2021-04-01T17:54:26 | [4830093903f6](https://github.com/tldr-pages/tldr/commit/4830093903f66ccf3ebbc2ecf477286e45edac59)
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | base32: add link (#5571) | 2021-03-30T09:11:31 | [30331c3d152d](https://github.com/tldr-pages/tldr/commit/30331c3d152d78ba495f78b7759f04b7bcd46f9f)
[Matthias Lübken](mailto:matthias.luebken@gmail.com) | base32, base64: fix -D flag (#5234) | 2021-03-07T23:58:11 | [00e00396a42a](https://github.com/tldr-pages/tldr/commit/00e00396a42a8b5fcc189909a1aae3173e513f72)
[Lucas Gabriel Schneider](mailto:casdpa@gmail.com) | multiple pages: format technical tokens (#5119) Co-authored-by: bl-ue <54780737+bl-ue@users.noreply.github.com> Co-authored-by: [...] | 2021-01-31T18:05:18 | [a5fe31bc47ae](https://github.com/tldr-pages/tldr/commit/a5fe31bc47aece3efa5e66b52b3cf384f27d5d72)
[Waldir Pimenta](mailto:waldyrious@gmail.com) | Harmonize formatting and capitalization of stdin/stdout/stderr | 2019-06-17T18:39:58 | [cf25745db1d8](https://github.com/tldr-pages/tldr/commit/cf25745db1d86744c762e15e6a2ba04ef9f9acc1)
[Marco Bonelli](mailto:mebeim@users.noreply.github.com) | base32/64: clearer command description. (#2722) | 2019-01-21T18:34:59 | [2babee607af2](https://github.com/tldr-pages/tldr/commit/2babee607af28bfb681882d8cee91a0e5cb878c6)
[Hayden Schiff](mailto:oxguy3@gmail.com) | base32: add page | 2016-02-05T17:37:35 | [ec4634971b31](https://github.com/tldr-pages/tldr/commit/ec4634971b31ca925f5baba8b0101bd272599b94)

