---
author: ['Damian Peterson', 'graves501', 'hodapp512']
date: 1662513704
title: "vimdiff"
description: "vimdiff, Open up two or more files in vim and show the differences between them."
categories: "common"
---
> See also `vim`.

> More information: <https://www.vim.org>.

- Open two files and show the differences:

```bash
vimdiff file1 file2
```

- Move the cursor to the window on the left|right:

```bash
Ctrl + w h|l
```

- Jump to the previous difference:

```bash
[c
```

- Jump to the next difference:

```bash
]c
```

- Copy the highlighted difference from the other window to the current window:

```bash
do
```

- Copy the highlighted difference from the current window to the other window:

```bash
dp
```

- Update all highlights and folds:

```bash
:diffupdate
```

- Toggle the highlighted code fold:

```bash
za
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[graves501](mailto:graves501@protonmail.com) | vimdiff: fix jump to previous/next difference instructions (#8462) | 2022-09-07T03:21:44 | [310c2fb54a8f](https://github.com/tldr-pages/tldr/commit/310c2fb54a8f85ff9a7a309b5e032fb22c6ae29d)
[hodapp512](mailto:hodapp512@gmail.com) | vimdiff: cleanup and update page (#4968) | 2020-12-14T14:03:56 | [76c19c3dfdc2](https://github.com/tldr-pages/tldr/commit/76c19c3dfdc2dfda918cea09dd9efa3dec8fb56b)
[Damian Peterson](mailto:damian@peterson.nz) | vimdiff: add page (#1373) | 2017-05-14T22:27:16 | [1ceb440ea489](https://github.com/tldr-pages/tldr/commit/1ceb440ea48957130f905c2cc37aadcea6437e7f)

