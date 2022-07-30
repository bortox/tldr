---
author: ['Ruben Vereecken', 'pxgamer', 'Joel Huang', 'Marco Bonelli']
date: 1564822908
title: "enca"
description: "enca, Detect and convert the encoding of text files."
categories: "common"
---
> More information: <https://github.com/nijel/enca>.

- Detect file(s) encoding according to the system's locale:

```bash
enca file1 file2 ...
```

- Detect file(s) encoding specifying a language in the POSIX/C locale format (e.g. zh_CN, en_US):

```bash
enca -L language file1 file2 ...
```

- Convert file(s) to a specific encoding:

```bash
enca -L language -x to_encoding file1 file2 ...
```

- Create a copy of an existing file using a different encoding:

```bash
enca -L language -x to_encoding < original_file > new_file
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Marco Bonelli](mailto:mebeim@users.noreply.github.com) | enca: clarify examples and fix tokens (#3214) - Clarify and simplify examples' descriptions. - Change the token {{files(s)}} to [...] | 2019-08-03T11:01:48 | [af602a181c88](https://github.com/tldr-pages/tldr/commit/af602a181c88547338047e9c44381029b3d1768b)
[pxgamer](mailto:owzie123@gmail.com) | enca: add link to homepage | 2019-06-09T06:54:24 | [b8aa766d3cfc](https://github.com/tldr-pages/tldr/commit/b8aa766d3cfc5ac79e41d8215495cf73f3fb9d6f)
[Ruben Vereecken](mailto:rubenvereecken@gmail.com) | Formatted all pages according to guidelines. | 2016-01-08T09:38:59 | [066582e8eab5](https://github.com/tldr-pages/tldr/commit/066582e8eab57bce9861cc8d379e158d61f1cc95)
[Joel Huang](mailto:joelhy@gmail.com) | enca: add page | 2016-01-07T01:30:17 | [85355d1ed6b2](https://github.com/tldr-pages/tldr/commit/85355d1ed6b22cdbdda166cc27874c153bbac765)

