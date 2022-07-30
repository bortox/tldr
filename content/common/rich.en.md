---
author: ['Niklas']
date: 1650995385
title: "rich"
description: "rich, Rich CLI is a toolbox for fancy output in the terminal."
categories: "common"
---
> More information: <https://github.com/Textualize/rich-cli>.

- Display a file with syntax highlighting:

```bash
rich path/to/file.py
```

- Add line numbers, and indentation guides:

```bash
rich path/to/file.py --line-number --guides
```

- Apply a theme:

```bash
rich path/to/file.py --theme monokai
```

- Display a file in an interactive pager:

```bash
rich path/to/file.py --pager
```

- Display contents from a URL:

```bash
rich https://raw.githubusercontent.com/Textualize/rich-cli/main/README.md --markdown --pager
```

- Export a file as HTML:

```bash
rich path/to/file.md --export-html path/to/file.html
```

- Display text with formatting tags, custom alignment, and line width:

```bash
rich --print "Hello [green on black]Stylized[/green on black] [bold]World[/bold]" --left|center|right --width 10
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Niklas](mailto:niklas.sm+github@gmail.com) | rich: add page (#8044) * Create rich * Update and rename rich to rich.md * Update rich.md * Update rich.md * Update rich.md * Update [...] | 2022-04-26T19:49:45 | [46e065db13fd](https://github.com/tldr-pages/tldr/commit/46e065db13fda7663622056de0744dde63ce5604)

