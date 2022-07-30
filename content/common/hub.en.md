---
author: ['Bruno Paz', 'Waldir Pimenta', 'lucas schneider', 'Eric Nielsen', 'Nicolas Kosinski', 'pxgamer', 'Naoya Yamashita']
date: 1624302381
title: "hub"
description: "hub, A wrapper for Git that adds commands for working with GitHub-based projects."
categories: "common"
---
> If set up as instructed by `hub alias`, one can use `git` to run `hub` commands.

> More information: <https://hub.github.com>.

- Clone a repository using its slug (owners can omit the username):

```bash
hub clone username/repo_name
```

- Create a fork of the current repository (cloned from another user) under your GitHub profile:

```bash
hub fork
```

- Push the current local branch to GitHub and create a PR for it in the original repository:

```bash
hub push remote_name && hub pull-request
```

- Create a PR of the current (already pushed) branch, reusing the message from the first commit:

```bash
hub pull-request --no-edit
```

- Create a new branch with the contents of a pull request and switch to it:

```bash
hub pr checkout pr_number
```

- Upload the current (local-only) repository to your GitHub account:

```bash
hub create
```

- Fetch Git objects from upstream and update local branches:

```bash
hub sync
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Nicolas Kosinski](mailto:nicokosi@yahoo.com) | hub: add sync example (#6108) | 2021-06-21T21:06:21 | [8f9e3caf2954](https://github.com/tldr-pages/tldr/commit/8f9e3caf2954ba0a3da3e16047dc0eb482f0b048)
[lucas schneider](mailto:casdpa@gmail.com) | rename git to Git | 2021-01-08T14:09:54 | [eef3712fc3a6](https://github.com/tldr-pages/tldr/commit/eef3712fc3a6a3774384b2e4ed934583c8349d75)
[lucas schneider](mailto:casdpa@gmail.com) | rename github to GitHub | 2021-01-07T23:11:37 | [1490bac06638](https://github.com/tldr-pages/tldr/commit/1490bac06638cdd33f5b29a3091b27bb20f3683f)
[Waldir Pimenta](mailto:waldyrious@gmail.com) | hub: fix instructions for aliasing the command (#3597) | 2019-11-22T02:35:56 | [e4161ff34f74](https://github.com/tldr-pages/tldr/commit/e4161ff34f74410176d17af427fcfd698b6bd9e8)
[Naoya Yamashita](mailto:conao3@gmail.com) | hub: add hub pr usage for checkout someone created pull-request (#3170) | 2019-07-05T23:06:57 | [4b911f1315f4](https://github.com/tldr-pages/tldr/commit/4b911f1315f4deca9a084db88afc8677183fdfbd)
[pxgamer](mailto:owzie123@gmail.com) | hub: add link to homepage | 2019-06-07T23:58:59 | [aa0df0442191](https://github.com/tldr-pages/tldr/commit/aa0df0442191673b8e0326137cd4912c1e985569)
[Waldir Pimenta](mailto:waldyrious@gmail.com) | hub: improve pull request examples - Add `push` command to the pull-request example - add a new example demonstrating the `--no-edit` option | 2019-01-05T06:16:24 | [8d671b6240e7](https://github.com/tldr-pages/tldr/commit/8d671b6240e7652993b86eac26afade0c63df35c)
[Waldir Pimenta](mailto:waldyrious@gmail.com) | hub: adjust descriptions for additional clarity (#1217) | 2017-01-02T19:36:06 | [ddf43daa4c02](https://github.com/tldr-pages/tldr/commit/ddf43daa4c025356f098f49fd8220ab7e2b2e352)
[Waldir Pimenta](mailto:waldyrious@gmail.com) | hub: overhaul the page for improved clarity (#1202) - make main description and command descriptions more specific - simplify the fork [...] | 2016-12-22T00:01:21 | [9a0a0335d66c](https://github.com/tldr-pages/tldr/commit/9a0a0335d66c8fbdcf0435b37835dd988f883e25)
[Eric Nielsen](mailto:eric@amalgamar.com.br) | hub: Further improve examples verbosity | 2016-09-22T23:33:58 | [672addab2125](https://github.com/tldr-pages/tldr/commit/672addab21252916af96793db79ce5cdb9cd3eeb)
[Eric Nielsen](mailto:eric@amalgamar.com.br) | hub: Improve examples verbosity | 2016-09-10T19:29:39 | [6b3bfccdcece](https://github.com/tldr-pages/tldr/commit/6b3bfccdcece26372a66a555ee12374599531482)
[Eric Nielsen](mailto:eric@amalgamar.com.br) | hub: Add fork and pull-request examples - Examples follow clone examples as a logical sequence - Pull-request example stresses that [...] | 2016-09-09T18:18:38 | [5e56f2a88624](https://github.com/tldr-pages/tldr/commit/5e56f2a88624a341dd50df22f3fb5666c811866a)
[Bruno Paz](mailto:brunopaz@sapo.pt) | Remove spaces from variable names | 2016-02-15T23:12:54 | [23a4b75bed8a](https://github.com/tldr-pages/tldr/commit/23a4b75bed8adfa80107acfd6730ac427728e37f)
[Bruno Paz](mailto:brunopaz@sapo.pt) | Add hub command | 2016-02-15T21:09:51 | [e9fe45d2f94a](https://github.com/tldr-pages/tldr/commit/e9fe45d2f94a081ba4c2aae44e74fb4633604522)

