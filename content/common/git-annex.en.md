---
author: ['nath1as', 'lucas schneider']
date: 1610111394
title: "git annex, TLDR Pages"
description: "git annex, Manage files with Git, without checking their contents in."
categories: "common"
---
> When a file is annexed, its content is moved into a key-value store, and a symlink is made that points to the content.

> More information: <https://git-annex.branchable.com>.

- Help:

```bash
git annex help
```

- Initialize a repo with Git annex:

```bash
git annex init
```

- Add a file:

```bash
git annex add path/to/file_or_directory
```

- Show the current status of a file or directory:

```bash
git annex status path/to/file_or_directory
```

- Synchronize a local repository with a remote:

```bash
git annex remote
```

- Get a file or directory:

```bash
git annex get path/to/file_or_directory
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[lucas schneider](mailto:casdpa@gmail.com) | rename git to Git | 2021-01-08T14:09:54 | [eef3712fc3a6](https://github.com/tldr-pages/tldr/commit/eef3712fc3a6a3774384b2e4ed934583c8349d75)
[nath1as](mailto:n@th1.as) | git-annex: add page (#4421) | 2020-10-06T13:53:35 | [68015e4699a5](https://github.com/tldr-pages/tldr/commit/68015e4699a54c792c04386e34d5062874c2686b)

