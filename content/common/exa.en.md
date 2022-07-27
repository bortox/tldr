---
author: ['ZabejAga', 'AnimiVulpis', 'Agniva De Sarker', 'pxgamer']
date: 1620846132
title: "exa, TLDR Pages"
description: "exa, A modern replacement for `ls` (List directory contents)."
categories: "common"
---
> More information: <https://the.exa.website>.

- List files one per line:

```bash
exa --oneline
```

- List all files, including hidden files:

```bash
exa --all
```

- Long format list (permissions, ownership, size and modification date) of all files:

```bash
exa --long --all
```

- List files with the largest at the top:

```bash
exa --reverse --sort=size
```

- Display a tree of files, three levels deep:

```bash
exa --long --tree --level=3
```

- List files sorted by modification date (oldest first):

```bash
exa --long --sort=modified
```

- List files with their headers, icons, and Git statuses:

```bash
exa --long --header --icons --git
```

- Don't list files mentioned in `.gitignore`:

```bash
exa --git-ignore
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[ZabejAga](mailto:81612608+ZabejAga@users.noreply.github.com) | exa: add --header, --git and --git-ignore examples (#5749) | 2021-05-12T21:02:12 | [94b99d3b281f](https://github.com/tldr-pages/tldr/commit/94b99d3b281f9ce2ac2988c92bce8063f1a367c0)
[pxgamer](mailto:owzie123@gmail.com) | exa: add link to homepage | 2019-06-09T06:54:24 | [16f380c38930](https://github.com/tldr-pages/tldr/commit/16f380c3893025ce78338818b0a0b1a23512c80c)
[Agniva De Sarker](mailto:agnivade@yahoo.co.in) | exa: update page - Added tokens around parameters - Put backticks around ls - Simplified some descriptions. | 2017-10-28T20:32:54 | [3c66fc488e40](https://github.com/tldr-pages/tldr/commit/3c66fc488e40a81554c71c972da6d9b282ed943e)
[AnimiVulpis](mailto:animi.vulpis@gmail.com) | exa: add page | 2017-10-27T16:38:37 | [1d019e820040](https://github.com/tldr-pages/tldr/commit/1d019e820040089da77713907ad14ba0e412caaf)

