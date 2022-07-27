---
author: ['Waldir Pimenta', 'Jan Willhaus', 'sebastientinel', 'pxgamer', 'Lucas Gabriel Schneider']
date: 1612112718
title: "lz4, TLDR Pages"
description: "lz4, Compress or decompress .lz4 files."
categories: "common"
---
> More information: <https://github.com/lz4/lz4>.

- Compress a file:

```bash
lz4 file
```

- Decompress a file:

```bash
lz4 -d file.lz4
```

- Decompress a file and write to stdout:

```bash
lz4 -dc file.lz4
```

- Package and compress a directory and its contents:

```bash
tar cvf - path/to/directory | lz4 - dir.tar.lz4
```

- Decompress and unpack a directory and its contents:

```bash
lz4 -d dir.tar.lz4 | tar -xv
```

- Compress a file using the best compression:

```bash
lz4 -9 file
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Lucas Gabriel Schneider](mailto:casdpa@gmail.com) | multiple pages: format technical tokens (#5119) Co-authored-by: bl-ue <54780737+bl-ue@users.noreply.github.com> Co-authored-by: [...] | 2021-01-31T18:05:18 | [a5fe31bc47ae](https://github.com/tldr-pages/tldr/commit/a5fe31bc47aece3efa5e66b52b3cf384f27d5d72)
[sebastientinel](mailto:sebastien.tinel@gmail.com) | multiple pages: Unify file path syntax to indicate a 'path to' (#4816) | 2020-10-28T18:19:43 | [1d32985f2f24](https://github.com/tldr-pages/tldr/commit/1d32985f2f24e5469dddc993dd7f354f79bfa128)
[Waldir Pimenta](mailto:waldyrious@gmail.com) | Harmonize formatting and capitalization of stdin/stdout/stderr | 2019-06-17T18:39:58 | [cf25745db1d8](https://github.com/tldr-pages/tldr/commit/cf25745db1d86744c762e15e6a2ba04ef9f9acc1)
[pxgamer](mailto:owzie123@gmail.com) | lz4: add link to homepage | 2019-06-06T04:42:48 | [f017dc0a2f3c](https://github.com/tldr-pages/tldr/commit/f017dc0a2f3c577549e1db5ca047209e51058094)
[Jan Willhaus](mailto:mail@janwillhaus.de) | lz4: add page (#2125) | 2018-05-24T23:53:42 | [7aba31a6808f](https://github.com/tldr-pages/tldr/commit/7aba31a6808f1967c392a23b42c12d0305c6dd1f)

