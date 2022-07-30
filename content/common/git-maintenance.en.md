---
author: ['Axel Navarro']
date: 1616489881
title: "git-maintenance"
description: "git-maintenance, Run tasks to optimize Git repository data."
categories: "common"
---
> More information: <https://git-scm.com/docs/git-maintenance>.

- Register the current repository in the user's list of repositories to daily have maintenance run:

```bash
git maintenance register
```

- Start running maintenance on the current repository:

```bash
git maintenance start
```

- Halt the background maintenance schedule for the current repository:

```bash
git maintenance stop
```

- Remove the current repository from the user's maintenance repository list:

```bash
git maintenance unregister
```

- Run a specific maintenance task on the current repository:

```bash
git maintenance run --task=commit-graph|gc|incremental-repack|loose-objects|pack-refs|prefetch
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Axel Navarro](mailto:navarroaxel@gmail.com) | git-maintenance: add page (#5463) * git-maintenance: add page * Apply suggestions from code review Co-authored-by: bl-ue <54780737+bl- [...] | 2021-03-23T09:58:01 | [6b1e529662e2](https://github.com/tldr-pages/tldr/commit/6b1e529662e210b8cef74cc4aaa34ff42cb07fbe)

