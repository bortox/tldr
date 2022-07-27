---
author: ['BillLucky', 'Max Xu']
date: 1621769895
title: "jps, TLDR Pages"
description: "jps, Show JVM Process Status of current user."
categories: "common"
---
> More information: <https://docs.oracle.com/en/java/javase/11/tools/jps.html>.

- List all JVM processes:

```bash
jps
```

- List all JVM processes with only PID:

```bash
jps -q
```

- Display the arguments passed to the processes:

```bash
jps -m
```

- Display the full package name of all processes:

```bash
jps -l
```

- Display the arguments passed to the JVM:

```bash
jps -v
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[BillLucky](mailto:bill.libiao@gmail.com) | jps: add more information link (#6017) | 2021-05-23T13:38:15 | [07c6ae3bc074](https://github.com/tldr-pages/tldr/commit/07c6ae3bc074a787a44c57f86dd63e8d35ce454d)
[Max Xu](mailto:xuhuan@live.cn) | jps.md: add page (#1946) | 2018-01-29T08:30:39 | [1ad1487937d5](https://github.com/tldr-pages/tldr/commit/1ad1487937d52be8182f36e4340d3c0adae4d793)

