---
author: ['Ronnie Gane', 'Dario Vladović', 'marchersimon']
date: 1620637392
title: "csplit, TLDR Pages"
description: "csplit, Split a file into pieces."
categories: "linux"
---
> This generates files named "xx00", "xx01", and so on.

> More information: <https://www.gnu.org/software/coreutils/csplit>.

- Split a file at lines 5 and 23:

```bash
csplit file 5 23
```

- Split a file every 5 lines (this will fail if the total number of lines is not divisible by 5):

```bash
csplit file 5 {*}
```

- Split a file every 5 lines, ignoring exact-division error:

```bash
csplit -k file 5 {*}
```

- Split a file at line 5 and use a custom prefix for the output files:

```bash
csplit file 5 -f prefix
```

- Split a file at a line matching a regular expression:

```bash
csplit file /regular_expression/
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | multiple pages: normalize `regular expression` instead of `regex`, `regexp` or `pattern` (#5830) | 2021-05-10T11:03:12 | [10728f1ab485](https://github.com/tldr-pages/tldr/commit/10728f1ab485957d66af3940a030b0fb77611fc0)
[Dario Vladović](mailto:d.vladimyr@gmail.com) | coreutils*: use short more info links (#5658) | 2021-04-01T17:54:26 | [4830093903f6](https://github.com/tldr-pages/tldr/commit/4830093903f66ccf3ebbc2ecf477286e45edac59)
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | csplit: add more information link (#5575) | 2021-03-30T12:10:07 | [5d92e443194d](https://github.com/tldr-pages/tldr/commit/5d92e443194da437deea00618a8bd37511ba99f5)
[Ronnie Gane](mailto:ronniegane@gmail.com) | csplit: add page (#2571) | 2018-11-29T08:55:23 | [e7ad6644b26e](https://github.com/tldr-pages/tldr/commit/e7ad6644b26e3eb83185059fe09e490a755d1e92)

