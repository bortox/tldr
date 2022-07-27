---
author: ['maniyar1']
date: 1656417098
title: "ld, TLDR Pages"
description: "ld, Link object files together."
categories: "common"
---
> More information: <https://sourceware.org/binutils/docs-2.38/ld.html>.

- Link a specific object file with no dependencies into an executable:

```bash
ld path/to/file.o --output path/to/output_executable
```

- Link two object files together:

```bash
ld path/to/file1.o path/to/file2.o --output path/to/output_executable
```

- Dynamically link an x86_64 program to glibc (file paths change depending on the system):

```bash
ld --output path/to/output_executable --dynamic-linker /lib/ld-linux-x86-64.so.2 /lib/crt1.o /lib/crti.o -lc path/to/file.o /lib/crtn.o
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[maniyar1](mailto:32717947+maniyar1@users.noreply.github.com) | ld: add page (#7922) | 2022-06-28T13:51:38 | [61763b2022cc](https://github.com/tldr-pages/tldr/commit/61763b2022cc83062c88c05f34ac4d199ddbaf3a)

