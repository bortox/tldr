---
author: ['JaiJoshi123']
date: 1630708874
title: "git bug"
description: "git bug, A distributed bug tracker that uses git's internal storage, so no files are added in your project."
categories: "common"
---
> You may submit your problems to the same git remote you use to interact with others, much like commits and branches.

> More information: <https://github.com/MichaelMure/git-bug/blob/master/doc/md/git-bug.md>.

- Create a new identity:

```bash
git bug user create
```

- Create a new bug:

```bash
git bug add
```

- You can push your new entry to a remote:

```bash
git bug push
```

- You can pull for updates:

```bash
git bug pull
```

- List existing bugs:

```bash
git bug ls
```

- Filter and sort bugs using a query:

```bash
git bug ls "status:open sort:edit"
```

- Search for bugs by text content:

```bash
git bug ls "search_query" baz
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[JaiJoshi123](mailto:64401010+JaiJoshi123@users.noreply.github.com) | git-bug, git-cola, gitlint: add page (#6444) | 2021-09-04T00:41:14 | [ac40409bbee8](https://github.com/tldr-pages/tldr/commit/ac40409bbee87256b81e82274299e769e7e5e2d5)

