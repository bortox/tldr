---
author: ['Hayden Schiff', 'marchersimon']
date: 1618756407
title: "cmp, TLDR Pages"
description: "cmp, Compare two files byte by byte."
categories: "common"
---
> More information: <https://www.gnu.org/software/diffutils/manual/html_node/Invoking-cmp.html>.

- Find the byte and line number of the first difference between two files:

```bash
cmp path/to/file1 path/to/file2
```

- Find the byte number and differing bytes of every difference:

```bash
cmp -l path/to/file1 path/to/file2
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[marchersimon](mailto:marchersimon@zohomail.eu) | cmp: add link | 2021-04-18T16:33:27 | [9eb75b07f3cc](https://github.com/tldr-pages/tldr/commit/9eb75b07f3cc3af985266eb4ded57ce7ac877abc)
[Hayden Schiff](mailto:oxguy3@gmail.com) | cmp: add page | 2016-02-23T02:29:35 | [eb5d016e4a4c](https://github.com/tldr-pages/tldr/commit/eb5d016e4a4cdfc6ea5cbf1ded8cce7882c5837c)

