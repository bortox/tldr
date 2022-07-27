---
author: ['Chuancong Gao', 'Ruben Vereecken', 'Dario Vladović', 'marchersimon']
date: 1617292466
title: "paste, TLDR Pages"
description: "paste, Merge lines of files."
categories: "common"
---
> More information: <https://www.gnu.org/software/coreutils/paste>.

- Join all the lines into a single line, using TAB as delimiter:

```bash
paste -s file
```

- Join all the lines into a single line, using the specified delimiter:

```bash
paste -s -d delimiter file
```

- Merge two files side by side, each in its column, using TAB as delimiter:

```bash
paste file1 file2
```

- Merge two files side by side, each in its column, using the specified delimiter:

```bash
paste -d delimiter file1 file2
```

- Merge two files, with lines added alternatively:

```bash
paste -d '\n' file1 file2
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Dario Vladović](mailto:d.vladimyr@gmail.com) | coreutils*: use short more info links (#5658) | 2021-04-01T17:54:26 | [4830093903f6](https://github.com/tldr-pages/tldr/commit/4830093903f66ccf3ebbc2ecf477286e45edac59)
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | paste: add more information link (#5588) | 2021-03-30T16:00:11 | [020d97eddae1](https://github.com/tldr-pages/tldr/commit/020d97eddae18a532aeb0b6466855aeea3a11a74)
[Ruben Vereecken](mailto:rubenvereecken@gmail.com) | Formatted all pages according to guidelines. | 2016-01-08T09:38:59 | [066582e8eab5](https://github.com/tldr-pages/tldr/commit/066582e8eab57bce9861cc8d379e158d61f1cc95)
[Chuancong Gao](mailto:chuanconggao@users.noreply.github.com) | paste: add page | 2015-12-30T04:41:32 | [ea1c76213a0a](https://github.com/tldr-pages/tldr/commit/ea1c76213a0a3325ad947f10aaf7f189391ae389)

