---
author: ['Waldir Pimenta', 'Seth Woodworth', 'Marco Bonelli', 'Ruben Vereecken', 'Starbeamrainbowlabs']
date: 1559564381
title: "git fetch, TLDR Pages"
description: "git fetch, Download objects and refs from a remote repository."
categories: "common"
---
> More information: <https://git-scm.com/docs/git-fetch>.

- Fetch the latest changes from the default remote upstream repository (if set):

```bash
git fetch
```

- Fetch new branches from a specific remote upstream repository:

```bash
git fetch remote_name
```

- Fetch the latest changes from all remote upstream repositories:

```bash
git fetch --all
```

- Also fetch tags from the remote upstream repository:

```bash
git fetch --tags
```

- Delete local references to remote branches that have been deleted upstream:

```bash
git fetch --prune
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Marco Bonelli](mailto:marco@mebeim.net) | Refactor: reword English pages' links' descriptions. | 2019-06-03T14:19:41 | [66abb98ce935](https://github.com/tldr-pages/tldr/commit/66abb98ce935c0f4516bf30c4d6da72180d5a3ab)
[Starbeamrainbowlabs](mailto:sbrl@starbeamrainbowlabs.com) | multiple pages: add homepages (#2660) | 2019-01-30T12:19:23 | [a19866e88add](https://github.com/tldr-pages/tldr/commit/a19866e88addb239484637579b17e7c6ea9b53aa)
[Waldir Pimenta](mailto:waldyrious@gmail.com) | git-fetch: --prune doesn't delete local branches (#1237) `git fetch --prune` deletes the local *references* to upstream branches (i.e. [...] | 2017-01-15T11:49:13 | [5582e23e8ae7](https://github.com/tldr-pages/tldr/commit/5582e23e8ae7e66e98de8e6f228fd44822413fe1)
[Waldir Pimenta](mailto:waldyrious@gmail.com) | git-fetch: add --prune and bare example (#1189) | 2016-12-02T14:19:05 | [d71904864d9a](https://github.com/tldr-pages/tldr/commit/d71904864d9a3e2686b755b284153ca65e67c659)
[Waldir Pimenta](mailto:waldyrious@gmail.com) | git-tag, git-fetch: add example for fetching tags (#1128) | 2016-10-27T06:55:22 | [173d3533755c](https://github.com/tldr-pages/tldr/commit/173d3533755c1f19f4bb2903eb1d047199d2d623)
[Ruben Vereecken](mailto:rubenvereecken@gmail.com) | Formatted git pages | 2016-01-21T13:08:45 | [d72dea793175](https://github.com/tldr-pages/tldr/commit/d72dea793175ac3b51c4e5c482403fddf8011737)
[Seth Woodworth](mailto:seth.ww@thelevelup.com) | adds better default option for git-fetch | 2015-12-30T19:54:58 | [15edb80ff380](https://github.com/tldr-pages/tldr/commit/15edb80ff380ea231ee9ffe4192a49c03ac588e6)
[Seth Woodworth](mailto:seth.ww@thelevelup.com) | Adds documentation for git rebase and git fetch | 2015-12-30T19:54:58 | [1fa146ee3051](https://github.com/tldr-pages/tldr/commit/1fa146ee3051cc2dd2418a78e80bd8d2b8201baf)

