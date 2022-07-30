---
author: ['Alwin Lohrie']
date: 1633628386
title: "lsd"
description: "lsd, List directory contents."
categories: "common"
---
> The next generation `ls` command, written in Rust.

> More information: <https://github.com/Peltoche/lsd>.

- List files and directories, one per line:

```bash
lsd -1
```

- List all files and directories, including hidden ones, in the current directory:

```bash
lsd -a
```

- List all files and directories with trailing `/` added to directory names:

```bash
lsd -F
```

- List all files and directories in long format (permissions, ownership, size, and modification date):

```bash
lsd -la
```

- List all files and directories in long format with size displayed using human-readable units (KiB, MiB, GiB):

```bash
lsd -lh
```

- List all files and directories in long format, sorted by size (descending):

```bash
lsd -lS
```

- List all files and directories in long format, sorted by modification date (oldest first):

```bash
lsd -ltr
```

- Only list directories:

```bash
lsd -d */
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Alwin Lohrie](mailto:46248939+niwla23@users.noreply.github.com) | lsd: add page (#6654) | 2021-10-07T19:39:46 | [9373a1ab23d6](https://github.com/tldr-pages/tldr/commit/9373a1ab23d68b92d9c88517dfe8e8d9523badbb)

