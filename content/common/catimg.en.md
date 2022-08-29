---
author: ['Cairn']
date: 1661728681
title: "catimg"
description: "catimg, Image printing in the terminal."
categories: "common"
---
> See also: `pixterm`, `chafa`.

> More information: <https://github.com/posva/catimg>.

- Print a JPEG, PNG, or GIF to the terminal:

```bash
catimg path/to/file
```

- Double the [r]esolution of an image:

```bash
catimg -r 2 path/to/file
```

- Disable 24-bit color for better [t]erminal support:

```bash
catimg -t path/to/file
```

- Specify a custom [w]idth or [H]eight:

```bash
catimg -w|-H 40 path/to/file
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Cairn](mailto:cairn@pm.me) | catimg: add page (#8412) * catimg: add page * Switch "path/to/input" with "path/to/file" * Remove "and" from see also section * [...] | 2022-08-29T01:18:01 | [9d82ca5bb35e](https://github.com/tldr-pages/tldr/commit/9d82ca5bb35e87fc8351c0ed797a0a8610aaf89c)

