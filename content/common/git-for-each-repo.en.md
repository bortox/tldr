---
author: ['Axel Navarro']
date: 1616524149
title: "git for-each-repo"
description: "git for-each-repo, Run a Git command on a list of repositories."
categories: "common"
---
> Note: this command is experimental and may change.

> More information: <https://git-scm.com/docs/git-for-each-repo>.

- Run maintenance on each of a list of repositories stored in the `maintenance.repo` user configuration variable:

```bash
git for-each-repo --config=maintenance.repo maintenance run
```

- Run `git pull` on each repository listed in a global configuration variable:

```bash
git for-each-repo --config=global_configuration_variable pull
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Axel Navarro](mailto:navarroaxel@gmail.com) | git-for-each-repo: add page (#5490) | 2021-03-23T19:29:09 | [5a40dd8341ae](https://github.com/tldr-pages/tldr/commit/5a40dd8341ae2b69384f4033ab8bb9b3abe9a992)

