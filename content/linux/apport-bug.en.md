---
author: ['Pierre Rudloff']
date: 1588891123
title: "apport-bug, TLDR Pages"
description: "apport-bug, File a bug report on Ubuntu."
categories: "linux"
---
> More information: <https://wiki.ubuntu.com/Apport>.

- Report a bug about the whole system:

```bash
apport-bug
```

- Report a bug about a specific package:

```bash
apport-bug package
```

- Report a bug about a specific executable:

```bash
apport-bug path/to/executable
```

- Report a bug about a specific process:

```bash
apport-bug PID
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Pierre Rudloff](mailto:contact@rudloff.pro) | apport-bug: add page (#4027) | 2020-05-08T00:38:43 | [23aa9a6a5828](https://github.com/tldr-pages/tldr/commit/23aa9a6a58283364b35954f76669c5fcd57746f3)

