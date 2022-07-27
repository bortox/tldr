---
author: ['Daniel']
date: 1633533899
title: "kitty, TLDR Pages"
description: "kitty, A fast, feature-rich, GPU based terminal emulator."
categories: "common"
---
> More information: <https://sw.kovidgoyal.net/kitty/>.

- Open a new terminal:

```bash
kitty
```

- Open a terminal with the specified title for the window:

```bash
kitty --title "title"
```

- Start the theme-chooser builtin:

```bash
kitty +kitten themes
```

- Display an image in the terminal:

```bash
kitty +kitten icat path/to/image
```

- Copy the contents of stdin to the clipboard:

```bash
echo example | kitty +kitten clipboard
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Daniel](mailto:33197631+dadav@users.noreply.github.com) | kitty: add page (#6676) | 2021-10-06T17:24:59 | [da5e72604ba3](https://github.com/tldr-pages/tldr/commit/da5e72604ba3ff0e0049ebb2c4a00e44f5edf108)

