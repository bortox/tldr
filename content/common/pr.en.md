---
author: ['Dario Vladović', 'Joshua']
date: 1617292466
title: "pr, TLDR Pages"
description: "pr, Paginate or columnate files for printing."
categories: "common"
---
> More information: <https://www.gnu.org/software/coreutils/pr>.

- Print multiple files with a default header and footer:

```bash
pr file1 file2 file3
```

- Print with a custom centered header:

```bash
pr -h "header" file1 file2 file3
```

- Print with numbered lines and a custom date format:

```bash
pr -n -D "format" file1 file2 file3
```

- Print all files together, one in each column, without a header or footer:

```bash
pr -m -T file1 file2 file3
```

- Print, beginning at page 2 up to page 5, with a given page length (including header and footer):

```bash
pr +2:5 -l page_length file1 file2 file3
```

- Print with an offset for each line and a truncating custom page width:

```bash
pr -o offset -W width file1 file2 file3
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Dario Vladović](mailto:d.vladimyr@gmail.com) | coreutils*: use short more info links (#5658) | 2021-04-01T17:54:26 | [4830093903f6](https://github.com/tldr-pages/tldr/commit/4830093903f66ccf3ebbc2ecf477286e45edac59)
[Joshua](mailto:Joshua.Doll@online.de) | pr: add page (#3412) | 2019-10-19T17:54:59 | [053569b9d441](https://github.com/tldr-pages/tldr/commit/053569b9d4419c113aa4f86f61184c33cedcbcca)

