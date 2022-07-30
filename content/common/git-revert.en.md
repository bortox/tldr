---
author: ['Starbeamrainbowlabs', 'Quinn Vissak', 'Andrew McIntosh', 'Robert Buchberger']
date: 1633114028
title: "git revert"
description: "git revert, Create new commits which reverse the effect of earlier ones."
categories: "common"
---
> More information: <https://git-scm.com/docs/git-revert>.

- Revert the most recent commit:

```bash
git revert HEAD
```

- Revert the 5th last commit:

```bash
git revert HEAD~4
```

- Revert multiple commits:

```bash
git revert branch_name~5..branch_name~2
```

- Don't create new commits, just change the working tree:

```bash
git revert -n 0c01a9..9a1743
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Andrew McIntosh](mailto:amcintosh@users.noreply.github.com) | git-revert: use HEAD in example (#6649) | 2021-10-01T20:47:08 | [55ec5b50d3f5](https://github.com/tldr-pages/tldr/commit/55ec5b50d3f56667aab8fbf89e61a8aa899fbbba)
[Starbeamrainbowlabs](mailto:sbrl@starbeamrainbowlabs.com) | git-*: use inclusive language (#4533) * git subtree: make language inclusive * git revert: make language inclusive * git rev-list: [...] | 2020-10-19T20:26:01 | [948bcac65d48](https://github.com/tldr-pages/tldr/commit/948bcac65d48179728f823176fb4f4f7d58c201d)
[Starbeamrainbowlabs](mailto:sbrl@starbeamrainbowlabs.com) | Revert "(chore) replace master/slave with inclusive language (#4459)" (#4532) This reverts commit 44975352462448049b79d323f67337620a4a1740. | 2020-10-06T18:48:57 | [be3998d964be](https://github.com/tldr-pages/tldr/commit/be3998d964be9b7de60ed7b80f6c89264948f710)
[Quinn Vissak](mailto:qvissak@yahoo.com) | (chore) replace master/slave with inclusive language (#4459) | 2020-10-06T16:24:10 | [449753524624](https://github.com/tldr-pages/tldr/commit/44975352462448049b79d323f67337620a4a1740)
[Robert Buchberger](mailto:robert@buchberger.cc) | git-revert: add page (#3151) | 2019-07-01T00:25:31 | [13a11782e80a](https://github.com/tldr-pages/tldr/commit/13a11782e80a47bb0c8dcc9784c704fd444f51ce)

