---
author: ['Kevin Zheng', 'Waldir Pimenta', 'Diki Ananta']
date: 1609242414
title: "rofi"
description: "rofi, An application launcher and window switcher."
categories: "linux"
---
> More information: <https://github.com/davatorium/rofi>.

- Show the list of apps:

```bash
rofi -show drun
```

- Show the list of all commands:

```bash
rofi -show run
```

- Switch between windows:

```bash
rofi -show window
```

- Pipe a list of items to stdin and print the selected item to stdout:

```bash
printf "Choice1\nChoice2\nChoice3" | rofi -dmenu
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Waldir Pimenta](mailto:waldyrious@gmail.com) | Fix syntax of "More information" links (#5050) | 2020-12-29T12:46:54 | [5430739f1dc4](https://github.com/tldr-pages/tldr/commit/5430739f1dc4d29b85b838e594550ba6c133001f)
[Kevin Zheng](mailto:coffeevector@gmail.com) | rofi: added dmenu option, added homepage (#3233) | 2019-08-29T10:26:31 | [2a6189a5bfea](https://github.com/tldr-pages/tldr/commit/2a6189a5bfeab17bf58cb2d40f9ab58829e12053)
[Diki Ananta](mailto:diki1aap@gmail.com) | rofi: add page | 2018-01-15T04:42:58 | [4ceb0fdee872](https://github.com/tldr-pages/tldr/commit/4ceb0fdee87287e448e3684a3c8da31412dc5dbe)

