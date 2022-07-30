---
author: ['Dario Vladović', 'Felix Yan', 'marchersimon']
date: 1617292466
title: "nproc"
description: "nproc, Print the number of processing units (normally CPUs) available."
categories: "common"
---
> More information: <https://www.gnu.org/software/coreutils/nproc>.

- Display the number of available processing units:

```bash
nproc
```

- Display the number of installed processing units, including any inactive ones:

```bash
nproc --all
```

- If possible, subtract a given number of units from the returned value:

```bash
nproc --ignore count
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Dario Vladović](mailto:d.vladimyr@gmail.com) | coreutils*: use short more info links (#5658) | 2021-04-01T17:54:26 | [4830093903f6](https://github.com/tldr-pages/tldr/commit/4830093903f66ccf3ebbc2ecf477286e45edac59)
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | nproc: add more information link (#5618) | 2021-03-30T15:56:51 | [b6dcd8a9122b](https://github.com/tldr-pages/tldr/commit/b6dcd8a9122b443c239adf0727acdc7776a52b38)
[Felix Yan](mailto:felixonmars@archlinux.org) | coreutils commands: move pages to common/ folder (#2442) | 2018-10-16T19:29:50 | [72b4f22ff97b](https://github.com/tldr-pages/tldr/commit/72b4f22ff97b1890344f2af870ad3d1c89a3f0b5)

