---
author: ['Marco Bonelli', 'Agniva De Sarker', 'pxgamer']
date: 1559564381
title: "hg pull, TLDR Pages"
description: "hg pull, Pull changes from a specified repository to the local repository."
categories: "common"
---
> More information: <https://www.mercurial-scm.org/doc/hg.1.html#pull>.

- Pull from the "default" source path:

```bash
hg pull
```

- Pull from a specified source repository:

```bash
hg pull path/to/source_repository
```

- Update the local repository to the head of the remote:

```bash
hg pull --update
```

- Pull changes even when the remote repository is unrelated:

```bash
hg pull --force
```

- Specify a specific revision changeset to pull up to:

```bash
hg pull --rev revision
```

- Specify a specific branch to pull:

```bash
hg pull --branch branch
```

- Specify a specific bookmark to pull:

```bash
hg pull --bookmark bookmark
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Marco Bonelli](mailto:marco@mebeim.net) | Refactor: reword English pages' links' descriptions. | 2019-06-03T14:19:41 | [66abb98ce935](https://github.com/tldr-pages/tldr/commit/66abb98ce935c0f4516bf30c4d6da72180d5a3ab)
[pxgamer](mailto:owzie123@gmail.com) | hg-pull: add link to homepage | 2019-03-24T00:27:35 | [56f6707ac49a](https://github.com/tldr-pages/tldr/commit/56f6707ac49a8180dde6434b2f80009068f6d8c7)
[Agniva De Sarker](mailto:agnivade@yahoo.co.in) | hg-pull: minor changes - using a single word joined by underscore - changing from backtick to double quotes | 2017-12-20T04:19:04 | [4f851987d121](https://github.com/tldr-pages/tldr/commit/4f851987d121cf0103180afdda29ebd2cd1b54ed)
[pxgamer](mailto:owzie123@gmail.com) | Correct description | 2017-12-19T17:35:07 | [30594060a454](https://github.com/tldr-pages/tldr/commit/30594060a45423dda43314eb9e1847fdc4bbab18)
[pxgamer](mailto:owzie123@gmail.com) | Added pulling from a specific source | 2017-12-19T17:24:27 | [92d37bd30593](https://github.com/tldr-pages/tldr/commit/92d37bd305933c1828deb3e05a9e1981e0bfd8eb)
[pxgamer](mailto:owzie123@gmail.com) | hg-pull: add page | 2017-12-19T17:22:33 | [e4e29b42bb88](https://github.com/tldr-pages/tldr/commit/e4e29b42bb88965e89e061589cd9c3fc598ae64a)

