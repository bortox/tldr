---
author: ['Waldir Pimenta', 'Andrik Albuquerque', 'Marco Bonelli', 'Hayden Schiff', 'Lucas Gabriel Schneider', 'Seth Falco']
date: 1629050349
title: "xz, TLDR Pages"
description: "xz, Compress or decompress .xz and .lzma files."
categories: "common"
---
> More information: <https://tukaani.org/xz/format.html>.

- Compress a file to the xz file format:

```bash
xz file
```

- Decompress a xz file:

```bash
xz -d file.xz
```

- Compress a file to the LZMA file format:

```bash
xz --format=lzma file
```

- Decompress an LZMA file:

```bash
xz -d --format=lzma file.lzma
```

- Decompress a file and write to stdout:

```bash
xz -dc file.xz
```

- Compress a file, but don't delete the original:

```bash
xz -k file
```

- Compress a file using the fastest compression:

```bash
xz -0 file
```

- Compress a file using the best compression:

```bash
xz -9 file
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Seth Falco](mailto:seth@falco.fun) | *: fix errors reported by languagetool (#6069) | 2021-08-15T19:59:09 | [3e4c519004a4](https://github.com/tldr-pages/tldr/commit/3e4c519004a471c861cdc609fd7239ee3355671c)
[Lucas Gabriel Schneider](mailto:casdpa@gmail.com) | multiple pages: format technical tokens (#5119) Co-authored-by: bl-ue <54780737+bl-ue@users.noreply.github.com> Co-authored-by: [...] | 2021-01-31T18:05:18 | [a5fe31bc47ae](https://github.com/tldr-pages/tldr/commit/a5fe31bc47aece3efa5e66b52b3cf384f27d5d72)
[Waldir Pimenta](mailto:waldyrious@gmail.com) | Harmonize formatting and capitalization of stdin/stdout/stderr | 2019-06-17T18:39:58 | [cf25745db1d8](https://github.com/tldr-pages/tldr/commit/cf25745db1d86744c762e15e6a2ba04ef9f9acc1)
[Marco Bonelli](mailto:marco@mebeim.net) | Refactor: reword English pages' links' descriptions. | 2019-06-03T14:19:41 | [66abb98ce935](https://github.com/tldr-pages/tldr/commit/66abb98ce935c0f4516bf30c4d6da72180d5a3ab)
[Andrik Albuquerque](mailto:andrik.albuquerque@gmail.com) | xz: add lzma format examples (#2908) | 2019-04-15T02:24:14 | [6fe385b344de](https://github.com/tldr-pages/tldr/commit/6fe385b344ded8725029e64d4164fe10af5c8840)
[Hayden Schiff](mailto:oxguy3@gmail.com) | xz: added "the" | 2016-02-01T19:48:59 | [4d7fcde503a2](https://github.com/tldr-pages/tldr/commit/4d7fcde503a2a15dafe9150567aced6c03508e08)
[Hayden Schiff](mailto:oxguy3@gmail.com) | xz: better compression ratio examples | 2016-01-28T22:20:30 | [f07f4532b23d](https://github.com/tldr-pages/tldr/commit/f07f4532b23d190751762f9d949092852fb8bdba)
[Hayden Schiff](mailto:oxguy3@gmail.com) | xz: add page | 2016-01-28T21:42:05 | [c2a39d42c246](https://github.com/tldr-pages/tldr/commit/c2a39d42c246e0e9db0e65712bd77c1fb635b526)

