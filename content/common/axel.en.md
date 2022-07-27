---
author: ['Marco Bonelli', 'Ruben Vereecken', 'DreamPiggy', 'Schneider']
date: 1559564381
title: "axel, TLDR Pages"
description: "axel, Download accelerator."
categories: "common"
---
> Supports HTTP, HTTPS, and FTP.

> More information: <https://github.com/axel-download-accelerator/axel>.

- Download a URL to a file:

```bash
axel url
```

- Download and specify filename:

```bash
axel url -o filename
```

- Download with multiple connections:

```bash
axel -n connections_num url
```

- Search for mirrors:

```bash
axel -S mirrors_num url
```

- Limit download speed (bytes per second):

```bash
axel -s speed url
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Marco Bonelli](mailto:marco@mebeim.net) | Refactor: reword English pages' links' descriptions. | 2019-06-03T14:19:41 | [66abb98ce935](https://github.com/tldr-pages/tldr/commit/66abb98ce935c0f4516bf30c4d6da72180d5a3ab)
[Schneider](mailto:lucas.schneider@sap.com) | axel.md: add homepage | 2019-04-12T14:41:22 | [5cabbf4ca5d2](https://github.com/tldr-pages/tldr/commit/5cabbf4ca5d2cf649637214821696fcfd80610de)
[Ruben Vereecken](mailto:rubenvereecken@gmail.com) | Formatted axel page | 2016-01-21T13:18:30 | [7aaf8e383e02](https://github.com/tldr-pages/tldr/commit/7aaf8e383e02d8e6aa7941c8f8df635d43004dc8)
[DreamPiggy](mailto:lizhuoli1126@126.com) | add axel axel: add | 2016-01-05T09:37:31 | [2887aaaea624](https://github.com/tldr-pages/tldr/commit/2887aaaea6249f26934735b65df607d03a36d6a3)

