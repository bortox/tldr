---
author: ['Seth Falco', 'bl-ue', 'Moti Korets', 'git-em']
date: 1646800137
title: "atq"
description: "atq, Show jobs scheduled by `at` or `batch` commands."
categories: "common"
---
> More information: <https://manned.org/atq>.

- Show the current user's scheduled jobs:

```bash
atq
```

- Show jobs from queue named 'a' (queues have single-character names):

```bash
atq -q a
```

- Show jobs of all users (run as superuser):

```bash
sudo atq
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[git-em](mailto:56173216+git-em@users.noreply.github.com) | common/*: replace man.archlinux.org (#7860) | 2022-03-09T05:28:57 | [a48819f19092](https://github.com/tldr-pages/tldr/commit/a48819f19092a82a1faef1f9f105bc1eb27d2df7)
[Seth Falco](mailto:seth@falco.fun) | *: fix errors reported by languagetool (#6069) | 2021-08-15T19:59:09 | [3e4c519004a4](https://github.com/tldr-pages/tldr/commit/3e4c519004a471c861cdc609fd7239ee3355671c)
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | at, atq, atrm, batch: add more information link (#5640) | 2021-03-30T21:01:46 | [f1da7db16065](https://github.com/tldr-pages/tldr/commit/f1da7db160655446057cf641b5339d2e9273bb7a)
[Moti Korets](mailto:moti@practitest.com) | at: add page, atq: add page, atrm: add page, and batch: add page (#1344) commands to queue commands execution at specified time or [...] | 2017-05-01T12:06:06 | [2f03bc1362f0](https://github.com/tldr-pages/tldr/commit/2f03bc1362f0eb861cc3a1c4abbd4bce546b8994)

