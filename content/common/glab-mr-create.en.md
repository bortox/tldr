---
author: ['Reinhart Previano Koentjoro']
date: 1641914987
title: "glab mr create"
description: "glab mr create, Manage GitLab merge requests from the command-line."
categories: "common"
---
> More information: <https://glab.readthedocs.io/en/latest/mr/create.html>.

- Interactively create a merge request:

```bash
glab mr create
```

- Create a merge request, determining the title and description from the commit messages of the current branch:

```bash
glab mr create --fill
```

- Create a draft merge request:

```bash
glab mr create --draft
```

- Create a merge request specifying the target branch, title, and description:

```bash
glab mr create --target-branch target_branch --title "title" --description "description"
```

- Start opening a merge request in the default web browser:

```bash
glab mr create --web
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Reinhart Previano Koentjoro](mailto:reinhart_previano@yahoo.com) | glab-mr*: add pages (#7635) | 2022-01-11T16:29:47 | [285609b2399b](https://github.com/tldr-pages/tldr/commit/285609b2399b62b066295a89b4844c83d376af6d)

