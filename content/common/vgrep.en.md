---
author: ['Muhammad Falak R Wani']
date: 1661034878
title: "vgrep"
description: "vgrep, A user friendly pager for grep."
categories: "common"
---
> See also: `ugrep`, `rg`.

> More information: <https://github.com/vrothberg/vgrep>.

- Recursively search the current directory for a pattern and cache it:

```bash
vgrep search_pattern
```

- Display the contents of the cache:

```bash
vgrep
```

- Open the "4th" match from the cache in the default editor:

```bash
vgrep --show 4
```

- Display a context of "3" lines for each match in the cache:

```bash
vgrep --show=context3
```

- Display the number of matches for each directory in the tree:

```bash
vgrep --show=tree
```

- Display the number of matches for each file in the tree:

```bash
vgrep --show=files
```

- Start an interactive shell with cached matches:

```bash
vgrep --interactive
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Muhammad Falak R Wani](mailto:falakreyaz@gmail.com) | vgrep: add page (#8383) * vgrep: add page Signed-off-by: Muhammad Falak R Wani <falakreyaz@gmail.com> * vgrep: fix token syntax [...] | 2022-08-21T00:34:38 | [f6685e6cb10c](https://github.com/tldr-pages/tldr/commit/f6685e6cb10cc5783252e651c85e5adb93bc4692)

