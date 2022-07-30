---
author: ['Florian B']
date: 1624457048
title: "git show-index"
description: "git show-index, Show the packed archive index of a Git repository."
categories: "common"
---
> More information: <https://git-scm.com/docs/git-show-index>.

- Read an IDX file for a Git packfile and dump its contents to stdout:

```bash
git show-index path/to/file.idx
```

- Specify the hash algorithm for the index file (experimental):

```bash
git show-index --object-format=sha1|sha256 path/to/file
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Florian B](mailto:gn0mish@protonmail.com) | git-show-index: add page (#5940) | 2021-06-23T16:04:08 | [4d63c004ee75](https://github.com/tldr-pages/tldr/commit/4d63c004ee7514c2b30ae2ccd581c2f3b5e5c56d)

