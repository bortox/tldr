---
author: ['Marco Bonelli', 'pxgamer', 'David']
date: 1559564381
title: "tokei, TLDR Pages"
description: "tokei, A program that prints out statistics about code."
categories: "common"
---
> More information: <https://github.com/XAMPPRocky/tokei>.

- Get a report on the code in a directory and all subdirectories:

```bash
tokei path/to/directory
```

- Get a report for a directory excluding `.min.js` files:

```bash
tokei path/to/directory -e *.min.js
```

- Print out statistics for individual files in a directory:

```bash
tokei path/to/directory --files
```

- Get a report for all files of type Rust and Markdown:

```bash
tokei path/to/directory -t=Rust,Markdown
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Marco Bonelli](mailto:marco@mebeim.net) | Refactor: reword English pages' links' descriptions. | 2019-06-03T14:19:41 | [66abb98ce935](https://github.com/tldr-pages/tldr/commit/66abb98ce935c0f4516bf30c4d6da72180d5a3ab)
[pxgamer](mailto:owzie123@gmail.com) | tokei: add link to homepage | 2019-05-14T19:58:59 | [f99fba17a0e5](https://github.com/tldr-pages/tldr/commit/f99fba17a0e59d5355cb5889c6b198301b1a5e29)
[Marco Bonelli](mailto:mb5.marcob@gmail.com) | Refactor: change "folder" to "directory" where needed. This commit fixes every instance in which the word "folder" is incorrectly used [...] | 2019-02-13T16:21:04 | [2599a6de483a](https://github.com/tldr-pages/tldr/commit/2599a6de483a70601ab17b29e0f18a5a8bdcaa12)
[David](mailto:david.bialik@gmail.com) | tokei: add page (#2545) | 2018-12-01T19:02:56 | [0642c8456280](https://github.com/tldr-pages/tldr/commit/0642c845628073c601f98148a15f8e2ed6baf8a1)

