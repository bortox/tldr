---
author: ['Reinhart Previano Koentjoro', 'Kohei SUGI']
date: 1651488938
title: "gh pr create, TLDR Pages"
description: "gh pr create, Manage GitHub pull requests from the command-line."
categories: "common"
---
> More information: <https://cli.github.com/manual/gh_pr_create>.

- Interactively create a pull request:

```bash
gh pr create
```

- Create a pull request, determining the title and description from the commit messages of the current branch:

```bash
gh pr create --fill
```

- Create a draft pull request:

```bash
gh pr create --draft
```

- Create a pull request specifying the base branch, title, and description:

```bash
gh pr create --base base_branch --title "title" --body "body"
```

- Start opening a pull request in the default web browser:

```bash
gh pr create --web
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Reinhart Previano Koentjoro](mailto:reinhart_previano@yahoo.com) | gh*, glab*: standardize documentation (#7957) | 2022-05-02T12:55:38 | [6ed9681dbcd6](https://github.com/tldr-pages/tldr/commit/6ed9681dbcd680e9529c8238221f7fab9cd2c130)
[Kohei SUGI](mailto:koheisg@hey.com) | gh-pr-create: add page (#6159) | 2021-06-28T21:58:36 | [2afdeff56ffc](https://github.com/tldr-pages/tldr/commit/2afdeff56ffc684eec49505f1476bca88bbbb905)

