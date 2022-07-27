---
author: ['fanatiicx']
date: 1633528234
title: "dlv, TLDR Pages"
description: "dlv, Debugger for the Go programming language."
categories: "common"
---
> More information: <https://github.com/go-delve/delve/blob/master/Documentation/usage/dlv.md>.

- Compile and begin debugging the main package in the current directory (by default, with no arguments):

```bash
dlv debug
```

- Compile and begin debugging a specific package:

```bash
dlv debug package arguments
```

- Compile a test binary and begin debugging the compiled program:

```bash
dlv test
```

- Connect to a headless debug server:

```bash
dlv connect ip_address
```

- Attach to a running process and begin debugging:

```bash
div attach pid
```

- Compile and begin tracing a program:

```bash
dlv trace package --regexp 'regular_expression'
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[fanatiicx](mailto:85956139+fanatiicx@users.noreply.github.com) | dlv: add page (#6697) | 2021-10-06T15:50:34 | [d08564637d02](https://github.com/tldr-pages/tldr/commit/d08564637d0223e8e3d21cfb6434376d77407cb4)

