---
author: ['Florian B']
date: 1623436519
title: "git daemon"
description: "git daemon, A really simple server for Git repositories."
categories: "common"
---
> More information: <https://git-scm.com/docs/git-daemon>.

- Launch a Git daemon with a whitelisted set of directories:

```bash
git daemon --export-all path/to/directory1 path/to/directory2
```

- Launch a Git daemon with a specific base directory and allow pulling from all sub-directories that look like Git repositories:

```bash
git daemon --base-path=path/to/directory --export-all --reuseaddr
```

- Launch a Git daemon for the specified directory, verbosely printing log messages and allowing Git clients to write to it:

```bash
git daemon path/to/directory --enable=receive-pack --informative-errors --verbose
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Florian B](mailto:gn0mish@protonmail.com) | git-daemon: add page (#5938) | 2021-06-11T20:35:19 | [87004beb0e32](https://github.com/tldr-pages/tldr/commit/87004beb0e32ed610acdf0ee9a7df4c30c6e1d41)

