---
author: ['ruru4143', 'Seth Falco']
date: 1629050349
title: "topydo, TLDR Pages"
description: "topydo, A to-do list application that uses the todo.txt format."
categories: "common"
---
> More information: <https://github.com/topydo/topydo>.

- Add a to-do to a specific project with a given context:

```bash
topydo add "todo_message +project_name @context_name"
```

- Add a to-do with a due date of tomorrow with a priority of `A`:

```bash
topydo add "(A) todo _message due:1d"
```

- Add a to-do with a due date of Friday:

```bash
topydo add "todo_message due:fri"
```

- Add a non-strict repeating to-do (next due = now + rec):

```bash
topydo add "water flowers due:mon rec:1w"
```

- Add a strict repeating to-do (next due = current due + rec):

```bash
topydo add "todo_message due:2020-01-01 rec:+1m"
```

- Revert the last `topydo` command executed:

```bash
topydo revert
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Seth Falco](mailto:seth@falco.fun) | *: fix errors reported by languagetool (#6069) | 2021-08-15T19:59:09 | [3e4c519004a4](https://github.com/tldr-pages/tldr/commit/3e4c519004a471c861cdc609fd7239ee3355671c)
[ruru4143](mailto:37406068+ruru4143@users.noreply.github.com) | topydo: add page (#5017) | 2020-12-19T20:07:28 | [f7a116929cac](https://github.com/tldr-pages/tldr/commit/f7a116929caca1d82c7d744916d6339bf8abfe04)

