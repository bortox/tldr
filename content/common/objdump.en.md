---
author: ['Guilherme Leobas', 'jxu', 'Joshua Shanks']
date: 1661609635
title: "objdump"
description: "objdump, View information about object files."
categories: "common"
---
> More information: <https://manned.org/objdump>.

- Display the file header information:

```bash
objdump -f binary
```

- Display the disassembled output of executable sections:

```bash
objdump -d binary
```

- Display the disassembled executable sections in intel syntax:

```bash
objdump -M intel -d binary
```

- Display a complete binary hex dump of all sections:

```bash
objdump -s binary
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[jxu](mailto:7989982+jxu@users.noreply.github.com) | objdump: add intel syntax command (#8402) | 2022-08-27T16:13:55 | [e70b607b7b3b](https://github.com/tldr-pages/tldr/commit/e70b607b7b3b27b93443882c5c003e9a677b9db7)
[Joshua Shanks](mailto:jjshanks@gmail.com) | nslookup, objdump, pactl, passwd, patch: add link (#6828) | 2021-10-07T01:34:03 | [d91120d92e31](https://github.com/tldr-pages/tldr/commit/d91120d92e31e12fa2bd5723fb386d9fe05438bf)
[Guilherme Leobas](mailto:guilhermeleobas@gmail.com) | objdump: move to common (#2627) | 2018-11-29T10:41:37 | [571e44e3e1ad](https://github.com/tldr-pages/tldr/commit/571e44e3e1ad6cfd27ac2b8789727d8295590bda)

