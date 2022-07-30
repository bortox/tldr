---
author: ['Liu233w']
date: 1653238181
title: "bindkey"
description: "bindkey, Add keybindings to Z-Shell."
categories: "common"
---
> More information: <https://zsh.sourceforge.io/Guide/zshguide04.html>.

- Bind a hotkey to a specific command:

```bash
bindkey "^k" kill-line
```

- Bind a hotkey to a specific key sequence:

```bash
bindkey -s '^o' 'cd ..\n'
```

- View keymaps:

```bash
bindkey -l
```

- View the hotkey in a keymap:

```bash
bindkey -M main
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Liu233w](mailto:github@liu233w.com) | bindkey: add page (#8089) Co-authored-by: Muhammad Falak R Wani <falakreyaz@gmail.com> Co-authored-by: Axel Navarro <navarroaxel@gmail.com> | 2022-05-22T18:49:41 | [b9919a01fb98](https://github.com/tldr-pages/tldr/commit/b9919a01fb9899be2175c7d0cb6ada6eb0660af6)

