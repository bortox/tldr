---
author: ['Philipp Weißmann', 'pxgamer']
date: 1559133670
title: "rdfind"
description: "rdfind, Find files with duplicate content and get rid of them."
categories: "common"
---
> More information: <https://rdfind.pauldreik.se>.

- Identify all duplicates in a given directory and output a summary:

```bash
rdfind -dryrun true path/to/directory
```

- Replace all duplicates with hardlinks:

```bash
rdfind -makehardlinks true path/to/directory
```

- Replace all duplicates with symlinks/soft links:

```bash
rdfind -makesymlinks true path/to/directory
```

- Delete all duplicates and do not ignore empty files:

```bash
rdfind -deleteduplicates true -ignoreempty false path/to/directory
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[pxgamer](mailto:owzie123@gmail.com) | multiple pages: update the web link descriptions | 2019-05-29T14:41:10 | [f2b1446e6247](https://github.com/tldr-pages/tldr/commit/f2b1446e6247d3e794ee6577dee0c867dfc9af26)
[pxgamer](mailto:owzie123@gmail.com) | rdfind: add link to homepage | 2019-05-29T14:41:10 | [83e0111befe5](https://github.com/tldr-pages/tldr/commit/83e0111befe517106bc32decb08548d5c61d0e33)
[Philipp Weißmann](mailto:github@philipp-weissmann.de) | rdfind: clarify usage of rdfind (#2341) | 2018-09-19T17:31:46 | [58263e404055](https://github.com/tldr-pages/tldr/commit/58263e4040554375f81a361c2b6ae7fc466785f2)
[Philipp Weißmann](mailto:github@philipp-weissmann.de) | rdfind: add page (#2337) | 2018-09-18T11:45:31 | [3bb46fd34426](https://github.com/tldr-pages/tldr/commit/3bb46fd34426a83c26aa9e77c1579085612944a4)

