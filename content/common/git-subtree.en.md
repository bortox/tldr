---
author: ['Quinn Vissak', 'Ein Verne', 'Starbeamrainbowlabs', 'lucas schneider']
date: 1610111394
title: "git subtree, TLDR Pages"
description: "git subtree, Tool to manage project dependencies as subprojects."
categories: "common"
---
> More information: <https://manpages.debian.org/testing/git-man/git-subtree.1.en.html>.

- Add a Git repository as a subtree:

```bash
git subtree add --prefix=path/to/directory/ --squash repository_url branch_name
```

- Update subtree repository to its latest commit:

```bash
git subtree pull --prefix=path/to/directory/ repository_url branch_name
```

- Merge recent changes up to the latest subtree commit into the subtree:

```bash
git subtree merge --prefix=path/to/directory/ --squash repository_url branch_name
```

- Push commits to a subtree repository:

```bash
git subtree push --prefix=path/to/directory/ repository_url branch_name
```

- Extract a new project history from the history of a subtree:

```bash
git subtree split --prefix=path/to/directory/ repository_url -b branch_name
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[lucas schneider](mailto:casdpa@gmail.com) | rename git to Git | 2021-01-08T14:09:54 | [eef3712fc3a6](https://github.com/tldr-pages/tldr/commit/eef3712fc3a6a3774384b2e4ed934583c8349d75)
[Starbeamrainbowlabs](mailto:sbrl@starbeamrainbowlabs.com) | git-*: use inclusive language (#4533) * git subtree: make language inclusive * git revert: make language inclusive * git rev-list: [...] | 2020-10-19T20:26:01 | [948bcac65d48](https://github.com/tldr-pages/tldr/commit/948bcac65d48179728f823176fb4f4f7d58c201d)
[Starbeamrainbowlabs](mailto:sbrl@starbeamrainbowlabs.com) | Revert "(chore) replace master/slave with inclusive language (#4459)" (#4532) This reverts commit 44975352462448049b79d323f67337620a4a1740. | 2020-10-06T18:48:57 | [be3998d964be](https://github.com/tldr-pages/tldr/commit/be3998d964be9b7de60ed7b80f6c89264948f710)
[Quinn Vissak](mailto:qvissak@yahoo.com) | (chore) replace master/slave with inclusive language (#4459) | 2020-10-06T16:24:10 | [449753524624](https://github.com/tldr-pages/tldr/commit/44975352462448049b79d323f67337620a4a1740)
[Ein Verne](mailto:einverne@gmail.com) | git-subtree: add page (#4012) Co-authored-by: Zlatan Vasović <zlatanvasovic@gmail.com> Co-authored-by: Andrik Albuquerque [...] | 2020-05-03T14:55:53 | [ee05f3f691f3](https://github.com/tldr-pages/tldr/commit/ee05f3f691f3422e02a8a10341f15a43464fdedd)

