---
author: ['Alex Larsen', 'Waldir Pimenta', 'pxgamer']
date: 1559328460
title: "psgrep"
description: "psgrep, Search running processes with `grep`."
categories: "common"
---
> More information: <https://jvz.github.io/psgrep>.

- Find process lines containing a specific string:

```bash
psgrep process_name
```

- Find process lines containing a specific string, excluding headers:

```bash
psgrep -n process_name
```

- Search using a simplified format (PID, user, command):

```bash
psgrep -s process_name
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[pxgamer](mailto:owzie123@gmail.com) | psgrep: add link to homepage | 2019-05-31T20:47:40 | [91bb5f605304](https://github.com/tldr-pages/tldr/commit/91bb5f605304417ebd0e4dbcc6514582c5659711)
[Waldir Pimenta](mailto:waldyrious@gmail.com) | psgrep: various tweaks (#3013) | 2019-05-12T16:30:55 | [86446e1bb220](https://github.com/tldr-pages/tldr/commit/86446e1bb2200b7fa7960f2d57bc641d03e84c94)
[Alex Larsen](mailto:alarsen0112@gmail.com) | Add page: psgrep (#2609) | 2018-11-24T13:37:30 | [6f9d6a976efe](https://github.com/tldr-pages/tldr/commit/6f9d6a976efe01045c8977e526e42ce097313742)

