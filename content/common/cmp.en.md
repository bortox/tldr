---
author: ['Hayden Schiff', 'git-em', 'marchersimon']
date: 1659182702
title: "cmp"
description: "cmp, Compare two files byte by byte."
categories: "common"
---
> More information: <https://www.gnu.org/software/diffutils/manual/html_node/Invoking-cmp.html>.

- Output char and line number of the first difference between two files:

```bash
cmp path/to/file1 path/to/file2
```

- Output info of the first difference: char, line number, bytes, and values:

```bash
cmp --print-bytes path/to/file1 path/to/file2
```

- Output the byte numbers and values of every difference:

```bash
cmp --verbose path/to/file1 path/to/file2
```

- Compare files but output nothing, yield only the exit status:

```bash
cmp --quiet path/to/file1 path/to/file2
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[git-em](mailto:56173216+git-em@users.noreply.github.com) | cmp: refresh page (#7822) | 2022-07-30T14:05:02 | [1dc747127b5c](https://github.com/tldr-pages/tldr/commit/1dc747127b5c668f69fd094b752ea44fc4a73360)
[marchersimon](mailto:marchersimon@zohomail.eu) | cmp: add link | 2021-04-18T16:33:27 | [9eb75b07f3cc](https://github.com/tldr-pages/tldr/commit/9eb75b07f3cc3af985266eb4ded57ce7ac877abc)
[Hayden Schiff](mailto:oxguy3@gmail.com) | cmp: add page | 2016-02-23T02:29:35 | [eb5d016e4a4c](https://github.com/tldr-pages/tldr/commit/eb5d016e4a4cdfc6ea5cbf1ded8cce7882c5837c)

