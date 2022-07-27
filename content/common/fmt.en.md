---
author: ['gRastello', 'Dario Vladović', 'marchersimon']
date: 1617292466
title: "fmt, TLDR Pages"
description: "fmt, Reformat a text file by joining its paragraphs and limiting the line width to given number of characters (75 by default)."
categories: "common"
---
> More information: <https://www.gnu.org/software/coreutils/fmt>.

- Reformat a file:

```bash
fmt path/to/file
```

- Reformat a file producing output lines of (at most) `n` characters:

```bash
fmt -w n path/to/file
```

- Reformat a file without joining lines shorter than the given width together:

```bash
fmt -s path/to/file
```

- Reformat a file with uniform spacing (1 space between words and 2 spaces between paragraphs):

```bash
fmt -u path/to/file
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Dario Vladović](mailto:d.vladimyr@gmail.com) | coreutils*: use short more info links (#5658) | 2021-04-01T17:54:26 | [4830093903f6](https://github.com/tldr-pages/tldr/commit/4830093903f66ccf3ebbc2ecf477286e45edac59)
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | fmt: add link (#5578) | 2021-03-30T08:56:16 | [30b4f26add36](https://github.com/tldr-pages/tldr/commit/30b4f26add3636e47ae11fd0f812671dacf2ab7f)
[gRastello](mailto:gabriele.rastello@edu.unito.it) | fmt: add page | 2019-02-10T00:22:44 | [5613928eeaa3](https://github.com/tldr-pages/tldr/commit/5613928eeaa361b5913cbfffa82ea7dc852fa40d)

