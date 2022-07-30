---
author: ['Robert Buchberger', 'lucas schneider', 'Lucas Gabriel Schneider']
date: 1612112718
title: "etckeeper"
description: "etckeeper, Track system configuration files in Git."
categories: "linux"
---
> More information: <http://etckeeper.branchable.com/>.

- Set up a Git repo and perform various setup tasks (run from `/etc`):

```bash
sudo etckeeper init
```

- Commit all changes in `/etc`:

```bash
sudo etckeeper commit message
```

- Run arbitrary Git commands:

```bash
sudo etckeeper vcs status
```

- Check if there are uncommitted changes (only returns an exit code):

```bash
sudo etckeeper unclean
```

- Destroy existing repo and stop tracking changes:

```bash
sudo etckeeper uninit
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Lucas Gabriel Schneider](mailto:casdpa@gmail.com) | multiple pages: format technical tokens (#5119) Co-authored-by: bl-ue <54780737+bl-ue@users.noreply.github.com> Co-authored-by: [...] | 2021-01-31T18:05:18 | [a5fe31bc47ae](https://github.com/tldr-pages/tldr/commit/a5fe31bc47aece3efa5e66b52b3cf384f27d5d72)
[lucas schneider](mailto:casdpa@gmail.com) | rename git to Git | 2021-01-08T14:09:54 | [eef3712fc3a6](https://github.com/tldr-pages/tldr/commit/eef3712fc3a6a3774384b2e4ed934583c8349d75)
[Robert Buchberger](mailto:robert@buchberger.cc) | etckeeper: add page (#3076) | 2019-06-07T12:12:39 | [cce15d0b1a38](https://github.com/tldr-pages/tldr/commit/cce15d0b1a38f22c477fe42e745a356441afbba5)

