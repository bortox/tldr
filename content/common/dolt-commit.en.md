---
author: ['bl-ue']
date: 1617094897
title: "dolt commit"
description: "dolt commit, Commit staged changes to tables."
categories: "common"
---
> More information: <https://docs.dolthub.com/interfaces/cli#dolt-commit>.

- Commit all staged changes, opening the editor specified by `$EDITOR` to enter the commit message:

```bash
dolt commit
```

- Commit all staged changes with the specified message:

```bash
dolt commit --message "commit_message"
```

- Stage all unstaged changes to tables before committing:

```bash
dolt commit --all
```

- Use the specified ISO 8601 commit date (defaults to current date and time):

```bash
dolt commit --date "2021-12-31T00:00:00"
```

- Use the specified author for the commit:

```bash
dolt commit --author "author_name <author_email>"
```

- Allow creating an empty commit, with no changes:

```bash
dolt commit --allow-empty
```

- Ignore foreign key warnings:

```bash
dolt commit --force
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | dolt-commit: add page (#5527) * dolt-commit: add page * add example date for clarity | 2021-03-30T11:01:37 | [98470c3b3549](https://github.com/tldr-pages/tldr/commit/98470c3b35494c95586b07cdba1e4fa582ae9f58)

