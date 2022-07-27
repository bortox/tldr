---
author: ['Stavros Tsourlidakis', 'Dario Vladović', 'Starbeamrainbowlabs', 'Muhammad Falak Reyaz Wani', 'marchersimon']
date: 1617292466
title: "join, TLDR Pages"
description: "join, Join lines of two sorted files on a common field."
categories: "common"
---
> More information: <https://www.gnu.org/software/coreutils/join>.

- Join two files on the first (default) field:

```bash
join file1 file2
```

- Join two files using a comma (instead of a space) as the field separator:

```bash
join -t ',' file1 file2
```

- Join field3 of file1 with field1 of file2:

```bash
join -1 3 -2 1 file1 file2
```

- Produce a line for each unpairable line for file1:

```bash
join -a 1 file1 file2
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Dario Vladović](mailto:d.vladimyr@gmail.com) | coreutils*: use short more info links (#5658) | 2021-04-01T17:54:26 | [4830093903f6](https://github.com/tldr-pages/tldr/commit/4830093903f66ccf3ebbc2ecf477286e45edac59)
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | join: add more information link (#5584) | 2021-03-30T15:31:19 | [a3a1e3033485](https://github.com/tldr-pages/tldr/commit/a3a1e3033485fd9390731e4a70695b62c2c934ee)
[Starbeamrainbowlabs](mailto:sbrl@starbeamrainbowlabs.com) | join: fix articles | 2019-10-30T06:05:45 | [def0f8e64c04](https://github.com/tldr-pages/tldr/commit/def0f8e64c04d69309131db01d24ad9640d480ae)
[Stavros Tsourlidakis](mailto:s.tsourlidakis@hotmail.com) | join: improve formatting | 2019-10-30T06:05:45 | [ca75a21db894](https://github.com/tldr-pages/tldr/commit/ca75a21db8940222f495a803e727797e71fce969)
[Stavros Tsourlidakis](mailto:s.tsourlidakis@hotmail.com) | join: add -t example | 2019-10-30T06:05:45 | [abbc8917def6](https://github.com/tldr-pages/tldr/commit/abbc8917def675a9def980c7ff8064dcabc93e91)
[Muhammad Falak Reyaz Wani](mailto:falakreyaz@gmail.com) | join: add page (#2288) | 2018-09-02T15:53:21 | [e97efdff069b](https://github.com/tldr-pages/tldr/commit/e97efdff069bd74f1200d5596cb804856f925441)

