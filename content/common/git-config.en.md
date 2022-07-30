---
author: ['Waldir Pimenta', 'lucas schneider', 'Igor Shubovych', 'Starbeamrainbowlabs', 'Marco Bonelli', 'Ruben Vereecken', 'Matt Watson']
date: 1610111394
title: "git config"
description: "git config, Manage custom configuration options for Git repositories."
categories: "common"
---
> These configurations can be local (for the current repository) or global (for the current user).

> More information: <https://git-scm.com/docs/git-config>.

- List only local configuration entries (stored in `.git/config` in the current repository):

```bash
git config --list --local
```

- List only global configuration entries (stored in `~/.gitconfig`):

```bash
git config --list --global
```

- List all configuration entries that have been defined either locally or globally:

```bash
git config --list
```

- Get the value of a given configuration entry:

```bash
git config alias.unstage
```

- Set the global value of a given configuration entry:

```bash
git config --global alias.unstage "reset HEAD --"
```

- Revert a global configuration entry to its default value:

```bash
git config --global --unset alias.unstage
```

- Edit the Git configuration for the current repository in the default editor:

```bash
git config --edit
```

- Edit the global Git configuration in the default editor:

```bash
git config --global --edit
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[lucas schneider](mailto:casdpa@gmail.com) | rename git to Git | 2021-01-08T14:09:54 | [eef3712fc3a6](https://github.com/tldr-pages/tldr/commit/eef3712fc3a6a3774384b2e4ed934583c8349d75)
[Matt Watson](mailto:matthew.watson1990@googlemail.com) | git-config: add example for editing in default editor (#4176) Co-authored-by: Starbeamrainbowlabs <sbrl@starbeamrainbowlabs.com> | 2020-07-17T19:40:48 | [01d22cdbc9f6](https://github.com/tldr-pages/tldr/commit/01d22cdbc9f678e08171e941c70d978e4354e812)
[Marco Bonelli](mailto:marco@mebeim.net) | Refactor: reword English pages' links' descriptions. | 2019-06-03T14:19:41 | [66abb98ce935](https://github.com/tldr-pages/tldr/commit/66abb98ce935c0f4516bf30c4d6da72180d5a3ab)
[Starbeamrainbowlabs](mailto:sbrl@starbeamrainbowlabs.com) | multiple pages: add homepages (#2660) | 2019-01-30T12:19:23 | [a19866e88add](https://github.com/tldr-pages/tldr/commit/a19866e88addb239484637579b17e7c6ea9b53aa)
[Waldir Pimenta](mailto:waldyrious@gmail.com) | git-config: overhaul page (#1402) - expand description of local and global options - adjust example descriptions for clarity - change [...] | 2017-06-16T00:30:21 | [87fb4e13bdcd](https://github.com/tldr-pages/tldr/commit/87fb4e13bdcd58a465ab2dd7e859e778389d1cab)
[Ruben Vereecken](mailto:rubenvereecken@gmail.com) | Formatted all pages according to guidelines. | 2016-01-08T09:38:59 | [066582e8eab5](https://github.com/tldr-pages/tldr/commit/066582e8eab57bce9861cc8d379e158d61f1cc95)
[Igor Shubovych](mailto:igor.shubovych@gmail.com) | git-config: add page | 2015-12-17T16:58:27 | [13740e2fd932](https://github.com/tldr-pages/tldr/commit/13740e2fd9328fb06a15e0d7d6dcc7b9b2b1eddf)

