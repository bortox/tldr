---
author: ['git-em']
date: 1645996123
title: "rga"
description: "rga, Ripgrep wrapper with rich file type searching capabilities."
categories: "common"
---
> More information: <https://github.com/phiresky/ripgrep-all>.

- Search recursively for a pattern in all files in the current directory:

```bash
rga regular_expression
```

- List available adapters:

```bash
rga --rga-list-adapters
```

- Change which adapters to use (e.g. ffmpeg, pandoc, poppler etc.):

```bash
rga --rga-adapters=adapter1,adapter2 regular_expression
```

- Search for a pattern using the mime type instead of the file extension (slower):

```bash
rga --rga-accurate regular_expression
```

- Display detailed help:

```bash
rga --help
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[git-em](mailto:56173216+git-em@users.noreply.github.com) | rga: add page (#7818) | 2022-02-27T22:08:43 | [d213b0ec90c6](https://github.com/tldr-pages/tldr/commit/d213b0ec90c6b42da73743bb06d15173e40f98b9)

