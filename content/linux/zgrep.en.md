---
author: ['derNiklaas', 'RH-sdavey', 'marchersimon']
date: 1633320039
title: "zgrep"
description: "zgrep, Grep text patterns from files within compressed file (equivalent to grep -Z)."
categories: "linux"
---
> More information: <https://manned.org/zgrep>.

- Grep a pattern in a compressed file (case-sensitive):

```bash
zgrep pattern path/to/compressed/file
```

- Grep a pattern in a compressed file (case-insensitive):

```bash
zgrep -i pattern path/to/compressed/file
```

- Output count of lines containing matched pattern in a compressed file:

```bash
zgrep -c pattern path/to/compressed/file
```

- Display the lines which don’t have the pattern present (Invert the search function):

```bash
zgrep -v pattern path/to/compressed/file
```

- Grep a compressed file for multiple patterns:

```bash
zgrep -e "pattern_1" -e "pattern_2" path/to/compressed/file
```

- Use extended regular expressions (supporting `?`, `+`, `{}`, `()` and `|`):

```bash
zgrep -E regular_expression path/to/file
```

- Print 3 lines of [C]ontext around, [B]efore, or [A]fter each match:

```bash
zgrep -C|B|A 3 pattern path/to/compressed/file
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[derNiklaas](mailto:derNiklaas@users.noreply.github.com) | zenity, zgrep, zramctl: add more information link (#6758) | 2021-10-04T06:00:39 | [c05f245fd530](https://github.com/tldr-pages/tldr/commit/c05f245fd530f6134b91568ae3d0181a74c6814b)
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | multiple pages: normalize `regular expression` instead of `regex`, `regexp` or `pattern` (#5830) | 2021-05-10T11:03:12 | [10728f1ab485](https://github.com/tldr-pages/tldr/commit/10728f1ab485957d66af3940a030b0fb77611fc0)
[RH-sdavey](mailto:32485509+RH-sdavey@users.noreply.github.com) | zgrep: add page (#4131) Co-authored-by: Zlatan Vasović <zlatanvasovic@gmail.com> | 2020-07-02T14:22:51 | [d9c7edcc848f](https://github.com/tldr-pages/tldr/commit/d9c7edcc848f41304010f37c76668418bfa51de1)

