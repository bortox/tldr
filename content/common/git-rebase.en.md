---
author: ['Seth Woodworth', 'Waldir Pimenta', 'Agniva De Sarker', 'Marco Bonelli', 'Eliot Sykes', 'Starbeamrainbowlabs', 'Te-Chi Liu', 'Peter Nguyen', 'Quinn Vissak', 'Ruben Vereecken']
date: 1603131961
title: "git rebase"
description: "git rebase, Reapply commits from one branch on top of another branch."
categories: "common"
---
> Commonly used to "move" an entire branch to another base, creating copies of the commits in the new location.

> More information: <https://git-scm.com/docs/git-rebase>.

- Rebase the current branch on top of another specified branch:

```bash
git rebase new_base_branch
```

- Start an interactive rebase, which allows the commits to be reordered, omitted, combined or modified:

```bash
git rebase -i target_base_branch_or_commit_hash
```

- Continue a rebase that was interrupted by a merge failure, after editing conflicting files:

```bash
git rebase --continue
```

- Continue a rebase that was paused due to merge conflicts, by skipping the conflicted commit:

```bash
git rebase --skip
```

- Abort a rebase in progress (e.g. if it is interrupted by a merge conflict):

```bash
git rebase --abort
```

- Move part of the current branch onto a new base, providing the old base to start from:

```bash
git rebase --onto new_base old_base
```

- Reapply the last 5 commits in-place, stopping to allow them to be reordered, omitted, combined or modified:

```bash
git rebase -i HEAD~5
```

- Auto-resolve any conflicts by favoring the working branch version (`theirs` keyword has reversed meaning in this case):

```bash
git rebase -X theirs branch_name
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Starbeamrainbowlabs](mailto:sbrl@starbeamrainbowlabs.com) | git-*: use inclusive language (#4533) * git subtree: make language inclusive * git revert: make language inclusive * git rev-list: [...] | 2020-10-19T20:26:01 | [948bcac65d48](https://github.com/tldr-pages/tldr/commit/948bcac65d48179728f823176fb4f4f7d58c201d)
[Starbeamrainbowlabs](mailto:sbrl@starbeamrainbowlabs.com) | Revert "(chore) replace master/slave with inclusive language (#4459)" (#4532) This reverts commit 44975352462448049b79d323f67337620a4a1740. | 2020-10-06T18:48:57 | [be3998d964be](https://github.com/tldr-pages/tldr/commit/be3998d964be9b7de60ed7b80f6c89264948f710)
[Quinn Vissak](mailto:qvissak@yahoo.com) | (chore) replace master/slave with inclusive language (#4459) | 2020-10-06T16:24:10 | [449753524624](https://github.com/tldr-pages/tldr/commit/44975352462448049b79d323f67337620a4a1740)
[Peter Nguyen](mailto:peter@mictis.com) | git-rebase: Add example with auto-resolve conflicts using merge strategy | 2019-08-12T15:25:16 | [fb01d2daf628](https://github.com/tldr-pages/tldr/commit/fb01d2daf628b07c936b457f7815a775e87e8009)
[Peter Nguyen](mailto:peter@mictis.com) | git-rebase: Add example with --skip option | 2019-08-12T15:25:16 | [df4bae9a5290](https://github.com/tldr-pages/tldr/commit/df4bae9a5290a63aa5ee044a6f5067ce6c7fd7cd)
[Marco Bonelli](mailto:marco@mebeim.net) | Refactor: reword English pages' links' descriptions. | 2019-06-03T14:19:41 | [66abb98ce935](https://github.com/tldr-pages/tldr/commit/66abb98ce935c0f4516bf30c4d6da72180d5a3ab)
[Starbeamrainbowlabs](mailto:sbrl@starbeamrainbowlabs.com) | multiple pages: add homepages (#2660) | 2019-01-30T12:19:23 | [a19866e88add](https://github.com/tldr-pages/tldr/commit/a19866e88addb239484637579b17e7c6ea9b53aa)
[Eliot Sykes](mailto:eliotsykes@gmail.com) | git-rebase: commit hash usage in interactive mode (#2123) | 2018-05-23T23:34:13 | [7acb97fd3c8d](https://github.com/tldr-pages/tldr/commit/7acb97fd3c8db37188b14f0d58a03574949be1ac)
[Agniva De Sarker](mailto:agnivade@yahoo.co.in) | wrapping some items in tokens | 2017-04-26T14:06:01 | [331c97b2093b](https://github.com/tldr-pages/tldr/commit/331c97b2093b089a1c2a497dd5959787842e1948)
[Waldir Pimenta](mailto:waldyrious@gmail.com) | git-rebase: improve desc of second -i example | 2017-04-26T14:06:01 | [4da1c1c3df77](https://github.com/tldr-pages/tldr/commit/4da1c1c3df7719c2ea7454ff388b9e3a36fb3143)
[Waldir Pimenta](mailto:waldyrious@gmail.com) | rephrase --onto example; add in-place rebase | 2017-04-26T14:06:01 | [e8dd7e0b5795](https://github.com/tldr-pages/tldr/commit/e8dd7e0b579542ac294229e61f1780a8aa375343)
[Waldir Pimenta](mailto:waldyrious@gmail.com) | git-rebase: hopefully clarify some points | 2017-04-26T14:06:01 | [8f18647c82bd](https://github.com/tldr-pages/tldr/commit/8f18647c82bd79ac8c6c7d967c1a1bc321b1c88a)
[Te-Chi Liu](mailto:liuderchi@gmail.com) | git-rebase: add --onto option (#1080) | 2016-09-21T08:58:28 | [a6efcb6ba846](https://github.com/tldr-pages/tldr/commit/a6efcb6ba846931bcd96a3bec2a3ff193dfd0590)
[Ruben Vereecken](mailto:rubenvereecken@gmail.com) | Formatted git pages | 2016-01-21T13:08:45 | [d72dea793175](https://github.com/tldr-pages/tldr/commit/d72dea793175ac3b51c4e5c482403fddf8011737)
[Seth Woodworth](mailto:seth.ww@thelevelup.com) | adds more examples for git-rebase | 2015-12-30T19:56:49 | [9c70b752201c](https://github.com/tldr-pages/tldr/commit/9c70b752201cee2fcd1cee5dee0443567b987b4e)
[Seth Woodworth](mailto:seth.ww@thelevelup.com) | Adds documentation for git rebase and git fetch | 2015-12-30T19:54:58 | [1fa146ee3051](https://github.com/tldr-pages/tldr/commit/1fa146ee3051cc2dd2418a78e80bd8d2b8201baf)

