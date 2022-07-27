---
author: ['Marco Bonelli', 'Waldir Pimenta', 'Starbeamrainbowlabs', 'lucas schneider']
date: 1610111394
title: "gitsome, TLDR Pages"
description: "gitsome, A terminal-based interface for GitHub, accessed via the `gh` command."
categories: "common"
---
> It also provides menu-style autocomplete suggestions for `git` commands.

> More information: <https://github.com/donnemartin/gitsome>.

- Enter the gitsome shell (optional), to enable autocompletion and interactive help for Git (and gh) commands:

```bash
gitsome
```

- Setup GitHub integration with the current account:

```bash
gh configure
```

- List notifications for the current account (as would be seen in https://github.com/notifications):

```bash
gh notifications
```

- List the current account's starred repos, filtered by a given search string:

```bash
gh starred "python 3"
```

- View the recent activity feed of a given GitHub repository:

```bash
gh feed tldr-pages/tldr
```

- View the recent activity feed for a given GitHub user, using the default pager (e.g. `less`):

```bash
gh feed torvalds -p
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[lucas schneider](mailto:casdpa@gmail.com) | rename git to Git | 2021-01-08T14:09:54 | [eef3712fc3a6](https://github.com/tldr-pages/tldr/commit/eef3712fc3a6a3774384b2e4ed934583c8349d75)
[Marco Bonelli](mailto:marco@mebeim.net) | Refactor: reword English pages' links' descriptions. | 2019-06-03T14:19:41 | [66abb98ce935](https://github.com/tldr-pages/tldr/commit/66abb98ce935c0f4516bf30c4d6da72180d5a3ab)
[Starbeamrainbowlabs](mailto:sbrl@starbeamrainbowlabs.com) | multiple pages: add homepages (#2660) | 2019-01-30T12:19:23 | [a19866e88add](https://github.com/tldr-pages/tldr/commit/a19866e88addb239484637579b17e7c6ea9b53aa)
[Waldir Pimenta](mailto:waldyrious@gmail.com) | gitsome: add page (#1214) | 2016-12-28T16:19:53 | [d668c9e788c1](https://github.com/tldr-pages/tldr/commit/d668c9e788c1dbb16be2a5fd9487ffd869a8f9a1)

