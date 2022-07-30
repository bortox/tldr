---
author: ['Spark', 'Starbeamrainbowlabs', 'Marco Bonelli']
date: 1559564381
title: "git worktree"
description: "git worktree, Manage multiple working trees attached to the same repository."
categories: "common"
---
> More information: <https://git-scm.com/docs/git-worktree>.

- Create a new directory with the specified branch checked out into it:

```bash
git worktree add path/to/directory branch
```

- Create a new directory with a new branch checked out into it:

```bash
git worktree add path/to/directory -b new_branch
```

- List all the working directories attached to this repository:

```bash
git worktree list
```

- Remove a worktree (after deleting worktree directory):

```bash
git worktree prune
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Marco Bonelli](mailto:marco@mebeim.net) | Refactor: reword English pages' links' descriptions. | 2019-06-03T14:19:41 | [66abb98ce935](https://github.com/tldr-pages/tldr/commit/66abb98ce935c0f4516bf30c4d6da72180d5a3ab)
[Marco Bonelli](mailto:mb5.marcob@gmail.com) | Refactor: change "folder" to "directory" where needed. This commit fixes every instance in which the word "folder" is incorrectly used [...] | 2019-02-13T16:21:04 | [2599a6de483a](https://github.com/tldr-pages/tldr/commit/2599a6de483a70601ab17b29e0f18a5a8bdcaa12)
[Starbeamrainbowlabs](mailto:sbrl@starbeamrainbowlabs.com) | multiple pages: add homepages (#2660) | 2019-01-30T12:19:23 | [a19866e88add](https://github.com/tldr-pages/tldr/commit/a19866e88addb239484637579b17e7c6ea9b53aa)
[Spark](mailto:stevegrandpre@gmail.com) | git-worktree.md: add page (#1232) | 2017-01-09T17:32:05 | [6860a404d9f9](https://github.com/tldr-pages/tldr/commit/6860a404d9f9c5b675c36a43a640946ff978225f)

