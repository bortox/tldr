---
author: ['Waldir Pimenta', 'Ruben Vereecken', 'Agniva De Sarker', 'Martin Czygan', 'Dario Vladović', 'Lucas Gabriel Schneider', 'marchersimon']
date: 1617292466
title: "comm, TLDR Pages"
description: "comm, Select or reject lines common to two files. Both files must be sorted."
categories: "common"
---
> More information: <https://www.gnu.org/software/coreutils/comm>.

- Produce three tab-separated columns: lines only in first file, lines only in second file and common lines:

```bash
comm file1 file2
```

- Print only lines common to both files:

```bash
comm -12 file1 file2
```

- Print only lines common to both files, reading one file from stdin:

```bash
cat file1 | comm -12 - file2
```

- Get lines only found in first file, saving the result to a third file:

```bash
comm -23 file1 file2 > file1_only
```

- Print lines only found in second file, when the files aren't sorted:

```bash
comm -13 <(sort file1) <(sort file2)
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Dario Vladović](mailto:d.vladimyr@gmail.com) | coreutils*: use short more info links (#5658) | 2021-04-01T17:54:26 | [4830093903f6](https://github.com/tldr-pages/tldr/commit/4830093903f66ccf3ebbc2ecf477286e45edac59)
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | comm: add link (#5574) | 2021-03-30T13:45:00 | [d2f1b60f45aa](https://github.com/tldr-pages/tldr/commit/d2f1b60f45aa596ac50271f9f18ad69817e3eb26)
[Lucas Gabriel Schneider](mailto:casdpa@gmail.com) | multiple pages: format technical tokens (#5119) Co-authored-by: bl-ue <54780737+bl-ue@users.noreply.github.com> Co-authored-by: [...] | 2021-01-31T18:05:18 | [a5fe31bc47ae](https://github.com/tldr-pages/tldr/commit/a5fe31bc47aece3efa5e66b52b3cf384f27d5d72)
[Waldir Pimenta](mailto:waldyrious@gmail.com) | Harmonize formatting and capitalization of stdin/stdout/stderr | 2019-06-17T18:39:58 | [cf25745db1d8](https://github.com/tldr-pages/tldr/commit/cf25745db1d86744c762e15e6a2ba04ef9f9acc1)
[Agniva De Sarker](mailto:agnivade@yahoo.co.in) | Applying the snake_case convention throughout the repo (#967) * Applying the snake_case convention throughout the repo - Also removing [...] | 2016-07-22T22:24:06 | [3da76e4150b8](https://github.com/tldr-pages/tldr/commit/3da76e4150b8631fd74aabfcc953cc23731b6bb8)
[Waldir Pimenta](mailto:waldyrious@gmail.com) | make the last examples more useful (#858) Output to file and sort files. | 2016-05-09T15:17:43 | [d95b01fcd1d1](https://github.com/tldr-pages/tldr/commit/d95b01fcd1d1ed9d24de82ccf3c5820f5896734f)
[Ruben Vereecken](mailto:rubenvereecken@gmail.com) | Formatted all pages according to guidelines. | 2016-01-08T09:38:59 | [066582e8eab5](https://github.com/tldr-pages/tldr/commit/066582e8eab57bce9861cc8d379e158d61f1cc95)
[Martin Czygan](mailto:martin.czygan@gmail.com) | add comm command | 2015-12-29T18:40:43 | [459771a45a17](https://github.com/tldr-pages/tldr/commit/459771a45a171897d4378b2e916cb0746eacb2fc)

