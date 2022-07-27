---
author: ['L Day', 'pxgamer', 'marchersimon']
date: 1620637392
title: "nvim, TLDR Pages"
description: "nvim, Neovim, a programmer's text editor based on Vim, provides several modes for different kinds of text manipulation."
categories: "common"
---
> Pressing `i` enters edit mode. `<Esc>` goes back to normal mode, which doesn't allow regular text insertion.

> More information: <https://neovim.io>.

- Open a file:

```bash
nvim file
```

- Enter text editing mode (insert mode):

```bash
<Esc>i
```

- Copy ("yank") or cut ("delete") the current line (paste it with `P`):

```bash
<Esc>yy|dd
```

- Undo the last operation:

```bash
<Esc>u
```

- Search for a pattern in the file (press `n`/`N` to go to next/previous match):

```bash
<Esc>/search_pattern<Enter>
```

- Perform a regular expression substitution in the whole file:

```bash
<Esc>:%s/regular_expression/replacement/g<Enter>
```

- Save (write) the file, and quit:

```bash
<Esc>:wq<Enter>
```

- Quit without saving:

```bash
<Esc>:q!<Enter>
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | multiple pages: normalize `regular expression` instead of `regex`, `regexp` or `pattern` (#5830) | 2021-05-10T11:03:12 | [10728f1ab485](https://github.com/tldr-pages/tldr/commit/10728f1ab485957d66af3940a030b0fb77611fc0)
[pxgamer](mailto:owzie123@gmail.com) | nvim: add link to homepage | 2019-06-04T21:29:40 | [210d67975475](https://github.com/tldr-pages/tldr/commit/210d67975475fd210668bbdffb71fb66cd913d47)
[L Day](mailto:daylightbrightledlight@users.noreply.github.com) | nvim: add page (#2264) | 2018-08-28T14:21:43 | [39bb938c0be9](https://github.com/tldr-pages/tldr/commit/39bb938c0be990733dba63bf3781122232f9ec34)

