---
author: ['Starbeamrainbowlabs', 'Marco Bonelli']
date: 1559564381
title: "git am"
description: "git am, Apply patch files. Useful when receiving commits via email."
categories: "common"
---
> See also `git format-patch`, which can generate patch files.

> More information: <https://git-scm.com/docs/git-am>.

- Apply a patch file:

```bash
git am path/to/file.patch
```

- Abort the process of applying a patch file:

```bash
git am --abort
```

- Apply as much of a patch file as possible, saving failed hunks to reject files:

```bash
git am --reject path/to/file.patch
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Marco Bonelli](mailto:marco@mebeim.net) | Refactor: reword English pages' links' descriptions. | 2019-06-03T14:19:41 | [66abb98ce935](https://github.com/tldr-pages/tldr/commit/66abb98ce935c0f4516bf30c4d6da72180d5a3ab)
[Starbeamrainbowlabs](mailto:sbrl@starbeamrainbowlabs.com) | multiple pages: add homepages (#2660) | 2019-01-30T12:19:23 | [a19866e88add](https://github.com/tldr-pages/tldr/commit/a19866e88addb239484637579b17e7c6ea9b53aa)
[Starbeamrainbowlabs](mailto:sbrl@starbeamrainbowlabs.com) | git am: add page (#2352) | 2018-09-25T08:47:56 | [44d8dac07486](https://github.com/tldr-pages/tldr/commit/44d8dac074865ca787632165470054793898fb46)

