---
author: ['WhileLoop']
date: 1633358896
title: "jhsdb"
description: "jhsdb, Attach to a Java process or launch a postmortem debugger to analyze the core dump from a crashed Java Virtual Machine."
categories: "common"
---
> More information: <https://manned.org/jhsdb>.

- Print stack and locks information of a Java process:

```bash
jhsdb jstack --pid pid
```

- Open a core dump in interactive debug mode:

```bash
jhsdb clhsdb --core path/to/core_dump --exe path/to/jdk/bin/java
```

- Start a remote debug server:

```bash
jhsdb debugd --pid pid --serverid optional_unique_id
```

- Connect to a process in interactive debug mode:

```bash
jhsdb clhsdb --pid pid
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[WhileLoop](mailto:1332785+WhileLoop@users.noreply.github.com) | jhsdb: add page (#6643) | 2021-10-04T16:48:16 | [c4e73acbcd6e](https://github.com/tldr-pages/tldr/commit/c4e73acbcd6eba551f5c909343c0d8831fd6f305)

