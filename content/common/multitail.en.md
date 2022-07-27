---
author: ['Lars Henrik Bolstad', 'marchersimon']
date: 1625253777
title: "multitail, TLDR Pages"
description: "multitail, Extension of tail."
categories: "common"
---
> More information: <https://manned.org/multitail>.

- Tail all files matching a pattern in a single stream:

```bash
multitail -Q 1 'pattern'
```

- Tail all files in a directory in a single stream:

```bash
multitail -Q 1 'directory/*'
```

- Automatically add new files to a window:

```bash
multitail -Q pattern
```

- Show 5 logfiles while merging 2 and put them in 2 columns with only one in the left column:

```bash
multitail -s 2 -sn 1,3 mergefile -I file1 file2 file3 file4
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | *: replace dead more information links (#5724) | 2021-07-02T21:22:57 | [6534b52a2ec9](https://github.com/tldr-pages/tldr/commit/6534b52a2ec92c1e691e21901799048c40b069db)
[Lars Henrik Bolstad](mailto:lahebo@gmail.com) | multitail: add page (#3604) | 2019-11-30T15:15:05 | [2a613d6a397d](https://github.com/tldr-pages/tldr/commit/2a613d6a397d47777a27ec1d899bb12f1c78f610)

