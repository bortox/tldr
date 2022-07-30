---
author: ['Waldir Pimenta', 'Agniva De Sarker', 'Lucas Gabriel Schneider', 'pxgamer', 'John Kleint', 'Ruben Vereecken']
date: 1612112718
title: "parallel"
description: "parallel, Run commands on multiple CPU cores."
categories: "common"
---
> More information: <https://www.gnu.org/software/parallel>.

- Gzip several files at once, using all cores:

```bash
parallel gzip ::: file1 file2 file3
```

- Read arguments from stdin, run 4 jobs at once:

```bash
ls *.txt | parallel -j4 gzip
```

- Convert JPG images to PNG using replacement strings:

```bash
parallel convert {} {.}.png ::: *.jpg
```

- Parallel xargs, cram as many args as possible onto one command:

```bash
args | parallel -X command
```

- Break stdin into ~1M blocks, feed each block to stdin of new command:

```bash
cat big_file.txt | parallel --pipe --block 1M command
```

- Run on multiple machines via SSH:

```bash
parallel -S machine1,machine2 command ::: arg1 arg2
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Lucas Gabriel Schneider](mailto:casdpa@gmail.com) | multiple pages: format technical tokens (#5119) Co-authored-by: bl-ue <54780737+bl-ue@users.noreply.github.com> Co-authored-by: [...] | 2021-01-31T18:05:18 | [a5fe31bc47ae](https://github.com/tldr-pages/tldr/commit/a5fe31bc47aece3efa5e66b52b3cf384f27d5d72)
[Waldir Pimenta](mailto:waldyrious@gmail.com) | Harmonize formatting and capitalization of stdin/stdout/stderr | 2019-06-17T18:39:58 | [cf25745db1d8](https://github.com/tldr-pages/tldr/commit/cf25745db1d86744c762e15e6a2ba04ef9f9acc1)
[pxgamer](mailto:owzie123@gmail.com) | parallel: add link to homepage | 2019-06-04T21:29:40 | [77bb59c5e2e3](https://github.com/tldr-pages/tldr/commit/77bb59c5e2e34fd1454b7d00bebe11b5fca4fac5)
[Waldir Pimenta](mailto:waldyrious@gmail.com) | page format: lowercase command names consistently (#1083) | 2016-09-22T09:03:38 | [107248374447](https://github.com/tldr-pages/tldr/commit/1072483744475ab5a25c87e8eb7ed10c99dd6ed8)
[Agniva De Sarker](mailto:agnivade@yahoo.co.in) | Applying the snake_case convention throughout the repo (#967) * Applying the snake_case convention throughout the repo - Also removing [...] | 2016-07-22T22:24:06 | [3da76e4150b8](https://github.com/tldr-pages/tldr/commit/3da76e4150b8631fd74aabfcc953cc23731b6bb8)
[Ruben Vereecken](mailto:rubenvereecken@gmail.com) | Formatted all pages according to guidelines. | 2016-01-08T09:38:59 | [066582e8eab5](https://github.com/tldr-pages/tldr/commit/066582e8eab57bce9861cc8d379e158d61f1cc95)
[John Kleint](mailto:jkleint@gmail.com) | Add GNU Parallel | 2015-12-30T05:55:04 | [39df861585ee](https://github.com/tldr-pages/tldr/commit/39df861585ee056ae092e65bbdac2143a04e97d3)

