---
author: ['Tony', 'Dario Vladović', 'marchersimon']
date: 1617292466
title: "runcon"
description: "runcon, Run a program in a different SELinux security context."
categories: "linux"
---
> With neither context nor command, print the current security context.

> More information: <https://www.gnu.org/software/coreutils/runcon>.

- Determine the current domain:

```bash
runcon
```

- Specify the domain to run a command in:

```bash
runcon -t domain_t command
```

- Specify the context role to run a command with:

```bash
runcon -r role_r command
```

- Specify the full context to run a command with:

```bash
runcon user_u:role_r:domain_t command
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Dario Vladović](mailto:d.vladimyr@gmail.com) | coreutils*: use short more info links (#5658) | 2021-04-01T17:54:26 | [4830093903f6](https://github.com/tldr-pages/tldr/commit/4830093903f66ccf3ebbc2ecf477286e45edac59)
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | runcon: add more information link (#5624) | 2021-03-30T16:12:54 | [a6a0d2073546](https://github.com/tldr-pages/tldr/commit/a6a0d2073546cb3f3a5a6a7a43da502737e1f92b)
[Tony](mailto:43508092+tonytheleg@users.noreply.github.com) | runcon: add page (#3297) | 2019-10-29T07:45:37 | [5fec60d0156d](https://github.com/tldr-pages/tldr/commit/5fec60d0156dfe58aa92564d21e9adc07f76503a)

