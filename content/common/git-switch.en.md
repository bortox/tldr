---
author: ['Starbeamrainbowlabs', 'bl-ue', 'Ryan Olson', 'lucas schneider']
date: 1610124748
title: "git switch"
description: "git switch, Switch between Git branches. Requires Git version 2.23+."
categories: "common"
---
> See also `git checkout`.

> More information: <https://git-scm.com/docs/git-switch>.

- Switch to an existing branch:

```bash
git switch branch_name
```

- Create a new branch and switch to it:

```bash
git switch --create branch_name
```

- Create a new branch based on an existing commit and switch to it:

```bash
git switch --create branch_name commit
```

- Switch to the previous branch:

```bash
git switch -
```

- Switch to a branch and update all submodules to match:

```bash
git switch --recurse-submodules branch_name
```

- Switch to a branch and automatically merge the current branch and any uncommitted changes into it:

```bash
git switch --merge branch_name
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | git-switch: fix more information link The old one led to an HTTP 500 because of the trailing /. | 2021-01-08T17:52:28 | [79b1257ea24f](https://github.com/tldr-pages/tldr/commit/79b1257ea24ff4293a7eca44482fa4eb6daf1a61)
[lucas schneider](mailto:casdpa@gmail.com) | rename git to Git | 2021-01-08T14:09:54 | [eef3712fc3a6](https://github.com/tldr-pages/tldr/commit/eef3712fc3a6a3774384b2e4ed934583c8349d75)
[Ryan Olson](mailto:ryanolsonx@gmail.com) | git-switch: switch to previous branch (#3784) | 2020-01-23T11:27:19 | [5eb53e4a7a82](https://github.com/tldr-pages/tldr/commit/5eb53e4a7a82df15b32112024af072ce36ec2606)
[Starbeamrainbowlabs](mailto:sbrl@starbeamrainbowlabs.com) | git-switch: improve wording of example descriptions (#3248) | 2019-08-21T13:44:22 | [1ceef96585f9](https://github.com/tldr-pages/tldr/commit/1ceef96585f9f096913ff3806c632c5fd0bc233f)
[Starbeamrainbowlabs](mailto:sbrl@starbeamrainbowlabs.com) | git-switch: add page (#3246) | 2019-08-19T14:44:48 | [48ce816e6175](https://github.com/tldr-pages/tldr/commit/48ce816e6175dca98b56a2adbcba882e9eb1f093)

