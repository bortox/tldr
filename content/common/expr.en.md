---
author: ['Dario Vladović', 'Felix Yan', 'marchersimon']
date: 1617292466
title: "expr"
description: "expr, Evaluate expressions and manipulate strings."
categories: "common"
---
> More information: <https://www.gnu.org/software/coreutils/expr>.

- Get string length:

```bash
expr length string
```

- Evaluate logical or math expression with an operator ('+', '-', '*', '&', '|', etc.). Special symbols should be escaped:

```bash
expr first_argument operator second_argument
```

- Get position of the first character in 'string' that matches 'substring':

```bash
echo $(expr index string substring)
```

- Extract part of the string:

```bash
echo $(expr substr string position_to_start number_of_characters
```

- Extract part of the string which matches a regular expression:

```bash
echo $(expr string : '\(regular_expression\)')
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Dario Vladović](mailto:d.vladimyr@gmail.com) | coreutils*: use short more info links (#5658) | 2021-04-01T17:54:26 | [4830093903f6](https://github.com/tldr-pages/tldr/commit/4830093903f66ccf3ebbc2ecf477286e45edac59)
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | expr: add link (#5608) | 2021-03-30T15:54:01 | [95846ed907a1](https://github.com/tldr-pages/tldr/commit/95846ed907a193631cf92289b51983d3394efa29)
[Felix Yan](mailto:felixonmars@archlinux.org) | coreutils commands: move pages to common/ folder (#2442) | 2018-10-16T19:29:50 | [72b4f22ff97b](https://github.com/tldr-pages/tldr/commit/72b4f22ff97b1890344f2af870ad3d1c89a3f0b5)

