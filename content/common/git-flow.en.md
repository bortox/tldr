---
author: ['Josip Ledic', 'lucas schneider']
date: 1610111394
title: "git flow, TLDR Pages"
description: "git flow, A collection of Git extensions to provide high-level repository operations."
categories: "common"
---
> More information: <https://github.com/nvie/gitflow>.

- Initialize it inside an existing Git repository:

```bash
git flow init
```

- Start developing on a feature branch based on `develop`:

```bash
git flow feature start feature
```

- Finish development on a feature branch, merging it into the `develop` branch and deleting it:

```bash
git flow feature finish feature
```

- Publish a feature to the remote server:

```bash
git flow feature publish feature
```

- Get a feature published by another user:

```bash
git flow feature pull origin feature
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[lucas schneider](mailto:casdpa@gmail.com) | rename git to Git | 2021-01-08T14:09:54 | [eef3712fc3a6](https://github.com/tldr-pages/tldr/commit/eef3712fc3a6a3774384b2e4ed934583c8349d75)
[Josip Ledic](mailto:ledicjp@gmail.com) | git flow: add page (#3775) * Create git-flow.md * Update pages/common/git-flow.md Co-Authored-By: Iván Hernández Cazorla [...] | 2020-01-31T17:55:57 | [16a1ee56c1e2](https://github.com/tldr-pages/tldr/commit/16a1ee56c1e27ad52c90288aa57e7bd3c78ec13d)

