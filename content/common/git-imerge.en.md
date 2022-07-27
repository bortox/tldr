---
author: ['Marco Bonelli', 'Waldir Pimenta', 'Starbeamrainbowlabs', 'lucas schneider']
date: 1610111394
title: "git-imerge, TLDR Pages"
description: "git-imerge, Perform a merge or rebase between two Git branches incrementally."
categories: "common"
---
> Conflicts between branches are tracked down to pairs of individual commits, to simplify conflict resolution.

> More information: <https://github.com/mhagger/git-imerge>.

- Start imerge-based rebase (checkout the branch to be rebased, first):

```bash
git imerge rebase branch_to_rebase_onto
```

- Start imerge-based merge (checkout the branch to merge into, first):

```bash
git imerge merge branch_to_be_merged
```

- Show ASCII diagram of in-progress merge or rebase:

```bash
git imerge diagram
```

- Continue imerge operation after resolving conflicts (`git add` the conflicted files, first):

```bash
git imerge continue --no-edit
```

- Wrap up imerge operation, after all conflicts are resolved:

```bash
git imerge finish
```

- Abort imerge operation, and return to the previous branch:

```bash
git-imerge remove && git checkout previous_branch
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[lucas schneider](mailto:casdpa@gmail.com) | rename git to Git | 2021-01-08T14:09:54 | [eef3712fc3a6](https://github.com/tldr-pages/tldr/commit/eef3712fc3a6a3774384b2e4ed934583c8349d75)
[Marco Bonelli](mailto:marco@mebeim.net) | Refactor: reword English pages' links' descriptions. | 2019-06-03T14:19:41 | [66abb98ce935](https://github.com/tldr-pages/tldr/commit/66abb98ce935c0f4516bf30c4d6da72180d5a3ab)
[Starbeamrainbowlabs](mailto:sbrl@starbeamrainbowlabs.com) | multiple pages: add homepages (#2660) | 2019-01-30T12:19:23 | [a19866e88add](https://github.com/tldr-pages/tldr/commit/a19866e88addb239484637579b17e7c6ea9b53aa)
[Waldir Pimenta](mailto:waldyrious@gmail.com) | git-imerge: add "abort" example (#1339) | 2017-04-21T11:45:54 | [df46736db743](https://github.com/tldr-pages/tldr/commit/df46736db74364eccad49f185958319f5251211f)
[Waldir Pimenta](mailto:waldyrious@gmail.com) | Create git-imerge.md (#934) | 2016-06-28T12:57:32 | [384557eb159a](https://github.com/tldr-pages/tldr/commit/384557eb159a76948849175c871ef9cdd7db08ff)

