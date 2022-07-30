---
author: ['Waldir Pimenta', 'Starbeamrainbowlabs', 'Marco Bonelli']
date: 1559564381
title: "git bisect"
description: "git bisect, Use binary search to find the commit that introduced a bug."
categories: "common"
---
> Git automatically jumps back and forth in the commit graph to progressively narrow down the faulty commit.

> More information: <https://git-scm.com/docs/git-bisect>.

- Start a bisect session on a commit range bounded by a known buggy commit, and a known clean (typically older) one:

```bash
git bisect start bad_commit good_commit
```

- For each commit that `git bisect` selects, mark it as "bad" or "good" after testing it for the issue:

```bash
git bisect good|bad
```

- After `git bisect` pinpoints the faulty commit, end the bisect session and return to the previous branch:

```bash
git bisect reset
```

- Skip a commit during a bisect (e.g. one that fails the tests due to a different issue):

```bash
git bisect skip
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Marco Bonelli](mailto:marco@mebeim.net) | Refactor: reword English pages' links' descriptions. | 2019-06-03T14:19:41 | [66abb98ce935](https://github.com/tldr-pages/tldr/commit/66abb98ce935c0f4516bf30c4d6da72180d5a3ab)
[Starbeamrainbowlabs](mailto:sbrl@starbeamrainbowlabs.com) | multiple pages: add homepages (#2660) | 2019-01-30T12:19:23 | [a19866e88add](https://github.com/tldr-pages/tldr/commit/a19866e88addb239484637579b17e7c6ea9b53aa)
[Waldir Pimenta](mailto:waldyrious@gmail.com) | git-bisect: add page (#1227) | 2017-01-07T02:43:53 | [57c294081ea0](https://github.com/tldr-pages/tldr/commit/57c294081ea06e2833ca8e957c560e5e05693624)

