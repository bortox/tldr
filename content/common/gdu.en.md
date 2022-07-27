---
author: ['Ein Verne']
date: 1631102661
title: "gdu, TLDR Pages"
description: "gdu, Disk usage analyzer with console interface."
categories: "common"
---
> More information: <https://github.com/dundee/gdu>.

- Interactively show the disk usage of the current directory:

```bash
gdu
```

- Interactively show the disk usage of a given directory:

```bash
gdu path/to/directory
```

- Interactively show the disk usage of all mounted disks:

```bash
gdu --show-disks
```

- Interactively show the disk usage of the current directory but ignore some sub-directories:

```bash
gdu --ignore-dirs path/to/directory1,path/to/directory2,...
```

- Ignore paths by regular expression:

```bash
gdu --ignore-dirs-pattern '.*[abc]+'
```

- Ignore hidden directories:

```bash
gdu --no-hidden
```

- Only print the result, do not enter interactive mode:

```bash
gdu --non-interactive path/to/directory
```

- Do not show the progress in non-interactive mode (useful in scripts):

```bash
gdu --no-progress path/to/directory
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Ein Verne](mailto:einverne@gmail.com) | gdu: add page (#6447) | 2021-09-08T14:04:21 | [ca6d87cd3080](https://github.com/tldr-pages/tldr/commit/ca6d87cd3080c1e836277709be22452efe92283b)

