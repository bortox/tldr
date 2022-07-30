---
author: ['Pelle Jacobs', 'pxgamer', 'ptzz', 'Seth Falco']
date: 1629050349
title: "fswatch"
description: "fswatch, A cross-platform file change monitor."
categories: "common"
---
> More information: <https://emcrisostomo.github.io/fswatch>.

- Run a Bash command on file creation, update or deletion:

```bash
fswatch path/to/file | xargs -n 1 bash_command
```

- Watch one or more files and/or directories:

```bash
fswatch path/to/file path/to/directory path/to/another_directory/**/*.js | xargs -n 1 bash_command
```

- Print the absolute paths of the changed files:

```bash
fswatch path/to/directory | xargs -n 1 -I {} echo {}
```

- Filter by event type:

```bash
fswatch --event Updated|Deleted|Created path/to/directory | xargs -n 1 bash_command
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Seth Falco](mailto:seth@falco.fun) | *: fix errors reported by languagetool (#6069) | 2021-08-15T19:59:09 | [3e4c519004a4](https://github.com/tldr-pages/tldr/commit/3e4c519004a471c861cdc609fd7239ee3355671c)
[pxgamer](mailto:owzie123@gmail.com) | fswatch: add link to homepage | 2019-06-07T23:58:59 | [2e786797125a](https://github.com/tldr-pages/tldr/commit/2e786797125ad889d6d54184fa9ce40294f827ed)
[ptzz](mailto:ptzzptzzp@gmail.com) | fswatch: Fix broken commands + simplifications Without the `-n 1` argument to `xargs`, fswatch will will not trigger on events. | 2018-05-24T07:46:16 | [44c201c7a727](https://github.com/tldr-pages/tldr/commit/44c201c7a727406c09289edf07e7236ab0cb70db)
[Pelle Jacobs](mailto:pelle.jacobs@novicap.com) | Create fswatch.md (#1005) * Create fswatch.md * Update fswatch.md * Update fswatch.md * Update fswatch.md * Update fswatch.md * Update [...] | 2016-08-21T13:03:49 | [3babe7cebce8](https://github.com/tldr-pages/tldr/commit/3babe7cebce8644dccd2641b9ac22801507422e3)

