---
author: ['Artiom Basenko', 'pxgamer', 'Marco Bonelli']
date: 1559328460
title: "pt"
description: "pt, Platinum Searcher."
categories: "common"
---
> A code search tool similar to `ag`.

> More information: <https://github.com/monochromegane/the_platinum_searcher>.

- Find files containing "foo" and print the files with highlighted matches:

```bash
pt foo
```

- Find files containing "foo" and display count of matches in each file:

```bash
pt -c foo
```

- Find files containing "foo" as a whole word and ignore its case:

```bash
pt -wi foo
```

- Find "foo" in files with a given extension using a regular expression:

```bash
pt -G='\.bar$' foo
```

- Find files whose contents match the regular expression, up to 2 directories deep:

```bash
pt --depth=2 -e '^ba[rz]*$'
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[pxgamer](mailto:owzie123@gmail.com) | pt: add link to homepage | 2019-05-31T20:47:40 | [cb3b7574bd22](https://github.com/tldr-pages/tldr/commit/cb3b7574bd225031bd227fbc7eb290951c63f908)
[Marco Bonelli](mailto:mb5.marcob@gmail.com) | Refactor: change "folder" to "directory" where needed. This commit fixes every instance in which the word "folder" is incorrectly used [...] | 2019-02-13T16:21:04 | [2599a6de483a](https://github.com/tldr-pages/tldr/commit/2599a6de483a70601ab17b29e0f18a5a8bdcaa12)
[Artiom Basenko](mailto:demi.log@gmail.com) | pt: add page (#2246) | 2018-08-17T12:24:45 | [4428bf586d2f](https://github.com/tldr-pages/tldr/commit/4428bf586d2fe3d0d705e23a7f62136d05e44054)

