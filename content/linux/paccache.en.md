---
author: ['Paul Reiter', 'Schneider', 'Emily Grace Seville']
date: 1647882468
title: "paccache, TLDR Pages"
description: "paccache, A pacman cache cleaning utility."
categories: "linux"
---
> More information: <https://manned.org/paccache>.

- Remove all but the 3 most recent package versions from the pacman cache:

```bash
paccache -r
```

- Set the number of package versions to keep:

```bash
paccache -rk num_versions
```

- Perform a dry-run and show the number of candidate packages for deletion:

```bash
paccache -d
```

- Move candidate packages to a directory instead of deleting them:

```bash
paccache -m path/to/directory
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Emily Grace Seville](mailto:emilyseville7cf@gmail.com) | linux/*: add more information link (#7848) | 2022-03-21T18:07:48 | [4659bcb243ac](https://github.com/tldr-pages/tldr/commit/4659bcb243ac572c9e0c95117097801f1e62bda4)
[Schneider](mailto:lucas.schneider@sap.com) | paccache: remove adjectives | 2020-02-20T18:00:28 | [4033082e56c8](https://github.com/tldr-pages/tldr/commit/4033082e56c834738f38467a5a33d46075164cc8)
[Paul Reiter](mailto:reiter.paul@gmail.com) | paccache: add page (#2788) | 2019-02-22T22:25:39 | [ed9bfb1f6e83](https://github.com/tldr-pages/tldr/commit/ed9bfb1f6e8352f70f794403a186a7f05e0c432b)

