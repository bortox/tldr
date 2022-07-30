---
author: ['Valentin Vetter', 'Axel Navarro', 'Starbeamrainbowlabs', 'Quinn Vissak', 'marchersimon']
date: 1645706297
title: "git rev-list"
description: "git rev-list, List revisions (commits) in reverse chronological order."
categories: "common"
---
> More information: <https://git-scm.com/docs/git-rev-list>.

- List all commits on the current branch:

```bash
git rev-list HEAD
```

- Print the latest commit that changed (add/edit/remove) a specific file on the current branch:

```bash
git rev-list -n 1 HEAD -- path/to/file
```

- List commits more recent than a specific date, on a specific branch:

```bash
git rev-list --since='2019-12-01 00:00:00' branch_name
```

- List all merge commits on a specific commit:

```bash
git rev-list --merges commit
```

- Print the number of commits since a specific tag:

```bash
git rev-list tag_name..HEAD --count
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Axel Navarro](mailto:navarroaxel@gmail.com) | git-rev-list: add -n example (#7763) | 2022-02-24T13:38:17 | [18642d59ebf0](https://github.com/tldr-pages/tldr/commit/18642d59ebf0f91667178fc85dfd59e484cb4774)
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | git rev-list: add --count example (#6459) | 2021-09-03T21:12:35 | [585954e9d0f8](https://github.com/tldr-pages/tldr/commit/585954e9d0f85d003177512123f23997e11e55ed)
[Starbeamrainbowlabs](mailto:sbrl@starbeamrainbowlabs.com) | git-*: use inclusive language (#4533) * git subtree: make language inclusive * git revert: make language inclusive * git rev-list: [...] | 2020-10-19T20:26:01 | [948bcac65d48](https://github.com/tldr-pages/tldr/commit/948bcac65d48179728f823176fb4f4f7d58c201d)
[Starbeamrainbowlabs](mailto:sbrl@starbeamrainbowlabs.com) | Revert "(chore) replace master/slave with inclusive language (#4459)" (#4532) This reverts commit 44975352462448049b79d323f67337620a4a1740. | 2020-10-06T18:48:57 | [be3998d964be](https://github.com/tldr-pages/tldr/commit/be3998d964be9b7de60ed7b80f6c89264948f710)
[Quinn Vissak](mailto:qvissak@yahoo.com) | (chore) replace master/slave with inclusive language (#4459) | 2020-10-06T16:24:10 | [449753524624](https://github.com/tldr-pages/tldr/commit/44975352462448049b79d323f67337620a4a1740)
[Valentin Vetter](mailto:BeLi4L@users.noreply.github.com) | git-ls-tree, git-rev-list, git-rev-parse: add pages (#3644) | 2019-12-17T21:31:17 | [a1a3faecb846](https://github.com/tldr-pages/tldr/commit/a1a3faecb846d3beb25615475818b4f5beafeb32)

