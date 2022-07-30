---
author: ['pxgamer', 'Frank LENORMAND', 'Seth Falco']
date: 1629050349
title: "kak"
description: "kak, Kakoune is a mode-based code editor implementing the 'multiple selections' paradigm."
categories: "common"
---
> Data can be selected and simultaneously edited in different locations, using multiple selections; users can also connect to the same session for collaborative editing.

> More information: <https://kakoune.org>.

- Open a file and enter normal mode, to execute commands:

```bash
kak path/to/file
```

- Enter insert mode from normal mode, to write text into the file:

```bash
i
```

- Escape insert mode, to go back to normal mode:

```bash
<Escape>
```

- Replace all instances of "foo" in the current file with "bar":

```bash
%sfoo<Enter>cbar<Escape>
```

- Unselect all secondary selections, and keep only the main one:

```bash
<Space>
```

- Search for numbers and select the first two:

```bash
/\d+<Enter>N
```

- Insert the contents of a file:

```bash
!cat path/to/file<Enter>
```

- Save the current file:

```bash
:w<Enter>
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Seth Falco](mailto:seth@falco.fun) | *: fix errors reported by languagetool (#6069) | 2021-08-15T19:59:09 | [3e4c519004a4](https://github.com/tldr-pages/tldr/commit/3e4c519004a471c861cdc609fd7239ee3355671c)
[pxgamer](mailto:owzie123@gmail.com) | kak: add link to homepage | 2019-06-06T04:42:48 | [9d0892142788](https://github.com/tldr-pages/tldr/commit/9d0892142788d50af0d3a6afdb1a4049fb586c64)
[Frank LENORMAND](mailto:lenormf@gmail.com) | kak: add page | 2018-02-23T13:26:27 | [8363356c7b1a](https://github.com/tldr-pages/tldr/commit/8363356c7b1a46367b53269a1d2188c1d88256f3)

