---
author: ['Marco Bonelli', 'pxgamer']
date: 1559564381
title: "hg push, TLDR Pages"
description: "hg push, Push changes from the local repository to a specified destination."
categories: "common"
---
> More information: <https://www.mercurial-scm.org/doc/hg.1.html#push>.

- Push changes to the "default" remote path:

```bash
hg push
```

- Push changes to a specified remote repository:

```bash
hg push path/to/destination_repository
```

- Push a new branch if it does not exist (disabled by default):

```bash
hg push --new-branch
```

- Specify a specific revision changeset to push:

```bash
hg push --rev revision
```

- Specify a specific branch to push:

```bash
hg push --branch branch
```

- Specify a specific bookmark to push:

```bash
hg push --bookmark bookmark
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Marco Bonelli](mailto:marco@mebeim.net) | Refactor: reword English pages' links' descriptions. | 2019-06-03T14:19:41 | [66abb98ce935](https://github.com/tldr-pages/tldr/commit/66abb98ce935c0f4516bf30c4d6da72180d5a3ab)
[pxgamer](mailto:owzie123@gmail.com) | hg-push: add link to homepage | 2019-03-24T00:27:35 | [a6800ad93a8a](https://github.com/tldr-pages/tldr/commit/a6800ad93a8a134bc17921e257ace69c49864fc4)
[pxgamer](mailto:owzie123@gmail.com) | Updated --new-branch description | 2017-12-20T18:43:46 | [0836e5f00d6f](https://github.com/tldr-pages/tldr/commit/0836e5f00d6f89d651561f2af098f7e2852f33fe)
[pxgamer](mailto:owzie123@gmail.com) | hg-push: add page | 2017-12-20T13:27:24 | [d143db80c12c](https://github.com/tldr-pages/tldr/commit/d143db80c12ccfd318b53cbdb459f92c919bec70)

