---
author: ['marchersimon', 'Niklas']
date: 1635215179
title: "yank, TLDR Pages"
description: "yank, Read input from stdin and display a selection interface that allows a field to be selected and copied to the clipboard."
categories: "common"
---
> More information: <https://manned.org/yank>.

- Yank using the default delimiters (\f, \n, \r, \s, \t):

```bash
sudo dmesg | yank
```

- Yank an entire line:

```bash
sudo dmesg | yank -l
```

- Yank using a specific delimiter:

```bash
echo hello=world | yank -d =
```

- Only yank fields matching a specific pattern:

```bash
ps ux | yank -g "[0-9]+"
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Niklas](mailto:derNiklaas@users.noreply.github.com) | yank, yaourt: add more information link (#7049) | 2021-10-26T04:26:19 | [bf5c13a00d3b](https://github.com/tldr-pages/tldr/commit/bf5c13a00d3b256646326a4d3bfd23fddc5dbed3)
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | whereis, xar, yank: move to common (#6552) | 2021-09-19T02:59:20 | [e94e6af88289](https://github.com/tldr-pages/tldr/commit/e94e6af88289f26bf25c85b45971f240f56d8672)

