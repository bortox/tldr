---
author: ['alefir', 'Waldir Pimenta', 'Starbeamrainbowlabs', 'Marco Bonelli']
date: 1559901729
title: "git cherry-pick"
description: "git cherry-pick, Apply the changes introduced by existing commits to the current branch."
categories: "common"
---
> To apply changes to another branch, first use `git checkout` to switch to the desired branch.

> More information: <https://git-scm.com/docs/git-cherry-pick>.

- Apply a commit to the current branch:

```bash
git cherry-pick commit
```

- Apply a range of commits to the current branch (see also `git rebase --onto`):

```bash
git cherry-pick start_commit~..end_commit
```

- Apply multiple (non-sequential) commits to the current branch:

```bash
git cherry-pick commit_1 commit_2
```

- Add the changes of a commit to the working directory, without creating a commit:

```bash
git cherry-pick -n commit
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Waldir Pimenta](mailto:waldyrious@gmail.com) | git-cherry-pick: add example for -n option (#3084) | 2019-06-07T12:02:09 | [67e7be965056](https://github.com/tldr-pages/tldr/commit/67e7be965056f6d2eb339bf076bf8955be29a507)
[Marco Bonelli](mailto:marco@mebeim.net) | Refactor: reword English pages' links' descriptions. | 2019-06-03T14:19:41 | [66abb98ce935](https://github.com/tldr-pages/tldr/commit/66abb98ce935c0f4516bf30c4d6da72180d5a3ab)
[Starbeamrainbowlabs](mailto:sbrl@starbeamrainbowlabs.com) | multiple pages: add homepages (#2660) | 2019-01-30T12:19:23 | [a19866e88add](https://github.com/tldr-pages/tldr/commit/a19866e88addb239484637579b17e7c6ea9b53aa)
[Waldir Pimenta](mailto:waldyrious@gmail.com) | git-cherry-pick: add examples to pick more commits (#1198) | 2016-12-15T16:25:23 | [71a329d775e6](https://github.com/tldr-pages/tldr/commit/71a329d775e66fc7c48bf269903a64572106a8ee)
[alefir](mailto:bob1nilly@gmail.com) | git-cherry-pick: add page (#1196) | 2016-12-15T10:59:11 | [34c8b016ad8f](https://github.com/tldr-pages/tldr/commit/34c8b016ad8f5c7a4662a442f4018058083aafb7)

