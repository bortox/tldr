---
author: ['CleanMachine1']
date: 1621774024
title: "git effort, TLDR Pages"
description: "git effort, Display how much activity a file has had, showing commits per file and 'active days' i.e. total number of days that contributed to the file."
categories: "common"
---
> Part of `git-extras`.

> More information: <https://github.com/tj/git-extras/blob/master/Commands.md#git-effort>.

- Display each file in the repository, showing commits and active days:

```bash
git effort
```

- Display files modified by a specific number of commits or more, showing commits and active days:

```bash
git effort --above 5
```

- Display files modified by a specific author, showing commits and active days:

```bash
git effort -- --author="username"
```

- Display files modified since a specific time/date, showing commits and active days:

```bash
git effort -- --since="last month"
```

- Display only the specified files or directories, showing commits and active days:

```bash
git effort path/to/file_or_directory1 path/to/file_or_directory2 ...
```

- Display all files in a specific directory, showing commits and active days:

```bash
git effort path/to/directory/*
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[CleanMachine1](mailto:78213164+CleanMachine1@users.noreply.github.com) | git-effort: add page (#6002) | 2021-05-23T14:47:04 | [8a60b2eadd01](https://github.com/tldr-pages/tldr/commit/8a60b2eadd010ebd9d552592719556ecb6130bde)

