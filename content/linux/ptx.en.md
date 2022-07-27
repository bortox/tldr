---
author: ['lbonanomi', 'Dario Vladović', 'marchersimon']
date: 1617292466
title: "ptx, TLDR Pages"
description: "ptx, Generate a permuted index of words from one or more text files."
categories: "linux"
---
> More information: <https://www.gnu.org/software/coreutils/ptx>.

- Generate a permuted index where the first field of each line is an index reference:

```bash
ptx --references path/to/file
```

- Generate a permuted index with automatically generated index references:

```bash
ptx --auto-reference path/to/file
```

- Generate a permuted index with a fixed width:

```bash
ptx --width=width_in_columns path/to/file
```

- Generate a permuted index with a list of filtered words:

```bash
ptx --only-file=path/to/filter path/to/file
```

- Generate a permuted index with SYSV-style behaviors:

```bash
ptx --traditional path/to/file
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Dario Vladović](mailto:d.vladimyr@gmail.com) | coreutils*: use short more info links (#5658) | 2021-04-01T17:54:26 | [4830093903f6](https://github.com/tldr-pages/tldr/commit/4830093903f66ccf3ebbc2ecf477286e45edac59)
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | ptx: add link (#5589) | 2021-03-30T15:56:25 | [230f9e28b1eb](https://github.com/tldr-pages/tldr/commit/230f9e28b1eb9f98799ed55b6c8ac33bf81e18cb)
[lbonanomi](mailto:5369016+lbonanomi@users.noreply.github.com) | ptx: add page (#2977) | 2019-05-08T01:32:47 | [55204d064f98](https://github.com/tldr-pages/tldr/commit/55204d064f98429882771ba2cd27dcb7a7a6c1dc)

