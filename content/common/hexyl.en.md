---
author: ['Mads Johansen']
date: 1571790112
title: "hexyl"
description: "hexyl, A simple hex viewer for the terminal. Uses colored output to distinguish different categories of bytes."
categories: "common"
---
> More information: <https://github.com/sharkdp/hexyl>.

- Print the hexadecimal representation of a file:

```bash
hexyl path/to/file
```

- Print the hexadecimal representation of the first n bytes of a file:

```bash
hexyl -n n path/to/file
```

- Print bytes 512 through 1024 of a file:

```bash
hexyl -r 512:1024 path/to/file
```

- Print 512 bytes starting at the 1024th byte:

```bash
hexyl -r 1024:+512 path/to/file
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Mads Johansen](mailto:johansen.max@gmail.com) | hexyl: add page (#3437) | 2019-10-23T02:21:52 | [5969edc90d69](https://github.com/tldr-pages/tldr/commit/5969edc90d69cb101b699fc06432f1f2afd9174e)

