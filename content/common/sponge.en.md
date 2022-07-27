---
author: ['Ein Verne', 'marchersimon']
date: 1618584134
title: "sponge, TLDR Pages"
description: "sponge, Soak up the input before writing the output file."
categories: "common"
---
> More information: <https://manned.org/sponge>.

- Append file content to the source file:

```bash
cat path/to/file | sponge -a path/to/file
```

- Remove all lines starting with # in a file:

```bash
grep -v '^#' path/to/file | sponge path/to/file
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | multiple pages: replace all die.net links (#5528) Most of the links were replaced by manned.org, except when there are more up-to-date [...] | 2021-04-16T16:42:14 | [dac4a710772f](https://github.com/tldr-pages/tldr/commit/dac4a710772f9adef5b9883172fb30ed2416c0eb)
[Ein Verne](mailto:einverne@gmail.com) | sponge: add page (#4117) | 2020-06-20T05:41:03 | [6e943a3808e5](https://github.com/tldr-pages/tldr/commit/6e943a3808e5a11ef7869debac7c1a994790e64e)

