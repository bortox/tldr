---
author: ['Dario Vladović', 'Sailesh Choyal', 'marchersimon']
date: 1617292466
title: "fold, TLDR Pages"
description: "fold, Wraps each line in an input file to fit a specified width and prints it to the standard output."
categories: "common"
---
> More information: <https://www.gnu.org/software/coreutils/fold>.

- Wrap each line to default width (80 characters):

```bash
fold file
```

- Wrap each line to width "30":

```bash
fold -w30 file
```

- Wrap each line to width "5" and break the line at spaces (puts each space separated word in a new line, words with length > 5 are wrapped):

```bash
fold -w5 -s file
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Dario Vladović](mailto:d.vladimyr@gmail.com) | coreutils*: use short more info links (#5658) | 2021-04-01T17:54:26 | [4830093903f6](https://github.com/tldr-pages/tldr/commit/4830093903f66ccf3ebbc2ecf477286e45edac59)
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | fold: add link (#5579) | 2021-03-30T08:53:35 | [5b92d1fb413d](https://github.com/tldr-pages/tldr/commit/5b92d1fb413d2d1d53d785e0b9191860902e8af1)
[Sailesh Choyal](mailto:gamebusterz2@gmail.com) | fold: add page (#1087) | 2016-09-24T13:57:28 | [6848f6db4428](https://github.com/tldr-pages/tldr/commit/6848f6db4428009f0691c6ea7da557118fc17570)

