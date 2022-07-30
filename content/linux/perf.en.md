---
author: ['Emanuele Rocca', 'Lucas Gabriel Schneider', 'Seth Falco', 'Muhammad Falak R Wani']
date: 1635247183
title: "perf"
description: "perf, Framework for Linux performance counter measurements."
categories: "linux"
---
> More information: <https://perf.wiki.kernel.org>.

- Display basic performance counter stats for a command:

```bash
perf stat gcc hello.c
```

- Display system-wide real-time performance counter profile:

```bash
sudo perf top
```

- Run a command and record its profile into `perf.data`:

```bash
sudo perf record command
```

- Record the profile of an existing process into `perf.data`:

```bash
sudo perf record -p pid
```

- Read `perf.data` (created by `perf record`) and display the profile:

```bash
sudo perf report
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Emanuele Rocca](mailto:ema@linux.it) | perf: add link and -p example (#7229) | 2021-10-26T13:19:43 | [5890df364101](https://github.com/tldr-pages/tldr/commit/5890df364101d3250f4f5a2aeb5c9da9b4c95fb9)
[Seth Falco](mailto:seth@falco.fun) | *: fix errors reported by languagetool (#6069) | 2021-08-15T19:59:09 | [3e4c519004a4](https://github.com/tldr-pages/tldr/commit/3e4c519004a471c861cdc609fd7239ee3355671c)
[Lucas Gabriel Schneider](mailto:casdpa@gmail.com) | multiple pages: format technical tokens (#5119) Co-authored-by: bl-ue <54780737+bl-ue@users.noreply.github.com> Co-authored-by: [...] | 2021-01-31T18:05:18 | [a5fe31bc47ae](https://github.com/tldr-pages/tldr/commit/a5fe31bc47aece3efa5e66b52b3cf384f27d5d72)
[Muhammad Falak R Wani](mailto:falakreyaz@gmail.com) | perf: make the example simpler | 2017-10-21T15:05:17 | [741fcf1b5821](https://github.com/tldr-pages/tldr/commit/741fcf1b5821d694868586051630fe2582675bb0)
[Muhammad Falak R Wani](mailto:falakreyaz@gmail.com) | perf: resolve review comments | 2017-10-21T12:37:00 | [84bcef29a17d](https://github.com/tldr-pages/tldr/commit/84bcef29a17d817f7a4f14cbd3ee1447ff702a8f)
[Muhammad Falak R Wani](mailto:falakreyaz@gmail.com) | perf: add page (#1556) | 2017-10-20T19:44:29 | [209fcdad91f4](https://github.com/tldr-pages/tldr/commit/209fcdad91f4d18b87e19787a6c6919fc4c2c191)

