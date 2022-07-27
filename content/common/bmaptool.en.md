---
author: ['Schneider', 'Marco Bonelli', 'Ruben Vereecken', '85pando', 'Lucas Gabriel Schneider']
date: 1581443623
title: "bmaptool, TLDR Pages"
description: "bmaptool, Create or copy block maps intelligently (designed to be faster than `cp` or `dd`)."
categories: "common"
---
> More information: <https://source.tizen.org/documentation/reference/bmaptool>.

- Create a blockmap from image file:

```bash
bmaptool create -o blockmap.bmap source.img
```

- Copy an image file into sdb:

```bash
bmaptool copy --bmap blockmap.bmap source.img /dev/sdb
```

- Copy a compressed image file into sdb:

```bash
bmaptool copy --bmap blockmap.bmap source.img.gz /dev/sdb
```

- Copy an image file into sdb without using a blockmap:

```bash
bmaptool copy --nobmap source.img /dev/sdb
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Lucas Gabriel Schneider](mailto:casdpa@gmail.com) | multiple pages: rephrase without adjectives (#3846) Co-authored-by: Starbeamrainbowlabs <sbrl@starbeamrainbowlabs.com> Co-authored-by: [...] | 2020-02-11T18:53:43 | [8211b80c1722](https://github.com/tldr-pages/tldr/commit/8211b80c17221eed9f3f8530eafed3cc3fbd03f1)
[Marco Bonelli](mailto:marco@mebeim.net) | Refactor: reword English pages' links' descriptions. | 2019-06-03T14:19:41 | [66abb98ce935](https://github.com/tldr-pages/tldr/commit/66abb98ce935c0f4516bf30c4d6da72180d5a3ab)
[Schneider](mailto:lucas.schneider@sap.com) | bmaptool.md add homepage | 2019-04-11T09:49:15 | [82090f62cb64](https://github.com/tldr-pages/tldr/commit/82090f62cb6422a3cf97ba9b0152fb7950cba46b)
[Ruben Vereecken](mailto:rubenvereecken@gmail.com) | Reformatted pages once more | 2016-01-13T12:04:46 | [967633411984](https://github.com/tldr-pages/tldr/commit/9676334119847078e5e05fec393a3fe36991dbc2)
[85pando](mailto:85pando@googlemail.com) | Add page for bmaptool. | 2016-01-08T10:06:36 | [e040817ad590](https://github.com/tldr-pages/tldr/commit/e040817ad5908e4260cecd501c6cac779347a700)

