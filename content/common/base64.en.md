---
author: ['Waldir Pimenta', 'Steven Pitts', 'Marco Bonelli', 'Dario Vladović', 'Hayden Schiff', 'Matthias Lübken', 'Lucas Gabriel Schneider', 'marchersimon']
date: 1618153665
title: "base64, TLDR Pages"
description: "base64, Encode or decode file or standard input to/from Base64, to standard output."
categories: "common"
---
> More information: <https://www.gnu.org/software/coreutils/base64>.

- Encode the contents of a file as base64 and write the result to stdout:

```bash
base64 filename
```

- Decode the base64 contents of a file and write the result to stdout:

```bash
base64 --decode filename
```

- Encode from stdin:

```bash
somecommand | base64
```

- Decode from stdin:

```bash
somecommand | base64 --decode
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Steven Pitts](mailto:25968054+makusu2@users.noreply.github.com) | base64: clarify example descriptions that do not edit files inplace (#5656) | 2021-04-11T17:07:45 | [85ad9ba2479b](https://github.com/tldr-pages/tldr/commit/85ad9ba2479b8e3d8cc144fbf0150bc0d858dc2e)
[Dario Vladović](mailto:d.vladimyr@gmail.com) | coreutils*: use short more info links (#5658) | 2021-04-01T17:54:26 | [4830093903f6](https://github.com/tldr-pages/tldr/commit/4830093903f66ccf3ebbc2ecf477286e45edac59)
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | base64: add link (#5572) | 2021-03-30T09:06:32 | [59583f4c3ef2](https://github.com/tldr-pages/tldr/commit/59583f4c3ef21258f554c49dc14001e27e3bd4e1)
[Matthias Lübken](mailto:matthias.luebken@gmail.com) | base32, base64: fix -D flag (#5234) | 2021-03-07T23:58:11 | [00e00396a42a](https://github.com/tldr-pages/tldr/commit/00e00396a42a8b5fcc189909a1aae3173e513f72)
[Lucas Gabriel Schneider](mailto:casdpa@gmail.com) | multiple pages: format technical tokens (#5119) Co-authored-by: bl-ue <54780737+bl-ue@users.noreply.github.com> Co-authored-by: [...] | 2021-01-31T18:05:18 | [a5fe31bc47ae](https://github.com/tldr-pages/tldr/commit/a5fe31bc47aece3efa5e66b52b3cf384f27d5d72)
[Waldir Pimenta](mailto:waldyrious@gmail.com) | Harmonize formatting and capitalization of stdin/stdout/stderr | 2019-06-17T18:39:58 | [cf25745db1d8](https://github.com/tldr-pages/tldr/commit/cf25745db1d86744c762e15e6a2ba04ef9f9acc1)
[Marco Bonelli](mailto:mebeim@users.noreply.github.com) | base32/64: clearer command description. (#2722) | 2019-01-21T18:34:59 | [2babee607af2](https://github.com/tldr-pages/tldr/commit/2babee607af28bfb681882d8cee91a0e5cb878c6)
[Hayden Schiff](mailto:oxguy3@gmail.com) | base64: moved from linux to common | 2016-02-05T17:37:27 | [753e94850b52](https://github.com/tldr-pages/tldr/commit/753e94850b52363dfc3a9fd4e4a9a86a7a4f3680)

