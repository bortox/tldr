---
author: ['Hieu Huynh', 'Emily Grace Seville']
date: 1647882468
title: "runuser"
description: "runuser, Run commands as a specific user and group without asking for password (needs root privileges)."
categories: "linux"
---
> More information: <https://manned.org/runuser>.

- Run command as a different user:

```bash
runuser user -c 'command'
```

- Run command as a different user and group:

```bash
runuser user -g group -c 'command'
```

- Start a login shell as a specific user:

```bash
runuser user -l
```

- Specify a shell for running instead of the default shell (also works for login):

```bash
runuser user -s /bin/sh
```

- Preserve the entire environment of root (only if `--login` is not specified):

```bash
runuser user --preserve-environment -c 'command'
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Emily Grace Seville](mailto:emilyseville7cf@gmail.com) | linux/*: add more information link (#7848) | 2022-03-21T18:07:48 | [4659bcb243ac](https://github.com/tldr-pages/tldr/commit/4659bcb243ac572c9e0c95117097801f1e62bda4)
[Hieu Huynh](mailto:huynhtrunghieu.cs@gmail.com) | runuser: add page (#3283) | 2019-10-04T15:12:20 | [de4c03124e26](https://github.com/tldr-pages/tldr/commit/de4c03124e265d52793ae041518fd3fb54c9cbd1)

