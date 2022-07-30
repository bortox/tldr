---
author: ['Seth Falco']
date: 1653620507
title: "xmodmap"
description: "xmodmap, Utility for modifying keymaps and pointer button mappings in X."
categories: "linux"
---
> More information: <https://manned.org/xmodmap>.

- Swap left-click and right-click on the pointer:

```bash
xmodmap -e 'pointer = 3 2 1'
```

- Reassign a key on the keyboard to another key:

```bash
xmodmap -e 'keycode keycode = keyname
```

- Disable a key on the keyboard:

```bash
xmodmap -e 'keycode keycode ='
```

- Execute all xmodmap expressions in the specified file:

```bash
xmodmap path/to/file
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Seth Falco](mailto:seth@falco.fun) | xmodmap: add page (#8106) | 2022-05-27T05:01:47 | [96b5eed73bf9](https://github.com/tldr-pages/tldr/commit/96b5eed73bf9b1d81336774c238bbf7ecf3ee3a5)

