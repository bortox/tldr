---
author: ['Marco Bonelli', 'pxgamer', 'Starbeamrainbowlabs']
date: 1559564381
title: "git gc, TLDR Pages"
description: "git gc, Optimise the local repository by cleaning unnecessary files."
categories: "common"
---
> More information: <https://git-scm.com/docs/git-gc>.

- Optimise the repository:

```bash
git gc
```

- Aggressively optimise, takes more time:

```bash
git gc --aggressive
```

- Do not prune loose objects (prunes by default):

```bash
git gc --no-prune
```

- Suppress all output:

```bash
git gc --quiet
```

- View full usage:

```bash
git gc --help
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Marco Bonelli](mailto:marco@mebeim.net) | Refactor: reword English pages' links' descriptions. | 2019-06-03T14:19:41 | [66abb98ce935](https://github.com/tldr-pages/tldr/commit/66abb98ce935c0f4516bf30c4d6da72180d5a3ab)
[Starbeamrainbowlabs](mailto:sbrl@starbeamrainbowlabs.com) | multiple pages: add homepages (#2660) | 2019-01-30T12:19:23 | [a19866e88add](https://github.com/tldr-pages/tldr/commit/a19866e88addb239484637579b17e7c6ea9b53aa)
[pxgamer](mailto:owzie123@gmail.com) | Moved help command to be the last example | 2017-12-04T09:59:30 | [4e0790e7e002](https://github.com/tldr-pages/tldr/commit/4e0790e7e00211576e5643fc6b722f621adaec29)
[pxgamer](mailto:owzie123@gmail.com) | git-gc: add page | 2017-12-03T15:37:44 | [57361e79b363](https://github.com/tldr-pages/tldr/commit/57361e79b363346f089ea33969ea9ef81db1123a)

