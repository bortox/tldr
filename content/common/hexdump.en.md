---
author: ['nzdjb', 'marchersimon']
date: 1634444509
title: "hexdump"
description: "hexdump, An ASCII, decimal, hexadecimal, octal dump."
categories: "common"
---
> More information: <https://manned.org/hexdump>.

- Print the hexadecimal representation of a file, replacing duplicate lines by '*':

```bash
hexdump file
```

- Display the input offset in hexadecimal and its ASCII representation in two columns:

```bash
hexdump -C file
```

- Display the hexadecimal representation of a file, but interpret only n bytes of the input:

```bash
hexdump -C -nnumber_of_bytes file
```

- Don't replace duplicate lines with '*':

```bash
hexdump --no-squeezing file
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[nzdjb](mailto:github@2a1b.com) | hexdump: add --no-squeezing example (#6894) | 2021-10-17T06:21:49 | [872d359bbd6a](https://github.com/tldr-pages/tldr/commit/872d359bbd6a93fc12c540c6eee3db7874d71286)
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | hexdump, logger, netstat, n, nm, pdfgrep: move to common (#6549) | 2021-09-18T23:05:08 | [442a013cb866](https://github.com/tldr-pages/tldr/commit/442a013cb86602dfb50e4beb8bd2f66dc97e117d)

