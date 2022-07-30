---
author: ['Daniel S Poulin', 'Ivan Aracki', 'Marco Bonelli']
date: 1563796756
title: "git-grep"
description: "git-grep, Find strings inside files anywhere in a repository's history."
categories: "common"
---
> Accepts a lot of the same flags as regular `grep`.

> More information: <https://git-scm.com/docs/git-grep>.

- Search for a string in tracked files:

```bash
git grep search_string
```

- Search for a string in files matching a pattern in tracked files:

```bash
git grep search_string -- file_glob_pattern
```

- Search for a string in tracked files, including submodules:

```bash
git grep --recurse-submodules search_string
```

- Search for a string at a specific point in history:

```bash
git grep search_string HEAD~2
```

- Search for a string across all branches:

```bash
git grep search_string $(git rev-list --all)
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Ivan Aracki](mailto:aracki.ivan@gmail.com) | git-grep: add new example (#3203) | 2019-07-22T13:59:16 | [41d82606b579](https://github.com/tldr-pages/tldr/commit/41d82606b5791ec1c67bb770dca61693ffd7420d)
[Marco Bonelli](mailto:marco@mebeim.net) | Refactor: reword English pages' links' descriptions. | 2019-06-03T14:19:41 | [66abb98ce935](https://github.com/tldr-pages/tldr/commit/66abb98ce935c0f4516bf30c4d6da72180d5a3ab)
[Daniel S Poulin](mailto:crimsonmage+github@gmail.com) | git grep: add page (#2833) | 2019-04-05T12:53:13 | [0eef8fc994de](https://github.com/tldr-pages/tldr/commit/0eef8fc994de8a65f856dd2d9d9d5c67bc691736)

