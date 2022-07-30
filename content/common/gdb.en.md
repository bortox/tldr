---
author: ['Bruno Bigras', 'L. Mountrakis', 'André Almeida', 'pxgamer']
date: 1603124778
title: "gdb"
description: "gdb, The GNU Debugger."
categories: "common"
---
> More information: <https://www.gnu.org/software/gdb>.

- Debug an executable:

```bash
gdb executable
```

- Attach a process to gdb:

```bash
gdb -p procID
```

- Debug with a core file:

```bash
gdb -c core executable
```

- Execute given GDB commands upon start:

```bash
gdb -ex "commands" executable
```

- Start gdb and pass arguments to the executable:

```bash
gdb --args executable argument1 argument2
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[André Almeida](mailto:andrealmeid@collabora.com) | gdb: disambiguate --args example (#4704) | 2020-10-19T18:26:18 | [30e4396146f6](https://github.com/tldr-pages/tldr/commit/30e4396146f65061dd6faa4eca38aab4d42089b5)
[pxgamer](mailto:owzie123@gmail.com) | gdb: add link to homepage | 2019-06-07T23:58:59 | [4c2fbae23c9f](https://github.com/tldr-pages/tldr/commit/4c2fbae23c9f02aabb2505f5df71ca165288c234)
[Bruno Bigras](mailto:bigras.bruno@gmail.com) | gdb: add core file example (#3021) | 2019-05-14T03:24:17 | [e6b313afab86](https://github.com/tldr-pages/tldr/commit/e6b313afab86f873df58975839e00f2e874a5e69)
[L. Mountrakis](mailto:LMountr@gmail.com) | gdb: add page | 2016-02-15T23:22:28 | [1db1b4d691e3](https://github.com/tldr-pages/tldr/commit/1db1b4d691e3ec1fa88048b1089e59f911dbd29f)

