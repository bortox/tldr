---
author: ['Mark Gross']
date: 1603906158
title: "slop, TLDR Pages"
description: "slop, Get a selection of the screen."
categories: "linux"
---
> More information: <https://github.com/naelstrof/slop>.

- Wait for the user to make a selection and output its geometry to standard output:

```bash
slop
```

- Double click, rather than click and drag, to draw a selection:

```bash
slop -D
```

- Highlight the selection rather than outlining it:

```bash
slop -l
```

- Specify the output format:

```bash
slop -f format_string
```

- Specify the selection rectangle's color:

```bash
slop -c red,green,blue,alpha
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Mark Gross](mailto:10702518+MarkusG@users.noreply.github.com) | slop: add page (#4741) | 2020-10-28T18:29:18 | [076ec67f88d4](https://github.com/tldr-pages/tldr/commit/076ec67f88d4d07134a420a6261622a3886155e3)

