---
author: ['Steven Pitts']
date: 1621187251
title: "dconf write"
description: "dconf write, Write a value to a dconf database path."
categories: "linux"
---
> More information: <https://developer.gnome.org/dconf>.

- Write a string to a dconf path (note the nested quotes):

```bash
dconf write /example/dconf/path "'Example Value'"
```

- Write a boolean to a dconf path:

```bash
dconf write /example/dconf/path true|false
```

- Write an integer to a dconf path:

```bash
dconf write /example/dconf/path 16
```

- Write an array to a dconf path:

```bash
dconf write /example/dconf/path "['My First Value', 'My Second Value']"
```

- Write an empty array to a dconf path:

```bash
dconf write /example/dconf/path "@as []"
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Steven Pitts](mailto:25968054+makusu2@users.noreply.github.com) | dconf, dconf-write: add page (#5967) | 2021-05-16T19:47:31 | [f82fd9c8f308](https://github.com/tldr-pages/tldr/commit/f82fd9c8f308c7eac988ff0c3e5df4968ef97914)

