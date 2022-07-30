---
author: ['Joshua Shanks', 'Guilherme Leobas']
date: 1633563243
title: "objdump"
description: "objdump, View information about object files."
categories: "common"
---
> More information: <https://manned.org/objdump>.

- Display the file header information:

```bash
objdump -f binary
```

- Display the dis-assembled output of executable sections:

```bash
objdump -d binary
```

- Display a complete binary hex dump of all sections:

```bash
objdump -s binary
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Joshua Shanks](mailto:jjshanks@gmail.com) | nslookup, objdump, pactl, passwd, patch: add link (#6828) | 2021-10-07T01:34:03 | [d91120d92e31](https://github.com/tldr-pages/tldr/commit/d91120d92e31e12fa2bd5723fb386d9fe05438bf)
[Guilherme Leobas](mailto:guilhermeleobas@gmail.com) | objdump: move to common (#2627) | 2018-11-29T10:41:37 | [571e44e3e1ad](https://github.com/tldr-pages/tldr/commit/571e44e3e1ad6cfd27ac2b8789727d8295590bda)

