---
author: ['Adrien Thebo']
date: 1652498542
title: "lsns"
description: "lsns, List information about all namespaces or about the specified namespace."
categories: "linux"
---
> More information: <https://man7.org/linux/man-pages/man8/lsns.8.html>.

- List all namespaces:

```bash
lsns
```

- List namespaces in JSON format:

```bash
lsns --json
```

- List namespaces associated with {{pid}}:

```bash
lsns --task pid
```

- List the specified type of namespaces only:

```bash
lsns --type <mnt|net|ipc|user|pid|uts|cgroup|time>
```

- List namespaces, only showing the namespace ID, type, PID, and command:

```bash
lsns --output NS,TYPE,PID,COMMAND
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Adrien Thebo](mailto:adrien@lagrange-automation.io) | lsns: add page (#8078) | 2022-05-14T05:22:22 | [74f72f6d827e](https://github.com/tldr-pages/tldr/commit/74f72f6d827e6438c7d823dfe09f6a3093a76101)

